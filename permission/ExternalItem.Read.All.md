# ExternalItem.Read.All

> Allow the app to read external datasets and content, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/connections/{connection-id}/items/{item-id}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/groups/{externalGroupId}](https://docs.microsoft.com/graph/api/externalconnectors-externalgroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /external/connections/{connectionsId}/items/{externalItemId}](https://docs.microsoft.com/graph/api/externalconnectors-externalitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /search/query](https://docs.microsoft.com/graph/api/search-query?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|922f9392-b1b7-483c-a4be-0089be7704fb|
|**Consent Type**|Admin|
|**Display String**|Read items in external datasets|
|**Description**|Allow the app to read external datasets and content, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7a7cffad-37d2-4f48-afa4-c6ab129adcc2|
|**Display String**|Read all external items|
|**Description**|Allows the app to read all external items without a signed-in user.|
## Resources
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
### [externalItem ](https://docs.microsoft.com/graph/api/resources/externalconnectors-externalitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|acl|microsoft.graph.externalConnectors.acl collection|An array of access control entries. Each entry specifies the access granted to a user or group. Required.|
|content|microsoft.graph.externalConnectors.externalItemContent|A plain-text  representation of the contents of the item. The text in this property is full-text indexed. Optional.|
|id|String|Developer-provided unique ID of the item within the containing externalConnection. Must be alphanumeric and a maximum of 128 characters. Required.|
|properties|microsoft.graph.externalConnectors.properties|A property bag with the properties of the item. The properties MUST conform to the schema defined for the externalConnection. Required.|
### [search-api-overview](https://docs.microsoft.com/graph/api/resources/search-api-overview?view=graph-rest-1.0&tabs=http)

### [searchRequest ](https://docs.microsoft.com/graph/api/resources/searchrequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description| 
|:-------------|:------------|:------------|
|aggregationFilters|String collection|Contains one or more filters to obtain search results aggregated and filtered to a specific value of a field. Optional.<br>Build this filter based on a prior search that aggregates by the same field. From the response of the prior search, identify the searchBucket that filters results to the specific value of the field, use the string in its **aggregationFilterToken** property, and build an aggregation filter string in the format **"{field}:\\"{aggregationFilterToken}\\""**. <br>If multiple values for the same field need to be provided, use the strings in its **aggregationFilterToken** property and build an aggregation filter string in the format **"{field}:or(\\"{aggregationFilterToken1}\\",\\"{aggregationFilterToken2}\\")"**. <br>For example, searching and aggregating drive items by file type returns a **searchBucket** for the file type `docx` in the response. You can conveniently use the **aggregationFilterToken** returned for this **searchBucket** in a subsequent search query and filter matches down to drive items of the `docx` file type. Example 1 and example 2 show the actual requests and responses.|
|aggregations|aggregationOption collection|Specifies aggregations (also known as refiners) to be returned alongside search results. Optional.|
|collapseProperties|collapseProperty collection|Contains the ordered collection of fields and limit to collapse results. Optional.|
|contentSources|String collection|Contains the connection to be targeted.|
|enableTopResults|Boolean|This triggers hybrid sort for messages : the first 3 messages are the most relevant. This property is only applicable to entityType=`message`. Optional.|
|entityTypes|entityType collection| One or more types of resources expected in the response. Possible values are: `event`, `message`, `driveItem`, `externalItem`, `site`, `list`, `listItem`, `drive`, `chatMessage`, `person`, `acronym`, `bookmark`.  Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `chatMessage`, `person`, `acronym`, `bookmark`. See known limitations for those combinations of two or more entity types that are supported in the same search request. Required.|
|fields|String collection |Contains the fields to be returned for each resource object specified in **entityTypes**, allowing customization of the fields returned by default; otherwise, including additional fields such as custom managed properties from SharePoint and OneDrive, or custom fields in **externalItem** from the content that Microsoft Graph connectors bring in. The **fields** property can use the semantic labels applied to properties. For example, if a property is labeled as title, you can retrieve it using the following syntax: `label_title`. Optional.|
|from|Int32|Specifies the offset for the search results. Offset 0 returns the very first result. Optional.|
|query|searchQuery|Contains the query terms. Required.|
|queryAlterationOptions|searchAlterationOptions|Query alteration options formatted in a JSON blob that contains two optional flags related to spelling correction. Optional. |
|region|String|The geographic location for the search. Required for searches that use application permissions. For details, see Get the region value. |
|resultTemplateOptions|resultTemplateOption collection|Provides the search result template options to render search results from connectors.|
|sharePointOneDriveOptions|sharePointOneDriveOptions|Indicates the kind of contents to be searched when a search is performed using application permissions. Optional.|
|size|Int32|The size of the page to be retrieved. The maximum value is 500. Optional.|
|sortProperties|sortProperty collection|Contains the ordered collection of fields and direction to sort results. There can be at most 5 sort properties in the collection. Optional.|
### [searchResponse ](https://docs.microsoft.com/graph/api/resources/searchresponse?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|hitsContainers|searchHitsContainer collection|A collection of search results.|
|queryAlterationResponse|alterationResponse|Provides information related to spelling corrections in the alteration response.|
|resultTemplates|resultTemplate collection|A dictionary of **resultTemplateIds** and associated values, which include the name and JSON schema of the result templates.|
|searchTerms|String collection|Contains the search terms sent in the initial search query.|
