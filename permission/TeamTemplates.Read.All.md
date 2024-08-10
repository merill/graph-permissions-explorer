# TeamTemplates.Read.All

> Allows the app to read all available Teams Templates, without a signed-user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[GET /teamwork/teamTemplates](https://docs.microsoft.com/graph/api/teamwork-list-teamtemplates?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /teamwork/teamTemplates?$expand=definitions](https://docs.microsoft.com/graph/api/teamtemplate-list-definitions?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /teamwork/teamTemplates/{teamTemplateId}/definitions/{teamTemplateDefinitionID}](https://docs.microsoft.com/graph/api/teamtemplatedefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /teamwork/teamTemplates/{teamTemplateId}/definitions/{teamTemplateDefinitionId}/teamDefinition](https://docs.microsoft.com/graph/api/teamtemplatedefinition-get-teamdefinition?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|6323133e-1f6e-46d4-9372-ac33a0870636|
|**Display String**|Read all available Teams Templates|
|**Description**|Allows the app to read all available Teams Templates, without a signed-user.|
## Resources
### [team ](https://docs.microsoft.com/graph/api/resources/team?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| id | string | The unique identifier of the team. The group has the same ID as the team. This property is read-only, and is inherited from the base entity type. |
|classification|string| An optional label. Typically describes the data or business sensitivity of the team. Must match one of a pre-configured set in the tenant's directory. |
|classSettings|teamClassSettings |Configure settings of a class. Available only when the team represents a class.|
|createdDateTime|dateTimeOffset|Timestamp at which the team was created.|
|description|string| An optional description for the team. Maximum length: 1024 characters. |
|displayName|string| The name of the team. |
|funSettings|teamFunSettings |Settings to configure use of Giphy, memes, and stickers in the team.|
|guestSettings|teamGuestSettings |Settings to configure whether guests can create, update, or delete channels in the team.|
|internalId | string | A unique ID for the team that has been used in a few places such as the audit log/Office 365 Management Activity API. |
|isArchived|Boolean|Whether this team is in read-only mode. |
|memberSettings|teamMemberSettings |Settings to configure whether members can perform certain actions, for example, create channels and add bots, in the team.|
|messagingSettings|teamMessagingSettings |Settings to configure messaging and mentions in the team.|
|specialization|teamSpecialization| Optional. Indicates whether the team is intended for a particular use case.  Each team specialization has access to unique behaviors and experiences targeted to its use case. |
|summary|teamSummary| Contains summary information about the team, including number of owners, members, and guests. |
|tenantId |string | The ID of the Microsoft Entra tenant. |
|visibility|teamVisibilityType| The visibility of the group and team. Defaults to Public. |
|webUrl|string (readonly) | A hyperlink that will go to the team in the Microsoft Teams client. This is the URL that you get when you right-click a team in the Microsoft Teams client and select **G
### [teamsTemplate ](https://docs.microsoft.com/graph/api/resources/teamstemplate?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| id                  | String   | Unique identifier of the template. Cannot be null. |
### [teamTemplate ](https://docs.microsoft.com/graph/api/resources/teamtemplate?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| id                  | String   | Unique identifier of the template. Cannot be null. |
### [teamTemplateDefinition ](https://docs.microsoft.com/graph/api/resources/teamtemplatedefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|audience|teamTemplateAudience|Describes the audience the team template is available to. The possible values are: `organization`, `user`, `public`, `unknownFutureValue`.|
|categories|String collection|The assigned categories for the team template.|
|description|String|A brief description of the team template as it will appear to the users in Microsoft Teams.|
|displayName|String|The user defined name of the team template.|
|iconUrl|String|The icon url for the team template.|
|id|String|Encoded64 of `templateId` + `audience` + `locale` for the team template. Inherited from entity.|
|languageTag|String|Language the template is available in.|
|lastModifiedBy|identitySet|The identity of the user who last modified the team template.|
|lastModifiedDateTime|DateTimeOffset|The date time of when the team template was last modified.|
|parentTemplateId|String|The `templateId` for the team template|
|publisherName|String|The organization which published the team template.|
|shortDescription|String|A short-description of the team template as it will appear to the users in Microsoft Teams.|
