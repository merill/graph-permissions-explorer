# RoleAssignmentSchedule.ReadWrite.Directory

> Allows the app to read and manage the active role-based access control (RBAC) assignments for your company's directory, on behalf of the signed-in user. This includes managing active directory role membership, and reading directory role templates, directory roles and active memberships.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/{unifiedRoleAssignmentScheduleInstanceId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/{unifiedRoleAssignmentScheduleInstancesId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/filterByCurrentUser(on=parameterValue)](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/{unifiedRoleAssignmentScheduleRequestId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/{unifiedRoleAssignmentScheduleRequestsId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/{unifiedRoleAssignmentScheduleId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/{unifiedRoleAssignmentSchedulesId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /roleManagement/directory/roleAssignmentScheduleRequests](https://docs.microsoft.com/graph/api/rbacapplication-post-roleassignmentschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /roleManagement/directory/roleAssignmentScheduleRequests/{unifiedRoleAssignmentScheduleRequestId}/cancel](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-cancel?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /roleManagement/directory/roleAssignmentScheduleRequests/{unifiedRoleAssignmentScheduleRequestsId}/cancel](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-cancel?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8c026be3-8e26-4774-9372-8d5d6f21daff|
|**Consent Type**|Admin|
|**Display String**|Read, update, and delete all active role assignments for your company's directory|
|**Description**|Allows the app to read and manage the active role-based access control (RBAC) assignments for your company's directory, on behalf of the signed-in user. This includes managing active directory role membership, and reading directory role templates, directory roles and active memberships.|
## Application Permission
|||
|-|-|
|**Id**|dd199f4a-f148-40a4-a2ec-f0069cc799ec|
|**Display String**|Read, update, and delete all policies for privileged role assignments of your company's directory|
|**Description**|Allows the app to read, update, and delete policies for privileged role-based access control (RBAC) assignments of your company's directory, without a signed-in user.|
## Resources
### [requestSchedule ](https://docs.microsoft.com/graph/api/resources/requestschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|expiration|expirationPattern|When the eligible or active assignment expires.|
|recurrence|patternedRecurrence|The frequency of the  eligible or active assignment. This property is currently unsupported in PIM.|
|startDateTime|DateTimeOffset|When the  eligible or active assignment becomes active.|
### [ticketInfo ](https://docs.microsoft.com/graph/api/resources/ticketinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|ticketNumber|String|The ticket number.|
|ticketSystem|String|The description of the ticket system.|
### [unifiedRoleAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appScopeId|String|Identifier of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by a resource application only. For the entitlement management provider, use this property to specify a catalog. For example, `/AccessPackageCatalog/beedadfe-01d5-4025-910b-84abb9369997`. Supports `$filter` (`eq`, `in`). For example, `/roleManagement/entitlementManagement/roleAssignments?$filter=appScopeId eq '/AccessPackageCatalog/{catalog id}'`.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications, unlike app scopes that are defined and understood by a resource application only. Supports `$filter` (`eq`, `in`).|
|id|String| The unique identifier for the unifiedRoleAssignment. Key, not nullable, Read-only. |
|principalId|String| Identifier of the principal to which the assignment is granted. Supported principals are users, role-assignable groups, and service principals. Supports `$filter` (`eq`, `in`). |
|roleDefinitionId|String| Identifier of the unifiedRoleDefinition the assignment is for. Read-only. Supports `$filter` (`eq`, `in`). |
### [unifiedRoleAssignmentSchedule ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignmentschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScopeId|String|Identifier of the app-specific scope when the assignment is scoped to an app. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Supports `$filter` (`eq`, `ne`, and on `null` values). Inherited from unifiedRoleScheduleBase.|
|assignmentType|String|The type of the assignment that can either be `Assigned` or `Activated`. Supports `$filter` (`eq`, `ne`).|
|createdDateTime|DateTimeOffset|When the schedule was created. Inherited from unifiedRoleScheduleBase.|
|createdUsing|String|Identifier of the **unifiedRoleAssignmentScheduleRequest** object through which this schedule was created. Nullable. Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Supports `$filter` (`eq`, `ne`, and on `null` values). Inherited from unifiedRoleScheduleBase.|
|id|String|The unique identifier for the **unifiedRoleAssignmentScheduleRequest** object. Supports `$filter` (`eq`). Inherited from entity.|
|memberType|String|How the assignment is inherited. It can either be `Inherited`, `Direct`, or `Group`. It can further imply whether the **unifiedRoleAssignmentSchedule** can be managed by the caller. Supports `$filter` (`eq`, `ne`).|
|modifiedDateTime|DateTimeOffset|When the schedule was last modified. Inherited from unifiedRoleScheduleBase.|
|principalId|String|Identifier of the principal that has been granted the role assignment. Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that is being assigned to the principal. Inherited from unifiedRoleScheduleBase. Supports `$filter` (`eq`, `ne`).|
|scheduleInfo|requestSchedule|The period of the role assignment. It can represent a single occurrence or multiple recurrences.|
|status|String|The status of the **u
### [unifiedRoleAssignmentScheduleInstance ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignmentscheduleinstance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScopeId|String|Identifier of the app-specific scope when the assignment is scoped to an app. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Supports `$filter` (`eq`, `ne`, and on `null` values). Inherited from unifiedRoleScheduleInstanceBase.|
|assignmentType|String|The type of the assignment that can either be `Assigned` or `Activated`. Supports `$filter` (`eq`, `ne`).|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Supports `$filter` (`eq`, `ne`, and on `null` values). Inherited from unifiedRoleScheduleInstanceBase.|
|endDateTime|DateTimeOffset| The end date of the schedule instance.|
|id|String|The unique identifier for the **unifiedRoleAssignmentScheduleInstance** object. Inherited from entity.|
|memberType|String|How the assignment is inherited. It can either be `Inherited`, `Direct`, or `Group`. It can further imply whether the **unifiedRoleAssignmentSchedule** can be managed by the caller. Supports `$filter` (`eq`, `ne`).|
|principalId|String|Identifier of the principal that has been granted the role assignment. Inherited from unifiedRoleScheduleInstanceBase. Supports `$filter` (`eq`, `ne`). |
|roleAssignmentOriginId|String|The identifier of the role assignment in Microsoft Entra. Supports `$filter` (`eq`, `ne`).|
|roleAssignmentScheduleId|String|The identifier of the **unifiedRoleAssignmentSchedule** object from which this instance was created. Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|The identifier of the unifiedRoleDefinition object that is being assigned to the principal. Inherited from unifiedRoleScheduleInstanceBase. Supports `$filter` (`eq`, `ne`).|
|startDateTime|DateTimeOffset|When this instance starts.|
### [unifiedRoleAssignmentScheduleRequest ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignmentschedulerequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|String|Represents the type of the operation on the role assignment request. The possible values are: `adminAssign`, `adminUpdate`, `adminRemove`, `selfActivate`, `selfDeactivate`, `adminExtend`, `adminRenew`, `selfExtend`, `selfRenew`, `unknownFutureValue`. <br/><ul><li>`adminAssign`: For administrators to assign roles to principals.</li><li>`adminRemove`: For administrators to remove principals from roles.</li><li> `adminUpdate`: For administrators to change existing role assignments.</li><li>`adminExtend`: For administrators to extend expiring assignments.</li><li>`adminRenew`: For administrators to renew expired assignments.</li><li>`selfActivate`: For principals to activate their assignments.</li><li>`selfDeactivate`: For principals to deactivate their active assignments.</li><li>`selfExtend`: For principals to request to extend their expiring assignments.</li><li>`selfRenew`: For principals to request to renew their expired assignments.</li></ul>|
|approvalId|String|The identifier of the approval of the request. Inherited from request.|
|appScopeId|String|Identifier of the app-specific scope when the assignment is scoped to an app. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by this application only. Use `/` for tenant-wide app scopes. Use **directoryScopeId** to limit the scope to particular directory objects, for example, administrative units. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|completedDateTime|DateTimeOffset|The request completion date time. Inherited from request.|
|createdBy|identitySet|The principal that created this request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|createdDateTime|DateTimeOffset|The request creation date time. Inherited from request. Read-only.|
|customData|String|Free text field to define any custom data for the request. Not used. Inherited from request.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. Use **appScopeId** to limit the scope to an application only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|id|String|The unique identifier for the **unifiedRoleAssignmentScheduleRequest** object. Key, not nullable, Read-only. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|isValidationOnly|Boolean|Determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when create they create the **unifiedRoleAssignmentScheduleRequest** object.|
|principalId|String|Identifier of the principal that has been granted the assignment. Can be a user, role-assignable group, or a service principal. Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|Identifier of the unifiedRoleDefinition object that is being assigned to the principal. Supports `$filter` (`eq`, `ne`).|
|scheduleInfo|requestSchedule|The period of the role assignment. Recurring schedules are currently unsupported.|
|status|String|The status of the role assignment request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`).|
|targetScheduleId|String|Identifier of the schedule object that's linked to the assignment request. Supports `$filter` (`eq`, `ne`).|
|ticketInfo|ticketInfo|Ticket details linked to the role assignment request including details of the ticket number and ticket system.|
### [unifiedRoleDefinition ](https://docs.microsoft.com/graph/api/resources/unifiedroledefinition?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String| The description for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. |
|displayName|String| The display name for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. Required.  Supports $filter (`eq`, `in`).|
|id|String| The unique identifier for the role definition. Key, not nullable, Read-only. Inherited from entity. Supports $filter (`eq`, `in`). |
|isBuiltIn|Boolean| Flag indicating whether the role definition is part of the default set included in Microsoft Entra or a custom definition. Read-only. Supports $filter (`eq`, `in`). |
|isEnabled|Boolean| Flag indicating whether the role is enabled for assignment. If `false` the role is not available for assignment. Read-only when **isBuiltIn** is true. |
|resourceScopes|String collection| List of the scopes or permissions the role definition applies to. Currently only `/` is supported. Read-only when **isBuiltIn** is true. **DO NOT USE. This will be deprecated soon. Attach scope to role assignment.** | 
|rolePermissions|unifiedRolePermission collection| List of permissions included in the role. Read-only when **isBuiltIn** is `true`. Required. |
|templateId|String| Custom template identifier that can be set when **isBuiltIn** is `false` but is read-only when **isBuiltIn** is `true`. This identifier is typically used if one needs an identifier to be the same across different directories. |
|version|String| Indicates version of the role definition. Read-only when **i
