# OrgSettings-Todo.ReadWrite.All

> Allows the app to read and write organization-wide Microsoft To Do settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/todo](https://docs.microsoft.com/graph/api/admintodo-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/todo](https://docs.microsoft.com/graph/api/admintodo-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|087502c2-5263-433e-abe3-8f77231a0627|
|**Consent Type**|Admin|
|**Display String**|Read and write organization-wide Microsoft To Do settings|
|**Description**|Allows the app to read and write organization-wide Microsoft To Do settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|5febc9da-e0d0-4576-bd13-ae70b2179a39|
|**Display String**|Read and write organization-wide Microsoft To Do settings|
|**Description**|Allows the app to read and write organization-wide Microsoft To Do settings, without a signed-in user.|
## Resources
### [adminTodo ](https://docs.microsoft.com/graph/api/resources/admintodo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID. Inherited from entity.|
|settings|todoSettings|Company-wide settings for Microsoft Todo.|
### [todoSettings ](https://docs.microsoft.com/graph/api/resources/todosettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isExternalJoinEnabled|Boolean|Controls whether users can join lists from users external to your organization.|
|isExternalShareEnabled|Boolean|Controls whether users can share lists with external users.|
|isPushNotificationEnabled|Boolean|Controls whether push notifications are enabled for your users.|
