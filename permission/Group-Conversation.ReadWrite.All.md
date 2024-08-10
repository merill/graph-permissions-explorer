# Group-Conversation.ReadWrite.All

> Allows the app to read and write group conversations that the signed-in user has access to.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/conversationthread-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{groupId}/conversations/{conversationId}/threads/{threadId}/posts](https://docs.microsoft.com/graph/api/conversationthread-list-posts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{groupId}/threads/{threadId}/posts](https://docs.microsoft.com/graph/api/conversationthread-list-posts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/conversations](https://docs.microsoft.com/graph/api/group-list-conversations?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /groups/{id}/conversations/{id}](https://docs.microsoft.com/graph/api/conversation-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /groups/{id}/conversations/{id}/threads](https://docs.microsoft.com/graph/api/conversation-list-threads?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/conversations/{id}/threads/{id}](https://docs.microsoft.com/graph/api/conversationthread-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/conversations/{id}/threads/{id}/posts/{id}](https://docs.microsoft.com/graph/api/post-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments](https://docs.microsoft.com/graph/api/post-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/threads](https://docs.microsoft.com/graph/api/group-list-threads?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/threads/{id}](https://docs.microsoft.com/graph/api/conversationthread-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/threads/{id}/posts/{id}](https://docs.microsoft.com/graph/api/post-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{id}/threads/{id}/posts/{id}/attachments](https://docs.microsoft.com/graph/api/post-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/{group id}/conversations/{conversation id}/threads/{thread id}](https://docs.microsoft.com/graph/api/conversationthread-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/{group id}/threads/{thread id}](https://docs.microsoft.com/graph/api/conversationthread-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/{id}/threads/{id}](https://docs.microsoft.com/graph/api/group-update-thread?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{id}/conversations/{id}/threads](https://docs.microsoft.com/graph/api/conversation-post-threads?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/forward](https://docs.microsoft.com/graph/api/post-forward?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/threads/{id}/posts/{id}/forward](https://docs.microsoft.com/graph/api/post-forward?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|302bcbb5-855a-4e49-ae20-94a331b0281e|
|**Consent Type**|Admin|
|**Display String**|Read and write group conversations|
|**Description**|Allows the app to read and write group conversations that the signed-in user has access to.|
## Application Permission
|||
|-|-|
|**Id**|6679c91b-820a-4900-ab47-e97b197a89c4|
|**Display String**|Read and write all group conversations|
|**Description**|Allows the app to read and write conversations of the groups this app has access to without a signed-in user.|
## Resources
### [attachment ](https://docs.microsoft.com/graph/api/resources/attachment?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contentType|String|The MIME type.|
|id|String| Read-only.|
|isInline|Boolean|`true` if the attachment is an inline attachment; otherwise, `false`.|
|lastModifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|name|String|The attachment's file name.|
|size|Int32|The length of the attachment in bytes.|
### [conversation ](https://docs.microsoft.com/graph/api/resources/conversation?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|hasAttachments|Boolean|Indicates whether any of the posts within this Conversation has at least one attachment. Supports `$filter` (`eq`, `ne`) and `$search`.|
|id|String|The conversations's unique identifier. Read-only.|
|lastDeliveredDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|preview|String|A short summary from the body of the latest post in this conversation. Supports `$filter` (`eq`, `ne`, `le`, `ge`).|
|topic|String|The topic of the conversation. This property can be set when the conversation is created, but it cannot be updated.|
|uniqueSenders|String collection|All the users that sent a message to this Conversation.|
### [conversationThread ](https://docs.microsoft.com/graph/api/resources/conversationthread?view=graph-rest-1.0&tabs=http)
| Property              | Type                                 | Description                                                                                                                                                                                      |
|:----------------------|:-------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ccRecipients          | recipient collection | The Cc: recipients for the thread. <br/><br/>Returned only on `$select`.                                                                                                                                                               |
| hasAttachments        | Boolean                              | Indicates whether any of the posts within this thread has at least one attachment. <br/><br/>Returned by default.                                                                                                              |
| id                    | String                               | Read-only. <br/><br/>Returned by default.                                                                                                                                                                                      |
| isLocked              | Boolean                              | Indicates if the thread is locked. <br/><br/>Returned by default.                                                                                                                                                              |
| lastDeliveredDateTime | DateTimeOffset                       | The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.<br/><br/>Returned by default. |
| preview               | String                               | A short summary from the body of the latest post in this conversation. <br/><br/>Returned by default.                                                                                                                           |
| topic                 | String                               | The topic of the conversation. This property can be set when the conversation is created, but it cannot be updated. <br/><br/>Returned by default.                                                                              |
| toRecipients          | recipient collection | The To: recipients for the thread. <br/><br/>Returned only on `$select`.                                                                                                                                                              |
| uniqueSenders         | String collection                    | All the users that sent a message to this thread. <br/><br/>Returned by default.                                                                                                                                               |
### [post ](https://docs.microsoft.com/graph/api/resources/post?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|body|itemBody|The contents of the post. This is a default property. This property can be null.|
|categories|String collection|The categories associated with the post.|
|changeKey|String|Identifies the version of the post. Every time the post is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object.|
|conversationId|String|Unique ID of the conversation. Read-only.|
|conversationThreadId|String|Unique ID of the conversation thread. Read-only.|
|createdDateTime|DateTimeOffset|Specifies when the post was created. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|from|recipient|Used in delegate access scenarios. Indicates who posted the message on behalf of another user. This is a default property.|
|hasAttachments|Boolean|Indicates whether the post has at least one attachment. This is a default property.|
|id|String| Read-only.|
|lastModifiedDateTime|DateTimeOffset|Specifies when the post was last modified. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|newParticipants|recipient collection|Conversation participants that were added to the thread as part of this post.|
|receivedDateTime|DateTimeOffset|Specifies when the post was received. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|sender|recipient|Contains the address of the sender. The value of Sender is assumed to be the address of the authenticated user in the case when Sender is not specified. This is a default property.|
### [recipient ](https://docs.microsoft.com/graph/api/resources/recipient?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|emailAddress|EmailAddress|The recipient's email address.|
