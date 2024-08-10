# Domain.ReadWrite.All

> Allows the app to read and write all domain properties on behalf of the signed-in user. Also allows the app to add, verify and remove domains.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /domains/{domainsId}/federationConfiguration/{internalDomainFederationId}](https://docs.microsoft.com/graph/api/internaldomainfederation-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /domains/{id}](https://docs.microsoft.com/graph/api/domain-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE directory/federationConfigurations/{samlOrWsFedExternalDomainFederation ID}](https://docs.microsoft.com/graph/api/samlorwsfedexternaldomainfederation-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/federationConfigurations/graph.samlOrWsFedExternalDomainFederation](https://docs.microsoft.com/graph/api/samlorwsfedexternaldomainfederation-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/federationConfigurations/graph.samlOrWsFedExternalDomainFederation?$filter=domains/any(x: x/id eq 'domainName-value')](https://docs.microsoft.com/graph/api/samlorwsfedexternaldomainfederation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains](https://docs.microsoft.com/graph/api/domain-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains/{domainsId}/federationConfiguration](https://docs.microsoft.com/graph/api/domain-list-federationconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains/{domainsId}/federationConfiguration/{internalDomainFederationId}](https://docs.microsoft.com/graph/api/internaldomainfederation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains/{id}](https://docs.microsoft.com/graph/api/domain-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains/{id}/domainNameReferences](https://docs.microsoft.com/graph/api/domain-list-domainnamereferences?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains/{id}/serviceConfigurationRecords](https://docs.microsoft.com/graph/api/domain-list-serviceconfigurationrecords?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /domains/{id}/verificationDnsRecords](https://docs.microsoft.com/graph/api/domain-list-verificationdnsrecords?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /domains/contoso.com/rootDomain](https://docs.microsoft.com/graph/api/domain-list-rootdomain?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /domains/{domainsId}/federationConfiguration/{internalDomainFederationId}](https://docs.microsoft.com/graph/api/internaldomainfederation-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /domains/{id}](https://docs.microsoft.com/graph/api/domain-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /domains](https://docs.microsoft.com/graph/api/domain-post-domains?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /domains/{domainsId}/federationConfiguration](https://docs.microsoft.com/graph/api/domain-post-federationconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /domains/{id}/forceDelete](https://docs.microsoft.com/graph/api/domain-forcedelete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /domains/{id}/promote](https://docs.microsoft.com/graph/api/domain-promote?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /domains/{id}/verify](https://docs.microsoft.com/graph/api/domain-verify?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|0b5d694c-a244-4bde-86e6-eb5cd07730fe|
|**Consent Type**|Admin|
|**Display String**|Read and write domains|
|**Description**|Allows the app to read and write all domain properties on behalf of the signed-in user. Also allows the app to add, verify and remove domains.|
## Application Permission
|||
|-|-|
|**Id**|7e05723c-0bb0-42da-be95-ae9f08a6e53c|
|**Display String**|Read and write domains|
|**Description**|Allows the app to read and write all domain properties without a signed in user.  Also allows the app to add,  verify and remove domains.|
## Resources
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [domain ](https://docs.microsoft.com/graph/api/resources/domain?view=graph-rest-1.0&tabs=http)
| Property   | Type | Description |
|:---------------|:--------|:----------|
|authenticationType|String| Indicates the configured authentication type for the domain. The value is either `Managed` or `Federated`. `Managed` indicates a cloud managed domain where Microsoft Entra ID performs user authentication. `Federated` indicates authentication is federated with an identity provider such as the tenant's on-premises Active Directory via Active Directory Federation Services. Not nullable.  <br/><br/>To update this property in delegated scenarios, the calling app must be assigned the *Directory.AccessAsUser.All* delegated permission.  |
|availabilityStatus|String| This property is always `null` except when the verify action is used. When the verify action is used, a **domain** entity is returned in the response. The **availabilityStatus** property of the **domain** entity in the response is either `AvailableImmediately` or `EmailVerifiedDomainTakeoverScheduled`.|
|id|String| The fully qualified name of the domain. Key, immutable, not nullable, unique. |
|isAdminManaged|Boolean| The value of the property is `false` if the DNS record management of the domain is delegated to Microsoft 365. Otherwise, the value is `true`. Not nullable |
|isDefault|Boolean| `true` if this is the default domain that is used for user creation. There's only one default domain per company. Not nullable |
|isInitial|Boolean| `true` if this is the initial domain created by Microsoft Online Services (contoso.com). There's only one initial domain per company. Not nullable |
|isRoot|Boolean| `true` if the domain is a verified root domain. Otherwise, `false` if the domain is a subdomain or unverified. Not nullable |
|isVerified|Boolean| `true` if the domain has completed domain ownership verification. Not nullable |
|passwordNotificationWindowInDays|Int32|Specifies the number of days before a user receives notification that their password will expire. If the property isn't set, a default value of 14 days is used.|
|passwordValidityPeriodInDays|Int32| Specifies the length of time that a password is valid before it must be changed. If the property isn't set, a default value of 90 days is used. |
|state|domainState| Status of asynchronous operations scheduled for the domain. |
|supportedServices|String collection| The capabilities assigned to the domain. Can include `0`, `1` or more of following values: `Email`, `Sharepoint`, `EmailInternalRelayOnly`, `OfficeCommunicationsOnline`, `SharePointDefaultDomain`, `FullRedelegation`, `SharePointPublic`, `OrgIdAuthentication`, `Yammer`, `Intune`. The values that you can add or remove using the API include: `Email`, `OfficeCommunicationsOnline`, `Yammer`. Not nullable.|
### [domainDnsRecord ](https://docs.microsoft.com/graph/api/resources/domaindnsrecord?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|id|String| Unique identifier assigned to this entity. Not nullable, Read-only.|
|isOptional|Boolean| If `false`, the customer must configure this record at the DNS host for Microsoft Online Services to operate correctly with the domain. |
|label|String| Value used when configuring the name of the DNS record at the DNS host. |
|recordType|String| Indicates what type of DNS record this entity represents. The value can be `CName`, `Mx`, `Srv`, or `Txt`. |
|supportedService|String| Microsoft Online Service or feature that has a dependency on this DNS record. Can be one of the following values: `null`, `Email`, `Sharepoint`, `EmailInternalRelayOnly`, `OfficeCommunicationsOnline`, `SharePointDefaultDomain`, `FullRedelegation`, `SharePointPublic`, `OrgIdAuthentication`, `Yammer`, `Intune`.|
|ttl|Int32| Value to use when configuring the time-to-live (ttl) property of the DNS record at the DNS host. Not nullable. |
### [externalDomainName ](https://docs.microsoft.com/graph/api/resources/externaldomainname?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Domain name of the external organization that the Microsoft Entra tenant is federating with. Inherited from entity.|
### [internalDomainFederation ](https://docs.microsoft.com/graph/api/resources/internaldomainfederation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activeSignInUri|String|URL of the endpoint used by active clients when authenticating with federated domains set up for single sign-on in Microsoft Entra ID. Corresponds to the **ActiveLogOnUri** property of the Set-MsolDomainFederationSettings MSOnline v1 PowerShell cmdlet.|
|displayName|String|The display name of the federated identity Provider (IdP). Inherited from identityProviderBase.|
|federatedIdpMfaBehavior|federatedIdpMfaBehavior|Determines whether Microsoft Entra ID accepts the MFA performed by the federated IdP when a federated user accesses an application that is governed by a conditional access policy that requires MFA. The possible values are: `acceptIfMfaDoneByFederatedIdp`, `enforceMfaByFederatedIdp`, `rejectMfaByFederatedIdp`, `unknownFutureValue`. For more information, see federatedIdpMfaBehavior values.|
|id|String|The identifier of the federated identity provider. Inherited from entity.|
|isSignedAuthenticationRequestRequired|Boolean|If `true`, when SAML authentication requests are sent to the federated SAML IdP, Microsoft Entra ID will sign those requests using the OrgID signing key. If `false` (default), the SAML authentication requests sent to the federated IdP aren't signed.|
|issuerUri|String|Issuer URI of the federation server. Inherited from samlOrWsFedProvider.|
|metadataExchangeUri|String|URI of the metadata exchange endpoint used for authentication from rich client applications. Inherited from samlOrWsFedProvider.|
|nextSigningCertificate|String|Fallback token signing certificate that can also be used to sign tokens, for example when the primary signing certificate expires. Formatted as Base64 encoded strings of the public portion of the federated IdP's token signing certificate. Needs to be compatible with the X509Certificate2 class. Much like the signingCertificate, the nextSigningCertificate property is used if a rollover is required outside of the auto-rollover update, a new federation service is being set up, or if the new token signing certificate isn't present in the federation properties after the federation service certificate has been updated.|
|passiveSignInUri|String|URI that web-based clients are directed to when signing into Microsoft Entra services. Inherited from samlOrWsFedProvider.|
|preferredAuthenticationProtocol|authenticationProtocol|Preferred authentication protocol. The possible values are: `wsFed`, `saml`, `unknownFutureValue`. Inherited from samlOrWsFedProvider.|
|promptLoginBehavior|promptLoginBehavior|Sets the preferred behavior for the sign-in prompt. The possible values are: `translateToFreshPasswordAuthentication`, `nativeSupport`, `disabled`, `unknownFutureValue`.|
|signingCertificate|String|Current certificate used to sign tokens passed to the Microsoft identity platform. The certificate is formatted as a Base64 encoded string of the public portion of the federated IdP's token signing certificate and must be compatible with the X509Certificate2 class. <br>This property is used in the following scenarios: <li> If a rollover is required outside of the autorollover update <li> A new federation service is being set up <li> If the new token signing certificate isn't present in the federation properties after the federation service certificate has been updated.<br>Microsoft Entra ID updates certificates via an autorollover process in which it attempts to retrieve a new certificate from the federation service metadata, 30 days before expiry of the current certificate. If a new certificate isn't available, Microsoft Entra ID monitors the metadata daily and will update the federation settings for the domain when a new certificate is available. Inherited from samlOrWsFedProvider.|
|signingCertificateUpdateStatus|signingCertificateUpdateStatus|Provides status and timestamp of the last update of the signing certificate.|
|signOutUri|String|URI that clients are redirected to when they sign out of Microsoft Entra services. Corresponds to the **L
### [samlOrWsFedExternalDomainFederation ](https://docs.microsoft.com/graph/api/resources/samlorwsfedexternaldomainfederation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the SAML or WS-Fed based IdP. Inherited from identityProviderBase.|
|id|String|The identifier of the identity provider. Inherited from entity.|
|issuerUri|String|Issuer URI of the federation server. Inherited from samlOrWsFedProvider.|
|metadataExchangeUri|String|URI of the metadata exchange endpoint used for authentication from rich client applications. Inherited from samlOrWsFedProvider.|
|passiveSignInUri|String|URI that web-based clients are directed to when signing in to Microsoft Entra services. Inherited from samlOrWsFedProvider.|
|preferredAuthenticationProtocol|authenticationProtocol|Preferred authentication protocol. The possible values are: `wsFed`, `saml`, `unknownFutureValue`. Inherited from samlOrWsFedProvider.|
|signingCertificate|String|Current certificate used to sign tokens passed to the Microsoft identity platform. The certificate is formatted as a Base64 encoded string of the public portion of the federated IdP's token signing certificate and must be compatible with the X509Certificate2 class.  <br/><br/> This property is used in the following scenarios: <ul><li> if a rollover is required outside of the autorollover update <li>a new federation service is being set up <li> if the new token signing certificate isn't present in the federation properties after the federation service certificate has been updated. </ul> <br/><br/> Microsoft Entra ID updates certificates via an autorollover process in which it attempts to retrieve a new certificate from the federation service metadata, 30 days before expiry of the current certificate. If a new certificate isn't available, Microsoft Entra ID monitors the metadata daily and will update the federation settings for the domain when a new certificate is available. <br/><br/> Inherited from samlOrWsFedProvider.|
### [samlOrWsFedProvider ](https://docs.microsoft.com/graph/api/resources/samlorwsfedprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the SAML/WS-Fed based identity provider. Inherited from identityProviderBase.|
|id|String|The identifier of the identity provider. Inherited from entity.|
|issuerUri|String|Issuer URI of the federation server.|
|metadataExchangeUri|String|URI of the metadata exchange endpoint used for authentication from rich client applications.|
|passiveSignInUri|String|URI that web-based clients are directed to when signing in to Microsoft Entra services.|
|preferredAuthenticationProtocol|authenticationProtocol|Preferred authentication protocol. The possible values are: `wsFed`, `saml`, `unknownFutureValue`.|
|signingCertificate|String|Current certificate used to sign tokens passed to the Microsoft identity platform. The certificate is formatted as a Base64 encoded string of the public portion of the federated IdP's token signing certificate and must be compatible with the X509Certificate2 class.  <br/><br/> This property is used in the following scenarios: <ul><li> if a rollover is required outside of the autorollover update <li>a new federation service is being set up <li> if the new token signing certificate isn't present in the federation properties after the federation service certificate has been updated. </ul> <br/><br/> Microsoft Entra ID updates certificates via an autorollover process in which it attempts to retrieve a new certificate from the federation service metadata, 30 days before expiry of the current certificate. If a new certificate isn't available, Microsoft Entra ID monitors the metadata daily and will update the federation settings for the domain when a new certificate is available.|
### [signingCertificateUpdateStatus ](https://docs.microsoft.com/graph/api/resources/signingcertificateupdatestatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|certificateUpdateResult|String|Status of the last certificate update. Read-only. For a list of statuses, see certificateUpdateResult status.|
|lastRunDateTime|DateTimeOffset|Date and time in ISO 8601 format and in UTC time when the certificate was last updated. Read-only. |
