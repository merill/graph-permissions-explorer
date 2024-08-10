# IndustryData-Run.Read.All

> Allows the app to read current and previous IndustryData runs on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/runs](https://docs.microsoft.com/graph/api/industrydata-industrydatarun-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/runs/{industryDataRunId}](https://docs.microsoft.com/graph/api/industrydata-industrydatarun-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/runs/{industryDataRunId}/getStatistics](https://docs.microsoft.com/graph/api/industrydata-industrydatarun-getstatistics?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|92685235-50c4-4702-b2c8-36043db6fa79|
|**Consent Type**|Admin|
|**Display String**|View current and previous runs|
|**Description**|Allows the app to read current and previous IndustryData runs on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|f6f5d10b-3024-4d1d-b674-aae4df4a1a73|
|**Display String**|View current and previous runs|
|**Description**|Allows the app to read current and previous IndustryData runs without a signed-in user.|
## Resources
### [industryDataRun ](https://docs.microsoft.com/graph/api/resources/industrydata-industrydatarun?view=graph-rest-1.0&tabs=http)
| Property      | Type                          | Description                                                                                                                                                                                                                                                   |
| :------------ | :---------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| blockingError | publicError | An error object to diagnose critical failures in the run.                                                                                                                                                                                                     |
| displayName   | String                        | The name of the run for rendering in a user interface.                                                                                                                                                                                                        |
| endDateTime   | DateTimeOffset                | The date and time when the run finished or null if the run is still in-progress. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on `Jan 1, 2014 is 2014-01-01T00:00:00Z`. |
| startDateTime | DateTimeOffset                | The date and time when the run started. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on `Jan 1, 2014 is 2014-01-01T00:00:00Z`.                                          |
| status        | microsoft.graph.industryData.industryDataRunStatus         | The current status of the run. The possible values are: `running`, `failed`, `completed`, `completedWithErrors`, `completedWithWarnings`, `unknownFutureValue`.                                                                                               |
### [industryDataRunStatistics ](https://docs.microsoft.com/graph/api/resources/industrydata-industrydatarunstatistics?view=graph-rest-1.0&tabs=http)
| Property           | Type                                                                                                                     | Description                                                                                                                                                    |
| :----------------- | :----------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| activityStatistics | microsoft.graph.industryData.industryDataActivityStatistics collection | The collection of statistics for each activity included in this run.                                                                                           |
| inboundTotals      | microsoft.graph.industryData.aggregatedInboundStatistics                  | The aggregate statistics for all inbound flows.                                                                                                                |
| runId              | String                                                                                                                   | The ID of the underlying run for the statistics.                                                                                                               |
| status             | microsoft.graph.industryData.industryDataRunStatus                                                                                                    | The latest status of the run. The possible values are: `running`, `failed`, `completed`, `completedWithErrors`, `completedWithWarnings`, `unknownFutureValue`. |
