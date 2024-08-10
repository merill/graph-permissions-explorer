# Analytics.Read

> Allows the app to read the signed-in user's activity statistics, such as how much time the user has spent on emails, in meetings, or in chat sessions.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /me/analytics/activitystatistics](https://docs.microsoft.com/graph/api/activitystatistics-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id|userPrincipalName}/analytics/activitystatistics](https://docs.microsoft.com/graph/api/activitystatistics-list?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|e03cf23f-8056-446a-8994-7d93dfc8b50e|
|**Consent Type**|User|
|**Display String**|Read user activity statistics|
|**Description**|Allows the app to read the signed-in user's activity statistics, such as how much time the user has spent on emails, in meetings, or in chat sessions.|
## Resources
### [activityStatistics ](https://docs.microsoft.com/graph/api/resources/activitystatistics?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|activity |analyticsActivityType |The type of activity for which statistics are returned. The possible values are: `call`, `chat`, `email`, `focus`, and `meeting`. |
|duration |Duration |Total hours spent on the activity. The value is represented in ISO 8601 format for durations. |
|endDate |Date |Date when the activity ended, expressed in ISO 8601 format for calendar dates. For example, the property value could be "2019-07-03" that follows the YYYY-MM-DD format. |
|id |String |Read-only ID for the activity. Do not parse or customize the value for your scenarios. |
|startDate |Date |Date when the activity started, expressed in ISO 8601 format for calendar dates. For example, the property value could be "2019-07-04" that follows the YYYY-MM-DD format. |
|timeZoneUsed |String |The time zone that the user sets in Microsoft Outlook is used for the computation. For example, the property value could be "Pacific Standard Time." |
