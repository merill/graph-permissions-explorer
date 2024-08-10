# PrivilegedAccess.ReadWrite.AzureAD

> Allows the app to request and manage just in time elevation (including scheduled elevation) of users to Azure AD built-in administrative roles, on behalf of signed-in users.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /privilegedAccess/azureResources/resources/{resourceId}/roleAssignmentRequests](https://docs.microsoft.com/graph/api/governanceroleassignmentrequest-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /privilegedAccess/azureResources/roleAssignmentRequests?$filter=resourceId+eq+'{resourceId}'](https://docs.microsoft.com/graph/api/governanceroleassignmentrequest-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /roleManagement/directory/roleScheduleInstances(directoryScopeId='@directoryScopeId',appScopeId='@appScopeId',principalId='@principalId',roleDefinitionId='@roleDefinitionId')](https://docs.microsoft.com/graph/api/rbacapplication-rolescheduleinstances?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /roleManagement/directory/roleSchedules(directoryScopeId='@directoryScopeId',appScopeId='@appScopeId',principalId='@principalId',roleDefinitionId='@roleDefinitionId')](https://docs.microsoft.com/graph/api/rbacapplication-roleschedules?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|3c3c74f5-cdaa-4a97-b7e0-4e788bfcfb37|
|**Consent Type**|Admin|
|**Display String**|Read and write privileged access to Azure AD|
|**Description**|Allows the app to request and manage just in time elevation (including scheduled elevation) of users to Azure AD built-in administrative roles, on behalf of signed-in users.|
## Application Permission
|||
|-|-|
|**Id**|854d9ab1-6657-4ec8-be45-823027bcd009|
|**Display String**|Read and write privileged access to Azure AD roles|
|**Description**|Allows the app to request and manage time-based assignment and just-in-time elevation (including scheduled elevation) of Azure AD built-in and custom administrative roles in your organization, without a signed-in user.|
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
### [unifiedRoleScheduleBase ](https://docs.microsoft.com/graph/api/resources/unifiedroleschedulebase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScopeId|String|Identifier of the app-specific scope when the assignment or eligibility is scoped to an app. The scope of an assignment or eligibility determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units.|
|createdDateTime|DateTimeOffset|When the schedule was created.|
|createdUsing|String|Identifier of the object through which this schedule was created.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment or eligibility. The scope of an assignment or eligibility determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only.|
|id|String|The unique identifier for the schedule object. Inherited from entity.|
|modifiedDateTime|DateTimeOffset|When the schedule was last modified.|
|principalId|String|Identifier of the principal that has been granted the role assignment or eligibility.|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that is being assigned to the principal or that a principal is eligible for.|
|status|String|The status of the role assignment or eligibility request.|
### [unifiedRoleScheduleInstanceBase ](https://docs.microsoft.com/graph/api/resources/unifiedrolescheduleinstancebase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScopeId|String|Identifier of the app-specific scope when the assignment or role eligibility is scoped to an app. The scope of an assignment or role eligibility determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment or role eligibility. The scope of an assignment or role eligibility determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only.|
|id|String|The unique identifier for the schedule object. Inherited from entity.|
|principalId|String|Identifier of the principal that has been granted the role assignment or that's eligible for a role.|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that is being assigned to the principal or that the principal is eligible for.|
