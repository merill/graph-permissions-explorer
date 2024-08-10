# ExternalItem.ReadWrite.All

> Allows the app to read and write all external items on behalf of a signed-in user. The signed-in user must be an administrator.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/connections/{connection-id}/items/{item-id}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /external/connections/{connectionId}/groups/{externalGroupId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroup-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /external/connections/{connectionId}/groups/{externalGroupId}/members/{externalGroupMemberId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroupmember-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /external/connections/{connectionId}/groups/{externalGroupId}/members/{identityId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroupmember-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /external/connections/{connectionsId}/groups/{externalGroupId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroup-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /external/connections/{connectionsId}/items/{externalItemId}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /external/connections/{connection-id}/items/{item-id}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/groups/{externalGroupId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/items/{externalItemId}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /external/connections/{connectionsId}/groups/{externalGroupId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroup-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /external/connections/{connectionId}/groups](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-post-groups?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /external/connections/{connectionsId}/groups](https://docs.microsoft.com/graph/api/externalconnectors-externalconnection-post-groups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /external/connections/{connectionsId}/groups/{externalGroupId}/members](https://docs.microsoft.com/graph/api/externalconnectors-externalgroup-post-members?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST external/connections/{connectionsId}/items/{externalItemId}/addActivities](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-addactivities?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /external/connections/{connection-id}/items/{item-id}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b02c54f8-eb48-4c50-a9f0-a149e5a2012f|
|**Consent Type**|Admin|
|**Display String**|Read and write all external items|
|**Description**|Allows the app to read and write all external items on behalf of a signed-in user. The signed-in user must be an administrator.|
## Application Permission
|||
|-|-|
|**Id**|38c3d6ee-69ee-422f-b954-e17819665354|
|**Display String**|Read and write items in external datasets|
|**Description**|Allow the app to read or write items in all external datasets that the app is authorized to access|
## Resources
### [acl ](https://docs.microsoft.com/graph/api/resources/externalconnectors-acl?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessType|microsoft.graph.externalConnectors.accessType|The access granted to the identity. Possible values are: `grant`, `deny`, `unknownFutureValue`.|
|type|microsoft.graph.externalConnectors.aclType|The type of identity. Possible values are: `user`, `group`, `everyone`, `everyoneExceptGuests`, `externalGroup`, `unknownFutureValue`.|
|value|String|The unique identifer of the identity. For Microsoft Entra identities, `value` is set to the object identifier of the user, group or tenant for types user, group and everyone (and everyoneExceptGuests) respectively. For external groups `value` is set to the ID of the externalGroup |
### [externalActivity ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalactivity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|startDateTime|DateTimeOffset|The date and time when the particular activity occurred. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|type|microsoft.graph.externalConnectors.externalActivityType|The type of activity performed. The possible values are: `viewed`, `modified`, `created`, `commented`, `unknownFutureValue`.|
### [externalActivityResult ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalactivityresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|error|microsoft.graph.publicError|Error information that explains the failure to process an external activity.|
|startDateTime|DateTimeOffset|The date and time when the particular activity occurred. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from externalActivity.|
|type|microsoft.graph.externalConnectors.externalActivityType|The type of activity performed. The possible values are: `viewed`, `modified`, `created`, `commented`, `unknownFutureValue`. Inherited from externalActivity.|
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
### [externalGroup ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalgroup?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                                                              |
|:------------|:-------|:-------------------------------------------------------------------------------------------------------------------------|
| description | String | The description of the external group. Optional.      |
| displayName | String | The friendly name of the external group. Optional.                                                                       |
| id          | String | The unique ID of the external group within a connection. It must be alphanumeric and can be up to 128 characters long. |
### [externalGroupMember ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalgroupmember?view=graph-rest-1.0&tabs=http)
| Property       | Type                    | Description                                                          |
|:---------------|:------------------------|:---------------------------------------------------------------------|
| id             | String                  | The unique ID of the member. It would be the objectId for Microsoft Entra users or groups and the **id** property of the **externalGroup** for external groups.                                    |
| type           | microsoft.graph.externalConnectors.externalGroupMemberType | The type of member added to the external group. Possible values are: `user` or `group` when the **identitySource** is `azureActiveDirectory` and just `group` when the **identitySource** is `external`. |
| identitySource | microsoft.graph.externalConnectors.identitySourceType      | The identity source that the member belongs to. Possible values are: `azureActiveDirectory`, `external`.                                                                                         |
### [externalItem ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|acl|microsoft.graph.externalConnectors.acl collection|An array of access control entries. Each entry specifies the access granted to a user or group. Required.|
|content|microsoft.graph.externalConnectors.externalItemContent|A plain-text  representation of the contents of the item. The text in this property is full-text indexed. Optional.|
|id|String|Developer-provided unique ID of the item within the containing externalConnection. Must be alphanumeric and a maximum of 128 characters. Required.|
|properties|microsoft.graph.externalConnectors.properties|A property bag with the properties of the item. The properties MUST conform to the schema defined for the externalConnection. Required.|
### [externalItemContent ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalitemcontent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|type|microsoft.graph.externalConnectors.externalItemContentType|The type of content in the value property. Possible values are: `text`, `html`, `unknownFutureValue`. These are the content types that the indexer supports, and not the file extension types allowed.|
|value|String|The content for the externalItem. Required.|
### [identity ](https://docs.microsoft.com/graph/api/resources/externalconnectors-identity?view=graph-rest-1.0&tabs=http)
| Property       | Type                    | Description                                                          |
|:---------------|:------------------------|:---------------------------------------------------------------------|
| id             | String                  | The unique ID of the identity. It would be the objectId property for Microsoft Entra users or groups and the **id** property of the **externalGroup** in the case of external groups.                                    |
| type           | microsoft.graph.externalConnectors.identityType | The type of identity. Possible values are: `user` or `group` for Microsoft Entra identities and `externalgroup` for groups in an external system. |
### [properties ](https://docs.microsoft.com/graph/api/resources/externalconnectors-properties?view=graph-rest-1.0&tabs=http)

### [schema ](https://docs.microsoft.com/graph/api/resources/externalconnectors-schema?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|baseType|String|Must be set to `microsoft.graph.externalConnector.externalItem`. Required.|
|properties|property collection|The properties defined for the items in the connection. The minimum number of properties is one, the maximum is 128.|
