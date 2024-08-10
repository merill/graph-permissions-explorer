# ServiceMessageViewpoint.Write

> Allows the app to update service announcement messages' user status on behalf of the signed-in user. The message status can be marked as read, archive, or favorite.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[POST /admin/serviceAnnouncement/messages/archive](https://docs.microsoft.com/graph/api/serviceupdatemessage-archive?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /admin/serviceAnnouncement/messages/favorite](https://docs.microsoft.com/graph/api/serviceupdatemessage-favorite?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /admin/serviceAnnouncement/messages/markRead](https://docs.microsoft.com/graph/api/serviceupdatemessage-markread?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /admin/serviceAnnouncement/messages/markUnread](https://docs.microsoft.com/graph/api/serviceupdatemessage-markunread?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /admin/serviceAnnouncement/messages/unarchive](https://docs.microsoft.com/graph/api/serviceupdatemessage-unarchive?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /admin/serviceAnnouncement/messages/unfavorite](https://docs.microsoft.com/graph/api/serviceupdatemessage-unfavorite?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|636e1b0b-1cc2-4b1c-9aa9-4eeed9b9761b|
|**Consent Type**|Admin|
|**Display String**|Update user status on service announcement messages|
|**Description**|Allows the app to update service announcement messages' user status on behalf of the signed-in user. The message status can be marked as read, archive, or favorite.|
## Resources
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
