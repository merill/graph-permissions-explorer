# Tasks.Read.All

> Allows the app to read all users’ tasks and task lists in your organization, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /drive/root/createdByUser/planner/tasks](https://docs.microsoft.com/graph/api/planneruser-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /groups/{group-id}/planner/plans](https://docs.microsoft.com/graph/api/plannergroup-list-plans?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /groups/{group-id}/planner/plans/delta](https://docs.microsoft.com/graph/api/plannerplan-delta?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/planner](https://docs.microsoft.com/graph/api/planneruser-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/planner/myDayTasks](https://docs.microsoft.com/graph/api/planneruser-list-mydaytasks?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /me/planner/tasks](https://docs.microsoft.com/graph/api/planneruser-list-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /me/planner/tasks/delta](https://docs.microsoft.com/graph/api/plannertask-delta?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /me/todo/lists](https://docs.microsoft.com/graph/api/todo-list-lists?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{id}/tasks/{id}/attachments/{id}](https://docs.microsoft.com/graph/api/taskfileattachment-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{id}/tasks/delta](https://docs.microsoft.com/graph/api/todotask-delta?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources](https://docs.microsoft.com/graph/api/todotask-list-linkedresources?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/attachments](https://docs.microsoft.com/graph/api/todotask-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems](https://docs.microsoft.com/graph/api/todotask-list-checklistitems?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /me/todo/lists/delta](https://docs.microsoft.com/graph/api/todotasklist-delta?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/buckets](https://docs.microsoft.com/graph/api/planner-list-buckets?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/buckets/{id}](https://docs.microsoft.com/graph/api/plannerbucket-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/buckets/{id}/tasks](https://docs.microsoft.com/graph/api/plannerbucket-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/plans](https://docs.microsoft.com/graph/api/planner-list-plans?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/plans/{id}/details](https://docs.microsoft.com/graph/api/plannerplandetails-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/plans/{plan-id}](https://docs.microsoft.com/graph/api/plannerplan-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/plans/{plan-id}/buckets](https://docs.microsoft.com/graph/api/plannerplan-list-buckets?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /planner/plans/{plan-id}/buckets/delta](https://docs.microsoft.com/graph/api/plannerbucket-delta?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /planner/plans/{plan-id}/tasks](https://docs.microsoft.com/graph/api/plannerplan-list-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /planner/rosters/{plannerRosterId}](https://docs.microsoft.com/graph/api/plannerroster-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /planner/rosters/{plannerRosterId}/members](https://docs.microsoft.com/graph/api/plannerroster-list-members?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /planner/rosters/{plannerRosterId}/members/{plannerRosterMemberId}](https://docs.microsoft.com/graph/api/plannerrostermember-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /planner/rosters/{plannerRosterId}/plans](https://docs.microsoft.com/graph/api/plannerroster-list-plans?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /planner/rosters/{plannerRosterId}/plans/delta](https://docs.microsoft.com/graph/api/plannerplan-delta?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /planner/tasks](https://docs.microsoft.com/graph/api/planner-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/tasks/{id}](https://docs.microsoft.com/graph/api/plannertask-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/tasks/{id}/assignedToTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerassignedtotaskboardtaskformat-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/tasks/{id}/bucketTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerbuckettaskboardtaskformat-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/tasks/{id}/details](https://docs.microsoft.com/graph/api/plannertaskdetails-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /planner/tasks/{id}/progressTaskBoardFormat](https://docs.microsoft.com/graph/api/plannerprogresstaskboardtaskformat-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /planner/tasks/delta](https://docs.microsoft.com/graph/api/plannertask-delta?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems](https://docs.microsoft.com/graph/api/todotask-list-checklistitems?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id | userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{todoTaskId}/checklistItems/{checklistItemId}](https://docs.microsoft.com/graph/api/checklistitem-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /users/{id}/planner](https://docs.microsoft.com/graph/api/planneruser-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /users/{id}/planner/myDayTasks](https://docs.microsoft.com/graph/api/planneruser-list-mydaytasks?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /users/{id}/planner/tasks](https://docs.microsoft.com/graph/api/planneruser-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id}/todo/lists/{id}/tasks/{id}/attachments](https://docs.microsoft.com/graph/api/todotask-list-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id}/todo/lists/{id}/tasks/{id}/attachments/{id}](https://docs.microsoft.com/graph/api/taskfileattachment-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists](https://docs.microsoft.com/graph/api/todo-list-lists?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}](https://docs.microsoft.com/graph/api/todotasklist-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks](https://docs.microsoft.com/graph/api/todotasklist-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/todotask-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources](https://docs.microsoft.com/graph/api/todotask-list-linkedresources?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/{taskId}/linkedResources/{linkedResourcesId}](https://docs.microsoft.com/graph/api/linkedresource-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/{todoTaskListId}/tasks/delta](https://docs.microsoft.com/graph/api/todotask-delta?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /users/{id|userPrincipalName}/todo/lists/delta](https://docs.microsoft.com/graph/api/todotasklist-delta?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /users/{usersId}/planner/rosterPlans](https://docs.microsoft.com/graph/api/planneruser-list-rosterplans?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /planner/plans/{planId}/moveToContainer](https://docs.microsoft.com/graph/api/plannerplan-movetocontainer?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|f10e1f91-74ed-437f-a6fd-d6ae88e26c1f|
|**Display String**|Read all users’ tasks and tasklist|
|**Description**|Allows the app to read all users’ tasks and task lists in your organization, without a signed-in user.|
## Resources
### [checklistItem ](https://docs.microsoft.com/graph/api/resources/checklistitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|checkedDateTime|DateTimeOffset|The date and time when the **checklistItem** was finished.|
|createdDateTime|DateTimeOffset|The date and time when the **checklistItem** was created.|
|displayName|String|Indicates the title of the **checklistItem**.|
|id|String|Server generated ID for the the **checkListItem**|
|isChecked|Boolean|State that indicates whether the item is checked off or not.|
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
### [linkedResource ](https://docs.microsoft.com/graph/api/resources/linkedresource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicationName|String|The app name of the source that sends the **linkedResource**.|
|displayName|String|The title of the **linkedResource**.|
|externalId|String|ID of the object that is associated with this task on the third-party/partner system.|
|id|String|Server generated ID for the **linkedResource**. Inherited from entity.|
|webUrl|String|Deep link to the **l
### [planner-overview](https://docs.microsoft.com/graph/api/resources/planner-overview?view=graph-rest-1.0&tabs=http)

### [plannerAssignedToTaskBoardTaskFormat ](https://docs.microsoft.com/graph/api/resources/plannerassignedtotaskboardtaskformat?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| ID of the resource. It's 28 characters long and case-sensitive. Format validation is done on the service. Read-only.|
|orderHintsByAssignee|plannerOrderHintsByAssignee|Dictionary of hints used to order tasks on the AssignedTo view of the Task Board. The key of each entry is one of the users the task is assigned to and the value is the order hint. The format of each value is defined as outlined here.|
|unassignedOrderHint|String|Hint value used to order the task on the AssignedTo view of the Task Board when the task isn't assigned to anyone, or if the orderHintsByAssignee dictionary doesn't provide an order hint for the user the task is assigned to. The format is defined as outlined here.|
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
### [plannerUser ](https://docs.microsoft.com/graph/api/resources/planneruser?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| Read-only. The unique identifier for the **p
### [taskFileAttachment ](https://docs.microsoft.com/graph/api/resources/taskfileattachment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentBytes|Binary|The base64-encoded contents of the file.|
|contentType|String|The content type of the attachment. Inherited from attachmentBase.|
|id|String|The ID of the attachment. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the attachment was last modified. Inherited from attachmentBase.|
|name|String|The name of the text displayed under the icon that represents the embedded attachment. This does not need to be the actual file name. Inherited from attachmentBase.|
|size|Int32|The size in bytes of the attachment. Inherited from attachmentBase.|
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
