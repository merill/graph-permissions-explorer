# IndustryData-ReferenceDefinition.ReadWrite.All

> Allows the app to read and write reference definitions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/industryData/referenceDefinitions/{referenceDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-referencedefinition-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/referenceDefinitions](https://docs.microsoft.com/graph/api/industrydata-referencedefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/referenceDefinitions/{referenceDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-referencedefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/referenceDefinitions/{referenceDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-referencedefinition-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/referenceDefinitions](https://docs.microsoft.com/graph/api/industrydata-referencedefinition-post?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|a757d430-be6d-430f-af57-28aabe79d247|
|**Consent Type**|Admin|
|**Display String**|Manage reference definitions|
|**Description**|Allows the app to read and write reference definitions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|bda16293-63d3-45b7-b16b-833841d27d56|
|**Display String**|Manage reference definitions|
|**Description**|Allows the app to read and write reference definitions without a signed-in user.|
## Resources
### [referenceDefinition ](https://docs.microsoft.com/graph/api/resources/industrydata-referencedefinition?view=graph-rest-1.0&tabs=http)
| Property             | Type           | Description                                                                                                                                                                                                                                   |
| :------------------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| code                 | String         | The code value for the definition that must be unique within the **referenceType**.                                                                                                                                                           |
| createdDateTime      | DateTimeOffset | The date and time when the definition was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.               |
| displayName          | String         | A human-readable representation of the reference code value for display in a user interface.                                                                                                                                                                    |
| isDisabled           | Boolean        | Indicates whether the definition is disabled.                                                                                                                                                                                           |
| lastModifiedDateTime | DateTimeOffset | The date and time when the definition was most recently changed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| referenceType        | String         | The categorical type for a collection of enumerated values.                                                                                                                                                                                   |
| sortIndex            | Int32          | The index that specifies the order in which to present the definition to the user. Must be unique within the referenceType.                                                                                                                                                  |
| source               | String         | The standards body or organization source which defined the code.                                                                                                                                                                             |
