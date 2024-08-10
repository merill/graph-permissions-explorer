# OnlineMeetingArtifact.Read.All

> Allows the app to read online meeting artifacts on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /me/onlineMeetings/{meetingId}/attendanceReports](https://docs.microsoft.com/graph/api/meetingattendancereport-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onlineMeetings/{meetingId}/attendanceReports/{reportId}](https://docs.microsoft.com/graph/api/meetingattendancereport-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onlineMeetings/{meetingId}/attendanceReports/{reportId}/attendanceRecords](https://docs.microsoft.com/graph/api/attendancerecord-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{userId}/onlineMeetings/{meetingId}/attendanceReports](https://docs.microsoft.com/graph/api/meetingattendancereport-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{userId}/onlineMeetings/{meetingId}/attendanceReports/{reportId}](https://docs.microsoft.com/graph/api/meetingattendancereport-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{userId}/onlineMeetings/{meetingId}/attendanceReports/{reportId}/attendanceRecords](https://docs.microsoft.com/graph/api/attendancerecord-list?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|110e5abb-a10c-4b59-8b55-9b4daa4ef743|
|**Consent Type**|User|
|**Display String**|Read user's online meeting artifacts|
|**Description**|Allows the app to read online meeting artifacts on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|df01ed3b-eb61-4eca-9965-6b3d789751b2|
|**Display String**|Read online meeting artifacts|
|**Description**|Allows the app to read online meeting artifacts in your organization, without a signed-in user.|
## Resources
### [attendanceRecord ](https://docs.microsoft.com/graph/api/resources/attendancerecord?view=graph-rest-1.0&tabs=http)
| Property            | Type    | Description|
|:--------------------|:--------|:-----------|
| attendanceIntervals | attendanceInterval collection | List of time periods between joining and leaving a meeting. |
| emailAddress | String | Email address of the user associated with this attendance record. |
| identity | identity | Identity of the user associated with this attendance record. |
| role | String | Role of the attendee. Possible values are: `None`, `Attendee`, `Presenter`, and `Organizer`.  |
| totalAttendanceInSeconds | Int32 | Total duration of the attendances in seconds. |
### [meetingAttendanceReport ](https://docs.microsoft.com/graph/api/resources/meetingattendancereport?view=graph-rest-1.0&tabs=http)
| Property              | Type                                               | Description                     |
|:----------------------|:---------------------------------------------------|:--------------------------------|
| id                    | String   | Unique identifier for the attendance report. Read-only. |
| meetingEndDateTime    | DateTimeOffset | UTC time when the meeting ended. Read-only.   |
| meetingStartDateTime  | DateTimeOffset | UTC time when the meeting started. Read-only.   |
| totalParticipantCount | Int32 | Total number of participants. Read-only.  |
### [onlineMeeting ](https://docs.microsoft.com/graph/api/resources/onlinemeeting?view=graph-rest-1.0&tabs=http)
| Property   | Type  | Description  |
| :-------------------- | :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------- |
| allowAttendeeToEnableCamera     | Boolean                       | Indicates whether attendees can turn on their camera. Inherited from onlineMeetingBase.                         |
| allowAttendeeToEnableMic     | Boolean                       | Indicates whether attendees can turn on their microphone. Inherited from onlineMeetingBase.                         |
| allowedPresenters     | onlineMeetingPresenters                       | Specifies who can be a presenter in a meeting. Possible values are listed in the following table. Inherited from onlineMeetingBase.                         |
| allowMeetingChat      | meetingChatMode | Specifies the mode of meeting chat. Inherited from onlineMeetingBase. |
| allowParticipantsToChangeName | Boolean | Specifies if participants are allowed to rename themselves in an instance of the meeting. Inherited from onlineMeetingBase. |
| allowTeamworkReactions | Boolean | Indicates whether Teams reactions are enabled for the meeting. Inherited from onlineMeetingBase. |
| audioConferencing     | audioConferencing     | The phone access (dial-in) information for an online meeting. Read-only. Inherited from onlineMeetingBase.                                                  |
| chatInfo              | chatInfo                       | The chat information associated with this online meeting. Inherited from onlineMeetingBase.                                                                 |
| creationDateTime      | DateTime                                      | The meeting creation time in UTC. Read-only.                                                                               |
| endDateTime           | DateTime                                      | The meeting end time in UTC. Required when you create an online meeting.                    
| joinWebUrl            | String                                        | The join URL of the online meeting. The format of the URL may change; therefore, users shouldn't rely on any information extracted from parsing the URL. Read-only. Inherited from onlineMeetingBase. |
| participants          | meetingParticipants | The participants associated with the online meeting, including the organizer and the attendees.                       |
| subject               | String                                        | The subject of the online meeting. Required when you create an online meeting.                                                                                        |
| id                    | String                                        | The default ID associated with the online meeting. Read-only. Inherited from onlineMeetingBase.                                                             |
| isEntryExitAnnounced  | Boolean                                       | Indicates whether to announce when callers join or leave. Inherited from onlineMeetingBase.                                                                    |
| joinInformation       | itemBody                       | The join information in the language and locale variant specified in the `Accept-Language` request HTTP header. Read-only. Inherited from onlineMeetingBase. |
| joinMeetingIdSettings | joinMeetingIdSettings | Specifies the **joinMeetingId**, the meeting passcode, and the requirement for the passcode. Once an **onlineMeeting** is created, the **joinMeetingIdSettings** can't be modified. To make any changes to this property, the meeting needs to be canceled and a new one needs to be created. Inherited from onlineMeetingBase.                 |
| lobbyBypassSettings   | lobbyBypassSettings | Specifies which participants can bypass the meeting lobby. Inherited from onlineMeetingBase.                                                              |
| recordAutomatically | Boolean | Indicates whether to record the meeting automatically. Inherited from onlineMeetingBase. |
| shareMeetingChatHistoryDefault | meetingChatHistoryDefaultMode | Specifies whether meeting chat history is shared with participants. Possible values are: `all`, `none`, `unknownFutureValue`. Inherited from onlineMeetingBase. |
| startDateTime         | DateTime                                      | The meeting start time in UTC.                                                                                             |
| videoTeleconferenceId | String                                        | The video teleconferencing ID. Read-only. Inherited from onlineMeetingBase.                                                                                 |
| watermarkProtection | watermarkProtectionValues     | Specifies whether the client application should apply a watermark a content type. Inherited from onlineMeetingBase. |
| attendeeReport (deprecated) | Stream | The content stream of the attendee report of a Microsoft Teams live event. Read-only. |
| broadcastSettings (deprecated)    | broadcastMeetingSettings                      | Settings related to a live event.                                                                  |
| isBroadcast (deprecated) | Boolean                                       | Indicates whether this meeting is a Teams live event.                  |
### [virtualEvent ](https://docs.microsoft.com/graph/api/resources/virtualevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|communicationsIdentitySet|The identity information for the creator of the virtual event. Inherited from virtualEvent.|
|description|itemBody|A description of the virtual event.|
|displayName|String|The display name of the virtual event. |
|endDateTime|dateTimeTimeZone|The end time of the virtual event. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone.|
|id|String|The unique identifier of the virtual event. Inherited from entity.|
|settings|virtualEventSettings| The virtual event settings. |
|startDateTime|dateTimeTimeZone|Start time of the virtual event. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone.|
|status|virtualEventStatus|The status of the virtual event. The possible values are: `draft`, `published`, `canceled`, and `unknownFutureValue`.|
