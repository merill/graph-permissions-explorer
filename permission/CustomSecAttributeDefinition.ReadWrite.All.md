# CustomSecAttributeDefinition.ReadWrite.All

> Allows the app to read and write custom security attribute definitions for the tenant on behalf of a signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /directory/attributeSets](https://docs.microsoft.com/graph/api/directory-list-attributesets?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/attributeSets/{attributeSetId}](https://docs.microsoft.com/graph/api/attributeset-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/customSecurityAttributeDefinitions](https://docs.microsoft.com/graph/api/directory-list-customsecurityattributedefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/customSecurityAttributeDefinitions/{customSecurityAttributeDefinitionId}](https://docs.microsoft.com/graph/api/customsecurityattributedefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/customSecurityAttributeDefinitions/{customSecurityAttributeDefinitionId}/allowedValues](https://docs.microsoft.com/graph/api/customsecurityattributedefinition-list-allowedvalues?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/customSecurityAttributeDefinitions/{customSecurityAttributeDefinitionId}/allowedValues/{allowedValueId}](https://docs.microsoft.com/graph/api/allowedvalue-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /directory/attributeSets/{attributeSetId}](https://docs.microsoft.com/graph/api/attributeset-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /directory/customSecurityAttributeDefinitions/{customSecurityAttributeDefinitionId}](https://docs.microsoft.com/graph/api/customsecurityattributedefinition-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /directory/customSecurityAttributeDefinitions/{customSecurityAttributeDefinitionId}/allowedValues/{allowedValueId}](https://docs.microsoft.com/graph/api/allowedvalue-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directory/attributeSets](https://docs.microsoft.com/graph/api/directory-post-attributesets?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directory/customSecurityAttributeDefinitions](https://docs.microsoft.com/graph/api/directory-post-customsecurityattributedefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directory/customSecurityAttributeDefinitions/{customSecurityAttributeDefinitionId}/allowedValues](https://docs.microsoft.com/graph/api/customsecurityattributedefinition-post-allowedvalues?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8b0160d4-5743-482b-bb27-efc0a485ca4a|
|**Consent Type**|Admin|
|**Display String**|Read and write custom security attribute definitions|
|**Description**|Allows the app to read and write custom security attribute definitions for the tenant on behalf of a signed in user.|
## Application Permission
|||
|-|-|
|**Id**|12338004-21f4-4896-bf5e-b75dfaf1016d|
|**Display String**|Read and write custom security attribute definitions|
|**Description**|Allows the app to read and write custom security attribute definitions for the tenant without a signed in user.|
## Resources
### [allowedValue ](https://docs.microsoft.com/graph/api/resources/allowedvalue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| id | String | Identifier for the predefined value. Can be up to 64 characters long and include Unicode characters. Can include spaces, but some special characters aren't allowed. Can't be changed later. Case sensitive. Inherited from entity. |
|isActive|Boolean|Indicates whether the predefined value is active or deactivated. If set to `false`, this predefined value can't be assigned to any other supported directory objects.|
### [attributeSet ](https://docs.microsoft.com/graph/api/resources/attributeset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Description of the attribute set. Can be up to 128 characters long and include Unicode characters. Can be changed later.|
|id|String|Identifier for the attribute set that is unique within a tenant. Can be up to 32 characters long and include Unicode characters. Cannot contain spaces or special characters. Cannot be changed later. Case insensitive. Inherited from entity.|
|maxAttributesPerSet|Int32|Maximum number of custom security attributes that can be defined in this attribute set. Default value is `null`. If not specified, the administrator can add up to the maximum of 500 active attributes per tenant. Can be changed later.|
### [customSecurityAttributeDefinition ](https://docs.microsoft.com/graph/api/resources/customsecurityattributedefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attributeSet|String|Name of the attribute set. Case insensitive.|
|description|String|Description of the custom security attribute. Can be up to 128 characters long and include Unicode characters. Can be changed later.|
|id|String|Identifier of the custom security attribute that is a combination of the attribute set name and the custom security attribute name separated by an underscore (`attributeSet`_`name`). The **id** property is auto generated and cannot be set. Case insensitive. Inherited from entity.|
|isCollection|Boolean|Indicates whether multiple values can be assigned to the custom security attribute. Cannot be changed later. If **type** is set to `Boolean`, **isCollection** cannot be set to `true`.|
|isSearchable|Boolean|Indicates whether custom security attribute values are indexed for searching on objects that are assigned attribute values. Cannot be changed later.|
|name|String|Name of the custom security attribute. Must be unique within an attribute set. Can be up to 32 characters long and include Unicode characters. Cannot contain spaces or special characters. Cannot be changed later. Case insensitive.|
|status|String|Specifies whether the custom security attribute is active or deactivated. Acceptable values are: `Available` and `Deprecated`. Can be changed later.|
|type|String|Data type for the custom security attribute values. Supported types are: `Boolean`, `Integer`, and `String`. Cannot be changed later.|
|usePreDefinedValuesOnly|Boolean|Indicates whether only predefined values can be assigned to the custom security attribute. If set to `false`, free-form values are allowed. Can later be changed from `true` to `false`, but cannot be changed from `false` to `true`. If **t
