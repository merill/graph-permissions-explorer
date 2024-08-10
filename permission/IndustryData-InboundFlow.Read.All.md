# IndustryData-InboundFlow.Read.All

> Allows the app to read inbound data flows on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/inboundFlows](https://docs.microsoft.com/graph/api/industrydata-inboundflow-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/inboundFlows/{inboundFlowId}](https://docs.microsoft.com/graph/api/industrydata-inboundflow-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|cb0774da-a605-42af-959c-32f438fb38f4|
|**Consent Type**|Admin|
|**Display String**|View inbound flow definitions|
|**Description**|Allows the app to read inbound data flows on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|305f6ba2-049a-4b1b-88bb-fe7e08758a00|
|**Display String**|View inbound flow definitions|
|**Description**|Allows the app to read inbound data flows without a signed-in user.|
## Resources
### [inboundFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-inboundflow?view=graph-rest-1.0&tabs=http)
| Property           | Type            | Description                                                                                                                                                                                                                                            |
| :----------------- | :-------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dataDomain         | microsoft.graph.industryData.inboundDomain   | The category of data that this flow imports. The possible values are: `educationRostering`, `unknownFutureValue`.                                                                                                                                |
| displayName        | String          | The name of the activity. Inherited from industryDataActivity.                                                                                                                                                 |
| effectiveDateTime  | DateTimeOffset  | The start of the time window when the flow is allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.             |
| expirationDateTime | DateTimeOffset  | The end of the time window when the flow is allowed to run. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.               |
| readinessStatus    | microsoft.graph.industryData.readinessStatus | The state of the activity from its creation through when it is ready to do work. Inherited from industryDataActivity. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
