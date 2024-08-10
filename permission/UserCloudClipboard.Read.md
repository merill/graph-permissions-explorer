# UserCloudClipboard.Read

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/cloudClipboard/items](https://docs.microsoft.com/graph/api/cloudclipboardroot-list-items?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/cloudClipboard/items/{cloudClipboardItemId}](https://docs.microsoft.com/graph/api/cloudclipboarditem-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
### [cloudClipboardItem ](https://docs.microsoft.com/graph/api/resources/cloudclipboarditem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Set by the server. DateTime in UTC when the object was created on the server.|
|expirationDateTime|DateTimeOffset|Set by the server. DateTime in UTC when the object expires and after that the object is no longer available. The default and also maximum TTL is **12 hours** after the creation, but it might change for performance optimization.  |
|id|Guid|The unique identifier of the object.|
|lastModifiedDateTime|DateTimeOffset|Set by the server if not provided in the client's request. DateTime in UTC when the object was modified by the client.|
|payloads|cloudClipboardItemPayload collection| A cloudClipboardItem can have multiple cloudClipboardItemPayload objects in the `payloads`. A window can place more than one clipboard object on the clipboard. Each one represents the same information in a different clipboard format.|
