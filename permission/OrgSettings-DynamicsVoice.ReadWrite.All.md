# OrgSettings-DynamicsVoice.ReadWrite.All

> Allows the app to read and write organization-wide Dynamics customer voice settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/dynamics](https://docs.microsoft.com/graph/api/admindynamics-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/dynamics](https://docs.microsoft.com/graph/api/admindynamics-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4cea26fb-6967-4234-82c4-c044414743f8|
|**Consent Type**|Admin|
|**Display String**|Read and write organization-wide Dynamics customer voice settings|
|**Description**|Allows the app to read and write organization-wide Dynamics customer voice settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|c3f1cc32-8bbd-4ab6-bd33-f270e0d9e041|
|**Display String**|Read and write organization-wide Dynamics customer voice settings|
|**Description**|Allows the app to read and write organization-wide Dynamics customer voice settings, without a signed-in user.|
## Resources
### [adminDynamics ](https://docs.microsoft.com/graph/api/resources/admindynamics?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|customerVoice|customerVoiceSettings|Company-wide settings for Microsoft Dynamics 365 Customer Voice.|
|id|String|Unique ID. Inherited from entity.|
### [customerVoiceSettings ](https://docs.microsoft.com/graph/api/resources/customervoicesettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isInOrgFormsPhishingScanEnabled|Boolean|Controls whether phishing protection is run on forms created by users, blocking the creation of forms if common phishing questions are detected.|
|isRecordIdentityByDefaultEnabled|Boolean|Controls whether the names of users who fill out forms are recorded.|
|isRestrictedSurveyAccessEnabled|Boolean|Controls whether only users inside your organization can submit a response.|
