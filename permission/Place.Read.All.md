# Place.Read.All

> Allows the app to read your company's places (conference rooms and room lists) for calendar events and other applications, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /places/{id}](https://docs.microsoft.com/graph/api/place-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /places/microsoft.graph.room](https://docs.microsoft.com/graph/api/place-list?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|cb8f45a0-5c2e-4ea1-b803-84b870a7d7ec|
|**Consent Type**|Admin|
|**Display String**|Read all company places|
|**Description**|Allows the app to read your company's places (conference rooms and room lists) for calendar events and other applications, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|913b9306-0ce1-42b8-9137-6a7df690a760|
|**Display String**|Read all company places|
|**Description**|Allows the app to read company places (conference rooms and room lists) for calendar events and other applications, without a signed-in user.|
## Resources
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
