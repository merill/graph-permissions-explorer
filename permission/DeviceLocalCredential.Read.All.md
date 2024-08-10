# DeviceLocalCredential.Read.All

> Allows the app to read device local credential properties including passwords, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /deviceLocalCredentials](https://docs.microsoft.com/graph/api/directory-list-devicelocalcredentials?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceLocalCredentials/{deviceId}](https://docs.microsoft.com/graph/api/devicelocalcredentialinfo-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /directory/deviceLocalCredentials](https://docs.microsoft.com/graph/api/directory-list-devicelocalcredentials?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/deviceLocalCredentials/{deviceId}](https://docs.microsoft.com/graph/api/devicelocalcredentialinfo-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|280b3b69-0437-44b1-bc20-3b2fca1ee3e9|
|**Consent Type**|Admin|
|**Display String**|Read device local credential passwords|
|**Description**|Allows the app to read device local credential properties including passwords, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|884b599e-4d48-43a5-ba94-15c414d00588|
|**Display String**|Read device local credential passwords|
|**Description**|Allows the app to read device local credential properties including passwords, without a signed-in user.|
## Resources
### [deviceLocalCredential ](https://docs.microsoft.com/graph/api/resources/devicelocalcredential?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accountName|String| The name of the local admin account for which LAPS is enabled.|
|accountSid|String|The SID of the local admin account for which LAPS is enabled.|
|backupDateTime|DateTimeOffset|When the local administrator account credential for the device object was backed up to Azure Active Directory.|
|passwordBase64|String|The password for the local administrator account that is backed up to Azure Active Directory and returned as a Base64 encoded value.|
### [deviceLocalCredentialInfo ](https://docs.microsoft.com/graph/api/resources/devicelocalcredentialinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|credentials|deviceLocalCredential collection|The credentials of the device's local administrator account backed up to Azure Active Directory.|
|deviceName|String|Display name of the device that the local credentials are associated with.|
|id|String| ID of the device that the local credentials are associated with Key. This is same as **deviceId** in the device object.|
|lastBackupDateTime|DateTimeOffset|When the local administrator account credential was backed up to Azure Active Directory.|
|refreshDateTime|DateTimeOffset|When the local administrator account credential will be refreshed and backed up to Azure Active Directory.|
