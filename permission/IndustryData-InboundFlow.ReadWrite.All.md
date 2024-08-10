# IndustryData-InboundFlow.ReadWrite.All

> Allows the app to read and write inbound data flows on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/industryData/inboundFlows/{inboundFlowId}](https://docs.microsoft.com/graph/api/industrydata-inboundflow-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/inboundFlows](https://docs.microsoft.com/graph/api/industrydata-inboundflow-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/inboundFlows/{inboundFlowId}](https://docs.microsoft.com/graph/api/industrydata-inboundflow-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/inboundFlows/{inboundFlowId}](https://docs.microsoft.com/graph/api/industrydata-inboundapiflow-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/inboundFlows](https://docs.microsoft.com/graph/api/industrydata-inboundapiflow-post?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|97044676-2cec-40ee-bd70-38df444c9e70|
|**Consent Type**|Admin|
|**Display String**|Manage inbound flow definitions|
|**Description**|Allows the app to read and write inbound data flows on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|e688c61f-d4c6-4d64-a197-3bcf6ba1d6ad|
|**Display String**|Manage inbound flow definitions|
|**Description**|Allows the app to read and write inbound data flows without a signed-in user.|
## Resources
### [inboundApiFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-inboundapiflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| dataDomain         | microsoft.graph.industryData.inboundDomain   | The category of data that this flow imports. Inherited from inboundFlow.The possible values are: `educationRostering`, `unknownFutureValue`.                                                                                                                     |
| displayName        | String                                       | The name of the activity. Inherited from industryDataActivity.                                                                                                                                                                                                |
| effectiveDateTime  | DateTimeOffset                               | The time when the flow is first allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from inboundFlow. |
| expirationDateTime | DateTimeOffset                               | The time when the flow is no longer allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from inboundFlow.   |
| readinessStatus    | microsoft.graph.industryData.readinessStatus | The state of the activity from its creation through when it is ready to do work. Inherited from industryDataActivity.The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`.                                                 |
### [inboundFileFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-inboundfileflow?view=graph-rest-1.0&tabs=http)
| Property           | Type            | Description                                                                                                                                                                                                                                                                                           |
| :----------------- | :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dataDomain         | microsoft.graph.industryData.inboundDomain   | The category of data that this flow imports. Inherited from inboundFlow. The possible values are: `educationRostering`, `unknownFutureValue`.                                                                                                                    |
| displayName        | String          | The name of the activity. Inherited from industryDataActivity.                                                                                                                                                                                                |
| effectiveDateTime  | DateTimeOffset  | The start of the time window when the flow is allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from inboundFlow. |
| expirationDateTime | DateTimeOffset  | The end of the time window when the flow is allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from inboundFlow.   |
| readinessStatus    | microsoft.graph.industryData.readinessStatus | The state of the activity from its creation through when it is ready to do work. Inherited from industryDataActivity. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`.                                                |
### [inboundFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-inboundflow?view=graph-rest-1.0&tabs=http)
| Property           | Type            | Description                                                                                                                                                                                                                                            |
| :----------------- | :-------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dataDomain         | microsoft.graph.industryData.inboundDomain   | The category of data that this flow imports. The possible values are: `educationRostering`, `unknownFutureValue`.                                                                                                                                |
| displayName        | String          | The name of the activity. Inherited from industryDataActivity.                                                                                                                                                 |
| effectiveDateTime  | DateTimeOffset  | The start of the time window when the flow is allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.             |
| expirationDateTime | DateTimeOffset  | The end of the time window when the flow is allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.               |
| readinessStatus    | microsoft.graph.industryData.readinessStatus | The state of the activity from its creation through when it is ready to do work. Inherited from industryDataActivity. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [industryDataActivity ](https://docs.microsoft.com/graph/api/resources/industrydata-industrydataactivity?view=graph-rest-1.0&tabs=http)
| Property        | Type            | Description                                                                                                                                                               |
| :-------------- | :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| displayName     | String          | The name of the activity. Maximum supported length is 100 characters.                                                                                                                                                 |
| readinessStatus | microsoft.graph.industryData.readinessStatus | The state of the activity from creation through to ready to do work. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [industryDataConnector ](https://docs.microsoft.com/graph/api/resources/industrydata-industrydataconnector?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                 |
| :---------- | :----- | :-------------------------------------------------------------------------- |
| displayName | String | The name of the data connector. Maximum supported length is 100 characters. |
### [yearTimePeriodDefinition ](https://docs.microsoft.com/graph/api/resources/industrydata-yeartimeperioddefinition?view=graph-rest-1.0&tabs=http)
| Property    | Type                                                                                  | Description                                                                                             |
| :---------- | :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------ |
| displayName | String                                                                                | The name of the year. Maximum supported length is 100 characters.                                       |
| endDate     | Date                                                                                  | The last day of the year using ISO 8601 format for date.                                                |
| startDate   | Date                                                                                  | The first day of the year using ISO 8601 format for date.                                               |
| year        | microsoft.graph.industryData.yearReferenceValue | A pointer to a year entry in the referenceDefinition collection. |
