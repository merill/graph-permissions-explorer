# Policy.ReadWrite.DeviceConfiguration

> Allows the app to read and write your organization's device configuration policies on behalf of the signed-in user.  For example, device registration policy can limit initial provisioning controls using quota restrictions, additional authentication and authorization checks.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /policies/deviceRegistrationPolicy](https://docs.microsoft.com/graph/api/deviceregistrationpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /policies/deviceRegistrationPolicy](https://docs.microsoft.com/graph/api/deviceregistrationpolicy-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|40b534c3-9552-4550-901b-23879c90bcf9|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's device configuration policies|
|**Description**|Allows the app to read and write your organization's device configuration policies on behalf of the signed-in user.  For example, device registration policy can limit initial provisioning controls using quota restrictions, additional authentication and authorization checks.|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [azureADJoinPolicy ](https://docs.microsoft.com/graph/api/resources/azureadjoinpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedToJoin|deviceRegistrationMembership|Determines if Microsoft Entra join is allowed.|
|isAdminConfigurable|Boolean|Determines if administrators can modify this policy.|
|localAdmins|localAdminSettings|Determines who becomes a local administrator on joined devices.|
### [azureADRegistrationPolicy ](https://docs.microsoft.com/graph/api/resources/azureadregistrationpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedToRegister|deviceRegistrationMembership|Determines if Microsoft Entra registered is allowed. |
|isAdminConfigurable|Boolean|Determines if administrators can modify this policy.|
### [deviceRegistrationPolicy ](https://docs.microsoft.com/graph/api/resources/deviceregistrationpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|azureADJoin|azureADJoinPolicy|Specifies the authorization policy for controlling registration of new devices using **Microsoft Entra join** within your organization. Required. For more information, see What is a device identity?.|
|azureADRegistration|azureADRegistrationPolicy|Specifies the authorization policy for controlling registration of new devices using **Microsoft Entra registered** within your organization. Required. For more information, see What is a device identity?.|
|description|String|The description of the device registration policy. It's always set to `Tenant-wide policy that manages intial provisioning controls using quota restrictions, additional authentication and authorization checks`. Read-only.|
|displayName|String|The name of the device registration policy. It's always set to `Device Registration Policy`. Read-only.|
|id|String| The identifier of the device registration policy. It's always set to `deviceRegistrationPolicy`. Read-only.|
|localAdminPassword|localAdminPasswordSettings| Specifies the setting for **Local Admin Password Solution (LAPS)** within your organization.|
|multiFactorAuthConfiguration|multiFactorAuthConfiguration|Specifies the authentication policy for a user to complete registration using **Microsoft Entra join** or **Microsoft Entra registered** within your organization. The possible values are: `notRequired`, `required`, `unknownFutureValue`. The default value is `notRequired`.|
|userDeviceQuota|Int32|Specifies the maximum number of devices that a user can have within your organization before blocking new device registrations. The default value is set to 50. If this property isn't specified during the policy update operation, it's automatically reset to `0` to indicate that users aren't allowed to join any devices.|
### [localAdminPasswordSettings ](https://docs.microsoft.com/graph/api/resources/localadminpasswordsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabled|Boolean|Specifies whether this policy scope is configurable by the admin. The default value is `false`. An admin can set it to true to enable Local Admin Password Solution (LAPS) within their organzation.|
