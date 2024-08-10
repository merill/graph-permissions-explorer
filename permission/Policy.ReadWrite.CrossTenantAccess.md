# Policy.ReadWrite.CrossTenantAccess

> Allows the app to read and write your organization's cross tenant access policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /policies/crossTenantAccessPolicy/partners/{id}](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationpartner-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /policies/crossTenantAccessPolicy/partners/{id}/identitySynchronization](https://docs.microsoft.com/graph/api/crosstenantidentitysyncpolicypartner-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy](https://docs.microsoft.com/graph/api/crosstenantaccesspolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/default](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationdefault-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/partners](https://docs.microsoft.com/graph/api/crosstenantaccesspolicy-list-partners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/partners/{id}](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationpartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/partners/{id}/identitySynchronization](https://docs.microsoft.com/graph/api/crosstenantidentitysyncpolicypartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationIdentitySynchronization](https://docs.microsoft.com/graph/api/multitenantorganizationidentitysyncpolicytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationPartnerConfiguration](https://docs.microsoft.com/graph/api/multitenantorganizationpartnerconfigurationtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/crossTenantAccessPolicy](https://docs.microsoft.com/graph/api/crosstenantaccesspolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/crossTenantAccessPolicy/default](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationdefault-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/crossTenantAccessPolicy/partners/{id}](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationpartner-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/crossTenantAccessPolicy/partners/{id}/identitySynchronization](https://docs.microsoft.com/graph/api/crosstenantidentitysyncpolicypartner-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationIdentitySynchronization](https://docs.microsoft.com/graph/api/multitenantorganizationidentitysyncpolicytemplate-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationPartnerConfiguration](https://docs.microsoft.com/graph/api/multitenantorganizationpartnerconfigurationtemplate-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/crossTenantAccessPolicy/default/resetToSystemDefault](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationdefault-resettosystemdefault?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/crossTenantAccessPolicy/partners](https://docs.microsoft.com/graph/api/crosstenantaccesspolicy-post-partners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationIdentitySynchronization/resetToDefaultSettings](https://docs.microsoft.com/graph/api/multitenantorganizationidentitysyncpolicytemplate-resettodefaultsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /policies/crossTenantAccessPolicy/templates/multiTenantOrganizationPartnerConfiguration/resetToDefaultSettings](https://docs.microsoft.com/graph/api/multitenantorganizationpartnerconfigurationtemplate-resettodefaultsettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /policies/crossTenantAccessPolicy/partners/{id}/identitySynchronization](https://docs.microsoft.com/graph/api/crosstenantaccesspolicyconfigurationpartner-put-identitysynchronization?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|014b43d0-6ed4-4fc6-84dc-4b6f7bae7d85|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's cross tenant access policies|
|**Description**|Allows the app to read and write your organization's cross tenant access policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|338163d7-f101-4c92-94ba-ca46fe52447c|
|**Display String**|Read and write your organization's cross tenant access policies|
|**Description**|Allows the app to read and write your organization's cross tenant access policies without a signed-in user.|
## Resources
### [crossTenantAccessPolicy ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| displayName | String | The display name of the cross-tenant access policy. Inherited from policyBase.|
| allowedCloudEndpoints | String collection | Used to specify which Microsoft clouds an organization would like to collaborate with. By default, this value is empty. Supported values for this field are: `microsoftonline.com`, `microsoftonline.us`, and `partner.microsoftonline.cn`. |
### [crossTenantAccessPolicyB2BSetting ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicyb2bsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applications|crossTenantAccessPolicyTargetConfiguration|The list of applications targeted with your cross-tenant access policy.|
|usersAndGroups|crossTenantAccessPolicyTargetConfiguration|The list of users and groups targeted with your cross-tenant access policy.|
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
### [crossTenantAccessPolicyInboundTrust ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicyinboundtrust?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| isCompliantDeviceAccepted | Boolean | Specifies whether compliant devices from external Microsoft Entra organizations are trusted. |
| isHybridAzureADJoinedDeviceAccepted | Boolean | Specifies whether Microsoft Entra hybrid joined devices from external Microsoft Entra organizations are trusted. |
| isMfaAccepted | Boolean | Specifies whether MFA from external Microsoft Entra organizations is trusted.|
### [crossTenantAccessPolicyTenantRestrictions ](https://docs.microsoft.com/graph/api/resources/crosstenantaccesspolicytenantrestrictions?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applications|crossTenantAccessPolicyTargetConfiguration|The list of applications targeted with your cross-tenant access policy. Inherited from crossTenantAccessPolicyB2BSetting.|
|devices|devicesFilter|Defines the rule for filtering devices and whether devices that satisfy the rule should be allowed or blocked. This property isn't supported on the server side yet. |
|usersAndGroups|crossTenantAccessPolicyTargetConfiguration|The list of users and groups targeted with your cross-tenant access policy. Inherited from crossTenantAccessPolicyB2BSetting.|
### [crossTenantIdentitySyncPolicyPartner ](https://docs.microsoft.com/graph/api/resources/crosstenantidentitysyncpolicypartner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name for the cross-tenant user synchronization policy. Use the name of the partner Microsoft Entra tenant to easily identify the policy. Optional.|
|tenantId|String|Tenant identifier for the partner Microsoft Entra organization. Read-only.|
|userSyncInbound|crossTenantUserSyncInbound|Defines whether users can be synchronized from the partner tenant. Key. |
### [crossTenantUserSyncInbound ](https://docs.microsoft.com/graph/api/resources/crosstenantusersyncinbound?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isSyncAllowed|Boolean|Defines whether user objects should be synchronized from the partner tenant. `false` causes any current user synchronization from the source tenant to the target tenant to stop. This property has no impact on existing users who have already been synchronized.|
### [inboundOutboundPolicyConfiguration ](https://docs.microsoft.com/graph/api/resources/inboundoutboundpolicyconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| inboundAllowed | Boolean | Defines whether external users coming inbound are allowed. |
| outboundAllowed | Boolean | Defines whether internal users are allowed to go outbound. |
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
