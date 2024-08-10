# MailboxSettings.ReadWrite

> Allows the app to create, read, update, and delete user's mailbox settings. Does not include permission to send mail.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /me/mailFolders/inbox/messageRules/{id}](https://docs.microsoft.com/graph/api/messagerule-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/outlook/masterCategories/{id}](https://docs.microsoft.com/graph/api/outlookcategory-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/mailFolders/inbox/messageRules/{id}](https://docs.microsoft.com/graph/api/messagerule-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id|userPrincipalName}/outlook/masterCategories/{id}](https://docs.microsoft.com/graph/api/outlookcategory-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/mailboxSettings](https://docs.microsoft.com/graph/api/user-get-mailboxsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id|userPrincipalName}/mailboxSettings](https://docs.microsoft.com/graph/api/user-get-mailboxsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/mailboxSettings](https://docs.microsoft.com/graph/api/user-update-mailboxsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/mailFolders/inbox/messageRules/{id}](https://docs.microsoft.com/graph/api/messagerule-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/outlook/masterCategories/{id}](https://docs.microsoft.com/graph/api/outlookcategory-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/mailFolders/inbox/messageRules/{id}](https://docs.microsoft.com/graph/api/messagerule-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id|userPrincipalName}/mailboxSettings](https://docs.microsoft.com/graph/api/user-update-mailboxsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id|userPrincipalName}/outlook/masterCategories/{id}](https://docs.microsoft.com/graph/api/outlookcategory-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/mailFolders/inbox/messageRules](https://docs.microsoft.com/graph/api/mailfolder-post-messagerules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/outlook/masterCategories](https://docs.microsoft.com/graph/api/outlookuser-post-mastercategories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/mailFolders/inbox/messageRules](https://docs.microsoft.com/graph/api/mailfolder-post-messagerules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id|userPrincipalName}/outlook/masterCategories](https://docs.microsoft.com/graph/api/outlookuser-post-mastercategories?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|818c620a-27a9-40bd-a6a5-d96f7d610b4b|
|**Consent Type**|User|
|**Display String**|Read and write user mailbox settings|
|**Description**|Allows the app to create, read, update, and delete user's mailbox settings. Does not include permission to send mail.|
## Application Permission
|||
|-|-|
|**Id**|6931bccd-447a-43d1-b442-00a195474933|
|**Display String**|Read and write all user mailbox settings|
|**Description**|Allows the app to create, read, update, and delete user's mailbox settings without a signed-in user. Does not include permission to send mail.|
## Resources
### [automaticRepliesSetting ](https://docs.microsoft.com/graph/api/resources/automaticrepliessetting?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|externalAudience|externalAudienceScope| The set of audience external to the signed-in user's organization who will receive the **ExternalReplyMessage**, if **Status** is `AlwaysEnabled` or `Scheduled`. The possible values are: `none`, `contactsOnly`, `all`.|
|externalReplyMessage|string|The automatic reply to send to the specified external audience, if **Status** is `AlwaysEnabled` or `Scheduled`.|
|internalReplyMessage|string|The automatic reply to send to the audience internal to the signed-in user's organization, if **Status** is `AlwaysEnabled` or `Scheduled`. |
|scheduledEndDateTime|dateTimeTimeZone|The date and time that automatic replies are set to end, if **Status** is set to `Scheduled`. |
|scheduledStartDateTime|dateTimeTimeZone|The date and time that automatic replies are set to begin, if **Status** is set to `Scheduled`.|
|status|automaticRepliesStatus|Configurations status for automatic replies. The possible values are: `disabled`, `alwaysEnabled`, `scheduled`.|
### [customTimeZone ](https://docs.microsoft.com/graph/api/resources/customtimezone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| bias | Edm.Int32 | The time offset of the time zone from Coordinated Universal Time (UTC). This value is in minutes. Time zones that are ahead of UTC have a positive offset; time zones that are behind UTC have a negative offset.|
| daylightOffset | daylightTimeZoneOffset | Specifies when the time zone switches from standard time to daylight saving time. |
| name | string | The name of the custom time zone. |
| standardOffset | standardTimeZoneOffset | Specifies when the time zone switches from daylight saving time to standard time. |
### [localeInfo ](https://docs.microsoft.com/graph/api/resources/localeinfo?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|displayName|string|A name representing the user's locale in natural language, for example, "English (United States)".|
|locale|string|A locale representation for the user, which includes the user's preferred language and country/region. For example, "en-us". The language component follows 2-letter codes as defined in ISO 639-1, and the country component follows 2-letter codes as defined in ISO 3166-1 alpha-2.|
### [mailboxSettings ](https://docs.microsoft.com/graph/api/resources/mailboxsettings?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|archiveFolder|string|Folder ID of an archive folder for the user.|
|automaticRepliesSetting|automaticRepliesSetting|Configuration settings to automatically notify the sender of an incoming email with a message from the signed-in user.|
|dateFormat|string|The date format for the user's mailbox.|
|delegateMeetingMessageDeliveryOptions|delegateMeetingMessageDeliveryOptions| If the user has a calendar delegate, this specifies whether the delegate, mailbox owner, or both receive meeting messages and meeting responses. Possible values are: `sendToDelegateAndInformationToPrincipal`, `sendToDelegateAndPrincipal`, `sendToDelegateOnly`.|
|language|localeInfo|The locale information for the user, including the preferred language and country/region.|
|timeFormat|string|The time format for the user's mailbox.|
|timeZone|string|The default time zone for the user's mailbox.|
|userPurpose|userPurpose|The purpose of the mailbox. Differentiates a mailbox for a single user from a shared mailbox and equipment mailbox in Exchange Online. Possible values are: `user`, `linked`, `shared`, `room`, `equipment`, `others`, `unknownFutureValue`. Read-only. |
|workingHours|workingHours|The days of the week and hours in a specific time zone that the user works.|
### [messageRule ](https://docs.microsoft.com/graph/api/resources/messagerule?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| actions | messageRuleActions | Actions to be taken on a message when the corresponding conditions are fulfilled. |
| conditions | messageRulePredicates | Conditions that when fulfilled trigger the corresponding actions for that rule. |
| displayName | String | The display name of the rule. |
| exceptions | messageRulePredicates | Exception conditions for the rule. |
| hasError | Boolean | Indicates whether the rule is in an error condition. Read-only. |
| id |String|The unique identifier of the rule. Read-only.|
| isEnabled | Boolean | Indicates whether the rule is enabled to be applied to messages. |
| isReadOnly | Boolean | Indicates if the rule is read-only and cannot be modified or deleted by the rules REST API. |
| sequence | Int32 | Indicates the order in which the rule is executed, among other rules. |
### [messageRuleActions ](https://docs.microsoft.com/graph/api/resources/messageruleactions?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| assignCategories | String collection | A list of categories to be assigned to a message. |
| copyToFolder | String | The ID of a folder that a message is to be copied to. |
| delete | Boolean | Indicates whether a message should be moved to the Deleted Items folder. |
| forwardAsAttachmentTo | recipient collection | The email addresses of the recipients to which a message should be forwarded as an attachment. |
| forwardTo | recipient collection | The email addresses of the recipients to which a message should be forwarded. |
| markAsRead | Boolean | Indicates whether a message should be marked as read. |
| markImportance | importance | Sets the importance of the message, which can be: `low`, `normal`, `high`. |
| moveToFolder |  String| The ID of the folder that a message will be moved to. |
| permanentDelete | Boolean | Indicates whether a message should be permanently deleted and not saved to the Deleted Items folder. |
| redirectTo | recipient collection | The email addresses to which a message should be redirected. |
| stopProcessingRules | Boolean | Indicates whether subsequent rules should be evaluated. |
### [messageRulePredicates ](https://docs.microsoft.com/graph/api/resources/messagerulepredicates?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| bodyContains | Collection(String) | Represents the strings that should appear in the body of an incoming message in order for the condition or exception to apply. |
| bodyOrSubjectContains | Collection(String) | Represents the strings that should appear in the body or subject of an incoming message in order for the condition or exception to apply. |
| categories | Collection(String) | Represents the categories that an incoming message should be labeled with in order for the condition or exception to apply. |
| fromAddresses | Collection(recipient) | Represents the specific sender email addresses of an incoming message in order for the condition or exception to apply. |
| hasAttachments | Boolean | Indicates whether an incoming message must have attachments in order for the condition or exception to apply. |
| headerContains | Collection(String) | Represents the strings that appear in the headers of an incoming message in order for the condition or exception to apply. |
| importance | importance | The importance that is stamped on an incoming message in order for the condition or exception to apply: `low`, `normal`, `high`. |
| isApprovalRequest | Boolean | Indicates whether an incoming message must be an approval request in order for the condition or exception to apply. |
| isAutomaticForward | Boolean | Indicates whether an incoming message must be automatically forwarded in order for the condition or exception to apply. |
| isAutomaticReply | Boolean | Indicates whether an incoming message must be an auto reply in order for the condition or exception to apply. |
| isEncrypted | Boolean | Indicates whether an incoming message must be encrypted in order for the condition or exception to apply. |
| isMeetingRequest | Boolean | Indicates whether an incoming message must be a meeting request in order for the condition or exception to apply. |
| isMeetingResponse | Boolean | Indicates whether an incoming message must be a meeting response in order for the condition or exception to apply. |
| isNonDeliveryReport | Boolean | Indicates whether an incoming message must be a non-delivery report in order for the condition or exception to apply. |
| isPermissionControlled | Boolean | Indicates whether an incoming message must be permission controlled (RMS-protected) in order for the condition or exception to apply. |
| isReadReceipt | Boolean | Indicates whether an incoming message must be a read receipt in order for the condition or exception to apply. |
| isSigned | Boolean | Indicates whether an incoming message must be S/MIME-signed in order for the condition or exception to apply. |
| isVoicemail | Boolean | Indicates whether an incoming message must be a voice mail in order for the condition or exception to apply. |
| messageActionFlag | messageActionFlag  | Represents the flag-for-action value that appears on an incoming message in order for the condition or exception to apply. The possible values are: `any`, `call`, `doNotForward`, `followUp`, `fyi`, `forward`, `noResponseNecessary`, `read`, `reply`, `replyToAll`, `review`. |
| notSentToMe | Boolean | Indicates whether the owner of the mailbox must not be a recipient of an incoming message in order for the condition or exception to apply. |
| recipientContains | Collection(String) | Represents the strings that appear in either the **toRecipients** or **ccRecipients** properties of an incoming message in order for the condition or exception to apply. |
| senderContains | Collection(String) | Represents the strings that appear in the **from** property of an incoming message in order for the condition or exception to apply. |
| sensitivity | sensitivity | Represents the sensitivity level that must be stamped on an incoming message in order for the condition or exception to apply. The possible values are: `normal`, `personal`, `private`, `confidential`. |
| sentCcMe | Boolean | Indicates whether the owner of the mailbox must be in the **ccRecipients** property of an incoming message in order for the condition or exception to apply. |
| sentOnlyToMe | Boolean | Indicates whether the owner of the mailbox must be the only recipient in an incoming message in order for the condition or exception to apply. |
| sentToAddresses | Collection(recipient) | Represents the email addresses that an incoming message must have been sent to in order for the condition or exception to apply. |
| sentToMe | Boolean | Indicates whether the owner of the mailbox must be in the **toRecipients** property of an incoming message in order for the condition or exception to apply. |
| sentToOrCcMe | Boolean | Indicates whether the owner of the mailbox must be in either a **toRecipients** or **ccRecipients** property of an incoming message in order for the condition or exception to apply. |
| subjectContains | Collection(String) | Represents the strings that appear in the subject of an incoming message in order for the condition or exception to apply. |
| withinSizeRange | sizeRange | Represents the minimum and maximum sizes (in kilobytes) that an incoming message must fall in between in order for the condition or exception to apply. |
### [outlookCategory ](https://docs.microsoft.com/graph/api/resources/outlookcategory?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|color|categoryColor|A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. For more details, see the following note. |
|displayName|String|A unique name that identifies a category in the user's mailbox. After a category is created, the name cannot be changed. Read-only.|
### [workingHours ](https://docs.microsoft.com/graph/api/resources/workinghours?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| daysOfWeek | dayOfWeek collection | The days of the week on which the user works. |
| endTime | Edm.TimeOfDay | The time of the day that the user stops working. |
| startTime | Edm.TimeOfDay | The time of the day that the user starts working. |
| timeZone | timeZoneBase | The time zone to which the working hours apply. |
