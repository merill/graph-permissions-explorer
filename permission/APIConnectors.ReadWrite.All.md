# APIConnectors.ReadWrite.All

> Allows the app to read, create and manage the API connectors used in user authentication flows, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /identity/apiConnectors/{identityApiConnectorId}](https://docs.microsoft.com/graph/api/identityapiconnector-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/apiConnectors/](https://docs.microsoft.com/graph/api/identityapiconnector-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/apiConnectors/{identityApiConnectorId}](https://docs.microsoft.com/graph/api/identityapiconnector-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/apiConnectors/{identityApiConnectorId}](https://docs.microsoft.com/graph/api/identityapiconnector-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/apiConnectors](https://docs.microsoft.com/graph/api/identityapiconnector-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/apiconnectors/{id}/uploadClientCertificate](https://docs.microsoft.com/graph/api/identityapiconnector-uploadclientcertificate?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c67b52c5-7c69-48b6-9d48-7b3af3ded914|
|**Consent Type**|Admin|
|**Display String**|Read and write API connectors for authentication flows|
|**Description**|Allows the app to read, create and manage the API connectors used in user authentication flows, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|1dfe531a-24a6-4f1b-80f4-7a0dc5a0a171|
|**Display String**|Read and write API connectors for authentication flows|
|**Description**|Allows the app to read, create and manage the API connectors used in user authentication flows, without a signed-in user.|
## Resources
### [apiAuthenticationConfigurationBase ](https://docs.microsoft.com/graph/api/resources/apiauthenticationconfigurationbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
### [basicAuthentication ](https://docs.microsoft.com/graph/api/resources/basicauthentication?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|password|String| The password. It isn't returned in the responses. |
|username|String| The username. |
### [clientCertificateAuthentication ](https://docs.microsoft.com/graph/api/resources/clientcertificateauthentication?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|certificateList| pkcs12CertificateInformation collection| The list of certificates uploaded for this API connector.|
### [identityApiConnector ](https://docs.microsoft.com/graph/api/resources/identityapiconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|apiAuthenticationConfigurationBase|The object which describes the authentication configuration details for calling the API. Basic and PKCS 12 client certificate are supported.|
|displayName|String| The name of the API connector. |
|id|String|The randomly generated identifier of the API connector. |
|targetUrl|String| The URL of the API endpoint to call. |
### [pkcs12Certificate ](https://docs.microsoft.com/graph/api/resources/pkcs12certificate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|password|String| The password for the pfx file. Required. If no password is used, you must still provide a value of `""`.|
|pkcs12Value|String| Represents the pfx content that is sent. The value should be a base-64 encoded version of the actual certificate content. Required.|
