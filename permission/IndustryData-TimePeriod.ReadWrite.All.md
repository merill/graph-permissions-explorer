# IndustryData-TimePeriod.ReadWrite.All

> Allows the app to read and write time period definitions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/industryData/years/{yearTimePeriodDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/inboundFlows/{inboundFlowId}/year](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/years](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/years/{yearTimePeriodDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/years/{yearTimePeriodDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/years](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-post?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b6d56528-3032-4f9d-830f-5a24a25e6661|
|**Consent Type**|Admin|
|**Display String**|Manage time period definitions|
|**Description**|Allows the app to read and write time period definitions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7afa7744-a782-4a32-b8c2-e3db637e8de7|
|**Display String**|Manage time period definitions|
|**Description**|Allows the app to read and write time period definitions without a signed-in user.|
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
### [yearReferenceValue ](https://docs.microsoft.com/graph/api/resources/industrydata-yearreferencevalue?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                                                                                                                          |
| :------- | :----- | :----------------------------------------------------------------------------------------------------------------------------------- |
| code     | String | The code of the desired **r
### [yearTimePeriodDefinition ](https://docs.microsoft.com/graph/api/resources/industrydata-yeartimeperioddefinition?view=graph-rest-1.0&tabs=http)
| Property    | Type                                                                                  | Description                                                                                             |
| :---------- | :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------ |
| displayName | String                                                                                | The name of the year. Maximum supported length is 100 characters.                                       |
| endDate     | Date                                                                                  | The last day of the year using ISO 8601 format for date.                                                |
| startDate   | Date                                                                                  | The first day of the year using ISO 8601 format for date.                                               |
| year        | microsoft.graph.industryData.yearReferenceValue | A pointer to a year entry in the referenceDefinition collection. |
