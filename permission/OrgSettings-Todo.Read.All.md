# OrgSettings-Todo.Read.All

> Allows the app to read organization-wide Microsoft To Do settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/todo](https://docs.microsoft.com/graph/api/admintodo-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7ff96f41-f022-45ba-acd8-ef3f03063d6b|
|**Consent Type**|Admin|
|**Display String**|Read organization-wide Microsoft To Do settings|
|**Description**|Allows the app to read organization-wide Microsoft To Do settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|e4d9cd09-d858-4363-9410-abb96737f0cf|
|**Display String**|Read organization-wide Microsoft To Do settings|
|**Description**|Allows the app to read organization-wide Microsoft To Do settings, without a signed-in user.|
## Resources
### [adminTodo ](https://docs.microsoft.com/graph/api/resources/admintodo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID. Inherited from entity.|
|settings|todoSettings|Company-wide settings for Microsoft Todo.|
