# RoleAssignmentSchedule.Read.Directory

> Allows the app to read the active role-based access control (RBAC) assignments for your company's directory, on behalf of the signed-in user. This includes reading directory role templates, and directory roles.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/{unifiedRoleAssignmentScheduleInstanceId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/{unifiedRoleAssignmentScheduleInstancesId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/filterByCurrentUser(on=parameterValue)](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/{unifiedRoleAssignmentScheduleId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/{unifiedRoleAssignmentSchedulesId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|344a729c-0285-42c6-9014-f12b9b8d6129|
|**Consent Type**|Admin|
|**Display String**|Read all active role assignments for your company's directory|
|**Description**|Allows the app to read the active role-based access control (RBAC) assignments for your company's directory, on behalf of the signed-in user. This includes reading directory role templates, and directory roles.|
## Application Permission
|||
|-|-|
|**Id**|d5fe8ce8-684c-4c83-a52c-46e882ce4be1|
|**Display String**|Read all active role assignments and role schedules for your company's directory|
|**Description**|Allows the app to read the active role-based access control (RBAC) assignments and schedules for your company's directory, without a signed-in user. This includes reading directory role templates, and directory roles.|
## Resources
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
