# PlaceDeviceTelemetry.ReadWrite.All

> Allows the app to read and write telemetry for all workplace devices, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[POST /workplace/sensorDevices/ingestTelemetry](https://docs.microsoft.com/graph/api/workplacesensordevice-ingesttelemetry?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|27fc435f-44e2-4b30-bf3c-e0ce74aed618|
|**Display String**|Read and write telemetry for all workplace devices.|
|**Description**|Allows the app to read and write telemetry for all workplace devices, without a signed-in user.|
## Resources
### [workplaceSensor ](https://docs.microsoft.com/graph/api/resources/workplacesensor?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the sensor. Optional.|
|placeId|String| The unique identifier of the place that the sensor detects. If the device is installed in a room equipped with a mailbox, this property should match the **ExternalDirectoryObjectId** or Microsoft Entra object ID of the room mailbox. If the sensor detects the same place as the location of the device, the property can be omitted. The default value is the place identifier of the device. Optional. |
|sensorId|String| The user-defined unique identifier of the sensor on the device. If the device has multiple sensors of the same type, the property must be provided to identify each sensor. If the device has only one sensor of a type, the property can be omitted. The default value is the sensor type. Optional. |
|sensorType|workplaceSensorType|The type of sensor. The possible values are: `occupancy`, `peopleCount`, `inferredOccupancy`, `heartbeat`, `bagde`, `wifi`, `unknownFutureValue`. Required. |
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
