# IdentityUserFlow.Read.All

> Allows the app to read your organization's user flows, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /identity/b2cUserFlows](https://docs.microsoft.com/graph/api/identitycontainer-list-b2cuserflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{b2cIdentityUserFlowId}/userAttributeAssignments/getOrder](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-getorder?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}](https://docs.microsoft.com/graph/api/b2cidentityuserflow-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages](https://docs.microsoft.com/graph/api/b2cidentityuserflow-list-languages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/defaultPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-defaultpages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/defaultPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/overridesPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-overridespages?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/languages/{id}/overridesPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/userAttributeAssignments](https://docs.microsoft.com/graph/api/b2cidentityuserflow-list-userattributeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/b2cUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows](https://docs.microsoft.com/graph/api/identitycontainer-list-b2xuserflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{b2xIdentityUserFlowId}/userAttributeAssignments/getOrder](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-getorder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}](https://docs.microsoft.com/graph/api/b2xidentityuserflow-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages](https://docs.microsoft.com/graph/api/b2xidentityuserflow-list-languages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/defaultPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-defaultpages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/defaultPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/overridesPages](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-list-overridespages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/languages/{id}/overridesPages/{id}/$value](https://docs.microsoft.com/graph/api/userflowlanguagepage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/userAttributeAssignments](https://docs.microsoft.com/graph/api/b2xidentityuserflow-list-userattributeassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/b2xUserFlows/{id}/userAttributeAssignments/{id}](https://docs.microsoft.com/graph/api/identityuserflowattributeassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/userFlowAttributes](https://docs.microsoft.com/graph/api/identityuserflowattribute-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/userFlowAttributes/{id}](https://docs.microsoft.com/graph/api/identityuserflowattribute-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identity/userFlows](https://docs.microsoft.com/graph/api/identityuserflow-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identity/userFlows/{id}](https://docs.microsoft.com/graph/api/identityuserflow-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET identity/b2cUserFlows/{id}/languages/{id}](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET identity/b2xUserFlows/{id}/languages/{id}](https://docs.microsoft.com/graph/api/userflowlanguageconfiguration-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|2903d63d-4611-4d43-99ce-a33f3f52e343|
|**Consent Type**|Admin|
|**Display String**|Read all identity user flows|
|**Description**|Allows the app to read your organization's user flows, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|1b0c317f-dd31-4305-9932-259a8b6e8099|
|**Display String**|Read all identity user flows|
|**Description**|Allows the app to read your organization's user flows, without a signed-in user.|
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
