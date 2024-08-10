# UserWindowsSettings.Read

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/settings/windows](https://docs.microsoft.com/graph/api/usersettings-list-windows?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/settings/windows/{windowsSettingId}](https://docs.microsoft.com/graph/api/windowssetting-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/settings/windows/{windowsSettingId}/instances](https://docs.microsoft.com/graph/api/windowssetting-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/settings/windows/{windowsSettingId}/instances/{windowsSettingInstanceId}](https://docs.microsoft.com/graph/api/windowssettinginstance-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
### [enums](https://docs.microsoft.com/graph/api/resources/enums?view=graph-rest-1.0&tabs=http)

### [windowsSetting ](https://docs.microsoft.com/graph/api/resources/windowssetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the object.|
|payloadType|String|The type of setting payloads contained in the *instances* navigation property.|
|settingType|**windowsSettingType**|The type of setting. Possible values are: `roaming`, `backup`, `unknownFutureValue`.|
|windowsDeviceId|String|A unique identifier for the device the setting might belong to if it is of the **s
### [windowsSettingInstance ](https://docs.microsoft.com/graph/api/resources/windowssettinginstance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Set by the server. Represents the dateTime in UTC when the object was created on the server.|
|expirationDateTime|DateTimeOffset|Set by the server. The object expires at the specified dateTime in UTC, making it unavailable after that time.|
|id|String|The unique identifier of the object. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|Set by the server if not provided in the request from the Windows client device. Refers to the user's Windows device that modified the object at the specified dateTime in UTC.|
|payload|String|Base64-encoded JSON setting value.|
