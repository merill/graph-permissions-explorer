# Calls.JoinGroupCallasGuest.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[GET /app/calls/{id}/participants/{id}](https://docs.microsoft.com/graph/api/participant-get?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /communications/calls/{id}/participants/{id}](https://docs.microsoft.com/graph/api/participant-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /app/calls/{id}/participants/{id}/mute](https://docs.microsoft.com/graph/api/participant-mute?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /app/calls/{id}/participants/muteAll](https://docs.microsoft.com/graph/api/participant-muteall?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /communications/calls/{id}/participants/{id}/mute](https://docs.microsoft.com/graph/api/participant-mute?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/participants/{id}/startHoldMusic](https://docs.microsoft.com/graph/api/participant-startholdmusic?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/calls/{id}/participants/{id}/stopHoldMusic](https://docs.microsoft.com/graph/api/participant-stopholdmusic?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /communications/calls/{id}/participants/muteAll](https://docs.microsoft.com/graph/api/participant-muteall?view=graph-rest-beta&tabs=http)|
|V1|A|[PS C:\> Set-CsApplicationMeetingConfiguration -AllowRemoveParticipantAppIds @{Add="app_id"}](https://docs.microsoft.com/graph/api/participant-delete?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [commsOperation ](https://docs.microsoft.com/graph/api/resources/commsoperation?view=graph-rest-1.0&tabs=http)
| Property           | Type                        | Description                                                                     |
| :----------------- | :-------------------------- | :-------------------------------------------------------------------------------|
| clientContext      | String                      | Unique Client Context string. Max limit is 256 chars.                           |
| ID                 | String                      | The operation ID. Read-only.                                                    |
| resultInfo         | resultInfo | The result information. Read-only.                                              |
| status             | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only. |
### [invitationParticipantInfo ](https://docs.microsoft.com/graph/api/resources/invitationparticipantinfo?view=graph-rest-1.0&tabs=http)
| Property                           | Type                          | Description                                                                          |
| :--------------------------------- | :---------------------------- | :----------------------------------------------------------------------------------- |
| hidden                             | Boolean                       | Optional. Whether to hide the participant from the roster. |
| identity                           | identitySet | The identitySet associated with this invitation.                   |
| participantId                      | String                        | Optional. The ID of the target participant.                                          |
| removeFromDefaultAudioRoutingGroup | Boolean                       | Optional. Whether to remove them from the main mixer. |
| replacesCallId                     | String                        | Optional. The call which the target identity is currently a part of. For peer-to-peer case, the call will be dropped once the participant is added successfully. |
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
