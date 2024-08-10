# Chat.Manage.Chat

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[DELETE /chats/{chat-id}/installedApps/{app-installation-id}](https://docs.microsoft.com/graph/api/chat-delete-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[DELETE /chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-delete-members?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}/installedApps](https://docs.microsoft.com/graph/api/chat-list-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}/installedApps/{app-installation-id}](https://docs.microsoft.com/graph/api/chat-get-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-get-members?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /chats/{chat-id}/operations](https://docs.microsoft.com/graph/api/chat-list-operations?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /chats/{chat-id}/operations/{operation-id}](https://docs.microsoft.com/graph/api/teamsasyncoperation-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /chats/{chat-id}/permissionGrants](https://docs.microsoft.com/graph/api/chat-list-permissiongrants?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /chats/{id}/members](https://docs.microsoft.com/graph/api/conversationmember-list?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{user-id | user-principal-name}/chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-get-members?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /chats/{chat-id}/installedApps](https://docs.microsoft.com/graph/api/chat-post-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /chats/{chat-id}/installedApps/{app-installation-id}/upgrade](https://docs.microsoft.com/graph/api/chat-teamsappinstallation-upgrade?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-post-members?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [channel ](https://docs.microsoft.com/graph/api/resources/channel?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|createdDateTime|dateTimeOffset|Read only. Timestamp at which the channel was created.|
|description|String|Optional textual description for the channel.|
|displayName|String|Channel name as it will appear to the user in Microsoft Teams. The maximum length is 50 characters.|
|email|String| The email address for sending messages to the channel. Read-only.|
|id|String|The channel's unique identifier. Read-only.|
|isArchived| Boolean | Indicates whether the channel is archived. Read-only. |
|isFavoriteByDefault|Boolean|Indicates whether the channel should be marked as recommended for all members of the team to show in their channel list. **Note:** All recommended channels automatically show in the channels list for education and frontline worker users. The property can only be set programmatically via the Create team method. The default value is `false`.|
|membershipType|channelMembershipType|The type of the channel. Can be set during creation and can't be changed. The possible values are: `standard`, `private`, `unknownFutureValue`, `shared`. The default value is `standard`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `shared`.|
|tenantId |string | The ID of the Microsoft Entra tenant. |
|webUrl|String|A hyperlink that will go to the channel in Microsoft Teams. This is the URL that you get when you right-click a channel in Microsoft Teams and select Get link to channel. This URL should be treated as an opaque blob, and not parsed. Read-only.|
|summary|channelSummary|Contains summary information about the channel, including number of owners, members, guests, and an indicator for members from other tenants. The **s
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
### [chatMessage ](https://docs.microsoft.com/graph/api/resources/chatmessage?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|attachments|chatMessageAttachment collection |References to attached objects like files, tabs, meetings etc.|
|body|itemBody|Plaintext/HTML representation of the content of the chat message. Representation is specified by the contentType inside the body. The content is always in HTML if the chat message contains a chatMessageMention. |
|chatId|string|If the message was sent in a chat, represents the identity of the chat.|
|channelIdentity|channelIdentity|If the message was sent in a channel, represents identity of the channel.|
|createdDateTime|dateTimeOffset|Timestamp of when the chat message was created.|
|deletedDateTime|dateTimeOffset|Read only. Timestamp at which the chat message was deleted, or null if not deleted. |
|etag| string | Read-only. Version number of the chat message. |
|eventDetail|eventMessageDetail|Read-only. If present, represents details of an event that happened in a **chat**, a **channel**, or a **team**, for example, adding new members. For event messages, the **messageType** property will be set to `systemEventMessage`.|
|from|chatMessageFromIdentitySet| Details of the sender of the chat message. Can only be set during migration.|
|id|String| Read-only. Unique ID of the message. IDs are unique within a chat/channel/reply-to-message, but might be duplicated in other chats/channels/reply-to-messages. |
|importance|string | The importance of the chat message. The possible values are: `normal`, `high`, `urgent`.|
|lastModifiedDateTime|dateTimeOffset|Read only. Timestamp when the chat message is created (initial setting) or modified, including when a reaction is added or removed. |
|lastEditedDateTime|dateTimeOffset|Read only. Timestamp when edits to the chat message were made. Triggers an "Edited" flag in the Teams UI. If no edits are made the value is `null`.|
|locale|string|Locale of the chat message set by the client. Always set to `en-us`.|
|mentions|chatMessageMention collection| List of entities mentioned in the chat message. Supported entities are: user, bot, team, and channel.|
|messageHistory|chatMessageHistoryItem collection|List of activity history of a message item, including modification time and actions, such as reactionAdded, reactionRemoved, or reaction changes, on the message.
|messageType|chatMessageType|The type of chat message. The possible values are: `message`, `chatEvent`, `typing`, `unknownFutureValue`, `systemEventMessage`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `systemEventMessage`.|
|policyViolation | chatMessagePolicyViolation |Defines the properties of a policy violation set by a data loss prevention (DLP) application.|
|reactions| chatMessageReaction collection | Reactions for this chat message (for example, Like).|
|replyToId| string | Read-only. ID of the parent chat message or root chat message of the thread. (Only applies to chat messages in channels, not chats.) |
|subject|string| The subject of the chat message, in plaintext.|
|summary|string| Summary text of the chat message that could be used for push notifications and summary views or fall back views. Only applies to channel chat messages, not chat messages in a chat. |
|webUrl|string|Read-only. Link to the message in Microsoft Teams.|
### [conversationMember ](https://docs.microsoft.com/graph/api/resources/conversationmember?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|displayName| string | The display name of the user. |
|id|String| Read-only. Unique ID of the user.|
|roles| string collection | The roles for that user. This property contains additional qualifiers only when relevant - for example, if the member has `owner` privileges, the **roles** property contains `owner` as one of the values. Similarly, if the member is an in-tenant guest, the **roles** property contains `guest` as one of the values. A basic member should not have any values specified in the **roles** property. An Out-of-tenant external member is assigned the `owner` role.|
|visibleHistoryStartDateTime| DateTimeOffset | The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat. |
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
### [teamsAsyncOperation ](https://docs.microsoft.com/graph/api/resources/teamsasyncoperation?view=graph-rest-1.0&tabs=http)
| Property | Type	| Description |
|:---------------|:--------|:----------|
|attemptsCount|Int32|Number of times the operation was attempted before being marked successful or failed.|
|createdDateTime|DateTimeOffset |Time when the operation was created.|
|error|operationError|Any error that causes the async operation to fail.|
|id|string |Unique operation ID.|
|lastActionDateTime|DateTimeOffset |Time when the async operation was last updated.|
|operationType|teamsAsyncOperationType |Denotes the type of operation described. Possible values are: `invalid`, `cloneTeam`, `archiveTeam`, `unarchiveTeam`, `createTeam`, `unknownFutureValue`, `teamifyGroup`, `createChannel`, `archiveChannel`, `unarchiveChannel`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values in this evolvable enum: `teamifyGroup`, `createChannel`, `archiveChannel`, `unarchiveChannel`. |
|status|teamsAsyncOperationStatus| Operation status.|
|targetResourceId|String |The ID of the object that's created or modified as result of this async operation, typically a team.|
|targetResourceLocation|string|The location of the object that's created or modified as result of this async operation. This URL should be treated as an opaque value and not parsed into its component paths.|
### [teamworkBot ](https://docs.microsoft.com/graph/api/resources/teamworkbot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the bot associated with the specific teamsAppDefinition. This value is usually a GUID.|
