# Presence.ReadWrite.All

> Allows the app to read all presence information and write activity and availability of all users in the directory without a signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, time zone and location.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /communications/presences](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/presence](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id}/presence](https://docs.microsoft.com/graph/api/presence-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /communications/getPresencesByUserId](https://docs.microsoft.com/graph/api/cloudcommunications-getpresencesbyuserid?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /users/{userId}/presence/clearPresence](https://docs.microsoft.com/graph/api/presence-clearpresence?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /users/{userId}/presence/clearUserPreferredPresence](https://docs.microsoft.com/graph/api/presence-clearuserpreferredpresence?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /users/{userId}/presence/setPresence](https://docs.microsoft.com/graph/api/presence-setpresence?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /users/{userId}/presence/setStatusMessage](https://docs.microsoft.com/graph/api/presence-setstatusmessage?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /users/{userId}/presence/setUserPreferredPresence](https://docs.microsoft.com/graph/api/presence-setuserpreferredpresence?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|83cded22-8297-4ff6-a7fa-e97e9545a259|
|**Display String**|Read and write presence information for all users|
|**Description**|Allows the app to read all presence information and write activity and availability of all users in the directory without a signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, time zone and location.|
## Resources
### [presence ](https://docs.microsoft.com/graph/api/resources/presence?view=graph-rest-1.0&tabs=http)
| Property | Type              | Description                                                                                                                                                                                                                                                                                       |
| :----------- | :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| activity     | String collection | The supplemental information to a user's availability. Possible values are `Available`, `Away`, `BeRightBack`, `Busy`, `DoNotDisturb`, `InACall`, `InAConferenceCall`, `Inactive`, `InAMeeting`, `Offline`, `OffWork`, `OutOfOffice`, `PresenceUnknown`, `Presenting`, `UrgentInterruptionsOnly`. |
| availability | String collection | The base presence information for a user. Possible values are `Available`, `AvailableIdle`,  `Away`, `BeRightBack`, `Busy`, `BusyIdle`, `DoNotDisturb`, `Offline`, `PresenceUnknown`                                                                                                              |
| id           | String            | The unique identifier for the user.                                                                                                                                                                                                                                                                                |
| statusMessage | presenceStatusMessage | The presence status message of a user. |
### [presenceStatusMessage ](https://docs.microsoft.com/graph/api/resources/presencestatusmessage?view=graph-rest-1.0&tabs=http)
| Property       | Type           | Description                                 | 
| -------------- | -------------- | ------------------------------------------- | 
| expiryDateTime | dateTimeTimeZone | Time in which the status message expires.<br/>If not provided, the status message doesn't expire.<br/><br/>**expiryDateTime.dateTime** shouldn't include time zone.<br/><br/>**expiryDateTime** isn't available when you request the presence of another user. |
| message | itemBody | Status message item.<br/><br/> The only supported format currently is `message.contentType = 'text'`. |
| publishedDateTime | DateTimeOffset |Time in which the status message was published.<br/>Read-only.<br/><br/>**p
