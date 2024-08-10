# OnlineMeetings.Read

> Allows the app to read online meeting details on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /me/onlineMeetings/{id}/registration](https://docs.microsoft.com/graph/api/meetingregistration-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/onlineMeetings/{id}/registration/microsoft.graph.meetingRegistration/customQuestions](https://docs.microsoft.com/graph/api/meetingregistration-list-customquestions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/onlineMeetings/{id}/registration/registrants](https://docs.microsoft.com/graph/api/meetingregistration-list-registrants?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/onlineMeetings/{meetingId}](https://docs.microsoft.com/graph/api/onlinemeeting-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/onlineMeetings/{meetingId}/registration](https://docs.microsoft.com/graph/api/externalmeetingregistration-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/onlineMeetings/{meetingId}/registration/customQuestions/{id}](https://docs.microsoft.com/graph/api/meetingregistrationquestion-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/onlineMeetings/{meetingId}/registration/registrants](https://docs.microsoft.com/graph/api/externalmeetingregistrant-list?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/onlineMeetings/{onlineMeetingId}/getVirtualAppointmentJoinWebUrl](https://docs.microsoft.com/graph/api/virtualappointment-getvirtualappointmentjoinweburl?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/onlineMeetings/{onlineMeetingId}/virtualAppointment](https://docs.microsoft.com/graph/api/virtualappointment-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{userId}/onlineMeetings/{meetingId}](https://docs.microsoft.com/graph/api/onlinemeeting-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId}/onlineMeetings/{meetingId}/registration](https://docs.microsoft.com/graph/api/externalmeetingregistration-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId}/onlineMeetings/{meetingId}/registration/registrants](https://docs.microsoft.com/graph/api/externalmeetingregistrant-list?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{userId}/onlineMeetings/{onlineMeetingId}/getVirtualAppointmentJoinWebUrl](https://docs.microsoft.com/graph/api/virtualappointment-getvirtualappointmentjoinweburl?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId}/onlineMeetings/{onlineMeetingId}/virtualAppointment](https://docs.microsoft.com/graph/api/virtualappointment-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{usersId}/onlineMeetings/getAllRecordings(meetingOrganizerUserId='{userId}',startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/onlinemeeting-getallrecordings?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{usersId}/onlineMeetings/getAllTranscripts(meetingOrganizerUserId='{userId}',startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/onlinemeeting-getalltranscripts?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9be106e1-f4e3-4df5-bdff-e4bc531cbe43|
|**Consent Type**|User|
|**Display String**|Read user's online meetings|
|**Description**|Allows the app to read online meeting details on behalf of the signed-in user.|
## Resources
### [callRecording ](https://docs.microsoft.com/graph/api/resources/callrecording?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
| callId | String | The unique identifier for the call that is related to this recording. Read-only.|
| content | Stream | The content of the recording. Read-only.|
| contentCorrelationId | String | The unique identifier that links the transcript with its corresponding recording. Read-only.|
| createdDateTime | DateTimeOffset |  Date and time at which the recording was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
| endDateTime | DateTimeOffset |  Date and time at which the recording ends. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
| id | String | The unique identifier for the recording. Read-only. Inherited from entity.|
| meetingId | String | The unique identifier of the **onlineMeeting** related to this recording. Read-only.|
| meetingOrganizer| identitySet| The identity information of the organizer of the **onlineMeeting** related to this recording. Read-only.|
| recordingContentUrl| String| The URL that can be used to access the content of the recording. Read-only.|
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
### [externalmeetingregistrant](https://docs.microsoft.com/graph/api/resources/externalmeetingregistrant?view=graph-rest-1.0&tabs=http)
| Property   | Type   | Description                                                                  |
|:-----------|:-------|:-----------------------------------------------------------------------------|
| id         | String | The unique identifier of the registrant in the external registration system. Inherited from meetingRegistrantBase. |
| joinWebUrl | String | A unique web URL for the registrant to join the meeting. Inherited from meetingRegistrantBase. Read-only.          |
| tenantId   | String | The tenant ID of this registrant if in Microsoft Entra ID.               |
| userId     | String | The user ID of this registrant if in Microsoft Entra ID.                 |
### [externalmeetingregistration](https://docs.microsoft.com/graph/api/resources/externalmeetingregistration?view=graph-rest-1.0&tabs=http)
| Property          | Type                                       | Description                                 |
|:------------------|:-------------------------------------------|:--------------------------------------------|
| allowedRegistrant | meetingAudience | Specifies who can register for the meeting. Inherited from meetingRegistrationBase. |
### [meetingregistrant](https://docs.microsoft.com/graph/api/resources/meetingregistrant?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :------- | :--- | :---------- |
| customQuestionAnswers | customQuestionAnswer collection | The registrant's answer to custom questions. |
| email | String | The email address of the registrant. |
| firstName | String | The first name of the registrant. |
| id | String | The unique identifier of the registrant. Read-only. |
| joinWebUrl | String | A unique web URL for the registrant to join the meeting. Read-only. |
| lastName | String | The family name of the registrant. |
| registrationDateTime | String | Time in UTC when the registrant registers for the meeting. Read-only. |
| status | meetingRegistrantStatus | The registration status of the registrant. Read-only. |
### [meetingregistration](https://docs.microsoft.com/graph/api/resources/meetingregistration?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :------- | :--- | :---------- |
| allowedRegistrant | meetingAudience | Specifies who can register for the meeting. |
| description | String | The description of the meeting. |
| endDateTime | DateTime | The meeting end time in UTC. |
| registrationPageViewCount | Int32 | The number of times the registration page has been visited. Read-only. |
| registrationPageWebUrl | String | The URL of the registration page. Read-only. |
| speakers | meetingSpeaker collection | The meeting speaker's information. |
| startDateTime | DateTime | The meeting start time in UTC. |
| subject | String | The subject of the meeting. |
### [meetingRegistrationQuestion ](https://docs.microsoft.com/graph/api/resources/meetingregistrationquestion?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :------- | :--- | :---------- |
| answerInputType | answerInputType | Answer input type of the custom registration question. |
| answerOptions | String collection | Answer options when **answerInputType** is `radioButton`. |
| displayName | String | Display name of the custom registration question. |
| id | String | ID of the custom registration question. Read-only. |
| isRequired | Boolean | Indicates whether the question is required. Default value is `false`. |
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
### [virtualappointment](https://docs.microsoft.com/graph/api/resources/virtualappointment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appointmentClients|virtualAppointmentUser collection|The client information for the virtual appointment, including name, email, and SMS phone number. Optional.|
|appointmentClientJoinWebUrl|String|The join web URL of the virtual appointment for clients with waiting room and browser join. Optional.|
|externalAppointmentId|String|The identifier of the appointment from the scheduling system, associated with the current virtual appointment. Optional.|
|externalAppointmentUrl|String|The URL of the appointment resource from the scheduling system, associated with the current virtual appointment. Optional.|
|settings|virtualAppointmentSettings|The settings associated with the virtual appointment resource. Optional.|
### [virtualEventWebinar ](https://docs.microsoft.com/graph/api/resources/virtualeventwebinar?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| -------- | ---- | ----------- |
| audience | meetingAudience | To whom the webinar is visible. Possible values are: `everyone`, `organization`, and `unknownFutureValue`. |
| coOrganizers  | communicationsUserIdentity collection | Identity information of coorganizers of the webinar. |
| createdBy | communicationsIdentitySet | Identity information for the creator of the webinar. Inherited from virtualEvent. |
| description | itemBody | Description of the webinar. Inherited from virtualEvent. |
| displayName | String | Display name of the webinar. Inherited from virtualEvent. |
| endDateTime | dateTimeTimeZone | End time of the webinar. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone. |
| startDateTime | dateTimeTimeZone | Start time of the webinar. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone. |
| id | String | Unique identifier of the webinar. Inherited from entity.|
| settings | virtualEventSettings | The webinar settings. Inherited from virtualEvent. |
| status | virtualEventStatus | Status of the webinar. Possible values are: `draft`, `published`, `canceled`, and `unknownFutureValue`. Inherited from virtualEvent. |
