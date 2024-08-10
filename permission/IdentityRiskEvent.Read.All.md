# IdentityRiskEvent.Read.All

> Allows the app to read identity risk event information for all users in your organization on behalf of the signed-in user. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /identityProtection/riskDetections](https://docs.microsoft.com/graph/api/riskdetection-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityProtection/riskDetections/{id}](https://docs.microsoft.com/graph/api/riskdetection-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityProtection/riskDetections/{riskDetectionId}](https://docs.microsoft.com/graph/api/riskdetection-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityProtection/servicePrincipalRiskDetections](https://docs.microsoft.com/graph/api/identityprotectionroot-list-serviceprincipalriskdetections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityProtection/servicePrincipalRiskDetections/{servicePrincipalRiskDetectionId}](https://docs.microsoft.com/graph/api/serviceprincipalriskdetection-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /riskDetections](https://docs.microsoft.com/graph/api/riskdetection-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /riskDetections/{id}](https://docs.microsoft.com/graph/api/riskdetection-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8f6a01e7-0391-4ee5-aa22-a3af122cef27|
|**Consent Type**|Admin|
|**Display String**|Read identity risk event information|
|**Description**|Allows the app to read identity risk event information for all users in your organization on behalf of the signed-in user. |
## Application Permission
|||
|-|-|
|**Id**|6e472fd1-ad78-48da-a0f0-97ab2c6b769e|
|**Display String**|Read all identity risk event information|
|**Description**|Allows the app to read the identity risk event information for your organization without a signed in user.|
## Resources
### [riskDetection ](https://docs.microsoft.com/graph/api/resources/riskdetection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activity|activityType|Indicates the activity type the detected risk is linked to. Possible values are: `signin`, `user`, `unknownFutureValue`.|
|activityDateTime|DateTimeOffset|Date and time that the risky activity occurred. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is look like this: `2014-01-01T00:00:00Z`|
|additionalInfo|String|Additional information associated with the risk detection in JSON format. For example, `"{\"Key\":\"userAgent\",\"Value\":\"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/68.0.3440.106 Safari/537.36\"}]"`. Possible keys in the additionalInfo JSON string are: `userAgent`, `alertUrl`, `relatedEventTimeInUtc`, `relatedUserAgent`, `deviceInformation`, `relatedLocation`, `requestId`, `correlationId`, `lastActivityTimeInUtc`, `malwareName`, `clientLocation`, `clientIp`, `riskReasons`. <br/>For more information about riskReasons and possible values, see [riskReasons values. |
|correlationId|String|Correlation ID of the sign-in associated with the risk detection. This property is `null` if the risk detection is not associated with a sign-in.|
|detectedDateTime|DateTimeOffset|Date and time that the risk was detected. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 looks like this: `2014-01-01T00:00:00Z`|
|detectionTimingType|riskDetectionTimingType|Timing of the detected risk (real-time/offline). Possible values are: `notDefined`, `realtime`, `nearRealtime`, `offline`, `unknownFutureValue`.|
|id|String|Unique ID of the risk detection. Inherited from entity|
|ipAddress|String|Provides the IP address of the client from where the risk occurred.|
|lastUpdatedDateTime|DateTimeOffset|Date and time that the risk detection was last updated. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is look like this: `2014-01-01T00:00:00Z`|
|location|signInLocation|Location of the sign-in.|
|requestId|String|Request ID of the sign-in associated with the risk detection. This property is `null` if the risk detection is not associated with a sign-in.|
|riskDetail|riskDetail|Details of the detected risk. The possible values are: `none`, `adminGeneratedTemporaryPassword`, `userPerformedSecuredPasswordChange`, `userPerformedSecuredPasswordReset`, `adminConfirmedSigninSafe`, `aiConfirmedSigninSafe`, `userPassedMFADrivenByRiskBasedPolicy`, `adminDismissedAllRiskForUser`, `adminConfirmedSigninCompromised`, `hidden`, `adminConfirmedUserCompromised`, `unknownFutureValue`, `m365DAdminDismissedDetection`. Note that you must use the `Prefer: include - unknown -enum-members` request header to get the following value(s) in this evolvable enum: `m365DAdminDismissedDetection`.|
|riskEventType|String|The type of risk event detected. The possible values are `adminConfirmedUserCompromised`, `anomalousToken`, `anomalousUserActivity`, `anonymizedIPAddress`, `generic`, `impossibleTravel`, `investigationsThreatIntelligence`, `suspiciousSendingPatterns`, `leakedCredentials`, `maliciousIPAddress`,`malwareInfectedIPAddress`, `mcasSuspiciousInboxManipulationRules`, `newCountry`, `passwordSpray`,`riskyIPAddress`, `suspiciousAPITraffic`, `suspiciousBrowser`,`suspiciousInboxForwarding`, `suspiciousIPAddress`, `tokenIssuerAnomaly`, `unfamiliarFeatures`, `unlikelyTravel`. If the risk detection is a premium detection, will show `generic`. <br/>For more information about each value, see Risk types and detection.|
|riskLevel|riskLevel|Level of the detected risk. Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|riskState|riskState|The state of a detected risky user or sign-in. Possible values are: `none`, `confirmedSafe`, `remediated`, `dismissed`, `atRisk`, `confirmedCompromised`, `unknownFutureValue`.|
|source|String|Source of the risk detection. For example, `activeDirectory`. |
|tokenIssuerType|tokenIssuerType|Indicates the type of token issuer for the detected sign-in risk. Possible values are: `AzureAD`, `ADFederationServices`, `UnknownFutureValue`.|
|userDisplayName|String|The user principal name (UPN) of the user. |
|userId|String|Unique ID of the user.|
|userPrincipalName|String|The user principal name (UPN) of the user.|
### [servicePrincipalRiskDetection ](https://docs.microsoft.com/graph/api/resources/serviceprincipalriskdetection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activity|activityType|Indicates the activity type the detected risk is linked to.  The possible values are: `signin`, `servicePrincipal`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `servicePrincipal`. |
|activityDateTime|DateTimeOffset|Date and time when the risky activity occurred. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|additionalInfo|String|Additional information associated with the risk detection. This string value is represented as a JSON object with the quotations escaped. |
|appId|String|The unique identifier for the associated application.|
|correlationId|String|Correlation ID of the sign-in activity associated with the risk detection. This property is `null` if the risk detection is not associated with a sign-in activity.|
|detectedDateTime|DateTimeOffset|Date and time when the risk was detected. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|detectionTimingType|riskDetectionTimingType|Timing of the detected risk , whether real-time or offline. The possible values are: `notDefined`, `realtime`, `nearRealtime`, `offline`, `unknownFutureValue`.|
|id|String|Unique identifier of the risk detection. Inherited from entity.|
|ipAddress|String|Provides the IP address of the client from where the risk occurred.|
|keyIds|String collection|The unique identifier for the key credential associated with the risk detection.|
|lastUpdatedDateTime|DateTimeOffset|Date and time when the risk detection was last updated.|
|location|signInLocation|Location from where the sign-in was initiated. |
|requestId|String|Request identifier of the sign-in activity associated with the risk detection. This property is `null` if the risk detection is not associated with a sign-in activity. Supports `$filter` (`eq`).|
|riskDetail|riskDetail|Details of the detected risk. <br>**Note:** Details for this property are only available for Workload Identities Premium customers. Events in tenants without this license will be returned `hidden`. <br/>The possible values are: `none`, `hidden`, `adminConfirmedServicePrincipalCompromised`, `adminDismissedAllRiskForServicePrincipal`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `adminConfirmedServicePrincipalCompromised` , `adminDismissedAllRiskForServicePrincipal`.|
|riskEventType|String|The type of risk event detected. The possible values are: `investigationsThreatIntelligence`, `generic`, `adminConfirmedServicePrincipalCompromised`, `suspiciousSignins`, `leakedCredentials`, `anomalousServicePrincipalActivity`, `maliciousApplication`, `suspiciousApplication`.|
|riskLevel|riskLevel|Level of the detected risk. <br>**Note:** Details for this property are only available for Workload Identities Premium customers. Events in tenants without this license will be returned `hidden`. The possible values are: `low`, `medium`, `high`, `hidden`, `none`.|
|riskState|riskState|The state of a detected risky service principal or sign-in activity. The possible values are: `none`, `dismissed`, `atRisk`, `confirmedCompromised`.|
|servicePrincipalDisplayName|String|	The display name for the service principal.|
|servicePrincipalId|String|The unique identifier for the service principal. Supports `$filter` (`eq`).|
|source|String|Source of the risk detection. For example, `identityProtection`.|
|tokenIssuerType|tokenIssuerType|Indicates the type of token issuer for the detected sign-in risk. The possible values are: `AzureAD`.|
