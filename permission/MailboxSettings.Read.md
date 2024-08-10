# MailboxSettings.Read

> Allows the app to the read user's mailbox settings. Does not include permission to send mail.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /me/mailboxSettings](https://docs.microsoft.com/graph/api/user-get-mailboxsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/mailFolders/inbox/messageRules](https://docs.microsoft.com/graph/api/mailfolder-list-messagerules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/mailFolders/inbox/messageRules/{id}](https://docs.microsoft.com/graph/api/messagerule-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/outlook/masterCategories](https://docs.microsoft.com/graph/api/outlookuser-list-mastercategories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/outlook/masterCategories/{id}](https://docs.microsoft.com/graph/api/outlookcategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/mailFolders/inbox/messageRules](https://docs.microsoft.com/graph/api/mailfolder-list-messagerules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/mailFolders/inbox/messageRules/{id}](https://docs.microsoft.com/graph/api/messagerule-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id|userPrincipalName}/mailboxSettings](https://docs.microsoft.com/graph/api/user-get-mailboxsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id|userPrincipalName}/outlook/masterCategories](https://docs.microsoft.com/graph/api/outlookuser-list-mastercategories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id|userPrincipalName}/outlook/masterCategories/{id}](https://docs.microsoft.com/graph/api/outlookcategory-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|87f447af-9fa4-4c32-9dfa-4a57a73d18ce|
|**Consent Type**|User|
|**Display String**|Read user mailbox settings|
|**Description**|Allows the app to the read user's mailbox settings. Does not include permission to send mail.|
## Application Permission
|||
|-|-|
|**Id**|40f97065-369a-49f4-947c-6a255697ae91|
|**Display String**|Read all user mailbox settings|
|**Description**|Allows the app to read user's mailbox settings without a signed-in user. Does not include permission to send mail.|
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
