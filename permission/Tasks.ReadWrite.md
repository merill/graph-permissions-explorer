# Tasks.ReadWrite

> Allows the app to create, read, update, and delete the signed-in user's tasks and task lists, including any shared with the user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[](https://docs.microsoft.com/graph/api/basetask-move?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/outlook/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/outlook/taskGroups/{id}](https://docs.microsoft.com/graph/api/outlooktaskgroup-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/outlook/taskGroups/{id}/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/outlook/tasks/{id}](https://docs.microsoft.com/graph/api/outlooktask-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/tasks/alltasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/tasks/lists/{baseTaskListId}](https://docs.microsoft.com/graph/api/tasklist-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources/{linkedResourceId}](https://docs.microsoft.com/graph/api/linkedresource_v2-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /me/todo/lists/{id}/tasks/{id}/attachments/{id}](https://docs.microsoft.com/graph/api/taskfileattachment-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /planner/buckets/{id}](https://docs.microsoft.com/graph/api/plannerbucket-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /planner/plans/{id}](https://docs.microsoft.com/graph/api/plannerplan-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /planner/rosters/{plannerRosterId}](https://docs.microsoft.com/graph/api/plannerroster-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /planner/rosters/{plannerRosterId}/members/{plannerRosterMemberId}](https://docs.microsoft.com/graph/api/plannerrostermember-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /planner/tasks/{id}](https://docs.microsoft.com/graph/api/plannertask-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources/{linkedResourceId}](https://docs.microsoft.com/graph/api/linkedresource_v2-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{id}/todo/lists/{id}/tasks/{id}/attachments/{id}](https://docs.microsoft.com/graph/api/taskfileattachment-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /users/{id|userPrincipalName}/outlook/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id|userPrincipalName}/outlook/taskGroups/{id}](https://docs.microsoft.com/graph/api/outlooktaskgroup-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id|userPrincipalName}/outlook/taskGroups/{id}/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id|userPrincipalName}/outlook/tasks/{id}](https://docs.microsoft.com/graph/api/outlooktask-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /users/{userId|userPrincipalName}/tasks/alltasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}](https://docs.microsoft.com/graph/api/tasklist-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /drive/root/createdByUser/planner/plans](https://docs.microsoft.com/graph/api/planneruser-list-plans?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drive/root/createdByUser/planner/tasks](https://docs.microsoft.com/graph/api/planneruser-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/planner/plans](https://docs.microsoft.com/graph/api/plannergroup-list-plans?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/planner](https://docs.microsoft.com/graph/api/planneruser-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/planner/all/delta](https://docs.microsoft.com/graph/api/planneruser-list-delta?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/planner/favoritePlans](https://docs.microsoft.com/graph/api/planneruser-list-favoriteplans?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/planner/myDayTasks](https://docs.microsoft.com/graph/api/planneruser-list-mydaytasks?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/planner/plans](https://docs.microsoft.com/graph/api/planneruser-list-plans?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/planner/recentPlans](https://docs.microsoft.com/graph/api/planneruser-list-recentplans?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/planner/tasks](https://docs.microsoft.com/graph/api/planneruser-list-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/tasks/alltasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/tasks/lists](https://docs.microsoft.com/graph/api/tasks-list-lists?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/tasks/lists/{baseTaskListId}/tasks](https://docs.microsoft.com/graph/api/basetasklist-list-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/checklistItems](https://docs.microsoft.com/graph/api/basetask-list-checklistitems?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources](https://docs.microsoft.com/graph/api/basetask-list-linkedresources?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources/{linkedResourceId}](https://docs.microsoft.com/graph/api/linkedresource_v2-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/tasks/lists/{baseTaskListId}/tasks/delta](https://docs.microsoft.com/graph/api/basetask-delta?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/tasks/lists/delta](https://docs.microsoft.com/graph/api/basetasklist-delta?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/todo/lists](https://docs.microsoft.com/graph/api/todo-list-lists?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{id}/tasks/{id}/attachments/{id}](https://docs.microsoft.com/graph/api/taskfileattachment-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{id}/tasks/delta](https://docs.microsoft.com/graph/api/todotask-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources](https://docs.microsoft.com/graph/api/todotask-list-linkedresources?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/attachments](https://docs.microsoft.com/graph/api/todotask-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems](https://docs.microsoft.com/graph/api/todotask-list-checklistitems?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/todo/lists/delta](https://docs.microsoft.com/graph/api/todotasklist-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/buckets](https://docs.microsoft.com/graph/api/planner-list-buckets?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/buckets/{id}](https://docs.microsoft.com/graph/api/plannerbucket-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/buckets/{id}/tasks](https://docs.microsoft.com/graph/api/plannerbucket-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/plans](https://docs.microsoft.com/graph/api/planner-list-plans?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/plans/{id}/details](https://docs.microsoft.com/graph/api/plannerplandetails-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/plans/{plan-id}](https://docs.microsoft.com/graph/api/plannerplan-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/plans/{plan-id}/buckets](https://docs.microsoft.com/graph/api/plannerplan-list-buckets?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/plans/{plan-id}/tasks](https://docs.microsoft.com/graph/api/plannerplan-list-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /planner/rosters/{plannerRosterId}](https://docs.microsoft.com/graph/api/plannerroster-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /planner/rosters/{plannerRosterId}/members](https://docs.microsoft.com/graph/api/plannerroster-list-members?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /planner/rosters/{plannerRosterId}/members/{plannerRosterMemberId}](https://docs.microsoft.com/graph/api/plannerrostermember-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /planner/rosters/{plannerRosterId}/plans](https://docs.microsoft.com/graph/api/plannerroster-list-plans?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /planner/tasks](https://docs.microsoft.com/graph/api/planner-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/tasks/{id}](https://docs.microsoft.com/graph/api/plannertask-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/tasks/{id}/assignedToTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerassignedtotaskboardtaskformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/tasks/{id}/bucketTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerbuckettaskboardtaskformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/tasks/{id}/details](https://docs.microsoft.com/graph/api/plannertaskdetails-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /planner/tasks/{id}/progressTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerprogresstaskboardtaskformat-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/checklistItems](https://docs.microsoft.com/graph/api/basetask-list-checklistitems?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources](https://docs.microsoft.com/graph/api/basetask-list-linkedresources?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources/{linkedResourceId}](https://docs.microsoft.com/graph/api/linkedresource_v2-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems](https://docs.microsoft.com/graph/api/todotask-list-checklistitems?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{id}/planner](https://docs.microsoft.com/graph/api/planneruser-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id}/planner/all/delta](https://docs.microsoft.com/graph/api/planneruser-list-delta?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id}/planner/favoritePlans](https://docs.microsoft.com/graph/api/planneruser-list-favoriteplans?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id}/planner/myDayTasks](https://docs.microsoft.com/graph/api/planneruser-list-mydaytasks?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{id}/planner/plans](https://docs.microsoft.com/graph/api/planneruser-list-plans?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{id}/planner/recentPlans](https://docs.microsoft.com/graph/api/planneruser-list-recentplans?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{id}/planner/tasks](https://docs.microsoft.com/graph/api/planneruser-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/todo/lists/{id}/tasks/{id}/attachments](https://docs.microsoft.com/graph/api/todotask-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/todo/lists/{id}/tasks/{id}/attachments/{id}](https://docs.microsoft.com/graph/api/taskfileattachment-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists](https://docs.microsoft.com/graph/api/todo-list-lists?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources](https://docs.microsoft.com/graph/api/todotask-list-linkedresources?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/delta](https://docs.microsoft.com/graph/api/todotask-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id|userPrincipalName}/todo/lists/delta](https://docs.microsoft.com/graph/api/todotasklist-delta?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId|userPrincipalName}/tasks/alltasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId|userPrincipalName}/tasks/lists](https://docs.microsoft.com/graph/api/tasks-list-lists?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks](https://docs.microsoft.com/graph/api/basetasklist-list-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/delta](https://docs.microsoft.com/graph/api/basetask-delta?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId|userPrincipalName}/tasks/lists/delta](https://docs.microsoft.com/graph/api/basetasklist-delta?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{usersId}/planner/rosterPlans](https://docs.microsoft.com/graph/api/planneruser-list-rosterplans?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/outlook/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/outlook/taskGroups/{id}](https://docs.microsoft.com/graph/api/outlooktaskgroup-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/outlook/taskGroups/{id}/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/outlook/tasks/{id}](https://docs.microsoft.com/graph/api/outlooktask-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/planner](https://docs.microsoft.com/graph/api/planneruser-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/tasks/alltasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/tasks/lists/{baseTaskListId}](https://docs.microsoft.com/graph/api/tasklist-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources/{linkedResourceId}](https://docs.microsoft.com/graph/api/linkedresource_v2-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/buckets/{id}](https://docs.microsoft.com/graph/api/plannerbucket-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/plans/{id}/details](https://docs.microsoft.com/graph/api/plannerplandetails-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/plans/{plan-id}](https://docs.microsoft.com/graph/api/plannerplan-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/tasks/{id}](https://docs.microsoft.com/graph/api/plannertask-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/tasks/{id}/assignedToTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerassignedtotaskboardtaskformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/tasks/{id}/bucketTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerbuckettaskboardtaskformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/tasks/{id}/details](https://docs.microsoft.com/graph/api/plannertaskdetails-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /planner/tasks/{id}/progressTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerprogresstaskboardtaskformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources/{linkedResourceId}](https://docs.microsoft.com/graph/api/linkedresource_v2-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /users/{id|userPrincipalName}/outlook/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id|userPrincipalName}/outlook/taskGroups/{id}](https://docs.microsoft.com/graph/api/outlooktaskgroup-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id|userPrincipalName}/outlook/taskGroups/{id}/taskFolders/{id}](https://docs.microsoft.com/graph/api/outlooktaskfolder-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id|userPrincipalName}/outlook/tasks/{id}](https://docs.microsoft.com/graph/api/outlooktask-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /users/{userId|userPrincipalName}/tasks/alltasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}](https://docs.microsoft.com/graph/api/tasklist-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}](https://docs.microsoft.com/graph/api/basetask-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/taskFolders](https://docs.microsoft.com/graph/api/outlookuser-post-taskfolders?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/taskFolders/{id}/tasks](https://docs.microsoft.com/graph/api/outlooktaskfolder-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/taskGroups](https://docs.microsoft.com/graph/api/outlookuser-post-taskgroups?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/taskGroups/{id}/taskFolders](https://docs.microsoft.com/graph/api/outlooktaskgroup-post-taskfolders?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/taskGroups/{id}/taskFolders/{id}/tasks](https://docs.microsoft.com/graph/api/outlooktaskfolder-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/tasks](https://docs.microsoft.com/graph/api/outlookuser-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/tasks/{id}/attachments](https://docs.microsoft.com/graph/api/outlooktask-post-attachments?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/outlook/tasks/{id}/complete](https://docs.microsoft.com/graph/api/outlooktask-complete?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/tasks/alltasks/{baseTaskId}/move](https://docs.microsoft.com/graph/api/basetask-move?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/tasks/lists](https://docs.microsoft.com/graph/api/tasks-post-lists?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/tasks/lists/{baseTaskListId}/tasks](https://docs.microsoft.com/graph/api/basetasklist-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/checklistItems](https://docs.microsoft.com/graph/api/basetask-post-checklistitems?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources](https://docs.microsoft.com/graph/api/basetask-post-linkedresources?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/move](https://docs.microsoft.com/graph/api/basetask-move?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/todo/lists](https://docs.microsoft.com/graph/api/todo-post-lists?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/todo/lists/{id}/tasks/{id}/attachments](https://docs.microsoft.com/graph/api/todotask-post-attachments?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/todo/lists/{id}/tasks/{id}/attachments/createUploadSession](https://docs.microsoft.com/graph/api/taskfileattachment-createuploadsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-post-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources](https://docs.microsoft.com/graph/api/todotask-post-linkedresources?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems](https://docs.microsoft.com/graph/api/todotask-post-checklistitems?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /planner/buckets](https://docs.microsoft.com/graph/api/planner-post-buckets?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /planner/plans](https://docs.microsoft.com/graph/api/planner-post-plans?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /planner/plans/{planId}/archive](https://docs.microsoft.com/graph/api/plannerplan-archive?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /planner/plans/{planId}/moveToContainer](https://docs.microsoft.com/graph/api/plannerplan-movetocontainer?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /planner/plans/{planId}/unarchive](https://docs.microsoft.com/graph/api/plannerplan-unarchive?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /planner/rosters](https://docs.microsoft.com/graph/api/planner-post-rosters?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /planner/rosters/{plannerRosterId}/members](https://docs.microsoft.com/graph/api/plannerroster-post-members?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /planner/rosters/{rosterId}/assignSensitivityLabel](https://docs.microsoft.com/graph/api/plannerroster-assignsensitivitylabel?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /planner/tasks](https://docs.microsoft.com/graph/api/planner-post-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/checklistItems](https://docs.microsoft.com/graph/api/basetask-post-checklistitems?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{id | userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/linkedResources](https://docs.microsoft.com/graph/api/basetask-post-linkedresources?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems](https://docs.microsoft.com/graph/api/todotask-post-checklistitems?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id}/todo/lists/{id}/tasks/{id}/attachments](https://docs.microsoft.com/graph/api/todotask-post-attachments?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id}/todo/lists/{id}/tasks/{id}/attachments/createUploadSession](https://docs.microsoft.com/graph/api/taskfileattachment-createuploadsession?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/taskFolders](https://docs.microsoft.com/graph/api/outlookuser-post-taskfolders?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/taskFolders/{id}/tasks](https://docs.microsoft.com/graph/api/outlooktaskfolder-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/taskGroups](https://docs.microsoft.com/graph/api/outlookuser-post-taskgroups?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/taskGroups/{id}/taskFolders](https://docs.microsoft.com/graph/api/outlooktaskgroup-post-taskfolders?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/taskGroups/{id}/taskFolders/{id}/tasks](https://docs.microsoft.com/graph/api/outlooktaskfolder-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/tasks](https://docs.microsoft.com/graph/api/outlookuser-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/tasks/{id}/attachments](https://docs.microsoft.com/graph/api/outlooktask-post-attachments?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id|userPrincipalName}/outlook/tasks/{id}/complete](https://docs.microsoft.com/graph/api/outlooktask-complete?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/todo/lists](https://docs.microsoft.com/graph/api/todo-post-lists?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-post-tasks?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources](https://docs.microsoft.com/graph/api/todotask-post-linkedresources?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{userId|userPrincipalName}/tasks/alltasks/{baseTaskId}/move](https://docs.microsoft.com/graph/api/basetask-move?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{userId|userPrincipalName}/tasks/lists](https://docs.microsoft.com/graph/api/tasks-post-lists?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks](https://docs.microsoft.com/graph/api/basetasklist-post-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{userId|userPrincipalName}/tasks/lists/{baseTaskListId}/tasks/{baseTaskId}/move](https://docs.microsoft.com/graph/api/basetask-move?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|2219042f-cab5-40cc-b0d2-16b1540b4c5f|
|**Consent Type**|User|
|**Display String**|Create, read, update, and delete user’s tasks and task lists|
|**Description**|Allows the app to create, read, update, and delete the signed-in user's tasks and task lists, including any shared with the user.|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [attachment ](https://docs.microsoft.com/graph/api/resources/attachment?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contentType|String|The MIME type.|
|id|String| Read-only.|
|isInline|Boolean|`true` if the attachment is an inline attachment; otherwise, `false`.|
|lastModifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|name|String|The attachment's file name.|
|size|Int32|The length of the attachment in bytes.|
### [attachmentInfo ](https://docs.microsoft.com/graph/api/resources/attachmentinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attachmentType|attachmentType|The type of the attachment. The possible values are: `file`, `item`, `reference`. Required.|
|contentType|String|The nature of the data in the attachment. Optional.|
|name|String|The display name of the attachment. This can be a descriptive string and doesn't have to be the actual file name. Required.|
|size|Int64|The length of the attachment in bytes. Required.|
### [basetask](https://docs.microsoft.com/graph/api/resources/basetask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|textBody|String|The task body in text format that typically contains information about the task. |
|bodyLastModifiedDateTime|DateTimeOffset|The date and time when the task was last modified. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2020 would look like this: '2020-01-01T00:00:00Z'. |
|completedDateTime|DateTimeOffset|The date when the task was finished. |
|createdDateTime|DateTimeOffset|The date and time when the task was created. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format. For example, midnight UTC on Jan 1, 2020 would look like this: '2020-01-01T00:00:00Z'. |
|displayName|String|The name of the task. |
|dueDateTime|dateTimeTimeZone|The date in the specified time zone that the task is to be finished. |
|id|String|Unique identifier for the task. By default, this value will not change if a task is moved from one list to another. |
|importance|importance|The importance of the task. Possible values are: `low`, `normal`, `high`.  The possible values are: `low`, `normal`, `high`.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the task was last modified. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2020 would look like this: '2020-01-01T00:00:00Z'. |
|viewpoint|taskViewpoint|Properties that are personal to a user such as **reminderDateTime** and **categories**. |
|recurrence|patternedRecurrence|The recurrence pattern for the task. |
|startDateTime|dateTimeTimeZone|The date in the specified time zone when the task is to begin. |
|status|taskStatus_v2|Indicates the state or progress of the task. Possible values are: `notStarted`, `inProgress`, `completed`,`unknownFutureValue`. |
### [basetasklist](https://docs.microsoft.com/graph/api/resources/basetasklist?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the task list.|
|id|String|The identifier of the task list, unique in the user's mailbox. Read-only.|
### [checklistItem ](https://docs.microsoft.com/graph/api/resources/checklistitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|checkedDateTime|DateTimeOffset|The date and time when the **checklistItem** was finished.|
|createdDateTime|DateTimeOffset|The date and time when the **checklistItem** was created.|
|displayName|String|Indicates the title of the **checklistItem**.|
|id|String|Server generated ID for the the **checkListItem**|
|isChecked|Boolean|State that indicates whether the item is checked off or not.|
### [dateTimeTimeZone ](https://docs.microsoft.com/graph/api/resources/datetimetimezone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|dateTime|String|A single point of time in a combined date and time representation (`{date}T{time}`; for example, `2017-08-29T04:00:00.0000000`).|
|timeZone|String|Represents a time zone, for example, "Pacific Standard Time". See below for more possible values.|
### [entity ](https://docs.microsoft.com/graph/api/resources/entity?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| The unique identifier for an entity. Read-only.|
### [fileAttachment ](https://docs.microsoft.com/graph/api/resources/fileattachment?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contentBytes|Edm.Binary|The base64-encoded contents of the file.|
|contentId|String|The ID of the attachment in the Exchange store.|
|contentLocation|String|Don't use this property as it isn't supported.|
|contentType|String|The content type of the attachment.|
|id|String|The attachment ID.|
|isInline|Boolean|Set to `true` if the attachment is an inline attachment.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the attachment was last modified.|
|name|String|The name representing the text that is displayed below the icon representing the embedded attachment and doesn't need to be the actual file name.|
|size|Int32|The size in bytes of the attachment.|
### [group ](https://docs.microsoft.com/graph/api/resources/group?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-|:-|:-|
| allowExternalSenders | Boolean | Indicates if people external to the organization can send messages to the group. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| assignedLabels | assignedLabel collection | The list of sensitivity label pairs (label ID, label name) associated with a Microsoft 365 group. <br><br>Returned only on `$select`. |
| assignedLicenses | assignedLicense collection | The licenses that are assigned to the group. <br><br>Returned only on `$select`. Supports `$filter` (`eq`).Read-only. |
| autoSubscribeNewMembers | Boolean | Indicates if new members added to the group are autosubscribed to receive email notifications. You can set this property in a PATCH request for the group; don't set it in the initial POST request that creates the group. Default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| classification | String | Describes a classification for the group (such as low, medium, or high business impact). Valid values for this property are defined by creating a ClassificationList setting value, based on the template definition.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| createdDateTime | DateTimeOffset | Timestamp of when the group was created. The value can't be modified and is automatically populated when the group is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. |
| deletedDateTime | DateTimeOffset | For some Microsoft Entra objects (user, group, application), if the object is deleted, it's first logically deleted, and this property is updated with the date and time when the object was deleted. Otherwise this property is `null`. If the object is restored, this property is updated to `null`. Inherited from directoryObject.  |
| description | String | An optional description for the group. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| displayName | String | The display name for the group. This property is required when a group is created and can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| expirationDateTime | DateTimeOffset | Timestamp of when the group is set to expire. It's `null` for security groups, but for Microsoft 365 groups, it represents when the group is set to expire as defined in the groupLifecyclePolicy. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| groupTypes | String collection | Specifies the group type and its membership. <br><br>If the collection contains `Unified`, the group is a Microsoft 365 group; otherwise, it's either a security group or a distribution group. For details, see groups overview.<br><br>If the collection includes `DynamicMembership`, the group has dynamic membership; otherwise, membership is static. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| hasMembersWithLicenseErrors | Boolean | Indicates whether there are members in this group that have license errors from its group-based license assignment. <br><br>This property is never returned on a GET operation. You can use it as a $filter argument to get groups that have members with license errors (that is, filter for this property being true). See an example. <br><br>Supports `$filter` (`eq`). |
| hideFromAddressLists | Boolean | True if the group isn't displayed in certain parts of the Outlook UI: the **Address Book**, address lists for selecting message recipients, and the **Browse Groups** dialog for searching groups; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| hideFromOutlookClients | Boolean | True if the group isn't displayed in Outlook clients, such as Outlook for Windows and Outlook on the web; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| id | String | The unique identifier for the group. <br><br>Returned by default. Inherited from directoryObject. Key. Not nullable. Read-only.<br><br>Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| isArchived | Boolean | When a group is associated with a team, this property determines whether the team is in read-only mode.<br/>To read this property, use the `/group/{groupId}/team` endpoint or the Get team API. To update this property, use the archiveTeam and unarchiveTeam APIs. |
| isAssignableToRole | Boolean | Indicates whether this group can be assigned to a Microsoft Entra role. Optional. <br><br>This property can only be set while creating the group and is immutable. If set to `true`, the **securityEnabled** property must also be set to `true`, **visibility** must be `Hidden`, and the group can't be a dynamic group (that is, **groupTypes** can't contain `DynamicMembership`). <br/><br/>Only callers with at least the Privileged Role Administrator role can set this property. The caller must also be assigned the _RoleManagement.ReadWrite.Directory_ permission to set this property or update the membership of such groups. For more, see Using a group to manage Microsoft Entra role assignments<br><br>Using this feature requires a Microsoft Entra ID P1 license. Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| isSubscribedByMail | Boolean | Indicates whether the signed-in user is subscribed to receive email conversations. The default value is `true`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| licenseProcessingState | String | Indicates the status of the group license assignment to all group members. The default value is `false`. Read-only. Possible values: `QueuedForProcessing`, `ProcessingInProgress`, and `ProcessingComplete`.<br><br>Returned only on `$select`. Read-only. |
| mail | String | The SMTP address for the group, for example, "serviceadmins@contoso.com". <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| mailEnabled | Boolean | Specifies whether the group is mail-enabled. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| mailNickname | String | The mail alias for the group, unique for Microsoft 365 groups in the organization. Maximum length is 64 characters. This property can contain only characters in the ASCII character set 0 - 127 except the following characters: ` @ () \ [] " ; : <> , SPACE`. <br><br>Required. Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| membershipRule | String | The rule that determines members for this group if the group is a dynamic group (groupTypes contains `DynamicMembership`). For more information about the syntax of the membership rule, see Membership Rules syntax. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| membershipRuleProcessingState | String | Indicates whether the dynamic membership processing is on or paused. Possible values are `On` or `Paused`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| onPremisesDomainName | String | Contains the on-premises **domain FQDN**, also called **dnsDomainName** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesLastSyncDateTime | DateTimeOffset | Indicates the last time at which the group was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
| onPremisesNetBiosName | String | Contains the on-premises **netBios name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | Errors when using Microsoft synchronization product during provisioning. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| onPremisesSamAccountName | String | Contains the on-premises **SAM account name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`). Read-only. |
| onPremisesSecurityIdentifier | String | Contains the on-premises security identifier (SID) for the group synchronized from on-premises to the cloud. Read-only. <br><br>Returned by default. Supports `$filter` (`eq` including on `null` values). |
| onPremisesSyncEnabled | Boolean | `true` if this group is synced from an on-premises directory; `false` if this group was originally synced from an on-premises directory but is no longer synced; **null** if this object has never synced from an on-premises directory (default). <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). |
| preferredDataLocation | String | The preferred data location for the Microsoft 365 group. By default, the group inherits the group creator's preferred data location. To set this property, the calling app must be granted the *Directory.ReadWrite.All* permission and the user be assigned at least one of the following Microsoft Entra roles: <br><ul>User Account Administrator <li>Directory Writer <li> Exchange Administrator <li> SharePoint Administrator </ul><br/> For more information about this property, see OneDrive Online Multi-Geo. <br><br>Nullable. Returned by default. |
| preferredLanguage | String | The preferred language for a Microsoft 365 group. Should follow ISO 639-1 Code; for example, `en-US`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| proxyAddresses | String collection | Email addresses for the group that direct to the same group mailbox. For example: `["SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. The **any** operator is required to filter expressions on multi-valued properties. <br><br>Returned by default. Read-only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`). |
| renewedDateTime | DateTimeOffset | Timestamp of when the group was last renewed. This value can't be modified directly and is only updated via the renew service action. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| securityEnabled | Boolean | Specifies whether the group is a security group. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| securityIdentifier | String | Security identifier of the group, used in Windows scenarios. Read-only. <br><br>Returned by default. |
| serviceProvisioningErrors | serviceProvisioningError collection | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a group object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance). |
| theme | string | Specifies a Microsoft 365 group's color theme. Possible values are `Teal`, `Purple`, `Green`, `Blue`, `Pink`, `Orange`, or `Red`. <br><br>Returned by default. |
| uniqueName | String | The unique identifier that can be assigned to a group and used as an alternate key. Immutable. Read-only. |
| unseenCount | Int32 | Count of conversations that received new posts since the signed-in user last visited the group. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| visibility | String | Specifies the group join policy and group content visibility for groups. Possible values are: `Private`, `Public`, or `HiddenMembership`. `HiddenMembership` can be set only for Microsoft 365 groups when the groups are created. It can't be updated later. Other values of visibility can be updated after group creation.<br> If visibility value isn't specified during group creation on Microsoft Graph, a security group is created as `Private` by default, and the Microsoft 365 group is `Public`. Groups assignable to roles are always `Private`. To learn more, see group visibility options. <br><br>Returned by default. Nullable. |
### [itemAttachment ](https://docs.microsoft.com/graph/api/resources/itemattachment?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contentType|String|The content type of the attachment. Returned as `null` by default, when not set explicitly. Optional.|
|id|String| The attachment ID.|
|isInline|Boolean|Set to true if the attachment is inline, such as an embedded image within the body of the item.|
|lastModifiedDateTime|DateTimeOffset|The last time and date that the attachment was modified.|
|name|String|The display name of the attachment.|
|size|Int32|The size in bytes of the attachment.|
### [itemBody ](https://docs.microsoft.com/graph/api/resources/itembody?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|content|String|The content of the item.|
|contentType|bodyType|The type of the content. Possible values are `text` and `html`.|
### [linkedResource ](https://docs.microsoft.com/graph/api/resources/linkedresource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicationName|String|The app name of the source that sends the **linkedResource**.|
|displayName|String|The title of the **linkedResource**.|
|externalId|String|ID of the object that is associated with this task on the third-party/partner system.|
|id|String|Server generated ID for the **linkedResource**. Inherited from entity.|
|webUrl|String|Deep link to the **l
### [linkedresource_v2](https://docs.microsoft.com/graph/api/resources/linkedresource_v2?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicationName|String|Field indicating the app name of the source that is sending the **linkedResource**.|
|displayName|String|Field indicating the title of the **linkedResource**.|
|externalId|String|Id of the object that is associated with this task on the third-party/partner system.|
|id|String|Server generated ID for the **linkedResource**. Inherited from entity.|
|webUrl|String|Deep link to the **l
### [outlookCategory ](https://docs.microsoft.com/graph/api/resources/outlookcategory?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|color|categoryColor|A pre-set color constant that characterizes a category, and that is mapped to one of 25 predefined colors. For more details, see the following note. |
|displayName|String|A unique name that identifies a category in the user's mailbox. After a category is created, the name cannot be changed. Read-only.|
### [outlooktask](https://docs.microsoft.com/graph/api/resources/outlooktask?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|assignedTo|String|The name of the person who has been assigned the task in Outlook. Read-only.|
|body|itemBody|The task body that typically contains information about the task. Note that only HTML type is supported.|
|categories|String collection|The categories associated with the task. Each category corresponds to the **displayName** property of an outlookCategory that the user has defined.|
|changeKey|String|The version of the task.|
|completedDateTime|dateTimeTimeZone|The date in the specified time zone that the task was finished.|
|createdDateTime|DateTimeOffset|The date and time when the task was created. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|dueDateTime|dateTimeTimeZone|The date in the specified time zone that the task is to be finished.|
|hasAttachments|Boolean|Set to true if the task has attachments.|
|id|String| Unique identifier for the task. !INCLUDE [outlook-beta-id] Read-only. |
|importance|importance|The importance of the event. Possible values are: `low`, `normal`, `high`.|
|isReminderOn|Boolean|Set to true if an alert is set to remind the user of the task.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the task was last modified. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|owner|String|The name of the person who created the task.|
|parentFolderId|String|The unique identifier for the task's parent folder.|
|recurrence|patternedRecurrence|The recurrence pattern for the task.|
|reminderDateTime|dateTimeTimeZone|The date and time for a reminder alert of the task to occur.|
|sensitivity|sensitivity|Indicates the level of privacy for the task. Possible values are: `normal`, `personal`, `private`, `confidential`.|
|startDateTime|dateTimeTimeZone|The date in the specified time zone when the task is to begin.|
|status|taskStatus|Indicates the state or progress of the task. Possible values are: `notStarted`, `inProgress`, `completed`, `waitingOnOthers`, `deferred`.|
|subject|String|A brief description or title of the task.|
### [outlooktaskfolder](https://docs.microsoft.com/graph/api/resources/outlooktaskfolder?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|changeKey|String|The version of the task folder.|
|id|String|The identifier of the task folder, unique in the user's mailbox. Read-only.|
|isDefaultFolder|Boolean|True if the folder is the default task folder.|
|name|String|The name of the task folder.|
|parentGroupKey|Guid|The unique GUID identifier for the task folder's parent group.|
### [outlooktaskgroup](https://docs.microsoft.com/graph/api/resources/outlooktaskgroup?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|changeKey|String|The version of the task group.|
|groupKey|Edm.Guid|The unique GUID identifier for the task group.|
|id|String|The unique string identifier of the task group. Read-only.|
|isDefaultGroup|Boolean|True if the task group is the default task group.|
|name|String|The name of the task group.|
### [patternedRecurrence ](https://docs.microsoft.com/graph/api/resources/patternedrecurrence?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|pattern|recurrencePattern|The frequency of an event. <br/><br/> For access reviews: <li>Do not specify this property for a one-time access review. <li> Only **interval**, **dayOfMonth**, and **type** (`weekly`, `absoluteMonthly`) properties of recurrencePattern are supported.|
|range|recurrenceRange|The duration of an event.|
### [planner-identifiers-disclaimer](https://docs.microsoft.com/graph/api/resources/planner-identifiers-disclaimer?view=graph-rest-1.0&tabs=http)

