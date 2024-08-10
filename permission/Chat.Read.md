# Chat.Read

> Allows an app to read 1 on 1 or group chats threads, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /chats](https://docs.microsoft.com/graph/api/chat-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-list-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-get-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-list-messages?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /chats/{chat-id}/operations](https://docs.microsoft.com/graph/api/chat-list-operations?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /chats/{chat-id}/operations/{operation-id}](https://docs.microsoft.com/graph/api/teamsasyncoperation-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /chats/{chat-id}/pinnedMessages](https://docs.microsoft.com/graph/api/chat-list-pinnedmessages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{id}/members](https://docs.microsoft.com/graph/api/conversationmember-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}](https://docs.microsoft.com/graph/api/chatmessage-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/hostedContents](https://docs.microsoft.com/graph/api/chatmessage-list-hostedcontents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/hostedContents/{hosted-content-id}](https://docs.microsoft.com/graph/api/chatmessagehostedcontent-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/replies/{reply-id}](https://docs.microsoft.com/graph/api/chatmessage-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/replies/{reply-id}/hostedContents](https://docs.microsoft.com/graph/api/chatmessage-list-hostedcontents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/replies/{reply-id}/hostedContents/{hosted-content-id}](https://docs.microsoft.com/graph/api/chatmessagehostedcontent-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-list-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-get-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /search/query](https://docs.microsoft.com/graph/api/search-query?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f501c180-9344-439a-bca0-6cbf209fd270|
|**Consent Type**|User|
|**Display String**|Read user chat messages|
|**Description**|Allows an app to read 1 on 1 or group chats threads, on behalf of the signed-in user.|
## Resources
### [change-notifications-api-overview](https://docs.microsoft.com/graph/api/resources/change-notifications-api-overview?view=graph-rest-1.0&tabs=http)

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
### [chatMessageHostedContent ](https://docs.microsoft.com/graph/api/resources/chatmessagehostedcontent?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|contentBytes  |Edm.Binary   | Write-only. When posting new chat message hosted content, represents the bytes of the payload and are represented as a base64 encoded string.|
|contentType   |String       | Write-only. When posting new chat message hosted content, represents the type of content, such as image/png.|
|id            |String       | Read-only. Represents the chat message hosted content identifier.|
### [conversationMember ](https://docs.microsoft.com/graph/api/resources/conversationmember?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|displayName| string | The display name of the user. |
|id|String| Read-only. Unique ID of the user.|
|roles| string collection | The roles for that user. This property contains additional qualifiers only when relevant - for example, if the member has `owner` privileges, the **roles** property contains `owner` as one of the values. Similarly, if the member is an in-tenant guest, the **roles** property contains `guest` as one of the values. A basic member should not have any values specified in the **roles** property. An Out-of-tenant external member is assigned the `owner` role.|
|visibleHistoryStartDateTime| DateTimeOffset | The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat. |
### [pinnedChatMessageInfo ](https://docs.microsoft.com/graph/api/resources/pinnedchatmessageinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| id| String| The ID of the chatMessage. Read-only. |
### [search-api-overview](https://docs.microsoft.com/graph/api/resources/search-api-overview?view=graph-rest-1.0&tabs=http)

### [searchRequest ](https://docs.microsoft.com/graph/api/resources/searchrequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description| 
|:-------------|:------------|:------------|
|aggregationFilters|String collection|Contains one or more filters to obtain search results aggregated and filtered to a specific value of a field. Optional.<br>Build this filter based on a prior search that aggregates by the same field. From the response of the prior search, identify the searchBucket that filters results to the specific value of the field, use the string in its **aggregationFilterToken** property, and build an aggregation filter string in the format **"{field}:\\"{aggregationFilterToken}\\""**. <br>If multiple values for the same field need to be provided, use the strings in its **aggregationFilterToken** property and build an aggregation filter string in the format **"{field}:or(\\"{aggregationFilterToken1}\\",\\"{aggregationFilterToken2}\\")"**. <br>For example, searching and aggregating drive items by file type returns a **searchBucket** for the file type `docx` in the response. You can conveniently use the **aggregationFilterToken** returned for this **searchBucket** in a subsequent search query and filter matches down to drive items of the `docx` file type. Example 1 and example 2 show the actual requests and responses.|
|aggregations|aggregationOption collection|Specifies aggregations (also known as refiners) to be returned alongside search results. Optional.|
|collapseProperties|collapseProperty collection|Contains the ordered collection of fields and limit to collapse results. Optional.|
|contentSources|String collection|Contains the connection to be targeted.|
|enableTopResults|Boolean|This triggers hybrid sort for messages : the first 3 messages are the most relevant. This property is only applicable to entityType=`message`. Optional.|
|entityTypes|entityType collection| One or more types of resources expected in the response. Possible values are: `event`, `message`, `driveItem`, `externalItem`, `site`, `list`, `listItem`, `drive`, `chatMessage`, `person`, `acronym`, `bookmark`.  Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `chatMessage`, `person`, `acronym`, `bookmark`. See known limitations for those combinations of two or more entity types that are supported in the same search request. Required.|
|fields|String collection |Contains the fields to be returned for each resource object specified in **entityTypes**, allowing customization of the fields returned by default; otherwise, including additional fields such as custom managed properties from SharePoint and OneDrive, or custom fields in **externalItem** from the content that Microsoft Graph connectors bring in. The **fields** property can use the semantic labels applied to properties. For example, if a property is labeled as title, you can retrieve it using the following syntax: `label_title`. Optional.|
|from|Int32|Specifies the offset for the search results. Offset 0 returns the very first result. Optional.|
|query|searchQuery|Contains the query terms. Required.|
|queryAlterationOptions|searchAlterationOptions|Query alteration options formatted in a JSON blob that contains two optional flags related to spelling correction. Optional. |
|region|String|The geographic location for the search. Required for searches that use application permissions. For details, see Get the region value. |
|resultTemplateOptions|resultTemplateOption collection|Provides the search result template options to render search results from connectors.|
|sharePointOneDriveOptions|sharePointOneDriveOptions|Indicates the kind of contents to be searched when a search is performed using application permissions. Optional.|
|size|Int32|The size of the page to be retrieved. The maximum value is 500. Optional.|
|sortProperties|sortProperty collection|Contains the ordered collection of fields and direction to sort results. There can be at most 5 sort properties in the collection. Optional.|
### [searchResponse ](https://docs.microsoft.com/graph/api/resources/searchresponse?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|hitsContainers|searchHitsContainer collection|A collection of search results.|
|queryAlterationResponse|alterationResponse|Provides information related to spelling corrections in the alteration response.|
|resultTemplates|resultTemplate collection|A dictionary of **resultTemplateIds** and associated values, which include the name and JSON schema of the result templates.|
|searchTerms|String collection|Contains the search terms sent in the initial search query.|
### [team ](https://docs.microsoft.com/graph/api/resources/team?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| id | string | The unique identifier of the team. The group has the same ID as the team. This property is read-only, and is inherited from the base entity type. |
|classification|string| An optional label. Typically describes the data or business sensitivity of the team. Must match one of a pre-configured set in the tenant's directory. |
|classSettings|teamClassSettings |Configure settings of a class. Available only when the team represents a class.|
|createdDateTime|dateTimeOffset|Timestamp at which the team was created.|
|description|string| An optional description for the team. Maximum length: 1024 characters. |
|displayName|string| The name of the team. |
|funSettings|teamFunSettings |Settings to configure use of Giphy, memes, and stickers in the team.|
|guestSettings|teamGuestSettings |Settings to configure whether guests can create, update, or delete channels in the team.|
|internalId | string | A unique ID for the team that has been used in a few places such as the audit log/Office 365 Management Activity API. |
|isArchived|Boolean|Whether this team is in read-only mode. |
|memberSettings|teamMemberSettings |Settings to configure whether members can perform certain actions, for example, create channels and add bots, in the team.|
|messagingSettings|teamMessagingSettings |Settings to configure messaging and mentions in the team.|
|specialization|teamSpecialization| Optional. Indicates whether the team is intended for a particular use case.  Each team specialization has access to unique behaviors and experiences targeted to its use case. |
|summary|teamSummary| Contains summary information about the team, including number of owners, members, and guests. |
|tenantId |string | The ID of the Microsoft Entra tenant. |
|visibility|teamVisibilityType| The visibility of the group and team. Defaults to Public. |
|webUrl|string (readonly) | A hyperlink that will go to the team in the Microsoft Teams client. This is the URL that you get when you right-click a team in the Microsoft Teams client and select **G
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
