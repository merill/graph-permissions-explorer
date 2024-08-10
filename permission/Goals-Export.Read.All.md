# Goals-Export.Read.All

> Allows the app to read all goals and export jobs that the signed-in user can access.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /employeeExperience/goals/exportJobs](https://docs.microsoft.com/graph/api/goals-list-exportjobs?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /employeeExperience/goals/exportJobs/{goalsExportJobId}](https://docs.microsoft.com/graph/api/goalsexportjob-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|092211d9-ca1a-427b-813e-b79c7653fe71|
|**Consent Type**|Admin|
|**Display String**|Read all goals and export jobs that a user can access|
|**Description**|Allows the app to read all goals and export jobs that the signed-in user can access.|
## Resources
### [goalsExportJob ](https://docs.microsoft.com/graph/api/resources/goalsexportjob?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|Stream|The content of the **goalsExportJob**.|
|createdDateTime|DateTimeOffset|The start time of the operation. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. Inherited from longRunningOperation.|
|expirationDateTime|DateTimeOffset|The date and time of expiry of the result of the operation.|
|explorerViewId|String|The unique identifier of the explorer view to be exported.|
|goalsOrganizationId|String|The unique identifier of the viva goals organization.|
|id|String|The unique identifier for the operation. Inherited from longRunningOperation.|
|resourceLocation|String|The URI of the resource on which the operation is performed. Inherited from longRunningOperation.|
|status|longRunningOperationStatus|The status of the operation. Inherited from longRunningOperation. The possible values are: `notStarted`, `running`, `succeeded`, `failed`, `unknownFutureValue`.|
