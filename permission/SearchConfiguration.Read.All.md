# SearchConfiguration.Read.All

> Allows the app to read search configuration, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /search/acronyms/{acronymsId}](https://docs.microsoft.com/graph/api/search-acronym-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /search/bookmarks/{bookmarksId}](https://docs.microsoft.com/graph/api/search-bookmark-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /search/qnas/{qnaId}](https://docs.microsoft.com/graph/api/search-qna-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /search/acronyms](https://docs.microsoft.com/graph/api/search-searchentity-list-acronyms?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /search/acronyms/{acronymsId}](https://docs.microsoft.com/graph/api/search-acronym-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /search/bookmarks](https://docs.microsoft.com/graph/api/search-searchentity-list-bookmarks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /search/bookmarks/{bookmarksId}](https://docs.microsoft.com/graph/api/search-bookmark-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /search/qnas](https://docs.microsoft.com/graph/api/search-searchentity-list-qnas?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /search/qnas/{qnaId}](https://docs.microsoft.com/graph/api/search-qna-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /search/acronyms/{acronymsId}](https://docs.microsoft.com/graph/api/search-acronym-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /search/bookmarks/{bookmarksId}](https://docs.microsoft.com/graph/api/search-bookmark-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /search/qnas/{qnaId}](https://docs.microsoft.com/graph/api/search-qna-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /search/acronyms](https://docs.microsoft.com/graph/api/search-searchentity-post-acronyms?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /search/bookmarks](https://docs.microsoft.com/graph/api/search-searchentity-post-bookmarks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /search/qnas](https://docs.microsoft.com/graph/api/search-searchentity-post-qnas?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7d307522-aa38-4cd0-bd60-90c6f0ac50bd|
|**Consent Type**|Admin|
|**Display String**|Read your organization's search configuration|
|**Description**|Allows the app to read search configuration, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|ada977a5-b8b1-493b-9a91-66c206d76ecf|
|**Display String**|Read your organization's search configuration|
|**Description**|Allows the app to read search configurations, without a signed-in user.|
## Resources
### [acronym ](https://docs.microsoft.com/graph/api/resources/search-acronym?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|A brief description of the acronym that gives users more information about the acronym and what it stands for. Inherited from searchAnswer.|
|displayName|String|The actual short form or acronym. Inherited from searchAnswer.|
|id|String|The unique identifier (GUID) for the acronym. Inherited from entity.|
|lastModifiedBy|microsoft.graph.identitySet|Details of the user who created or last modified the acronym. Inherited from searchAnswer. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the acronym was created or last edited. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from searchAnswer. Read-only.|
|standsFor|String|What the acronym stands for.|
|state|microsoft.graph.search.answerState|State of the acronym. Possible values are: `published`, `draft`, `excluded`, `unknownFutureValue`.|
|webUrl|String|The URL of the page or website where users can go for more information about the acronym. Inherited from searchAnswer.|
### [answerKeyword ](https://docs.microsoft.com/graph/api/resources/search-answerkeyword?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|keywords|String collection|A collection of keywords used to trigger the search answer.|
|matchSimilarKeywords|Boolean|If `true`, indicates that the search term contains similar words to the keywords that should trigger the search answer.|
|reservedKeywords|String collection|Unique keywords that guarantee the search answer is triggered.|
### [answerVariant ](https://docs.microsoft.com/graph/api/resources/search-answervariant?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The answer variation description that is shown on the search results page.|
|displayName|String|The answer variation name that is displayed in search results.|
|languageTag|String|The country or region that can view this answer variation.|
|platform|microsoft.graph.devicePlatformType|The device or operating system that can view this answer variation. Possible values are: `android`, `androidForWork`, `ios`, `macOS`, `windowsPhone81`, `windowsPhone81AndLater`, `windows10AndLater`, `androidWorkProfile`, `unknown`, `androidASOP`, `androidMobileApplicationManagement`, `iOSMobileApplicationManagement`, `unknownFutureValue`.|
|webUrl|String|The URL link for the answer variation. When users select this answer variation from the search results, they're directed to the specified URL.|
### [search-api-answers-overview](https://docs.microsoft.com/graph/api/resources/search-api-answers-overview?view=graph-rest-1.0&tabs=http)

### [bookmark ](https://docs.microsoft.com/graph/api/resources/search-bookmark?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|availabilityEndDateTime|DateTimeOffset|Date and time when the bookmark stops appearing as a search result. Set as `null` for always available. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|availabilityStartDateTime|DateTimeOffset|Date and time when the bookmark starts to appear as a search result. Set as `null` for always available. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|categories|String collection|Categories commonly used to describe this bookmark. For example, `IT` and `HR`.|
|description|String|The bookmark description that is shown on the search results page. Inherited from searchAnswer.|
|displayName|String|The bookmark name that is displayed in search results. Inherited from searchAnswer.|
|groupIds|String collection|The list of security groups that are able to view this bookmark.|
|isSuggested|Boolean|`True` if this bookmark was suggested to the admin, by a user, or was mined and suggested by Microsoft. Read-only.|
|id|String|The unique identifier (GUID) for the bookmark. Inherited from searchAnswer.|
|keywords|microsoft.graph.search.answerKeyword|Keywords that trigger this bookmark to appear in search results.|
|languageTags|String collection|A list of geographically specific language names in which this bookmark can be viewed. Each language tag value follows the pattern {language}-{region}. For example, `en-us` is English as used in the United States. For the list of possible values, see Supported language tags.|
|lastModifiedBy|microsoft.graph.identitySet|Details of the user who created or last modified the bookmark. Inherited from searchAnswer. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the bookmark was created or last edited. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from searchAnswer. Read-only. |
|platforms|microsoft.graph.devicePlatformType collection|List of devices and operating systems that are able to view this bookmark. Possible values are: `android`, `androidForWork`, `ios`, `macOS`, `windowsPhone81`, `windowsPhone81AndLater`, `windows10AndLater`, `androidWorkProfile`, `unknown`, `androidASOP`, `androidMobileApplicationManagement`, `iOSMobileApplicationManagement`, `unknownFutureValue`.|
|powerAppIds|String collection|List of Power Apps associated with this bookmark. If users add existing Power Apps to a bookmark, they can complete tasks directly on the search results page, such as entering vacation time or reporting expenses.|
|state|microsoft.graph.search.answerState|State of the bookmark. Possible values are: `published`, `draft`, `excluded`, `unknownFutureValue`.|
|targetedVariations|microsoft.graph.search.answerVariant collection|Variations of a bookmark for different countries or devices. Use when you need to show different content to users based on their device, country/region, or both. The date and group settings apply to all variations.|
|webUrl|String|The URL link for the bookmark. When users select this bookmark from the search results, they're directed to the specified URL. Inherited from searchAnswer.|
### [qna ](https://docs.microsoft.com/graph/api/resources/search-qna?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|availabilityEndDateTime|DateTimeOffset|Date and time when the QnA stops appearing as a search result. Set as `null` for always available. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|availabilityStartDateTime|DateTimeOffset|Date and time when the QnA starts to appear as a search result. Set as `null` for always available. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|Answer that is displayed in search results. Inherited from searchAnswer.|
|displayName|String|Question that is displayed in search results. Inherited from searchAnswer.|
|groupIds|String collection|The list of security groups that are able to view this QnA.|
|id|String|The unique identifier (GUID) for the QnA. Inherited from searchAnswer.|
|isSuggested|Boolean| `True` if a user or Microsoft suggested this QnA to the admin. Read-only.|
|keywords|microsoft.graph.search.answerKeyword|Keywords that trigger this QnA to appear in search results.|
|languageTags|String collection|A list of geographically specific language names in which this QnA can be viewed. Each language tag value follows the pattern {language}-{region}. For example, `en-us` is English as used in the United States. For the list of possible values, see Supported language tags. |
|lastModifiedBy|microsoft.graph.identitySet|Details of the user who created or last modified the QnA. Inherited from searchAnswer. Read-only. |
|lastModifiedDateTime|DateTimeOffset| Date and time when the QnA was created or last edited. Inherited from searchAnswer. Read-only.|
|platforms|microsoft.graph.devicePlatformType collection|List of devices and operating systems that are able to view this QnA. Possible values are: `android`, `androidForWork`, `ios`, `macOS`, `windowsPhone81`, `windowsPhone81AndLater`, `windows10AndLater`, `androidWorkProfile`, `unknown`, `androidASOP`, `androidMobileApplicationManagement`, `iOSMobileApplicationManagement`, `unknownFutureValue`.|
|state|microsoft.graph.search.answerState|State of the QnA. Possible values are: `published`, `draft`, `excluded`, `unknownFutureValue`.|
|targetedVariations|microsoft.graph.search.answerVariant collection|Variations of a QnA for different countries or devices. Use when you need to show different content to users based on their device, country/region, or both. The date and group settings apply to all variations.|
|webUrl|String|The URL link for the QnA. When users select this QnA from the search results, they're directed to the specified URL. Inherited from searchAnswer.|
### [searchAnswer ](https://docs.microsoft.com/graph/api/resources/search-searchanswer?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The search answer description that is shown on the search results page.|
|displayName|String|The search answer name that is displayed in search results.|
|id|String|The unique identifier (GUID) for the search answer. Inherited from entity.|
|lastModifiedBy|microsoft.graph.identitySet|Details of the user who created or last modified the search answer. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the search answer was created or last edited. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|webUrl|String|The URL link for the search answer. When users select this search answer from the search results, they are directed to the specified URL.|
