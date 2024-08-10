# SchedulePermissions.ReadWrite.All

> Allows the app to read/write schedule permissions for a specific role in Shifts application on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /team/{teamId}/schedule/shiftsRoleDefinitions/{roleId}](https://docs.microsoft.com/graph/api/shiftsroledefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /team/{teamId}/schedule/shiftsRoleDefinitions/{roleId}](https://docs.microsoft.com/graph/api/shiftsroledefinition-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|07919803-6073-4cd8-bc55-28077db0ee10|
|**Consent Type**|Admin|
|**Display String**|Read/Write schedule permissions for a role.|
|**Description**|Allows the app to read/write schedule permissions for a specific role in Shifts application on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7239b71d-b402-4150-b13d-78ecfe8df441|
|**Display String**|Read/Write schedule permissions for a role|
|**Description**|Allows the app to read/write schedule permissions for a specific role in Shifts application without a signed-in user.|
## Resources
### [shiftsRoleDefinition ](https://docs.microsoft.com/graph/api/resources/shiftsroledefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of the role.|
|displayName|String|The display name of the role.|
|id|String|The ID of the role.|
|shiftsRolePermissions|shiftsRolePermission collection|The collection of role permissions within the role.|
### [shiftsRolePermission ](https://docs.microsoft.com/graph/api/resources/shiftsrolepermission?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedResourceActions|String collection|The permissions that are allowed for a role. Permissions that aren't in this collection are disabled.|
