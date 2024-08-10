# ExternalConnection.ReadWrite.All

> Allows the app to read and write all external connections on behalf of a signed-in user. The signed-in user must be an administrator.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /external/connections/{connectionsId}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /external/connections/{id}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /external/connections](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /external/connections/{connection-id}/operations/{operation-id}](https://docs.microsoft.com/graph/api/externalconnectors-connectionoperation-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/operations/{connectionOperationId}](https://docs.microsoft.com/graph/api/externalconnectors-connectionoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/schema](https://docs.microsoft.com/graph/api/externalconnectors-schema-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /external/connections/{id}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/connections/{id}/schema](https://docs.microsoft.com/graph/api/externalconnectors-schema-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/connections/{connectionId}/schema](https://docs.microsoft.com/graph/api/externalconnectors-schema-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /external/connections/{connectionsId}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /external/connections/{id}](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /external/connections/{id}/schema](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-patch-schema?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /external/connections](https://docs.microsoft.com/graph/api/externalconnectors-external-post-connections?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|bbbbd9b3-3566-4931-ac37-2b2180d9e334|
|**Consent Type**|Admin|
|**Display String**|Read and write all external connections|
|**Description**|Allows the app to read and write all external connections on behalf of a signed-in user. The signed-in user must be an administrator.|
## Application Permission
|||
|-|-|
|**Id**|34c37bc0-2b40-4d5e-85e1-2365cd256d79|
|**Display String**|Read and write all external connections|
|**Description**|Allows the app to read and write all external connections without a signed-in user.|
## Resources
### [configuration ](https://docs.microsoft.com/graph/api/resources/externalconnectors-configuration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authorizedAppIds|String collection|A collection of application IDs for registered Microsoft Entra apps that are allowed to manage the externalConnection and to index content in the externalConnection.|
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
