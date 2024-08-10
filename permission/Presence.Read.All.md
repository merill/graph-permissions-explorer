# Presence.Read.All

> Allows the app to read presence information of all users in the directory on behalf of the signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /communications/presences](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/presence](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id}/presence](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /communications/getPresencesByUserId](https://docs.microsoft.com/graph/api/cloudcommunications-getpresencesbyuserid?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9c7a330d-35b3-4aa1-963d-cb2b9f927841|
|**Consent Type**|User|
|**Display String**|Read presence information of all users in your organization|
|**Description**|Allows the app to read presence information of all users in the directory on behalf of the signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location.|
## Application Permission
|||
|-|-|
|**Id**|a70e0c2d-e793-494c-94c4-118fa0a67f42|
|**Display String**|Read presence information for all users|
|**Description**|Allows the app to read presence information of all users in the directory without a signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location. |
## Resources
### [presence ](https://docs.microsoft.com/graph/api/resources/presence?view=graph-rest-1.0&tabs=http)
| Property | Type              | Description                                                                                                                                                                                                                                                                                       |
| :----------- | :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| activity     | String collection | The supplemental information to a user's availability. Possible values are `Available`, `Away`, `BeRightBack`, `Busy`, `DoNotDisturb`, `InACall`, `InAConferenceCall`, `Inactive`, `InAMeeting`, `Offline`, `OffWork`, `OutOfOffice`, `PresenceUnknown`, `Presenting`, `UrgentInterruptionsOnly`. |
| availability | String collection | The base presence information for a user. Possible values are `Available`, `AvailableIdle`,  `Away`, `BeRightBack`, `Busy`, `BusyIdle`, `DoNotDisturb`, `Offline`, `PresenceUnknown`                                                                                                              |
| id           | String            | The unique identifier for the user.                                                                                                                                                                                                                                                                                |
| statusMessage | presenceStatusMessage | The presence status message of a user. |
