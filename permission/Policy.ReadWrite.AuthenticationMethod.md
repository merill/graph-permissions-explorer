# Policy.ReadWrite.AuthenticationMethod

> Allows the app to read and write the authentication method policies, on behalf of the signed-in user. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-delete-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/email](https://docs.microsoft.com/graph/api/emailauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/fido2](https://docs.microsoft.com/graph/api/fido2authenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/hardwareOath](https://docs.microsoft.com/graph/api/hardwareoathauthenticationmethodconfiguration-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/microsoftAuthenticator](https://docs.microsoft.com/graph/api/microsoftauthenticatorauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/sms](https://docs.microsoft.com/graph/api/smsauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/softwareOath](https://docs.microsoft.com/graph/api/softwareoathauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/temporaryAccessPass](https://docs.microsoft.com/graph/api/temporaryaccesspassauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/voice](https://docs.microsoft.com/graph/api/voiceauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/x509Certificate](https://docs.microsoft.com/graph/api/x509certificateauthenticationmethodconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}](https://docs.microsoft.com/graph/api/authenticationstrengthroot-delete-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/authenticationMethodModes](https://docs.microsoft.com/graph/api/authenticationstrengthroot-list-authenticationmethodmodes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/authenticationMethodModes/{authenticationMethodModeDetailId}](https://docs.microsoft.com/graph/api/authenticationmethodmodedetail-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-list-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationcombinationconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy](https://docs.microsoft.com/graph/api/authenticationmethodspolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/email](https://docs.microsoft.com/graph/api/emailauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/fido2](https://docs.microsoft.com/graph/api/fido2authenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/hardwareOath](https://docs.microsoft.com/graph/api/hardwareoathauthenticationmethodconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/microsoftAuthenticator](https://docs.microsoft.com/graph/api/microsoftauthenticatorauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/sms](https://docs.microsoft.com/graph/api/smsauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/softwareOath](https://docs.microsoft.com/graph/api/softwareoathauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/temporaryAccessPass](https://docs.microsoft.com/graph/api/temporaryaccesspassauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/voice](https://docs.microsoft.com/graph/api/voiceauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/x509Certificate](https://docs.microsoft.com/graph/api/x509certificateauthenticationmethodconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationStrengthPolicies](https://docs.microsoft.com/graph/api/authenticationstrengthroot-list-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}/usage](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-usage?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /policies/authenticationStrengthPolicies/findByMethodMode(authenticationMethodModes={authenticationMethodMode})](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-findbymethodmode?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationcombinationconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy](https://docs.microsoft.com/graph/api/authenticationmethodspolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/email](https://docs.microsoft.com/graph/api/emailauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/fido2](https://docs.microsoft.com/graph/api/fido2authenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/hardwareOath](https://docs.microsoft.com/graph/api/hardwareoathauthenticationmethodconfiguration-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/microsoftAuthenticator](https://docs.microsoft.com/graph/api/microsoftauthenticatorauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/sms](https://docs.microsoft.com/graph/api/smsauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/softwareOath](https://docs.microsoft.com/graph/api/softwareoathauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/TemporaryAccessPass](https://docs.microsoft.com/graph/api/temporaryaccesspassauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/voice](https://docs.microsoft.com/graph/api/voiceauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationMethodsPolicy/authenticationMethodConfigurations/x509Certificate](https://docs.microsoft.com/graph/api/x509certificateauthenticationmethodconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /policies/b2cAuthenticationMethodsPolicy](https://docs.microsoft.com/graph/api/b2cauthenticationmethodspolicy-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-post-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/authenticationStrengthPolicies](https://docs.microsoft.com/graph/api/authenticationstrengthroot-post-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}/updateAllowedCombinations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-updateallowedcombinations?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7e823077-d88e-468f-a337-e18f1f0e6c7c|
|**Consent Type**|Admin|
|**Display String**|Read and write authentication method policies|
|**Description**|Allows the app to read and write the authentication method policies, on behalf of the signed-in user. |
## Application Permission
|||
|-|-|
|**Id**|29c18626-4985-4dcd-85c0-193eef327366|
|**Display String**|Read and write all authentication method policies |
|**Description**|Allows the app to read and write all authentication method policies for the tenant, without a signed-in user. |
## Resources
### [authenticationCombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/authenticationcombinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appliesToCombinations|authenticationMethodModes collection|Which authentication method combinations this configuration applies to. Must be an **allowedCombinations** object, part of the authenticationStrengthPolicy. The only possible value for `fido2combinationConfigurations` is `"fido2"`.|
|id|String|A unique system-generated identifier.|
### [authenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/authenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from a policy.|
|id|String|The policy name.|
|state|authenticationMethodState|The state of the policy. Possible values are: `enabled`, `disabled`.|
### [authenticationMethodModeDetail ](https://docs.microsoft.com/graph/api/resources/authenticationmethodmodedetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationMethod|baseAuthenticationMethod|The authentication method that this mode modifies. The possible values are: `password`, `voice`, `hardwareOath`, `softwareOath`, `sms`, `fido2`, `windowsHelloForBusiness`, `microsoftAuthenticator`, `temporaryAccessPass`, `email`, `x509Certificate`, `federation`, `unknownFutureValue`.|
|displayName|String|The display name of this mode|
|id|String|The system-generated identifier for this mode. |
### [authenticationmethodspolicies-overview](https://docs.microsoft.com/graph/api/resources/authenticationmethodspolicies-overview?view=graph-rest-1.0&tabs=http)

### [authenticationMethodsPolicy ](https://docs.microsoft.com/graph/api/resources/authenticationmethodspolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|A description of the policy. Read-only.|
|displayName|String|The name of the policy. Read-only.|
|id|String|The identifier of the policy. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time of the last update to the policy. Read-only.|
|policyVersion|String|The version of the policy in use. Read-only.|
|registrationEnforcement|registrationEnforcement|Enforce registration at sign-in time. This property can be used to remind users to set up targeted authentication methods.|
|policyMigrationState|authenticationMethodsPolicyMigrationState|The state of migration of the authentication methods policy from the legacy multifactor authentication and self-service password reset (SSPR) policies. The possible values are: <br/><li>`premigration` - means the authentication methods policy is used for authentication only, legacy policies are respected. <li>`migrationInProgress` - means the authentication methods policy is used for both authentication and SSPR, legacy policies are respected. <li>`migrationComplete` - means the authentication methods policy is used for authentication and SSPR, legacy policies are ignored. <li>`unknownFutureValue` - Evolvable enumeration sentinel value. Do not use. |
### [authenticationMethodTarget ](https://docs.microsoft.com/graph/api/resources/authenticationmethodtarget?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Object Id of a Microsoft Entra user or group.|
|isRegistrationRequired|Boolean|Determines if the user is enforced to register the authentication method.|
|targetType|authenticationMethodTargetType|Possible values are: `user`, `group`.|
### [authenticationStrengthPolicy ](https://docs.microsoft.com/graph/api/resources/authenticationstrengthpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedCombinations|authenticationMethodModes collection|A collection of authentication method modes that are required be used to satify this authentication strength.|
|createdDateTime|DateTimeOffset|The datetime when this policy was created.|
|description|String|The human-readable description of this policy.|
|displayName|String|The human-readable display name of this policy. <br><br>Supports `$filter` (`eq`, `ne`, `not` , and `in`). |
|id|String|The system-generated identifier for this mode.|
|modifiedDateTime|DateTimeOffset|The datetime when this policy was last modified.|
|policyType|authenticationStrengthPolicyType|A descriptor of whether this policy is built into Microsoft Entra ID or created by an admin for the tenant. The possible values are: `builtIn`, `custom`, `unknownFutureValue`. <br><br>Supports `$filter` (`eq`, `ne`, `not` , and `in`). |
|requirementsSatisfied|authenticationStrengthRequirements|A descriptor of whether this authentication strength grants the MFA claim upon successful satisfaction. The possible values are: `none`, `mfa`, `unknownFutureValue`.|
### [authenticationStrengthUsage ](https://docs.microsoft.com/graph/api/resources/authenticationstrengthusage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|mfa|conditionalAccessPolicy collection|A collection of Conditional Access policies that reference the specified authentication strength policy and that require an MFA claim.|
|none|conditionalAccessPolicy collection|A collection of Conditional Access policies that reference the specified authentication strength policy and that do not require an MFA claim.|
### [b2cAuthenticationMethodsPolicy ](https://docs.microsoft.com/graph/api/resources/b2cauthenticationmethodspolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String|The ID of the B2C authentication methods policy. This is a read only property and the key.|
|isEmailPasswordAuthenticationEnabled|Boolean|The tenant admin can configure local accounts using email if the email and password authentication method is enabled.|
|isUserNameAuthenticationEnabled|Boolean|The tenant admin can configure local accounts using username if the username and password authentication method is enabled.|
|isPhoneOneTimePasswordAuthenticationEnabled|Boolean|The tenant admin can configure local accounts using phone number if the phone number and one-time password authentication method is enabled.|
### [emailAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/emailauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowExternalIdToUseEmailOtp|externalEmailOtpState|Determines whether email OTP is usable by external users for authentication. Possible values are: `default`, `enabled`, `disabled`, `unknownFutureValue`. Tenants in the `default` state who didn't use public preview have email OTP enabled beginning in October 2021.|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier. Inherited from authenticationMethodConfiguration.|
|state|authenticationMethodState|Indicates whether this authentication method is enabled or not. Possible values are: `enabled`, `disabled`.|
### [excludeTarget ](https://docs.microsoft.com/graph/api/resources/excludetarget?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The object identifier of a Microsoft Entra user or group.|
|targetType|authenticationMethodTargetType|The type of the authentication method target. Possible values are: `user`, `group`, `unknownFutureValue`.|
### [fido2AuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/fido2authenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier.|
|isAttestationEnforced|Boolean|Determines whether attestation must be enforced for FIDO2 security key registration.|
|isSelfServiceRegistrationAllowed|Boolean|Determines if users can register new FIDO2 security keys.|
|keyRestrictions|fido2KeyRestrictions|Controls whether key restrictions are enforced on FIDO2 security keys, either allowing or disallowing certain key types as defined by Authenticator Attestation GUID (AAGUID), an identifier that indicates the type (e.g. make and model) of the authenticator.|
|state|authenticationMethodState|Possible values are: `enabled`, `disabled`.|
### [fido2CombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/fido2combinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAAGUIDs|String collection|A list of AAGUIDs allowed to be used as part of the specified authentication method combinations.|
|appliesToCombinations|authenticationMethodModes collection|Which authentication method combinations this configuration applies to. The only possible value is `"fido2"`. Inherited from authenticationCombinationConfiguration.|
|id|String|A system-generated identifier. Inherited from entity.|
### [hardwareOathAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/hardwareoathauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy. Inherited from authenticationMethodConfiguration.|
|id|String|The authentication method policy identifier. Inherited from entity.|
|state|authenticationMethodState|Possible values are: `enabled`, `disabled`. Inherited from authenticationMethodConfiguration.|
### [microsoftAuthenticatorAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/microsoftauthenticatorauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier.|
|featureSettings|microsoftAuthenticatorFeatureSettings|A collection of Microsoft Authenticator settings such as application context and location context, and whether they are enabled for all users or specific users only.|
|state|authenticationMethodState|Possible values are: `enabled`, `disabled`.|
### [registrationEnforcement ](https://docs.microsoft.com/graph/api/resources/registrationenforcement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationMethodsRegistrationCampaign|authenticationMethodsRegistrationCampaign|Run campaigns to remind users to set up targeted authentication methods.|
### [reportSuspiciousActivitySettings ](https://docs.microsoft.com/graph/api/resources/reportsuspiciousactivitysettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|includeTarget|includeTarget|Group IDs in scope for report suspicious activity.|
|state|advancedConfigState|Specifies the state of the reportSuspiciousActivitySettings object. The possible values are: `default`, `enabled`, `disabled`, `unknownFutureValue`. Setting to `default` results in a disabled state.|
|voiceReportingCode|Int32|Specifies the number the user enters on their phone to report the MFA prompt as suspicious.|
### [smsAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/smsauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier.|
|state|authenticationMethodState|Possible values are: `enabled`, `disabled`.|
### [softwareOathAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/softwareoathauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier.|
|state|authenticationMethodState|Represents whether users can register this authentication method. The possible values are: `enabled`, `disabled`.|
### [systemCredentialPreferences ](https://docs.microsoft.com/graph/api/resources/systemcredentialpreferences?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Users and groups excluded from the preferred authentication method experience of the system.|
|includeTargets|includeTarget collection|Users and groups included in the preferred authentication method experience of the system.|
|state|advancedConfigState|Indicates whether the feature is enabled or disabled. Possible values are: `default`, `enabled`, `disabled`, `unknownFutureValue`. The `default` value is used when the configuration hasn't been explicitly set, and uses the default behavior of Microsoft Entra ID for the setting. The default value is `disabled`.|
### [temporaryAccessPassAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/temporaryaccesspassauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|defaultLength|Int|Default length in characters of a Temporary Access Pass object. Must be between 8 and 48 characters.|
|defaultLifetimeInMinutes|Int|Default lifetime in minutes for a Temporary Access Pass. Value can be any integer between the **minimumLifetimeInMinutes** and **maximumLifetimeInMinutes**.|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The identifier of the authentication method policy. Inherited from entity.|
|isUsableOnce|Boolean    |If `true`, all the passes in the tenant will be restricted to one-time use. If `false`, passes in the tenant can be created to be either one-time use or reusable.|
|maximumLifetimeInMinutes|Int|Maximum lifetime in minutes for any Temporary Access Pass created in the tenant. Value can be between 10 and 43200 minutes (equivalent to 30 days).|
|minimumLifetimeInMinutes|Int|Minimum lifetime in minutes for any Temporary Access Pass created in the tenant. Value can be between 10 and 43200 minutes (equivalent to 30 days).|
|state|authenticationMethodState|Whether the Temporary Access Pass method is enabled in the tenant. Possible values are: `enabled`, `disabled`. Inherited from authenticationMethodConfiguration. |
### [updateAllowedCombinationsResult ](https://docs.microsoft.com/graph/api/resources/updateallowedcombinationsresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|additionalInformation|String|Information about why the updateAllowedCombinations action was successful or failed.|
|conditionalAccessReferences|String collection|References to existing Conditional Access policies that use this authentication strength.|
|currentCombinations|authenticationMethodModes collection|The list of current authentication method combinations allowed by the authentication strength.|
|previousCombinations|authenticationMethodModes collection|The list of former authentication method combinations allowed by the authentication strength before they were updated through the updateAllowedCombinations action.|
### [voiceAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/voiceauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier.|
|isOfficePhoneAllowed|Boolean|`true` if users can register office phones, otherwise, `false`. |
|state|authenticationMethodState|Represents whether users can register this authentication method. The possible values are: `enabled`, `disabled`.|
### [x509CertificateAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/x509certificateauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationModeConfiguration|x509CertificateAuthenticationModeConfiguration|Defines strong authentication configurations. This configuration includes the default authentication mode and the different rules for strong authentication bindings. |
|certificateUserBindings|x509CertificateUserBinding collection|Defines fields in the X.509 certificate that map to attributes of the Microsoft Entra user object in order to bind the certificate to the user. The **priority** of the object determines the order in which the binding is carried out. The first binding that matches will be used and the rest ignored. |
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The identifier for the authentication method policy. The value is always `X509Certificate`. Inherited from
|state|authenticationMethodState|The possible values are: `enabled`, `disabled`. Inherited from authenticationMethodConfiguration.|
### [x509CertificateAuthenticationModeConfiguration ](https://docs.microsoft.com/graph/api/resources/x509certificateauthenticationmodeconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|rules|x509CertificateRule collection| Rules are configured in addition to the authentication mode to bind a specific **x509CertificateRuleType** to an **x509CertificateAuthenticationMode**. For example, bind the `policyOID` with identifier `1.32.132.343` to `x509CertificateMultiFactor` authentication mode.|
|x509CertificateAuthenticationDefaultMode|x509CertificateAuthenticationMode| The type of strong authentication mode. The possible values are: `x509CertificateSingleFactor`, `x509CertificateMultiFactor`, `unknownFutureValue`.|
### [x509CertificateCombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/x509certificatecombinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedIssuerSkis|String collection|A list of allowed subject key identifier values.|
|allowedPolicyOIDs|String collection|A list of allowed policy OIDs.|
|appliesToCombinations|authenticationMethodModes collection| Which authentication method combinations this configuration applies to. The possible values for x509certificatecombinationconfiguration are `"x509CertificateSingleFactor"` or `"x509CertificateMultiFactor"`. Inherited from authenticationCombinationConfiguration.|
|id|String|A system-generated identifier. Inherited from entity.|
### [x509CertificateIssuerHintsConfiguration ](https://docs.microsoft.com/graph/api/resources/x509certificateissuerhintsconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|state|x509CertificateIssuerHintsState|The possible values are: `disabled`, `enabled`, `unknownFutureValue`.|
### [x509CertificateUserBinding ](https://docs.microsoft.com/graph/api/resources/x509certificateuserbinding?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|priority|Int32|The priority of the binding. Microsoft Entra ID uses the binding with the highest priority. This value must be a non-negative integer and unique in the collection of objects in the **certificateUserBindings** property of an **x509CertificateAuthenticationMethodConfiguration** object. Required|
|userProperty|String|Defines the Microsoft Entra user property of the user object to use for the binding. The possible values are: `userPrincipalName`, `onPremisesUserPrincipalName`, `certificateUserIds`. Required.|
|x509CertificateField|String|The field on the X.509 certificate to use for the binding. The possible values are: `PrincipalName`, `RFC822Name`, `SubjectKeyIdentifier`, `SHA1PublicKey`. |
