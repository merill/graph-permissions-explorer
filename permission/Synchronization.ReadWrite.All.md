# Synchronization.ReadWrite.All

> Allows the app to configure the Azure AD synchronization service, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-validatecredentials?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}/synchronization/jobs/{jobId}/](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /applications/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /applications/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /applications/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/synchronization/templates/{templateId}/schema/filterOperators](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-filteroperators?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/synchronization/templates/{templateId}/schema/functions](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-functions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-jobs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema/filterOperators](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-filteroperators?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema/functions](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-functions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /servicePrincipals/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}/schema/filterOperators](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-filteroperators?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}/schema/functions](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-functions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET applications/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET applications/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET servicePrincipals/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET servicePrincipals/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /applications/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH applications/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{applicationsId}/synchronization/acquireAccessToken](https://docs.microsoft.com/graph/api/synchronization-synchronization-acquireaccesstoken?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/synchronization/jobs/{jobId}/restart](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-restart?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/jobs/](https://docs.microsoft.com/graph/api/synchronization-synchronization-post-jobs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/jobs/{id}/schema/parseExpression](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-parseexpression?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/jobs/{id}/validateCredentials](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-validatecredentials?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/jobs/{jobId}/pause](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-pause?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/jobs/{jobId}/start](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-start?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/templates/{id}/schema/parseExpression](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-parseexpression?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{servicePrincipalId}/synchronization/jobs/{jobId}/restart](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-restart?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{servicePrincipalsId}/synchronization/acquireAccessToken](https://docs.microsoft.com/graph/api/synchronization-synchronization-acquireaccesstoken?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{servicePrincipalsId}/synchronization/jobs/{synchronizationJobId}/provisionOnDemand](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-provisionondemand?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /applications/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /servicePrincipals/{id}/synchronization/secrets](https://docs.microsoft.com/graph/api/synchronization-serviceprincipal-put-synchronization?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7bb27fa3-ea8f-4d67-a916-87715b6188bd|
|**Consent Type**|Admin|
|**Display String**|Read and write all Azure AD synchronization data|
|**Description**|Allows the app to configure the Azure AD synchronization service, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|9b50c33d-700f-43b1-b2eb-87e89b703581|
|**Display String**|Read and write all Azure AD synchronization data. |
|**Description**|Allows the application to configure the Azure AD synchronization service, without a signed-in user.|
## Resources
### [attributeDefinition ](https://docs.microsoft.com/graph/api/resources/synchronization-attributedefinition?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|anchor         |Boolean    | `true` if the attribute should be used as the anchor for the object. Anchor attributes must have a unique value identifying an object, and must be immutable. Default is `false`. One, and only one, of the object's attributes must be designated as the anchor to support synchronization. |
|caseExact      |Boolean    |`true` if value of this attribute should be treated as case-sensitive. This setting affects how the synchronization engine detects changes for the attribute.|
|defaultValue   |String     |The default value of the attribute.|
|flowNullValues |Boolean    |'true' to allow null values for attributes.|
|metadata       |attributeDefinitionMetadataEntry collection   |Metadata for the given object.|
|multivalued    |Boolean    |`true` if an attribute can have multiple values. Default is `false`.|
|mutability     |mutability     |An attribute's mutability. Possible values are:  `ReadWrite`, `ReadOnly`, `Immutable`, `WriteOnly`. Default is `ReadWrite`.|
|name           |String     |Name of the attribute. Must be unique within the object definition. Not nullable.|
|required       |Boolean    |`true` if attribute is required. Object can not be created if any of the required attributes are missing. If during synchronization, the required attribute has no value, the default value will be used. If default the value was not set, synchronization will record an error.|
|referencedObjects|referencedObject collection |For attributes with `reference` type, lists referenced objects (for example, the `manager` attribute would list `User` as the referenced object).|
|type           |attributeType     |Attribute value type. Possible values are: `String`, `Integer`, `Reference`, `Binary`, `Boolean`,`DateTime`. Default is `String`.|
### [attributeMappingFunctionSchema ](https://docs.microsoft.com/graph/api/resources/synchronization-attributemappingfunctionschema?view=graph-rest-1.0&tabs=http)
| Property                   | Type                      | Description    |
|:---------------------------|:-------------------------|:---------------|
|id                        |String                    |Key. Read-only. |
|parameters                  |attributeMappingParameterSchema collection  |Collection of function parameters.|
### [attributeMappingSource ](https://docs.microsoft.com/graph/api/resources/synchronization-attributemappingsource?view=graph-rest-1.0&tabs=http)
| Property              | Type                      | Description               |
|:----------------------|:--------------------------|:--------------------------|
|expression             |String                     |Equivalent expression representation of this **attributeMappingSource** object.|
|name                   |String                     |Name parameter of the mapping source. Depending on the **type** property value, this can be the name of the function, the name of the source attribute, or a constant value to be used. |
|parameters             |stringKeyAttributeMappingSourceValuePair collection | If this object represents a function, lists function parameters. Parameters consist of **attributeMappingSource** objects themselves, allowing for complex expressions. If **type** isn't `Function`, this property is null/empty array. |
|type                   | attributeMappingSourceType                    |The type of this attribute mapping source. Possible values are: `Attribute`, `Constant`, `Function`. Default is `Attribute`.|
### [expressionInputObject ](https://docs.microsoft.com/graph/api/resources/synchronization-expressioninputobject?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|definition|objectDefinition|Definition of the test object.|
|properties|stringKeyObjectValuePair collection|Property values of the test object.|
### [filter ](https://docs.microsoft.com/graph/api/resources/synchronization-filter?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|categoryFilterGroups|filterGroup collection|`*Experimental*` Filter group set used to decide whether given object belongs and should be processed as part of this object mapping. An object is considered in scope *if ANY of the groups in the collection is evaluated to `true`*.|
|groups|filterGroup collection|Filter group set used to decide whether given object is in scope for provisioning. **This is the filter which should be used in most cases**. If an object used to satisfy this filter at a given moment, and then the object or the filter was changed so that filter isn't satisfied any longer, such object *will get deprovisioned". An object is considered in scope *if ANY of the groups in the collection is evaluated to `true`*.|
|inputFilterGroups|filterGroup collection|`*Experimental*` Filter group set used to filter out objects at the early stage of reading them from the directory. If an object doesn't satisfy this filter, then it will not be processed further. Important to understand is that if an object used to satisfy this filter at a given moment, and then the object or the filter was changed so that filter is no longer satisfied, such object *w
### [filterOperatorSchema ](https://docs.microsoft.com/graph/api/resources/synchronization-filteroperatorschema?view=graph-rest-1.0&tabs=http)
| Property                   | Type                      | Description    |
|:---------------------------|:--------------------------|:---------------|
|arity                       |scopeOperatorType          |Arity of the operator. Possible values are: `Binary`, `Unary`. The default is `Binary`.|
|multivaluedComparisonType   |scopeOperatorMultiValuedComparisonType          |Possible values are: `All`, `Any`. Applies only to multivalued attributes. `All` means that all values must satisfy the condition. `Any` means that at least one value has to satisfy the condition. The default is `All`.|
|name                        |String                     |Operator name. |
|supportedAttributeTypes     |attributeType collection         |Attribute types supported by the operator. Possible values are: `Boolean`, `Binary`, `Reference`, `Integer`, `String`.|
### [parseExpressionResponse ](https://docs.microsoft.com/graph/api/resources/synchronization-parseexpressionresponse?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|error|publicError|Error details, if expression evaluation resulted in an error.|
|evaluationResult|String collection|A collection of values produced by the evaluation of the expression.|
|evaluationSucceeded|Boolean|`true` if the evaluation was successful.|
|parsedExpression|attributeMappingSource|An attributeMappingSource object representing the parsed expression.|
|parsingSucceeded|Boolean|`true` if the expression was parsed successfully.|
### [synchronizationJob ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationjob?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|id             |String                     |Unique synchronization job identifier. Read-only.|
|schedule       |synchronizationSchedule|Schedule used to run the job. Read-only.|
|status         |synchronizationStatus     |Status of the job, which includes when the job was last run, current job state, and errors.|
|synchronizationJobSettings   |keyValuePair    |Settings associated with the job. Some settings are inherited from the template.|
|templateId     |String    |Identifier of the synchronization template this job is based on.|
### [synchronizationJobApplicationParameters ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationjobapplicationparameters?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|ruleId|String|The identifier of the synchronizationRule to be applied. This rule ID is defined in the schema for a given synchronization job or template. |
|subjects|synchronizationJobSubject collection|The identifiers of one or more objects to which a synchronizationJob is to be applied.|
### [synchronizationJobRestartCriteria ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationjobrestartcriteria?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|resetScope|synchronizationJobRestartScope| Comma-separated combination of the following values: `None`, `ConnectorDataStore`, `Escrows`, `Watermark`, `QuarantineState`, `Full`, `ForceDeletes`. The property can also be empty. <br/> <ol><li> `None`: Starts a paused or quarantined provisioning job. **D
### [synchronizationSchema ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationschema?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|id|String|Unique identifier for the schema.|
|synchronizationRules   |synchronizationRule collection   |A collection of synchronization rules configured for the synchronizationJob or synchronizationTemplate. |
|version                |String                             |The version of the schema, updated automatically with every schema change.|
### [synchronizationSecretKeyStringValuePair ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationsecretkeystringvaluepair?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|key|synchronizationSecret| Possible values are: `None`, `UserName`, `Password`, `SecretToken`, `AppKey`, `BaseAddress`, `ClientIdentifier`, `ClientSecret`, `SingleSignOnType`, `Sandbox`, `Url`, `Domain`, `ConsumerKey`, `ConsumerSecret`, `TokenKey`, `TokenExpiration`, `Oauth2AccessToken`, `Oauth2AccessTokenCreationTime`, `Oauth2RefreshToken`, `SyncAll`, `InstanceName`, `Oauth2ClientId`, `Oauth2ClientSecret`, `CompanyId`, `UpdateKeyOnSoftDelete`, `SynchronizationSchedule`, `SystemOfRecord`, `SandboxName`, `EnforceDomain`, `SyncNotificationSettings`, `SkipOutOfScopeDeletions`, `Oauth2AuthorizationCode`, `Oauth2RedirectUri`, `ApplicationTemplateIdentifier`, `Oauth2TokenExchangeUri`, `Oauth2AuthorizationUri`, `AuthenticationType`, `Server`, `PerformInboundEntitlementGrants`, `HardDeletesEnabled`, `SyncAgentCompatibilityKey`, `SyncAgentADContainer`, `ValidateDomain`, `TestReferences`, `ConnectionString`.|
|value|String|The value of the secret.|
### [synchronizationTemplate ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationtemplate?view=graph-rest-1.0&tabs=http)
| Property      | Type                      | Description                  |
|:--------------|:--------------------------|:-----------------------------|
|id             |String                     |Unique template identifier.|
|applicationId  |String                     |Identifier of the application this template belongs to.|
|default        |Boolean                    |`true` if this template is recommended to be the default for the application.|
|description    |String                     |Description of the template.|
|discoverable   |String                     |`true` if this template should appear in the collection of templates available for the application instance (service principal).|
|factoryTag     |String                     |One of the well-known factory tags supported by the synchronization engine. The **factoryTag** tells the synchronization engine which implementation to use when processing jobs based on this template.|
|metadata       |synchronizationMetadataEntry collection  |Additional extension properties. Unless mentioned explicitly, metadata values should not be changed.|
