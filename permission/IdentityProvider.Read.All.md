# IdentityProvider.Read.All

> Allows the app to read your organization’s identity (authentication) providers’ properties on behalf of the user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /directory/federationConfigurations/microsoft.graph.samlOrWsFedExternalDomainFederation/{samlOrWsFedExternalDomainFederation ID}/domains](https://docs.microsoft.com/graph/api/samlorwsfedexternaldomainfederation-list-domains?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/identityProviders](https://docs.microsoft.com/graph/api/identitycontainer-list-identityproviders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/identityProviders/{id}](https://docs.microsoft.com/graph/api/identityproviderbase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/identityProviders/availableProviderTypes](https://docs.microsoft.com/graph/api/identityproviderbase-availableprovidertypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityProviders](https://docs.microsoft.com/graph/api/identityprovider-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityProviders/{id}](https://docs.microsoft.com/graph/api/identityprovider-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityProviders/availableProviderTypes](https://docs.microsoft.com/graph/api/identityprovider-list-availableprovidertypes?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|43781733-b5a7-4d1b-98f4-e8edff23e1a9|
|**Consent Type**|Admin|
|**Display String**|Read identity providers|
|**Description**|Allows the app to read your organization’s identity (authentication) providers’ properties on behalf of the user.|
## Application Permission
|||
|-|-|
|**Id**|e321f0bb-e7f7-481e-bb28-e3b0b32d4bd0|
|**Display String**|Read identity providers|
|**Description**|Allows the app to read your organization’s identity (authentication) providers’ properties without a signed in user.|
## Resources
### [appleManagedIdentityProvider ](https://docs.microsoft.com/graph/api/resources/applemanagedidentityprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|certificateData|String|The certificate data, which is a long string of text from the certificate. Can be null.|
|developerId|String|The Apple developer identifier. Required.|
|displayName|String|The display name of the identity provider. Inherited from identityProviderBase.|
|id|String|The identifier of the identity provider. Inherited from identityProviderBase. Read-only.|
|keyId|String|The Apple key identifier. Required.|
|serviceId|String|The Apple service identifier. Required.|
### [builtInIdentityProvider ](https://docs.microsoft.com/graph/api/resources/builtinidentityprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|displayName|String|The display name of the identity provider. Inherited from identityProviderBase.|
|id|String|The identifier of the identity provider. Inherited from identityProviderBase. Read-only.|
|identityProviderType|String|The identity provider type. For a B2B scenario, possible values: `AADSignup`, `MicrosoftAccount`, `EmailOTP`. Required.|
### [externalDomainName ](https://docs.microsoft.com/graph/api/resources/externaldomainname?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Domain name of the external organization that the Microsoft Entra tenant is federating with. Inherited from entity.|
### [identityprovider](https://docs.microsoft.com/graph/api/resources/identityprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:--------|
|clientId|String|The client ID for the application. This is the client ID obtained when registering the application with the identity provider. Required. Not nullable.|
|clientSecret|String|The client secret for the application. This is the client secret obtained when registering the application with the identity provider. This is write-only. A read operation will return `****`.  Required. Not nullable.|
|id|String|The ID of the identity provider.|
|name|String|The display name of the identity provider. Not nullable.|
|type|String|The identity provider type is a required field. For B2B scenario: `Google`, `Facebook`. For B2C scenario: `Microsoft`, `Google`, `Amazon`, `LinkedIn`, `Facebook`, `GitHub`, `Twitter`, `Weibo`, `QQ`, `WeChat`, `OpenIDConnect`. Not nullable.|
### [identityProviderBase ](https://docs.microsoft.com/graph/api/resources/identityproviderbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|displayName|String|The display name of the identity provider.|
|id|String|The identifier of the identity provider.|
### [openIdConnectIdentityProvider ](https://docs.microsoft.com/graph/api/resources/openidconnectidentityprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|clientId|String|The client identifier for the application obtained when registering the application with the identity provider. Required.|
|clientSecret|String|The client secret for the application obtained when registering the application with the identity provider. The clientSecret has a dependency on **responseType**. <ul><li>When **responseType** is `code`, a secret is required for the auth code exchange.</li><li>When **responseType** is `id_token` the secret is not required because there is no code exchange. The id_token is returned directly from the authorization response.</li></ul> This is write-only. A read operation returns `****`.|
|id|String|The identifier of the identity provider.Required. Inherited from identityProviderBase. Read-only.|
|displayName|String|The display name of the identity provider. |
|claimsMapping|claimsMapping|After the OIDC provider sends an ID token back to Microsoft Entra ID, Microsoft Entra ID needs to be able to map the claims from the received token to the claims that Microsoft Entra ID recognizes and uses. This complex type captures that mapping. Required.|
|domainHint|String|The domain hint can be used to skip directly to the sign-in page of the specified identity provider, instead of having the user make a selection among the list of available identity providers.|
|metadataUrl|String|The URL for the metadata document of the OpenID Connect identity provider. Every OpenID Connect identity provider describes a metadata document that contains most of the information required to perform sign-in. This includes information such as the URLs to use and the location of the service's public signing keys. The OpenID Connect metadata document is always located at an endpoint that ends in `.well-known/openid-configuration`. Provide the metadata URL for the OpenID Connect identity provider you add. Read-only. Required.|
|responseMode|openIdConnectResponseMode|The response mode defines the method used to send data back from the custom identity provider to Azure AD B2C. Possible values: `form_post`, `query`. Required.|
|responseType|openIdConnectResponseTypes|The response type describes the type of information sent back in the initial call to the authorization_endpoint of the custom identity provider. Possible values: `code` , `id_token` , `token`.  Required.|
|scope|String|Scope defines the information and permissions you are looking to gather from your custom identity provider. OpenID Connect requests must contain the openid scope value in order to receive the ID token from the identity provider. Without the ID token, users are not able to sign in to Azure AD B2C using the custom identity provider. Other scopes can be appended, separated by a space. For more details about the scope limitations, see RFC6749 Section 3.3. Required.|
### [openidconnectprovider](https://docs.microsoft.com/graph/api/resources/openidconnectprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|clientId|String|The client identifier for the application obtained when registering the application with the identity provider. Inherited from identityProvider. This is a required property.|
|clientSecret|String|The client secret for the application obtained when registering the application with the identity provider. The clientSecret has a dependency on **responseType**. When **responseType** is `code`, a secret is required for the auth code exchange. When **responseType** is `id_token` the secret isn't required because there's no code exchange, the `id_token` is returned directly from the authorization response. This is write-only. A read operation returns "\*\*\*\*". Inherited from identityProvider.|
|id|String|The ID of the identity provider. It's a required property and is read only after creation.|
|name|String|The display name of the identity provider. It's a required property and is read only after creation.|
|type|String|The identity provider type. It must be `OpenIDConnect`. It's a required property and is read only after creation.|
|claimsMapping|claimsMapping|After the OIDC provider sends an ID token back to Microsoft Entra ID, Microsoft Entra ID needs to be able to map the claims from the received token to the claims that Microsoft Entra ID recognizes and uses. This complex type captures that mapping. It's a required property.|
|domainHint|String|The domain hint can be used to skip directly to the sign-in page of the specified identity provider, instead of having the user make a selection among the list of available identity providers.|
|metadataUrl|String|The URL for the metadata document of the OpenID Connect identity provider. Every OpenID Connect identity provider describes a metadata document that contains most of the information required to perform sign-in. This includes information such as the URLs to use and the location of the service's public signing keys. The OpenID Connect metadata document is always located at an endpoint that ends in a well-known/openid-configuration. For the OpenID Connect identity provider you're looking to add, you need to provide the metadata URL. It's a required property and is read only after creation.|
|responseMode|openIdConnectResponseMode|The response mode defines the method that should be used to send the data back from the custom identity provider to Azure AD B2C. The following response modes can be used: `form_post`, `query`. `query` response mode means the code or token is returned as a query parameter. `form_post` response mode is recommended for the best security. The response is transmitted via the HTTP POST method, with the code or token being encoded in the body using the application/x-www-form-urlencoded format. It's a required property.|
|responseType|openIdConnectResponseTypes| response type describes what kind of information is sent back in the initial call to the authorization_endpoint of the custom identity provider. The following response types can be used: `code` , `id_token` , `token`. It's a required property.|
|scope|String|Scope defines the information and permissions you're looking to gather from your custom identity provider. OpenID Connect requests must contain the openid scope value in order to receive the ID token from the identity provider. Without the ID token, users aren't able to sign in to Azure AD B2C using the custom identity provider. Other scopes can be appended separated by space. For more information about the scope limitations, see RFC6749 Section 3.3. It's a required property.|
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
### [socialIdentityProvider ](https://docs.microsoft.com/graph/api/resources/socialidentityprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|clientId|String|The identifier for the client application obtained when registering the application with the identity provider. Required.|
|clientSecret|String|The client secret for the application that is obtained when the application is registered with the identity provider. This is write-only. A read operation returns `****`. Required.|
|displayName|String|The display name of the identity provider. Inherited from identityProviderBase.|
|id|String|The identifier of the identity provider. Inherited from identityProviderBase. Read-only.|
|identityProviderType|String|For a B2B scenario, possible values: `Google`, `Facebook`. For a B2C scenario, possible values: `Microsoft`, `Google`, `Amazon`, `LinkedIn`, `Facebook`, `GitHub`, `Twitter`, `Weibo`, `QQ`, `WeChat`. Required.|
