# PlaceDevice.Read.All

> Allows the app to read all workplace devices, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /workplace/sensorDevices](https://docs.microsoft.com/graph/api/workplace-list-sensordevices?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /workplace/sensorDevices/{id}](https://docs.microsoft.com/graph/api/workplacesensordevice-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4c7f93d2-6b0b-4e05-91aa-87842f0a2142|
|**Consent Type**|Admin|
|**Display String**|Read all workplace devices|
|**Description**|Allows the app to read all workplace devices, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|8b724a84-ceac-4fd9-897e-e31ba8f2d7a3|
|**Display String**|Read all workplace devices|
|**Description**|Allows the app to read all workplace devices, without a signed-in user.|
## Resources
### [workplaceSensorDevice ](https://docs.microsoft.com/graph/api/resources/workplacesensordevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String| The description of the device. |
|deviceId|String| The user-defined unique identifier of the device provided at the time of creation. |
|displayName|String| The display name of the device. |
|id|String| The unique identifier of the device. It's system generated and a user can't change it. Inherited from entity.|
|ipV4Address|String| The IPv4 address of the device. |
|ipV6Address|String| The IPv6 address of the device. |
|macAddress|String| The MAC address of the device. |
|manufacturer|String| The manufacturer of the device. |
|placeId|String| The unique identifier of the place where the device is located. If the device is installed in a room equipped with a mailbox, this property should match the **ExternalDirectoryObjectId** or Microsoft Entra object ID of the room mailbox. |
|sensors|workplaceSensor collection| A list of sensors associated with the device that collect and report data about physical or environmental conditions, such as occupancy, people count, inferred occupancy, temperature, and more. |
|tags|String collection| A list of custom tags associated with the device. |
