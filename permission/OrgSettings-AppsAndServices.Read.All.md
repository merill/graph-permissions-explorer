# OrgSettings-AppsAndServices.Read.All

> Allows the app to read organization-wide apps and services settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/appsAndServices](https://docs.microsoft.com/graph/api/adminappsandservices-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1e9b7a7e-4d64-44ff-acf5-2e9651c1519f|
|**Consent Type**|Admin|
|**Display String**|Read organization-wide apps and services settings|
|**Description**|Allows the app to read organization-wide apps and services settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|56c84fa9-ea1f-4a15-90f2-90ef41ece2c9|
|**Display String**|Read organization-wide apps and services settings|
|**Description**|Allows the app to read organization-wide apps and services settings, without a signed-in user.|
## Resources
### [adminAppsAndServices ](https://docs.microsoft.com/graph/api/resources/adminappsandservices?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID. Inherited from entity.|
|settings|appsAndServicesSettings|Company-wide settings for apps and services.|
