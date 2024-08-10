# IndustryData-TimePeriod.Read.All

> Allows the app to read time period definitions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/inboundFlows/{inboundFlowId}/year](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/years](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/years/{yearTimePeriodDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-yeartimeperioddefinition-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c9d51f28-8ccd-42b2-a836-fd8fe9ebf2ae|
|**Consent Type**|Admin|
|**Display String**|Read time period definitions|
|**Description**|Allows the app to read time period definitions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7c55c952-b095-4c23-a522-022bce4cc1e3|
|**Display String**|Read time period definitions|
|**Description**|Allows the app to read time period definitions without a signed-in user.|
## Resources
### [yearTimePeriodDefinition ](https://docs.microsoft.com/graph/api/resources/industrydata-yeartimeperioddefinition?view=graph-rest-1.0&tabs=http)
| Property    | Type                                                                                  | Description                                                                                             |
| :---------- | :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------ |
| displayName | String                                                                                | The name of the year. Maximum supported length is 100 characters.                                       |
| endDate     | Date                                                                                  | The last day of the year using ISO 8601 format for date.                                                |
| startDate   | Date                                                                                  | The first day of the year using ISO 8601 format for date.                                               |
| year        | microsoft.graph.industryData.yearReferenceValue | A pointer to a year entry in the referenceDefinition collection. |
