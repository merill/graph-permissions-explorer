# RoleManagement.Read.Directory

> Allows the app to read the role-based access control (RBAC) settings for your company's directory, on behalf of the signed-in user.  This includes reading directory role templates, directory roles and memberships.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[](https://docs.microsoft.com/graph/api/directoryrole-delta?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/scopedRoleMembers](https://docs.microsoft.com/graph/api/administrativeunit-list-scopedrolemembers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/scopedRoleMembers/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get-scopedrolemembers?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/scopedRoleMembers](https://docs.microsoft.com/graph/api/administrativeunit-list-scopedrolemembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/scopedRoleMembers/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get-scopedrolemembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles](https://docs.microsoft.com/graph/api/directoryrole-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles(roleTemplateId='{roleTemplateId}')](https://docs.microsoft.com/graph/api/directoryrole-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles(roleTemplateId='{roleTemplateId}')/members](https://docs.microsoft.com/graph/api/directoryrole-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles(roleTemplateId='{roleTemplateId}')/scopedMembers](https://docs.microsoft.com/graph/api/directoryrole-list-scopedmembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles/{role-id}](https://docs.microsoft.com/graph/api/directoryrole-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles/{role-id}/members](https://docs.microsoft.com/graph/api/directoryrole-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryroles/{role-id}/scopedMembers](https://docs.microsoft.com/graph/api/directoryrole-list-scopedmembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles/delta](https://docs.microsoft.com/graph/api/directoryrole-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoleTemplates](https://docs.microsoft.com/graph/api/directoryroletemplate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoleTemplates/{id}](https://docs.microsoft.com/graph/api/directoryroletemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/roleManagementPolicies?$filter=scopeId eq '/' and scopeType eq 'DirectoryRole'](https://docs.microsoft.com/graph/api/policyroot-list-rolemanagementpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/effectiveRules](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-list-effectiverules?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/rules](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-list-rules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/rules/{unifiedRoleManagementPolicyRuleId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicyrule-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/roleManagementPolicyAssignments?$filter=scopeId eq '/' and scopeType eq 'DirectoryRole'](https://docs.microsoft.com/graph/api/policyroot-list-rolemanagementpolicyassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/roleManagementPolicyAssignments/{unifiedRoleManagementPolicyAssignmentId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/resourceNamespaces](https://docs.microsoft.com/graph/api/rbacapplicationmultiple-list-resourcenamespaces?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/resourceNamespaces/{unifiedRbacResourceNamespaceId}](https://docs.microsoft.com/graph/api/unifiedrbacresourcenamespace-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/resourceNamespaces/{unifiedRbacResourceNamespaceId}/resourceActions](https://docs.microsoft.com/graph/api/unifiedrbacresourcenamespace-list-resourceactions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/resourceNamespaces/{unifiedRbacResourceNamespaceId}/resourceActions/{unifiedRbacResourceActionId}](https://docs.microsoft.com/graph/api/unifiedrbacresourceaction-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/{unifiedRoleAssignmentScheduleInstanceId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/{unifiedRoleAssignmentScheduleInstancesId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleInstances/filterByCurrentUser(on=parameterValue)](https://docs.microsoft.com/graph/api/unifiedroleassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleAssignmentScheduleRequests](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/{unifiedRoleAssignmentScheduleRequestId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/{unifiedRoleAssignmentScheduleRequestsId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentScheduleRequests/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedulerequest-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignmentschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/{unifiedRoleAssignmentScheduleId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/{unifiedRoleAssignmentSchedulesId}](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleAssignmentSchedules/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleassignmentschedule-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleDefinitions/{unifiedRoleDefinitionId}/assignedPrincipals(transitive=@transitive,directoryScopeType='@directoryScopeType',directoryScopeId='@directoryScopeId')](https://docs.microsoft.com/graph/api/unifiedroledefinition-assignedprincipals?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances](https://docs.microsoft.com/graph/api/rbacapplication-list-roleeligibilityscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/{unifiedRoleEligibilityScheduleInstanceId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/{unifiedRoleEligibilityScheduleInstancesId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleEligibilityScheduleInstances/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityscheduleinstance-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests](https://docs.microsoft.com/graph/api/rbacapplication-list-roleeligibilityschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests/{unifiedRoleEligibilityScheduleRequestId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /roleManagement/directory/roleEligibilityScheduleRequests/{unifiedRoleEligibilityScheduleRequestsId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilityScheduleRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/RoleEligibilityScheduleRequests/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedulerequest-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilitySchedules](https://docs.microsoft.com/graph/api/rbacapplication-list-roleeligibilityschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilitySchedules/{unifiedRoleEligibilityScheduleId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/roleEligibilitySchedules/{unifiedRoleEligibilitySchedulesId}](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleEligibilitySchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/transitiveRoleAssignments?$filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/rbacapplication-list-transitiveroleassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET roleManagement/directory/roleEligibilitySchedules/filterByCurrentUser(on='principal')](https://docs.microsoft.com/graph/api/unifiedroleeligibilityschedule-filterbycurrentuser?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|741c54c3-0c1e-44a1-818b-3f97ab4e8c83|
|**Consent Type**|Admin|
|**Display String**|Read directory RBAC settings|
|**Description**|Allows the app to read the role-based access control (RBAC) settings for your company's directory, on behalf of the signed-in user.  This includes reading directory role templates, directory roles and memberships.|
## Application Permission
|||
|-|-|
|**Id**|483bed4a-2ad3-4361-a73b-c83ccdbdc53c|
|**Display String**|Read all directory RBAC settings|
|**Description**|Allows the app to read the role-based access control (RBAC) settings for your company's directory, without a signed-in user.  This includes reading directory role templates, directory roles and memberships.|
## Resources
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [directoryRole ](https://docs.microsoft.com/graph/api/resources/directoryrole?view=graph-rest-1.0&tabs=http)
| Property   | Type | Description |
|:---------------|:--------|:----------|
|description|String|The description for the directory role. Read-only. Supports `$filter` (`eq`), `$search`, `$select`. |
|displayName|String|The display name for the directory role. Read-only. Supports `$filter` (`eq`), `$search`, `$select`. |
|id|String|The unique identifier for the directory role. Inherited from directoryObject. Key, Not nullable, Read-only. Supports `$filter` (`eq`), `$select`.|
|roleTemplateId|String| The **i
### [directoryRoleTemplate ](https://docs.microsoft.com/graph/api/resources/directoryroletemplate?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|description|String|The description to set for the directory role. Read-only.|
|displayName|String|The display name to set for the directory role. Read-only. |
|id|String|The unique identifier for the template. Inherited from directoryObject. You specify the **i
### [scopedRoleMembership ](https://docs.microsoft.com/graph/api/resources/scopedrolemembership?view=graph-rest-1.0&tabs=http)
| Property   | Type | Description |
|:---------------|:--------|:----------|
|administrativeUnitId|string|Unique identifier for the administrative unit that the directory role is scoped to|
|ID|string| Unique identifier for the scoped-role membership. Read-only.|
|roleId|string| Unique identifier for the directory role that the member is in.|
|roleMemberInfo|identity| Role member identity information. Represents the user that is a member of this scoped-role.|
### [unifiedRbacResourceAction ](https://docs.microsoft.com/graph/api/resources/unifiedrbacresourceaction?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionVerb|String|HTTP method for the action, such as `DELETE`, `GET`, `PATCH`, `POST`, `PUT`, or `null`. Supports `$filter` (`eq`) but not for `null` values. |
|description|String|Description for the action. Supports `$filter` (`eq`). |
|id|String|Unique identifier for an action within the resource namespace, such as `microsoft.insights-programs-update-patch`. can't include slash character (`/`). Case insensitive. Required. Supports `$filter` (`eq`). |
|isPrivileged|Boolean|Flag indicating if the action is a sensitive resource action. Applies only for actions in the `microsoft.directory` resource namespace. Read-only. Supports `$filter` (`eq`).|
|name|String|Name for the action within the resource namespace, such as `microsoft.insights/programs/update`. Can include slash character (`/`). Case insensitive. Required. Supports `$filter` (`eq`). |
|resourceScopeId|String|Not implemented.|
### [unifiedRbacResourceNamespace ](https://docs.microsoft.com/graph/api/resources/unifiedrbacresourcenamespace?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the resource namespace that defines permissions, such as `microsoft.aad.b2c`. Required.|
|name|String|Name of the resource namespace. Typically, the same name as the **i
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
### [unifiedRoleManagementPolicy ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Description for the policy.|
|displayName|String|Display name for the policy.|
|id|String|Unique identifier for the policy.|
|isOrganizationDefault|Boolean|This can only be set to `true` for a single tenant-wide policy which will apply to all scopes and roles. Set the scopeId to `/` and scopeType to `Directory`. Supports `$filter` (`eq`, `ne`).|
|lastModifiedBy|identity|The identity who last modified the role setting.|
|lastModifiedDateTime|DateTimeOffset|The time when the role setting was last modified.|
|scopeId|String|The identifier of the scope where the policy is created. Can be `/` for the tenant or a group ID. Required.|
|scopeType|String|The type of the scope where the policy is created. One of `Directory`, `DirectoryRole`, `Group`. Required.|
### [unifiedRoleManagementPolicyApprovalRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyapprovalrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity.|
|setting|approvalSettings|The settings for approval of the role assignment.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the approval rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the policy assignment. The ID is typically a concatenation of the **unifiedRoleManagementPolicy** ID and the **roleDefinitionId** separated by an underscore.|
|policyId|String|The id of the policy. Inherited from entity.|
|roleDefinitionId|String|For Microsoft Entra roles policy, it's the identifier of the role definition object where the policy applies. For PIM for groups membership and ownership, it's either `member` or `owner`. Supports $filter (`eq`).|
|scopeId|String|The identifier of the scope where the policy is assigned.  Can be `/` for the tenant or a group ID. Required.|
|scopeType|String|The type of the scope where the policy is assigned. One of `Directory`, `DirectoryRole`, `Group`. Required.|
### [unifiedRoleManagementPolicyAuthenticationContextRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyauthenticationcontextrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|claimValue|String|The value of the authentication context claim.|
|id|String|Identifier for the rule. Inherited from entity.|
|isEnabled|Boolean| Determines whether this rule is enabled.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that the enablement rule targets. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyEnablementRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyenablementrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|enabledRules|String collection|The collection of rules that are enabled for this policy rule. For example, `MultiFactorAuthentication`, `Ticketing`, and `Justification`.|
|id|String|Identifier for the rule. Inherited from entity.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the enablement rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyExpirationRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyexpirationrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity.|
|isExpirationRequired|Boolean|Indicates whether expiration is required or if it's a permanently active assignment or eligibility. |
|maximumDuration|Duration| The maximum duration allowed for eligibility or assignment that isn't permanent. Required when **isExpirationRequired** is `true`. |
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the expiration rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyNotificationRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicynotificationrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity.|
|isDefaultRecipientsEnabled|Boolean|Indicates whether a default recipient will receive the notification email.|
|notificationLevel|String|The level of notification. The possible values are `None`, `Critical`, `All`.|
|notificationRecipients|String collection|The list of recipients of the email notifications.|
|notificationType|String|The type of notification. Only `Email` is supported.|
|recipientType|String|The type of recipient of the notification. The possible values are `Requestor`, `Approver`, `Admin`.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the notification rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity. Read-only.|
|target|unifiedRoleManagementPolicyRuleTarget| Defines details of scope that's targeted by role management policy rule. The details can include the principal type, the role assignment type, and actions affecting a role. Supports `$filter` (`eq`, `ne`).|
