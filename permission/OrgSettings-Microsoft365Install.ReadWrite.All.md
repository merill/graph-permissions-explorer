# OrgSettings-Microsoft365Install.ReadWrite.All

> Allows the app to read and write organization-wide Microsoft 365 apps installation settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /admin/microsoft365Apps/installationOptions](https://docs.microsoft.com/graph/api/m365appsinstallationoptions-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /admin/microsoft365Apps/installationOptions](https://docs.microsoft.com/graph/api/m365appsinstallationoptions-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1ff35e91-19eb-42d8-aa2d-cc9891127ae5|
|**Consent Type**|Admin|
|**Display String**|Read and write organization-wide Microsoft 365 apps installation settings|
|**Description**|Allows the app to read and write organization-wide Microsoft 365 apps installation settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|83f7232f-763c-47b2-a097-e35d2cbe1da5|
|**Display String**|Read and write organization-wide Microsoft 365 apps installation settings|
|**Description**|Allows the app to read and write organization-wide Microsoft 365 apps installation settings, without a signed-in user. |
