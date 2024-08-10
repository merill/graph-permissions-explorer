# CustomAuthenticationExtension.ReadWrite.All

> Allows the app to read or write your organization's custom authentication extensions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /identity/customAuthenticationExtensions/{customAuthenticationExtensionId}](https://docs.microsoft.com/graph/api/customauthenticationextension-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/customAuthenticationExtensions](https://docs.microsoft.com/graph/api/identitycontainer-list-customauthenticationextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/customAuthenticationExtensions/{customAuthenticationExtensionId}](https://docs.microsoft.com/graph/api/customauthenticationextension-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/customAuthenticationExtensions/{customAuthenticationExtensionId}](https://docs.microsoft.com/graph/api/customauthenticationextension-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/customAuthenticationExtensions](https://docs.microsoft.com/graph/api/identitycontainer-post-customauthenticationextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/customAuthenticationExtensions/{customAuthenticationExtensionId}/validateAuthenticationConfiguration](https://docs.microsoft.com/graph/api/customauthenticationextension-validateauthenticationconfiguration?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8dfcf82f-15d0-43b3-bc78-a958a13a5792|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's custom authentication extensions|
|**Description**|Allows the app to read or write your organization's custom authentication extensions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|c2667967-7050-4e7e-b059-4cbbb3811d03|
|**Display String**|Read and write all custom authentication extensions|
|**Description**|Allows the app to read or write your organization's custom authentication extensions without a signed-in user.|
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
### [customCalloutExtension ](https://docs.microsoft.com/graph/api/resources/customcalloutextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. For example, using OAuth client credentials flow. |
|clientConfiguration|customExtensionClientConfiguration| HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed.|
|description|String|Description for the customCalloutExtension object.|
|displayName|String|Display name for the customCalloutExtension object.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the logic app's workflow.|
|id|String|Identifier for the customCalloutExtension object. Inherited from entity.|
### [customExtensionAuthenticationConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionauthenticationconfiguration?view=graph-rest-1.0&tabs=http)

### [customExtensionClientConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionclientconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|timeoutInMilliseconds|Int32|The max duration in milliseconds that Microsoft Entra ID waits for a response from the external app before it shuts down the connection. The valid range is between `200` and `2000` milliseconds. Default duration is `1000`.|
|maximumRetries|Int32|The max number of retries that Microsoft Entra ID makes to the external API. Values of 0 or 1 are supported. If `null`, the default for the service applies.|
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
### [onAttributeCollectionStartCustomExtensionHandler ](https://docs.microsoft.com/graph/api/resources/onattributecollectionstartcustomextensionhandler?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|configuration|customExtensionOverwriteConfiguration|Configuration regarding properties of the custom extension that are can be overwritten per event listener.|
### [onAttributeCollectionSubmitCustomExtension ](https://docs.microsoft.com/graph/api/resources/onattributecollectionsubmitcustomextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|HTTP connection settings that define how long Microsoft Entra ID can wait for a connection, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|description|String|Description for the onAttributeCollectionSubmitCustomExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the onAttributeCollectionSubmitCustomExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the app's workflow. Inherited from customCalloutExtension.|
|id|String|Identifier for the onAttributeCollectionSubmitCustomExtension object. Inherited from entity. Inherited from entity.|
### [onAttributeCollectionSubmitCustomExtensionHandler ](https://docs.microsoft.com/graph/api/resources/onattributecollectionsubmitcustomextensionhandler?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|configuration|customExtensionOverwriteConfiguration|Configuration regarding properties of the custom extension that can be overwritten per event listener.|
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
### [onTokenIssuanceStartReturnClaim ](https://docs.microsoft.com/graph/api/resources/ontokenissuancestartreturnclaim?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|claimIdInApiResponse|String|The identifier of the claim returned by an API that is to be add to a token being issued.|
