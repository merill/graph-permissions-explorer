# OrgSettings-Forms.Read.All

> Allows the app to read organization-wide Microsoft Forms settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/forms](https://docs.microsoft.com/graph/api/adminforms-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|210051a0-1ffc-435c-ae76-02d226d05752|
|**Consent Type**|Admin|
|**Display String**|Read organization-wide Microsoft Forms settings|
|**Description**|Allows the app to read organization-wide Microsoft Forms settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|434d7c66-07c6-4b1f-ab21-417cf2cdaaca|
|**Display String**|Read organization-wide Microsoft Forms settings|
|**Description**|Allows the app to read organization-wide Microsoft Forms settings, without a signed-in user.|
## Resources
### [adminForms ](https://docs.microsoft.com/graph/api/resources/adminforms?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID. Inherited from entity.|
|settings|formsSettings|Company-wide settings for Microsoft Forms.|
