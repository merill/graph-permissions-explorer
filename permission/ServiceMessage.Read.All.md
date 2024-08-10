# ServiceMessage.Read.All

> Allows the app to read your tenant's service announcement messages on behalf of the signed-in user. Messages may include information about new or changed features.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /admin/serviceAnnouncement/messages](https://docs.microsoft.com/graph/api/serviceannouncement-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/messages/{serviceUpdateMessageId}](https://docs.microsoft.com/graph/api/serviceupdatemessage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/messages/{serviceUpdateMessageId}/attachments](https://docs.microsoft.com/graph/api/serviceupdatemessage-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/messages/{serviceUpdateMessageId}/attachments/{serviceAnnouncementAttachmentId}](https://docs.microsoft.com/graph/api/serviceannouncementattachment-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|eda39fa6-f8cf-4c3c-a909-432c683e4c9b|
|**Consent Type**|Admin|
|**Display String**|Read service announcement messages|
|**Description**|Allows the app to read your tenant's service announcement messages on behalf of the signed-in user. Messages may include information about new or changed features.|
## Application Permission
|||
|-|-|
|**Id**|1b620472-6534-4fe6-9df2-4680e8aa28ec|
|**Display String**|Read service messages|
|**Description**|Allows the app to read your tenant's service announcement messages, without a signed-in user. Messages may include information about new or changed features.|
## Resources
### [serviceAnnouncementAttachment ](https://docs.microsoft.com/graph/api/resources/serviceannouncementattachment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|Stream|The attachment content.|
|contentType|String|The content type of the attachment.|
|id|String|The attachment ID. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the attachment was last modified.|
|name|String|The attachment name.|
|size|Int32|The size in bytes of the attachment.|
### [serviceUpdateMessage ](https://docs.microsoft.com/graph/api/resources/serviceupdatemessage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionRequiredByDateTime|DateTimeOffset|The expected deadline of the action for the message.|
|attachmentsArchive|Stream|The zip file that contains all attachments for a message.|
|body|itemBody|The content type and content of the service message body. The supported value for the contentType property is `html`.|
|category|serviceUpdateCategory|The service message category. Possible values are: `preventOrFixIssue`, `planForChange`, `stayInformed`, `unknownFutureValue`.|
|details|Collection(keyValuePair)|Additional details about service message. This property doesn't support filters. Inherited from serviceAnnouncementBase.|
|endDateTime|DateTimeOffset|The end time of the service message. Inherited from serviceAnnouncementBase.|
|hasAttachments|Boolean|Indicates whether the message has any attachment.|
|id|String|The id of the service message. Inherited from serviceAnnouncementBase.|
|isMajorChange|Boolean|Indicates whether the message describes a major update for the service.|
|lastModifiedDateTime|DateTimeOffset|The last modified time of the service message. Inherited from serviceAnnouncementBase.|
|services|Collection(string)|The affected services by the service message.|
|severity|serviceUpdateSeverity|The severity of the service message. Possible values are: `normal`, `high`, `critical`, `unknownFutureValue`.|
|startDateTime|DateTimeOffset|The start time of the service message. Inherited from serviceAnnouncementBase.|
|tags|Collection(string)|A collection of tags for the service message. Tags are provided by the service team/support team who post the message to tell whether this message contains privacy data, or whether this message is for a service new feature update, and so on.|
|title|String|The title of the service message. Inherited from serviceAnnouncementBase.|
|viewPoint|serviceUpdateMessageViewpoint|Represents user viewpoints data of the service message. This data includes message status such as whether the user has archived, read, or marked the message as favorite. This property is null when accessed with application permissions.|
