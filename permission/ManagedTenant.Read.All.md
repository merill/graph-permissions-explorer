# ManagedTenant.Read.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /tenantRelationships/managedTenants/auditEvents](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-auditevents?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
### [auditEvent ](https://docs.microsoft.com/graph/api/resources/managedtenants-auditevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activity|String|A string that uniquely represents the operation that occurred. Required. Read-only.|
|activityDateTime|DateTimeOffset|The time when the activity occurred. Required. Read-only.|
|activityId|String|The identifier of the activity request that made the audit event. Required. Read-only.|
|category|String|A category that represents a logical grouping of activities. Required. Read-only.|
|httpVerb|String|The HTTP verb that was used when making the API request. Required. Read-only.|
|id|String|The unique identifier of the audit event. Required. Read-only.|
|initiatedByAppId|String|The identifier of the app that was used to make the request. Required. Read-only.|
|initiatedByUpn|String|The UPN of the user who initiated the activity. Required. Read-only.|
|initiatedByUserId|String|The identifier of the user who initiated the activity. Required. Read-only.|
|ipAddress|String|The IP address of where the activity was initiated. This may be an IPv4 or IPv6 address. Required. Read-only.|
|requestBody|String|The raw HTTP request body. Some sensitive information may be removed.|
|requestUrl|String|The raw HTTP request URL. Required. Read-only.|
|tenantIds|String|The collection of Microsoft Entra tenant identifiers for the managed tenants that were affected by a change, and is formatted as a list of comma-separated values. Required. Read-only.|
|tenantNames|String|The collection of tenant names that were affected by a change, and is formatted as a list of comma-separated values. Required. Read-only.|