### [planner-order-hint-format](https://docs.microsoft.com/graph/api/resources/planner-order-hint-format?view=graph-rest-1.0&tabs=http)

### [planner-overview](https://docs.microsoft.com/graph/api/resources/planner-overview?view=graph-rest-1.0&tabs=http)

### [plannerAppliedCategories ](https://docs.microsoft.com/graph/api/resources/plannerappliedcategories?view=graph-rest-1.0&tabs=http)

### [plannerAssignedToTaskBoardTaskFormat ](https://docs.microsoft.com/graph/api/resources/plannerassignedtotaskboardtaskformat?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| ID of the resource. It's 28 characters long and case-sensitive. Format validation is done on the service. Read-only.|
|orderHintsByAssignee|plannerOrderHintsByAssignee|Dictionary of hints used to order tasks on the AssignedTo view of the Task Board. The key of each entry is one of the users the task is assigned to and the value is the order hint. The format of each value is defined as outlined here.|
|unassignedOrderHint|String|Hint value used to order the task on the AssignedTo view of the Task Board when the task isn't assigned to anyone, or if the orderHintsByAssignee dictionary doesn't provide an order hint for the user the task is assigned to. The format is defined as outlined here.|
### [plannerAssignments ](https://docs.microsoft.com/graph/api/resources/plannerassignments?view=graph-rest-1.0&tabs=http)

