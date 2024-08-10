# Policy.Read.ApplicationConfiguration

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /policies/activityBasedTimeoutPolicies/{id}](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/appManagementPolicies/{id}](https://docs.microsoft.com/graph/api/appmanagementpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/claimsMappingPolicies/{id}](https://docs.microsoft.com/graph/api/claimsmappingpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/homeRealmDiscoveryPolicies/{id}](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/tokenIssuancePolicies/{id}](https://docs.microsoft.com/graph/api/tokenissuancepolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/tokenLifetimePolicies/{id}](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/events/onSignupStart](https://docs.microsoft.com/graph/api/authenticationeventspolicy-list-onsignupstart?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/activityBasedTimeoutPolicies/{id}](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies](https://docs.microsoft.com/graph/api/appmanagementpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/appManagementPolicies/{id}](https://docs.microsoft.com/graph/api/appmanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies](https://docs.microsoft.com/graph/api/claimsmappingpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/claimsMappingPolicies/{id}](https://docs.microsoft.com/graph/api/claimsmappingpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/defaultAppManagementPolicy](https://docs.microsoft.com/graph/api/tenantappmanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/homeRealmDiscoveryPolicies/{id}](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenIssuancePolicies/{id}](https://docs.microsoft.com/graph/api/tokenissuancepolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/tokenLifetimePolicies/{id}](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-get?view=graph-rest-1.0&tabs=http)|
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
|Beta|A,D|[POST /identity/events/onSignupStart](https://docs.microsoft.com/graph/api/authenticationeventspolicy-post-onsignupstart?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /policies/appManagementPolicies](https://docs.microsoft.com/graph/api/appmanagementpolicy-post?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/claimsMappingPolicies](https://docs.microsoft.com/graph/api/claimsmappingpolicy-post-claimsmappingpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/homeRealmDiscoveryPolicies](https://docs.microsoft.com/graph/api/homerealmdiscoverypolicy-post-homerealmdiscoverypolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST policies/activityBasedTimeoutPolicies](https://docs.microsoft.com/graph/api/activitybasedtimeoutpolicy-post-activitybasedtimeoutpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST policies/tokenIssuancePolicies](https://docs.microsoft.com/graph/api/tokenissuancepolicy-post-tokenissuancepolicy?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST policies/tokenLifetimePolicies](https://docs.microsoft.com/graph/api/tokenlifetimepolicy-post-tokenlifetimepolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /identity/events/onSignupStart/{id}](https://docs.microsoft.com/graph/api/authenticationlistener-put?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /servicePrincipals/{servicePrincipalsId}/claimsPolicy](https://docs.microsoft.com/graph/api/serviceprincipal-put-claimspolicy?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [activityBasedTimeoutPolicy ](https://docs.microsoft.com/graph/api/resources/activitybasedtimeoutpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|definition|String collection| A string collection containing a JSON string that defines the rules and settings for this policy. See below for more details about the JSON schema for this property. Required.|
|description|String| Description for this policy.|
|displayName|String| Display name for this policy. Required.|
|id|String| Unique identifier for this policy. Read-only.|
|isOrganizationDefault|Boolean|If set to true, activates this policy. There can be many policies for the same policy type, but only one can be activated as the organization default. Optional, default value is false.|
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
