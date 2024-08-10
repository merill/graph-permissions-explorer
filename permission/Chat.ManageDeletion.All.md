# Chat.ManageDeletion.All

> Allows the app to delete and recover deleted chats, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teamwork/deletedChats/{deleted-chat-id}](https://docs.microsoft.com/graph/api/deletedchat-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /teamwork/deletedChats/{deletedChatId}/undoDelete](https://docs.microsoft.com/graph/api/deletedchat-undodelete?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|bb64e6fc-6b6d-4752-aea0-dd922dbba588|
|**Consent Type**|Admin|
|**Display String**|Delete and recover deleted chats|
|**Description**|Allows the app to delete and recover deleted chats, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|9c7abde0-eacd-4319-bf9e-35994b1a1717|
|**Display String**|Delete and recover deleted chats|
|**Description**|Allows the app to delete and recover deleted chats, without a signed-in user.|
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
### [deletedChat ](https://docs.microsoft.com/graph/api/resources/deletedchat?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of a deleted chat. Inherited from entity.|
