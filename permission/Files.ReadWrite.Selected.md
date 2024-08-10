# Files.ReadWrite.Selected

> (Preview) Allows the app to read and write files that the user selects. The app has access for several hours after the user selects a file.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /me/drive/items/{id}/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/drive/root:/{item-path}:/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|17dde5bd-8c17-420f-a486-969730c1b827|
|**Consent Type**|User|
|**Display String**|Read and write files that the user selects (preview)|
|**Description**|(Preview) Allows the app to read and write files that the user selects. The app has access for several hours after the user selects a file.|
## Resources
### [workbookNamedItem ](https://docs.microsoft.com/graph/api/resources/workbooknameditem?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|comment|String|The comment associated with this name.|
|name|String|The name of the object. Read-only.|
|scope|String|Indicates whether the name is scoped to the workbook or to a specific worksheet. Read-only.|
|type|String|The type of reference is associated with the name. Possible values are: `String`, `Integer`, `Double`, `Boolean`, `Range`. Read-only.|
|value|String|The formula that the name is defined to refer to. For example, `=Sheet14!$B$2:$H$12` and `=4.75`. Read-only.|
|visible|Boolean|Indicates whether the object is visible.|
