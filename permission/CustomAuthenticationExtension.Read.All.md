# CustomAuthenticationExtension.Read.All

> Allows the app to read your organization's custom authentication extensions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /identity/customAuthenticationExtensions](https://docs.microsoft.com/graph/api/identitycontainer-list-customauthenticationextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/customAuthenticationExtensions/{customAuthenticationExtensionId}](https://docs.microsoft.com/graph/api/customauthenticationextension-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/customAuthenticationExtensions/{customAuthenticationExtensionId}/validateAuthenticationConfiguration](https://docs.microsoft.com/graph/api/customauthenticationextension-validateauthenticationconfiguration?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b2052569-c98c-4f36-a5fb-43e5c111e6d0|
|**Consent Type**|Admin|
|**Display String**|Read your oganization's custom authentication extensions|
|**Description**|Allows the app to read your organization's custom authentication extensions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|88bb2658-5d9e-454f-aacd-a3933e079526|
|**Display String**|Read all custom authentication extensions|
|**Description**|Allows the app to read your organization's custom authentication extensions without a signed-in user.|
## Resources
### [authenticationConfigurationValidation ](https://docs.microsoft.com/graph/api/resources/authenticationconfigurationvalidation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|errors|genericError collection|Errors in the validation result of a customAuthenticationExtension.|
|warnings|genericError collection|Warnings in the validation result of a customAuthenticationExtension.|
### [customAuthenticationExtension ](https://docs.microsoft.com/graph/api/resources/customauthenticationextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|The authentication configuration for the customAuthenticationExtension. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|The connection settings for the customAuthenticationExtension. Inherited from customCalloutExtension.|
|description|String|The description of the customAuthenticationExtension. Inherited from customCalloutExtension.|
|displayName|String|The display name for the customAuthenticationExtension. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The HTTP endpoint that this custom extension calls. Inherited from customCalloutExtension.|
|id|String|Identifier for the customAuthenticationExtension. Inherited from entity.|
### [customExtensionEndpointConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionendpointconfiguration?view=graph-rest-1.0&tabs=http)

### [onAttributeCollectionStartCustomExtension ](https://docs.microsoft.com/graph/api/resources/onattributecollectionstartcustomextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|HTTP connection settings that define how long Microsoft Entra ID can wait for a connection, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|description|String|Description for the onAttributeCollectionStartCustomExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the onAttributeCollectionStartCustomExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the app's workflow. Inherited from customCalloutExtension.|
|id|String|Identifier for the onAttributeCollectionStartCustomExtension object. Inherited from entity. Inherited from entity.|
### [onAttributeCollectionSubmitCustomExtension ](https://docs.microsoft.com/graph/api/resources/onattributecollectionsubmitcustomextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|HTTP connection settings that define how long Microsoft Entra ID can wait for a connection, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|description|String|Description for the onAttributeCollectionSubmitCustomExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the onAttributeCollectionSubmitCustomExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the app's workflow. Inherited from customCalloutExtension.|
|id|String|Identifier for the onAttributeCollectionSubmitCustomExtension object. Inherited from entity. Inherited from entity.|
### [onTokenIssuanceStartCustomExtension ](https://docs.microsoft.com/graph/api/resources/ontokenissuancestartcustomextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|The authentication configuration for this custom authentication extension. Inherited from customCalloutExtension.|
|claimsForTokenConfiguration|onTokenIssuanceStartReturnClaim collection|Collection of claims to be returned by the API called by this custom authentication extension. Used to populate claims mapping experience in Microsoft Entra admin center. Optional. |
|clientConfiguration|customExtensionClientConfiguration|The connection settings for the custom authentication extension. Inherited from customCalloutExtension.|
|description|String|Description for the custom authentication extension. Inherited from customCalloutExtension.|
|displayName|String|Display name for the custom authentication extension. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|Configuration for the API endpoint that the custom authentication extension will call. Inherited from customCalloutExtension.|
|id|String|Identifier for onTokenIssuanceStartCustomExtension. Inherited from entity.|
