# TeamworkDevice.Read.All

> Allow the app to read the management data for Teams devices on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /teamwork/devices](https://docs.microsoft.com/graph/api/teamworkdevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teamwork/devices/{teamworkDeviceId}](https://docs.microsoft.com/graph/api/teamworkdevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teamwork/devices/{teamworkDeviceId}/activity](https://docs.microsoft.com/graph/api/teamworkdeviceactivity-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teamwork/devices/{teamworkDeviceId}/configuration](https://docs.microsoft.com/graph/api/teamworkdeviceconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teamwork/devices/{teamworkDeviceId}/health](https://docs.microsoft.com/graph/api/teamworkdevicehealth-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teamwork/devices/{teamworkDeviceId}/operations](https://docs.microsoft.com/graph/api/teamworkdeviceoperation-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teamwork/devices/{teamworkDeviceId}/operations/{teamworkDeviceOperationId}](https://docs.microsoft.com/graph/api/teamworkdeviceoperation-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b659488b-9d28-4208-b2be-1c6652b3c970|
|**Consent Type**|Admin|
|**Display String**|Read Teams devices|
|**Description**|Allow the app to read the management data for Teams devices on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|0591bafd-7c1c-4c30-a2a5-2b9aacb1dfe8|
|**Display String**|Read Teams devices|
|**Description**|Allow the app to read the management data for Teams devices, without a signed-in user.|
## Resources
### [teamworkDevice ](https://docs.microsoft.com/graph/api/resources/teamworkdevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activityState|teamworkDeviceActivityState|The activity state of the device. The possible values are: `unknown`, `busy`, `idle`, `unavailable`, `unknownFutureValue`.|
|companyAssetTag|String|The company asset tag assigned by the admin on the device.|
|createdBy|identitySet|Identity of the user who enrolled the device to the tenant.|
|createdDateTime|DateTimeOffset|The UTC date and time when the device was enrolled to the tenant.|
|currentUser|teamworkUserIdentity|The signed-in user on the device.|
|deviceType|teamworkDeviceType|The type of device. The possible values are: `unknown`, `ipPhone`, `teamsRoom`, `surfaceHub`, `collaborationBar`, `teamsDisplay`, `touchConsole`, `lowCostPhone`, `teamsPanel`, `sip`, `sipAnalog`, `unknownFutureValue`.|
|hardwareDetail|teamworkHardwareDetail|A collection of hardware-related properties. For example, **oemSerialNumber** and **model**.|
|healthStatus|teamworkDeviceHealthStatus|The health status of the device. The possible values are: `unknown`, `offline`, `critical`, `nonUrgent`, `healthy`, `unknownFutureValue`.|
|id|String|Device identifier. Inherited from entity.|
|lastModifiedBy|identitySet|Identity of the user who last modified the device details.|
|lastModifiedDateTime|DateTimeOffset|The UTC date and time when the device detail was last modified.|
|notes|String|The notes added by the admin to the device.|
### [teamworkDeviceActivity ](https://docs.microsoft.com/graph/api/resources/teamworkdeviceactivity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activePeripherals|teamworkActivePeripherals|The active peripheral devices attached to the device.|
|createdBy|identitySet|Identity of the user who created the device activity document.|
|createdDateTime|DateTimeOffset|The UTC date and time when the device activity document was created.|
|id|String|Document identifier. Inherited from entity.|
|lastModifiedBy|identitySet|Identity of the user who last modified the device activity details.|
|lastModifiedDateTime|DateTimeOffset|The UTC date and time when the device activity detail was last modified.|
### [teamworkDeviceConfiguration ](https://docs.microsoft.com/graph/api/resources/teamworkdeviceconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|cameraConfiguration|teamworkCameraConfiguration|The camera configuration. Applicable only for Microsoft Teams Rooms-enabled devices.|
|createdBy|identitySet|Identity of the user who created the device configuration document.|
|createdDateTime|DateTimeOffset|The UTC date and time when the device configuration document was created.|
|displayConfiguration|teamworkDisplayConfiguration|The display configuration.|
|hardwareConfiguration|teamworkHardwareConfiguration|The hardware configuration. Applicable only for Teams Rooms-enabled devices.|
|id|String|Document identifier. Inherited from entity.|
|lastModifiedBy|identitySet|Identity of the user who last modified the device configuration.|
|lastModifiedDateTime|DateTimeOffset|The UTC date and time when the device configuration was last modified.|
|microphoneConfiguration|teamworkMicrophoneConfiguration|The microphone configuration. Applicable only for Teams Rooms-enabled devices.|
|softwareVersions|teamworkDeviceSoftwareVersions|Information related to software versions for the device, such as firmware, operating system, Teams client, and admin agent.|
|speakerConfiguration|teamworkSpeakerConfiguration|The speaker configuration. Applicable only for Teams Rooms-enabled devices.|
|systemConfiguration|teamworkSystemConfiguration|The system configuration. Not applicable for Teams Rooms-enabled devices.|
|teamsClientConfiguration|teamworkTeamsClientConfiguration|The Teams client configuration. Applicable only for Teams Rooms-enabled devices.|
### [teamworkDeviceHealth ](https://docs.microsoft.com/graph/api/resources/teamworkdevicehealth?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|connection|teamworkConnection|Information about the connection status.|
|createdBy|identitySet|Identity of the user who created the device health document.|
|createdDateTime|DateTimeOffset|The UTC date and time when the device health document was created.|
|hardwareHealth|teamworkHardwareHealth|Health details about the device hardware.|
|id|String|Doucument identifier. Inherited from entity.|
|lastModifiedBy|identitySet|Identity of the user who last modified the device health details.|
|lastModifiedDateTime|DateTimeOffset|The UTC date and time when the device health detail was last modified.|
|loginStatus|teamworkLoginStatus|The login status of Microsoft Teams, Skype for Business, and Exchange.|
|peripheralsHealth|teamworkPeripheralsHealth|Health details about all peripherals (for example, speaker and microphone) attached to a device.|
|softwareUpdateHealth|teamworkSoftwareUpdateHealth|Software updates available for the device.|
### [teamworkDeviceOperation ](https://docs.microsoft.com/graph/api/resources/teamworkdeviceoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|completedDateTime|DateTimeOffset|Time at which the operation reached a final state (for example, `Successful`, `Failed`, and `Cancelled`).|
|createdBy|identitySet|Identity of the user who created the device operation.|
|createdDateTime|DateTimeOffset|The UTC date and time when the device operation was created.|
|error|operationError|Error details are available only in case of a failed status.|
|id|String|Document identifier. Inherited from entity.|
|lastActionBy|identitySet|Identity of the user who last modified the device operation.|
|lastActionDateTime|DateTimeOffset|The UTC date and time when the device operation was last modified.|
|operationType|teamworkDeviceOperationType|Type of async operation on a device. The possible values are: `deviceRestart`, `configUpdate`, `deviceDiagnostics`, `softwareUpdate`, `deviceManagementAgentConfigUpdate`, `remoteLogin`, `remoteLogout`, `unknownFutureValue`.|
|startedDateTime|DateTimeOffset|Time at which the operation was started.|
|status|String|The current status of the async operation, for example, `Queued`, `Scheduled`, `InProgress`,  `Successful`, `Cancelled`, and `Failed`.|
