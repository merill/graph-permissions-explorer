# Schedule.Read.All

> Allows the app to read schedule, schedule groups, shifts and associated entities in the Teams or Shifts application on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[DELETE /teams/{teamId}/schedule/shifts/{shiftId}](https://docs.microsoft.com/graph/api/shift-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /me/joinedTeams/getOpenShifts](https://docs.microsoft.com/graph/api/team-getopenshifts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/joinedTeams/getShifts](https://docs.microsoft.com/graph/api/team-getshifts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/joinedTeams/getTimesOff](https://docs.microsoft.com/graph/api/team-gettimesoff?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /team/{teamId}/schedule/shiftsRoleDefinitions/{roleId}](https://docs.microsoft.com/graph/api/shiftsroledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /teams/{id}/schedule/openShiftChangeRequests](https://docs.microsoft.com/graph/api/openshiftchangerequest-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{id}/schedule/openShiftChangeRequests/{openShiftsChangeRequestId}](https://docs.microsoft.com/graph/api/openshiftchangerequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{id}/schedule/openShifts](https://docs.microsoft.com/graph/api/openshift-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{id}/schedule/openShifts/{openShiftId}](https://docs.microsoft.com/graph/api/openshift-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule](https://docs.microsoft.com/graph/api/schedule-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/offerShiftRequests/{offerShiftRequestId}](https://docs.microsoft.com/graph/api/offershiftrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/schedulingGroups](https://docs.microsoft.com/graph/api/schedule-list-schedulinggroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/schedulingGroups/{schedulingGroupId}](https://docs.microsoft.com/graph/api/schedulinggroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/shifts](https://docs.microsoft.com/graph/api/schedule-list-shifts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/shifts/{shiftId}](https://docs.microsoft.com/graph/api/shift-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/swapShiftsChangeRequests](https://docs.microsoft.com/graph/api/swapshiftschangerequest-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /teams/{teamId}/schedule/timeCards](https://docs.microsoft.com/graph/api/timecard-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teams/{teamId}/schedule/timeCards/{timeCardId}](https://docs.microsoft.com/graph/api/timecard-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/timeOffReasons](https://docs.microsoft.com/graph/api/schedule-list-timeoffreasons?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/timeOffReasons/{timeOffReasonId}](https://docs.microsoft.com/graph/api/timeoffreason-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/timeOffRequests](https://docs.microsoft.com/graph/api/timeoffrequest-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/timeOffRequests/{timeOffRequestId}](https://docs.microsoft.com/graph/api/timeoffrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/timesOff](https://docs.microsoft.com/graph/api/schedule-list-timesoff?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{teamId}/schedule/timesOff/{timeOffId}](https://docs.microsoft.com/graph/api/timeoff-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /teams/{teamsId}/schedule/dayNotes](https://docs.microsoft.com/graph/api/daynote-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /teams/{teamsId}/schedule/dayNotes/{dayNoteId}](https://docs.microsoft.com/graph/api/daynote-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | user-principal-name}/joinedTeams/getOpenShifts](https://docs.microsoft.com/graph/api/team-getopenshifts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | user-principal-name}/joinedTeams/getShifts](https://docs.microsoft.com/graph/api/team-getshifts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | user-principal-name}/joinedTeams/getTimesOff](https://docs.microsoft.com/graph/api/team-gettimesoff?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|fccf6dd8-5706-49fa-811f-69e2e1b585d0|
|**Consent Type**|Admin|
|**Display String**|Read user schedule items|
|**Description**|Allows the app to read schedule, schedule groups, shifts and associated entities in the Teams or Shifts application on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7b2ebf90-d836-437f-b90d-7b62722c4456|
|**Display String**|Read all schedule items|
|**Description**|Allows the app to read all schedules, schedule groups, shifts and associated entities in the Teams or Shifts application without a signed-in user.|
## Resources
### [dayNote ](https://docs.microsoft.com/graph/api/resources/daynote?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|ID of the day note.|
|dayNoteDate|Date|The date of the day note.|
|draftDayNote|itemBody|The draft version of this day note that is viewable by managers. Only contentType text is supported.|
|sharedDayNote|itemBody|The shared version of this day note that is viewable by both employees and managers. Only contentType text is supported.|
### [offerShiftRequest ](https://docs.microsoft.com/graph/api/resources/offershiftrequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|recipientActionDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|recipientActionMessage|String| Custom message sent by recipient of the offer shift request. |
|recipientUserId|String| User ID of the recipient of the offer shift request.|
|senderShiftId|String| User ID of the sender of the offer shift request.|
### [openShift ](https://docs.microsoft.com/graph/api/resources/openshift?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|draftOpenShift|openShiftItem|An unpublished open shift.|
|schedulingGroupId|String|ID for the scheduling group that the open shift belongs to.|
|sharedOpenShift|openShiftItem|A published open shift.|
### [openShiftChangeRequest ](https://docs.microsoft.com/graph/api/resources/openshiftchangerequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|openShiftId|String| ID for the open shift.|
### [schedule ](https://docs.microsoft.com/graph/api/resources/schedule?view=graph-rest-1.0&tabs=http)

### [schedulingGroup ](https://docs.microsoft.com/graph/api/resources/schedulinggroup?view=graph-rest-1.0&tabs=http)

### [shift ](https://docs.microsoft.com/graph/api/resources/shift?view=graph-rest-1.0&tabs=http)

### [shiftsRoleDefinition ](https://docs.microsoft.com/graph/api/resources/shiftsroledefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of the role.|
|displayName|String|The display name of the role.|
|id|String|The ID of the role.|
|shiftsRolePermissions|shiftsRolePermission collection|The collection of role permissions within the role.|
### [swapShiftsChangeRequest ](https://docs.microsoft.com/graph/api/resources/swapshiftschangerequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|recipientShiftId|String|ShiftId for the recipient user with whom the request is to swap.|
### [timeCard ](https://docs.microsoft.com/graph/api/resources/timecard?view=graph-rest-1.0&tabs=http)
|Property               |Type           |Description                                                                |
|-----------------------|---------------|---------------------------------------------------------------------------|
| breaks 	|timeCardBreak collection  |The list of breaks associated with the **timeCard**.|
| clockInEvent       |timeCardEvent    | The clock-in event of the **timeCard**. |
| clockOutEvent			        |timeCardEvent  |The clock-out event of the **timeCard**. |
| confirmedBy |confirmedBy    | Indicates whether this **timeCard** entry is confirmed. Possible values are `none`, `user`, `manager`, `unknownFutureValue`.|
|createdBy|identitySet| Identity of the person who created the entity. |
|createdDateTime|DateTimeOffset| The timestamp in which the **timeCard** was created. |
| id			        |String  |Unique identifier for the **timeCard**.|
|lastModifiedBy| identitySet| Identity of the person who last modified the entity.|
|lastModifiedDateTime|DateTimeOffset| The timestamp in which the **timeCard** was last modified.|
| notes			        | itemBody  |Notes about the **timeCard**. |
| originalEntry| timeCardEntry | The original **timeCardEntry** of the **timeCard**, before user edits. |
| state 		        |timeCardState  | The current state of the **timeCard** during its life cycle.Possible values are: `clockedIn`, `onBreak`, `clockedOut`, `unknownFutureValue`.|
| userId			        |String |User ID to which  the **t
### [timeOff ](https://docs.microsoft.com/graph/api/resources/timeoff?view=graph-rest-1.0&tabs=http)

### [timeOffReason ](https://docs.microsoft.com/graph/api/resources/timeoffreason?view=graph-rest-1.0&tabs=http)
|Property          |Type           |Description                                                                                 |
|--------------|---------------|--------------------------------------------------------------------------------------------|
| createdDateTime		| DateTimeOffset        |The time stamp on which this **timeOffReason** was first created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| displayName               | String                  | The name of the **timeOffReason**. Required. |
| iconType | timeOffReasonIconType   | Supported icon types are: `none`, `car`, `calendar,` `running`, `plane`, `firstAid`, `doctor`, `notWorking`, `clock`, `juryDuty`, `globe`, `cup`, `phone`, `weather`, `umbrella`, `piggyBank`, `dog`, `cake`, `trafficCone`, `pin`, `sunny`. Required. |
| id			| String      |Unique identifier for the time-off reason.|
| isActive 			| Boolean      | Indicates whether the **timeOffReason** can be used when creating new entities or updating existing ones. Required. |
| lastModifiedBy		| identitySet        |The identity that last updated this **timeOffReason**.|
| lastModifiedDateTime		| DateTimeOffset         |The time stamp on which this **t
### [timeOffRequest ](https://docs.microsoft.com/graph/api/resources/timeoffrequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|endDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|startDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|timeOffReasonId|String|The reason for the time off.|
