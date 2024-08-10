# OnlineMeetingTranscript.Read.All

> Allows the app to read all transcripts of online meetings, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/onlineMeetings/{meetingId}/transcripts/{transcriptId}](https://docs.microsoft.com/graph/api/calltranscript-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/onlineMeetings/{online-meeting-id}/transcripts](https://docs.microsoft.com/graph/api/onlinemeeting-list-transcripts?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/onlineMeetings/{online-meeting-id}/transcripts](https://docs.microsoft.com/graph/api/onlinemeeting-list-transcripts?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{userId}/onlineMeetings/{meetingId}/transcripts/{transcriptId}](https://docs.microsoft.com/graph/api/calltranscript-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /users/{usersId}/onlineMeetings/getAllTranscripts(meetingOrganizerUserId='{userId}',startDateTime={startDateTime})/delta](https://docs.microsoft.com/graph/api/calltranscript-delta?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|30b87d18-ebb1-45db-97f8-82ccb1f0190c|
|**Consent Type**|Admin|
|**Display String**|Read all transcripts of online meetings. |
|**Description**|Allows the app to read all transcripts of online meetings, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|a4a80d8d-d283-4bd8-8504-555ec3870630|
|**Display String**|Read all transcripts of online meetings.|
|**Description**|Allows the app to read all transcripts of all online meetings, without a signed-in user.|
## Resources
### [callTranscript ](https://docs.microsoft.com/graph/api/resources/calltranscript?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
| callId | String | The unique identifier for the call that is related to this transcript. Read-only.|
| content| Stream| The content of the transcript. Read-only.|
| contentCorrelationId | String | The unique identifier that links the transcript with its corresponding recording. Read-only.|
| createdDateTime| DateTimeOffset|  Date and time at which the transcript was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
| endDateTime | DateTimeOffset |  Date and time at which the transcription ends. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.| 
| id| String| The unique identifier for the transcript. Read-only.|
| meetingId | String | The unique identifier of the online meeting related to this transcript. Read-only.|
| meetingOrganizer| identitySet| The identity information of the organizer of the **onlineMeeting** related to this transcript. Read-only.|
| metadataContent| Stream| The time-aligned metadata of the utterances in the transcript. Read-only.|
| transcriptContentUrl| String| The URL that can be used to access the content of the transcript. Read-only.|
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
