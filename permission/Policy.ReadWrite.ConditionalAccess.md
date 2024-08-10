# Policy.ReadWrite.ConditionalAccess

> Allows the app to read and write your organization's conditional access policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-delete-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/conditionalAccess/namedLocations/{id}](https://docs.microsoft.com/graph/api/ipnamedlocation-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/conditionalAccess/policies/{id}](https://docs.microsoft.com/graph/api/conditionalaccesspolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}](https://docs.microsoft.com/graph/api/authenticationstrengthroot-delete-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationContextClassReferences](https://docs.microsoft.com/graph/api/conditionalaccessroot-list-authenticationcontextclassreferences?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/authenticationMethodModes](https://docs.microsoft.com/graph/api/authenticationstrengthroot-list-authenticationmethodmodes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/authenticationMethodModes/{authenticationMethodModeDetailId}](https://docs.microsoft.com/graph/api/authenticationmethodmodedetail-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-list-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationcombinationconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationStrengthPolicies](https://docs.microsoft.com/graph/api/authenticationstrengthroot-list-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}/usage](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-usage?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /policies/authenticationStrengthPolicies/findByMethodMode(authenticationMethodModes={authenticationMethodMode})](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-findbymethodmode?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/conditionalAccessPolicyCoverages](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-conditionalaccesspolicycoverages?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/conditionalAccessPolicyCoverages/{conditionalAccessPolicyCoverageId}](https://docs.microsoft.com/graph/api/managedtenants-conditionalaccesspolicycoverage-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/authenticationContextClassReferences/{id}](https://docs.microsoft.com/graph/api/authenticationcontextclassreference-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationcombinationconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/namedLocations/{id}](https://docs.microsoft.com/graph/api/ipnamedlocation-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/policies/{id}](https://docs.microsoft.com/graph/api/conditionalaccesspolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /identity/continuousAccessEvaluationPolicy](https://docs.microsoft.com/graph/api/continuousaccessevaluationpolicy-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/identitySecurityDefaultsEnforcementPolicy](https://docs.microsoft.com/graph/api/identitysecuritydefaultsenforcementpolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /identity/conditionalAccess/authenticationContextClassReferences](https://docs.microsoft.com/graph/api/conditionalaccessroot-post-authenticationcontextclassreferences?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-post-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/conditionalAccess/namedLocations](https://docs.microsoft.com/graph/api/conditionalaccessroot-post-namedlocations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/conditionalAccess/policies](https://docs.microsoft.com/graph/api/conditionalaccessroot-post-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/authenticationStrengthPolicies](https://docs.microsoft.com/graph/api/authenticationstrengthroot-post-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/authenticationStrengthPolicies/{authenticationStrengthPolicyId}/updateAllowedCombinations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-updateallowedcombinations?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ad902697-1014-4ef5-81ef-2b4301988e8c|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's conditional access policies|
|**Description**|Allows the app to read and write your organization's conditional access policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|01c0a623-fc9b-48e9-b794-0756f8e8f067|
|**Display String**|Read and write your organization's conditional access policies|
|**Description**|Allows the app to read and write your organization's conditional access policies, without a signed-in user.|
## Resources
### [authenticationCombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/authenticationcombinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appliesToCombinations|authenticationMethodModes collection|Which authentication method combinations this configuration applies to. Must be an **allowedCombinations** object, part of the authenticationStrengthPolicy. The only possible value for `fido2combinationConfigurations` is `"fido2"`.|
|id|String|A unique system-generated identifier.|
### [authenticationContextClassReference ](https://docs.microsoft.com/graph/api/resources/authenticationcontextclassreference?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String| A short explanation of the policies that are enforced by authenticationContextClassReference. This value should be used to provide secondary text to describe the authentication context class reference when building user-facing admin experiences. For example, a selection UX.|
|displayName|String| The display name is the friendly name of the authenticationContextClassReference object. This value should be used to identify the authentication context class reference when building user-facing admin experiences. For example, a selection UX.|
|id|String| Identifier used to reference the authentication context class. The ID is used to trigger step-up authentication for the referenced authentication requirements and is the value that will be issued in the `acrs` claim of an access token. This value in the claim is used to verify that the required authentication context has been satisfied. The allowed values are `c1` through `c25`. <br/> Supports `$filter` (`eq`).|
|isAvailable|Boolean| Indicates whether the authenticationContextClassReference has been published by the security admin and is ready for use by apps. When it's set to `false`, it shouldn't be shown in authentication context selection UX, or used to protect app resources. It's shown and available for Conditional Access policy authoring. The default value is `false`. <br/> Supports `$filter` (`eq`). |
### [authenticationMethodModeDetail ](https://docs.microsoft.com/graph/api/resources/authenticationmethodmodedetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationMethod|baseAuthenticationMethod|The authentication method that this mode modifies. The possible values are: `password`, `voice`, `hardwareOath`, `softwareOath`, `sms`, `fido2`, `windowsHelloForBusiness`, `microsoftAuthenticator`, `temporaryAccessPass`, `email`, `x509Certificate`, `federation`, `unknownFutureValue`.|
|displayName|String|The display name of this mode|
|id|String|The system-generated identifier for this mode. |
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
### [compliantNetworkNamedLocation ](https://docs.microsoft.com/graph/api/resources/compliantnetworknamedlocation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|compliantNetworkType|compliantNetworkType|Type of compliant network. Currently the only possible value is `allTenantCompliantNetworks`.|
|createdDateTime|DateTimeOffset|The timestamp type represents creation date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from namedLocation.|
|displayName|String|Human-readable name of the location. Required. Always "All Compliant Network Locations". Inherited from namedLocation.|
|id|String|Identifier of the object. Read-only. Inherited from entity.|
|isTrusted|Boolean|`true` if this location is explicitly trusted. Optional. Default value is `false`.|
|modifiedDateTime|DateTimeOffset|The timestamp type represents last modified date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from namedLocation.|
### [conditionalAccessApplications ](https://docs.microsoft.com/graph/api/resources/conditionalaccessapplications?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| excludeApplications | String collection | Can be one of the following: <li> The list of client IDs (**appId**) explicitly excluded from the policy.<li> `Office365` - For the list of apps included in `Office365`, see Apps included in Conditional Access Office 365 app suite <li> `MicrosoftAdminPortals` - For more information, see Conditional Access Target resources: Microsoft Admin Portals|
| includeApplications | String collection | Can be one of the following: <li> The list of client IDs (**appId**) the policy applies to, unless explicitly excluded (in **excludeApplications**) <li> `All` <li> `Office365` - For the list of apps included in `Office365`, see Apps included in Conditional Access Office 365 app suite <li> `MicrosoftAdminPortals` - For more information, see Conditional Access Target resources: Microsoft Admin Portals |
| includeUserActions | String collection | User actions to include. Supported values are `urn:user:registersecurityinfo` and `urn:user:registerdevice` |
### [conditionalAccessGrantControls ](https://docs.microsoft.com/graph/api/resources/conditionalaccessgrantcontrols?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-------- |:---- |:----------- |
| builtInControls | conditionalAccessGrantControl collection | List of values of built-in controls required by the policy. Possible values: `block`, `mfa`, `compliantDevice`, `domainJoinedDevice`, `approvedApplication`, `compliantApplication`, `passwordChange`, `unknownFutureValue`. |
| customAuthenticationFactors | String collection | List of custom controls IDs required by the policy. For more information, see Custom controls. |
| operator | String | Defines the relationship of the grant controls. Possible values: `AND`, `OR`. |
| termsOfUse | String collection | List of terms of use IDs required by the policy. |
### [conditionalAccessPolicy ](https://docs.microsoft.com/graph/api/resources/conditionalaccesspolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|conditions|conditionalAccessConditionSet| Specifies the rules that must be met for the policy to apply. Required. |
|createdDateTime|DateTimeOffset| The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Readonly. |
|displayName|String| Specifies a display name for the conditionalAccessPolicy object. |
|grantControls|conditionalAccessGrantControls| Specifies the grant controls that must be fulfilled to pass the policy. |
|id|String| Specifies the identifier of a conditionalAccessPolicy object. Read-only.|
|modifiedDateTime| DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Readonly. |
|sessionControls|conditionalAccessSessionControls| Specifies the session controls that are enforced after sign-in. |
|state|conditionalAccessPolicyState| Specifies the state of the conditionalAccessPolicy object. Possible values are: `enabled`, `disabled`, `enabledForReportingButNotEnforced`. Required. |
### [conditionalAccessSessionControls ](https://docs.microsoft.com/graph/api/resources/conditionalaccesssessioncontrols?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|applicationEnforcedRestrictions|applicationEnforcedRestrictionsSessionControl| Session control to enforce application restrictions. Only Exchange Online and Sharepoint Online support this session control. |
|cloudAppSecurity|cloudAppSecuritySessionControl| Session control to apply cloud app security.|
|disableResilienceDefaults|Boolean| Session control that determines whether it is acceptable for Microsoft Entra ID to extend existing sessions based on information collected prior to an outage or not.|
|persistentBrowser|persistentBrowserSessionControl| Session control to define whether to persist cookies or not. All apps should be selected for this session control to work correctly. |
|signInFrequency|signInFrequencySessionControl| Session control to enforce signin frequency.|
### [conditionalAccessUsers ](https://docs.microsoft.com/graph/api/resources/conditionalaccessusers?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| excludeGroups | String collection | Group IDs excluded from scope of policy. |
| excludeGuestsOrExternalUsers | conditionalAccessGuestsOrExternalUsers | Internal guests or external users excluded from the policy scope. Optionally populated. |
| excludeRoles | String collection | Role IDs excluded from scope of policy. |
| excludeUsers | String collection | User IDs excluded from scope of policy and/or `GuestsOrExternalUsers`. |
| includeGroups | String collection | Group IDs in scope of policy unless explicitly excluded. |
| includeGuestsOrExternalUsers | conditionalAccessGuestsOrExternalUsers | Internal guests or external users included in the policy scope. Optionally populated. |
| includeRoles | String collection | Role IDs in scope of policy unless explicitly excluded. |
| includeUsers | String collection | User IDs in scope of policy unless explicitly excluded, `None`, `All`, or `GuestsOrExternalUsers`. |
### [continuousAccessEvaluationPolicy ](https://docs.microsoft.com/graph/api/resources/continuousaccessevaluationpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Continuous access evaluation automatically blocks access to resources and applications in near real time when a user's access is removed or a client IP address changes. Read-only.|
|displayName|String| The value is always `Continuous Access Evaluation`. Read-only.|
|groups|String collection|The collection of group identifiers in scope for evaluation. All groups are in scope when the collection is empty. Read-only.|
|id|String|Specifies the identifier of a continuousAccessEvaluationPolicy object. Read-only.|
|isEnabled|Boolean| `true` to indicate whether continuous access evaluation should be performed; otherwise `false`. Read-only.|
|users|String collection|The collection of user identifiers in scope for evaluation. All users are in scope when the collection is empty. Read-only.|
|migrate|Boolean| `true` to indicate that the continuous access evaluation policy settings should be or has been migrated to the conditional access policy. |
### [countryNamedLocation ](https://docs.microsoft.com/graph/api/resources/countrynamedlocation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|countriesAndRegions|String collection|List of countries and/or regions in two-letter format specified by ISO 3166-2. Required.|
|countryLookupMethod|countryLookupMethodType|Determines what method is used to decide which country the user is located in. Possible values are `clientIpAddress`(default) and `authenticatorAppGps`. Note: `authenticatorAppGps` is not yet supported in the Microsoft Cloud for US Government.|
|createdDateTime|DateTimeOffset|The Timestamp type represents creation date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from namedLocation.|
|displayName|String|Human-readable name of the location. Required. Inherited from namedLocation.|
|id|String|Identifier of a namedLocation object. Read-only. Inherited from namedLocation.|
|includeUnknownCountriesAndRegions|Boolean|`true` if IP addresses that don't map to a country or region should be included in the named location. Optional. Default value is `false`.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents last modified date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from namedLocation.|
### [fido2CombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/fido2combinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAAGUIDs|String collection|A list of AAGUIDs allowed to be used as part of the specified authentication method combinations.|
|appliesToCombinations|authenticationMethodModes collection|Which authentication method combinations this configuration applies to. The only possible value is `"fido2"`. Inherited from authenticationCombinationConfiguration.|
|id|String|A system-generated identifier. Inherited from entity.|
### [identitySecurityDefaultsEnforcementPolicy ](https://docs.microsoft.com/graph/api/resources/identitysecuritydefaultsenforcementpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String|Description for this policy. Read-only.|
|displayName|String|Display name for this policy. Read-only.|
|id|String|Identifier for this policy. Read-only.|
|isEnabled|Boolean|If set to `true`, Microsoft Entra security defaults are enabled for the tenant.|
### [ipNamedLocation ](https://docs.microsoft.com/graph/api/resources/ipnamedlocation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The Timestamp type represents creation date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from namedLocation.|
|displayName|String|Human-readable name of the location. Required.|
|id|String|Identifier of a namedLocation object. Read-only. Inherited from namedLocation.|
|ipRanges|ipRange collection|List of IP address ranges in IPv4 CIDR format (for example, 1.2.3.4/32) or any allowable IPv6 format from IETF RFC5969. Required.|
|isTrusted|Boolean|`true` if this location is explicitly trusted. Optional. Default value is `false`.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents last modified date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from namedLocation.|
### [ipRange ](https://docs.microsoft.com/graph/api/resources/iprange?view=graph-rest-1.0&tabs=http)

