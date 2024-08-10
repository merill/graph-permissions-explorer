# AgreementAcceptance.Read.All

> Allows the app to read terms of use acceptance statuses on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[](https://docs.microsoft.com/graph/api/user-list-agreementacceptances?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/termsOfUse/agreements/{agreementsId}/acceptances](https://docs.microsoft.com/graph/api/agreement-list-acceptances?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/agreementAcceptances](https://docs.microsoft.com/graph/api/user-list-agreementacceptances?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/agreementAcceptances](https://docs.microsoft.com/graph/api/user-list-agreementacceptances?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|a66a5341-e66e-4897-9d52-c2df58c2bfb9|
|**Consent Type**|Admin|
|**Display String**|Read terms of use acceptance statuses that user can access|
|**Description**|Allows the app to read terms of use acceptance statuses on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|d8e4ec18-f6c0-4620-8122-c8b1f2bf400e|
|**Display String**|Read all terms of use acceptance statuses|
|**Description**|Allows the app to read terms of use acceptance statuses, without a signed in user.|
## Resources
### [agreementAcceptance ](https://docs.microsoft.com/graph/api/resources/agreementacceptance?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|agreementFileId|String|The identifier of the agreement file accepted by the user.|
|agreementId|String|The identifier of the agreement.|
|deviceDisplayName|String|The display name of the device used for accepting the agreement.|
|deviceId|String|The unique identifier of the device used for accepting the agreement. Supports `$filter` (`eq`) and `eq` for `null` values.|
|deviceOSType|String|The operating system used to accept the agreement.|
|deviceOSVersion|String|The operating system version of the device used to accept the agreement.    |
|expirationDateTime|DateTimeOffset|The expiration date time of the acceptance. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$filter` (`eq`, `ge`, `le`) and `eq` for `null` values.|
|id|String| The identifier of the agreement acceptance. Read-only. Supports `$filter` (`eq`).|
|recordedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|state|string| The state of the agreement acceptance. Possible values are: `accepted`, `declined`. Supports `$filter` (`eq`).|
|userDisplayName|String|Display name of the user when the acceptance was recorded.|
|userEmail|String|Email of the user when the acceptance was recorded.|
|userId|String|The identifier of the user who accepted the agreement. Supports `$filter` (`eq`).|
|userPrincipalName|String|UPN of the user when the acceptance was recorded.|
