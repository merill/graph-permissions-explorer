# PrivilegedEligibilitySchedule.Remove.AzureADGroup

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[POST /identityGovernance/privilegedAccess/group/eligibilityScheduleRequests](https://docs.microsoft.com/graph/api/privilegedaccessgroup-post-eligibilityschedulerequests?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
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