### [conditionalAccessPolicyCoverage ](https://docs.microsoft.com/graph/api/resources/managedtenants-conditionalaccesspolicycoverage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|conditionalAccessPolicyState|String|The state for the conditional access policy. Possible values are: `enabled`, `disabled`, `enabledForReportingButNotEnforced`. Required. Read-only.|
|id|String|The unique identifier for this entity. Required. Read-only.|
|latestPolicyModifiedDateTime|DateTimeOffset|The date and time the conditional access policy was last modified. Required. Read-only.|
|requiresDeviceCompliance|Boolean|A flag indicating whether the conditional access policy requires device compliance. Required. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Required. Read-only.|
### [namedLocation ](https://docs.microsoft.com/graph/api/resources/namedlocation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The Timestamp type represents creation date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|Human-readable name of the location.|
|id|String|Identifier of a namedLocation object. Read-only.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents last modified date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
### [updateAllowedCombinationsResult ](https://docs.microsoft.com/graph/api/resources/updateallowedcombinationsresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|additionalInformation|String|Information about why the updateAllowedCombinations action was successful or failed.|
|conditionalAccessReferences|String collection|References to existing Conditional Access policies that use this authentication strength.|
|currentCombinations|authenticationMethodModes collection|The list of current authentication method combinations allowed by the authentication strength.|
|previousCombinations|authenticationMethodModes collection|The list of former authentication method combinations allowed by the authentication strength before they were updated through the updateAllowedCombinations action.|
### [x509CertificateCombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/x509certificatecombinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedIssuerSkis|String collection|A list of allowed subject key identifier values.|
|allowedPolicyOIDs|String collection|A list of allowed policy OIDs.|
|appliesToCombinations|authenticationMethodModes collection| Which authentication method combinations this configuration applies to. The possible values for x509certificatecombinationconfiguration are `"x509CertificateSingleFactor"` or `"x509CertificateMultiFactor"`. Inherited from authenticationCombinationConfiguration.|
|id|String|A system-generated identifier. Inherited from entity.|
