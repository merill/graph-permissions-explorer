# Place.ReadWrite.All

> Allows the app to manage organization places (conference rooms and room lists) for calendar events and other applications, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[PATCH /places/{id | emailAddress}](https://docs.microsoft.com/graph/api/place-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4c06a06a-098a-4063-868e-5dfee3827264|
|**Consent Type**|Admin|
|**Display String**|Read and write organization places|
|**Description**|Allows the app to manage organization places (conference rooms and room lists) for calendar events and other applications, on behalf of the signed-in user.|
## Resources
### [outlookGeoCoordinates ](https://docs.microsoft.com/graph/api/resources/outlookgeocoordinates?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|accuracy|double|The accuracy of the latitude and longitude. As an example, the accuracy can be measured in meters, such as the latitude and longitude are accurate to within 50 meters.|
|altitude|double|The altitude of the location.|
|altitudeAccuracy|double|The accuracy of the altitude.|
|latitude|double|The latitude of the location.|
|longitude|double|The longitude of the location.|
### [physicalAddress ](https://docs.microsoft.com/graph/api/resources/physicaladdress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|city|String|The city.|
|countryOrRegion|String|The country or region. It's a free-format string value, for example, "United States".|
|postalCode|String|The postal code.|
|state|String|The state.|
|street|String|The street.|
### [place ](https://docs.microsoft.com/graph/api/resources/place?view=graph-rest-1.0&tabs=http)
| Property       | Type                                              | Description |
|:---------------|:--------------------------------------------------|:--------|
| address        | physicalAddress             | The street address of the place. |
| displayName    | String                                            | The name associated with the place. |
| geoCoordinates | outlookGeoCoordinates | Specifies the place location in latitude, longitude, and (optionally) altitude coordinates. |
| id             | String                                            | A unique identifier for the place. Read-only. This identifier isn't immutable and can change if there are changes to the mailbox or the tenant configuration. The beta version of this API has a new property added called **placeId**, which provides an immutable ID. |
| phone          | String                                            | The phone number of the place. |
### [room ](https://docs.microsoft.com/graph/api/resources/room?view=graph-rest-1.0&tabs=http)
| Property               | Type                                              | Description |
|:-----------------------|:--------------------------------------------------|:--|
| address                | physicalAddress             | The street address of the room. |
| audioDeviceName        | String                                            | Specifies the name of the audio device in the room. |
| bookingType            | bookingType                | Type of room. Possible values are `standard`, and `reserved`. |
| building               | String                                            | Specifies the building name or building number that the room is in. |
| capacity               | Int32                                             | Specifies the capacity of the room. |
| displayDeviceName      | String                                            | Specifies the name of the display device in the room. |
| displayName            | String                                            | The name associated with the room. |
| emailAddress           | String                                            | Email address of the room. |
| floorLabel             | String                                            | Specifies a descriptive label for the floor, for example, P. |
| floorNumber            | Int32                                             | Specifies the floor number that the room is on. |
| geoCoordinates         | outlookGeoCoordinates | Specifies the room location in latitude, longitude, and optionally, altitude coordinates. |
| id                     | String                                            | Unique identifier for the room. Read-only. This identifier isn't immutable and can change if there are changes to the mailbox or the tenant configuration. The beta version of this API has a new property added called **placeId**, which provides an immutable ID. |
| isWheelChairAccessible | Boolean                                           | Specifies whether the room is wheelchair accessible. |
| label                  | String                                            | Specifies a descriptive label for the room, for example, a number or name. |
| nickname               | String                                            | Specifies a nickname for the room, for example, "conf room". |
| phone                  | String                                            | The phone number of the room. |
| tags                   | String collection                                 | Specifies other features of the room, for example, details like the type of view or furniture type. |
| videoDeviceName        | String                                            | Specifies the name of the video device in the room. |
### [roomList ](https://docs.microsoft.com/graph/api/resources/roomlist?view=graph-rest-1.0&tabs=http)
| Property       | Type                                              | Description |
|:---------------|:--------------------------------------------------|:--------|
| address        | physicalAddress             | The street address of the room list. |
| displayName    | String                                            | The name associated with the room list. |
| emailAddress   | String                                            | The email address of the room list. |
| geoCoordinates | outlookGeoCoordinates | Specifies the roomlist location in latitude, longitude, and (optionally) altitude coordinates. |
| id             | String                                            | Unique identifier for the room list. Read-only. This identifier isn't immutable and can change if there are changes to the mailbox or the tenant configuration. The beta version of this API has a new property added called **placeId**, which provides an immutable ID |
| phone          | String                                            | The phone number of the room list. |
### [workspace ](https://docs.microsoft.com/graph/api/resources/workspace?view=graph-rest-1.0&tabs=http)
| Property               | Type                                              | Description |
|:-----------------------|:--------------------------------------------------|:--|
| address                | physicalAddress             | The street address of the workspace. |
| building               | String                                            | Specifies the building name or building number that the workspace is in. |
| capacity               | Int32                                             | Specifies the capacity of the workspace. |
| displayName            | String                                            | The name associated with the workspace. |
| emailAddress           | String                                            | Email address of the workspace. |
| floorLabel             | String                                            | Specifies a descriptive label for the floor, for example, P. |
| floorNumber            | Int32                                             | Specifies the floor number that the workspace is on. |
| geoCoordinates         | outlookGeoCoordinates | Specifies the workspace location in latitude, longitude, and optionally, altitude coordinates. |
| id                     | String                                            | Unique identifier for the workspace. Read-only. This identifier isn't immutable and can change if there are changes to the mailbox or to the tenant configuration. |
| isWheelChairAccessible | Boolean                                           | Specifies whether the workspace is wheelchair accessible. |
| label                  | String                                            | Specifies a descriptive label for the workspace, for example, a number or name. |
| nickname               | String                                            | Specifies a nickname for the workspace, for example, "quiet workspace". |
| phone                  | String                                            | The phone number of the workspace. |
| placeId                | String                                            | A unique, immutable identifier for the workspace. Read-only. The value of this identifier is equal to the **ExternalDirectoryObjectId** returned from the `Get-Mailbox` cmdlet. |
| tags                   | String collection                                 | Specifies other features of the workspace; for example, the type of view or furniture type. |
