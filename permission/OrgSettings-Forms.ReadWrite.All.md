# OrgSettings-Forms.ReadWrite.All

> Allows the app to read and write organization-wide Microsoft Forms settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/forms](https://docs.microsoft.com/graph/api/adminforms-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/forms](https://docs.microsoft.com/graph/api/adminforms-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|346c19ff-3fb2-4e81-87a0-bac9e33990c1|
|**Consent Type**|Admin|
|**Display String**|Read and write organization-wide Microsoft Forms settings|
|**Description**|Allows the app to read and write organization-wide Microsoft Forms settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|2cb92fee-97a3-4034-8702-24a6f5d0d1e9|
|**Display String**|Read and write organization-wide Microsoft Forms settings|
|**Description**|Allows the app to read and write organization-wide Microsoft Forms settings, without a signed-in user.|
## Resources
### [adminForms ](https://docs.microsoft.com/graph/api/resources/adminforms?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID. Inherited from entity.|
|settings|formsSettings|Company-wide settings for Microsoft Forms.|
### [formsSettings ](https://docs.microsoft.com/graph/api/resources/formssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isBingImageSearchEnabled|Boolean|Controls whether users can add images from Bing to forms.|
|isExternalSendFormEnabled|Boolean|Controls whether users can send a link to a form to an external user.|
|isExternalShareCollaborationEnabled|Boolean|Controls whether users can collaborate on a form layout and structure with an external user.|
|isExternalShareResultEnabled|Boolean|Controls whether users can share form results with external users.|
|isExternalShareTemplateEnabled|Boolean|Controls whether users can share form templates with external users.|
|isInOrgFormsPhishingScanEnabled|Boolean|Controls whether phishing protection is run on forms created by users, blocking the creation of forms if common phishing questions are detected.|
|isRecordIdentityByDefaultEnabled|Boolean|Controls whether the names of users who fill out forms are recorded.|
