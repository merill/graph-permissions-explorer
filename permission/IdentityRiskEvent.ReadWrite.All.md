# IdentityRiskEvent.ReadWrite.All

> Allows the app to read and update identity risk event information for all users in your organization on behalf of the signed-in user. Update operations include confirming risk event detections. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[POST /auditLogs/signIns/confirmCompromised](https://docs.microsoft.com/graph/api/signin-confirmcompromised?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /auditLogs/signIns/confirmSafe](https://docs.microsoft.com/graph/api/signin-confirmsafe?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9e4862a5-b68f-479e-848a-4e07e25c9916|
|**Consent Type**|Admin|
|**Display String**|Read and write risk event information|
|**Description**|Allows the app to read and update identity risk event information for all users in your organization on behalf of the signed-in user. Update operations include confirming risk event detections. |
## Application Permission
|||
|-|-|
|**Id**|db06fb33-1953-4b7b-a2ac-f1e2c854f7ae|
|**Display String**|Read and write all risk detection information|
|**Description**|Allows the app to read and update identity risk detection information for your organization without a signed-in user. Update operations include confirming risk event detections. |
