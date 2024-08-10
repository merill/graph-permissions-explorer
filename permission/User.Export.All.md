# User.Export.All

> Allows the app to export data (e.g. customer content or system-generated logs), associated with any user in your company, when the app is used by a privileged user (e.g. a Company Administrator).
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/user-exportpersonaldata?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /dataPolicyOperations/{id}](https://docs.microsoft.com/graph/api/datapolicyoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/exportPersonalData](https://docs.microsoft.com/graph/api/user-exportpersonaldata?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|405a51b5-8d8d-430b-9842-8be4b0e9f324|
|**Consent Type**|Admin|
|**Display String**|Export user's data|
|**Description**|Allows the app to export data (e.g. customer content or system-generated logs), associated with any user in your company, when the app is used by a privileged user (e.g. a Company Administrator).|
## Application Permission
|||
|-|-|
|**Id**|405a51b5-8d8d-430b-9842-8be4b0e9f324|
|**Display String**|Export user's data|
|**Description**|Allows the app to export data (e.g. customer content or system-generated logs), associated with any user in your company, when the app is used by a privileged user (e.g. a Company Administrator).|
## Resources
### [dataPolicyOperation ](https://docs.microsoft.com/graph/api/resources/datapolicyoperation?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|completedDateTime|DateTimeOffset|Represents when the request for this data policy operation was completed, in UTC time, using the ISO 8601 format. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Null until the operation completes.|
|id|String| Unique key for this operation. |
|status|dataPolicyOperationStatus| Possible values are: `notStarted`, `running`, `complete`, `failed`, `unknownFutureValue`.|
|storageLocation|String|The URL location to where data is being exported for export requests.|
|userId|String|The id for the user on whom the operation is performed.|
|submittedDateTime|DateTimeOffset|Represents when the request for this data operation was submitted, in UTC time, using the ISO 8601 format. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|progress|String|Specifies the progress of an operation.|
