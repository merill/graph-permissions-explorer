# IndustryData-SourceSystem.ReadWrite.All

> Allows the app to read and write source system definitions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/industryData/sourceSystems/{sourceSystemDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/sourceSystems](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/SourceSystems/{industrySourceSystemId}/sourceSystem](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/sourceSystems/{sourceSystemDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/sourceSystems/{sourceSystemDefinitionId}](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/sourceSystems](https://docs.microsoft.com/graph/api/industrydata-sourcesystemdefinition-post?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9599f005-05d6-4ea7-b1b1-4929768af5d0|
|**Consent Type**|Admin|
|**Display String**|Manage source system definitions|
|**Description**|Allows the app to read and write source system definitions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7d866958-e06e-4dd6-91c6-a086b3f5cfeb|
|**Display String**|Manage source system definitions|
|**Description**|Allows the app to read and write source system definitions without a signed-in user.|
## Resources
### [roleGroup ](https://docs.microsoft.com/graph/api/resources/industrydata-rolegroup?view=graph-rest-1.0&tabs=http)
| Property    | Type                                                                                             | Description                                  |
| :---------- | :----------------------------------------------------------------------------------------------- | :------------------------------------------- |
| displayName | String                                                                                           | The name of the role group.                  |
| roles       | microsoft.graph.industryData.roleReferenceValue collection | The set of roles included in the role group. |
### [sourceSystemDefinition ](https://docs.microsoft.com/graph/api/resources/industrydata-sourcesystemdefinition?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                               | Description                                                                                        |
| :------------------- | :------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------- |
| displayName          | String                                                                                             | The name of the source system. Maximum supported length is 100 characters.                         |
| userMatchingSettings | microsoft.graph.industryData.userMatchingSetting collection | A collection of user matching settings by roleGroup.                  |
| vendor               | String                                                                                             | The name of the vendor who supplies the source system. Maximum supported length is 100 characters. |
### [userMatchingSetting ](https://docs.microsoft.com/graph/api/resources/industrydata-usermatchingsetting?view=graph-rest-1.0&tabs=http)
| Property         | Type                                                                                                        | Description                                                                                              |
| :--------------- | :---------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------- |
| matchTarget      | microsoft.graph.industryData.userMatchTargetReferenceValue | The `RefUserMatchTarget` for matching a user from the source with a Microsoft Entra user object. |
| priorityOrder    | Int32                                                                                                       | The priority order to apply when a user has multiple `RefRole` codes assigned.                           |
| sourceIdentifier | microsoft.graph.industryData.identifierTypeReferenceValue   | The `RefIdentifierType` that uniquely identifies a user in the source data.                              |
