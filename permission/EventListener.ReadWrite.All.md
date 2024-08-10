# EventListener.ReadWrite.All

> Allows the app to read or write your organization's authentication event listeners on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /identity/authenticationEventListeners/{authenticationEventListenerId}](https://docs.microsoft.com/graph/api/authenticationeventlistener-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/authenticationEventsFlows/{authenticationEventsFlow-id}](https://docs.microsoft.com/graph/api/authenticationeventsflow-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/](https://docs.microsoft.com/graph/api/authenticationeventsflow-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/conditions/applications/includeApplications/{appId}](https://docs.microsoft.com/graph/api/authenticationconditionapplication-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAttributeCollection/microsoft.graph.onAttributeCollectionExternalUsersSelfServiceSignUp/attributes/{attributeId}/$ref](https://docs.microsoft.com/graph/api/onattributecollectionexternalusersselfservicesignup-delete-attributes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAuthenticationMethodLoadStart/microsoft.graph.onAuthenticationMethodLoadStartExternalUsersSelfServiceSignUp/{identityProviders-id}/$ref](https://docs.microsoft.com/graph/api/onauthenticationmethodloadstartexternalusersselfservicesignup-delete-identityproviders?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAuthenticationMethodLoadStart/microsoft.graph.onAuthenticationMethodLoadStartExternalUsersSelfServiceSignUp/identityProviders/$ref](https://docs.microsoft.com/graph/api/onauthenticationmethodloadstartexternalusersselfservicesignup-delete-identityproviders?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventListeners](https://docs.microsoft.com/graph/api/identitycontainer-list-authenticationeventlisteners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventListeners/{authenticationEventListenerId}](https://docs.microsoft.com/graph/api/authenticationeventlistener-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/authenticationEventListeners/{listenerId}/microsoft.graph.onAttributeCollectionStartListener/handler/microsoft.graph.onAttributeCollectionStartCustomExtensionHandler/customExtension](https://docs.microsoft.com/graph/api/onattributecollectionstartcustomextension-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/authenticationEventListeners/{listenerId}/microsoft.graph.onAttributeCollectionSubmitListener/handler/microsoft.graph.onAttributeCollectionSubmitCustomExtensionHandler/customExtension](https://docs.microsoft.com/graph/api/onattributecollectionsubmitcustomextension-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventsFlows](https://docs.microsoft.com/graph/api/identitycontainer-list-authenticationeventsflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventsFlows/{authenticationEventsFlow-id}](https://docs.microsoft.com/graph/api/authenticationeventsflow-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/conditions/applications/includeApplications/](https://docs.microsoft.com/graph/api/authenticationconditionsapplications-list-includeapplications?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAttributeCollection/microsoft.graph.onAttributeCollectionExternalUsersSelfServiceSignUp/attributes/](https://docs.microsoft.com/graph/api/onattributecollectionexternalusersselfservicesignup-list-attributes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAuthenticationMethodLoadStart/microsoft.graph.onAuthenticationMethodLoadStartExternalUsersSelfServiceSignUp/identityProviders/](https://docs.microsoft.com/graph/api/onauthenticationmethodloadstartexternalusersselfservicesignup-list-identityproviders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/authenticationEventListeners/{authenticationEventListenerId}](https://docs.microsoft.com/graph/api/authenticationeventlistener-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identity/authenticationEventsFlows/{authenticationEventsFlow-id}](https://docs.microsoft.com/graph/api/authenticationeventsflow-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/authenticationEventListeners](https://docs.microsoft.com/graph/api/identitycontainer-post-authenticationeventlisteners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/authenticationEventsFlows](https://docs.microsoft.com/graph/api/identitycontainer-post-authenticationeventsflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/conditions/applications/includeApplications](https://docs.microsoft.com/graph/api/authenticationconditionsapplications-post-includeapplications?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAttributeCollection/microsoft.graph.onAttributeCollectionExternalUsersSelfServiceSignUp/attributes/$ref](https://docs.microsoft.com/graph/api/onattributecollectionexternalusersselfservicesignup-post-attributes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/authenticationEventsFlows/{authenticationEventsFlow-id}/microsoft.graph.externalUsersSelfServiceSignUpEventsFlow/onAuthenticationMethodLoadStart/microsoft.graph.onAuthenticationMethodLoadStartExternalUsersSelfServiceSignUp/identityProviders/$ref](https://docs.microsoft.com/graph/api/onauthenticationmethodloadstartexternalusersselfservicesignup-post-identityproviders?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /identity/authenticationEventListeners/{listenerId}/microsoft.graph.onAttributeCollectionStartListener/handler/microsoft.graph.onAttributeCollectionStartCustomExtensionHandler/customExtension/$ref](https://docs.microsoft.com/graph/api/onattributecollectionstartcustomextension-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /identity/authenticationEventListeners/{listenerId}/microsoft.graph.onAttributeCollectionSubmitListener/handler/microsoft.graph.onAttributeCollectionSubmitCustomExtensionHandler/customExtension/$ref](https://docs.microsoft.com/graph/api/onattributecollectionsubmitcustomextension-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|d11625a6-fe21-4fc6-8d3d-063eba5525ad|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's authentication event listeners|
|**Description**|Allows the app to read or write your organization's authentication event listeners on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|0edf5e9e-4ce8-468a-8432-d08631d18c43|
|**Display String**|Read and write all authentication event listeners|
|**Description**|Allows the app to read or write your organization's authentication event listeners without a signed-in user.|
## Resources
### [authenticationConditionApplication ](https://docs.microsoft.com/graph/api/resources/authenticationconditionapplication?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appId|String|The identifier for an application corresponding to a condition which will trigger an authenticationEventListener.|
### [authenticationConditions ](https://docs.microsoft.com/graph/api/resources/authenticationconditions?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applications|authenticationConditionsApplications|Applications which trigger a custom authentication extension.|
### [authenticationEventListener ](https://docs.microsoft.com/graph/api/resources/authenticationeventlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|conditions|authenticationConditions|The conditions on which this authenticationEventListener should trigger.|
|id|String|Identifier for this authenticationEventListener. Inherited from entity.|
|authenticationEventsFlowId|String|Indicates the authenticationEventListener is associated with an authenticationEventsFlow. Read-only.

