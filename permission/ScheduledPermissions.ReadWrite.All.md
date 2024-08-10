# ScheduledPermissions.ReadWrite.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[POST /identityGovernance/permissionsManagement/scheduledPermissionsRequests](https://docs.microsoft.com/graph/api/permissionsmanagement-post-scheduledpermissionsrequests?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
### [permissionsDefinition ](https://docs.microsoft.com/graph/api/resources/permissionsdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authorizationSystemInfo|permissionsDefinitionAuthorizationSystem|Information relating to the authorization system and permissions assigned.|
### [requestSchedule ](https://docs.microsoft.com/graph/api/resources/requestschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|expiration|expirationPattern|When the eligible or active assignment expires.|
|recurrence|patternedRecurrence|The frequency of the  eligible or active assignment. This property is currently unsupported in PIM.|
|startDateTime|DateTimeOffset|When the  eligible or active assignment becomes active.|
### [scheduledPermissionsRequest ](https://docs.microsoft.com/graph/api/resources/scheduledpermissionsrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Defines when the identity created the request.|
|id|String|Unique identifier for the permissions request within Permissions Management. Inherited from entity.|
|justification|String|The identity's justification for the request.|
|notes|String|Additional context for the permissions request.|
|requestedPermissions|permissionsDefinition|The permissions requested.|
|scheduleInfo|requestSchedule|When to assign the requested permissions.|
|statusDetail|statusDetail|The current status of the request. The possible values are: `submitted`, `approved`, `completed`, `canceled`, `rejected`, `unknownFutureValue`.|
|ticketInfo|ticketInfo|Ticketing-related metadata that you can use to correlate to the request.|
### [ticketInfo ](https://docs.microsoft.com/graph/api/resources/ticketinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|ticketNumber|String|The ticket number.|
|ticketSystem|String|The description of the ticket system.|
