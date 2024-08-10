# RoleManagement.ReadWrite.Exchange

> Allows the app to read and manage the role-based access control (RBAC) settings for your organization's Exchange Online service, on behalf of the signed-in user. This includes reading, creating, updating, and deleting Exchange management role definitions, role groups, role group membership, role assignments, management scopes, and role assignment policies.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /roleManagement/directory/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignment-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /roleManagement/exchange/customAppScopes/{id}](https://docs.microsoft.com/graph/api/customappscope-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignments?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/exchange/customAppScopes](https://docs.microsoft.com/graph/api/unifiedrbacapplication-list-customappscopes?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/exchange/customAppScopes/{id}](https://docs.microsoft.com/graph/api/customappscope-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /roleManagement/exchange/customAppScopes/{id}](https://docs.microsoft.com/graph/api/customappscope-update?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /roleManagement/directory/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplication-post-roleassignments?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /roleManagement/exchange/customAppScopes](https://docs.microsoft.com/graph/api/unifiedrbacapplication-post-customappscope?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c1499fe0-52b1-4b22-bed2-7a244e0e879f|
|**Consent Type**|Admin|
|**Display String**|Read and write Exchange Online RBAC configuration|
|**Description**|Allows the app to read and manage the role-based access control (RBAC) settings for your organization's Exchange Online service, on behalf of the signed-in user. This includes reading, creating, updating, and deleting Exchange management role definitions, role groups, role group membership, role assignments, management scopes, and role assignment policies.|
## Application Permission
|||
|-|-|
|**Id**|025d3225-3f02-4882-b4c0-cd5b541a4e80|
|**Display String**|Read and write Exchange Online RBAC configuration|
|**Description**|Allows the app to read and manage the role-based access control (RBAC) settings for your organization's Exchange Online service, without a signed-in user. This includes reading, creating, updating, and deleting Exchange management role definitions, role groups, role group membership, role assignments, management scopes, and role assignment policies.|
## Resources
### [customAppScope ](https://docs.microsoft.com/graph/api/resources/customappscope?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-------- |:---- |:----------- |
| customAttributes | customAppScopeAttributesDictionary | An open dictionary type that holds workload-specific properties for the scope object. |
| displayName | String | The display name of the app-specific resource represented by the app scope. Provided for display purposes since the **appScopeId** is often an immutable, non-human-readable ID. Read-only. Inherited from appScope. |
| id | String | The unique identifier of an app-specific container or resource that represents the scope of the assignment. Usually the immutable ID of the resource. The scope of an assignment determines the set of resources for which the principal has been granted access. Required. Inherited from appScope. |
| type | String | The type of app-specific resource represented by the app scope. Provided for display purposes, so a user interface can convey to the user the kind of app-specific resource represented by the app scope. Read-only. Inherited from appScope. |
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [unifiedRoleAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appScopeId|String|Identifier of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by a resource application only. For the entitlement management provider, use this property to specify a catalog. For example, `/AccessPackageCatalog/beedadfe-01d5-4025-910b-84abb9369997`. Supports `$filter` (`eq`, `in`). For example, `/roleManagement/entitlementManagement/roleAssignments?$filter=appScopeId eq '/AccessPackageCatalog/{catalog id}'`.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications, unlike app scopes that are defined and understood by a resource application only. Supports `$filter` (`eq`, `in`).|
|id|String| The unique identifier for the unifiedRoleAssignment. Key, not nullable, Read-only. |
|principalId|String| Identifier of the principal to which the assignment is granted. Supported principals are users, role-assignable groups, and service principals. Supports `$filter` (`eq`, `in`). |
|roleDefinitionId|String| Identifier of the unifiedRoleDefinition the assignment is for. Read-only. Supports `$filter` (`eq`, `in`). |
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
