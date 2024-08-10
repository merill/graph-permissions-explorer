# IndustryData-SourceSystem.Read.All

> Allows the app to read source system definitions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/sourceSystems](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/SourceSystems/{industrySourceSystemId}/sourceSystem](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/sourceSystems/{sourceSystemDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|49b7016c-89ae-41e7-bd6f-b7170c5490bf|
|**Consent Type**|Admin|
|**Display String**|View source system definitions|
|**Description**|Allows the app to read source system definitions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|bc167a60-39fe-4865-8b44-78400fc6ed03|
|**Display String**|View source system definitions|
|**Description**|Allows the app to read source system definitions without a signed-in user.|
## Resources
### [sourceSystemDefinition ](https://docs.microsoft.com/graph/api/resources/industrydata-sourcesystemdefinition?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                               | Description                                                                                        |
| :------------------- | :------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------- |
| displayName          | String                                                                                             | The name of the source system. Maximum supported length is 100 characters.                         |
| userMatchingSettings | microsoft.graph.industryData.userMatchingSetting collection | A collection of user matching settings by roleGroup.                  |
| vendor               | String                                                                                             | The name of the vendor who supplies the source system. Maximum supported length is 100 characters. |
