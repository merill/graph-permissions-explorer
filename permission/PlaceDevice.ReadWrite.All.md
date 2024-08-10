# PlaceDevice.ReadWrite.All

> Allows the app to read and write all workplace devices, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /workplace/sensorDevices/{id}](https://docs.microsoft.com/graph/api/workplacesensordevice-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /workplace/sensorDevices](https://docs.microsoft.com/graph/api/workplace-list-sensordevices?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /workplace/sensorDevices/{id}](https://docs.microsoft.com/graph/api/workplacesensordevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /workplace/sensorDevices/{id}](https://docs.microsoft.com/graph/api/workplacesensordevice-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /workplace/sensorDevices](https://docs.microsoft.com/graph/api/workplace-post-sensordevices?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /workplace/sensorDevices/ingestTelemetry](https://docs.microsoft.com/graph/api/workplacesensordevice-ingesttelemetry?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|eafd6a71-e95a-4f8a-bb6e-fb84ab7fbd9e|
|**Consent Type**|Admin|
|**Display String**|Read and write all workplace devices|
|**Description**|Allows the app to read and write all workplace devices, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|2d510721-5c4e-43cd-bfdb-ac0f8819fb92|
|**Display String**|Read and write all workplace devices|
|**Description**|Allows the app to read and write all workplace devices, without a signed-in user.|
## Resources
### [workplaceSensor ](https://docs.microsoft.com/graph/api/resources/workplacesensor?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the sensor. Optional.|
|placeId|String| The unique identifier of the place that the sensor detects. If the device is installed in a room equipped with a mailbox, this property should match the **ExternalDirectoryObjectId** or Microsoft Entra object ID of the room mailbox. If the sensor detects the same place as the location of the device, the property can be omitted. The default value is the place identifier of the device. Optional. |
|sensorId|String| The user-defined unique identifier of the sensor on the device. If the device has multiple sensors of the same type, the property must be provided to identify each sensor. If the device has only one sensor of a type, the property can be omitted. The default value is the sensor type. Optional. |
|sensorType|workplaceSensorType|The type of sensor. The possible values are: `occupancy`, `peopleCount`, `inferredOccupancy`, `heartbeat`, `bagde`, `wifi`, `unknownFutureValue`. Required. |
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
### [workplaceSensorDeviceTelemetry ](https://docs.microsoft.com/graph/api/resources/workplacesensordevicetelemetry?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|boolValue|Boolean|The value of the sensor can be `true` or `false`. Use it for sensors that report binary values, such as occupancy or heartbeat.|
|deviceId|String|The user-defined unique identifier of the device provided at the time of creation. Don't use the system generated identifier of the device.|
|intValue|Int32|The value of the sensor as an integer. Use it for sensors that report numerical values, such as people count. |
|sensorId|String|The user-defined unique identifier of the sensor on the device. Optional. If the device has multiple sensors of the same type, the property must be provided to identify each sensor. If the device has unique sensor types, the property can be omitted. The default value is the sensor type.|
|sensorType|workplaceSensorType| The type of sensor. The possible values are: `occupancy`, `peopleCount`, `inferredOccupancy`, `heartbeat`, `badge`, `wifi`, `unknownFutureValue`.|
|timestamp|DateTimeOffset|The date and time when the sensor measured and reported its value. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|eventValue| workplaceSensorEventValue| The extra values associated with badge and Wi-Fi signals. |
|locationHint|String|The additional information to indicate the location of the device. |
