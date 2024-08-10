# CrossTenantInformation.ReadBasic.All

> Allows the application to obtain basic tenant information about another target tenant within the Azure AD ecosystem on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /tenantRelationships/findTenantInformationByDomainName(domainName='{id}')](https://docs.microsoft.com/graph/api/tenantrelationship-findtenantinformationbydomainname?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/findTenantInformationByTenantId(tenantId='{id}')](https://docs.microsoft.com/graph/api/tenantrelationship-findtenantinformationbytenantid?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|81594d25-e88e-49cf-ac8c-fecbff49f994|
|**Consent Type**|Admin|
|**Display String**|Read cross-tenant basic information|
|**Description**|Allows the application to obtain basic tenant information about another target tenant within the Azure AD ecosystem on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|cac88765-0581-4025-9725-5ebc13f729ee|
|**Display String**|Read cross-tenant basic information|
|**Description**|Allows the application to obtain basic tenant information about another target tenant within the Azure AD ecosystem without a signed-in user.|
## Resources
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
### [tenantInformation ](https://docs.microsoft.com/graph/api/resources/tenantinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| defaultDomainName | String | Primary domain name of a Microsoft Entra tenant. |
| displayName | String | Display name of a Microsoft Entra tenant. |
| federationBrandName | String | Name shown to users that sign in to a Microsoft Entra tenant. |
| tenantId | String | Unique identifier of a Microsoft Entra tenant. |
