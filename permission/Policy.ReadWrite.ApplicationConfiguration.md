# Policy.ReadWrite.ApplicationConfiguration

> Allows the app to read and write your organization's application configuration policies on behalf of the signed-in user.  This includes policies such as activityBasedTimeoutPolicy, claimsMappingPolicy, homeRealmDiscoveryPolicy,  tokenIssuancePolicy and tokenLifetimePolicy.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[](https://docs.microsoft.com/graph/api/application-delete-tokenlifetimepolicies?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /applications(appId='{appId}')/tokenIssuancePolicies/{id}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications(appId='{appId}')/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{applicationObjectId}/appManagementPolicies/{appManagementPolicyId}/$ref](https://docs.microsoft.com/graph/api/appmanagementpolicy-delete-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{applicationObjectId}/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{id}/tokenIssuancePolicies/{id}/$ref](https://docs.microsoft.com/graph/api/application-delete-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /policies/activityBasedTimeoutPolicies/{id}](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/appManagementPolicies/{id}](https://docs.microsoft.com/graph/api/appmanagementpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/claimsMappingPolicies/{id}](https://docs.microsoft.com/graph/api/claimsmappingpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/homeRealmDiscoveryPolicies/{id}](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/tokenIssuancePolicies/{id}](https://docs.microsoft.com/graph/api/tokenissuancepolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/tokenLifetimePolicies/{id}](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/claimsMappingPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies/{policyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}/claimsMappingPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}/homeRealmDiscoveryPolicies/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /servicePrincipals/{id}/homeRealmDiscoveryPolicies/{policyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-homerealmdiscoverypolicies?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{servicePrincipalObjectId}/appManagementPolicies/{appManagementPolicyId}/$ref](https://docs.microsoft.com/graph/api/appmanagementpolicy-delete-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{servicePrincipalObjectId}/tokenLifetimePolicies/{tokenLifetimePolicyId}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/application-list-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/application-list-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/application-list-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/application-list-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/events/onSignupStart](https://docs.microsoft.com/graph/api/authenticationeventspolicy-list-onsignupstart?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/activityBasedTimeoutPolicies/{id}](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies](https://docs.microsoft.com/graph/api/appmanagementpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies/{id}](https://docs.microsoft.com/graph/api/appmanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/appmanagementpolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies](https://docs.microsoft.com/graph/api/claimsmappingpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies/{id}](https://docs.microsoft.com/graph/api/claimsmappingpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/claimsmappingpolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/defaultAppManagementPolicy](https://docs.microsoft.com/graph/api/tenantappmanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies/{id}](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies/{id}/appliesTo](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-list-appliesto?view=graph-rest-1.0&tabs=http)|
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
|Beta|A,D|[GET /servicePrincipals/{servicePrincipalsId}/claimsPolicy](https://docs.microsoft.com/graph/api/customclaimspolicy-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET policies/activityBasedTimeoutPolicies](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET policies/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/tokenissuancepolicy-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET policies/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /policies/activityBasedTimeoutPolicies/{id}](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/appManagementPolicies/{id}](https://docs.microsoft.com/graph/api/appmanagementpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/claimsMappingPolicies/{id}](https://docs.microsoft.com/graph/api/claimsmappingpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/defaultAppManagementPolicy](https://docs.microsoft.com/graph/api/tenantappmanagementpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/homeRealmDiscoveryPolicies/{id}](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/tokenIssuancePolicies/{id}](https://docs.microsoft.com/graph/api/tokenissuancepolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/tokenLifetimePolicies/{id}](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /servicePrincipals/{servicePrincipalsId}/claimsPolicy](https://docs.microsoft.com/graph/api/customclaimspolicy-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/tokenIssuancePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/appManagementPolicies/$ref](https://docs.microsoft.com/graph/api/appmanagementpolicy-post-appliesto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/tokenIssuancePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenissuancepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/application-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /identity/events/onSignupStart](https://docs.microsoft.com/graph/api/authenticationeventspolicy-post-onsignupstart?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /policies/appManagementPolicies](https://docs.microsoft.com/graph/api/appmanagementpolicy-post?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/claimsMappingPolicies](https://docs.microsoft.com/graph/api/claimsmappingpolicy-post-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-post-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/claimsMappingPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/homeRealmDiscoveryPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/claimsMappingPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/homeRealmDiscoveryPolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/tokenLifetimePolicies/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST policies/activityBasedTimeoutPolicies](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-post-activitybasedtimeoutpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST policies/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/tokenissuancepolicy-post-tokenissuancepolicy?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST policies/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-put?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /servicePrincipals/{servicePrincipalsId}/claimsPolicy](https://docs.microsoft.com/graph/api/serviceprincipal-put-claimspolicy?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b27add92-efb2-4f16-84f5-8108ba77985c|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's application configuration policies|
|**Description**|Allows the app to read and write your organization's application configuration policies on behalf of the signed-in user.  This includes policies such as activityBasedTimeoutPolicy, claimsMappingPolicy, homeRealmDiscoveryPolicy,  tokenIssuancePolicy and tokenLifetimePolicy.|
## Application Permission
|||
|-|-|
|**Id**|be74164b-cff1-491c-8741-e671cb536e13|
|**Display String**|Read and write your organization's application configuration policies|
|**Description**|Allows the app to read and write your organization's application configuration policies, without a signed-in user.  This includes policies such as activityBasedTimeoutPolicy, claimsMappingPolicy, homeRealmDiscoveryPolicy, tokenIssuancePolicy  and tokenLifetimePolicy.|
## Resources
### [activityBasedTimeoutPolicy ](https://docs.microsoft.com/graph/api/resources/activitybasedtimeoutpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. See below for more details about the JSON schema for this property. Required.|
|description|String| Description for this policy.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.|
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
### [appManagementConfiguration ](https://docs.microsoft.com/graph/api/resources/appmanagementconfiguration?view=graph-rest-1.0&tabs=http)
| Property            | Type                                                                  | Description                                                                                       |
| :------------------ | :-------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------ |
| passwordCredentials | passwordCredentialConfiguration collection | Collection of password restrictions settings to be applied to an application or service principal. |
| keyCredentials | keyCredentialConfiguration collection | Collection of keyCredential restrictions settings to be applied to an application or service principal. |
### [appManagementPolicy ](https://docs.microsoft.com/graph/api/resources/appmanagementpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type                                                        | Description                                                            |
| :----------- | :---------------------------------------------------------- | :--------------------------------------------------------------------- |
| displayName  | String                                                      | The display name of the policy. Inherited from policyBase. |
| description  | String                                                      | The description of the policy. Inherited from policyBase.  |
| id           | String                                                      | The unique identifier for the policy.                                       |
| isEnabled    | Boolean                                                     | Denotes whether the policy is enabled.                                      |
| restrictions | appManagementConfiguration | Restrictions that apply to an application or service principal object. |
### [authenticationListener ](https://docs.microsoft.com/graph/api/resources/authenticationlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the action.|
|priority|Int32|The priority of the listener. Determines the order of evaluation when an event has multiple listeners. The priority is evaluated from low to high.|
|sourceFilter|authenticationSourceFilter|Filter based on the source of the authentication that is used to determine whether the listener is evaluated, and is currently limited to evaluations based on application the user is authenticating to.|
### [authenticationSourceFilter ](https://docs.microsoft.com/graph/api/resources/authenticationsourcefilter?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|includeApplications|String collection|Applications to include for evaluation of the authenticationListener. These applications trigger the associated action when used as the client application in the authentication flow. The application identifer is the application's client id.|
### [b2xIdentityUserFlow ](https://docs.microsoft.com/graph/api/resources/b2xidentityuserflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|apiConnectorConfiguration|userFlowApiConnectorConfiguration|Configuration for enabling an API connector for use as part of the self-service sign-up user flow. You can only obtain the value of this object using Get userFlowApiConnectorConfiguration.|
|id|String|The name of the user flow is a required value and is immutable after it's created. The name will be prefixed with the value of `B2X_1_` after creation.|
|userFlowType|userFlowType|The type of user flow. For self-service sign-up user flows, the value can only be `signUpOrSignIn` and can't be modified after creation.|
|userFlowTypeVersion|Single|The version of the user flow. For self-service sign-up user flows, the version is always `1`.|
### [claimsMappingPolicy ](https://docs.microsoft.com/graph/api/resources/claimsmappingpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. For more information about the JSON schema for this property, see Properties of a claims-mapping policy definition. Required.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|Ignore this property. The claims-mapping policy can only be applied to service principals and can't be set globally for the organization.|
### [customClaimBase ](https://docs.microsoft.com/graph/api/resources/customclaimbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|configurations|customClaimConfiguration collection|One or more configurations that describe how the claim is sourced and under what conditions.|
### [customClaimsPolicy ](https://docs.microsoft.com/graph/api/resources/customclaimspolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|audienceOverride|String|If specified, it overrides the content of the audience claim for WS-Federation and SAML2 protocols. A custom signing key must be used for audienceOverride to be applied, otherwise, the audienceOverride value is ignored. The value provided must be in the format of an absolute URI.|
|claims|customClaim collection|Defines which claims are present in the tokens affected by the policy, in addition to the basic claim and the core claim set. Inherited from customclaimbase.|
|id|String|Policy identifier string. Inherited from entity.|
|includeApplicationIdInIssuer|Boolean|Indicates whether the application ID is added to the claim. It is relevant only for SAML2.0 and if a custom signing key is used. the default value is `true`. Optional.|
|includeBasicClaimSet|Boolean|Determines whether the basic claim set is included in tokens affected by this policy. If set to `true`, all claims in the basic claim set are emitted in tokens affected by the policy. By default the basic claim set isn't in the tokens unless they're explicitly configured in this policy.|
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [homeRealmDiscoveryPolicy ](https://docs.microsoft.com/graph/api/resources/homerealmdiscoverypolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. For more information about the JSON schema for this property, see Properties of a home realm discovery policy definition. Required.|
|description|String| Description for this policy.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|If set to `true`, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is `false`.|
### [invokeUserFlowListener ](https://docs.microsoft.com/graph/api/resources/invokeuserflowlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the action. Inherited from authenticationListener.|
|priority|Int32|The priority of the action that is used to determine one out of multiple applicable actions. Inherited from authenticationListener.|
|sourceFilter|authenticationSourceFilter|Filter based on the source of the authentication that is used to determine whether the listener is executed. Inherited from authenticationListener.|
### [policyBase ](https://docs.microsoft.com/graph/api/resources/policybase?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String| Unique identifier for this policy. Read-only. Inherited from directoryObject.|
|description|String| Description for this policy. Required.|
|displayName|String| Display name for this policy. Required. |
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

### [tenantAppManagementPolicy ](https://docs.microsoft.com/graph/api/resources/tenantappmanagementpolicy?view=graph-rest-1.0&tabs=http)
| Property                     | Type                                                                     | Description                                                                         |
| :--------------------------- | :----------------------------------------------------------------------- | :---------------------------------------------------------------------------------- |
| applicationRestrictions      | appManagementConfiguration | Restrictions that apply as default to all application objects in the tenant.        |
| description                  | String                                                                   | The description of the default policy. Inherited from policyBase.  |
| displayName                  | String                                                                   | The display name of the default policy. Inherited from policyBase. |
| id                           | String                                                                   | The default policy identifier.                                                      |
| isEnabled                    | Boolean                                                                  | Denotes whether the policy is enabled. Default value is `false`.                    |
| servicePrincipalRestrictions | appManagementConfiguration | Restrictions that apply as default to all service principal objects in the tenant.  |
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
