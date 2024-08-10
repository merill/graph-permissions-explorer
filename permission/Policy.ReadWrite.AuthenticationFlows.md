# Policy.ReadWrite.AuthenticationFlows

> Allows the app to read and write the authentication flow policies, on behalf of the signed-in user. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /policies/authenticationFlowsPolicy](https://docs.microsoft.com/graph/api/authenticationflowspolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authenticationFlowsPolicy](https://docs.microsoft.com/graph/api/authenticationflowspolicy-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|edb72de9-4252-4d03-a925-451deef99db7|
|**Consent Type**|Admin|
|**Display String**|Read and write authentication flow policies|
|**Description**|Allows the app to read and write the authentication flow policies, on behalf of the signed-in user. |
## Application Permission
|||
|-|-|
|**Id**|25f85f3c-f66c-4205-8cd5-de92dd7f0cec|
|**Display String**|Read and write authentication flow policies|
|**Description**|Allows the app to read and write all authentication flow policies for the tenant, without a signed-in user.|
## Resources
### [authenticationFlowsPolicy ](https://docs.microsoft.com/graph/api/resources/authenticationflowspolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:-------|:---|:----------|
|description|String|Inherited property. A description of the policy. Optional. Read-only.|
|displayName|String| Inherited property. The human-readable name of the policy. Optional. Read-only.|
|id|String| Inherited property. The identifier of the authentication flows policy. Optional. Read-only.|
|selfServiceSignUp|selfServiceSignUpAuthenticationFlowConfiguration |Contains selfServiceSignUpAuthenticationFlowConfiguration settings that convey whether self-service sign-up is enabled or disabled. Optional. Read-only. |
### [selfServiceSignUpAuthenticationFlowConfiguration ](https://docs.microsoft.com/graph/api/resources/selfservicesignupauthenticationflowconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:-------|:---|:----------|
|isEnabled|Boolean|Indicates whether self-service sign-up flow is enabled or disabled. The default value is `false`. This property isn't a key. Required. |
