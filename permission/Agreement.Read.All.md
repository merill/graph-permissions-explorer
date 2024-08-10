# Agreement.Read.All

> Allows the app to read terms of use agreements on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /agreements/{agreementsId}?$expand=files](https://docs.microsoft.com/graph/api/agreement-list-files?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /agreements/{agreementsId}/file](https://docs.microsoft.com/graph/api/agreementfile-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /agreements/{agreementsId}/file/localizations](https://docs.microsoft.com/graph/api/agreementfile-list-localizations?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/termsOfUse/agreements](https://docs.microsoft.com/graph/api/termsofusecontainer-list-agreements?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /identityGovernance/termsOfUse/agreements/{id}](https://docs.microsoft.com/graph/api/agreement-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|af2819c9-df71-4dd3-ade7-4d7c9dc653b7|
|**Consent Type**|Admin|
|**Display String**|Read all terms of use agreements|
|**Description**|Allows the app to read terms of use agreements on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|2f3e6f8c-093b-4c57-a58b-ba5ce494a169|
|**Display String**|Read all terms of use agreements|
|**Description**|Allows the app to read terms of use agreements, without a signed in user.|
## Resources
### [agreement ](https://docs.microsoft.com/graph/api/resources/agreement?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|displayName|String|Display name of the agreement. The display name is used for internal tracking of the agreement but isn't shown to end users who view the agreement. Supports `$filter` (`eq`).|
|id|String| The identifier of the agreement. Read-only. Supports `$filter` (`eq`).|
|isPerDeviceAcceptanceRequired|Boolean|Indicates whether end users are required to accept this agreement on every device that they access it from. The end user is required to register their device in Microsoft Entra ID, if they haven't already done so. Supports `$filter` (`eq`).|
|isViewingBeforeAcceptanceRequired|Boolean|Indicates whether the user has to expand the agreement before accepting. Supports `$filter` (`eq`).|
|termsExpiration|termsExpiration| Expiration schedule and frequency of agreement for all users. Supports `$filter` (`eq`).|
|userReacceptRequiredFrequency|Duration|The duration after which the user must reaccept the terms of use. The value is represented in ISO 8601 format for durations. Supports `$filter` (`eq`).|
### [agreementFile ](https://docs.microsoft.com/graph/api/resources/agreementfile?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The date time representing when the file was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from agreementFileProperties.|
|displayName|String|Localized display name of the policy file of an agreement. The localized display name is shown to end users who view the agreement. Inherited from agreementFileProperties.|
|fileData|agreementFileData|Data that represents the terms of use PDF document. Read-only. Inherited from agreementFileProperties.|
|fileName|String|Name of the agreement file (for example, TOU.pdf). Read-only. Inherited from agreementFileProperties.|
|id|String|The identifier of the agreementFileVersion object. Read-only. Inherited from agreementFileProperties.|
|isDefault|Boolean|If none of the languages matches the client preference, indicates whether this is the default agreement file. If none of the files are marked as default, the first one is treated as the default. Read-only. Inherited from agreementFileProperties.|
|isMajorVersion|Boolean|Indicates whether the agreement file is a major version update. Major version updates invalidate the agreement's acceptances on the corresponding language. Inherited from agreementFileProperties.|
|language|String|The language of the agreement file in the format "languagecode2-country/regioncode2". "languagecode2" is a lowercase two-letter code derived from ISO 639-1, while "country/regioncode2" is derived from ISO 3166 and usually consists of two uppercase letters, or a BCP-47 language tag. For example, U.S. English is `en-US`. Read-only. Inherited from agreementFileProperties.|
### [agreementFileLocalization ](https://docs.microsoft.com/graph/api/resources/agreementfilelocalization?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The date time representing when the file was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from agreementFileProperties.|
|displayName|String|Localized display name of the policy file of an agreement. The localized display name is shown to end users who view the agreement. Inherited from agreementFileProperties.|
|fileData|agreementFileData|Data that represents the terms of use PDF document. Read-only. Inherited from agreementFileProperties.|
|fileName|String|Name of the agreement file (for example, TOU.pdf). Read-only. Inherited from agreementFileProperties.|
|id|String|The identifier of the agreementFileVersion object. Read-only. Inherited from agreementFileProperties.|
|isDefault|Boolean|If none of the languages matches the client preference, indicates whether this is the default agreement file. If none of the files are marked as default, the first one is treated as the default. Read-only. Inherited from agreementFileProperties.|
|isMajorVersion|Boolean|Indicates whether the agreement file is a major version update. Major version updates invalidate the agreement's acceptances on the corresponding language. Inherited from agreementFileProperties.|
|language|String|The language of the agreement file in the format "languagecode2-country/regioncode2". "languagecode2" is a lowercase two-letter code derived from ISO 639-1, while "country/regioncode2" is derived from ISO 3166 and usually consists of two uppercase letters, or a BCP-47 language tag. For example, U.S. English is `en-US`. Read-only. Inherited from agreementFileProperties.|
