# LearningContent.Read.All

> Allows the app to read learning content in the organization's directory, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /employeeExperience/learningProviders/{learningProviderId}/learningContents](https://docs.microsoft.com/graph/api/learningprovider-list-learningcontents?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /employeeExperience/learningProviders/{learningProviderId}/learningContents/{learningContentId}](https://docs.microsoft.com/graph/api/learningcontent-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ea4c1fd9-6a9f-4432-8e5d-86e06cc0da77|
|**Consent Type**|Admin|
|**Display String**|Read learning content|
|**Description**|Allows the app to read learning content in the organization's directory, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|8740813e-d8aa-4204-860e-2a0f8f84dbc8|
|**Display String**|Read all learning content|
|**Description**|Allows the app to read all learning content in the organization's directory, without a signed-in user.|
## Resources
### [learningContent ](https://docs.microsoft.com/graph/api/resources/learningcontent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|additionalTags|String collection|Keywords, topics, and other tags associated with the learning content. Optional.|
|contentWebUrl|String|The content web URL for the learning content. Required.|
|contributors|String collection|The authors, creators, or contributors of the learning content. Optional.|
|createdDateTime|DateTimeOffset|The date and time when the learning content was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Optional.|
|description|String|The description or summary for the learning content. Optional.|
|duration|Duration|The duration of the learning content in seconds. The value is represented in ISO 8601 format for durations. Optional.|
|externalId|String|Unique external content ID for the learning content. Required.|
|format|String|The format of the learning content. For example, `Course`, `Video`, `Book`, `Book Summary`, `Audiobook Summary`. Optional.|
|level|Level|The difficulty level of the learning content. Possible values are: `Beginner`, `Intermediate`, `Advanced`, `unknownFutureValue`. Optional.|
|id|String|The unique identifier for the learning content. Not nullable. Read-only. Inherited from entity.|
|isActive|Boolean|Indicates whether the content is active or not. Inactive content doesn't show up in the UI. The default value is `true`. Optional.|
|isPremium|Boolean|Indicates whether the learning content requires the user to sign-in on the learning provider platform or not. The default value is `false`. Optional.|
|isSearchable|Boolean|Indicates whether the learning content is searchable or not. The default value is `true`. Optional.|
|languageTag|String|The language of the learning content, for example, `en-us` or `fr-fr`. Required.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the learning content was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Optional.|
|numberOfPages|Int32|The number of pages of the learning content, for example, `9`. Optional.|
|skillTags|String collection|The skills tags associated with the learning content. Optional.|
|sourceName|String|The source name of the learning content, such as `LinkedIn Learning` or `Coursera`. Optional.|
|thumbnailWebUrl|String|The URL of learning content thumbnail image. Optional.|
|title|String|The title of the learning content. Required.|
