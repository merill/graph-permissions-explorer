# ReportSettings.Read.All

> Allows the app to read admin report settings, such as whether to display concealed information in reports, on behalf of the signed-in user
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/reportSettings](https://docs.microsoft.com/graph/api/adminreportsettings-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|84fac5f4-33a9-4100-aa38-a20c6d29e5e7|
|**Consent Type**|Admin|
|**Display String**|Read admin report settings|
|**Description**|Allows the app to read admin report settings, such as whether to display concealed information in reports, on behalf of the signed-in user|
## Application Permission
|||
|-|-|
|**Id**|ee353f83-55ef-4b78-82da-555bfa2b4b95|
|**Display String**|Read all admin report settings|
|**Description**|Allows the app to read all admin report settings, such as whether to display concealed information in reports, without a signed-in user.|
## Resources
### [adminReportSettings ](https://docs.microsoft.com/graph/api/resources/adminreportsettings?view=graph-rest-1.0&tabs=http)
| Property       | Type           | Description                                 |
| -------------- | -------------- | ------------------------------------------- |
| displayConcealedNames | Boolean | If set to `true`, all reports will conceal user information such as usernames, groups, and sites. If `false`, all reports will show identifiable information. This property represents a setting in the Microsoft 365 admin center. Required. |
