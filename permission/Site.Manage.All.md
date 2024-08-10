# Site.Manage.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[POST /sites/{sitesId}/contentModels/{contentModelId}/addToDrive](https://docs.microsoft.com/graph/api/contentmodel-addtodrive?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [contentModel ](https://docs.microsoft.com/graph/api/resources/contentmodel?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|Identity of the user, device, or applicationthat created the item. Read-only.|
|createdDateTime|DateTimeOffset|Date and time of item creation. Read-only.|
|id|String|The ID of the content model. Read-only.|
|lastModifiedBy|identitySet|	Identity of the user, device, or application that modified the item. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time of item last modification. Read-only.|
|modelType|contentModelType|The type of the **contentModel**. The possible values are: `teachingMethod`, `layoutMethod`, `freeformSelectionMethod`, `prebuiltContractModel`, `prebuiltInvoiceModel`, `prebuiltReceiptModel`, `unknownFutureValue`.|
|name|String|The name of the **c
### [contentModelUsage ](https://docs.microsoft.com/graph/api/resources/contentmodelusage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|Identity of the user, device, or application that first applied the contentModel to the library.|
|createdDateTime|DateTimeOffset|Date and time of the contentModel is first applied.|
|driveId|String|The ID of the drive where the contentModel is applied.|
|lastModifiedBy|identitySet|Identity of the user, device, or application that last applied the contentModel to the library.|
|lastModifiedDateTime|DateTimeOffset|Date and time of the contentModel is last applied.|
|modelId|String|The ID of the contentModel.|
|modelVersion|String|The version of the current applied contentModel.|
