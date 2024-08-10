# IndustryData-DataConnector.ReadWrite.All

> Allows the app to read and write data connectors on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/industryData/dataConnectors/{industryDataConnectorId}](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/dataConnectors](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/dataConnectors/{industryDataConnectorId}](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/dataConnectors/{industryDataConnectorId}/microsoft.graph.industryData.azureDataLakeConnector/getUploadSession](https://docs.microsoft.com/graph/api/industrydata-azuredatalakeconnector-getuploadsession?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/inboundFlows/{inboundFlowId}/dataConnector](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/dataConnectors/{industryDataConnectorId}](https://docs.microsoft.com/graph/api/industrydata-onerosterapidataconnector-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/dataConnectors](https://docs.microsoft.com/graph/api/industrydata-onerosterapidataconnector-post?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/dataConnectors/{industryDataConnectorId}/validate](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-validate?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/inboundFlows/{inboundFlowId}/dataConnector/validate](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-validate?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5ce933ac-3997-4280-aed0-cc072e5c062a|
|**Consent Type**|Admin|
|**Display String**|Manage data connector definitions|
|**Description**|Allows the app to read and write data connectors on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|eda0971c-482e-4345-b28f-69c309cb8a34|
|**Display String**|Manage data connector definitions|
|**Description**|Allows the app to read and write data connectors without a signed-in user.|
## Resources
### [apiDataConnector ](https://docs.microsoft.com/graph/api/resources/industrydata-apidataconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| apiFormat   | microsoft.graph.industryData.apiFormat                                             | The API format of the external system being connected to. The possible values are: `oneRoster`, `unknownFutureValue`.                          |
| baseUrl     | String                                                                             | The base URL, including the scheme, host, and path for the API, with or without a trailing '/'. For example, "https://example.com/ims/oneRoster/v1p1"              |
| credential  | microsoft.graph.industryData.credential | A credential to use to connect to the API.                                                                                                               |
| displayName | String                                                                             | The name of the data connector. Inherited from industryDataConnector. |
### [azureDataLakeConnector ](https://docs.microsoft.com/graph/api/resources/industrydata-azuredatalakeconnector?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                                                |
| :---------- | :----- | :--------------------------------------------------------------------------------------------------------- |
| displayName | String | The name of the data connector. Inherited from industryDataConnector. |
| fileFormat  |microsoft.graph.industryData.fileFormatReferenceValue|The file format that external systems can upload using this connector.|
### [industryData credential ](https://docs.microsoft.com/graph/api/resources/industrydata-credential?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| displayName       | String         | The name of the credential.                                                           |
| isValid           | Boolean        | Indicates whether the credential provided is valid based on the last data connector validate operation. |
| lastValidDateTime | DateTimeOffset | The time that the credential was last successfully validated by the data connector validate operation.                                  |
### [fileFormatReferenceValue ](https://docs.microsoft.com/graph/api/resources/industrydata-fileformatreferencevalue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| code | String | The code of the desired referenceDefinition entry. Inherited from referenceValue.The possible values are: `schoolDataSyncV1`, `schoolDataSyncV2Rev1` |
### [fileUploadSession ](https://docs.microsoft.com/graph/api/resources/industrydata-fileuploadsession?view=graph-rest-1.0&tabs=http)
| Property                    | Type           | Description                                               |
| :-------------------------- | :------------- | :-------------------------------------------------------- |
| containerExpirationDateTime | DateTimeOffset | The expiration date and time for the container. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.          |
| containerId                 | String         | The container ID where the files are uploaded.            |
| sessionExpirationDateTime   | DateTimeOffset | The expiration date and time for the file upload session. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| sessionUrl                  | String         | The Azure Storage SAS URI to upload source files to.      |
### [industryDataConnector ](https://docs.microsoft.com/graph/api/resources/industrydata-industrydataconnector?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                 |
| :---------- | :----- | :-------------------------------------------------------------------------- |
| displayName | String | The name of the data connector. Maximum supported length is 100 characters. |
### [oneRosterApiDataConnector ](https://docs.microsoft.com/graph/api/resources/industrydata-onerosterapidataconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| apiFormat             | microsoft.graph.industryData.apiFormat                                             | The API format of the external system being connected to. Inherited from apiDataConnector.The possible values are: `oneRoster`, `unknownFutureValue`.           |
| apiVersion            | String                                                                             | The API version of the OneRoster source. Example: 1.1, 1.2                                                                                                                                                                                       |
| baseUrl               | String                                                                             | The base URL including the scheme, host, and path for the API (with or without a trailing '/'). Example: https://example.com/ims/oneRoster/v1p1. Inherited from apiDataConnector. |
| credential            | microsoft.graph.industryData.credential | The base type for all supported credentials. Inherited from apiDataConnector.                                                                    |
| displayName           | String                                                                             | The name of the data connector. Inherited from industryDataConnector.                                                                                                        |
| isContactsEnabled     | Boolean                                                                            | Indicates whether the user specified to import optional contacts data.                                                                                                                                                                                                |
| isDemographicsEnabled | Boolean                                                                            | Indicates whether the user specified to import optional demographics data.                                                                                                                                                                                            |
| isFlagsEnabled        | Boolean                                                                            | Indicates whether the user specified to import optional flags data.                                                                                                                                                                                                   |
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
