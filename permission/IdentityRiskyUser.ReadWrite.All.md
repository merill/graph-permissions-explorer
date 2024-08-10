# IdentityRiskyUser.ReadWrite.All

> Allows the app to read and update identity risky user information for all users in your organization on behalf of the signed-in user. Update operations include dismissing risky users.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /identityProtection/riskyUsers/{id}/history/](https://docs.microsoft.com/graph/api/riskyuser-list-history?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityProtection/riskyUsers/{riskyUserId}/history](https://docs.microsoft.com/graph/api/riskyuser-list-history?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityProtection/riskyUsers/{userid}/history/{id}](https://docs.microsoft.com/graph/api/riskyuserhistoryitem-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /riskyUsers/{id}/history](https://docs.microsoft.com/graph/api/riskyuser-list-history?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /riskyUsers/{userid}/history/{id}](https://docs.microsoft.com/graph/api/riskyuserhistoryitem-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /auditLogs/signIns/confirmCompromised](https://docs.microsoft.com/graph/api/signin-confirmcompromised?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /auditLogs/signIns/confirmSafe](https://docs.microsoft.com/graph/api/signin-confirmsafe?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identityProtection/riskyUsers/confirmCompromised](https://docs.microsoft.com/graph/api/riskyuser-confirmcompromised?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityProtection/riskyUsers/dismiss](https://docs.microsoft.com/graph/api/riskyuser-dismiss?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /riskyUsers/confirmCompromised](https://docs.microsoft.com/graph/api/riskyusers-confirmcompromised?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /riskyUsers/dismiss](https://docs.microsoft.com/graph/api/riskyusers-dismiss?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|e0a7cdbb-08b0-4697-8264-0069786e9674|
|**Consent Type**|Admin|
|**Display String**|Read and write risky user information|
|**Description**|Allows the app to read and update identity risky user information for all users in your organization on behalf of the signed-in user. Update operations include dismissing risky users.|
## Application Permission
|||
|-|-|
|**Id**|656f6061-f9fe-4807-9708-6a2e0934df76|
|**Display String**|Read and write all risky user information|
|**Description**|Allows the app to read and update identity risky user information for your organization without a signed-in user.  Update operations include dismissing risky users.|
## Resources
### [riskyUser ](https://docs.microsoft.com/graph/api/resources/riskyuser?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID of the user at risk.|
|isDeleted|Boolean|Indicates whether the user is deleted. Possible values are: `true`, `false`.|
|isProcessing|Boolean|Indicates whether the backend is processing a user's risky state.|
|riskLastUpdatedDateTime|DateTimeOffset|The date and time that the risky user was last updated. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|riskLevel|riskLevel|Level of the detected risky user. Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|riskState|riskState|State of the user's risk. Possible values are: `none`, `confirmedSafe`, `remediated`, `dismissed`, `atRisk`, `confirmedCompromised`, `unknownFutureValue`.|
|riskDetail|riskDetail| The possible values are `none`, `adminGeneratedTemporaryPassword`, `userPerformedSecuredPasswordChange`, `userPerformedSecuredPasswordReset`, `adminConfirmedSigninSafe`, `aiConfirmedSigninSafe`, `userPassedMFADrivenByRiskBasedPolicy`, `adminDismissedAllRiskForUser`, `adminConfirmedSigninCompromised`, `hidden`, `adminConfirmedUserCompromised`, `unknownFutureValue`, `adminConfirmedServicePrincipalCompromised`, `adminDismissedAllRiskForServicePrincipal`, `m365DAdminDismissedDetection`, `userChangedPasswordOnPremises`, `adminDismissedRiskForSignIn`, `adminConfirmedAccountSafe`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value or values in this evolvable enum: `adminConfirmedServicePrincipalCompromised`, `adminDismissedAllRiskForServicePrincipal`, `m365DAdminDismissedDetection`, `userChangedPasswordOnPremises`, `adminDismissedRiskForSignIn`, `adminConfirmedAccountSafe`.|
|userDisplayName|String|Risky user display name.|
|userPrincipalName|String|Risky user principal name.|
### [riskyUserHistoryItem ](https://docs.microsoft.com/graph/api/resources/riskyuserhistoryitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activity|riskUserActivity|The activity related to user risk level change.|
|id|String|The unique identifier for the **riskyUserHistoryItem** object. Inherited from entity.|
|initiatedBy|String|The ID of actor that does the operation.|
|isDeleted|Boolean|Indicates whether the user is deleted. Inherited from riskyUser.|
|isProcessing|Boolean|Indicates whether a user's risky state is being processed by the backend. Inherited from riskyUser.|
|riskDetail|riskDetail|Details of the detected risk. Inherited from riskyUser. Possible values are: `none`, `adminGeneratedTemporaryPassword`, `userPerformedSecuredPasswordChange`, `userPerformedSecuredPasswordReset`, `adminConfirmedSigninSafe`, `aiConfirmedSigninSafe`, `userPassedMFADrivenByRiskBasedPolicy`, `adminDismissedAllRiskForUser`, `adminConfirmedSigninCompromised`, `hidden`, `adminConfirmedUserCompromised`, `unknownFutureValue`.|
|riskLastUpdatedDateTime|DateTimeOffset|The date and time when the risky user was last updated. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from riskyUser.|
|riskLevel|riskLevel|Level of the detected risky user. Inherited from riskyUser. Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|riskState|riskState|State of the user's risk. Inherited from riskyUser. Possible values are: `none`, `confirmedSafe`, `remediated`, `dismissed`, `atRisk`, `confirmedCompromised`, `unknownFutureValue`.|
|userDisplayName|String|Risky user display name. Inherited from riskyUser.|
|userId|String|The ID of the user.|
|userPrincipalName|String|Risky user principal name. Inherited from riskyUser.|
