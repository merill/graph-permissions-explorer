# RoleEligibilitySchedule.Read.Directory

> Allows the app to read the eligible role-based access control (RBAC) assignments for your company's directory, on behalf of the signed-in user. This includes reading directory role templates, and directory roles.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances](https://docs.microsoft.com/graph/api/rbacapplication-list-roleeligibilityscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/{unifiedRoleEligibilityScheduleInstanceId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/{unifiedRoleEligibilityScheduleInstancesId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests](https://docs.microsoft.com/graph/api/rbacapplication-list-roleeligibilityschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests/{unifiedRoleEligibilityScheduleRequestId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests/{unifiedRoleEligibilityScheduleRequestsId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /roleManagement/directory/RoleEligibilityScheduleRequests/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilitySchedules](https://docs.microsoft.com/graph/api/rbacapplication-list-roleeligibilityschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilitySchedules/{unifiedRoleEligibilityScheduleId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleEligibilitySchedules/{unifiedRoleEligibilitySchedulesId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilitySchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET roleManagement/directory/roleEligibilitySchedules/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|eb0788c2-6d4e-4658-8c9e-c0fb8053f03d|
|**Consent Type**|Admin|
|**Display String**|Read all eligible role assignments for your company's directory|
|**Description**|Allows the app to read the eligible role-based access control (RBAC) assignments for your company's directory, on behalf of the signed-in user. This includes reading directory role templates, and directory roles.|
## Application Permission
|||
|-|-|
|**Id**|ff278e11-4a33-4d0c-83d2-d01dc58929a5|
|**Display String**|Read all eligible role assignments and role schedules for your company's directory|
|**Description**|Allows the app to read the eligible role-based access control (RBAC) assignments and schedules for your company's directory, without a signed-in user. This includes reading directory role templates, and directory roles.|
## Resources
### [unifiedRoleEligibilitySchedule ](https://docs.microsoft.com/graph/api/resources/unifiedroleeligibilityschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScopeId|String|Identifier of the app-specific scope when the role eligibility is scoped to an app. The scope of a role eligibility determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|createdDateTime|DateTimeOffset|When the schedule was created. Inherited from unifiedRoleScheduleBase.|
|createdUsing|String|Identifier of the object through which this schedule was created. Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|directoryScopeId|String|Identifier of the directory object representing the scope of the role eligibility. The scope of a role eligibility determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|id|String|The unique identifier for the schedule object. Inherited from entity. Supports `$filter` (`eq`).|
|memberType|String|How the role eligibility is inherited. It can either be `Inherited`, `Direct`, or `Group`. It can further imply whether the **unifiedRoleEligibilitySchedule** can be managed by the caller. Supports `$filter` (`eq`, `ne`).|
|modifiedDateTime|DateTimeOffset|When the schedule was last modified. Inherited from unifiedRoleScheduleBase.|
|principalId|String|Identifier of the principal that is eligible for a role.Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that a principal is eligible for. Inherited from unifiedRoleScheduleBase.|
|scheduleInfo|requestSchedule|The period of the role eligibility.|
|status|String|The status of the role eligibility request. Inherited from unifiedRoleScheduleBase. The possible values are: `Canceled`, `Denied`, `Failed`, `Granted`, `PendingAdminDecision`, `PendingApproval`, `PendingProvisioning`, `PendingScheduleCreation`, `Provisioned`, `Revoked`, and `ScheduleCreated`. Not nullable. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleEligibilityScheduleInstance ](https://docs.microsoft.com/graph/api/resources/unifiedroleeligibilityscheduleinstance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScopeId|String|Identifier of the app-specific scope when the role eligibility is scoped to an app. The scope of the role eligibility determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Inherited from unifiedRoleScheduleInstanceBase. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|directoryScopeId|String|Identifier of the directory object representing the scope of the role eligibility. The scope of the role eligibility determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Inherited from unifiedRoleScheduleInstanceBase. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|endDateTime|DateTimeOffset|The end date of the schedule instance.|
|id|String|The unique identifier for the schedule object. Inherited from entity.|
|memberType|String|How the role eligibility is inherited. It can either be `Inherited`, `Direct`, or `Group`. It can further imply whether the **unifiedRoleEligibilitySchedule** can be managed by the caller. Supports `$filter` (`eq`, `ne`).|
|principalId|String|Identifier of the principal that's eligible for a role. Inherited from unifiedRoleScheduleInstanceBase. Supports `$filter` (`eq`, `ne`). |
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that the principal is eligible for. Inherited from unifiedRoleScheduleInstanceBase. Supports `$filter` (`eq`, `ne`).|
|roleEligibilityScheduleId|String|The identifier of the **unifiedRoleEligibilitySchedule** object from which this instance was created. Supports `$filter` (`eq`, `ne`).|
|startDateTime|DateTimeOffset|When this instance starts.|
### [unifiedRoleEligibilityScheduleRequest ](https://docs.microsoft.com/graph/api/resources/unifiedroleeligibilityschedulerequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|unifiedRoleScheduleRequestActions|Represents the type of operation on the role eligibility request. The possible values are: `adminAssign`, `adminUpdate`, `adminRemove`, `selfActivate`, `selfDeactivate`, `adminExtend`, `adminRenew`, `selfExtend`, `selfRenew`, `unknownFutureValue`. <br/><ul><li>`adminAssign`: For administrators to assign eligible roles to principals.</li><li>`adminRemove`: For administrators to remove eligible roles from principals.</li><li> `adminUpdate`: For administrators to change existing role eligibilities.</li><li>`adminExtend`: For administrators to extend expiring role eligibilities.</li><li>`adminRenew`: For administrators to renew expired eligibilities.</li><li>`selfActivate`: For users to activate their assignments.</li><li>`selfDeactivate`: For users to deactivate their active assignments.</li><li>`selfExtend`: For users to request to extend their expiring assignments.</li><li>`selfRenew`: For users to request to renew their expired assignments.</li></ul>|
|approvalId|String|The identifier of the approval of the request. Inherited from request.|
|appScopeId|String|Identifier of the app-specific scope when the role eligibility is scoped to an app. The scope of a role eligibility determines the set of resources for which the principal is eligible to access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|completedDateTime|DateTimeOffset|The request completion date time. Inherited from request.|
|createdBy|identitySet|The principal that created this request. Inherited from request.|
|createdDateTime|DateTimeOffset|The request creation date time. Inherited from request.|
|customData|String|Free text field to define any custom data for the request. Not used. Inherited from request.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the role eligibility. The scope of a role eligibility determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|id|String|The unique identifier for the **unifiedRoleEligibilityScheduleRequest** object. Key, not nullable, Read-only.  Inherited from entity.|
|isValidationOnly|Boolean|Determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when create they create the **unifiedRoleEligibilityScheduleRequest** object.|
|principalId|String|Identifier of the principal that has been granted the role eligibility. Can be a user or a role-assignable group. You can grant only active assignments service principals.Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that is being assigned to the principal. Supports `$filter` (`eq`, `ne`).|
|scheduleInfo|requestSchedule|The period of the role eligibility. Recurring schedules are currently unsupported.|
|status|String|The status of the role eligibility request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`).|
|targetScheduleId|String|Identifier of the schedule object that's linked to the eligibility request. Supports `$filter` (`eq`, `ne`).|
|ticketInfo|ticketInfo|Ticket details linked to the role eligibility request including details of the ticket number and ticket system. Optional.|
