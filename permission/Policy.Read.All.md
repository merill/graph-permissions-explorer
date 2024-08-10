# Policy.Read.All

> Allows the app to read your organization's policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[](https://docs.microsoft.com/graph/api/application-delete-tokenlifetimepolicies?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /applications(appId='{appId}')/tokenIssuancePolicies/{id}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications(appId='{appId}')/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{applicationObjectId}/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{id}/tokenIssuancePolicies/{id}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/conditionalAccess/namedLocations/{id}](https://docs.microsoft.com/graph/api/ipnamedlocation-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/conditionalAccess/policies/{id}](https://docs.microsoft.com/graph/api/conditionalaccesspolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/claimsMappingPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies/{policyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}/claimsMappingPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}/homeRealmDiscoveryPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /servicePrincipals/{id}/homeRealmDiscoveryPolicies/{policyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{servicePrincipalObjectId}/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/application-list-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/application-list-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/application-list-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/application-list-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/authenticationMethodModes](https://docs.microsoft.com/graph/api/authenticationstrengthroot-list-authenticationmethodmodes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/authenticationMethodModes/{authenticationMethodModeDetailId}](https://docs.microsoft.com/graph/api/authenticationmethodmodedetail-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations](https://docs.microsoft.com/graph/api/authenticationstrengthpolicy-list-combinationconfigurations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationStrength/policies/{authenticationStrengthPolicyId}/combinationConfigurations/{authenticationCombinationConfigurationId}](https://docs.microsoft.com/graph/api/authenticationcombinationconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/namedLocations](https://docs.microsoft.com/graph/api/conditionalaccessroot-list-namedlocations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/namedLocations/{id}](https://docs.microsoft.com/graph/api/namedlocation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/policies](https://docs.microsoft.com/graph/api/conditionalaccessroot-list-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/policies/{id}](https://docs.microsoft.com/graph/api/conditionalaccesspolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/templates](https://docs.microsoft.com/graph/api/conditionalaccessroot-list-templates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/templates/{id}](https://docs.microsoft.com/graph/api/conditionalaccesstemplate-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/continuousAccessEvaluationPolicy](https://docs.microsoft.com/graph/api/continuousaccessevaluationpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/events/onSignupStart](https://docs.microsoft.com/graph/api/authenticationeventspolicy-list-onsignupstart?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/accessReviews/policy](https://docs.microsoft.com/graph/api/accessreviewpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /policies/accessReviewPolicy](https://docs.microsoft.com/graph/api/accessreviewpolicy-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/activityBasedTimeoutPolicies/{id}](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/adminConsentRequestPolicy](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies](https://docs.microsoft.com/graph/api/appmanagementpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies/{id}](https://docs.microsoft.com/graph/api/appmanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/appmanagementpolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/authenticationFlowsPolicy](https://docs.microsoft.com/graph/api/authenticationflowspolicy-get?view=graph-rest-1.0&tabs=http)|
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
|V1|A,D|[GET /policies/authorizationPolicy](https://docs.microsoft.com/graph/api/authorizationpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /policies/b2cAuthenticationMethodsPolicy](https://docs.microsoft.com/graph/api/b2cauthenticationmethodspolicy-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies](https://docs.microsoft.com/graph/api/claimsmappingpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies/{id}](https://docs.microsoft.com/graph/api/claimsmappingpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/claimsmappingpolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy](https://docs.microsoft.com/graph/api/crosstenantaccesspolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/default](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationdefault-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/partners](https://docs.microsoft.com/graph/api/crosstenantaccesspolicy-list-partners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/partners/{id}](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationpartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/partners/{id}/identitySynchronization](https://docs.microsoft.com/graph/api/crosstenantidentitysyncpolicypartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationIdentitySynchronization](https://docs.microsoft.com/graph/api/multitenantorganizationidentitysyncpolicytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationPartnerConfiguration](https://docs.microsoft.com/graph/api/multitenantorganizationpartnerconfigurationtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/defaultAppManagementPolicy](https://docs.microsoft.com/graph/api/tenantappmanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /policies/deviceRegistrationPolicy](https://docs.microsoft.com/graph/api/deviceregistrationpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /policies/externalIdentitiesPolicy](https://docs.microsoft.com/graph/api/externalidentitiespolicy-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies/{id}](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/identitySecurityDefaultsEnforcementPolicy](https://docs.microsoft.com/graph/api/identitysecuritydefaultsenforcementpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /policies/mobileAppManagementPolicies](https://docs.microsoft.com/graph/api/mobileappmanagementpolicies-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /policies/mobileAppManagementPolicies/{id}](https://docs.microsoft.com/graph/api/mobileappmanagementpolicies-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /policies/mobileAppManagementPolicies/{id}/includedGroups](https://docs.microsoft.com/graph/api/mobileappmanagementpolicies-list-includedgroups?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /policies/mobileDeviceManagementPolicies](https://docs.microsoft.com/graph/api/mobiledevicemanagementpolicies-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /policies/mobileDeviceManagementPolicies/{id}](https://docs.microsoft.com/graph/api/mobiledevicemanagementpolicies-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /policies/mobileDeviceManagementPolicies/{id}/includedGroups](https://docs.microsoft.com/graph/api/mobiledevicemanagementpolicies-list-includedgroups?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/tokenIssuancePolicies/{id}](https://docs.microsoft.com/graph/api/tokenissuancepolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenIssuancePolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/tokenissuancepolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenLifetimePolicies/{id}](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenLifetimePolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/claimsMappingPolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/claimsMappingPolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/conditionalAccessPolicyCoverages](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-conditionalaccesspolicycoverages?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/conditionalAccessPolicyCoverages/{conditionalAccessPolicyCoverageId}](https://docs.microsoft.com/graph/api/managedtenants-conditionalaccesspolicycoverage-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /trustFramework/policies/](https://docs.microsoft.com/graph/api/trustframework-list-trustframeworkpolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /trustFramework/policies/{id}/$value](https://docs.microsoft.com/graph/api/trustframeworkpolicy-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET policies/activityBasedTimeoutPolicies](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET policies/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/tokenissuancepolicy-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET policies/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/namedLocations/{id}](https://docs.microsoft.com/graph/api/ipnamedlocation-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/conditionalAccess/policies/{id}](https://docs.microsoft.com/graph/api/conditionalaccesspolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /identity/continuousAccessEvaluationPolicy](https://docs.microsoft.com/graph/api/continuousaccessevaluationpolicy-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /policies/identitySecurityDefaultsEnforcementPolicy](https://docs.microsoft.com/graph/api/identitysecuritydefaultsenforcementpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/tokenIssuancePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/tokenIssuancePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/conditionalAccess/namedLocations](https://docs.microsoft.com/graph/api/conditionalaccessroot-post-namedlocations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/conditionalAccess/policies](https://docs.microsoft.com/graph/api/conditionalaccessroot-post-policies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/claimsMappingPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/claimsMappingPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/homeRealmDiscoveryPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|572fea84-0151-49b2-9301-11cb16974376|
|**Consent Type**|Admin|
|**Display String**|Read your organization's policies|
|**Description**|Allows the app to read your organization's policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|246dd0d5-5bd0-4def-940b-0421030a5b68|
|**Display String**|Read your organization's policies|
|**Description**|Allows the app to read all your organization's policies without a signed in user.|
## Resources
### [accessReviewPolicy ](https://docs.microsoft.com/graph/api/resources/accessreviewpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Description for this policy. Read-only.|
|displayName|String|Display name for this policy. Read-only.|
|isGroupOwnerManagementEnabled|Boolean|If `true`, group owners can create and manage access reviews on groups they own.|
### [activityBasedTimeoutPolicy ](https://docs.microsoft.com/graph/api/resources/activitybasedtimeoutpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. See below for more details about the JSON schema for this property. Required.|
|description|String| Description for this policy.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.|
### [adminConsentRequestPolicy ](https://docs.microsoft.com/graph/api/resources/adminconsentrequestpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabled|Boolean|Specifies whether the admin consent request feature is enabled or disabled. Required.|
|notifyReviewers|Boolean|Specifies whether reviewers will receive notifications. Required.|
|remindersEnabled|Boolean|Specifies whether reviewers will receive reminder emails. Required.|
|requestDurationInDays|Int32|Specifies the duration the request is active before it automatically expires if no decision is applied.|
|reviewers|accessReviewReviewerScope collection|The list of reviewers for the admin consent. Required.|
|version|Int32|Specifies the version of this policy. When the policy is updated, this version is updated. Read-only.|
### [application ](https://docs.microsoft.com/graph/api/resources/application?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| addIns | addIn collection| Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams can set the addIns property for its "FileHandler" functionality. This lets services like Microsoft 365 call the application in the context of a document the user is working on. |
| api | apiApplication | Specifies settings for an application that implements a web API. |
| appId | String | The unique identifier for the application that is assigned to an application by Microsoft Entra ID. Not nullable. Read-only. Alternate key. Supports `$filter` (`eq`).  |
| applicationTemplateId | String | Unique identifier of the applicationTemplate. Supports `$filter` (`eq`, `not`, `ne`). Read-only. `null` if the app wasn't created from an application template.|
| appRoles | appRole collection | The collection of roles defined for the application. With app role assignments, these roles can be assigned to users, groups, or service principals associated with other applications. Not nullable. |
|certification|certification|Specifies the certification status of the application.|
| createdDateTime | DateTimeOffset | The date and time the application was registered. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. <br><br> Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, and `eq` on `null` values) and `$orderby`. |
| deletedDateTime | DateTimeOffset | The date and time the application was deleted. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| description | String | Free text field to provide a description of the application object to end users. The maximum allowed size is 1,024 characters. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| disabledByMicrosoftStatus | String | Specifies whether Microsoft has disabled the registered application. Possible values are: `null` (default value), `NotDisabled`, and `DisabledDueToViolationOfServicesAgreement` (reasons include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement). <br><br> Supports `$filter` (`eq`, `ne`, `not`). |
| displayName | String | The display name for the application. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| groupMembershipClaims | String | Configures the `groups` claim issued in a user or OAuth 2.0 access token that the application expects. To set this attribute, use one of the following valid string values: `None`, `SecurityGroup` (for security groups and Microsoft Entra roles), `All` (this gets all of the security groups, distribution groups, and Microsoft Entra directory roles that the signed-in user is a member of). |
| id | String | Unique identifier for the application object. This property is referred to as **Object ID** in the Microsoft Entra admin center. Inherited from directoryObject. Key. Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| identifierUris | String collection | Also known as App ID URI, this value is set when an application is used as a resource app. The identifierUris acts as the prefix for the scopes you reference in your API's code, and it must be globally unique. You can use the default value provided, which is in the form `api://<appId>`, or specify a more readable URI like `https://contoso.com/api`. For more information on valid identifierUris patterns and best practices, see Microsoft Entra application registration security best practices. Not nullable. <br><br>Supports `$filter` (`eq`, `ne`, `ge`, `le`, `startsWith`).|
| info | informationalUrl | Basic profile information of the application such as  app's marketing, support, terms of service and privacy statement URLs. The terms of service and privacy statement are surfaced to users through the user consent experience. For more info, see How to: Add Terms of service and privacy statement for registered Microsoft Entra apps. <br><br>Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values). |
| isDeviceOnlyAuthSupported | Boolean | Specifies whether this application supports device authentication without a user. The default is `false`.  |
| isFallbackPublicClient | Boolean | Specifies the fallback application type as public client, such as an installed application running on a mobile device. The default value is `false`, which means the fallback application type is confidential client such as a web app. There are certain scenarios where Microsoft Entra ID can't determine the client application type. For example, the ROPC flow where it's configured without specifying a redirect URI. In those cases, Microsoft Entra ID interprets the application type based on the value of this property.|
| keyCredentials | keyCredential collection | The collection of key credentials associated with the application. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`). |
| logo | Stream | The main logo for the application. Not nullable. |
| nativeAuthenticationApisEnabled | nativeAuthenticationApisEnabled | Specifies whether the Native Authentication APIs are enabled for the application. The possible values are: `none` and `all`. Default is `none`. For more information, see Native Authentication. |
| notes | String | Notes relevant for the management of the application. |
| oauth2RequiredPostResponse | Boolean | Specifies whether, as part of OAuth 2.0 token requests, Microsoft Entra ID allows POST requests, as opposed to GET requests. The default is `false`, which specifies that only GET requests are allowed. |
| optionalClaims | optionalClaims | Application developers can configure optional claims in their Microsoft Entra applications to specify the claims that are sent to their application by the Microsoft security token service. For more information, see How to: Provide optional claims to your app.|
| parentalControlSettings | parentalControlSettings |Specifies parental control settings for an application. |
| passwordCredentials | passwordCredential collection|The collection of password credentials associated with the application. Not nullable.|
| publicClient | publicClientApplication | Specifies settings for installed clients such as desktop or mobile devices. |
| publisherDomain | String | The verified publisher domain for the application. Read-only. For more information, see How to: Configure an application's publisher domain. Supports `$filter` (`eq`, `ne`, `ge`, `le`, `startsWith`).|
| requestSignatureVerification | requestSignatureVerification| Specifies whether this application requires Microsoft Entra ID to verify the signed authentication requests.|
| requiredResourceAccess |requiredResourceAccess collection| Specifies the resources that the application needs to access. This property also specifies the set of delegated permissions and application roles that it needs for each of those resources. This configuration of access to the required resources drives the consent experience. <br/><br/>No more than 50 resource services (APIs) can be configured. Beginning mid-October 2021, the total number of required permissions must not exceed 400. For more information, see Limits on requested permissions per app. Not nullable. <br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`).|
| samlMetadataUrl | String | The URL where the service exposes SAML metadata for federation. This property is valid only for single-tenant applications. Nullable. |
| serviceManagementReference | String | References application or service contact information from a Service or Asset Management database. Nullable. |
| servicePrincipalLockConfiguration | servicePrincipalLockConfiguration | Specifies whether sensitive properties of a multitenant application should be locked for editing after the application is provisioned in a tenant. Nullable. `null` by default. |
| signInAudience | String | Specifies the Microsoft accounts that are supported for the current application. The possible values are: `AzureADMyOrg` (default), `AzureADMultipleOrgs`, `AzureADandPersonalMicrosoftAccount`, and `PersonalMicrosoftAccount`. See more in the table. <br/><br/>The value of this object also limits the number of permissions an app can request. For more information, see Limits on requested permissions per app. <br><br>The value for this property has implications on other app object properties. As a result, if you change this property, you might need to change other properties first. For more information, see Validation differences for signInAudience.<br><br>Supports `$filter` (`eq`, `ne`, `not`).|
| spa                     | spaApplication                            | Specifies settings for a single-page application, including sign out URLs and redirect URIs for authorization codes and access tokens. |
| tags |String collection| Custom strings that can be used to categorize and identify the application. Not nullable. Strings added here will also appear in the **tags** property of any associated service principals.<br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`) and `$search`.|
| tokenEncryptionKeyId |String|Specifies the keyId of a public key from the keyCredentials collection. When configured, Microsoft Entra ID encrypts all the tokens it emits by using the key this property points to. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.|
| uniqueName | String | The unique identifier that can be assigned to an application and used as an alternate key. Immutable. Read-only. |
| verifiedPublisher          | verifiedPublisher                            | Specifies the verified publisher of the application. For more information about how publisher verification helps support application security, trustworthiness, and compliance, see Publisher verification.|
| web |webApplication| Specifies settings for a web application. |
### [authenticationCombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/authenticationcombinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appliesToCombinations|authenticationMethodModes collection|Which authentication method combinations this configuration applies to. Must be an **allowedCombinations** object, part of the authenticationStrengthPolicy. The only possible value for `fido2combinationConfigurations` is `"fido2"`.|
|id|String|A unique system-generated identifier.|
### [authenticationFlowsPolicy ](https://docs.microsoft.com/graph/api/resources/authenticationflowspolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:-------|:---|:----------|
|description|String|Inherited property. A description of the policy. Optional. Read-only.|
|displayName|String| Inherited property. The human-readable name of the policy. Optional. Read-only.|
|id|String| Inherited property. The identifier of the authentication flows policy. Optional. Read-only.|
|selfServiceSignUp|selfServiceSignUpAuthenticationFlowConfiguration |Contains selfServiceSignUpAuthenticationFlowConfiguration settings that convey whether self-service sign-up is enabled or disabled. Optional. Read-only. |
### [authenticationListener ](https://docs.microsoft.com/graph/api/resources/authenticationlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the action.|
|priority|Int32|The priority of the listener. Determines the order of evaluation when an event has multiple listeners. The priority is evaluated from low to high.|
|sourceFilter|authenticationSourceFilter|Filter based on the source of the authentication that is used to determine whether the listener is evaluated, and is currently limited to evaluations based on application the user is authenticating to.|
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
### [authorizationPolicy ](https://docs.microsoft.com/graph/api/resources/authorizationpolicy?view=graph-rest-1.0&tabs=http)
| Property | Type | Description | 
|-|-|-|
|allowEmailVerifiedUsersToJoinOrganization|Boolean| Indicates whether a user can join the tenant by email validation. | 
|allowInvitesFrom|allowInvitesFrom|Indicates who can invite guests to the organization. Possible values are: `none`, `adminsAndGuestInviters`, `adminsGuestInvitersAndAllMembers`, `everyone`.  `everyone` is the default setting for all cloud environments except US Government. For more information, see allowInvitesFrom values. |
|allowUserConsentForRiskyApps|Boolean| Indicates whether user consent for risky apps is allowed. We recommend keeping allowUserConsentForRiskyApps as `false`. Default value is `false`. |
|allowedToSignUpEmailBasedSubscriptions|Boolean| Indicates whether users can sign up for email based subscriptions. | 
|allowedToUseSSPR|Boolean|  Indicates whether administrators of the tenant can use the Self-Service Password Reset (SSPR). For more information, see Self-service password reset for administrators. | 
|blockMsolPowerShell|Boolean| To disable the use of MSOL PowerShell, set this property to `true`. This also disables user-based access to the legacy service endpoint used by MSOL PowerShell. This doesn't affect Microsoft Entra Connect or Microsoft Graph. | 
|defaultUserRolePermissions|defaultUserRolePermissions| Specifies certain customizable permissions for default user role. | 
|description|String| Description of this policy.|
|displayName|String| Display name for this policy. |    
|guestUserRoleId|Guid| Represents role templateId for the role that should be granted to guests. Currently following roles are supported:  *User* (`a0b1b346-4d3e-4e8b-98f8-753987be4970`), *Guest User* (`10dae51f-b6af-4016-8d66-8c2a99b929b3`), and *Restricted Guest User* (`2af84b1e-32c8-42b7-82bc-daa82404023b`). |
|id|String| ID of the authorization policy. Required. Read-only.|
### [b2cAuthenticationMethodsPolicy ](https://docs.microsoft.com/graph/api/resources/b2cauthenticationmethodspolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String|The ID of the B2C authentication methods policy. This is a read only property and the key.|
|isEmailPasswordAuthenticationEnabled|Boolean|The tenant admin can configure local accounts using email if the email and password authentication method is enabled.|
|isUserNameAuthenticationEnabled|Boolean|The tenant admin can configure local accounts using username if the username and password authentication method is enabled.|
|isPhoneOneTimePasswordAuthenticationEnabled|Boolean|The tenant admin can configure local accounts using phone number if the phone number and one-time password authentication method is enabled.|
### [claimsMappingPolicy ](https://docs.microsoft.com/graph/api/resources/claimsmappingpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. For more information about the JSON schema for this property, see Properties of a claims-mapping policy definition. Required.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|Ignore this property. The claims-mapping policy can only be applied to service principals and can't be set globally for the organization.|
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
### [conditionalAccessTemplate ](https://docs.microsoft.com/graph/api/resources/conditionalaccesstemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String| The user-friendly name of the template. |
|details|conditionalAccessPolicyDetail| Complete list of policy details specific to the template. This property contains the JSON of policy settings for configuring a Conditional Access policy. |
|id|String| Immutable ID of a template. Inherited from entity. |
|name|String| The user-friendly name of the template. |
|scenarios|templateScenarios| List of conditional access scenarios that the template is recommended for. The possible values are: `new`, `secureFoundation`, `zeroTrust`, `remoteWork`, `protectAdmins`, `emergingThreats`, `unknownFutureValue`. This is a multi-valued enum. Supports `$filter` (`has`).|
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
### [crossTenantAccessPolicy ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| displayName | String | The display name of the cross-tenant access policy. Inherited from policyBase.|
| allowedCloudEndpoints | String collection | Used to specify which Microsoft clouds an organization would like to collaborate with. By default, this value is empty. Supported values for this field are: `microsoftonline.com`, `microsoftonline.us`, and `partner.microsoftonline.cn`. |
### [crossTenantAccessPolicyConfigurationDefault ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicyconfigurationdefault?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| automaticUserConsentSettings | inboundOutboundPolicyConfiguration | Determines the default configuration for automatic user consent settings. The **inboundAllowed** and **outboundAllowed** properties are always `false` and can't be updated in the default configuration. Read-only. |
| b2bCollaborationInbound | crossTenantAccessPolicyB2BSetting |Defines your default configuration for users from other organizations accessing your resources via Microsoft Entra B2B collaboration. |
| b2bCollaborationOutbound | crossTenantAccessPolicyB2BSetting |Defines your default configuration for users in your organization going outbound to access resources in another organization via Microsoft Entra B2B collaboration. |
| b2bDirectConnectInbound  |crossTenantAccessPolicyB2BSetting | Defines your default configuration for users from other organizations accessing your resources via Microsoft Entra B2B direct connect. |
| b2bDirectConnectOutbound | crossTenantAccessPolicyB2BSetting |Defines your default configuration for users in your organization going outbound to access resources in another organization via Microsoft Entra B2B direct connect. |
| inboundTrust | crossTenantAccessPolicyInboundTrust | Determines the default configuration for trusting other Conditional Access claims from external Microsoft Entra organizations. |
| invitationRedemptionIdentityProviderConfiguration | defaultInvitationRedemptionIdentityProviderConfiguration | Defines the priority order based on which an identity provider is selected during invitation redemption for a guest user. |
| isServiceDefault | Boolean | If `true`, the default configuration is set to the system default configuration. If `false`, the default settings are customized. |
| tenantRestrictions  |crossTenantAccessPolicyTenantRestrictions | Defines the default tenant restrictions configuration for users in your organization who access an external organization on your network or devices. |
### [crossTenantAccessPolicyConfigurationPartner ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicyconfigurationpartner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| automaticUserConsentSettings | inboundOutboundPolicyConfiguration | Determines the partner-specific configuration for automatic user consent settings. Unless specifically configured, the **inboundAllowed** and **outboundAllowed** properties are `null` and inherit from the default settings, which is always `false`. |
| b2bCollaborationInbound | crossTenantAccessPolicyB2BSetting | Defines your partner-specific configuration for users from other organizations accessing your resources via Microsoft Entra B2B collaboration. |
| b2bCollaborationOutbound | crossTenantAccessPolicyB2BSetting | Defines your partner-specific configuration for users in your organization going outbound to access resources in another organization via Microsoft Entra B2B collaboration. |
| b2bDirectConnectInbound | crossTenantAccessPolicyB2BSetting | Defines your partner-specific configuration for users from other organizations accessing your resources via Azure B2B direct connect. |
| b2bDirectConnectOutbound | crossTenantAccessPolicyB2BSetting | Defines your partner-specific configuration for users in your organization going outbound to access resources in another organization via Microsoft Entra B2B direct connect. |
| inboundTrust | crossTenantAccessPolicyInboundTrust | Determines the partner-specific configuration for trusting other Conditional Access claims from external Microsoft Entra organizations. |
| isInMultiTenantOrganization | Boolean | Identifies whether a tenant is a member of a multitenant organization. |
| isServiceProvider | Boolean | Identifies whether the partner-specific configuration is a Cloud Service Provider for your organization. |
| tenantId | String | The tenant identifier for the partner Microsoft Entra organization. Read-only. Key.|
| tenantRestrictions | crossTenantAccessPolicyTenantRestrictions | Defines the partner-specific tenant restrictions configuration for users in your organization who access a partner organization using partner supplied identities on your network or devices. |
### [crossTenantIdentitySyncPolicyPartner ](https://docs.microsoft.com/graph/api/resources/crosstenantidentitysyncpolicypartner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name for the cross-tenant user synchronization policy. Use the name of the partner Microsoft Entra tenant to easily identify the policy. Optional.|
|tenantId|String|Tenant identifier for the partner Microsoft Entra organization. Read-only.|
|userSyncInbound|crossTenantUserSyncInbound|Defines whether users can be synchronized from the partner tenant. Key. |
### [deviceRegistrationPolicy ](https://docs.microsoft.com/graph/api/resources/deviceregistrationpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|azureADJoin|azureADJoinPolicy|Specifies the authorization policy for controlling registration of new devices using **Microsoft Entra join** within your organization. Required. For more information, see What is a device identity?.|
|azureADRegistration|azureADRegistrationPolicy|Specifies the authorization policy for controlling registration of new devices using **Microsoft Entra registered** within your organization. Required. For more information, see What is a device identity?.|
|description|String|The description of the device registration policy. It's always set to `Tenant-wide policy that manages intial provisioning controls using quota restrictions, additional authentication and authorization checks`. Read-only.|
|displayName|String|The name of the device registration policy. It's always set to `Device Registration Policy`. Read-only.|
|id|String| The identifier of the device registration policy. It's always set to `deviceRegistrationPolicy`. Read-only.|
|localAdminPassword|localAdminPasswordSettings| Specifies the setting for **Local Admin Password Solution (LAPS)** within your organization.|
|multiFactorAuthConfiguration|multiFactorAuthConfiguration|Specifies the authentication policy for a user to complete registration using **Microsoft Entra join** or **Microsoft Entra registered** within your organization. The possible values are: `notRequired`, `required`, `unknownFutureValue`. The default value is `notRequired`.|
|userDeviceQuota|Int32|Specifies the maximum number of devices that a user can have within your organization before blocking new device registrations. The default value is set to 50. If this property isn't specified during the policy update operation, it's automatically reset to `0` to indicate that users aren't allowed to join any devices.|
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [emailAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/emailauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowExternalIdToUseEmailOtp|externalEmailOtpState|Determines whether email OTP is usable by external users for authentication. Possible values are: `default`, `enabled`, `disabled`, `unknownFutureValue`. Tenants in the `default` state who didn't use public preview have email OTP enabled beginning in October 2021.|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier. Inherited from authenticationMethodConfiguration.|
|state|authenticationMethodState|Indicates whether this authentication method is enabled or not. Possible values are: `enabled`, `disabled`.|
### [externalIdentitiesPolicy ](https://docs.microsoft.com/graph/api/resources/externalidentitiespolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowDeletedIdentitiesDataRemoval|Boolean|<!--Notifies Azure AD whether to clean up the user information about the external identity, from the guest tenant, when the user is deleted in their home tenant.--> **Reserved for future use.**| 
|allowExternalIdentitiesToLeave|Boolean|Defines whether external users can leave the guest tenant. If set to `false`, self-service controls are disabled, and the admin of the guest tenant must manually remove the external user from the guest tenant. When the external user leaves the tenant, their data in the guest tenant is first soft-deleted then permanently deleted in 30 days.|
|displayName|String|The policy name. Inherited from policyBase.|
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
### [group ](https://docs.microsoft.com/graph/api/resources/group?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-|:-|:-|
| allowExternalSenders | Boolean | Indicates if people external to the organization can send messages to the group. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| assignedLabels | assignedLabel collection | The list of sensitivity label pairs (label ID, label name) associated with a Microsoft 365 group. <br><br>Returned only on `$select`. |
| assignedLicenses | assignedLicense collection | The licenses that are assigned to the group. <br><br>Returned only on `$select`. Supports `$filter` (`eq`).Read-only. |
| autoSubscribeNewMembers | Boolean | Indicates if new members added to the group are autosubscribed to receive email notifications. You can set this property in a PATCH request for the group; don't set it in the initial POST request that creates the group. Default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| classification | String | Describes a classification for the group (such as low, medium, or high business impact). Valid values for this property are defined by creating a ClassificationList setting value, based on the template definition.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| createdDateTime | DateTimeOffset | Timestamp of when the group was created. The value can't be modified and is automatically populated when the group is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. |
| deletedDateTime | DateTimeOffset | For some Microsoft Entra objects (user, group, application), if the object is deleted, it's first logically deleted, and this property is updated with the date and time when the object was deleted. Otherwise this property is `null`. If the object is restored, this property is updated to `null`. Inherited from directoryObject.  |
| description | String | An optional description for the group. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| displayName | String | The display name for the group. This property is required when a group is created and can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| expirationDateTime | DateTimeOffset | Timestamp of when the group is set to expire. It's `null` for security groups, but for Microsoft 365 groups, it represents when the group is set to expire as defined in the groupLifecyclePolicy. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| groupTypes | String collection | Specifies the group type and its membership. <br><br>If the collection contains `Unified`, the group is a Microsoft 365 group; otherwise, it's either a security group or a distribution group. For details, see groups overview.<br><br>If the collection includes `DynamicMembership`, the group has dynamic membership; otherwise, membership is static. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| hasMembersWithLicenseErrors | Boolean | Indicates whether there are members in this group that have license errors from its group-based license assignment. <br><br>This property is never returned on a GET operation. You can use it as a $filter argument to get groups that have members with license errors (that is, filter for this property being true). See an example. <br><br>Supports `$filter` (`eq`). |
| hideFromAddressLists | Boolean | True if the group isn't displayed in certain parts of the Outlook UI: the **Address Book**, address lists for selecting message recipients, and the **Browse Groups** dialog for searching groups; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| hideFromOutlookClients | Boolean | True if the group isn't displayed in Outlook clients, such as Outlook for Windows and Outlook on the web; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| id | String | The unique identifier for the group. <br><br>Returned by default. Inherited from directoryObject. Key. Not nullable. Read-only.<br><br>Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| isArchived | Boolean | When a group is associated with a team, this property determines whether the team is in read-only mode.<br/>To read this property, use the `/group/{groupId}/team` endpoint or the Get team API. To update this property, use the archiveTeam and unarchiveTeam APIs. |
| isAssignableToRole | Boolean | Indicates whether this group can be assigned to a Microsoft Entra role. Optional. <br><br>This property can only be set while creating the group and is immutable. If set to `true`, the **securityEnabled** property must also be set to `true`, **visibility** must be `Hidden`, and the group can't be a dynamic group (that is, **groupTypes** can't contain `DynamicMembership`). <br/><br/>Only callers with at least the Privileged Role Administrator role can set this property. The caller must also be assigned the _RoleManagement.ReadWrite.Directory_ permission to set this property or update the membership of such groups. For more, see Using a group to manage Microsoft Entra role assignments<br><br>Using this feature requires a Microsoft Entra ID P1 license. Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| isSubscribedByMail | Boolean | Indicates whether the signed-in user is subscribed to receive email conversations. The default value is `true`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| licenseProcessingState | String | Indicates the status of the group license assignment to all group members. The default value is `false`. Read-only. Possible values: `QueuedForProcessing`, `ProcessingInProgress`, and `ProcessingComplete`.<br><br>Returned only on `$select`. Read-only. |
| mail | String | The SMTP address for the group, for example, "serviceadmins@contoso.com". <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| mailEnabled | Boolean | Specifies whether the group is mail-enabled. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| mailNickname | String | The mail alias for the group, unique for Microsoft 365 groups in the organization. Maximum length is 64 characters. This property can contain only characters in the ASCII character set 0 - 127 except the following characters: ` @ () \ [] " ; : <> , SPACE`. <br><br>Required. Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| membershipRule | String | The rule that determines members for this group if the group is a dynamic group (groupTypes contains `DynamicMembership`). For more information about the syntax of the membership rule, see Membership Rules syntax. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| membershipRuleProcessingState | String | Indicates whether the dynamic membership processing is on or paused. Possible values are `On` or `Paused`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| onPremisesDomainName | String | Contains the on-premises **domain FQDN**, also called **dnsDomainName** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesLastSyncDateTime | DateTimeOffset | Indicates the last time at which the group was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
| onPremisesNetBiosName | String | Contains the on-premises **netBios name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | Errors when using Microsoft synchronization product during provisioning. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| onPremisesSamAccountName | String | Contains the on-premises **SAM account name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`). Read-only. |
| onPremisesSecurityIdentifier | String | Contains the on-premises security identifier (SID) for the group synchronized from on-premises to the cloud. Read-only. <br><br>Returned by default. Supports `$filter` (`eq` including on `null` values). |
| onPremisesSyncEnabled | Boolean | `true` if this group is synced from an on-premises directory; `false` if this group was originally synced from an on-premises directory but is no longer synced; **null** if this object has never synced from an on-premises directory (default). <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). |
| preferredDataLocation | String | The preferred data location for the Microsoft 365 group. By default, the group inherits the group creator's preferred data location. To set this property, the calling app must be granted the *Directory.ReadWrite.All* permission and the user be assigned at least one of the following Microsoft Entra roles: <br><ul>User Account Administrator <li>Directory Writer <li> Exchange Administrator <li> SharePoint Administrator </ul><br/> For more information about this property, see OneDrive Online Multi-Geo. <br><br>Nullable. Returned by default. |
| preferredLanguage | String | The preferred language for a Microsoft 365 group. Should follow ISO 639-1 Code; for example, `en-US`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| proxyAddresses | String collection | Email addresses for the group that direct to the same group mailbox. For example: `["SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. The **any** operator is required to filter expressions on multi-valued properties. <br><br>Returned by default. Read-only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`). |
| renewedDateTime | DateTimeOffset | Timestamp of when the group was last renewed. This value can't be modified directly and is only updated via the renew service action. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| securityEnabled | Boolean | Specifies whether the group is a security group. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| securityIdentifier | String | Security identifier of the group, used in Windows scenarios. Read-only. <br><br>Returned by default. |
| serviceProvisioningErrors | serviceProvisioningError collection | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a group object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance). |
| theme | string | Specifies a Microsoft 365 group's color theme. Possible values are `Teal`, `Purple`, `Green`, `Blue`, `Pink`, `Orange`, or `Red`. <br><br>Returned by default. |
| uniqueName | String | The unique identifier that can be assigned to a group and used as an alternate key. Immutable. Read-only. |
| unseenCount | Int32 | Count of conversations that received new posts since the signed-in user last visited the group. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| visibility | String | Specifies the group join policy and group content visibility for groups. Possible values are: `Private`, `Public`, or `HiddenMembership`. `HiddenMembership` can be set only for Microsoft 365 groups when the groups are created. It can't be updated later. Other values of visibility can be updated after group creation.<br> If visibility value isn't specified during group creation on Microsoft Graph, a security group is created as `Private` by default, and the Microsoft 365 group is `Public`. Groups assignable to roles are always `Private`. To learn more, see group visibility options. <br><br>Returned by default. Nullable. |
### [hardwareOathAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/hardwareoathauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy. Inherited from authenticationMethodConfiguration.|
|id|String|The authentication method policy identifier. Inherited from entity.|
|state|authenticationMethodState|Possible values are: `enabled`, `disabled`. Inherited from authenticationMethodConfiguration.|
### [homeRealmDiscoveryPolicy ](https://docs.microsoft.com/graph/api/resources/homerealmdiscoverypolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. For more information about the JSON schema for this property, see Properties of a home realm discovery policy definition. Required.|
|description|String| Description for this policy.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|If set to `true`, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is `false`.|
### [identitySecurityDefaultsEnforcementPolicy ](https://docs.microsoft.com/graph/api/resources/identitysecuritydefaultsenforcementpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String|Description for this policy. Read-only.|
|displayName|String|Display name for this policy. Read-only.|
|id|String|Identifier for this policy. Read-only.|
|isEnabled|Boolean|If set to `true`, Microsoft Entra security defaults are enabled for the tenant.|
### [invokeUserFlowListener ](https://docs.microsoft.com/graph/api/resources/invokeuserflowlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the action. Inherited from authenticationListener.|
|priority|Int32|The priority of the action that is used to determine one out of multiple applicable actions. Inherited from authenticationListener.|
|sourceFilter|authenticationSourceFilter|Filter based on the source of the authentication that is used to determine whether the listener is executed. Inherited from authenticationListener.|
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
### [microsoftAuthenticatorAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/microsoftauthenticatorauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The authentication method policy identifier.|
|featureSettings|microsoftAuthenticatorFeatureSettings|A collection of Microsoft Authenticator settings such as application context and location context, and whether they are enabled for all users or specific users only.|
|state|authenticationMethodState|Possible values are: `enabled`, `disabled`.|
### [mobilityManagementPolicy ](https://docs.microsoft.com/graph/api/resources/mobilitymanagementpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appliesTo|policyScope|Indicates the user scope of the mobility management policy. Possible values are: `none`, `all`, `selected`.|
|complianceUrl|String|Compliance URL of the mobility management application.|
|description|String|Description of the mobility management application.|
|discoveryUrl|String|Discovery URL of the mobility management application.|
|displayName|String|Display name of the mobility management application.|
|id|String|Object Id of the mobility management application.|
|isValid|Boolean|Whether policy is valid. Invalid policies may not be updated and should be deleted.|
|termsOfUseUrl|String|Terms of Use URL of the mobility management application.|
### [multiTenantOrganizationIdentitySyncPolicyTemplate ](https://docs.microsoft.com/graph/api/resources/multitenantorganizationidentitysyncpolicytemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|ID of the template. Key.|
|templateApplicationLevel|templateApplicationLevel|Specifies whether the template will be applied to user synchronization settings of certain tenants. The possible values are: `none`, `newPartners`, `existingPartners`, `unknownFutureValue`. You can also specify multiple values like `newPartners,existingPartners` (default). `none` indicates the template isn't applied to any new or existing partner tenants. `newPartners` indicates the template is applied to new partner tenants. `existingPartners` indicates the template is applied to existing partner tenants, those who already had partner-specific user synchronization settings in place.|
|userSyncInbound|crossTenantUserSyncInbound|Defines whether users can be synchronized from the partner tenant.|
### [multiTenantOrganizationPartnerConfigurationTemplate ](https://docs.microsoft.com/graph/api/resources/multitenantorganizationpartnerconfigurationtemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|ID of the template. Key.|
|automaticUserConsentSettings|inboundOutboundPolicyConfiguration|Determines the partner-specific configuration for automatic user consent settings. Unless configured, the **inboundAllowed** and **outboundAllowed** properties are `null` and inherit from the default settings, which is always `false`.|
|b2bCollaborationInbound|crossTenantAccessPolicyB2BSetting|Defines your partner-specific configuration for users from other organizations accessing your resources via Microsoft Entra B2B collaboration.|
|b2bCollaborationOutbound|crossTenantAccessPolicyB2BSetting|Defines your partner-specific configuration for users in your organization going outbound to access resources in another organization via Microsoft Entra B2B collaboration.|
|b2bDirectConnectInbound|crossTenantAccessPolicyB2BSetting|Defines your partner-specific configuration for users from other organizations accessing your resources via Azure B2B direct connect.|
|b2bDirectConnectOutbound|crossTenantAccessPolicyB2BSetting|Defines your partner-specific configuration for users in your organization going outbound to access resources in another organization via Microsoft Entra B2B direct connect.|
|inboundTrust|crossTenantAccessPolicyInboundTrust|Determines the partner-specific configuration for trusting other Conditional Access claims from external Microsoft Entra organizations.|
|templateApplicationLevel|templateApplicationLevel|Specifies whether the template will be applied to partner configuration settings of certain tenants. The possible values are: `none`, `newPartners`, `existingPartners`, `unknownFutureValue`. You can also specify multiple values like `newPartners,existingPartners` (default). `none` indicates the template isn't applied to any new or existing partner tenants. `newPartners` indicates the template is applied to new partner tenants. `existingPartners` indicates the template is applied to existing partner tenants, those who already had partner-specific partner configurations in place.|
### [namedLocation ](https://docs.microsoft.com/graph/api/resources/namedlocation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The Timestamp type represents creation date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|Human-readable name of the location.|
|id|String|Identifier of a namedLocation object. Read-only.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents last modified date and time of the location using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
### [servicePrincipal ](https://docs.microsoft.com/graph/api/resources/serviceprincipal?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
| accountEnabled |Boolean| `true` if the service principal account is enabled; otherwise, `false`. If set to `false`, then no users are able to sign in to this app, even if they're assigned to it. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| addIns | addIn collection | Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams may set the addIns property for its "FileHandler" functionality. This lets services like Microsoft 365 call the application in the context of a document the user is working on.|
|alternativeNames|String collection| Used to retrieve service principals by subscription, identify resource group and full resource IDs for managed identities. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|appDescription|String|The description exposed by the associated application.|
|appDisplayName|String|The display name exposed by the associated application.|
|appId|String|The unique identifier for the associated application (its **appId** property). Alternate key. Supports `$filter` (`eq`, `ne`, `not`, `in`, `startsWith`).|
|applicationTemplateId|String|Unique identifier of the applicationTemplate. Supports `$filter` (`eq`, `not`, `ne`). Read-only. `null` if the service principal wasn't created from an application template.|
|appOwnerOrganizationId|Guid|Contains the tenant ID where the application is registered. This is applicable only to service principals backed by applications. Supports `$filter` (`eq`, `ne`, `NOT`, `ge`, `le`).|
|appRoleAssignmentRequired|Boolean|Specifies whether users or other service principals need to be granted an app role assignment for this service principal before users can sign in or apps can get tokens. The default value is `false`. Not nullable. <br><br>Supports `$filter` (`eq`, `ne`, `NOT`). |
|appRoles|appRole collection|The roles exposed by the application that's linked to this service principal. For more information, see the **appRoles** property definition on the application entity. Not nullable. |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). Filter value is case sensitive.|
| deletedDateTime | DateTimeOffset | The date and time the service principal was deleted. Read-only. |
| description | String | Free text field to provide an internal end-user facing description of the service principal. End-user portals such MyApps displays the application description in this field. The maximum allowed size is 1,024 characters. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`.|
| disabledByMicrosoftStatus | String | Specifies whether Microsoft has disabled the registered application. Possible values are: `null` (default value), `NotDisabled`, and `DisabledDueToViolationOfServicesAgreement` (reasons include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement). <br><br> Supports `$filter` (`eq`, `ne`, `not`).  |
|displayName|String|The display name for the service principal. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
|homepage|String|Home page or landing page of the application.|
|id|String|The unique identifier for the service principal. Inherited from directoryObject. Key. Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| info | informationalUrl | Basic profile information of the acquired application such as app's marketing, support, terms of service and privacy statement URLs. The terms of service and privacy statement are surfaced to users through the user consent experience. For more info, see How to: Add Terms of service and privacy statement for registered Microsoft Entra apps. <br><br>Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values).  |
|keyCredentials|keyCredential collection|The collection of key credentials associated with the service principal. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`).            |
|loginUrl|String|Specifies the URL where the service provider redirects the user to Microsoft Entra ID to authenticate. Microsoft Entra ID uses the URL to launch the application from Microsoft 365 or the Microsoft Entra My Apps. When blank, Microsoft Entra ID performs IdP-initiated sign-on for applications configured with SAML-based single sign-on. The user launches the application from Microsoft 365, the Microsoft Entra My Apps, or the Microsoft Entra SSO URL.|
|logoutUrl|String| Specifies the URL that the Microsoft's authorization service uses to sign out a user using OpenID Connect front-channel, back-channel, or SAML sign out protocols.|
|notes|String|Free text field to capture information about the service principal, typically used for operational purposes. Maximum allowed size is 1,024 characters.|
|notificationEmailAddresses|String collection|Specifies the list of email addresses where Microsoft Entra ID sends a notification when the active certificate is near the expiration date. This is only for the certificates used to sign the SAML token issued for Microsoft Entra Gallery applications.|
|oauth2PermissionScopes|permissionScope collection|The delegated permissions exposed by the application. For more information, see the **oauth2PermissionScopes** property on the application entity's **api** property. Not nullable.|
| passwordCredentials | passwordCredential collection|The collection of password credentials associated with the application. Not nullable.|
|preferredSingleSignOnMode|string|Specifies the single sign-on mode configured for this application. Microsoft Entra ID uses the preferred single sign-on mode to launch the application from Microsoft 365 or the My Apps portal. The supported values are `password`, `saml`, `notSupported`, and `oidc`.|
|preferredTokenSigningKeyThumbprint|String|This property can be used on SAML applications (apps that have **preferredSingleSignOnMode** set to `saml`) to control which certificate is used to sign the SAML responses. For applications that aren't SAML, don't write or otherwise rely on this property.|
|replyUrls|String collection|The URLs that user tokens are sent to for sign in with the associated application, or the redirect URIs that OAuth 2.0 authorization codes and access tokens are sent to for the associated application. Not nullable. |
|resourceSpecificApplicationPermissions|resourceSpecificPermission collection|The resource-specific application permissions exposed by this application. Currently, resource-specific permissions are only supported for Teams apps accessing to specific chats and teams using Microsoft Graph. Read-only.|
|samlSingleSignOnSettings|samlSingleSignOnSettings|The collection for settings related to saml single sign-on.|
|servicePrincipalNames|String collection|Contains the list of **identifiersUris**, copied over from the associated application. Additional values can be added to hybrid applications. These values can be used to identify the permissions exposed by this app within Microsoft Entra ID. For example,<ul><li>Client apps can specify a resource URI that is based on the values of this property to acquire an access token, which is the URI returned in the "aud" claim.</li></ul><br>The any operator is required for filter expressions on multi-valued properties. Not nullable. <br><br> Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|servicePrincipalType|String|Identifies whether the service principal represents an application, a managed identity, or a legacy application. This is set by Microsoft Entra ID internally. The **servicePrincipalType** property can be set to three different values: <ul><li>__Application__ - A service principal that represents an application or service. The **appId** property identifies the associated app registration, and matches the **appId** of an application, possibly from a different tenant. If the associated app registration is missing, tokens aren't issued for the service principal.</li><li>__ManagedIdentity__ - A service principal that represents a managed identity. Service principals representing managed identities can be granted access and permissions, but can't be updated or modified directly.</li><li>__Legacy__ - A service principal that represents an app created before app registrations, or through legacy experiences. A legacy service principal can have credentials, service principal names, reply URLs, and other properties that are editable by an authorized user, but doesn't have an associated app registration. The **appId** value doesn't associate the service principal with an app registration. The service principal can only be used in the tenant where it was created.</li><li>__SocialIdp__ - For internal use. </ul>|
| signInAudience | String | Specifies the Microsoft accounts that are supported for the current application. Read-only. <br><br>Supported values are:<ul><li>`AzureADMyOrg`: Users with a Microsoft work or school account in my organization's Microsoft Entra tenant (single-tenant).</li><li>`AzureADMultipleOrgs`: Users with a Microsoft work or school account in any organization's Microsoft Entra tenant (multitenant).</li><li>`AzureADandPersonalMicrosoftAccount`: Users with a personal Microsoft account, or a work or school account in any organization's Microsoft Entra tenant.</li><li>`PersonalMicrosoftAccount`: Users with a personal Microsoft account only.</li></ul> |
|tags|String collection| Custom strings that can be used to categorize and identify the service principal. Not nullable. The value is the union of strings set here and on the associated application entity's **tags** property.<br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
| tokenEncryptionKeyId |String|Specifies the keyId of a public key from the keyCredentials collection. When configured, Microsoft Entra ID issues tokens for this application encrypted using the key specified by this property. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.|
| verifiedPublisher          | verifiedPublisher                            | Specifies the verified publisher of the application that's linked to this service principal.

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
### [tokenIssuancePolicy ](https://docs.microsoft.com/graph/api/resources/tokenissuancepolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. See below for more details about the JSON schema for this property. Required.|
|description|String| Description for this policy.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|Ignore this property. The token-issuance policy can only be applied to service principals and can't be set globally for the organization.|
### [tokenLifetimePolicy ](https://docs.microsoft.com/graph/api/resources/tokenlifetimepolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. For more information about the JSON schema for this property, see Properties of a token lifetime policy definition . Required.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|If set to `true`, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is `false`.|
### [trustFrameworkPolicy ](https://docs.microsoft.com/graph/api/resources/trustframeworkpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|id|String|The ID of the policy.|
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
### [x509CertificateCombinationConfiguration ](https://docs.microsoft.com/graph/api/resources/x509certificatecombinationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedIssuerSkis|String collection|A list of allowed subject key identifier values.|
|allowedPolicyOIDs|String collection|A list of allowed policy OIDs.|
|appliesToCombinations|authenticationMethodModes collection| Which authentication method combinations this configuration applies to. The possible values for x509certificatecombinationconfiguration are `"x509CertificateSingleFactor"` or `"x509CertificateMultiFactor"`. Inherited from authenticationCombinationConfiguration.|
|id|String|A system-generated identifier. Inherited from entity.|
