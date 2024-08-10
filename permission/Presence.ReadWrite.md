# Presence.ReadWrite

> Allows the app to read the presence information and write activity and availability on behalf of the signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[POST /users/{userId}/presence/clearPresence](https://docs.microsoft.com/graph/api/presence-clearpresence?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/presence/clearUserPreferredPresence](https://docs.microsoft.com/graph/api/presence-clearuserpreferredpresence?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/presence/setPresence](https://docs.microsoft.com/graph/api/presence-setpresence?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/presence/setStatusMessage](https://docs.microsoft.com/graph/api/presence-setstatusmessage?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/presence/setUserPreferredPresence](https://docs.microsoft.com/graph/api/presence-setuserpreferredpresence?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8d3c54a7-cf58-4773-bf81-c0cd6ad522bb|
|**Consent Type**|User|
|**Display String**|Read and write a user's presence information|
|**Description**|Allows the app to read the presence information and write activity and availability on behalf of the signed-in user. Presence information includes activity, availability, status note, calendar out-of-office message, timezone and location.|
## Resources
### [presenceStatusMessage ](https://docs.microsoft.com/graph/api/resources/presencestatusmessage?view=graph-rest-1.0&tabs=http)
| Property       | Type           | Description                                 | 
| -------------- | -------------- | ------------------------------------------- | 
| expiryDateTime | dateTimeTimeZone | Time in which the status message expires.<br/>If not provided, the status message doesn't expire.<br/><br/>**expiryDateTime.dateTime** shouldn't include time zone.<br/><br/>**expiryDateTime** isn't available when you request the presence of another user. |
| message | itemBody | Status message item.<br/><br/> The only supported format currently is `message.contentType = 'text'`. |
| publishedDateTime | DateTimeOffset |Time in which the status message was published.<br/>Read-only.<br/><br/>**p