### [plannerBucket ](https://docs.microsoft.com/graph/api/resources/plannerbucket?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| Read-only. ID of the bucket. It is 28 characters long and case-sensitive. Format validation is done on the service.|
|name|String|Name of the bucket.|
|orderHint|String|Hint used to order items of this type in a list view. For details about the supported format, see Using order hints in Planner.|
|planId|String|Plan ID to which the bucket belongs.|
### [plannerBucketTaskBoardTaskFormat ](https://docs.microsoft.com/graph/api/resources/plannerbuckettaskboardtaskformat?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| Read-only. ID of the resource. It's 28 characters long and case-sensitive. The format validation is done on the service.|
|orderHint|String|Hint used to order tasks in the bucket view of the task board. For details about the supported format, see Using order hints in Planner.|
### [plannerCategoryDescriptions ](https://docs.microsoft.com/graph/api/resources/plannercategorydescriptions?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|category1|String|The label associated with Category 1|
|category2|String|The label associated with Category 2|
|category3|String|The label associated with Category 3|
|category4|String|The label associated with Category 4|
|category5|String|The label associated with Category 5|
|category6|String|The label associated with Category 6|
|category7|String|The label associated with Category 7|
|category8|String|The label associated with Category 8|
|category9|String|The label associated with Category 9|
|category10|String|The label associated with Category 10|
|category11|String|The label associated with Category 11|
|category12|String|The label associated with Category 12|
|category13|String|The label associated with Category 13|
|category14|String|The label associated with Category 14|
|category15|String|The label associated with Category 15|
|category16|String|The label associated with Category 16|
|category17|String|The label associated with Category 17|
|category18|String|The label associated with Category 18|
|category19|String|The label associated with Category 19|
|category20|String|The label associated with Category 20|
|category21|String|The label associated with Category 21|
|category22|String|The label associated with Category 22|
|category23|String|The label associated with Category 23|
|category24|String|The label associated with Category 24|
|category25|String|The label associated with Category 25|
### [plannerChecklistItems ](https://docs.microsoft.com/graph/api/resources/plannerchecklistitems?view=graph-rest-1.0&tabs=http)

