# OrgSettings-AppsAndServices.ReadWrite.All

> Allows the app to read and write organization-wide apps and services settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/appsAndServices](https://docs.microsoft.com/graph/api/adminappsandservices-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/appsAndServices](https://docs.microsoft.com/graph/api/adminappsandservices-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c167b0e7-47c0-48e8-9eee-9892f58018fa|
|**Consent Type**|Admin|
|**Display String**|Read and write organization-wide apps and services settings|
|**Description**|Allows the app to read and write organization-wide apps and services settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|4a8e4191-c1c8-45f8-b801-f9a1a5ee6ad3|
|**Display String**|Read and write organization-wide apps and services settings|
|**Description**|Allows the app to read and write organization-wide apps and services settings, without a signed-in user.|
## Resources
### [adminAppsAndServices ](https://docs.microsoft.com/graph/api/resources/adminappsandservices?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID. Inherited from entity.|
|settings|appsAndServicesSettings|Company-wide settings for apps and services.|
### [appsAndServicesSettings ](https://docs.microsoft.com/graph/api/resources/appsandservicessettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isAppAndServicesTrialEnabled|Boolean|Controls whether users can start trial subscriptions for apps and services in your organization.|
|isOfficeStoreEnabled|Boolean|Controls whether users can access the Microsoft Store.|
