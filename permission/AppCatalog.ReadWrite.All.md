# AppCatalog.ReadWrite.All

> Allows the app to create, read, update, and delete apps in the app catalogs.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /appCatalogs/teamsApps/{id}](https://docs.microsoft.com/graph/api/teamsapp-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /appCatalogs/teamsApps](https://docs.microsoft.com/graph/api/appcatalogs-list-teamsapps?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /appCatalogs/teamsApps/{app-id}/appDefinitions/{app-definition-id}/bot](https://docs.microsoft.com/graph/api/teamworkbot-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /appCatalogs/teamsApps/{teams-app-id}/appDefinitions/{app-definition-id}/colorIcon](https://docs.microsoft.com/graph/api/teamsappicon-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /appCatalogs/teamsApps/{teams-app-id}/appDefinitions/{app-definition-id}/colorIcon/hostedContent/](https://docs.microsoft.com/graph/api/teamworkhostedcontent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /appCatalogs/teamsApps/{teams-app-id}/appDefinitions/{app-definition-id}/colorIcon/hostedContent/$value](https://docs.microsoft.com/graph/api/teamworkhostedcontent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /appCatalogs/teamsApps/{teams-app-id}/appDefinitions/{app-definition-id}/outlineIcon/hostedContent/](https://docs.microsoft.com/graph/api/teamworkhostedcontent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /appCatalogs/teamsApps/{teams-app-id}/appDefinitions/{app-definition-id}/outlineIcon/hostedContent/$value](https://docs.microsoft.com/graph/api/teamworkhostedcontent-get?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /appCatalogs/teamsApps](https://docs.microsoft.com/graph/api/teamsapp-publish?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /appCatalogs/teamsApps/{id}/appDefinitions](https://docs.microsoft.com/graph/api/teamsapp-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1ca167d5-1655-44a1-8adf-1414072e1ef9|
|**Consent Type**|Admin|
|**Display String**|Read and write to all app catalogs|
|**Description**|Allows the app to create, read, update, and delete apps in the app catalogs.|
## Application Permission
|||
|-|-|
|**Id**|dc149144-f292-421e-b185-5953f2e98d7f|
|**Display String**|Read and write to all app catalogs|
|**Description**|Allows the app to create, read, update, and delete apps in the app catalogs without a signed-in user.|
## Resources
### [teamsApp ](https://docs.microsoft.com/graph/api/resources/teamsapp?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| displayName                | string   | The name of the catalog app provided by the app developer in the Microsoft Teams zip app package. |
| distributionMethod  | teamsAppDistributionMethod     | The method of distribution for the app. Read-only.|
| externalId          | string   | The ID of the catalog provided by the app developer in the Microsoft Teams zip app package. |
| id                  | string   | The app ID generated for the catalog is different from the developer-provided ID found within the Microsoft Teams zip app package. The **e
### [teamsAppDefinition ](https://docs.microsoft.com/graph/api/resources/teamsappdefinition?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| description         | string   | Verbose description of the application. |
| displayName         | string   | The name of the app provided by the app developer. |
| id                  | string   | A unique ID (not the Teams app ID). |
| publishingState| string|The published status of a specific version of a Teams app. Possible values are:</br>`submitted`—The specific version of the Teams app has been submitted and is under review. </br>`published`—The request to publish the specific version of the Teams app has been approved by the admin and the app is published. </br> `rejected`—The admin rejected the request to publish the specific version of the Teams app. |
| shortDescription    | string   | Short description of the application. |
| teamsAppId          | string   | The ID from the Teams app manifest. |
| version             | string   | The version number of the application. |
|authorization|teamsAppAuthorization|Authorization requirements specified in the Teams app manifest.|
### [teamsAppIcon ](https://docs.microsoft.com/graph/api/resources/teamsappicon?view=graph-rest-1.0&tabs=http)
| Property      | Type                        | Description                                                                             |
| :------------ | :-------------------------- | :-------------------------------------------------------------------------------------- |
| id            | string                      | The unique ID of the app icon.                                                          |
| webUrl        | string                      | The web URL that can be used for downloading the image.                                 |
### [teamworkBot ](https://docs.microsoft.com/graph/api/resources/teamworkbot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the bot associated with the specific teamsAppDefinition. This value is usually a GUID.|
### [teamworkHostedContent ](https://docs.microsoft.com/graph/api/resources/teamworkhostedcontent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentBytes|Binary|Write only. Bytes for the hosted content (such as images).|
|contentType|String|Write only. Content type. such as image/png, image/jpg.|
|id|String|ID of the hosted content.|
