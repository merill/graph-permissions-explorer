# ReportSettings.ReadWrite.All

> Allows the app to read and update admin report settings, such as whether to display concealed information in reports, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/reportSettings](https://docs.microsoft.com/graph/api/adminreportsettings-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/reportSettings](https://docs.microsoft.com/graph/api/adminreportsettings-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b955410e-7715-4a88-a940-dfd551018df3|
|**Consent Type**|Admin|
|**Display String**|Read and write admin report settings|
|**Description**|Allows the app to read and update admin report settings, such as whether to display concealed information in reports, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|2a60023f-3219-47ad-baa4-40e17cd02a1d|
|**Display String**|Read and write all admin report settings|
|**Description**|Allows the app to read and update all admin report settings, such as whether to display concealed information in reports, without a signed-in user.|
## Resources
### [adminReportSettings ](https://docs.microsoft.com/graph/api/resources/adminreportsettings?view=graph-rest-1.0&tabs=http)
| Property       | Type           | Description                                 |
| -------------- | -------------- | ------------------------------------------- |
| displayConcealedNames | Boolean | If set to `true`, all reports will conceal user information such as usernames, groups, and sites. If `false`, all reports will show identifiable information. This property represents a setting in the Microsoft 365 admin center. Required. |
