# UserShiftPreferences.Read.All

> Allows the app to read all users' shift schedule preferences without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /users/{userId}/settings/shiftPreferences](https://docs.microsoft.com/graph/api/shiftpreferences-get?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|de023814-96df-4f53-9376-1e2891ef5a18|
|**Display String**|Read all user shift preferences|
|**Description**|Allows the app to read all users' shift schedule preferences without a signed-in user.|
## Resources
### [shiftPreferences ](https://docs.microsoft.com/graph/api/resources/shiftpreferences?view=graph-rest-1.0&tabs=http)
|Property          |Type           |Description                                                                                                                                      |
|--------------|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| availability | shiftAvailability collection | Availability of the user to be scheduled for work and its recurrence pattern. |
| createdDateTime | `Edm.DateTimeOffset` | Timestamp corresponding to when the entity was created. |
| id | `Edm.String` | The identifier of the entity. |
| lastModifiedBy | identitySet | Identity of the person who last modified the entity. |
| lastModifiedDateTime | `Edm.DateTimeOffset` | Timestamp corresponding to when the entity was last modified. |
| @odata.etag | `Edm.String` | The change key for the entity. |
