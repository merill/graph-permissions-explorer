# Mail.Send

> Allows the app to send mail as users in the organization. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[POST /me/mailFolders/{id}/messages/{id}/forward](https://docs.microsoft.com/graph/api/message-forward?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/mailFolders/{id}/messages/{id}/reply](https://docs.microsoft.com/graph/api/message-reply?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/mailFolders/{id}/messages/{id}/replyAll](https://docs.microsoft.com/graph/api/message-replyall?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/messages/{id}/forward](https://docs.microsoft.com/graph/api/message-forward?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/messages/{id}/reply](https://docs.microsoft.com/graph/api/message-reply?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/messages/{id}/send](https://docs.microsoft.com/graph/api/message-send?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/sendMail](https://docs.microsoft.com/graph/api/user-sendmail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward](https://docs.microsoft.com/graph/api/message-forward?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/reply](https://docs.microsoft.com/graph/api/message-reply?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/replyAll](https://docs.microsoft.com/graph/api/message-replyall?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/messages/{id}/forward](https://docs.microsoft.com/graph/api/message-forward?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/messages/{id}/reply](https://docs.microsoft.com/graph/api/message-reply?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/messages/{id}/replyAll](https://docs.microsoft.com/graph/api/message-replyall?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/messages/{id}/send](https://docs.microsoft.com/graph/api/message-send?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{id | userPrincipalName}/messages/{id}/unsubscribe](https://docs.microsoft.com/graph/api/message-unsubscribe?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/sendMail](https://docs.microsoft.com/graph/api/user-sendmail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/me/messages/{id}/replyAll](https://docs.microsoft.com/graph/api/message-replyall?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|e383f46e-2787-4529-855e-0e479a3ffac0|
|**Consent Type**|User|
|**Display String**|Send mail as a user |
|**Description**|Allows the app to send mail as users in the organization. |
## Application Permission
|||
|-|-|
|**Id**|b633e1c5-b582-4048-a93e-9f11b44c7e96|
|**Display String**|Send mail as any user|
|**Description**|Allows the app to send mail as any user without a signed-in user.|
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
### [fileAttachment ](https://docs.microsoft.com/graph/api/resources/fileattachment?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contentBytes|Edm.Binary|The base64-encoded contents of the file.|
|contentId|String|The ID of the attachment in the Exchange store.|
|contentLocation|String|Don't use this property as it isn't supported.|
|contentType|String|The content type of the attachment.|
|id|String|The attachment ID.|
|isInline|Boolean|Set to `true` if the attachment is an inline attachment.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the attachment was last modified.|
|name|String|The name representing the text that is displayed below the icon representing the embedded attachment and doesn't need to be the actual file name.|
|size|Int32|The size in bytes of the attachment.|
### [mention ](https://docs.microsoft.com/graph/api/resources/mention?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|application | String | The name of the application where the mention is created. Optional. Not used and defaulted as null for **message**. |
|clientReference | String | A unique identifier that represents a parent of the resource instance. Optional. Not used and defaulted as null for **message**. |
|createdBy  | emailAddress | The email information of the user who made the mention. |
|createdDateTime  |DateTimeOffset |The date and time that the mention is created on the client. |
|deepLink | String | A deep web link to the context of the mention in the resource instance. Optional. Not used and defaulted as null for **message**. |
|id | String| The unique identifier of a mention in a resource instance.|
|mentioned | emailAddress | The email information of the mentioned person. Required. |
|mentionText | String | Optional. Not used and defaulted as null for **message**. To get the mentions in a message, see the **bodyPreview** property of the message instead. |
|serverCreatedDateTime | DateTimeOffset | The date and time that the mention is created on the server. Optional. Not used and defaulted as null for **m
### [message ](https://docs.microsoft.com/graph/api/resources/message?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|bccRecipients|recipient collection|The Bcc: recipients for the message.|
|body|itemBody|The body of the message. It can be in HTML or text format. Find out about safe HTML in a message body.|
|bodyPreview|String|The first 255 characters of the message body. It is in text format.|
|ccRecipients|recipient collection|The Cc: recipients for the message.|
|changeKey|String|The version of the message.|
|conversationId|String|The ID of the conversation the email belongs to.|
|conversationIndex|Edm.Binary|Indicates the position of the message within the conversation.|
|createdDateTime|DateTimeOffset|The date and time the message was created. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|flag|followupFlag|The flag value that indicates the status, start date, due date, or completion date for the message.|
|from|recipient|The owner of the mailbox from which the message is sent. In most cases, this value is the same as the **sender** property, except for sharing or delegation scenarios. The value must correspond to the actual mailbox used. Find out more about setting the from and sender properties of a message.|
|hasAttachments|Boolean|Indicates whether the message has attachments. This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false. To verify the existence of inline attachments, parse the **body** property to look for a `src` attribute, such as `<IMG src="cid:image001.jpg@01D26CD8.6C05F070">`.|
|id|String|Unique identifier for the message. !INCLUDE [outlook-beta-id] Read-only. |
|importance|importance| The importance of the message. The possible values are: `low`, `normal`, and `high`.|
|inferenceClassification | inferenceClassificationType | The classification of the message for the user, based on inferred relevance or importance, or on an explicit override. The possible values are: `focused` or `other`. |
|internetMessageHeaders | internetMessageHeader collection | A collection of message headers defined by RFC5322. The set includes message headers indicating the network path taken by a message from the sender to the recipient. It can also contain custom message headers that hold app data for the message. <br><br> Returned only on applying a `$select` query option. Read-only. |
|internetMessageId |String |The message ID in the format specified by RFC2822. |
|isDeliveryReceiptRequested|Boolean|Indicates whether a read receipt is requested for the message.|
|isDraft|Boolean|Indicates whether the message is a draft. A message is a draft if it hasn't been sent yet.|
|isRead|Boolean|Indicates whether the message has been read.|
|isReadReceiptRequested|Boolean|Indicates whether a read receipt is requested for the message.|
|lastModifiedDateTime|DateTimeOffset|The date and time the message was last changed. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|parentFolderId|String|The unique identifier for the message's parent mailFolder.|
|receivedDateTime|DateTimeOffset|The date and time the message was received. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|replyTo|recipient collection|The email addresses to use when replying.|
|sender|recipient|The account that is actually used to generate the message. In most cases, this value is the same as the **from** property. You can set this property to a different value when sending a message from a shared mailbox, for a shared calendar, or as a delegate. In any case, the value must correspond to the actual mailbox used. Find out more about setting the from and sender properties of a message.|
|sentDateTime|DateTimeOffset|The date and time the message was sent. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|subject|String|The subject of the message.|
|toRecipients|recipient collection|The To: recipients for the message.|
|uniqueBody|itemBody|The part of the body of the message that is unique to the current message. **uniqueBody** is not returned by default but can be retrieved for a given message by use of the `?$select=uniqueBody` query. It can be in HTML or text format.|
|webLink|String|The URL to open the message in Outlook on the web.<br><br>You can append an ispopout argument to the end of the URL to change how the message is displayed. If ispopout is not present or if it is set to 1, then the message is shown in a popout window. If ispopout is set to 0, the browser shows the message in the Outlook on the web review pane.<br><br>The message opens in the browser if you are signed in to your mailbox via Outlook on the web. You are prompted to sign in if you are not already signed in with the browser.<br><br>This URL cannot be accessed from within an iFrame.|
### [recipient ](https://docs.microsoft.com/graph/api/resources/recipient?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|emailAddress|EmailAddress|The recipient's email address.|
