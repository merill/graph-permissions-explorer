# Calls.AccessMedia.All

> Allows the app to get direct access to media streams in a call, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[DELETE /app/calls/{id}](https://docs.microsoft.com/graph/api/call-delete?view=graph-rest-beta&tabs=http)|
|V1|A|[DELETE /communications/calls/{id}](https://docs.microsoft.com/graph/api/call-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /app/calls/{id}](https://docs.microsoft.com/graph/api/call-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /app/calls/{id}/participants](https://docs.microsoft.com/graph/api/call-list-participants?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /communications/calls/{id}](https://docs.microsoft.com/graph/api/call-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/calls/{id}/participants](https://docs.microsoft.com/graph/api/call-list-participants?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /app/calls/{id}/cancelMediaProcessing](https://docs.microsoft.com/graph/api/call-cancelmediaprocessing?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/changeScreenSharingRole](https://docs.microsoft.com/graph/api/call-changescreensharingrole?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/mute](https://docs.microsoft.com/graph/api/call-mute?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/playPrompt](https://docs.microsoft.com/graph/api/call-playprompt?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/recordResponse](https://docs.microsoft.com/graph/api/call-record?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /app/calls/{id}/sendDtmfTones](https://docs.microsoft.com/graph/api/call-senddtmftones?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /app/calls/{id}/subscribeToTone](https://docs.microsoft.com/graph/api/call-subscribetotone?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/unmute](https://docs.microsoft.com/graph/api/call-unmute?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/updateRecordingStatus](https://docs.microsoft.com/graph/api/call-updaterecordingstatus?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /communications/calls/{id}/cancelMediaProcessing](https://docs.microsoft.com/graph/api/call-cancelmediaprocessing?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/changeScreenSharingRole](https://docs.microsoft.com/graph/api/call-changescreensharingrole?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/keepAlive](https://docs.microsoft.com/graph/api/call-keepalive?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/mute](https://docs.microsoft.com/graph/api/call-mute?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/playPrompt](https://docs.microsoft.com/graph/api/call-playprompt?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/recordResponse](https://docs.microsoft.com/graph/api/call-record?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/sendDtmfTones](https://docs.microsoft.com/graph/api/call-senddtmftones?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/subscribeToTone](https://docs.microsoft.com/graph/api/call-subscribetotone?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/unmute](https://docs.microsoft.com/graph/api/call-unmute?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/updateRecordingStatus](https://docs.microsoft.com/graph/api/call-updaterecordingstatus?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/logTeleconferenceDeviceQuality](https://docs.microsoft.com/graph/api/call-logteleconferencedevicequality?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|a7a681dc-756e-4909-b988-f160edc6655f|
|**Display String**|Access media streams in a call as an app|
|**Description**|Allows the app to get direct access to media streams in a call, without a signed-in user.|
## Resources
### [call ](https://docs.microsoft.com/graph/api/resources/call?view=graph-rest-1.0&tabs=http)
| Property            | Type                                                                                                   | Description                                                                                                                                                                                         |
| :------------------ | :------------------------------------------------------------------------------------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| callbackUri         | String                                                                                                 | The callback URL on which callbacks are delivered. Must be an HTTPS URL.                                                                                                                             |
| callChainId         | String                                                                                                 | A unique identifier for all the participant calls in a conference or a unique identifier for two participant calls in a P2P call.  This identifier must be copied over from `Microsoft.Graph.Call.CallChainId`. |
| callOptions         | outgoingCallOptions                                                          | Contains the optional features for the call.                                                                                                                                                        |
| callRoutes          | callRoute collection                                                                   | The routing information on how the call was retargeted. Read-only.                                                                                                                                  |
| chatInfo            | chatInfo                                                                                | The chat information. Required information for joining a meeting.                                                                                                                                   |
| direction           | callDirection                                                                                          | The direction of the call. The possible values are `incoming` or `outgoing`. Read-only.                                                                                                              |
| id                  | String                                                                                                 | The unique identifier for the call. Read-only.                                                                                                                                                      |
|incomingContext      | incomingContext                                                                  | Call context associated with an incoming call.                                                                                                                                                      |
| mediaConfig         | appHostedMediaConfig or serviceHostedMediaConfig | The media configuration. Required.                                                                                                                                                              |
| mediaState          | callMediaState                                                                    | Read-only. The call media state.                                                                                                                                                                    |
| meetingInfo         | organizerMeetingInfo, tokenMeetingInfo, or joinMeetingIdMeetingInfo | The meeting information. Required information for meeting scenarios.                                                                                  |
| myParticipantId     | String                                                                                                 | Read-only.                                                                                                                                                                                          |
| requestedModalities | modality collection                                                                                    | The list of requested modalities. Possible values are: `unknown`, `audio`, `video`, `videoBasedScreenSharing`, `data`.                                                                              |
| resultInfo          | resultInfo                                                                            | The result information. For example, the result can hold termination reason. Read-only.                                                                                                                         |
| source              | participantInfo                                                                  | The originator of the call.                                                                                                                                                                         |
| state               | callState                                                                                              | The call state. Possible values are: `incoming`, `establishing`, `ringing`, `established`, `hold`, `transferring`, `transferAccepted`, `redirecting`, `terminating`, `terminated`. Read-only.       |
| subject             | String                                                                                                 | The subject of the conversation.                                                                                                                                                                    |
| targets             | invitationParticipantInfo collection                                             | The targets of the call. Required information for creating peer to peer call.                                                                                                                       |
|toneInfo             | toneInfo                                                                                | Read-only.                                                                                                                                                                                          |
|transcription        | callTranscriptionInfo                                                      | The transcription information for the call. Read-only.                                                                                                                                              |
### [commsOperation ](https://docs.microsoft.com/graph/api/resources/commsoperation?view=graph-rest-1.0&tabs=http)
| Property           | Type                        | Description                                                                     |
| :----------------- | :-------------------------- | :-------------------------------------------------------------------------------|
| clientContext      | String                      | Unique Client Context string. Max limit is 256 chars.                           |
| ID                 | String                      | The operation ID. Read-only.                                                    |
| resultInfo         | resultInfo | The result information. Read-only.                                              |
| status             | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only. |
### [mediaPrompt ](https://docs.microsoft.com/graph/api/resources/mediaprompt?view=graph-rest-1.0&tabs=http)
| Property    | Type                      | Description                                                                     |
| :---------- | :------------------------ | :------------------------------------------------------------------------------ |
| mediaInfo   | mediaInfo | The media information                                                           |
### [MuteParticipantOperation ](https://docs.microsoft.com/graph/api/resources/muteparticipantoperation?view=graph-rest-1.0&tabs=http)
| Property                       | Type                        | Description                                                                                                                                       |
| :----------------------------- | :---------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------|
| clientContext                  | String                      | Unique client context string. Can have a maximum of 256 characters.                                                                               |
| id                             | String                      | The server operation ID. Read-only.                                                                                            |
| resultInfo                     | resultInfo | The result information.  Read-only.                                                                                            |
| status                         | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only.                                                 |
### [participant ](https://docs.microsoft.com/graph/api/resources/participant?view=graph-rest-1.0&tabs=http)
| Property             | Type                                     | Description                                                  |
| :------------------- | :--------------------------------------- | :------------------------------------------------------------|
| id                   | String                                   | The participant ID.                                          |
| info                 | participantInfo    | Information about the participant.                          |
| isInLobby            | Boolean                                  | `true` if the participant is in lobby.                          |
| isMuted              | Boolean                                  | `true` if the participant is muted (client or server muted).    |
| mediaStreams         | mediaStream collection | The list of media streams.                                   |
| metadata             | String                                   | A blob of data provided by the participant in the roster.     |
| recordingInfo        | recordingInfo        | Information about whether the participant has recording capability. |
| removedState         | removedState          | Indicates the reason why the **participant** was removed from the roster. |
| restrictedExperience | onlineMeetingRestricted        | Indicates the reason or reasons media content from this participant is restricted. |
| rosterSequenceNumber | Int64        | Indicates the roster sequence number in which the **p
### [playPromptOperation ](https://docs.microsoft.com/graph/api/resources/playpromptoperation?view=graph-rest-1.0&tabs=http)
| Property            | Type                        | Description|
|:--------------------|:----------------------------|:-----------------------------------------------------------------------------------|
| clientContext       | String                      | Unique Client Context string. Max limit is 256 chars.                              |
| id                  | String                      | Read-only.                                                                         |
| resultInfo          | resultInfo | The result information. Read-only.                                |
| status              | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`.               |
### [recordOperation ](https://docs.microsoft.com/graph/api/resources/recordoperation?view=graph-rest-1.0&tabs=http)
| Property                       | Type                        | Description                                                                                                                                       |
| :----------------------------- | :---------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------|
| clientContext                  | String                      | Unique Client Context string. Max limit is 256 chars.                                                                                                                               |
| id                             | String                      | The server operation id. Read-only.                                                                                              |
| recordingAccessToken           | String                      | The access token required to retrieve the recording.                                                                                              |
| recordingLocation              | String                      | The location where the recording is located.                                                                                                      |
| resultInfo                     | resultInfo | The result information.  Read-only.                                                                                              |
| status                         | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only.                                                |
### [sendDtmfTonesOperation ](https://docs.microsoft.com/graph/api/resources/senddtmftonesoperation?view=graph-rest-1.0&tabs=http)
| Property            | Type                        | Description|
|:--------------------|:----------------------------|:-----------------------------------------------------------------------------------|
| clientContext       | String                      | A unique string that the client sends to Microsoft Graph to keep context in multiple requests. Maximum size is 256 characters. |
| completionReason    | sendDtmfCompletionReason    | The results of the action. Possible values are: `unknown`, `completedSuccessfully`, `mediaOperationCanceled`, `unknownfutureValue`. |
| id                  | String                      | Read-only.                                                                         |
| resultInfo          | resultInfo | The result information with a specific status code, subcode, and message. Read-only.        |
| status              | String                      | The status of the operation. Possible values are: `notStarted`, `running`, `completed`, `failed`.               |
### [serviceHostedMediaConfig ](https://docs.microsoft.com/graph/api/resources/servicehostedmediaconfig?view=graph-rest-1.0&tabs=http)
| Property                    | Type                                                        | Description                                       |
| :-------------------------- | :---------------------------------------------------------- | :-------------------------------------------------|
| preFetchMedia               | mediaInfo collection                        | The list of media to pre-fetch.                   |
### [teleconferenceDeviceQuality ](https://docs.microsoft.com/graph/api/resources/teleconferencedevicequality?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|callChainId|Guid|A unique identifier for all  the participant calls in a conference or a unique identifier for two participant calls in P2P call. This needs to be copied over from `Microsoft.Graph.Call.CallChainId`.|
|cloudServiceDeploymentEnvironment|String|A geo-region where the service is deployed, such as `ProdNoam`.|
|cloudServiceDeploymentId|String|A unique deployment identifier assigned by Azure.|
|cloudServiceInstanceName|String|The Azure deployed cloud service instance name, such as `FrontEnd_IN_3`.|
|cloudServiceName|String|The Azure deployed cloud service name, such as `contoso.cloudapp.net`.|
|deviceDescription|String|Any additional description, such as `VTC Bldg 30/21`.|
|deviceName|String|The user media agent name, such as `Cisco SX80`.|
|mediaLegId|Guid|A unique identifier for a specific media leg of a participant in a conference.  One participant can have multiple media leg identifiers if retargeting happens. CVI partner assigns this value.|
|mediaQualityList|teleconferenceDeviceMediaQuality collection|The list of media qualities in a media session (call), such as audio quality, video quality, and/or screen sharing quality.|
|participantId|Guid|A unique identifier for a specific participant in a conference. The CVI partner needs to copy over `Call.MyParticipantId` to this property.|
### [toneInfo ](https://docs.microsoft.com/graph/api/resources/toneinfo?view=graph-rest-1.0&tabs=http)
| Property       | Type    | Description|
|:---------------|:--------|:----------|
| sequenceId | Int64 | An incremental identifier used for ordering DTMF events. |
| tone | tone | Possible values are: `tone0`, `tone1`, `tone2`, `tone3`, `tone4`, `tone5`, `tone6`, `tone7`, `tone8`, `tone9`, `star`, `pound`, `a`, `b`, `c`, `d`, `flash`. |
### [updateRecordingStatusOperation ](https://docs.microsoft.com/graph/api/resources/updaterecordingstatusoperation?view=graph-rest-1.0&tabs=http)
| Property            | Type                        | Description|
|:--------------------|:----------------------------|:-----------------------------------------------------------------------------------|
| clientContext       | String                      | Unique client context string. Max limit is 256 chars.                              |
| id                  | String                      | Read-only.                                                                         |
| resultInfo          | resultInfo | The result information. Read-only.                                                 |
| status              | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`.               |
