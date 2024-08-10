# Presence.Read

> Allows the app to read presence information on behalf of the signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /communications/presences](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/presence](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/presence](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|76bc735e-aecd-4a1d-8b4c-2b915deabb79|
|**Consent Type**|User|
|**Display String**|Read user's presence information|
|**Description**|Allows the app to read presence information on behalf of the signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location.|
## Resources
### [presence ](https://docs.microsoft.com/graph/api/resources/presence?view=graph-rest-1.0&tabs=http)
| Property | Type              | Description                                                                                                                                                                                                                                                                                       |
| :----------- | :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| activity     | String collection | The supplemental information to a user's availability. Possible values are `Available`, `Away`, `BeRightBack`, `Busy`, `DoNotDisturb`, `InACall`, `InAConferenceCall`, `Inactive`, `InAMeeting`, `Offline`, `OffWork`, `OutOfOffice`, `PresenceUnknown`, `Presenting`, `UrgentInterruptionsOnly`. |
| availability | String collection | The base presence information for a user. Possible values are `Available`, `AvailableIdle`,  `Away`, `BeRightBack`, `Busy`, `BusyIdle`, `DoNotDisturb`, `Offline`, `PresenceUnknown`                                                                                                              |
| id           | String            | The unique identifier for the user.                                                                                                                                                                                                                                                                                |
| statusMessage | presenceStatusMessage | The presence status message of a user. |
