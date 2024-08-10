# IdentityUserFlow.ReadWrite.All

> Allows the app to read or write your organization's user flows, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /identity/b2cUserFlows/{id}](https://docs.microsoft.com/graph/api/b2cidentityuserflow-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identity/b2cUserFlows/{id}/identityProviders/{id}/$ref](https://docs.microsoft.com/graph/api/b2cidentityuserflow-delete-identityproviders?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identity/b2cUserFlows/{id}/languages/{id}](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identity/b2cUserFlows/{id}/languages/{id}/overridesPages/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identity/b2cUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /identity/b2cUserFlows/{userflow-id}/userflowIdentityProviders/{identityProvider-id}/$ref](https://docs.microsoft.com/graph/api/b2cidentityuserflow-delete-userflowidentityproviders?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identity/b2xUserFlows/{id}](https://docs.microsoft.com/graph/api/b2xidentityuserflow-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/b2xUserFlows/{id}/identityProviders/{id}/$ref](https://docs.microsoft.com/graph/api/b2xidentityuserflow-delete-identityproviders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/b2xUserFlows/{id}/languages/{id}/overridesPages/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identity/b2xUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identity/b2xUserFlows/{userflow-id}/userflowIdentityProviders/{id}/$ref](https://docs.microsoft.com/graph/api/b2xidentityuserflow-delete-userflowidentityproviders?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identity/userFlowAttributes/{id}](https://docs.microsoft.com/graph/api/identityuserflowattribute-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identity/userFlows/{id}](https://docs.microsoft.com/graph/api/identityuserflow-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows](https://docs.microsoft.com/graph/api/identitycontainer-list-b2cuserflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{b2cIdentityUserFlowId}/userAttributeAssignments/getOrder](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-getorder?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}](https://docs.microsoft.com/graph/api/b2cidentityuserflow-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/identityProviders](https://docs.microsoft.com/graph/api/b2cidentityuserflow-list-identityproviders?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages](https://docs.microsoft.com/graph/api/b2cidentityuserflow-list-languages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/defaultPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-defaultpages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/defaultPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/overridesPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-overridespages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/overridesPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/userAttributeAssignments](https://docs.microsoft.com/graph/api/b2cidentityuserflow-list-userattributeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{userflow-id}/userflowIdentityProviders](https://docs.microsoft.com/graph/api/b2cidentityuserflow-list-userflowidentityproviders?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows](https://docs.microsoft.com/graph/api/identitycontainer-list-b2xuserflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{b2xIdentityUserFlowId}/userAttributeAssignments/getOrder](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-getorder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}](https://docs.microsoft.com/graph/api/b2xidentityuserflow-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/identityProviders](https://docs.microsoft.com/graph/api/b2xidentityuserflow-list-identityproviders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages](https://docs.microsoft.com/graph/api/b2xidentityuserflow-list-languages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/defaultPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-defaultpages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/defaultPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/overridesPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-overridespages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/overridesPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/userAttributeAssignments](https://docs.microsoft.com/graph/api/b2xidentityuserflow-list-userattributeassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/b2xUserFlows/{userflow-id}/userflowIdentityProviders](https://docs.microsoft.com/graph/api/b2xidentityuserflow-list-userflowidentityproviders?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identity/userFlowAttributes](https://docs.microsoft.com/graph/api/identityuserflowattribute-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/userFlowAttributes/{id}](https://docs.microsoft.com/graph/api/identityuserflowattribute-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/userFlows](https://docs.microsoft.com/graph/api/identityuserflow-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/userFlows/{id}](https://docs.microsoft.com/graph/api/identityuserflow-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET identity/b2cUserFlows/{id}/apiConnectorConfiguration](https://docs.microsoft.com/graph/api/b2cidentityuserflow-get-apiconnectorconfiguration?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET identity/b2cUserFlows/{id}/languages/{id}](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET identity/b2xUserFlows/{id}/apiConnectorConfiguration](https://docs.microsoft.com/graph/api/b2xidentityuserflow-get-apiconnectorconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET identity/b2xUserFlows/{id}/languages/{id}](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /identity/b2cUserFlows/{id}](https://docs.microsoft.com/graph/api/b2cidentityuserflow-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /identity/b2cUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identity/b2xUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /identity/b2xUserFlows/{userflow-id}/userflowIdentityProviders/$ref](https://docs.microsoft.com/graph/api/b2xidentityuserflow-userflowidentityproviders-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /identity/userFlowAttributes/{id}](https://docs.microsoft.com/graph/api/identityuserflowattribute-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /identity/b2cUserFlows](https://docs.microsoft.com/graph/api/identitycontainer-post-b2cuserflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identity/b2cUserFlows/{b2cIdentityUserFlowId}/userAttributeAssignments/setOrder](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-setorder?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identity/b2cUserFlows/{id}/identityProviders/$ref](https://docs.microsoft.com/graph/api/b2cidentityuserflow-post-identityproviders?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identity/b2cUserFlows/{id}/userAttributeAssignments](https://docs.microsoft.com/graph/api/b2cidentityuserflow-post-userattributeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identity/b2cUserFlows/{userflow-id}/userflowIdentityProviders/$ref](https://docs.microsoft.com/graph/api/b2cidentityuserflow-userflowidentityproviders-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identity/b2xUserFlows](https://docs.microsoft.com/graph/api/identitycontainer-post-b2xuserflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/b2xUserFlows/{b2xIdentityUserFlowId}/userAttributeAssignments/setOrder](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-setorder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/b2xUserFlows/{id}/identityProviders/$ref](https://docs.microsoft.com/graph/api/b2xidentityuserflow-post-identityproviders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/b2xUserFlows/{id}/userAttributeAssignments](https://docs.microsoft.com/graph/api/b2xidentityuserflow-post-userattributeassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identity/userFlowAttributes](https://docs.microsoft.com/graph/api/identityuserflowattribute-post?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /identity/userFlows](https://docs.microsoft.com/graph/api/identityuserflow-post-userflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /identity/b2cUserFlows/{b2cUserFlowId}/apiConnectorConfiguration/{step}/$ref](https://docs.microsoft.com/graph/api/b2cidentityuserflow-put-apiconnectorconfiguration?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /identity/b2cUserFlows/{id}/languages/{id}](https://docs.microsoft.com/graph/api/b2cidentityuserflow-put-languages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /identity/b2cUserFlows/{id}/languages/{id}/overridesPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-put?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /identity/b2xUserFlows/{b2xUserFlowId}/apiConnectorConfiguration/{step}/$ref](https://docs.microsoft.com/graph/api/b2xidentityuserflow-put-apiconnectorconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /identity/b2xUserFlows/{id}/languages/{id}/overridesPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-put?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|281892cc-4dbf-4e3a-b6cc-b21029bb4e82|
|**Consent Type**|Admin|
|**Display String**|Read and write all identity user flows|
|**Description**|Allows the app to read or write your organization's user flows, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|65319a09-a2be-469d-8782-f6b07debf789|
|**Display String**|Read and write all identity user flows|
|**Description**|Allows the app to read or write your organization's user flows, without a signed-in user.|
## Resources
### [assignmentOrder ](https://docs.microsoft.com/graph/api/resources/assignmentorder?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|order|String collection|A list of identityUserFlowAttribute object identifiers that determine the order in which attributes should be collected within a user flow.|
### [b2cIdentityUserFlow ](https://docs.microsoft.com/graph/api/resources/b2cidentityuserflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|id|String|The name of the user flow. This is a required value and is immutable after it's created. The name will be prefixed with the value of `B2C_1_` after creation.|
|userFlowType|userFlowType|The type of user flow. The supported values for **userFlowType** are: `signUp`, `signIn`, `signUpOrSignIn`, `passwordReset`, `profileUpdate`, `resourceOwner`.|
|userFlowTypeVersion|Single|The version of the user flow.|
|isLanguageCustomizationEnabled|Boolean|The property that determines whether language customization is enabled within the B2C user flow. Language customization is not enabled by default for B2C user flows.|
|defaultLanguageTag|String|Indicates the default language of the b2cIdentityUserFlow that is used when no `ui_locale` tag is specified in the request. This field is RFC 5646 compliant.|
|apiConnectorConfiguration|userFlowApiConnectorConfiguration|Configuration for enabling an API connector for use as part of the user flow. You can only obtain the value of this object using Get userFlowApiConnectorConfiguration.|
### [b2xIdentityUserFlow ](https://docs.microsoft.com/graph/api/resources/b2xidentityuserflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|apiConnectorConfiguration|userFlowApiConnectorConfiguration|Configuration for enabling an API connector for use as part of the self-service sign-up user flow. You can only obtain the value of this object using Get userFlowApiConnectorConfiguration.|
|id|String|The name of the user flow is a required value and is immutable after it's created. The name will be prefixed with the value of `B2X_1_` after creation.|
|userFlowType|userFlowType|The type of user flow. For self-service sign-up user flows, the value can only be `signUpOrSignIn` and can't be modified after creation.|
|userFlowTypeVersion|Single|The version of the user flow. For self-service sign-up user flows, the version is always `1`.|
### [identityApiConnector ](https://docs.microsoft.com/graph/api/resources/identityapiconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|apiAuthenticationConfigurationBase|The object which describes the authentication configuration details for calling the API. Basic and PKCS 12 client certificate are supported.|
|displayName|String| The name of the API connector. |
|id|String|The randomly generated identifier of the API connector. |
|targetUrl|String| The URL of the API endpoint to call. |
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
### [UserFlow ](https://docs.microsoft.com/graph/api/resources/identityuserflow?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String| The identifier of the user flow. The prefix of **B2C_1_** is added to the value that you provide.|
|userFlowType|userFlowType| Possible values are: `signUp`, `signIn`, `signUpOrSignIn`, `passwordReset`, `profileUpdate`, `resourceOwner`, `unknownFutureValue`.|
|userFlowTypeVersion|Single| This is the version of the user flow type. Each user flow type can have different possible versions such as 1, 1.1 or 2.  |
### [identityUserFlowAttribute ](https://docs.microsoft.com/graph/api/resources/identityuserflowattribute?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|dataType|identityUserFlowAttributeDataType|The data type of the user flow attribute. Can't be modified after the custom user flow attribute is created. The supported values for **dataType** are: `string` , `boolean` , `int64` , `stringCollection` , `dateTime`, `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`, `ne`).|
|displayName|String|The display name of the user flow attribute. <br/><br/> Supports `$filter` (`eq`, `ne`). |
|description|String|The description of the user flow attribute that's shown to the user at the time of sign up.|
|id|String|The identifier of the user flow attribute. Read-only. <br/><br/> Supports `$filter` (`eq`, `ne`). |
|userFlowAttributeType|identityUserFlowAttributeType|The type of the user flow attribute. Read-only. Depending on the type of attribute, the values for this property are `builtIn`, `custom`, `required`, `unknownFutureValue`. <br/><br/> Supports `$filter` (`eq`, `ne`). |
### [identityUserFlowAttributeAssignment ](https://docs.microsoft.com/graph/api/resources/identityuserflowattributeassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the identityUserFlowAttribute within a user flow.|
|id|String|The identifier of the identityUserFlowAttributeAssignment. This identifier is immutable after it's created and is a read-only property.|
|isOptional|Boolean|Determines whether the identityUserFlowAttribute is optional. `true` means the user doesn't have to provide a value. `false` means the user can't complete sign-up without providing a value.|
|requiresVerification|Boolean|Determines whether the identityUserFlowAttribute requires verification, and is only used for verifying the user's phone number or email address.|
|userAttributeValues|userAttributeValuesItem collection|The input options for the user flow attribute. Only applicable when the userInputType is `radioSingleSelect`, `dropdownSingleSelect`, or `checkboxMultiSelect`.|
|userInputType|identityUserFlowAttributeInputType|The input type of the user flow attribute. Possible values are: `textBox`, `dateTimeDropdown`, `radioSingleSelect`, `dropdownSingleSelect`, `emailBox`, `checkboxMultiSelect`.|
### [userAttributeValuesItem ](https://docs.microsoft.com/graph/api/resources/userattributevaluesitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isDefault|Boolean|Determines whether the value is set as the default.|
|name|String|The display name of the property displayed to the user in the user flow.|
|value|String|The value that is set when this item is selected.|
### [userFlowApiConnectorConfiguration ](https://docs.microsoft.com/graph/api/resources/userflowapiconnectorconfiguration?view=graph-rest-1.0&tabs=http)

### [userFlowLanguageConfiguration ](https://docs.microsoft.com/graph/api/resources/userflowlanguageconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The language name to display. This property is read-only.|
|id|String|The identifier of the language. This field is Language ID tag RFC 5646 compliant and must be a documented Language ID.|
|isEnabled|Boolean|Indicates whether the language is enabled within the user flow.|
### [userFlowLanguagePage ](https://docs.microsoft.com/graph/api/resources/userflowlanguagepage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the userFlowLanguage page.|
