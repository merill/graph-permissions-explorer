# TeamworkAppSettings.ReadWrite.All

> Allows the app to read and write the Teams app settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /teamwork/teamsAppSettings](https://docs.microsoft.com/graph/api/teamsappsettings-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /teamwork/teamsAppSettings](https://docs.microsoft.com/graph/api/teamsappsettings-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|87c556f0-2bd9-4eed-bd74-5dd8af6eaf7e|
|**Consent Type**|Admin|
|**Display String**|Read and write Teams app settings|
|**Description**|Allows the app to read and write the Teams app settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|ab5b445e-8f10-45f4-9c79-dd3f8062cc4e|
|**Display String**|Read and write Teams app settings|
|**Description**|Allows the app to read and write the Teams app settings without a signed-in user.|
## Resources
### [teamsAppSettings ](https://docs.microsoft.com/graph/api/resources/teamsappsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowUserRequestsForAppAccess|Boolean|Indicates whether users are allowed to request access to the unavailable Teams apps.|
|id|String|Unique identifier for the **teamsAppSettings** object. Inherited from entity.|
|isUserPersonalScopeResourceSpecificConsentEnabled|Boolean|Indicates whether resource-specific consent for personal scope in Teams apps is enabled for the tenant. `True` indicates that Teams apps that are allowed in the tenant and require resource-specific permissions can be installed in the personal scope. `False` blocks the installation of any Teams app that requires resource-specific permissions in the personal scope.|
