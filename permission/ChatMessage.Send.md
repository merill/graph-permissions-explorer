# ChatMessage.Send

> Allows an app to send one-to-one and group chat messages in Microsoft Teams, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[POST /chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-post-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chat-Id}/pinnedMessages](https://docs.microsoft.com/graph/api/chat-post-pinnedmessages?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}/setReaction](https://docs.microsoft.com/graph/api/chatmessage-setreaction?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}/unsetReaction](https://docs.microsoft.com/graph/api/chatmessage-unsetreaction?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamsId}/channels/{channelId}/messages/{chatMessageId}/setReaction](https://docs.microsoft.com/graph/api/chatmessage-setreaction?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamsId}/channels/{channelId}/messages/{chatMessageId}/unsetReaction](https://docs.microsoft.com/graph/api/chatmessage-unsetreaction?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|116b7235-7cc6-461e-b163-8e55691d839e|
|**Consent Type**|User|
|**Display String**|Send user chat messages|
|**Description**|Allows an app to send one-to-one and group chat messages in Microsoft Teams, on behalf of the signed-in user.|
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
### [pinnedChatMessageInfo ](https://docs.microsoft.com/graph/api/resources/pinnedchatmessageinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| id| String| The ID of the chatMessage. Read-only. |
