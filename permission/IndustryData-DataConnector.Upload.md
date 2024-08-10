# IndustryData-DataConnector.Upload

> Allows the app to upload data files to a data connector on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/dataConnectors/{industryDataConnectorId}/microsoft.graph.industryData.azureDataLakeConnector/getUploadSession](https://docs.microsoft.com/graph/api/industrydata-azuredatalakeconnector-getuploadsession?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/dataConnectors/{industryDataConnectorId}/validate](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-validate?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/inboundFlows/{inboundFlowId}/dataConnector/validate](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-validate?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|fc47391d-ab2c-410f-9059-5600f7af660d|
|**Consent Type**|Admin|
|**Display String**|Upload files to a data connector|
|**Description**|Allows the app to upload data files to a data connector on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|9334c44b-a7c6-4350-8036-6bf8e02b4c1f|
|**Display String**|Upload files to a data connector|
|**Description**|Allows the app to upload data files to a data connector without a signed-in user.|
## Resources
### [fileUploadSession ](https://docs.microsoft.com/graph/api/resources/industrydata-fileuploadsession?view=graph-rest-1.0&tabs=http)
| Property                    | Type           | Description                                               |
| :-------------------------- | :------------- | :-------------------------------------------------------- |
| containerExpirationDateTime | DateTimeOffset | The expiration date and time for the container. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.          |
| containerId                 | String         | The container ID where the files are uploaded.            |
| sessionExpirationDateTime   | DateTimeOffset | The expiration date and time for the file upload session. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| sessionUrl                  | String         | The Azure Storage SAS URI to upload source files to.      |
