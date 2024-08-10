# Community.ReadWrite.All

> Allows the app to create Viva Engage communities and read all community properties on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /employeeExperience/communities/{communityId}](https://docs.microsoft.com/graph/api/community-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /employeeExperience/communities](https://docs.microsoft.com/graph/api/employeeexperience-list-communities?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /employeeExperience/communities/{communityId}](https://docs.microsoft.com/graph/api/community-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /employeeExperience/engagementAsyncOperations/{engagementAsyncOperationId}](https://docs.microsoft.com/graph/api/engagementasyncoperation-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /employeeExperience/communities/{communityId}](https://docs.microsoft.com/graph/api/community-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /employeeExperience/communities](https://docs.microsoft.com/graph/api/employeeexperience-post-communities?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9e69467d-e0e2-402b-a926-3d796990197f|
|**Consent Type**|Admin|
|**Display String**|Read and write all Viva Engage communities|
|**Description**|Allows the app to create Viva Engage communities and read all community properties on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|35d59e32-eab5-4553-9345-abb62b4c703c|
|**Display String**|Read and write all Viva Engage communities|
|**Description**|Allows the app to create Viva Engage communities, read all community properties, update community properties, and delete communities without a signed-in user.|
## Resources
### [community ](https://docs.microsoft.com/graph/api/resources/community?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| description | String | The description of the community. The maximum length is 1024 characters. |
| displayName | String | The name of the community. The maximum length is 255 characters. |
| groupId | String | The ID of the Microsoft 365 group that manages the membership of this community. |
| id | String | The unique identifier of the community. Read only. Inherited from entity. |
| privacy | communityPrivacy | Defines the privacy level of the community. The possible values are: `public`, `private`, `unknownFutureValue`. |
### [engagementAsyncOperation ](https://docs.microsoft.com/graph/api/resources/engagementasyncoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| createdDateTime | DateTimeOffset | Date and time when the operation was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from longRunningOperation. |
| id | String | The unique identifier for the operation. Inherited from longRunningOperation. |
| lastActionDateTime | DateTimeOffset | Date and time when the async operation was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from longRunningOperation. |
| operationType | engagementAsyncOperationType | The type of the long-running operation. The possible values are: `createCommunity`, `unknownFutureValue`. |
| resourceId | String | The ID of the object created or modified as a result of this async operation. |
| resourceLocation |String| The location of the object created or modified as a result of this async operation. Inherited from longRunningOperation. |
| status | longRunningOperationStatus | The status of the operation. The possible values are: `notStarted`, `running`, `succeeded`, `failed`, `skipped`, `unknownFutureValue`. Inherited from longRunningOperation. |
|statusDetail|String|Details about the status of the operation. Inherited from longRunningOperation. |
