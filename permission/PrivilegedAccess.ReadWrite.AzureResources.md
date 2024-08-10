# PrivilegedAccess.ReadWrite.AzureResources

> Allows the app to request and manage time-based assignment and just-in-time elevation of user privileges to manage Azure resources (like subscriptions, resource groups, storage, compute) on behalf of the signed-in users.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /privilegedAccess/azureResources/resources/{resourceId}/roleAssignmentRequests](https://docs.microsoft.com/graph/api/governanceroleassignmentrequest-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /privilegedAccess/azureResources/roleAssignmentRequests?$filter=resourceId+eq+'{resourceId}'](https://docs.microsoft.com/graph/api/governanceroleassignmentrequest-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /privilegedAccess/azureResources/roleAssignmentRequests/{id}/cancel](https://docs.microsoft.com/graph/api/governanceroleassignmentrequest-cancel?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|a84a9652-ffd3-496e-a991-22ba5529156a|
|**Consent Type**|Admin|
|**Display String**|Read and write privileged access to Azure resources|
|**Description**|Allows the app to request and manage time-based assignment and just-in-time elevation of user privileges to manage Azure resources (like subscriptions, resource groups, storage, compute) on behalf of the signed-in users.|
## Application Permission
|||
|-|-|
|**Id**|6f9d5abc-2db6-400b-a267-7de22a40fb87|
|**Display String**|Read and write privileged access to Azure resources|
|**Description**|Allows the app to request and manage time-based assignment and just-in-time elevation of Azure resources (like your subscriptions, resource groups, storage, compute) in your organization, without a signed-in user.|
## Resources
### [governanceRoleAssignmentRequest ](https://docs.microsoft.com/graph/api/resources/governanceroleassignmentrequest?view=graph-rest-1.0&tabs=http)
| Property                    | Type            |Description|
|:--------------------------|:--------------|:----------|
|id                         |String         |The identifier of the role assignment request.|
|resourceId                 |String         |Required. The unique identifier of the Azure resource that is associated with the role assignment request. Azure resources can include subscriptions, resource groups, virtual machines, and SQL databases.|
|roleDefinitionId           |String         |Required. The identifier of the Azure role definition that the role assignment request is associated with.|
|subjectId                  |String         |Required. The unique identifier of the principal or subject that the role assignment request is associated with. Principals can be users, groups, or service principals.|
|type                       |String        |Required. Representing the type of the operation on the role assignment. The possible values are: `AdminAdd` , `UserAdd` , `AdminUpdate` , `AdminRemove` , `UserRemove` , `UserExtend` , `AdminExtend` , `UserRenew` , `AdminRenew`.|
|assignmentState|String  |Required. The state of the assignment. The possible values are: `Eligible` (for eligible assignment),  `Active` (if it is directly assigned), `Active` (by administrators, or activated on an eligible assignment by the users).|
|requestedDateTime          |DateTimeOffset |Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|schedule                   |governanceSchedule|The schedule object of the role assignment request.|
|reason                     |String         |A message provided by users and administrators when create the request about why it is needed.|
|status                     |governanceRoleAssignmentRequestStatus         |The status of the role assignment request.|
|linkedEligibleRoleAssignmentId|String        |If this is a request for role activation, it represents the id of the `eligible assignment` being referred; Otherwise, the value is `null`. |