### [plannerExternalReferences ](https://docs.microsoft.com/graph/api/resources/plannerexternalreferences?view=graph-rest-1.0&tabs=http)

### [plannerFavoritePlanReferenceCollection ](https://docs.microsoft.com/graph/api/resources/plannerfavoriteplanreferencecollection?view=graph-rest-1.0&tabs=http)

### [plannerOrderHintsByAssignee ](https://docs.microsoft.com/graph/api/resources/plannerorderhintsbyassignee?view=graph-rest-1.0&tabs=http)

### [plannerPlan ](https://docs.microsoft.com/graph/api/resources/plannerplan?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|container|plannerPlanContainer|Identifies the container of the plan. Specify only the **url**, the **containerId** and **type**, or all properties. After it's set, this property can’t be updated. Required.|
|createdBy|identitySet|Read-only. The user who created the plan.|
|createdDateTime|DateTimeOffset|Read-only. Date and time at which the plan is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|id|String| Read-only. ID of the plan. It's 28 characters long and case-sensitive. Format validation is done on the service.|
|owner (deprecated) |String| Use the **container** property instead. ID of the group that owns the plan. After it's set, this property can’t be updated. This property won't return a valid group ID if the container of the plan isn't a group.|
|title|String|Required. Title of the plan.|
### [plannerPlanContainer ](https://docs.microsoft.com/graph/api/resources/plannerplancontainer?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|containerId|String|The identifier of the resource that contains the plan. Optional.|
|type|plannerContainerType| The type of the resource that contains the plan. For supported types, see the previous table. Possible values are: `group`, `unknownFutureValue`, `roster`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `roster`. Optional.|
|url|String|The full canonical URL of the container. Optional.|
### [plannerPlanDetails ](https://docs.microsoft.com/graph/api/resources/plannerplandetails?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|categoryDescriptions|plannerCategoryDescriptions|An object that specifies the descriptions of the 25 categories that can be associated with tasks in the plan.|
|id|String| The unique identifier for the plan details. It's 28 characters long and case-sensitive. Format validation is done on the service. Read-only.|
|sharedWith|plannerUserIds|Set of user IDs that this plan is shared with. If you're using Microsoft 365 groups, use the Groups API to manage group membership to share the group's plan. You can also add existing members of the group to this collection, although it isn't required for them to access the plan owned by the group. |
### [plannerProgressTaskBoardTaskFormat ](https://docs.microsoft.com/graph/api/resources/plannerprogresstaskboardtaskformat?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| Read-only. ID of the resource. It's 28 characters long and case-sensitive. The format validation is done on the service.|
|orderHint|String|Hint value used to order the task on the progress view of the task board. For details about the supported format, see Using order hints in Planner.|
### [plannerRecentPlanReferenceCollection ](https://docs.microsoft.com/graph/api/resources/plannerrecentplanreferencecollection?view=graph-rest-1.0&tabs=http)

