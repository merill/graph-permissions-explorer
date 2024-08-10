# ManagedTenants.ReadWrite.All

> Allows the app to read and write all managed tenant information on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /tenantRelationships/managedTenants/tenantTags/{tenantTagId}](https://docs.microsoft.com/graph/api/managedtenants-tenanttag-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/auditEvents/{auditEventId}](https://docs.microsoft.com/graph/api/managedtenants-auditevent-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementActions](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-managementactions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementActions/{managementActionId}](https://docs.microsoft.com/graph/api/managedtenants-managementaction-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementActionTenantDeploymentStatuses](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-managementactiontenantdeploymentstatuses?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementActionTenantDeploymentStatuses/{managementActionTenantDeploymentStatusId}](https://docs.microsoft.com/graph/api/managedtenants-managementactiontenantdeploymentstatus-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementIntents](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-managementintents?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementIntents/{managementIntentId}](https://docs.microsoft.com/graph/api/managedtenants-managementintent-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementTemplates](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-managementtemplates?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managementTemplates/{managementTemplateId}](https://docs.microsoft.com/graph/api/managedtenants-managementtemplate-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/myRoles](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-myroles?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantGroups](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-tenantgroups?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantGroups/{tenantGroupId}](https://docs.microsoft.com/graph/api/managedtenants-tenantgroup-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenants](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-tenants?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenants/{tenantId}](https://docs.microsoft.com/graph/api/managedtenants-tenant-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantsCustomizedInformation](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-tenantscustomizedinformation?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantsCustomizedInformation/{tenantCustomizedInformationId}](https://docs.microsoft.com/graph/api/managedtenants-tenantcustomizedinformation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantsDetailedInformation](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-tenantsdetailedinformation?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantsDetailedInformation/{tenantDetailedInformationId}](https://docs.microsoft.com/graph/api/managedtenants-tenantdetailedinformation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantTags](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-tenanttags?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantTags/{tenantTagId}](https://docs.microsoft.com/graph/api/managedtenants-tenanttag-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/tenantUsage](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-tenantusage?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /tenantRelationships/managedTenants/tenantsCustomizedInformation/{tenantCustomizedInformationId}](https://docs.microsoft.com/graph/api/managedtenants-tenantcustomizedinformation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /tenantRelationships/managedTenants/tenantTags/{tenantTagId}](https://docs.microsoft.com/graph/api/managedtenants-tenanttag-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/managementActions/{managementActionId}/apply](https://docs.microsoft.com/graph/api/managedtenants-managementaction-apply?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/managementActionTenantDeploymentStatuses/changeDeploymentStatus](https://docs.microsoft.com/graph/api/managedtenants-managementactiontenantdeploymentstatus-changedeploymentstatus?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/tenantGroups/tenantSearch](https://docs.microsoft.com/graph/api/managedtenants-tenantgroup-tenantsearch?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/tenants/{tenantId}/offboardTenant](https://docs.microsoft.com/graph/api/managedtenants-tenant-offboardtenant?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/tenants/{tenantId}/resetTenantOnboardingStatus](https://docs.microsoft.com/graph/api/managedtenants-tenant-resettenantonboardingstatus?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/tenantTags](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-post-tenanttags?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/tenantTags/{tenantTagId}/assignTag](https://docs.microsoft.com/graph/api/managedtenants-tenanttag-assigntag?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /tenantRelationships/managedTenants/tenantTags/{tenantTagId}/unassignTag](https://docs.microsoft.com/graph/api/managedtenants-tenanttag-unassigntag?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b31fa710-c9b3-4d9e-8f5e-8036eecddab9|
|**Consent Type**|Admin|
|**Display String**|Read and write all managed tenant information|
|**Description**|Allows the app to read and write all managed tenant information on behalf of the signed-in user.|
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
### [managedTenant ](https://docs.microsoft.com/graph/api/resources/managedtenants-managedtenant?view=graph-rest-1.0&tabs=http)

### [managementAction ](https://docs.microsoft.com/graph/api/resources/managedtenants-managementaction?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|category|managementCategory|The category for the management action. Possible values are: `custom`, `devices`, `identity`, `unknownFutureValue`. Optional. Read-only.|
|description|String|The description for the management action. Optional. Read-only.|
|displayName|String|The display name for the management action. Optional. Read-only.|
|id|String|The unique identifier for the management action. Required. Read-only.|
|referenceTemplateId|String|The reference for the management template used to generate the management action. Required. Read-only.|
|workloadActions|microsoft.graph.managedTenants.workloadAction collection|The collection of workload actions associated with the management action. Required. Read-only.|
### [managementActionDeploymentStatus ](https://docs.microsoft.com/graph/api/resources/managedtenants-managementactiondeploymentstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|managementActionId|String|The identifier for the management action. Required. Read-only.|
|managementTemplateId|String|The management template identifier that was used to generate the management action. Required. Read-only.|
|status|managementActionStatus|The status of the management action. Possible values are: `toAddress`, `completed`, `error`, `timeOut`, `inProgress`, `planned`, `resolvedBy3rdParty`, `resolvedThroughAlternateMitigation`, `riskAccepted`, `unknownFutureValue`. Required.|
|workloadActionDeploymentStatuses|microsoft.graph.managedTenants.workloadActionDeploymentStatus collection|The collection of workload action deployment statues for the given management action. Optional.|
### [managementActionTenantDeploymentStatus ](https://docs.microsoft.com/graph/api/resources/managedtenants-managementactiontenantdeploymentstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the tenant level deployment status. Required. Read-only.|
|statuses|microsoft.graph.managedTenants.managementActionDeploymentStatus collection|The collection of deployment status for each instance of a management action. Optional.|
|tenantGroupId|String|The identifier for the tenant group that is associated with the management action. Required. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Required. Read-only.|
### [managementIntent ](https://docs.microsoft.com/graph/api/resources/managedtenants-managementintent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name for the management intent. Optional. Read-only.|
|id|String|The unique identifier for the management intent. Required. Read-only.|
|isGlobal|Boolean|A flag indicating whether the management intent is global. Required. Read-only.|
|managementTemplates|microsoft.graph.managedTenants.managementTemplateDetailedInfo collection|The collection of management templates associated with the management intent. Optional. Read-only.|
### [managementTemplate ](https://docs.microsoft.com/graph/api/resources/managedtenants-managementtemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|category|managementCategory|The management category for the management template. Possible values are: `custom`, `devices`, `identity`, `unknownFutureValue`. Required. Read-only.|
|description|String|The description for the management template. Optional. Read-only.|
|displayName|String|The display name for the management template. Required. Read-only.|
|id|String|The unique identifier for the management template. Required. Read-only.|
|parameters|microsoft.graph.managedTenants.templateParameter collection|The collection of parameters used by the management template. Optional. Read-only.|
|workloadActions|microsoft.graph.managedTenants.workloadAction collection|The collection of workload actions associated with the management template. Optional. Read-only.|
### [myRole ](https://docs.microsoft.com/graph/api/resources/managedtenants-myrole?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignments|microsoft.graph.managedTenants.roleAssignment collection|A collection of role assignments for the managed tenant.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.|
### [tenant ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenant?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contract|microsoft.graph.managedTenants.tenantContract|The relationship details for the tenant with the managing entity.|
|createdDateTime|DateTimeOffset|The date and time the tenant was created in the multi-tenant management platform. Optional. Read-only.|
|displayName|String|The display name for the tenant. Required. Read-only.|
|id|String|The Microsoft Entra tenant identifier for the tenant. Required. Read-only.|
|lastUpdatedDateTime|DateTimeOffset|The date and time the tenant was last updated within the multi-tenant management platform. Optional. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.|
|tenantStatusInformation|microsoft.graph.managedTenants.tenantStatusInformation|The onboarding status information for the tenant. Optional. Read-only.|
### [tenantContactInformation ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenantcontactinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|email|String|The email address for the contact. Optional|
|name|String|The name for the contact. Required.|
|notes|String|The notes associated with the contact. Optional|
|phone|String|The phone number for the contact. Optional.|
|title|String|The title for the contact. Required.|
### [tenantCustomizedInformation ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenantcustomizedinformation?view=graph-rest-1.0&tabs=http)
| Property                          | Type                                                                                                                          | Description                                                                                                                                                                                         |
| :-------------------------------- | :---------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| contacts                          | microsoft.graph.managedTenants.tenantContactInformation collection | The collection of contacts for the managed tenant. Optional.                                                                                                                                        |
| displayName                       | String                                                                                                                        | The display name for the managed tenant. Required. Read-only.                                                                                                                                       |
| id                                | String                                                                                                                        | The Microsoft Entra tenant identifier for the managed tenant. Required. Read-only.                                                                                                                  |
| tenantId                          | String                                                                                                                        | The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.                                                                         |
| website                           | String                                                                                                                        | The website for the managed tenant. Required.                                                                                                                                                       |
| businessRelationship              | String                                                                                                                        | Describes the relationship between the Managed Services Provider and the managed tenant; for example, Managed, Co-managed, Licensing. The maximum length is 250 characters. Optional.               |
| complianceRequirements            | String collection                                                                                                             | Contains the compliance requirements for the customer tenant; for example, HIPPA, NIST, CMMC. The maximum length is 250 characters per compliance requirement. Optional.                            |
| managedServicesPlans              | String collection                                                                                                             | This is the Managed Services Plans for the customer tenant that the Managed Services Provider manages. The maximum length is 250 characters per managed service plan. Optional.                     |
| note                              | String                                                                                                                        | A field for the Managed Services Provider technician to input custom text to share notes between technicians within the Managed Service Providers. The maximum length is 5000 characters. Optional. |
| noteLastModifiedDateTime          | DateTimeOffset                                                                                                                | The date on which the note field of this entity was last modified. Optional.                                                                                                                        |
| partnerRelationshipManagerUserIds | String collection                                                                                                             | The list of Entra user IDs for users in the Managed Services Provider that manage the relationship with the managed tenant. Optional.                                                               |
### [tenantDetailedInformation ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenantdetailedinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|city|String|The city where the managed tenant is located. Optional. Read-only.|
|countryCode|String|The code for the country where the managed tenant is located. Optional. Read-only.|
|countryName|String|The name for the country where the managed tenant is located. Optional. Read-only.|
|defaultDomainName|String|The default domain name for the managed tenant. Optional. Read-only.|
|displayName|String|The display name for the managed tenant.|
|id|String|The unique identifier for this entity. Required. Read-only.|
|industryName|String|The business industry associated with the managed tenant. Optional. Read-only.|
|region|String|The region where the managed tenant is located. Optional. Read-only.|
|segmentName|String|The business segment associated with the managed tenant. Optional. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant.|
|verticalName|String|The vertical associated with the managed tenant. Optional. Read-only.|
### [tenantGroup ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenantgroup?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allTenantsIncluded|Boolean|A flag indicating whether all managed tenant are included in the tenant group. Required. Read-only.|
|displayName|String|The display name for the tenant group. Optional. Read-only.|
|id|String|The unique identifier for the tenant group. Required. Read-only.|
|managementActions|microsoft.graph.managedTenants.managementActionInfo collection|The collection of management action associated with the tenant group. Optional. Read-only.|
|managementIntents|microsoft.graph.managedTenants.managementIntentInfo collection|The collection of management intents associated with the tenant group. Optional. Read-only.|
|tenantIds|String collection|The collection of managed tenant identifiers include in the tenant group. Optional. Read-only.|
### [tenantInfo ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenantinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional.|
### [tenantTag ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenanttag?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdByUserId|String|The identifier for the account that created the tenant tag. Required. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the tenant tag was created. Required. Read-only.|
|deletedDateTime|DateTimeOffset|The date and time when the tenant tag was deleted. Required. Read-only.|
|description|String|The description for the tenant tag. Optional. Read-only.|
|displayName|String|The display name for the tenant tag. Required. Read-only.|
|id|String|The unique identifier for the tenant tag. Required. Read-only.|
|lastActionByUserId|String|The identifier for the account that lasted on the tenant tag. Optional. Read-only.|
|lastActionDateTime|DateTimeOffset|The date and time the last action was performed against the tenant tag. Optional. Read-only.|
|tenants|microsoft.graph.managedTenants.tenantInfo collection|The collection of managed tenants associated with the tenant tag. Optional.|
### [tenantUsage ](https://docs.microsoft.com/graph/api/resources/managedtenants-tenantusage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the tenant. Required. Read-only.|
|reportDateTime|DateTimeOffset|The day the report was generated for the previous month. Required. Read-only.|
|serviceUsages|microsoft.graph.managedTenants.serviceUsage collection|The number of monthly active users for each service in the tenant. Example services: `Excel`, `Exchange`, `Intune`, `Outlook`, `Teams`, `Word`. Required. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Read-only.|
|totalActiveUsers|Int32|The total number of unique, active users. Required. Read-only.|
