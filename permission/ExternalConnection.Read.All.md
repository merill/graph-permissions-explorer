# ExternalConnection.Read.All

> Allows the app to read all external connections on behalf of a signed-in user. The signed-in user must be an administrator.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /external/connections](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /external/connections/{connection-id}/operations/{operation-id}](https://docs.microsoft.com/graph/api/externalconnectors-connectionoperation-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/operations/{connectionOperationId}](https://docs.microsoft.com/graph/api/externalconnectors-connectionoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/schema](https://docs.microsoft.com/graph/api/externalconnectors-schema-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /external/connections/{id}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/connections/{id}/schema](https://docs.microsoft.com/graph/api/externalconnectors-schema-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|a38267a5-26b6-4d76-9493-935b7599116b|
|**Consent Type**|Admin|
|**Display String**|Read all external connections|
|**Description**|Allows the app to read all external connections on behalf of a signed-in user. The signed-in user must be an administrator.|
## Application Permission
|||
|-|-|
|**Id**|1914711b-a1cb-4793-b019-c2ce0ed21b8c|
|**Display String**|Read all external connections|
|**Description**|Allows the app to read all external connections without a signed-in user.|
## Resources
### [connectionOperation ](https://docs.microsoft.com/graph/api/resources/externalconnectors-connectionoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|error|publicError| If `status` is `failed`, provides more information about the error that caused the failure.|
|id|String| Unique identifier for the connectionOperation. Read-only. |
|status|microsoft.graph.externalConnectors.connectionOperationStatus| Indicates the status of the asynchronous operation. Possible values are: `unspecified`, `inprogress`, `completed`, `failed`, `unknownFutureValue`.|
### [externalConnection ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalconnection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| activitySettings  |microsoft.graph.externalConnectors.activitySettings| Collects configurable settings related to activities involving connector content.|
| configuration     |microsoft.graph.externalConnectors.configuration|Specifies additional application IDs that are allowed to manage the connection and to index content in the connection. Optional.|
| connectorId       | String | The Teams app ID. Optional.|
| description       |String|Description of the connection displayed in the Microsoft 365 admin center. Optional.|
| id                |String| Developer-provided unique ID of the connection within the Microsoft Entra tenant. Must be between 3 and 32 characters in length. Must only contain alphanumeric characters. Cannot begin with `Microsoft` or be one of the following values: `None`, `Directory`, `Exchange`, `ExchangeArchive`, `LinkedIn`, `Mailbox`, `OneDriveBusiness`, `SharePoint`, `Teams`, `Yammer`, `Connectors`, `TaskFabric`, `PowerBI`, `Assistant`, `TopicEngine`, `MSFT_All_Connectors`. Required. |
| name              |String|The display name of the connection to be displayed in the Microsoft 365 admin center. Maximum length of 128 characters. Required.|
| searchSettings    |microsoft.graph.externalConnectors.searchSettings|The settings configuring the search experience for content in this connection, such as the display templates for search results.|
| state             |microsoft.graph.externalConnectors.connectionState|Indicates the current state of the connection. Possible values are: `draft`, `ready`, `obsolete`, `limitExceeded`, `unknownFutureValue`.|
### [schema ](https://docs.microsoft.com/graph/api/resources/externalconnectors-schema?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|baseType|String|Must be set to `microsoft.graph.externalConnector.externalItem`. Required.|
|properties|property collection|The properties defined for the items in the connection. The minimum number of properties is one, the maximum is 128.|
