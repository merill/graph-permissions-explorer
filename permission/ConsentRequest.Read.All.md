# ConsentRequest.Read.All

> Allows the app to read consent requests and approvals on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /identityGovernance/appConsent/appConsentRequests](https://docs.microsoft.com/graph/api/appconsentapprovalroute-list-appconsentrequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/appConsent/appConsentRequests/{appconsentrequest-id}/userConsentRequests/{userconsentrequest-id}](https://docs.microsoft.com/graph/api/userconsentrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/appConsent/appConsentRequests/{id}](https://docs.microsoft.com/graph/api/appconsentrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/appConsent/appConsentRequests/{id}/userConsentRequests](https://docs.microsoft.com/graph/api/appconsentrequest-list-userconsentrequests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/appConsent/appConsentRequests/{id}/userConsentRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/userconsentrequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/appConsent/appConsentRequests/filterByCurrentUser(on='parameterValue')](https://docs.microsoft.com/graph/api/appconsentrequest-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f3bfad56-966e-4590-a536-82ecf548ac1e|
|**Consent Type**|Admin|
|**Display String**|Read consent requests|
|**Description**|Allows the app to read consent requests and approvals on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|1260ad83-98fb-4785-abbb-d6cc1806fd41|
|**Display String**|Read all consent requests|
|**Description**|Allows the app to read consent requests and approvals without a signed-in user.|
## Resources
### [appConsentRequest ](https://docs.microsoft.com/graph/api/resources/appconsentrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appDisplayName|String|The display name of the app for which consent is requested. Required. Supports `$filter` (`eq` only) and `$orderby`. |
|appId|String|The identifier of the application. Required. Supports `$filter` (`eq` only) and `$orderby`. |
|id|String|The identifier of the app consent request. Required.|
|pendingScopes|appConsentRequestScope collection|A list of pending scopes waiting for approval. Required.|
### [userConsentRequest ](https://docs.microsoft.com/graph/api/resources/userconsentrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|approvalId|String|The id of the approval. This value is equal to the value of the `id`.|
|completedDateTime|DateTimeOffset|The date and time when the **status** of the request was marked as `Completed`. The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|createdBy|identitySet|The user who created the request.|
|createdDateTime|DateTimeOffset|The date and time when the request was created. The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$filter` (`eq` only) and `$orderby`.|
|customData|String|Free text field to define any custom data for the user consent request. Not used.|
|id|String|Identifier of the request. |
|reason|String|The user's justification for requiring access to the app. Supports `$filter` (`eq` only) and `$orderby`.  |
|status|String|The status of the user's app consent request. Possible values are: `Initializing`, `InProgress`, `Expired`, and `Completed`. Supports `$filter` (`eq` only) and `$orderby`. |