### [authenticationEventsFlow ](https://docs.microsoft.com/graph/api/resources/authenticationeventsflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the entity. Read-only. Inherited from entity. Autogenerated.|
|displayName|String|Required. The display name for the events policy.|
|description|String|The description of the events policy.|
|conditions|authenticationConditions|The conditions representing the context of the authentication request that's used to decide whether the events policy is invoked. <br/><br/> Supports `$filter` (`eq`). See support for filtering on user flows for syntax information.|
### [customAuthenticationExtension ](https://docs.microsoft.com/graph/api/resources/customauthenticationextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|The authentication configuration for the customAuthenticationExtension. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|The connection settings for the customAuthenticationExtension. Inherited from customCalloutExtension.|
|description|String|The description of the customAuthenticationExtension. Inherited from customCalloutExtension.|
|displayName|String|The display name for the customAuthenticationExtension. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The HTTP endpoint that this custom extension calls. Inherited from customCalloutExtension.|
|id|String|Identifier for the customAuthenticationExtension. Inherited from entity.|
### [externalUsersSelfServiceSignUpEventsFlow ](https://docs.microsoft.com/graph/api/resources/externalusersselfservicesignupeventsflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the entity. Read-only. Inherited from entity.|
|displayName|String|Required. The display name for the events policy. Must be unique. Inherited from authenticationEventsFlow.|
|description|String|Optional. The description of the events policy. Inherited from authenticationEventsFlow.|
|conditions|authenticationConditions|Optional. The conditions representing the context of the authentication request which is used to decide whether the events policy is invoked. Inherited from authenticationEventsFlow.|
|onInteractiveAuthFlowStart|onInteractiveAuthFlowStartHandler|Required. The configuration for what to invoke when an authentication flow is ready to be initiated. |
|onAttributeCollection|onAttributeCollectionHandler|The configuration for what to invoke when attributes are ready to be collected from the user.|
|onAuthenticationMethodLoadStart|onAuthenticationMethodLoadStartHandler|Required. The configuration for what to invoke when authentication methods are ready to be presented to the user. Must have at least one identity provider linked. <br/><br/> Supports `$filter` (`eq`). See support for filtering on user flows for syntax information. |
|onUserCreateStart|onUserCreateStartHandler|The configuration for what to invoke during user creation.|
### [identityProviderBase ](https://docs.microsoft.com/graph/api/resources/identityproviderbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|displayName|String|The display name of the identity provider.|
|id|String|The identifier of the identity provider.|
### [identityUserFlowAttribute ](https://docs.microsoft.com/graph/api/resources/identityuserflowattribute?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|dataType|identityUserFlowAttributeDataType|The data type of the user flow attribute. Can't be modified after the custom user flow attribute is created. The supported values for **dataType** are: `string` , `boolean` , `int64` , `stringCollection` , `dateTime`, `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`, `ne`).|
|displayName|String|The display name of the user flow attribute. <br/><br/> Supports `$filter` (`eq`, `ne`). |
|description|String|The description of the user flow attribute that's shown to the user at the time of sign up.|
|id|String|The identifier of the user flow attribute. Read-only. <br/><br/> Supports `$filter` (`eq`, `ne`). |
|userFlowAttributeType|identityUserFlowAttributeType|The type of the user flow attribute. Read-only. Depending on the type of attribute, the values for this property are `builtIn`, `custom`, `required`, `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`, `ne`). |
### [onAttributeCollectionHandler ](https://docs.microsoft.com/graph/api/resources/onattributecollectionhandler?view=graph-rest-1.0&tabs=http)

