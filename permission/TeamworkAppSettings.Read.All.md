# TeamworkAppSettings.Read.All

> Allows the app to read the Teams app settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /teamwork/teamsAppSettings](https://docs.microsoft.com/graph/api/teamsappsettings-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|44e060c4-bbdc-4256-a0b9-dcc0396db368|
|**Consent Type**|User|
|**Display String**|Read Teams app settings|
|**Description**|Allows the app to read the Teams app settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|475ebe88-f071-4bd7-af2b-642952bd4986|
|**Display String**|Read Teams app settings|
|**Description**|Allows the app to read the Teams app settings without a signed-in user.|
## Resources
### [teamsAppSettings ](https://docs.microsoft.com/graph/api/resources/teamsappsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowUserRequestsForAppAccess|Boolean|Indicates whether users are allowed to request access to the unavailable Teams apps.|
|id|String|Unique identifier for the **teamsAppSettings** object. Inherited from entity.|
|isUserPersonalScopeResourceSpecificConsentEnabled|Boolean|Indicates whether resource-specific consent for personal scope in Teams apps is enabled for the tenant. `True` indicates that Teams apps that are allowed in the tenant and require resource-specific permissions can be installed in the personal scope. `False` blocks the installation of any Teams app that requires resource-specific permissions in the personal scope.|
