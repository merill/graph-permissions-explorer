# BrowserSiteLists.Read.All

> Allows an app to read the browser site lists configured for your organization, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /admin/edge/internetExplorerMode/siteLists](https://docs.microsoft.com/graph/api/internetexplorermode-list-sitelists?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/edge/internetExplorerMode/siteLists/{browserSiteListId}](https://docs.microsoft.com/graph/api/browsersitelist-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/edge/internetExplorerMode/siteLists/{browserSiteListId}/sharedCookies](https://docs.microsoft.com/graph/api/browsersitelist-list-sharedcookies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/edge/internetExplorerMode/siteLists/{browserSiteListId}/sharedCookies/{browserSharedCookieId}](https://docs.microsoft.com/graph/api/browsersharedcookie-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/edge/internetExplorerMode/siteLists/{browserSiteListId}/sites](https://docs.microsoft.com/graph/api/browsersitelist-list-sites?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/edge/internetExplorerMode/siteLists/{browserSiteListId}/sites/{browserSiteId}](https://docs.microsoft.com/graph/api/browsersite-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|fb9be2b7-a7fc-4182-aec1-eda4597c43d5|
|**Consent Type**|User|
|**Display String**|Read browser site lists for your organization|
|**Description**|Allows an app to read the browser site lists configured for your organization, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|c5ee1f21-fc7f-4937-9af0-c91648ff9597|
|**Display String**|Read all browser site lists for your organization|
|**Description**|Allows an app to read all browser site lists configured for your organization, without a signed-in user.|
## Resources
### [browserSharedCookie ](https://docs.microsoft.com/graph/api/resources/browsersharedcookie?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|comment|String|The comment for the shared cookie.|
|createdDateTime|DateTimeOffset|The date and time when the shared cookie was created.|
|deletedDateTime|DateTimeOffset|The date and time when the shared cookie was deleted.|
|displayName|String|The name of the cookie.|
|history|browserSharedCookieHistory collection|The history of modifications applied to the cookie.|
|hostOnly|Boolean|Controls whether a cookie is a host-only or domain cookie.|
|hostOrDomain|String|The URL of the cookie.|
|id|String|The unique identifier for the cookie.|
|lastModifiedBy|identitySet|The user who last modified the cookie.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the cookie was last modified.|
|path|String|The path of the cookie.|
|sourceEnvironment|browserSharedCookieSourceEnvironment|Specifies how the cookies are shared between Microsoft Edge and Internet Explorer. The possible values are: `microsoftEdge`, `internetExplorer11`, `both`, `unknownFutureValue`.|
|status|browserSharedCookieStatus|The status of the cookie. The possible values are: `published`, `pendingAdd`, `pendingEdit`, `pendingDelete`, `unknownFutureValue`.|
### [browserSite ](https://docs.microsoft.com/graph/api/resources/browsersite?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowRedirect|Boolean|Controls the behavior of redirected sites. If `true`, indicates that the site will open in Internet Explorer 11 or Microsoft Edge even if the site is navigated to as part of a HTTP or meta refresh redirection chain.|
|comment|String|The comment for the site.|
|compatibilityMode|browserSiteCompatibilityMode|Controls what compatibility setting is used for specific sites or domains. The possible values are: `default`, `internetExplorer8Enterprise`, `internetExplorer7Enterprise`, `internetExplorer11`, `internetExplorer10`, `internetExplorer9`, `internetExplorer8`, `internetExplorer7`, `internetExplorer5`, `unknownFutureValue`.|
|createdDateTime|DateTimeOffset|The date and time when the site was created.|
|deletedDateTime|DateTimeOffset|The date and time when the site was deleted.|
|history|browserSiteHistory collection|The history of modifications applied to the site.|
|id|String|The unique identifier for the site.|
|lastModifiedBy|identitySet|The user who last modified the site.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the site was last modified.|
|mergeType|browserSiteMergeType|The merge type of the site. The possible values are: `noMerge`, `default`, `unknownFutureValue`.|
|status|browserSiteStatus|Indicates the status of the site. The possible values are: `published`, `pendingAdd`, `pendingEdit`, `pendingDelete`, `unknownFutureValue`.|
|targetEnvironment|browserSiteTargetEnvironment|The target environment that the site should open in. The possible values are: `internetExplorerMode`, `internetExplorer11`, `microsoftEdge`, `configurable`, `none`, `unknownFutureValue`.<br /><br />Prior to June 15, 2022, the `internetExplorer11` option would allow opening a site in the Internet Explorer 11 (IE11) desktop application. Following the retirement of IE11 on June 15, 2022, the `internetExplorer11` option will no longer open an IE11 window and will instead behave the same as the `internetExplorerMode` option.|
|webUrl|String|The URL of the site.|
### [browserSiteList ](https://docs.microsoft.com/graph/api/resources/browsersitelist?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of the site list.|
|displayName|String|The name of the site list.|
|id|String|The unique identifier for the site list.|
|lastModifiedBy|identitySet|The user who last modified the site list.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the site list was last modified.|
|publishedBy|identitySet|The user who published the site list.|
|publishedDateTime|DateTimeOffset|The date and time when the site list was published.|
|revision|String|The current revision of the site list.|
|status|browserSiteListStatus|The current status of the site list. The possible values are: `draft`, `published`, `pending`, `unknownFutureValue`.|