### [onAttributeCollectionListener ](https://docs.microsoft.com/graph/api/resources/onattributecollectionlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Required. Inherited from entity.|
|conditions|authenticationConditions|Required. Inherited from authenticationEventListener.|
|authenticationEventsFlowId|String| Inherited from authenticationEventListener.|
|handler|onAttributeCollectionHandler|Required. Configuration for what to invoke if the event resolves to this listener.|
### [onAttributeCollectionStartCustomExtension ](https://docs.microsoft.com/graph/api/resources/onattributecollectionstartcustomextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|HTTP connection settings that define how long Microsoft Entra ID can wait for a connection, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|description|String|Description for the onAttributeCollectionStartCustomExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the onAttributeCollectionStartCustomExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the app's workflow. Inherited from customCalloutExtension.|
|id|String|Identifier for the onAttributeCollectionStartCustomExtension object. Inherited from entity. Inherited from entity.|
### [onAttributeCollectionStartHandler ](https://docs.microsoft.com/graph/api/resources/onattributecollectionstarthandler?view=graph-rest-1.0&tabs=http)

### [onAttributeCollectionStartListener ](https://docs.microsoft.com/graph/api/resources/onattributecollectionstartlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationEventsFlowId|String|The identifier of the authenticationEventsFlow object. Inherited from authenticationEventListener.|
|conditions|authenticationConditions|The conditions on which this authenticationEventListener should trigger. Inherited from authenticationEventListener.|
|handler|onAttributeCollectionStartHandler|Configuration for what to invoke if the event resolves to this listener.|
|id|String|Identifier for this authenticationEventListener. Inherited from entity.|
|priority|Int32|The priority of this handler. Between 0 (lower priority) and 1000 (higher priority). Inherited from authenticationEventListener.|
### [onAttributeCollectionSubmitCustomExtension ](https://docs.microsoft.com/graph/api/resources/onattributecollectionsubmitcustomextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|clientConfiguration|customExtensionClientConfiguration|HTTP connection settings that define how long Microsoft Entra ID can wait for a connection, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|description|String|Description for the onAttributeCollectionSubmitCustomExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the onAttributeCollectionSubmitCustomExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the app's workflow. Inherited from customCalloutExtension.|
|id|String|Identifier for the onAttributeCollectionSubmitCustomExtension object. Inherited from entity. Inherited from entity.|
### [onAttributeCollectionSubmitHandler ](https://docs.microsoft.com/graph/api/resources/onattributecollectionsubmithandler?view=graph-rest-1.0&tabs=http)

