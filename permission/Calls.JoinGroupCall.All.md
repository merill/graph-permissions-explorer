# Calls.JoinGroupCall.All

> Allows the app to join group calls and scheduled meetings in your organization, without a signed-in user.  The app will be joined with the privileges of a directory user to meetings in your organization.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[DELETE /app/calls/{id}/audioRoutingGroups/{id}](https://docs.microsoft.com/graph/api/audioroutinggroup-delete?view=graph-rest-1.0&tabs=http)|
|V1|A|[DELETE /communications/calls/{id}/audioRoutingGroups/{id}](https://docs.microsoft.com/graph/api/audioroutinggroup-delete?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /app/calls/{id}/audioRoutingGroups](https://docs.microsoft.com/graph/api/call-list-audioroutinggroups?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /app/calls/{id}/audioRoutingGroups/{id}](https://docs.microsoft.com/graph/api/audioroutinggroup-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /app/calls/{id}/participants/{id}](https://docs.microsoft.com/graph/api/participant-get?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /communications/calls/{id}/audioRoutingGroups](https://docs.microsoft.com/graph/api/call-list-audioroutinggroups?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/calls/{id}/audioRoutingGroups/{id}](https://docs.microsoft.com/graph/api/audioroutinggroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/calls/{id}/contentSharingSessions](https://docs.microsoft.com/graph/api/call-list-contentsharingsessions?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/calls/{id}/contentSharingSessions/{id}](https://docs.microsoft.com/graph/api/contentsharingsession-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/calls/{id}/participants/{id}](https://docs.microsoft.com/graph/api/participant-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /app/calls/{id}/audioRoutingGroups/{id}](https://docs.microsoft.com/graph/api/audioroutinggroup-update?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /communications/calls/{id}/audioRoutingGroups/{id}](https://docs.microsoft.com/graph/api/audioroutinggroup-update?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /app/calls](https://docs.microsoft.com/graph/api/application-post-calls?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /app/calls/{id}/addLargeGalleryView](https://docs.microsoft.com/graph/api/call-addlargegalleryview?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /app/calls/{id}/answer](https://docs.microsoft.com/graph/api/call-answer?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /app/calls/{id}/audioRoutingGroups](https://docs.microsoft.com/graph/api/call-post-audioroutinggroups?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /app/calls/{id}/participants/{id}/mute](https://docs.microsoft.com/graph/api/participant-mute?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/participants/muteAll](https://docs.microsoft.com/graph/api/participant-muteall?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/updateRecordingStatus](https://docs.microsoft.com/graph/api/call-updaterecordingstatus?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /communications/calls](https://docs.microsoft.com/graph/api/application-post-calls?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/addLargeGalleryView](https://docs.microsoft.com/graph/api/call-addlargegalleryview?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/answer](https://docs.microsoft.com/graph/api/call-answer?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/audioRoutingGroups](https://docs.microsoft.com/graph/api/call-post-audioroutinggroups?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/participants/{id}/mute](https://docs.microsoft.com/graph/api/participant-mute?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/participants/{id}/startHoldMusic](https://docs.microsoft.com/graph/api/participant-startholdmusic?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/participants/{id}/stopHoldMusic](https://docs.microsoft.com/graph/api/participant-stopholdmusic?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /communications/calls/{id}/participants/muteAll](https://docs.microsoft.com/graph/api/participant-muteall?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /communications/calls/{id}/updateRecordingStatus](https://docs.microsoft.com/graph/api/call-updaterecordingstatus?view=graph-rest-1.0&tabs=http)|
|V1|A|[PS C:\> Set-CsApplicationMeetingConfiguration -AllowRemoveParticipantAppIds @{Add="app_id"}](https://docs.microsoft.com/graph/api/participant-delete?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|f6b49018-60ab-4f81-83bd-22caeabfed2d|
|**Display String**|Join group calls and meetings as an app|
|**Description**|Allows the app to join group calls and scheduled meetings in your organization, without a signed-in user.  The app will be joined with the privileges of a directory user to meetings in your organization.|
## Resources
### [addLargeGalleryViewOperation ](https://docs.microsoft.com/graph/api/resources/addlargegalleryviewoperation?view=graph-rest-1.0&tabs=http)
| Property      | Type                        | Description                                                                                                  |
|:--------------|:----------------------------|:-------------------------------------------------------------------------------------------------------------|
| clientContext | String                      | The client context.                                                                                          |
| id            | String                      | The ID of the server operation. Read-only.                                                                   |
| resultInfo    | resultInfo | The result information. Read-only.                                                                           |
| status        | operationStatus             | The status of the operation. Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only. |
### [appHostedMediaConfig ](https://docs.microsoft.com/graph/api/resources/apphostedmediaconfig?view=graph-rest-1.0&tabs=http)
| Property                          | Type    | Description                                                     |
| :-------------------------------- | :------ | :---------------------------------------------------------------|
| blob                              | String  | The media configuration blob generated by smart media agent.    |
### [audioRoutingGroup ](https://docs.microsoft.com/graph/api/resources/audioroutinggroup?view=graph-rest-1.0&tabs=http)
| Property      | Type              | Description                                                          |
| :----------   | :---------------- | :--------------------------------------------------------------------|
| id            | string            | Read-only.                                                           |
| receivers     | collection(string) | List of receiving participant ids.                                   |
| routingMode   | string            | Routing group mode.  Possible values are: `oneToOne`, `multicast`.   |
| sources       | collection(string) | List of source participant ids.                                      |
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
### [chatInfo ](https://docs.microsoft.com/graph/api/resources/chatinfo?view=graph-rest-1.0&tabs=http)
| Property            | Type    | Description|
|:--------------------|:--------|:-----------|
| messageId           | String  | The unique identifier of a message in a Microsoft Teams channel. |
| replyChainMessageId | String  | The ID of the reply message. |
| threadId            | String  | The unique identifier for a thread in Microsoft Teams. |
### [commsOperation ](https://docs.microsoft.com/graph/api/resources/commsoperation?view=graph-rest-1.0&tabs=http)
| Property           | Type                        | Description                                                                     |
| :----------------- | :-------------------------- | :-------------------------------------------------------------------------------|
| clientContext      | String                      | Unique Client Context string. Max limit is 256 chars.                           |
| ID                 | String                      | The operation ID. Read-only.                                                    |
| resultInfo         | resultInfo | The result information. Read-only.                                              |
| status             | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only. |
### [contentSharingSession ](https://docs.microsoft.com/graph/api/resources/contentsharingsession?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                                                                                                    |
|:---------|:-------|:---------------------------------------------------------------------------------------------------------------|
| id       | String | Unique identifier for the content sharing session. Read-only. Inherited from entity. |
### [identitySet ](https://docs.microsoft.com/graph/api/resources/identityset?view=graph-rest-1.0&tabs=http)
| Property    | Type                    | Description                                            |
|:------------|:------------------------|:-------------------------------------------------------|
| application | identity | Optional. The application associated with this action.  |
| applicationInstance | identity | Optional. The application instance associated with this action.  |
| conversation| identity | Optional. The team or channel associated with this action.       |
| conversationIdentityType| identity | Optional. Indicates whether the **conversation** property identifies a team or channel.|
| device      | identity | Optional. The device associated with this action.       |
| encrypted       | identity | Optional. The encrypted identity associated with this action. |
| onPremises       | identity | Optional. The on-premises identity associated with this action. |
| guest       | identity | Optional. The guest identity associated with this action. |
| phone       | identity | Optional. The phone number associated with this action. |
| user        | identity | Optional. The user associated with this action.         |
### [incomingCallOptions ](https://docs.microsoft.com/graph/api/resources/incomingcalloptions?view=graph-rest-1.0&tabs=http)
| Property                            | Type    | Description                                                                                                                   |
|:------------------------------------|:--------|:------------------------------------------------------------------------------------------------------------------------------|
| hideBotAfterEscalation              | Boolean | Indicates whether to hide the app after the call is escalated. Inherited from callOptions.                  |
| isContentSharingNotificationEnabled | Boolean | Indicates whether content sharing notifications should be enabled for the call. Inherited from callOptions. |
### [invitationParticipantInfo ](https://docs.microsoft.com/graph/api/resources/invitationparticipantinfo?view=graph-rest-1.0&tabs=http)
| Property                           | Type                          | Description                                                                          |
| :--------------------------------- | :---------------------------- | :----------------------------------------------------------------------------------- |
| hidden                             | Boolean                       | Optional. Whether to hide the participant from the roster. |
| identity                           | identitySet | The identitySet associated with this invitation.                   |
| participantId                      | String                        | Optional. The ID of the target participant.                                          |
| removeFromDefaultAudioRoutingGroup | Boolean                       | Optional. Whether to remove them from the main mixer. |
| replacesCallId                     | String                        | Optional. The call which the target identity is currently a part of. For peer-to-peer case, the call will be dropped once the participant is added successfully. |
### [meetingInfo ](https://docs.microsoft.com/graph/api/resources/meetinginfo?view=graph-rest-1.0&tabs=http)

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
### [serviceHostedMediaConfig ](https://docs.microsoft.com/graph/api/resources/servicehostedmediaconfig?view=graph-rest-1.0&tabs=http)
| Property                    | Type                                                        | Description                                       |
| :-------------------------- | :---------------------------------------------------------- | :-------------------------------------------------|
| preFetchMedia               | mediaInfo collection                        | The list of media to pre-fetch.                   |
### [startHoldMusicOperation ](https://docs.microsoft.com/graph/api/resources/startholdmusicoperation?view=graph-rest-1.0&tabs=http)
| Property                       | Type                        | Description                                                                                                                                       |
| :----------------------------- | :---------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------|
| clientContext                  | String                      | Inherited from **commsOperation**. Unique client context string. Can have a maximum of 256 characters.                                                                               |
| id                             | String                      | Inherited from **commsOperation**. The server operation ID. Read-only.                                                                                            |
| resultInfo                     | resultInfo | Inherited from **commsOperation**. The result information.  Read-only.                                                                                            |
| status                         | String                      | Inherited from **c
### [stopHoldMusicOperation ](https://docs.microsoft.com/graph/api/resources/stopholdmusicoperation?view=graph-rest-1.0&tabs=http)
| Property                       | Type                        | Description                                                                                                                                       |
| :----------------------------- | :---------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------|
| clientContext                  | String                      | Inherited from **commsOperation**. Unique client context string. Can have a maximum of 256 characters.                                                                               |
| id                             | String                      | Inherited from **commsOperation**. The server operation ID. Read-only.                                                                                            |
| resultInfo                     | resultInfo | Inherited from **commsOperation**. The result information.  Read-only.                                                                                            |
| status                         | String                      | Inherited from **c
### [updateRecordingStatusOperation ](https://docs.microsoft.com/graph/api/resources/updaterecordingstatusoperation?view=graph-rest-1.0&tabs=http)
| Property            | Type                        | Description|
|:--------------------|:----------------------------|:-----------------------------------------------------------------------------------|
| clientContext       | String                      | Unique client context string. Max limit is 256 chars.                              |
| id                  | String                      | Read-only.                                                                         |
| resultInfo          | resultInfo | The result information. Read-only.                                                 |
| status              | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`.               |
