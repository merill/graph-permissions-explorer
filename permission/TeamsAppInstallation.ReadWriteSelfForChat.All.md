# TeamsAppInstallation.ReadWriteSelfForChat.All

> Allows a Teams app to read, install, upgrade, and uninstall itself for any chat, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[DELETE /chats/{chat-id}/installedApps/{app-installation-id}](https://docs.microsoft.com/graph/api/chat-delete-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}/installedApps](https://docs.microsoft.com/graph/api/chat-list-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}/installedApps/{app-installation-id}](https://docs.microsoft.com/graph/api/chat-get-installedapps?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /chats/{chat-id}/permissionGrants](https://docs.microsoft.com/graph/api/chat-list-permissiongrants?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /chats/{chat-id}/installedApps](https://docs.microsoft.com/graph/api/chat-post-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /chats/{chat-id}/installedApps/{app-installation-id}/upgrade](https://docs.microsoft.com/graph/api/chat-teamsappinstallation-upgrade?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|73a45059-f39c-4baf-9182-4954ac0e55cf|
|**Display String**|Allow the Teams app to manage itself for all chats|
|**Description**|Allows a Teams app to read, install, upgrade, and uninstall itself for any chat, without a signed-in user.|
## Resources
### [chat ](https://docs.microsoft.com/graph/api/resources/chat?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
| chatType| chatType | Specifies the type of chat. Possible values are: `group`, `oneOnOne`, `meeting`, `unknownFutureValue`.|
| createdDateTime| dateTimeOffset|  Date and time at which the chat was created. Read-only.|
| id| String| The chat's unique identifier. Read-only.|
| lastUpdatedDateTime| dateTimeOffset|  Date and time at which the chat was renamed or the list of members was last changed. Read-only.|
| onlineMeetingInfo | teamworkOnlineMeetingInfo | Represents details about an online meeting. If the chat isn't associated with an online meeting, the property is empty. Read-only.|
| tenantId| String | The identifier of the tenant in which the chat was created. Read-only.|
| topic| String|  (Optional) Subject or topic for the chat. Only available for group chats.|
| viewpoint|chatViewpoint|Represents caller-specific information about the chat, such as the last message read date and time. This property is populated only when the request is made in a delegated context.|
| webUrl | String| The URL for the chat in Microsoft Teams. The URL should be treated as an opaque blob, and not parsed. Read-only. |
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
### [resourceSpecificPermissionGrant ](https://docs.microsoft.com/graph/api/resources/resourcespecificpermissiongrant?view=graph-rest-1.0&tabs=http)
| Property        | Type          | Description                                                                           |
| :-------------- | :------------ | :------------------------------------------------------------------------------------ |
| clientId        | string        | ID of the Microsoft Entra app that has been granted access. Read-only.                            |
| clientAppId     | string        | ID of the service principal of the Microsoft Entra app that has been granted access. Read-only.   |
| deletedDateTime | dateTimeOffset| Not used.                                                                             |
| id              | string        | The unique identifier of the resource-specific permission grant. Read-only.           |
| resourceAppId   | string        | ID of the Microsoft Entra app that is hosting the resource. Read-only.                        |
| permissionType  | string        | The type of permission. Possible values are: `Application`, `Delegated`. Read-only. |
| permission      | string        | The name of the resource-specific permission. Read-only.                                                |
### [teamsApp ](https://docs.microsoft.com/graph/api/resources/teamsapp?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| displayName                | string   | The name of the catalog app provided by the app developer in the Microsoft Teams zip app package. |
| distributionMethod  | teamsAppDistributionMethod     | The method of distribution for the app. Read-only.|
| externalId          | string   | The ID of the catalog provided by the app developer in the Microsoft Teams zip app package. |
| id                  | string   | The app ID generated for the catalog is different from the developer-provided ID found within the Microsoft Teams zip app package. The **e
### [teamsAppInstallation ](https://docs.microsoft.com/graph/api/resources/teamsappinstallation?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
|consentedPermissionSet|teamsAppPermissionSet|The set of resource-specific permissions consented to while installing or upgrading the teamsApp.|
| id                  | string   | A unique ID (not the Teams app ID). |
### [teamsAppPermissionSet ](https://docs.microsoft.com/graph/api/resources/teamsapppermissionset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|resourceSpecificPermissions|teamsAppResourceSpecificPermission collection|A collection of resource-specific permissions.|
### [teamworkBot ](https://docs.microsoft.com/graph/api/resources/teamworkbot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the bot associated with the specific teamsAppDefinition. This value is usually a GUID.|
