# Mail.ReadBasic

> Allows the app to read email in the signed-in user's mailbox except body, previewBody, attachments and any extended properties.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[](https://docs.microsoft.com/graph/api/eventmessage-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders](https://docs.microsoft.com/graph/api/user-list-mailfolders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders/{id}](https://docs.microsoft.com/graph/api/mailfolder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders/{id}/childFolders](https://docs.microsoft.com/graph/api/mailfolder-list-childfolders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders/{id}/messages](https://docs.microsoft.com/graph/api/mailfolder-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders/{id}/messages/{id}](https://docs.microsoft.com/graph/api/message-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders/{id}/messages/delta](https://docs.microsoft.com/graph/api/message-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/mailFolders/delta](https://docs.microsoft.com/graph/api/mailfolder-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/messages](https://docs.microsoft.com/graph/api/user-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/messages/{id}](https://docs.microsoft.com/graph/api/message-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/mailFolders](https://docs.microsoft.com/graph/api/user-list-mailfolders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/mailFolders/{id}](https://docs.microsoft.com/graph/api/mailfolder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/mailFolders/{id}/childFolders](https://docs.microsoft.com/graph/api/mailfolder-list-childfolders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/mailFolders/{id}/messages](https://docs.microsoft.com/graph/api/mailfolder-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}](https://docs.microsoft.com/graph/api/message-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/messages](https://docs.microsoft.com/graph/api/user-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/messages/{id}](https://docs.microsoft.com/graph/api/message-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/mailFolders/{id}/messages/delta](https://docs.microsoft.com/graph/api/message-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/mailFolders/delta](https://docs.microsoft.com/graph/api/mailfolder-delta?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|a4b8392a-d8d1-4954-a029-8e668a39a170|
|**Consent Type**|User|
|**Display String**|Read user basic mail|
|**Description**|Allows the app to read email in the signed-in user's mailbox except body, previewBody, attachments and any extended properties.|
## Application Permission
|||
|-|-|
|**Id**|6be147d2-ea4f-4b5a-a3fa-3eab6f3c140a|
|**Display String**|Read basic mail in all mailboxes|
|**Description**|Allows the app to read basic mail properties in all mailboxes without a signed-in user. Includes all properties except body, previewBody, attachments and any extended properties.|
## Resources
### [event ](https://docs.microsoft.com/graph/api/resources/event?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
|allowNewTimeProposals| Boolean | `true` if the meeting organizer allows invitees to propose a new time when responding; otherwise, `false`. Optional. Default is `true`. |
|attendees|Attendee collection|The collection of attendees for the event.|
|body|ItemBody|The body of the message associated with the event. It can be in HTML or text format.|
|bodyPreview|String|The preview of the message associated with the event. It is in text format.|
|categories|String collection|The categories associated with the event. Each category corresponds to the **displayName** property of an outlookCategory defined for the user.|
|changeKey|String|Identifies the version of the event object. Every time the event is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|end|DateTimeTimeZone|The date, time, and time zone that the event ends. By default, the end time is in UTC.|
|hasAttachments|Boolean|Set to true if the event has attachments.|
|hideAttendees|Boolean|When set to `true`, each attendee only sees themselves in the meeting request and meeting **Tracking** list. Default is false.|
|iCalUId|String|A unique identifier for an event across calendars. This ID is different for each occurrence in a recurring series. Read-only.|
|id|String| Unique identifier for the event. !INCLUDE [outlook-beta-id] Case-sensitive and read-only.|
|importance|String|The importance of the event. The possible values are: `low`, `normal`, `high`.|
|isAllDay|Boolean|Set to true if the event lasts all day. If true, regardless of whether it's a single-day or multi-day event, start and end time must be set to midnight and be in the same time zone.|
|isCancelled|Boolean|Set to true if the event has been canceled.|
|isDraft|Boolean|Set to true if the user has updated the meeting in Outlook but has not sent the updates to attendees. Set to false if all changes have been sent, or if the event is an appointment without any attendees.|
|isOnlineMeeting|Boolean| `True` if this event has online meeting information (that is, **onlineMeeting** points to an onlineMeetingInfo resource), `false` otherwise. Default is `false` (**onlineMeeting** is `null`). Optional. <br> After you set **isOnlineMeeting** to `true`, Microsoft Graph initializes **onlineMeeting**. Subsequently Outlook ignores any further changes to **isOnlineMeeting**, and the meeting remains available online. |
|isOrganizer|Boolean|Set to true if the calendar owner (specified by the **owner** property of the calendar) is the organizer of the event (specified by the **organizer** property of the **event**). This also applies if a delegate organized the event on behalf of the owner.|
|isReminderOn|Boolean|Set to true if an alert is set to remind the user of the event.|
|lastModifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|location|Location|The location of the event.|
|locations|Location collection|The locations where the event is held or attended from. The **location** and **locations** properties always correspond with each other. If you update the **location** property, any prior locations in the **locations** collection would be removed and replaced by the new **location** value. |
|onlineMeeting|OnlineMeetingInfo| Details for an attendee to join the meeting online. Default is null. Read-only. <br>After you set the **isOnlineMeeting** and **onlineMeetingProvider** properties to enable a meeting online, Microsoft Graph initializes **onlineMeeting**. When set, the meeting remains available online, and you cannot change the **isOnlineMeeting**, **onlineMeetingProvider**, and **onlneMeeting** properties again.|
|onlineMeetingProvider|onlineMeetingProviderType| Represents the online meeting service provider. By default, **onlineMeetingProvider** is `unknown`. The possible values are `unknown`, `teamsForBusiness`, `skypeForBusiness`, and `skypeForConsumer`. Optional. <br> After you set **onlineMeetingProvider**, Microsoft Graph initializes **onlineMeeting**. Subsequently you cannot change **onlineMeetingProvider** again, and the meeting remains available online. |
|onlineMeetingUrl|String|A URL for an online meeting. The property is set only when an organizer specifies in Outlook that an event is an online meeting such as Skype. Read-only.<br>To access the URL to join an online meeting, use **joinUrl** which is exposed via the **onlineMeeting** property of the **event**. The **onlineMeetingUrl** property will be deprecated in the future. |
|organizer|Recipient|The organizer of the event.|
|originalEndTimeZone|String|The end time zone that was set when the event was created. A value of `tzone://Microsoft/Custom` indicates that a legacy custom time zone was set in desktop Outlook.|
|originalStart|DateTimeOffset|Represents the start time of an event when it is initially created as an occurrence or exception in a recurring series. This property is not returned for events that are single instances. Its date and time information is expressed in ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|originalStartTimeZone|String|The start time zone that was set when the event was created. A value of `tzone://Microsoft/Custom` indicates that a legacy custom time zone was set in desktop Outlook.|
|recurrence|PatternedRecurrence|The recurrence pattern for the event.|
|reminderMinutesBeforeStart|Int32|The number of minutes before the event start time that the reminder alert occurs.|
|responseRequested|Boolean|Default is true, which represents the organizer would like an invitee to send a response to the event.|
|responseStatus|ResponseStatus|Indicates the type of response sent in response to an event message.|
|sensitivity|String| Possible values are: `normal`, `personal`, `private`, `confidential`.|
|seriesMasterId|String|The ID for the recurring series master item, if this event is part of a recurring series.|
|showAs|String|The status to show. Possible values are: `free`, `tentative`, `busy`, `oof`, `workingElsewhere`, `unknown`.|
|start|DateTimeTimeZone|The start date, time, and time zone of the event. By default, the start time is in UTC.|
|subject|String|The text of the event's subject line.|
|transactionId|String|A custom identifier specified by a client app for the server to avoid redundant POST operations in case of client retries to create the same event. This is useful when low network connectivity causes the client to time out before receiving a response from the server for the client's prior create-event request. After you set **transactionId** when creating an event, you cannot change **transactionId** in a subsequent update. This property is only returned in a response payload if an app has set it. Optional.|
|type|String|The event type. Possible values are: `singleInstance`, `occurrence`, `exception`, `seriesMaster`. Read-only|
|webLink|String|The URL to open the event in Outlook on the web.<br/><br/>Outlook on the web opens the event in the browser if you are signed in to your mailbox. Otherwise, Outlook on the web prompts you to sign in.<br/><br/>This URL cannot be accessed from within an iFrame.|
### [eventMessage ](https://docs.microsoft.com/graph/api/resources/eventmessage?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|bccRecipients|recipient collection|The Bcc: recipients for the message.|
|body|itemBody|The body of the message. It can be in HTML or text format.|
|bodyPreview|String|The first 255 characters of the message body. It is in text format.|
|categories|String collection|The categories associated with the message.|
|ccRecipients|recipient collection|The Cc: recipients for the message.|
|changeKey|String|The version of the message.|
|conversationId|String|The ID of the conversation the email belongs to.|
|conversationIndex|Edm.Binary|Indicates the position of the message within the conversation.|
|createdDateTime|DateTimeOffset|The date and time the message was created.|
|flag|followupFlag|The flag value that indicates the status, start date, due date, or completion date for the message.|
|from|recipient|The owner of the mailbox from which the message is sent. In most cases, this value is the same as the **sender** property, except for sharing or delegation scenarios. The value must correspond to the actual mailbox used. Find out more about setting the from and sender properties of a message.|
|hasAttachments|Boolean|Indicates whether the message has attachments.|
|id|String|Unique identifier for the event message. !INCLUDE [outlook-beta-id] Read-only. |
|importance|String| The importance of the message: `low`, `normal`, `high`.|
|inferenceClassification|String| The possible values are: `focused`, `other`.|
|internetMessageHeaders | internetMessageHeader collection | The collection of message headers, defined by RFC5322, that provide details of the network path taken by a message from the sender to the recipient. Read-only.|
|internetMessageId |String |The message ID in the format specified by RFC2822. |
|isDelegated|Boolean|True if this meeting request is accessible to a delegate, false otherwise. Default is false.|
|isDeliveryReceiptRequested|Boolean|Indicates whether a read receipt is requested for the message.|
|isDraft|Boolean|Indicates whether the message is a draft. A message is a draft if it hasn't been sent yet.|
|isRead|Boolean|Indicates whether the message has been read.|
|isReadReceiptRequested|Boolean|Indicates whether a read receipt is requested for the message.|
|lastModifiedDateTime|DateTimeOffset|The date and time the message was last changed.|
|meetingMessageType|meetingMessageType| The type of event message: `none`, `meetingRequest`, `meetingCancelled`, `meetingAccepted`, `meetingTenativelyAccepted`, `meetingDeclined`.|
|parentFolderId|String|The unique identifier for the message's parent mailFolder.|
|receivedDateTime|DateTimeOffset|The date and time the message was received.|
|replyTo|recipient collection|The email addresses to use when replying.|
|sender|recipient|The account that is actually used to generate the message. In most cases, this value is the same as the **from** property. You can set this property to a different value when sending a message from a shared mailbox, for a shared calendar, or as a delegate. In any case, the value must correspond to the actual mailbox used. Find out more about setting the from and sender properties of a message.|
|sentDateTime|DateTimeOffset|The date and time the message was sent.|
|subject|String|The subject of the message.|
|toRecipients|recipient collection|The To: recipients for the message.|
|uniqueBody|itemBody|The part of the body of the message that is unique to the current message.|
|webLink|String|The URL to open the message in Outlook on the web.<br><br>You can append an ispopout argument to the end of the URL to change how the message is displayed. If ispopout is not present or if it is set to 1, then the message is shown in a popout window. If ispopout is set to 0, then the browser will show the message in the Outlook on the web review pane.<br><br>The message will open in the browser if you are logged in to your mailbox via Outlook on the web. You will be prompted to login if you are not already logged in with the browser.<br><br>This URL cannot be accessed from within an iFrame.|
### [mailFolder ](https://docs.microsoft.com/graph/api/resources/mailfolder?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------|:-----|:------------|
|childFolderCount|Int32|The number of immediate child mailFolders in the current mailFolder.|
|displayName|String|The mailFolder's display name.|
|id|String|The mailFolder's unique identifier.|
|isHidden|Boolean|Indicates whether the mailFolder is hidden. This property can be set only when creating the folder. Find more information in Hidden mail folders.|
|parentFolderId|String|The unique identifier for the mailFolder's parent mailFolder.|
|totalItemCount|Int32|The number of items in the mailFolder.|
|unreadItemCount|Int32|The number of items in the mailFolder marked as unread.|
### [mailSearchFolder ](https://docs.microsoft.com/graph/api/resources/mailsearchfolder?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| filterQuery | String | The OData query to filter the messages. |
| includeNestedFolders | Boolean | Indicates how the mailbox folder hierarchy should be traversed in the search. `true` means that a deep search should be done to include child folders in the hierarchy of each folder explicitly specified in **sourceFolderIds**. `false` means a shallow search of only each of the folders explicitly specified in **sourceFolderIds**. |
| isSupported | Boolean | Indicates whether a search folder is editable using REST APIs. |
| sourceFolderIds | String collection | The mailbox folders that should be mined. |
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
