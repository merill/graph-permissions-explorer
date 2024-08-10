# IndustryData.ReadBasic.All

> Allows the app to read basic Industry Data service and resource information on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/operations](https://docs.microsoft.com/graph/api/industrydata-filevalidateoperation-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/operations/{fileValidateOperationId}](https://docs.microsoft.com/graph/api/industrydata-filevalidateoperation-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/referenceDefinitions](https://docs.microsoft.com/graph/api/industrydata-referencedefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/roleGroups](https://docs.microsoft.com/graph/api/industrydata-rolegroup-list?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|60382b96-1f5e-46ea-a544-0407e489e588|
|**Consent Type**|User|
|**Display String**|Read basic Industry Data service and resource definitions|
|**Description**|Allows the app to read basic Industry Data service and resource information on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|4f5ac95f-62fd-472c-b60f-125d24ca0bc5|
|**Display String**|View basic service and resource information|
|**Description**|Allows the app to read basic service and resource information without a signed-in user.|
## Resources
### [fileValidateOperation ](https://docs.microsoft.com/graph/api/resources/industrydata-filevalidateoperation?view=graph-rest-1.0&tabs=http)
| Property           | Type                                                     | Description                                                                                                                                                                                                              |
| :----------------- | :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| createdDateTime    | DateTimeOffset                                           | The date and time when this operation was created. Inherited from validateOperation.                                                                                   |
| errors             | microsoft.graph.publicError collection | Set of errors discovered through validation. Inherited from validateOperation.                                                                                         |
| id                 | String                                                   | The unique identifier for the operation. Inherited from validateOperation.                                                                                             |
| lastActionDateTime | DateTimeOffset                                           | The date and time when the last action was run on this operation. Inherited from validateOperation.                                                                    |
| resourceLocation   | String                                                   | The canonical URL of the resource. Inherited from validateOperation.                                                                                                   |
| status             | longRunningOperationStatus                               | The status of the long-running operation. Inherited from validateOperation. Possible values are: `notStarted`, `running`, `succeeded`, `failed`, `unknownFutureValue`. |
| statusDetail       | String                                                   | The detail about the status value. Inherited from validateOperation.                                                                                                   |
| validatedFiles     | String collection                                        | Set of files validated by the validate operation.                                                                                                                                                                        |
| warnings           | microsoft.graph.publicError collection | Set of warnings discovered through validation. Inherited from validateOperation.                                                                                       |
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
### [roleGroup ](https://docs.microsoft.com/graph/api/resources/industrydata-rolegroup?view=graph-rest-1.0&tabs=http)
| Property    | Type                                                                                             | Description                                  |
| :---------- | :----------------------------------------------------------------------------------------------- | :------------------------------------------- |
| displayName | String                                                                                           | The name of the role group.                  |
| roles       | microsoft.graph.industryData.roleReferenceValue collection | The set of roles included in the role group. |
