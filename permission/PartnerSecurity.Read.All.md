# PartnerSecurity.Read.All

> Allows the app to read security alerts of customer with CSP relationship on behalf of the partner signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /security/partner/securityAlerts](https://docs.microsoft.com/graph/api/partner-security-partnersecurityalert-list-securityalerts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/partner/securityAlerts/{partnerSecurityAlertId}](https://docs.microsoft.com/graph/api/partner-security-partnersecurityalert-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5567b981-0bf1-4796-9038-0648b46e116d|
|**Consent Type**|Admin|
|**Display String**|Read security alerts of customer with CSP relationship|
|**Description**|Allows the app to read security alerts of customer with CSP relationship on behalf of the partner signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|21ffa320-2e7f-47d3-a466-7ff04d2dd68d|
|**Display String**|Read security alerts of customer with CSP relationship|
|**Description**|Allows the app to read security alerts of customer with CSP relationship, without a signed-in user.|
## Resources
### [partnerSecurityAlert ](https://docs.microsoft.com/graph/api/resources/partner-security-partnersecurityalert?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activityLogs|microsoft.graph.partner.security.activityLog collection|Represents the activity by a partner and includes details of state transitions, who performed them, and when they occurred.|
|additionalDetails|microsoft.graph.partner.security.additionalDataDictionary|A bag of name-value pairs that contain more details about an alert.|
|affectedResources|microsoft.graph.partner.security.affectedResource collection|Contains details of the resources affected by the security alert.|
|alertType|String|The type of vulnerability that impacts the customer due to this alert. For more information, see Security alerts reference guide.|
|catalogOfferId|String|The modern offer category ID of the subscription.|
|confidenceLevel|microsoft.graph.partner.security.securityAlertConfidence|Specifies the confidence in the alert. The possible values are: `low`, `medium`, `high`, `unknownFutureValue`.|
|customerTenantId|String|The impacted customer tenant associated with the alert.|
|description|String|The description for each alert.|
|detectedDateTime|DateTimeOffset|Time when the alert was detected or created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|The display name of the alert.|
|firstObservedDateTime|DateTimeOffset|Time of the first activity associated with the alert. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String|Unique identifier to represent the alert. Inherited from microsoft.graph.entity.|
|isTest|Boolean|Indicates whether an alert is a test alert.|
|lastObservedDateTime|DateTimeOffset|Time of the latest activity associated with the alert. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|resolvedBy|String|The UPN of the partner user who resolved the alert.|
|resolvedOnDateTime|DateTimeOffset|Time when the alert was resolved. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|resolvedReason|microsoft.graph.partner.security.securityAlertResolvedReason|The reason provided by the partner for addressing the alert. The possible values are: `legitimate`, `ignore`, `fraud`, `unknownFutureValue`.|
|severity|microsoft.graph.partner.security.securityAlertSeverity|Indicates the possible impact on assets. The higher the severity the bigger the impact. Typically higher severity items require the most immediate attention. The possible values are: `informational`, `high`, `medium`, `low`, `unknownFutureValue`.|
|status|microsoft.graph.partner.security.securityAlertStatus|The status of the alert. The possible values are: `active`, `resolved`, `investigating`, `unknownFutureValue`.|
|subscriptionId|String|The subscription associated with the alert for the customer.|
|valueAddedResellerTenantId|String|The value-added reseller tenant associated with the partner tenant and customer tenant.|
