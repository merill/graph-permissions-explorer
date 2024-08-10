# AppCertTrustConfiguration.ReadWrite.All

> Allows the app to create, read, update and delete the trusted certificate authority configuration which can be used to restrict application certificates based on their issuing authority, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}](https://docs.microsoft.com/graph/api/certificatebasedapplicationconfiguration-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}/trustedCertificateAuthorities/{trustedCertificateAuthorityId}](https://docs.microsoft.com/graph/api/certificateauthorityasentity-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/certificateAuthorities/certificateBasedApplicationConfigurations](https://docs.microsoft.com/graph/api/certificateauthoritypath-list-certificatebasedapplicationconfigurations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}](https://docs.microsoft.com/graph/api/certificatebasedapplicationconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}/trustedCertificateAuthorities](https://docs.microsoft.com/graph/api/certificatebasedapplicationconfiguration-list-trustedcertificateauthorities?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}/trustedCertificateAuthorities/{trustedCertificateAuthorityId}](https://docs.microsoft.com/graph/api/certificateauthorityasentity-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /certificateAuthorityPath/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}](https://docs.microsoft.com/graph/api/certificatebasedapplicationconfiguration-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}/trustedCertificateAuthorities/{trustedCertificateAuthorityId}](https://docs.microsoft.com/graph/api/certificateauthorityasentity-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/certificateAuthorities/certificateBasedApplicationConfigurations](https://docs.microsoft.com/graph/api/certificateauthoritypath-post-certificatebasedapplicationconfigurations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/certificateAuthorities/certificateBasedApplicationConfigurations/{certificateBasedApplicationConfigurationId}/trustedCertificateAuthorities](https://docs.microsoft.com/graph/api/certificatebasedapplicationconfiguration-post-trustedcertificateauthorities?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4bae2ed4-473e-4841-a493-9829cfd51d48|
|**Consent Type**|Admin|
|**Display String**|Read and write the trusted certificate authority configuration for applications|
|**Description**|Allows the app to create, read, update and delete the trusted certificate authority configuration which can be used to restrict application certificates based on their issuing authority, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [certificateAuthorityAsEntity ](https://docs.microsoft.com/graph/api/resources/certificateauthorityasentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|certificate|Binary|The trusted certificate.|
|id|String|The unique identifier for the certificate authority. Inherited from entity.|
|isRootAuthority|Boolean|Indicates if the certificate is a root authority. In a certificateBasedApplicationConfiguration object, at least one object in the **trustedCertificateAuthorities** collection must be a root authority. |
|issuer|String|The issuer of the trusted certificate.|
|issuerSubjectKeyIdentifier|String|The subject key identifier of the trusted certificate.|
### [certificateBasedApplicationConfiguration ](https://docs.microsoft.com/graph/api/resources/certificatebasedapplicationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. Inherited from trustedCertificateAuthorityAsEntityBase.|
|description|String|The description of the trusted certificate authorities.|
|displayName|String|The display name of the trusted certificate authorities.|
|id|String|The unique identifier for the trusted certificate authorities. Inherited from trustedCertificateAuthorityAsEntityBase.|
