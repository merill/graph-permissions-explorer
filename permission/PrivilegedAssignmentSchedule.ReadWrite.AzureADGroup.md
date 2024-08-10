# PrivilegedAssignmentSchedule.ReadWrite.AzureADGroup

> Allows the app to read, create, and delete time-based assignment schedules for access to Azure AD groups, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleInstances?$filter=groupId eq '{groupId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-assignmentscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleInstances?$filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-assignmentscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleInstances/{privilegedAccessGroupAssignmentScheduleInstanceId}](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleInstances/filterByCurrentUser(on=parameterValue)](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleRequests?$filter=groupId eq '{groupId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-assignmentschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleRequests?$filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-assignmentschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleRequests/{privilegedAccessGroupAssignmentScheduleRequestId}](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentschedulerequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentScheduleRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentschedulerequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentSchedules?$filter=groupId eq '{groupId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-assignmentschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentSchedules?$filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-assignmentschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentSchedules/{privilegedAccessGroupAssignmentScheduleId}](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentschedule-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/assignmentSchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/privilegedAccess/group/assignmentScheduleRequests](https://docs.microsoft.com/graph/api/privilegedaccessgroup-post-assignmentschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/privilegedAccess/group/assignmentScheduleRequests/{privilegedAccessGroupAssignmentScheduleRequestId}/cancel](https://docs.microsoft.com/graph/api/privilegedaccessgroupassignmentschedulerequest-cancel?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|06dbc45d-6708-4ef0-a797-f797ee68bf4b|
|**Consent Type**|Admin|
|**Display String**|Read, create, and delete assignment schedules for access to Azure AD groups|
|**Description**|Allows the app to read, create, and delete time-based assignment schedules for access to Azure AD groups, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|41202f2c-f7ab-45be-b001-85c9728b9d69|
|**Display String**|Read, create, and delete assignment schedules for access to Azure AD groups|
|**Description**|Allows the app to read, create, and delete time-based assignment schedules for access to Azure AD groups, without a signed-in user.|
## Resources
### [privilegedAccessGroupAssignmentSchedule ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupassignmentschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of the membership or ownership assignment to the group that is governed through PIM. Required. The possible values are: `owner`, `member`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|assignmentType|privilegedAccessGroupAssignmentType|Indicates whether the membership or ownership assignment for the principal is granted through activation or direct assignment. Required. The possible values are: `assigned`, `activated`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|createdDateTime|DateTimeOffset|When the schedule was created. Optional.|
|createdUsing|String|The identifier of the access assignment or eligibility request that created this schedule. Optional. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|groupId|String|The identifier of the group representing the scope of the membership or ownership assignment through PIM for groups. Required. Supports `$filter` (`eq`).|
|id|String|The identifier of the schedule. Required. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|memberType|privilegedAccessGroupMemberType|Indicates whether the assignment is derived from a direct group assignment or through a transitive assignment. The possible values are: `direct`, `group`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|modifiedDateTime|DateTimeOffset|When the schedule was last modified. Optional.|
|principalId|String|The identifier of the principal whose membership or ownership assignment is granted through PIM for groups. Required. Supports `$filter` (`eq`).|
|scheduleInfo|requestSchedule|Represents the period of the access assignment or eligibility. The scheduleInfo can represent a single occurrence or multiple recurring instances. Required.|
|status|String|The status of the access assignment or eligibility request. The possible values are: `Canceled`, `Denied`, `Failed`, `Granted`, `PendingAdminDecision`, `PendingApproval`, `PendingProvisioning`, `PendingScheduleCreation`, `Provisioned`, `Revoked`, and `ScheduleCreated`. Not nullable. Optional. Supports `$filter` (`eq`, `ne`).|
### [privilegedAccessGroupAssignmentScheduleInstance ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupassignmentscheduleinstance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of the membership or ownership assignment relationship to the group. Required. The possible values are: `owner`, `member`,  `unknownFutureValue`. Supports `$filter` (`eq`).|
|assignmentScheduleId|String|The identifier of the privilegedAccessGroupAssignmentSchedule from which this instance was created. Required. Supports `$filter` (`eq`, `ne`).|
|assignmentType|privilegedAccessGroupAssignmentType|Indicates whether the membership or ownership assignment is granted through activation of an eligibility or through direct assignment. Required. The possible values are: `assigned`, `activated`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|endDateTime|DateTimeOffset|When the schedule instance ends. Required.|
|groupId|String|The identifier of the group representing the scope of the membership or ownership assignment through PIM for groups. Optional. Supports `$filter` (`eq`).|
|id|String|The identifier of the access assignment schedule instance. Required. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|memberType|privilegedAccessGroupMemberType| Indicates whether the assignment is derived from a group assignment. It can further imply whether the caller can manage the assignment schedule. Required. The possible values are: `direct`, `group`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|principalId|String|The identifier of the principal whose membership or ownership assignment to the group is managed through PIM for groups. Required. Supports `$filter` (`eq`).|
|startDateTime|DateTimeOffset|When this instance starts. Required.|
### [privilegedAccessGroupAssignmentScheduleRequest ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupassignmentschedulerequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of a membership or ownership assignment relationship to the group. Required. The possible values are: `owner`, `member`, `unknownFutureValue`.|
|action|String|Represents the type of operation on the group membership or ownership assignment request. The possible values are: `adminAssign`, `adminUpdate`, `adminRemove`, `selfActivate`, `selfDeactivate`, `adminExtend`, `adminRenew`. <br/><ul><li>`adminAssign`: For administrators to assign group membership or ownership to principals.</li><li>`adminRemove`: For administrators to remove principals from group membership or ownership.</li><li> `adminUpdate`: For administrators to change existing group membership or ownership assignments.</li><li>`adminExtend`: For administrators to extend expiring assignments.</li><li>`adminRenew`: For administrators to renew expired assignments.</li><li>`selfActivate`: For principals to activate their assignments.</li><li>`selfDeactivate`: For principals to deactivate their active assignments.</li></ul>|
|approvalId|String|The identifier of the approval of the request. Inherited from request.|
|completedDateTime|DateTimeOffset|The request completion date time. Inherited from request.|
|createdBy|identitySet|The principal that created this request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|createdDateTime|DateTimeOffset|The request creation date time. Inherited from request. Read-only.|
|customData|String|Free text field to define any custom data for the request. Not used. Inherited from request.|
|groupId|String|The identifier of the group representing the scope of the membership or ownership assignment through PIM for groups. Required.|
|id|String|The unique identifier for the **privilegedAccessGroupAssignmentScheduleRequest** object. Key, not nullable, Read-only. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|isValidationOnly|Boolean|Determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when they create the **privilegedAccessGroupAssignmentScheduleRequest** object.|
|principalId|String|The identifier of the principal whose membership or ownership assignment to the group is managed through PIM for groups. Supports `$filter` (`eq`, `ne`).|
|scheduleInfo|requestSchedule|The period of the group membership or ownership assignment. Recurring schedules are currently unsupported.|
|status|String|The status of the group membership or ownership assignment request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`).|
|targetScheduleId|String| The identifier of the schedule that's created from the membership or ownership assignment request. Supports `$filter` (`eq`, `ne`).|
|ticketInfo|ticketInfo|Ticket details linked to the group membership or ownership assignment request including details of the ticket number and ticket system.|
### [requestSchedule ](https://docs.microsoft.com/graph/api/resources/requestschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|expiration|expirationPattern|When the eligible or active assignment expires.|
|recurrence|patternedRecurrence|The frequency of the  eligible or active assignment. This property is currently unsupported in PIM.|
|startDateTime|DateTimeOffset|When the  eligible or active assignment becomes active.|
### [ticketInfo ](https://docs.microsoft.com/graph/api/resources/ticketinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|ticketNumber|String|The ticket number.|
|ticketSystem|String|The description of the ticket system.|