### [plannerRoster ](https://docs.microsoft.com/graph/api/resources/plannerroster?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| assignedSensitivityLabel | sensitivityLabelAssignmentMethod| The sensitivity label applied to the roster. If mandatory labeling is enabled for the user and no label is specified, the user can't create the roster. Also, if labels are mandatory for the user, the user can't change the label of the roster to `null`. Possible values are: `standard`, `privileged`, `auto`, `unknownFutureValue`.|
|id|String|Identifier of the **p
### [plannerRosterMember ](https://docs.microsoft.com/graph/api/resources/plannerrostermember?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the **plannerRosterMember**. Inherited from entity|
|roles|String collection|Additional roles associated with the **PlannerRosterMember**, which determines permissions of the member in the **plannerRoster**. Currently there are no available roles to assign, and every member has full control over the contents of the **plannerRoster**.|
|tenantId|String|Identifier of the tenant the user belongs to. Currently only the users from the same tenant can be added to a **plannerRoster**. |
|userId|String|Identifier of the user.|
### [plannerTask ](https://docs.microsoft.com/graph/api/resources/plannertask?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|activeChecklistItemCount|Int32|Number of checklist items with value set to `false`, representing incomplete items.|
|appliedCategories|plannerAppliedCategories|The categories to which the task has been applied. See applied Categories for possible values.|
|assigneePriority|String|Hint used to order items of this type in a list view. The format is defined as outlined here.|
|assignments|plannerAssignments|The set of assignees the task is assigned to.|
|bucketId|String|Bucket ID to which the task belongs. The bucket needs to be in the plan that the task is in. It's 28 characters long and case-sensitive. Format validation is done on the service. |
|checklistItemCount|Int32|Number of checklist items that are present on the task.|
|completedBy|identitySet|Identity of the user that completed the task.|
|completedDateTime|DateTimeOffset|Read-only. Date and time at which the `'percentComplete'` of the task is set to `'100'`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|conversationThreadId|String|Thread ID of the conversation on the task. This is the ID of the conversation thread object created in the group.|
|createdBy|identitySet|Identity of the user that created the task.|
|createdDateTime|DateTimeOffset|Read-only. Date and time at which the task is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|dueDateTime|DateTimeOffset|Date and time at which the task is due. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|hasDescription|Boolean|Read-only. Value is `true` if the details object of the task has a nonempty description and `false` otherwise.|
|id|String|Read-only. ID of the task. It's 28 characters long and case-sensitive. Format validation is done on the service.|
|orderHint|String|Hint used to order items of this type in a list view. The format is defined as outlined here.|
|percentComplete|Int32|Percentage of task completion. When set to `100`, the task is considered completed. |
|planId|String|Plan ID to which the task belongs.|
|previewType|String|This sets the type of preview that shows up on the task. The possible values are: `automatic`, `noPreview`, `checklist`, `description`, `reference`.|
|priority|Int32|Priority of the task. The valid range of values is between `0` and `10`, with the increasing value being lower priority (`0` has the highest priority and `10` has the lowest priority).  Currently, Planner interprets values `0` and `1` as "urgent", `2`, `3` and `4` as "important", `5`, `6`, and `7` as "medium", and `8`, `9`, and `10` as "low".  Additionally, Planner sets the value `1` for "urgent", `3` for "important", `5` for "medium", and `9` for "low".|
|referenceCount|Int32|Number of external references that exist on the task.|
|startDateTime|DateTimeOffset|Date and time at which the task starts. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|title|String|Title of the task.|
### [plannerTaskDetails ](https://docs.microsoft.com/graph/api/resources/plannertaskdetails?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|checklist|plannerChecklistItems|The collection of checklist items on the task.|
|description|String|Description of the task.|
|id|String| Read-only. ID of the task details. It's 28 characters long and case-sensitive. Format validation is done on the service.|
|previewType|string|This sets the type of preview that shows up on the task. The possible values are: `automatic`, `noPreview`, `checklist`, `description`, `reference`. When set to `automatic` the displayed preview is chosen by the app viewing the task.|
|references|plannerExternalReferences|The collection of references on the task.|
### [plannerTaskRecurrence ](https://docs.microsoft.com/graph/api/resources/plannertaskrecurrence?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|nextInSeriesTaskId|String|The **taskId** of the next task in this series. This value is assigned at the time the next task in the series is created, and is `null` prior to that time.|
|occurrenceId|Int32|The 1-based index of this task within the recurrence series. The first task in a series has the value `1`, the next task in the series has the value `2`, and so on.|
|previousInSeriesTaskId|String|The **taskId** of the previous task in this series. `null` for the first task in a series since it has no predecessor. All subsequent tasks in the series have a value that corresponds to their predecessors.|
|recurrenceStartDateTime|DateTimeOffset|The date and time when this recurrence series begin. For the first task in a series (**occurrenceId** = `1`) this value is copied from **schedule.patternStartDateTime**. For subsequent tasks in the series (**occurrenceId** >= `2`) this value is copied from the previous task and never changes; it preserves the start date of the recurring series. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|schedule|plannerRecurrenceSchedule|The schedule for recurrence. Clients define and edit recurrence by specifying the schedule. If **nextInSeriesTaskId** isn't assigned, clients may terminate the series by assigning `null` to this property.|
|seriesId|String|The recurrence series this task belongs to. A GUID-based value that serves as the unique identifier for a series.|
### [plannerUser ](https://docs.microsoft.com/graph/api/resources/planneruser?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| Read-only. The unique identifier for the **p
### [plannerUserIds ](https://docs.microsoft.com/graph/api/resources/planneruserids?view=graph-rest-1.0&tabs=http)

