# ChatMessage.Read.All

> Allows the app to read all one-to-one and group chats messages in Microsoft Teams, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /chats/{chat-id}/pinnedMessages](https://docs.microsoft.com/graph/api/chat-list-pinnedmessages?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|b9bb2381-47a4-46cd-aafb-00cb12f68504|
|**Display String**|Read all chat messages|
|**Description**|Allows the app to read all one-to-one and group chats messages in Microsoft Teams, without a signed-in user.|
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
### [pinnedChatMessageInfo ](https://docs.microsoft.com/graph/api/resources/pinnedchatmessageinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| id| String| The ID of the chatMessage. Read-only. |
