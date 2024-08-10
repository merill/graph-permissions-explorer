# UserActivity.ReadWrite.CreatedByApp

> Allows the app to read and report the signed-in user's activity in the app.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /me/activities/{id}](https://docs.microsoft.com/graph/api/projectrome-delete-activity?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/activities/{id}/historyItems/{id}](https://docs.microsoft.com/graph/api/projectrome-delete-historyitem?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/activities](https://docs.microsoft.com/graph/api/projectrome-get-activities?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/activities/recent](https://docs.microsoft.com/graph/api/projectrome-get-recent-activities?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /me/activities/{appActivityId}](https://docs.microsoft.com/graph/api/projectrome-put-activity?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /me/activities/{id}/historyItems/{id}](https://docs.microsoft.com/graph/api/projectrome-put-historyitem?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|47607519-5fb1-47d9-99c7-da4b48f369b1|
|**Consent Type**|User|
|**Display String**|Read and write app activity to users' activity feed|
|**Description**|Allows the app to read and report the signed-in user's activity in the app.|
## Resources
### [userActivity ](https://docs.microsoft.com/graph/api/resources/projectrome-activity?view=graph-rest-1.0&tabs=http)

### [activityHistoryItem ](https://docs.microsoft.com/graph/api/resources/projectrome-historyitem?view=graph-rest-1.0&tabs=http)