### [sensitivityLabelAssignment ](https://docs.microsoft.com/graph/api/resources/sensitivitylabelassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignmentMethod|sensitivityLabelAssignmentMethod|Indicates whether the label assignment is done automatically, as a standard, or a privileged operation. The possible values are: `standard`, `privileged`, `auto`, `unknownFutureValue`.|
|sensitivityLabelId|String|The unique identifier for the sensitivity label assigned to the file.|
|tenantId|String|The unique identifier for the tenant that hosts the file when this label is applied.|
### [taskFileAttachment ](https://docs.microsoft.com/graph/api/resources/taskfileattachment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentBytes|Binary|The base64-encoded contents of the file.|
|contentType|String|The content type of the attachment. Inherited from attachmentBase.|
|id|String|The ID of the attachment. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the attachment was last modified. Inherited from attachmentBase.|
|name|String|The name of the text displayed under the icon that represents the embedded attachment. This does not need to be the actual file name. Inherited from attachmentBase.|
|size|Int32|The size in bytes of the attachment. Inherited from attachmentBase.|
### [tasklist](https://docs.microsoft.com/graph/api/resources/tasklist?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the task list. Inherited from baseTaskList.|
|id|String|The identifier of the task list, unique in the user's mailbox. Read-only. Inherited from baseTaskList.|
### [tasks-identifiers-disclaimer](https://docs.microsoft.com/graph/api/resources/tasks-identifiers-disclaimer?view=graph-rest-1.0&tabs=http)

