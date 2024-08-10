# AuditLog.Read.All

> Allows the app to read and query your audit log activities, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /auditLogs/directoryaudits](https://docs.microsoft.com/graph/api/directoryaudit-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /auditLogs/directoryAudits](https://docs.microsoft.com/graph/api/directoryaudit-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /auditLogs/directoryAudits/{id}](https://docs.microsoft.com/graph/api/directoryaudit-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /auditLogs/provisioning](https://docs.microsoft.com/graph/api/provisioningobjectsummary-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /auditLogs/signIns](https://docs.microsoft.com/graph/api/signin-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /auditLogs/signIns/{id}](https://docs.microsoft.com/graph/api/signin-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/appCredentialSignInActivities](https://docs.microsoft.com/graph/api/reportroot-list-appcredentialsigninactivities?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/appCredentialSignInActivities/{appCredentialSignInActivityId}](https://docs.microsoft.com/graph/api/appcredentialsigninactivity-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/authenticationMethods/userRegistrationDetails](https://docs.microsoft.com/graph/api/authenticationmethodsroot-list-userregistrationdetails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/authenticationMethods/userRegistrationDetails/{userId}](https://docs.microsoft.com/graph/api/userregistrationdetails-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/authenticationMethods/usersRegisteredByFeature](https://docs.microsoft.com/graph/api/authenticationmethodsroot-usersregisteredbyfeature?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/authenticationMethods/usersRegisteredByMethod](https://docs.microsoft.com/graph/api/authenticationmethodsroot-usersregisteredbymethod?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/servicePrincipalSignInActivities](https://docs.microsoft.com/graph/api/reportroot-list-serviceprincipalsigninactivities?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/servicePrincipalSignInActivities/{servicePrincipalSignInActivityId}](https://docs.microsoft.com/graph/api/serviceprincipalsigninactivity-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|e4c9e354-4dc5-45b8-9e7c-e1393b0b1a20|
|**Consent Type**|Admin|
|**Display String**|Read audit log data|
|**Description**|Allows the app to read and query your audit log activities, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|b0afded3-3588-46d8-8b3d-9842eff778da|
|**Display String**|Read all audit log data|
|**Description**|Allows the app to read and query your audit log activities, without a signed-in user.|
## Resources
### [appCredentialSignInActivity ](https://docs.microsoft.com/graph/api/resources/appcredentialsigninactivity?view=graph-rest-1.0&tabs=http)
| Property                 | Type                                             | Description                                                                                           |
| ------------------------ | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| appId                    | String                                           | The globally unique **appId** (also called *client ID* on the Microsoft Entra admin center) of the credentialed application.                                                                 |
| appObjectId              | String                                           | The ID of the credential application instance.                                                        |
| createdDateTime          | DateTimeOffset                                   | The date and time when the credential was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                                                   |
| credentialOrigin         | applicationKeyOrigin                             | The type the key credential originated from. Possible values are: `application`, `servicePrincipal`, `unknownFutureValue`. |
| expirationDateTime       | DateTimeOffset                                   | The date and time when the credential is set to expire. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                                                   |
| id                       | String                                           | The unique identifier of the **appCredentialSignInActivity** instance in the response.                    |
| keyId                    | String                                           | The key ID of the credential.                                                                          |
| keyType                  | applicationKeyType                               | Specifies the key type. The possible values are: `clientSecret`, `certificate`, `unknownFutureValue`. |
| keyUsage                 | applicationKeyUsage                              | Specifies what the key was used for. The possible values are: `sign`, `verify`, `unknownFutureValue`.  |
| resourceId               | String                                           | The ID of the accessed resource.                                                                      |
| servicePrincipalObjectId | String                                           | The ID of the service principal.                                                                      |
| signInActivity           | signInActivity | The sign-in activity of the credential across all flows.                                              |
### [directoryAudit ](https://docs.microsoft.com/graph/api/resources/directoryaudit?view=graph-rest-1.0&tabs=http)
| Property            | Type                                                | Description                                                                                                                                                                                                                                                                        |
|:--------------------|:----------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| activityDateTime    | DateTimeOffset                                      | Indicates the date and time the activity was performed. The Timestamp type is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$filter` (`eq`, `ge`, `le`) and `$orderby`.                                                                                          |
| activityDisplayName | String                                              | Indicates the activity name or the operation name (examples: "Create User" and "Add member to group"). For a list of activities logged, refer to Microsoft Entra audit log categories and activities. Supports `$filter` (`eq`, `startswith`). |
| additionalDetails   | keyValue collection                  | Indicates additional details on the activity.                                                                                                                                                                                                                                      |
| category            | String                                              | Indicates which resource category that's targeted by the activity. For example: `UserManagement`, `GroupManagement`, `ApplicationManagement`, `RoleManagement`. For a list of categories for activities logged, refer to Microsoft Entra audit log categories and activities.                                                                                                                                                          |
| correlationId       | Guid                                                | Indicates a unique ID that helps correlate activities that span across various services. Can be used to trace logs across services. Supports `$filter` (`eq`).                                                                                                                                                |
| id                  | String                                              | Indicates the unique ID for the activity. This is a GUID. Supports `$filter` (`eq`).                                                                                                                                                                                                                          |
| initiatedBy         | auditActivityInitiator | Indicates information about the user or app initiated the activity. Supports `$filter` (`eq`) for **user**/**id**, **user**/**displayName**, **user**/**userPrincipalName**, **app**/**appId**, **app**/**displayName**; and `$filter` (`startswith`) for **user**/**userPrincipalName**.                                                                                                                                                                                                               |
| loggedByService     | String                                              | Indicates information on which service initiated the activity (For example: `Self-service Password Management`, `Core Directory`, `B2C`, `Invited Users`, `Microsoft Identity Manager`, `Privileged Identity Management`. Supports `$filter` (`eq`).                                                                      |
| operationType       | String                                              | Indicates the type of operation that was performed. The possible values include but are not limited to the following: `Add`, `Assign`, `Update`, `Unassign`, and `Delete`.                                                                                   |
| result              | operationResult                                              | Indicates the result of the activity. Possible values are: `success`, `failure`, `timeout`, `unknownFutureValue`.                                                                                                                                                                   |
| resultReason        | String                                              | Indicates the reason for failure if the **result** is `failure` or `timeout`.                                                                                                                                                                                                                                 |
| targetResources     | targetResource collection      | Indicates information on which resource was changed due to the activity. Target Resource Type can be `User`, `Device`, `Directory`, `App`, `Role`, `Group`, `Policy` or `Other`. Supports `$filter` (`eq`) for **i
### [provisioningObjectSummary ](https://docs.microsoft.com/graph/api/resources/provisioningobjectsummary?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|activityDateTime|DateTimeOffset|Represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. <br/><br/> SUpports `$filter` (`eq`, `gt`, `lt`) and `orderby`.|
|changeId|String|Unique ID of this change in this cycle. Supports `$filter` (`eq`, `contains`).|
|cycleId|String|Unique ID per job iteration. Supports `$filter` (`eq`, `contains`).|
|durationInMilliseconds|Int32|Indicates how long this provisioning action took to finish. Measured in milliseconds.|
|id|String| Indicates the unique ID for the activity. Read-only. Supports `$filter` (`eq`, `contains`).|
|initiatedBy|initiator|Details of who initiated this provisioning. Supports `$filter` (`eq`, `contains`).|
|jobId|String|The unique ID for the whole provisioning job. Supports `$filter` (`eq`, `contains`).|
|modifiedProperties|modifiedProperty collection|Details of each property that was modified in this provisioning action on this object.|
|provisioningAction|provisioningAction|Indicates the activity name or the operation name. Possible values are: `create`, `update`, `delete`, `stageddelete`, `disable`, `other` and `unknownFutureValue`. For a list of activities logged, refer to Microsoft Entra activity list. Supports `$filter` (`eq`, `contains`).|
|provisioningStatusInfo|provisioningStatusInfo|Details of provisioning status.|
|provisioningSteps|provisioningStep collection|Details of each step in provisioning.|
|servicePrincipal|servicePrincipal collection|Represents the service principal used for provisioning. Supports `$filter` (`eq`) for **id** and **name**.|
|sourceIdentity|provisionedIdentity|Details of source object being provisioned. Supports `$filter` (`eq`, `contains`) for **identityType**, **id**, and **displayName***.|
|sourceSystem|provisioningSystem|Details of source system of the object being provisioned. Supports `$filter` (`eq`, `contains`) for **displayName**.|
|targetIdentity|provisionedIdentity|Details of target object being provisioned. Supports `$filter` (`eq`, `contains`) for **identityType**, **id**, and **displayName***.|
|targetSystem|provisioningSystem|Details of target system of the object being provisioned. Supports `$filter` (`eq`, `contains`) for **displayName**.|
|tenantId|String|Unique Microsoft Entra tenant ID. Supports `$filter` (`eq`, `contains`).|
### [servicePrincipalSignInActivity ](https://docs.microsoft.com/graph/api/resources/serviceprincipalsigninactivity?view=graph-rest-1.0&tabs=http)
| Property                                        | Type                                             | Description                                                                                                                                     |
| :---------------------------------------------- | :----------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------- |
| appId                                           | String                                           | The globally unique **appId** (also called *client ID* on the Microsoft Entra admin center) of the credentialed resource application.                                                                                                             |
| applicationAuthenticationClientSignInActivity   | signInActivity | The sign-in activity of the application in a app-only authentication flow (app-to-app tokens) where the application acts like a client.              |
| applicationAuthenticationResourceSignInActivity | signInActivity | The sign-in activity of the application in a app-only authentication flow (app-to-app tokens) where the application acts like a resource.            |
| delegatedClientSignInActivity                   | signInActivity | The sign-in activity of the application in a delegated flow (user sign-in) where the application acts like a client.                       |
| delegatedResourceSignInActivity                 | signInActivity | The sign-in activity of the application in a delegated flow (user sign-in) where the application acts like a resource.                     |
| id                                              | String                                           | The unique ID for each service principal sign-in event.                                                                                         |
| lastSignInActivity                              | signInActivity | The most recent sign-in activity of the application across delegated or app-only flows where the application is used either as a client or resource. |
### [signIn ](https://docs.microsoft.com/graph/api/resources/signin?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|appDisplayName|String|App name displayed in the Microsoft Entra admin center. <br/><br/> Supports `$filter` (`eq`, `startsWith`).|
|appId|String|Unique GUID that represents the app ID in the Microsoft Entra ID. <br/><br/> Supports `$filter` (`eq`).|
|appliedConditionalAccessPolicies|appliedConditionalAccessPolicy collection|Provides a list of conditional access policies that the corresponding sign-in activity triggers. Apps need more Conditional Access-related privileges to read the details of this property. For more information, see Viewing applied conditional access (CA) policies in sign-ins.|
|clientAppUsed|String|Identifies the client used for the sign-in activity. Modern authentication clients include `Browser`, `modern clients`. Legacy authentication clients include `Exchange ActiveSync`, `IMAP`, `MAPI`, `SMTP`, `POP`, and `other clients`. <br/><br/> Supports `$filter` (`eq`).|
|conditionalAccessStatus|conditionalAccessStatus| Reports status of an activated conditional access policy. Possible values are: `success`, `failure`, `notApplied`, and `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`).|
|correlationId|String|The request ID sent from the client when the sign-in is initiated. Used to troubleshoot sign-in activity. <br/><br/> Supports `$filter` (`eq`).|
|createdDateTime|DateTimeOffset|Date and time (UTC) the sign-in was initiated. Example: midnight on Jan 1, 2014 is reported as `2014-01-01T00:00:00Z`. <br/><br/> Supports `$orderby`, `$filter` (`eq`, `le`, and `ge`).|
|deviceDetail|deviceDetail|Device information from where the sign-in occurred; includes device ID, operating system, and browser. <br/><br/> Supports `$filter` (`eq`, `startsWith`) on **browser** and **operatingSytem** properties. |
|id|String|Unique ID representing the sign-in activity. <br/><br/> Supports `$filter` (`eq`).|
|ipAddress|String|IP address of the client used to sign in. <br/><br/> Supports `$filter` (`eq`, `startsWith`).|
|isInteractive|Boolean|Indicates whether a sign-in is interactive.|
|location|signInLocation|Provides the city, state, and country code where the sign-in originated. <br/><br/> Supports `$filter` (`eq`, `startsWith`) on **city**, **state**, and **countryOrRegion** properties.|
|resourceDisplayName|String|Name of the resource the user signed into. <br/><br/> Supports `$filter` (`eq`).|
|resourceId|String|ID of the resource that the user signed into. <br/><br/> Supports `$filter` (`eq`).|
|riskDetail|riskDetail|The reason behind a specific state of a risky user, sign-in, or a risk event. The possible values are `none`, `adminGeneratedTemporaryPassword`, `userPerformedSecuredPasswordChange`, `userPerformedSecuredPasswordReset`, `adminConfirmedSigninSafe`, `aiConfirmedSigninSafe`, `userPassedMFADrivenByRiskBasedPolicy`, `adminDismissedAllRiskForUser`, `adminConfirmedSigninCompromised`, `hidden`, `adminConfirmedUserCompromised`, `unknownFutureValue`, `adminConfirmedServicePrincipalCompromised`, `adminDismissedAllRiskForServicePrincipal`, `m365DAdminDismissedDetection`, `userChangedPasswordOnPremises`, `adminDismissedRiskForSignIn`, `adminConfirmedAccountSafe`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value or values in this evolvable enum: `adminConfirmedServicePrincipalCompromised`, `adminDismissedAllRiskForServicePrincipal`, `m365DAdminDismissedDetection`, `userChangedPasswordOnPremises`, `adminDismissedRiskForSignIn`, `adminConfirmedAccountSafe`.The value `none` means that Microsoft Entra risk detection did not flag the user or the sign-in as a risky event so far. <br/><br/> Supports `$filter` (`eq`).<br> **Note:** Details for this property are only available for Microsoft Entra ID P2 customers. All other customers are returned `hidden`.|
|riskEventTypes_v2|String collection|The list of risk event types associated with the sign-in. Possible values: `unlikelyTravel`, `anonymizedIPAddress`, `maliciousIPAddress`, `unfamiliarFeatures`, `malwareInfectedIPAddress`, `suspiciousIPAddress`, `leakedCredentials`, `investigationsThreatIntelligence`, `generic`, or `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`, `startsWith`).|
|riskLevelAggregated|riskLevel|Aggregated risk level. The possible values are: `none`, `low`, `medium`, `high`, `hidden`, and `unknownFutureValue`. The value `hidden` means the user or sign-in wasn't enabled for Microsoft Entra ID Protection. <br/><br/> Supports `$filter` (`eq`). <br> **Note:** Details for this property are only available for Microsoft Entra ID P2 customers. All other customers are returned `hidden`.|
|riskLevelDuringSignIn|riskLevel|Risk level during sign-in. The possible values are: `none`, `low`, `medium`, `high`, `hidden`, and `unknownFutureValue`. The value `hidden` means the user or sign-in wasn't enabled for Microsoft Entra ID Protection. <br/><br/> Supports `$filter` (`eq`). <br>**Note:** Details for this property are only available for Microsoft Entra ID P2 customers. All other customers are returned `hidden`.|
|riskState|riskState|Reports status of the risky user, sign-in, or a risk event. The possible values are: `none`, `confirmedSafe`, `remediated`, `dismissed`, `atRisk`, `confirmedCompromised`, `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`).|
|status|signInStatus|Sign-in status. Includes the error code and description of the error (if a sign-in failure occurs). <br/><br/> Supports `$filter` (`eq`) on **errorCode** property.|
|userDisplayName|String|Display name of the user that initiated the sign-in. <br/><br/> Supports `$filter` (`eq`, `startsWith`).|
|userId|String|ID of the user that initiated the sign-in. <br/><br/> Supports `$filter` (`eq`).|
|userPrincipalName|String|User principal name of the user that initiated the sign-in. This value is always in lowercase. For guest users whose values in the user object typically contain `#EXT#` before the domain part, this property stores the value in both lowercase and the "true" format. For example, while the user object stores `AdeleVance_fabrikam.com#EXT#@contoso.com`, the sign-in logs store `adelevance@fabrikam.com`.<br/><br/> Supports `$filter` (`eq`, `startsWith`).|
### [userRegistrationDetails ](https://docs.microsoft.com/graph/api/resources/userregistrationdetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|User object identifier in Microsoft Entra ID. Inherited from entity.|
|isAdmin|Boolean|Indicates whether the user has an admin role in the tenant. This value can be used to check the authentication methods that privileged accounts are registered for and capable of.|
|isMfaCapable|Boolean|Indicates whether the user has registered a strong authentication method for multifactor authentication. The method must be allowed by the authentication methods policy. Supports `$filter` (`eq`).|
|isMfaRegistered|Boolean|Indicates whether the user has registered a strong authentication method for multifactor authentication. The method may not necessarily be allowed by the authentication methods policy. Supports `$filter` (`eq`).|
|isPasswordlessCapable|Boolean|Indicates whether the user has registered a passwordless strong authentication method (including FIDO2, Windows Hello for Business, and Microsoft Authenticator (Passwordless)) that is allowed by the authentication methods policy. Supports `$filter` (`eq`).|
|isSsprCapable|Boolean|Indicates whether the user has registered the required number of authentication methods for self-service password reset and the user is allowed to perform self-service password reset by policy. Supports `$filter` (`eq`).|
|isSsprEnabled|Boolean|Indicates whether the user is allowed to perform self-service password reset by policy. The user may not necessarily have registered the required number of authentication methods for self-service password reset. Supports `$filter` (`eq`).|
|isSsprRegistered|Boolean|Indicates whether the user has registered the required number of authentication methods for self-service password reset. The user may not necessarily be allowed to perform self-service password reset by policy. Supports `$filter` (`eq`).|
|isSystemPreferredAuthenticationMethodEnabled|Boolean|Indicates whether system preferred authentication method is enabled. If enabled, the system dynamically determines the most secure authentication method among the methods registered by the user. Supports `$filter` (`eq`).|
|lastUpdatedDateTime|DateTimeOffset|The date and time (UTC) when the report was last updated. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|methodsRegistered|String collection|Collection of authentication methods registered, such as `mobilePhone`, `email`, `passKeyDeviceBound`. Supports `$filter` (`any` with `eq`).|
|systemPreferredAuthenticationMethods|String collection| Collection of authentication methods that the system determined to be the most secure authentication methods among the registered methods for second factor authentication. Possible values are: `push`, `oath`, `voiceMobile`, `voiceAlternateMobile`, `voiceOffice`, `sms`, `none`, `unknownFutureValue`. Supports `$filter` (`any` with `eq`).|
|userDisplayName|String| The user display name, such as `Adele Vance`. Supports `$filter` (`eq`, `startsWith`) and `$orderby`.|
|userPreferredMethodForSecondaryAuthentication|userDefaultAuthenticationMethod|The method the user selected as the default second-factor for performing multifactor authentication. Possible values are: `push`, `oath`, `voiceMobile`, `voiceAlternateMobile`, `voiceOffice`, `sms`, `none`, `unknownFutureValue`. This property is used as preferred MFA method when **isSystemPreferredAuthenticationMethodEnabled** is `false`. Supports `$filter` (`any` with `eq`).|
|userPrincipalName|String|The user principal name, such as `AdeleV@contoso.com`. Supports `$filter` (`eq`, `startsWith`) and `$orderby`.|
|userType|signInUserType|Identifies whether the user is a member or guest in the tenant. The possible values are: `member`, `guest`, `unknownFutureValue`.|
### [userRegistrationFeatureSummary ](https://docs.microsoft.com/graph/api/resources/userregistrationfeaturesummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|totalUserCount|Int64|Total number of users accounts, excluding those that are blocked.|
|userRegistrationFeatureCounts|userRegistrationFeatureCount collection|Number of users registered or capable for multi-factor authentication, self-service password reset, and passwordless authentication.|
|userRoles|includedUserRoles|The role type of the user. Possible values are: `all`, `privilegedAdmin`, `admin`, `user`, `unknownFutureValue`.|
|userTypes|includedUserTypes|User type. Possible values are: `all`, `member`, `guest`, `unknownFutureValue`.|
### [userRegistrationMethodSummary ](https://docs.microsoft.com/graph/api/resources/userregistrationmethodsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|totalUserCount|Int64|Total number of users in the tenant.|
|userRegistrationMethodCounts|userRegistrationMethodCount collection|Number of users registered for each authentication method.|
|userRoles|includedUserRoles|The role type of the user. Possible values are: `all`, `privilegedAdmin`, `admin`, `user`, `unknownFutureValue`.|
|userTypes|includedUserTypes|User type. Possible values are: `all`, `member`, `guest`, `unknownFutureValue`.|
