# IndustryData-DataConnector.Read.All

> Allows the app to read data connectors on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/dataConnectors](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/dataConnectors/{industryDataConnectorId}](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/inboundFlows/{inboundFlowId}/dataConnector](https://docs.microsoft.com/graph/api/industrydata-industrydataconnector-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|d19c0de5-7ecb-4aba-b090-da35ebcd5425|
|**Consent Type**|Admin|
|**Display String**|View data connector definitions|
|**Description**|Allows the app to read data connectors on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7ab52c2f-a2ee-4d98-9ebc-725e3934aae2|
|**Display String**|View data connector definitions|
|**Description**|Allows the app to read data connectors without a signed-in user.|
## Resources
### [industryDataConnector ](https://docs.microsoft.com/graph/api/resources/industrydata-industrydataconnector?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                 |
| :---------- | :----- | :-------------------------------------------------------------------------- |
| displayName | String | The name of the data connector. Maximum supported length is 100 characters. |
