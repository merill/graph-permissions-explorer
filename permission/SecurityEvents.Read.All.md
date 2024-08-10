# SecurityEvents.Read.All

> Allows the app to read your organization’s security events on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /security/alerts](https://docs.microsoft.com/graph/api/alert-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/alerts?$filter={property} eq '{property-value}'](https://docs.microsoft.com/graph/api/alert-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/alerts?$filter={property} eq '{property-value}' and {property} eq '{property-value}'](https://docs.microsoft.com/graph/api/alert-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /security/alerts?$filter={property} eq '{property-value}'&{property} eq '{property-value}'](https://docs.microsoft.com/graph/api/alert-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /security/alerts?$filter={property} eq '{property-value}'&$top=5](https://docs.microsoft.com/graph/api/alert-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/alerts?$top=1](https://docs.microsoft.com/graph/api/alert-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/alerts/{alert_id}](https://docs.microsoft.com/graph/api/alert-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /security/alerts/{id}](https://docs.microsoft.com/graph/api/alert-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /security/secureScoreControlProfiles](https://docs.microsoft.com/graph/api/security-list-securescorecontrolprofiles?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScoreControlProfiles?$filter={property} eq '{property-value}'](https://docs.microsoft.com/graph/api/security-list-securescorecontrolprofiles?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScoreControlProfiles?$top=1](https://docs.microsoft.com/graph/api/security-list-securescorecontrolprofiles?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScoreControlProfiles/{id}](https://docs.microsoft.com/graph/api/securescorecontrolprofile-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScores](https://docs.microsoft.com/graph/api/security-list-securescores?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScores?$filter={property} eq '{property-value}'](https://docs.microsoft.com/graph/api/security-list-securescores?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScores?$top=1](https://docs.microsoft.com/graph/api/security-list-securescores?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScores?$top=1&$skip=7](https://docs.microsoft.com/graph/api/security-list-securescores?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/secureScores/{id}](https://docs.microsoft.com/graph/api/securescore-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|64733abd-851e-478a-bffb-e47a14b18235|
|**Consent Type**|Admin|
|**Display String**|Read your organization’s security events|
|**Description**|Allows the app to read your organization’s security events on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|bf394140-e372-4bf9-a898-299cfc7564e5|
|**Display String**|Read your organization’s security events|
|**Description**|Allows the app to read your organization’s security events without a signed-in user.|
## Resources
### [alert](https://docs.microsoft.com/graph/api/resources/alert?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                         | Description                                                                                                                                                                                                                                                                                          |
|:---------------------|:-------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| activityGroupName    | String                                                       | Name or alias of the activity group (attacker) this alert is attributed to.                                                                                                                                                                                                                          |
| assignedTo           | String                                                       | Name of the analyst the alert is assigned to for triage, investigation, or remediation (supports update).                                                                                                                                                                  |
| azureSubscriptionId  | String                                                       | Azure subscription ID, present if this alert is related to an Azure resource.                                                                                                                                                                                                                        |
| azureTenantId        | String                                                       | Microsoft Entra tenant ID. Required.                                                                                                                                                                                                                                                          |
| category             | String                                                       | Category of the alert (for example, credentialTheft, ransomware).                                                                                                                                                                                                                              |
| closedDateTime       | DateTimeOffset                                               | Time at which the alert was closed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z` (supports update).                    |
| cloudAppStates       | cloudAppSecurityState collection | Security-related stateful information generated by the provider about the cloud application/s related to this alert.                                                                                                                                                                                 |
| comments             | String collection                                            | Customer-provided comments on alert (for customer alert management) (supports update).                                                                                                                                                                                     |
| confidence           | Int32                                                        | Confidence of the detection logic (percentage between 1-100).                                                                                                                                                                                                                                        |
| createdDateTime      | DateTimeOffset                                               | Time at which the alert was created by the alert provider. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Required.                               |
| description          | String                                                       | Alert description.                                                                                                                                                                                                                                                                                   |
| detectionIds         | String collection                                            | Set of alerts related to this alert entity (each alert is pushed to the SIEM as a separate record).                                                                                                                                                                                                  |
| eventDateTime        | DateTimeOffset                                               | Time at which the event or events that served as the trigger to generate the alert occurred. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Required. |
| feedback             | alertFeedback                                                | Analyst feedback on the alert. Possible values are: `unknown`, `truePositive`, `falsePositive`, `benignPositive`. Supports update. |
| fileStates           | fileSecurityState collection         | Security-related stateful information generated by the provider about the file(s) related to this alert.                                                                                                                                                                                             |
| hostStates           | hostSecurityState collection         | Security-related stateful information generated by the provider about the host(s) related to this alert.                                                                                                                                                                                             |
| id                   | String                                                       | Provider-generated GUID/unique identifier. Read-only. Required.                                                                                                                                                                                                                                      |
| incidentIds          | String collection                                            | IDs of incidents related to current alert.                                                                                                                                                                                                                                                           |
| lastModifiedDateTime | DateTimeOffset                                               | Time at which the alert entity was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                                                  |
| malwareStates        | malwareState collection                   | Threat Intelligence pertaining to malware related to this alert.                                                                                                                                                                                                                                     |
| networkConnections   | networkConnection collection         | Security-related stateful information generated by the provider about the network connection(s) related to this alert.                                                                                                                                                                               |
| processes            | process collection                             | Security-related stateful information generated by the provider about the process or processes related to this alert.                                                                                                                                                                                |
| recommendedActions   | String collection                                            | Vendor/provider recommended action(s) to take as a result of the alert (for example, isolate machine, enforce2FA, reimage host).                                                                                                                                                                     |
| registryKeyStates    | registryKeyState collection           | Security-related stateful information generated by the provider about the registry keys related to this alert.                                                                                                                                                                                       |
| securityResources    | securityResource collection           | Resources related to current alert. For example, for some alerts this can have the Azure Resource value.                                                                                                                                                                                             |
| severity             | alertSeverity                                                | Alert severity - set by vendor/provider. Possible values are: `unknown`, `informational`, `low`, `medium`, `high`. Required.                                                                                                                                                                         |
| sourceMaterials      | String collection                                            | Hyperlinks (URIs) to the source material related to the alert, for example, provider's user interface for alerts or log search.                                                                                                                                                                 |
| status               | alertStatus                                                  | Alert lifecycle status (stage). Possible values are: `unknown`, `newAlert`, `inProgress`, `resolved`. (supports update). Required.                                                                                                                                         |
| tags                 | String collection                                            | User-definable labels that can be applied to an alert and can serve as filter conditions (for example "HVA", "SAW") (supports update).                                                                                                                               |
| title                | String                                                       | Alert title. Required.                                                                                                                                                                                                                                                                               |
| triggers             | alertTrigger collection                   | Security-related information about the specific properties that triggered the alert (properties appearing in the alert). Alerts might contain information about multiple users, hosts, files, ip addresses. This field indicates which properties triggered the alert generation.                    |
| userStates           | userSecurityState collection         | Security-related stateful information generated by the provider about the user accounts related to this alert.                                                                                                                                                                                       |
| vendorInformation    | securityVendorInformation    | Complex type containing details about the security product/service vendor, provider, and subprovider (for example, vendor=Microsoft; provider=Windows Defender ATP; subProvider=AppLocker). Required.                                                                                                |
| vulnerabilityStates  | vulnerabilityState collection       | Threat intelligence pertaining to one or more vulnerabilities related to this alert.                                                                                                                                                                                                                 |
### [secureScore ](https://docs.microsoft.com/graph/api/resources/securescore?view=graph-rest-1.0&tabs=http)
|Property |Type |Description |
|:--|:--|:--|
|	activeUserCount	|	Int32	|	Active user count of the given tenant.	|
|	averageComparativeScores |	averageComparativeScore collection	|Average score by different scopes (for example, average by industry, average by seating) and control category (Identity, Data, Device, Apps, Infrastructure) within the scope.	|
|	azureTenantId	|	String	|	GUID string for tenant ID.	|
|	controlScores |	controlScore collection	|	Contains tenant scores for a set of controls.	|
|	createdDateTime	|	DateTimeOffset	|	When the report was created.  |
|	currentScore	|	Double	|	Tenant current attained score on specified date.	|
|	enabledServices |	String collection	|	Microsoft-provided services for the tenant (for example, Exchange online, Skype, Sharepoint).	|
|id |String|Provider-generated GUID/unique identifier. Read-only. Required.|
|	licensedUserCount	|	Int32	|	Licensed user count of the given tenant.	|
|	maxScore |	Double	|	Tenant maximum possible score on specified date.	|
|vendorInformation |securityVendorInformation|Complex type containing details about the security product/service vendor, provider, and subprovider (for example, vendor=Microsoft; provider=SecureScore). Required.|
### [secureScoreControlProfile ](https://docs.microsoft.com/graph/api/resources/securescorecontrolprofile?view=graph-rest-1.0&tabs=http)

### [secureScoreControlProfile ](https://docs.microsoft.com/graph/api/resources/securescorecontrolprofiles?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:--|:--|:--|
|actionType|String|Control action type (Config, Review, Behavior).|
|actionUrl|String|URL to where the control can be actioned.|
|azureTenantId|String|GUID string for tenant ID.|
|complianceInformation|complianceInformation collection|The collection of compliance information associated with secure score control|
|controlCategory|String|Control action category (Account, Data, Device, Apps, Infrastructure).|
|controlName|String|Name of the control.|
|controlStateUpdates|secureScoreControlStateUpdate collection|Flag to indicate where the tenant has marked a control (ignored, thirdParty, reviewed) (supports update).|
|deprecated|Boolean|Flag to indicate if a control is depreciated.|
|id|String|Provider-generated GUID/unique identifier. Read-only. Required.|
|implementationCost|String|Resource cost of implemmentating control (low, moderate, high).|
|lastModifiedDateTime|DateTimeOffset|Time at which the control profile entity was last modified. The Timestamp type represents date and time| 
|maxScore|String|Current obtained max score on specified date.|
|rank|Int32|Microsoft's stack ranking of control.|
|remediation|String|Description of what the control will help remediate.|
|remediationImpact|String|Description of the impact on users of the remediation.|
|service|String|Service that owns the control (Exchange, Sharepoint, Microsoft Entra ID).|
|threats|String collection|List of threats the control mitigates (accountBreach, dataDeletion, dataExfiltration, dataSpillage, elevationOfPrivilege, maliciousInsider, passwordCracking, phishingOrWhaling, spoofing).|
|tier|String|Control tier (Core, Defense in Depth, Advanced.)|
|title|String|Title of the control.|
|userImpact|String|User impact of implementing control (low, moderate, high).|
|vendorInformation|securityVendorInformation|Complex type containing details about the security product/service vendor, provider, and subprovider (for example, vendor=Microsoft; provider=SecureScore). Required.|
### [security-error-codes](https://docs.microsoft.com/graph/api/resources/security-error-codes?view=graph-rest-1.0&tabs=http)