### [taskViewpoint ](https://docs.microsoft.com/graph/api/resources/taskviewpoint?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|reminderDateTime|dateTimeTimeZone|The date and time for a reminder alert of the **task** to occur.|
|categories|String collection|The categories associated with the task. Each category corresponds to the **d
### [todoTask ](https://docs.microsoft.com/graph/api/resources/todotask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|body|itemBody|The task body that typically contains information about the task.|
|bodyLastModifiedDateTime|DateTimeOffset|The date and time when the task body was last modified. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2020 would look like this: '2020-01-01T00:00:00Z'.|
|categories|String collection|The categories associated with the task. Each category corresponds to the **displayName** property of an outlookCategory that the user has defined.|
|completedDateTime|dateTimeTimeZone|The date and time in the specified time zone that the task was finished.|
|createdDateTime|DateTimeOffset|The date and time when the task was created. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format. For example, midnight UTC on Jan 1, 2020 would look like this: '2020-01-01T00:00:00Z'.|
|dueDateTime|dateTimeTimeZone|The date and time in the specified time zone that the task is to be finished.|
|hasAttachments|Boolean|Indicates whether the task has attachments.|
|id|String|Unique identifier for the task. By default, this value changes when the item is moved from one list to another.|
|importance|importance|The importance of the task. Possible values are: `low`, `normal`, `high`.|
|isReminderOn|Boolean|Set to true if an alert is set to remind the user of the task.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the task was last modified. By default, it is in UTC. You can provide a custom time zone in the request header. The property value uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2020 would look like this: '2020-01-01T00:00:00Z'.|
|recurrence|patternedRecurrence|The recurrence pattern for the task.|
|reminderDateTime|dateTimeTimeZone|The date and time in the specified time zone for a reminder alert of the task to occur.|
|startDateTime|dateTimeTimeZone|The date and time in the specified time zone at which the task is scheduled to start.|
|status|taskStatus|Indicates the state or progress of the task. Possible values are: `notStarted`, `inProgress`, `completed`, `waitingOnOthers`, `deferred`.|
|title|String|A brief description of the task.|
### [todoTaskList ](https://docs.microsoft.com/graph/api/resources/todotasklist?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name of the task list.|
|id|String| The identifier of the task list, unique in the user's mailbox. Read-only. Inherited from entity|
|isOwner|Boolean| True if the user is owner of the given task list.|
|isShared|Boolean| True if the task list is shared with other users|
|wellknownListName|wellknownListName| Property indicating the list name if the given list is a well-known list. Possible values are: `none`, `defaultList`, `flaggedEmails`, `unknownFutureValue`.|
### [uploadSession ](https://docs.microsoft.com/graph/api/resources/uploadsession?view=graph-rest-1.0&tabs=http)
| Property	     | Type              |Description
|:-------------------|:------------------|:------------------------------------
| expirationDateTime | DateTimeOffset    | The date and time in UTC that the upload session will expire. The complete file must be uploaded before this expiration time is reached.|
| nextExpectedRanges | String collection | A collection of byte ranges that the server is missing for the file. These ranges are zero indexed and of the format "start-end" (for example "0-26" to indicate the first 27 bytes of the file). When uploading files as Outlook attachments, instead of a collection of ranges, this property always indicates a single value "{start}", the location in the file where the next upload should begin.|
| uploadUrl          | String            | The URL endpoint that accepts PUT requests for byte ranges of the file.|
### [user ](https://docs.microsoft.com/graph/api/resources/user?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|aboutMe|String|A freeform text entry field for the user to describe themselves. Returned only on `$select`.|
|accountEnabled|Boolean| `true` if the account is enabled; otherwise, `false`. This property is required when a user is created. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).    |
|ageGroup|ageGroup|Sets the age group of the user. Allowed values: `null`, `Minor`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|assignedLicenses|assignedLicense collection|The licenses that are assigned to the user, including inherited (group-based) licenses. This property doesn't differentiate between directly assigned and inherited licenses. Use the **licenseAssignmentStates** property to identify the directly assigned and inherited licenses. Not nullable. Returned only on `$select`. Supports `$filter` (`eq`, `not`, `/$count eq 0`, `/$count ne 0`).           |
|assignedPlans|assignedPlan collection|The plans that are assigned to the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq` and `not`). |
|birthday|DateTimeOffset|The birthday of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|businessPhones|String collection|The telephone numbers for the user. NOTE: Although it's a string collection, only one number can be set for this property. Read-only for users synced from the on-premises directory. <br><br>Returned by default. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|city|String|The city where the user is located. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|companyName | String | The name of the company that the user is associated with. This property can be useful for describing the company that a guest comes from. The maximum length is 64 characters.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|consentProvidedForMinor|consentProvidedForMinor|Sets whether consent was obtained for minors. Allowed values: `null`, `Granted`, `Denied`, and `NotRequired`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|country|String|The country/region where the user is located; for example, `US` or `UK`. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|createdDateTime | DateTimeOffset |The date and time the user was created, in ISO 8601 format and UTC. The value can't be modified and is automatically populated when the entity is created. Nullable. For on-premises users, the value represents when they were first created in Microsoft Entra ID. Property is `null` for some users created before June 2018 and on-premises users that were synced to Microsoft Entra ID before June 2018. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| creationType | String | Indicates whether the user account was created through one of the following methods: <br/> <ul><li>As a regular school or work account (`null`). <li>As an external account (`Invitation`). <li>As a local account for an Azure Active Directory B2C tenant (`LocalAccount`). <li>Through self-service sign-up by an internal user using email verification (`EmailVerified`). <li>Through self-service sign-up by a guest signing up through a link that is part of a user flow (`SelfServiceSignUp`).</ul> <br>Read-only.<br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). The filter value is case-sensitive.|
|deletedDateTime| DateTimeOffset | The date and time the user was deleted. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
|department|String|The name of the department in which the user works. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, and `eq` on `null` values).|
|displayName|String|The name displayed in the address book for the user. This value is usually the combination of the user's first name, middle initial, and family name. This property is required when a user is created and it can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$orderby`, and `$search`.|
| employeeHireDate | DateTimeOffset |The date and time when the user was hired or will start work in a future hire. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeLeaveDateTime | DateTimeOffset | The date and time when the user left or will leave the organization. <br><br>To read this property, the calling app must be assigned the *User-LifeCycleInfo.Read.All* permission. To write this property, the calling app must be assigned the *User.Read.All* and *User-LifeCycleInfo.ReadWrite.All* permissions. To read this property in delegated scenarios, the admin needs at least one of the following Microsoft Entra roles: *Lifecycle Workflows Administrator*, *Global Reader*. To write this property in delegated scenarios, the admin needs the *Global Administrator* role. <br><br>Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`). <br><br>For more information, see Configure the employeeLeaveDateTime property for a user.|
| employeeId | String | The employee identifier assigned to the user by the organization. The maximum length is 16 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|employeeOrgData|employeeOrgData |Represents organization data (for example, division and costCenter) associated with a user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeType | String | Captures enterprise worker type. For example, `Employee`, `Contractor`, `Consultant`, or `Vendor`. Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`).|
|externalUserState|String|For a guest invited to the tenant using the invitation API, this property represents the invited user's invitation status. For invited users, the state can be `PendingAcceptance` or `Accepted`, or `null` for all other users. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|externalUserStateChangeDateTime|DateTimeOffset|Shows the timestamp for the latest change to the **externalUserState** property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|faxNumber|String|The fax number of the user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|givenName|String|The given name (first name) of the user. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| hireDate | DateTimeOffset | The hire date of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`. <br> **Note:** This property is specific to SharePoint in Microsoft 365. We recommend using the native **employeeHireDate** property to set and update hire date values using Microsoft Graph APIs. |
|id|String|The unique identifier for the user. Should be treated as an opaque identifier. Inherited from directoryObject. Key. Not nullable. Read-only. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
|identities|objectIdentity collection| Represents the identities that can be used to sign in to this user account. Microsoft (also known as a local account), organizations, or social identity providers such as Facebook, Google, and Microsoft can provide identity and tie it to a user account. It might contain multiple items with the same **signInType** value. <br><br>Returned only on `$select`. <br><br> Supports `$filter` (`eq`) with limitations. <!--Supports `$filter` (`eq`) including on `null` values, only where the **signInType** is not `userPrincipalName`.-->|
|imAddresses|String collection|The instant message voice-over IP (VOIP) session initiation protocol (SIP) addresses for the user. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|interests|String collection|A list for the user to describe their interests. <br><br>Returned only on `$select`.|
|isResourceAccount|Boolean| Don't use – reserved for future use.|
|jobTitle|String|The user's job title. Maximum length is 128 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|lastPasswordChangeDateTime| DateTimeOffset | The time when this Microsoft Entra user last changed their password or when their password was created, whichever date the latest action was performed. The date and time information uses ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|legalAgeGroupClassification|legalAgeGroupClassification| Used by enterprise applications to determine the legal age group of the user. This property is read-only and calculated based on **ageGroup** and **consentProvidedForMinor** properties. Allowed values: `null`, `MinorWithOutParentalConsent`, `MinorWithParentalConsent`, `MinorNoParentalConsentRequired`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`.|
|licenseAssignmentStates|licenseAssignmentState collection|State of license assignments for this user. Also indicates licenses that are directly assigned or the user inherited through group memberships. Read-only. <br><br>Returned only on `$select`.|
|mail|String|The SMTP address for the user, for example, `jeff@contoso.com`. Changes to this property update the user's **proxyAddresses** collection to include the value as an SMTP address. This property can't contain accent characters. <br/> **NOTE:** We don't recommend updating this property for Azure AD B2C user profiles. Use the **otherMails** property instead. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, and `eq` on `null` values).|
|mailboxSettings|mailboxSettings|Settings for the primary mailbox of the signed-in user. You can get or update settings for sending automatic replies to incoming messages, locale, and time zone. <br><br>Returned only on `$select`.|
|mailNickname|String|The mail alias for the user. This property must be specified when a user is created. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|mobilePhone|String|The primary cellular telephone number for the user. Read-only for users synced from the on-premises directory. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values) and `$search`. |
|mySite|String|The URL for the user's site. <br><br>Returned only on `$select`.|
|officeLocation|String|The office location in the user's place of business. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|onPremisesDistinguishedName|String| Contains the on-premises Active Directory `distinguished name` or `DN`. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. |
|onPremisesDomainName|String| Contains the on-premises `domainFQDN`, also called dnsDomainName synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`.|
|onPremisesExtensionAttributes|onPremisesExtensionAttributes|Contains extensionAttributes1-15 for the user. These extension attributes are also known as Exchange custom attributes 1-15. <br><li>For an **onPremisesSyncEnabled** user, the source of authority for this set of properties is the on-premises and is read-only. </li><li>For a cloud-only user (where **onPremisesSyncEnabled** is `false`), these properties can be set during the creation or update of a user object.  </li><li>For a cloud-only user previously synced from on-premises Active Directory, these properties are read-only in Microsoft Graph but can be fully managed through the Exchange Admin Center or the Exchange Online V2 module in PowerShell.</li><br> Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|onPremisesImmutableId|String|This property is used to associate an on-premises Active Directory user account to their Microsoft Entra user object. This property must be specified when creating a new user account in the Graph if you're using a federated domain for the user's **userPrincipalName** (UPN) property. **NOTE:** The **$** and **\_** characters can't be used when specifying this property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).                            |
|onPremisesLastSyncDateTime|DateTimeOffset|Indicates the last time at which the object was synced with the on-premises directory; for example: `2013-02-16T03:04:54Z`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).|
|onPremisesProvisioningErrors|onPremisesProvisioningError collection| Errors when using Microsoft synchronization product during provisioning. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|onPremisesSamAccountName|String| Contains the on-premises `samAccountName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|onPremisesSecurityIdentifier|String|Contains the on-premises security identifier (SID) for the user that was synchronized from on-premises to the cloud. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq` including on `null` values). |
|onPremisesSyncEnabled|Boolean| `true` if this user object is currently being synced from an on-premises Active Directory (AD); otherwise the user isn't being synced and can be managed in Microsoft Entra ID. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|onPremisesUserPrincipalName|String| Contains the on-premises `userPrincipalName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|otherMails|String collection| A list of other email addresses for the user; for example: `["bob@contoso.com", "Robert@fabrikam.com"]`. <br>NOTE: This property can't contain accent characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|passwordPolicies|String|Specifies password policies for the user. This value is an enumeration with one possible value being `DisableStrongPassword`, which allows weaker passwords than the default policy to be specified. `DisablePasswordExpiration` can also be specified. The two might be specified together; for example: `DisablePasswordExpiration, DisableStrongPassword`. <br><br>Returned only on `$select`. For more information on the default password policies, see Microsoft Entra password policies. Supports `$filter` (`ne`, `not`, and `eq` on `null` values).|
|passwordProfile|passwordProfile|Specifies the password profile for the user. The profile contains the user's password. This property is required when a user is created. The password in the profile must satisfy minimum requirements as specified by the **passwordPolicies** property. By default, a strong password is required. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|pastProjects|String collection|A list for the user to enumerate their past projects. <br><br>Returned only on `$select`.|
|postalCode|String|The postal code for the user's postal address. The postal code is specific to the user's country/region. In the United States of America, this attribute contains the ZIP code. Maximum length is 40 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| preferredDataLocation | String | The preferred data location for the user. For more information, see OneDrive Online Multi-Geo.|
|preferredLanguage|String|The preferred language for the user. The preferred language format is based on RFC 4646. The name is a combination of an ISO 639 two-letter lowercase culture code associated with the language, and an ISO 3166 two-letter uppercase subculture code associated with the country or region. Example: "en-US", or "es-ES". <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values)|
|preferredName|String|The preferred name for the user. **Not Supported. This attribute returns an empty string.**<br><br>Returned only on `$select`.|
|provisionedPlans|provisionedPlan collection|The plans that are provisioned for the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|proxyAddresses|String collection|For example: `"SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. Changes to the **mail** property update this collection to include the value as an SMTP address. For more information, see [mail and proxyAddresses properties. The proxy address prefixed with `SMTP` (capitalized) is the primary proxy address, while those addresses prefixed with `smtp` are the secondary proxy addresses. For Azure AD B2C accounts, this property has a limit of 10 unique addresses. Read-only in Microsoft Graph; you can update this property only through the Microsoft 365 admin center. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|refreshTokensValidFromDateTime|DateTimeOffset|Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. <br><br>Returned only on `$select`. Read-only. |
|responsibilities|String collection|A list for the user to enumerate their responsibilities. <br><br>Returned only on `$select`.|
| serviceProvisioningErrors    | serviceProvisioningError collection       | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a user object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance).  |
|schools|String collection|A list for the user to enumerate the schools they attended. <br><br>Returned only on `$select`.|
|securityIdentifier| String | Security identifier (SID) of the user, used in Windows scenarios. <br><br>Read-only. Returned by default. <br>Supports `$select` and `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
|showInAddressList|Boolean|**Do not use in Microsoft Graph. Manage this property through the Microsoft 365 admin center instead.** Represents whether the user should be included in the Outlook global address list. See Known issue.|
|signInActivity | signInActivity | Get the last signed-in date and request ID of the sign-in for a given user. Read-only.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`) *but not with any other filterable properties*. <br><br>**Note:** <br/><li>Details for this property require a Microsoft Entra ID P1 or P2 license and the **AuditLog.Read.All** permission.<li>This property isn't returned for a user who never signed in or last signed in before April 2020.|
|signInSessionsValidFromDateTime|DateTimeOffset| Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. Read-only. Use revokeSignInSessions to reset. <br><br>Returned only on `$select`.|
|skills|String collection|A list for the user to enumerate their skills. <br><br>Returned only on `$select`.|
|state|String|The state or province in the user's address. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|streetAddress|String|The street address of the user's place of business. Maximum length is 1,024 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|surname|String|The user's surname (family name or last name). Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|usageLocation|String|A two-letter country code (ISO standard 3166). Required for users that are assigned licenses due to legal requirements to check for availability of services in countries. Examples include: `US`, `JP`, and `GB`. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|userPrincipalName|String|The user principal name (UPN) of the user. The UPN is an Internet-style sign-in name for the user based on the Internet standard RFC 822. By convention, this value should map to the user's email name. The general format is alias@domain, where the domain must be present in the tenant's collection of verified domains. This property is required when a user is created. The verified domains for the tenant can be accessed from the **verifiedDomains** property of organization.<br>NOTE: This property can't contain accent characters. Only the following characters are allowed `A - Z`, `a - z`, `0 - 9`, ` ' . - _ ! # ^ ~`. For the complete list of allowed characters, see username policies. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`) and `$orderby`.
|userType|String|A string value that can be used to classify user types in your directory. The possible values are `Member` and `Guest`. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). **N
