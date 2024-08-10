# PrivilegedEligibilitySchedule.ReadWrite.AzureADGroup

> Allows the app to read, create, and delete time-based eligibility schedules for access to Azure AD groups, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleInstances?$filter=groupId eq '{groupId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-eligibilityscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleInstances?filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-eligibilityscheduleinstances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleInstances/{privilegedAccessGroupEligibilityScheduleInstanceId}](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityscheduleinstance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleInstances/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityscheduleinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests?$filter=groupId eq '{groupId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-eligibilityschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests?$filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-eligibilityschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests/{privilegedAccessGroupEligibilityScheduleRequestId}](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityschedulerequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityschedulerequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilitySchedules?$filter=groupId eq '{groupId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-eligibilityschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilitySchedules?filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/privilegedaccessgroup-list-eligibilityschedules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilitySchedules/{privilegedAccessGroupEligibilityScheduleId}](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityschedule-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/privilegedAccess/group/eligibilitySchedules/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityschedule-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests](https://docs.microsoft.com/graph/api/privilegedaccessgroup-post-eligibilityschedulerequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests/{privilegedAccessGroupEligibilityScheduleRequestId}/cancel](https://docs.microsoft.com/graph/api/privilegedaccessgroupeligibilityschedulerequest-cancel?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ba974594-d163-484e-ba39-c330d5897667|
|**Consent Type**|Admin|
|**Display String**|Read, create, and delete eligibility schedules for access to Azure AD groups|
|**Description**|Allows the app to read, create, and delete time-based eligibility schedules for access to Azure AD groups, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|618b6020-bca8-4de6-99f6-ef445fa4d857|
|**Display String**|Read, create, and delete eligibility schedules for access to Azure AD groups|
|**Description**|Allows the app to read, create, and delete time-based eligibility schedules for access to Azure AD groups, without a signed-in user.|
## Resources
### [privilegedAccessGroupEligibilitySchedule ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupeligibilityschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of the membership or ownership eligibility to the group that is governed by PIM. Required. The possible values are: `owner`, `member`. Supports `$filter` (`eq`).|
|createdDateTime|DateTimeOffset|When the schedule was created. Optional. Inherited from privilegedAccessSchedule.|
|createdUsing|String|The identifier of the access assignment or eligibility request that creates this schedule. Optional. Inherited from privilegedAccessSchedule. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|groupId|String|The identifier of the group representing the scope of the membership or ownership eligibility through PIM for groups. Required. Supports `$filter` (`eq`).|
|id|String|The identifier of the schedule. Required. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|memberType|privilegedAccessGroupMemberType|Indicates whether the assignment is derived from a group assignment. It can further imply whether the caller can manage the schedule. Required. The possible values are: `direct`, `group`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|modifiedDateTime|DateTimeOffset|When the schedule was last modified. Optional. Inherited from privilegedAccessSchedule.|
|principalId|String|The identifier of the principal whose membership or ownership eligibility is granted through PIM for groups. Required. Supports `$filter` (`eq`).|
|scheduleInfo|requestSchedule|Represents the period of the access assignment or eligibility. The scheduleInfo can represent a single occurrence or multiple recurring instances. Required. Inherited from privilegedAccessSchedule.|
|status|String|The status of the access assignment or eligibility request. The possible values are: `Canceled`, `Denied`, `Failed`, `Granted`, `PendingAdminDecision`, `PendingApproval`, `PendingProvisioning`, `PendingScheduleCreation`, `Provisioned`, `Revoked`, and `ScheduleCreated`. Not nullable. Optional. Inherited from privilegedAccessSchedule. Supports `$filter` (`eq`, `ne`).|
### [privilegedAccessGroupEligibilityScheduleInstance ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupeligibilityscheduleinstance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of the membership or ownership eligibility relationship to the group. Required. The possible values are: `owner`, `member`. Supports `$filter` (`eq`).|
|eligibilityScheduleId|String|The identifier of the privilegedAccessGroupEligibilitySchedule from which this instance was created. Required. Supports `$filter` (`eq`, `ne`).|
|endDateTime|DateTimeOffset|When the schedule instance ends. Required.|
|groupId|String|The identifier of the group representing the scope of the membership or ownership eligibility through PIM for groups. Required. Supports `$filter` (`eq`).|
|id|String|The identifier of the access assignment schedule instance. Required. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|memberType|privilegedAccessGroupMemberType|Indicates whether the assignment is derived from a group assignment. It can further imply whether the calling principal can manage the assignment schedule. Required. The possible values are: `direct`, `group`, `unknownFutureValue`. Supports `$filter` (`eq`).|
|principalId|String|The identifier of the principal whose membership or ownership eligibility to the group is managed through PIM for groups. Required. Supports `$filter` (`eq`).|
|startDateTime|DateTimeOffset|When this instance starts. Required.|
### [privilegedAccessGroupEligibilityScheduleRequest ](https://docs.microsoft.com/graph/api/resources/privilegedaccessgroupeligibilityschedulerequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessId|privilegedAccessGroupRelationships|The identifier of membership or ownership eligibility relationship to the group. Required. The possible values are: `owner`, `member`, `unknownFutureValue`.|
|action|String|Represents the type of operation on the group membership or ownership eligibility assignment request. The possible values are: `adminAssign`, `adminUpdate`, `adminRemove`, `selfActivate`, `selfDeactivate`, `adminExtend`, `adminRenew`. <br/><ul><li>`adminAssign`: For administrators to assign group membership or ownership eligibility to principals.</li><li>`adminRemove`: For administrators to remove principals from group membership or ownership eligibilities.</li><li> `adminUpdate`: For administrators to change existing eligible assignments.</li><li>`adminExtend`: For administrators to extend expiring eligible assignments.</li><li>`adminRenew`: For administrators to renew expired eligible assignments.</li><li>`selfActivate`: For principals to activate their eligible assignments.</li><li>`selfDeactivate`: For principals to deactivate their eligible assignments.</li></ul>|
|approvalId|String|The identifier of the approval of the request. Inherited from request.|
|completedDateTime|DateTimeOffset|The request completion date time. Inherited from request.|
|createdBy|identitySet|The principal that created this request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`, and on `null` values).|
|createdDateTime|DateTimeOffset|The request creation date time. Inherited from request. Read-only.|
|customData|String|Free text field to define any custom data for the request. Not used. Inherited from request.|
|groupId|String|The identifier of the group representing the scope of the membership and ownership eligibility through PIM for groups. Required.|
|id|String|The unique identifier for the **privilegedAccessGroupEligibilityScheduleRequest** object. Key, not nullable, read-only. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|isValidationOnly|Boolean|Determines whether the call is a validation or an actual call. Only set this property if you want to check whether an activation is subject to additional rules like MFA before actually submitting the request.|
|justification|String|A message provided by users and administrators when they create the **privilegedAccessGroupEligibilityScheduleRequest** object.|
|principalId|String|The identifier of the principal whose membership or ownership eligibility to the group is managed through PIM for groups. Required.|
|scheduleInfo|requestSchedule|The period of the group membership or ownership assignment. Recurring schedules are currently unsupported.|
|status|String|The status of the group membership or ownership assignment request. Inherited from request. Read-only. Supports `$filter` (`eq`, `ne`).|
|targetScheduleId|String|The identifier of the schedule that's created from the eligibility request. Optional.|
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
