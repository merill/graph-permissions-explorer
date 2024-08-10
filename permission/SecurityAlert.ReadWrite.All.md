# SecurityAlert.ReadWrite.All

> Allows the app to read and write to all security alerts, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /security/alerts_v2](https://docs.microsoft.com/graph/api/security-list-alerts_v2?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/alerts_v2/{alertId}](https://docs.microsoft.com/graph/api/security-alert-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /security/alerts_v2/{alertId}](https://docs.microsoft.com/graph/api/security-alert-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/alerts_v2/{alertId}/comments](https://docs.microsoft.com/graph/api/security-alert-post-comments?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|471f2a7f-2a42-4d45-a2bf-594d0838070d|
|**Consent Type**|Admin|
|**Display String**|Read and write to all security alerts|
|**Description**|Allows the app to read and write to all security alerts, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|ed4fca05-be46-441f-9803-1873825f8fdb|
|**Display String**|Read and write to all security alerts|
|**Description**|Allows the app to read and write to all security alerts, without a signed-in user.|
## Resources
### [alert ](https://docs.microsoft.com/graph/api/resources/security-alert?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|actorDisplayName|String| The adversary or activity group that is associated with this alert.|
|additionalData|microsoft.graph.security.dictionary| A collection of other alert properties, including user-defined properties. Any custom details defined in the alert, and any dynamic content in the alert details, are stored here.|         
|alertPolicyId|String| The ID of the policy that generated the alert, and populated when there is a specific policy that generated the alert, whether configured by a customer or a built-in policy.|
|alertWebUrl|String|URL for the Microsoft 365 Defender portal alert page.|
|assignedTo|String| Owner of the **alert**, or null if no owner is assigned.|
|category|String| The attack kill-chain category that the alert belongs to. Aligned with the MITRE ATT&CK framework.|
|classification|microsoft.graph.security.alertClassification| Specifies whether the alert represents a true threat. Possible values are: `unknown`, `falsePositive`, `truePositive`, `informationalExpectedActivity`, `unknownFutureValue`.|
|comments|microsoft.graph.security.alertComment collection| Array of comments created by the Security Operations (SecOps) team during the alert management process.|
|createdDateTime|DateTimeOffset| Time when Microsoft 365 Defender created the alert.|
|description|String| String value describing each alert.|
|detectionSource|microsoft.graph.security.detectionSource| Detection technology or sensor that identified the notable component or activity. Possible values are: `unknown`, `microsoftDefenderForEndpoint`, `antivirus`, `smartScreen`, `customTi`, `microsoftDefenderForOffice365`, `automatedInvestigation`, `microsoftThreatExperts`, `customDetection`, `microsoftDefenderForIdentity`, `cloudAppSecurity`, `microsoft365Defender`, `azureAdIdentityProtection`, `manual`, `microsoftDataLossPrevention`, `appGovernancePolicy`, `appGovernanceDetection`, `unknownFutureValue`, `microsoftDefenderForCloud`, `microsoftDefenderForIoT`, `microsoftDefenderForServers`, `microsoftDefenderForStorage`, `microsoftDefenderForDNS`, `microsoftDefenderForDatabases`, `microsoftDefenderForContainers`, `microsoftDefenderForNetwork`, `microsoftDefenderForAppService`, `microsoftDefenderForKeyVault`, `microsoftDefenderForResourceManager`, `microsoftDefenderForApiManagement`, `microsoftSentinel`, `nrtAlerts`, `scheduledAlerts`, `microsoftDefenderThreatIntelligenceAnalytics`, `builtInMl`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `microsoftDefenderForCloud`, `microsoftDefenderForIoT`, `microsoftDefenderForServers`, `microsoftDefenderForStorage`, `microsoftDefenderForDNS`, `microsoftDefenderForDatabases`, `microsoftDefenderForContainers`, `microsoftDefenderForNetwork`, `microsoftDefenderForAppService`, `microsoftDefenderForKeyVault`, `microsoftDefenderForResourceManager`, `microsoftDefenderForApiManagement`, `microsoftSentinel`, `nrtAlerts`, `scheduledAlerts`, `microsoftDefenderThreatIntelligenceAnalytics`, `builtInMl`.|
|detectorId|String| The ID of the detector that triggered the alert.|
|determination|microsoft.graph.security.alertDetermination| Specifies the result of the investigation, whether the alert represents a true attack and if so, the nature of the attack. Possible values are: `unknown`, `apt`, `malware`, `securityPersonnel`, `securityTesting`, `unwantedSoftware`, `other`, `multiStagedAttack`, `compromisedUser`, `phishing`, `maliciousUserActivity`, `clean`, `insufficientData`, `confirmedUserActivity`, `lineOfBusinessApplication`, `unknownFutureValue`.|
|evidence|microsoft.graph.security.alertEvidence collection| Collection of evidence related to the alert.|
|firstActivityDateTime|DateTimeOffset| The earliest activity associated with the alert.|
|id|String| Unique identifier to represent the **alert** resource.|
|incidentId|String| Unique identifier to represent the incident this **alert** resource is associated with.|
|incidentWebUrl|String| URL for the incident page in the Microsoft 365 Defender portal.|
|lastActivityDateTime|DateTimeOffset| The oldest activity associated with the alert.|
|lastUpdateDateTime|DateTimeOffset| Time when the alert was last updated at Microsoft 365 Defender.|
|mitreTechniques|Collection(Edm.String)| The attack techniques, as aligned with the MITRE ATT&CK framework.|
|productName|String|The name of the product which published this alert.|
|providerAlertId|String| The ID of the alert as it appears in the security provider product that generated the alert.|
|recommendedActions|String| Recommended response and remediation actions to take in the event this alert was generated.|
|resolvedDateTime|DateTimeOffset| Time when the alert was resolved.|
|serviceSource|microsoft.graph.security.serviceSource| The service or product that created this alert. Possible values are: `unknown`, `microsoftDefenderForEndpoint`, `microsoftDefenderForIdentity`, `microsoftDefenderForCloudApps`, `microsoftDefenderForOffice365`, `microsoft365Defender`, `azureAdIdentityProtection`, `microsoftAppGovernance`, `dataLossPrevention`, `unknownFutureValue`, `microsoftDefenderForCloud`, `microsoftSentinel`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `microsoftDefenderForCloud`, `microsoftSentinel`.|
|severity|microsoft.graph.security.alertSeverity| Indicates the possible impact on assets. The higher the severity the bigger the impact. Typically higher severity items require the most immediate attention. Possible values are: `unknown`, `informational`, `low`, `medium`, `high`, `unknownFutureValue`.|
|status|microsoft.graph.security.alertStatus| The status of the alert. Possible values are: `new`, `inProgress`, `resolved`, `unknownFutureValue`.|
|tenantId|String| The Microsoft Entra tenant the alert was created in.|
|threatDisplayName|String| The threat associated with this alert.|
|threatFamilyName|String| Threat family associated with this alert.|
|title|String| Brief identifying string value describing the alert.|
|systemTags|String collection| The system tags associated with the alert.|
### [alertComment ](https://docs.microsoft.com/graph/api/resources/security-alertcomment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|comment|String|The comment text.|
|createdByDisplayName|String|The person or app name that submitted the comment.|
|createdDateTime|DateTimeOffset|The time when the comment was submitted.|