### [onAttributeCollectionSubmitListener ](https://docs.microsoft.com/graph/api/resources/onattributecollectionsubmitlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationEventsFlowId|String|The identifier of the authenticationEventsFlow object. Inherited from authenticationEventListener.|
|conditions|authenticationConditions|The conditions on which this authenticationEventListener should trigger. Inherited from authenticationEventListener.|
|handler|onAttributeCollectionSubmitHandler|Configuration for what to invoke if the event resolves to this listener. |
|id|String|Identifier for this authenticationEventListener. Inherited from entity.|
|priority|Int32|The priority of this listener. Between 0 (lower priority) and 1000 (higher priority). Inherited from authenticationEventListener.|
### [onAuthenticationMethodLoadStartHandler ](https://docs.microsoft.com/graph/api/resources/onauthenticationmethodloadstarthandler?view=graph-rest-1.0&tabs=http)

### [onAuthenticationMethodLoadStartListener ](https://docs.microsoft.com/graph/api/resources/onauthenticationmethodloadstartlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Required. Inherited from entity.|
|conditions|authenticationConditions|Required. Inherited from authenticationEventListener.|
|authenticationEventsFlowId|String| Inherited from authenticationEventListener.|
|handler|onAuthenticationMethodLoadStartHandler|Required. Configuration for what to invoke if the event resolves to this listener. This lets us define potential handler configurations per-event.|
### [onInteractiveAuthFlowStartHandler ](https://docs.microsoft.com/graph/api/resources/oninteractiveauthflowstarthandler?view=graph-rest-1.0&tabs=http)

### [onInteractiveAuthFlowStartListener ](https://docs.microsoft.com/graph/api/resources/oninteractiveauthflowstartlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Required. Inherited from entity.|
|conditions|authenticationConditions|Required. Inherited from authenticationEventListener.|
|authenticationEventsFlowId|String| Inherited from authenticationEventListener.|
|handler|onInteractiveAuthFlowStartHandler|Required. Configuration for what to invoke if the event resolves to this listener. This lets us define potential handler configurations per-event.|
### [onTokenIssuanceStartHandler ](https://docs.microsoft.com/graph/api/resources/ontokenissuancestarthandler?view=graph-rest-1.0&tabs=http)

### [onTokenIssuanceStartListener ](https://docs.microsoft.com/graph/api/resources/ontokenissuancestartlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|conditions|authenticationConditions|The conditions on which onTokenIssuanceStartListener should trigger. Inherited from authenticationEventListener.|
|handler|onTokenIssuanceStartHandler|The handler to invoke when conditions are met for this onTokenIssuanceStartListener.|
|id|String|Identifier for the onTokenIssuanceStartListener. Inherited from entity.|
### [onUserCreateStartHandler ](https://docs.microsoft.com/graph/api/resources/onusercreatestarthandler?view=graph-rest-1.0&tabs=http)

### [onUserCreateStartListener ](https://docs.microsoft.com/graph/api/resources/onusercreatestartlistener?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Required. Inherited from entity.|
|conditions|authenticationConditions|Required. Inherited from authenticationEventListener.|
|authenticationEventsFlowId|String| Inherited from authenticationEventListener.|
|handler|onUserCreateStartHandler|Required. Configuration for what to invoke if the event resolves to this listener. This lets us define potential handler configurations per-event.|
