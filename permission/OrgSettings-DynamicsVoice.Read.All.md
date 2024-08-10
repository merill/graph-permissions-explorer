# OrgSettings-DynamicsVoice.Read.All

> Allows the app to read organization-wide Dynamics customer voice settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /admin/dynamics](https://docs.microsoft.com/graph/api/admindynamics-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9862d930-5aec-4a98-8d4f-7277a8db9bcb|
|**Consent Type**|Admin|
|**Display String**|Read organization-wide Dynamics customer voice settings|
|**Description**|Allows the app to read organization-wide Dynamics customer voice settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|c18ae2dc-d9f3-4495-a93f-18980a0e159f|
|**Display String**|Read organization-wide Dynamics customer voice settings|
|**Description**|Allows the app to read organization-wide Dynamics customer voice settings, without a signed-in user.|
## Resources
### [adminDynamics ](https://docs.microsoft.com/graph/api/resources/admindynamics?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|customerVoice|customerVoiceSettings|Company-wide settings for Microsoft Dynamics 365 Customer Voice.|
|id|String|Unique ID. Inherited from entity.|
