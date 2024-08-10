# Bookmark.Read.All

> Allows an app to read all bookmarks that the signed-in user can access.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[POST /search/query](https://docs.microsoft.com/graph/api/search-query?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|98b17b35-f3b1-4849-a85f-9f13733002f0|
|**Consent Type**|User|
|**Display String**|Read all bookmarks that the user can access|
|**Description**|Allows an app to read all bookmarks that the signed-in user can access.|
## Application Permission
|||
|-|-|
|**Id**|be95e614-8ef3-49eb-8464-1c9503433b86|
|**Display String**|Read all bookmarks|
|**Description**|Allows an app to read all bookmarks without a signed-in user.|
## Resources
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
