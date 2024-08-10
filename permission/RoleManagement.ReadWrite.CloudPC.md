# RoleManagement.ReadWrite.CloudPC

> Allows the app to read and manage the Cloud PC role-based access control (RBAC) settings, on behalf of the signed-in user. This includes reading and managing Cloud PC role definitions and role assignments.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /roleManagement/deviceManagement/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /roleManagement/deviceManagement/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /roleManagement/deviceManagement/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-post-roledefinitions?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|501d06f8-07b8-4f18-b5c6-c191a4af7a82|
|**Consent Type**|Admin|
|**Display String**|Read and write Cloud PC RBAC settings|
|**Description**|Allows the app to read and manage the Cloud PC role-based access control (RBAC) settings, on behalf of the signed-in user. This includes reading and managing Cloud PC role definitions and role assignments.|
## Application Permission
|||
|-|-|
|**Id**|274d0592-d1b6-44bd-af1d-26d259bcb43a|
|**Display String**|Read and write all Cloud PC RBAC settings|
|**Description**|Allows the app to read and manage the Cloud PC role-based access control (RBAC) settings, without a signed-in user. This includes reading and managing Cloud PC role definitions and memberships.|
## Resources
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
### [unifiedRolePermission ](https://docs.microsoft.com/graph/api/resources/unifiedrolepermission?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|allowedResourceActions|String collection| Set of tasks that can be performed on a resource. Required. |
|condition|String| Optional constraints that must be met for the permission to be effective. Not supported for custom roles.|
|excludedResourceActions|String collection| Set of tasks that may not be performed on a resource. Not yet supported. |
