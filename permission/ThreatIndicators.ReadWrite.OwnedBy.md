# ThreatIndicators.ReadWrite.OwnedBy

> Allows the app to create threat indicators, and fully manage those threat indicators (read, update and delete), on behalf of the signed-in user.  It cannot update any threat indicators it does not own.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /security/tiIndicators/{id}](https://docs.microsoft.com/graph/api/tiindicator-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/tiIndicators](https://docs.microsoft.com/graph/api/tiindicators-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/tiIndicators/{id}](https://docs.microsoft.com/graph/api/tiindicator-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /security/tiIndicators/{id}](https://docs.microsoft.com/graph/api/tiindicator-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/tiIndicators](https://docs.microsoft.com/graph/api/tiindicators-post?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/tiIndicators/deleteTiIndicators](https://docs.microsoft.com/graph/api/tiindicator-deletetiindicators?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/tiIndicators/deleteTiIndicatorsByExternalId](https://docs.microsoft.com/graph/api/tiindicator-deletetiindicatorsbyexternalid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/tiIndicators/submitTiIndicators](https://docs.microsoft.com/graph/api/tiindicator-submittiindicators?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/tiIndicators/updateTiIndicators](https://docs.microsoft.com/graph/api/tiindicator-updatetiindicators?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|91e7d36d-022a-490f-a748-f8e011357b42|
|**Consent Type**|Admin|
|**Display String**|Manage threat indicators this app creates or owns|
|**Description**|Allows the app to create threat indicators, and fully manage those threat indicators (read, update and delete), on behalf of the signed-in user.  It cannot update any threat indicators it does not own.|
## Application Permission
|||
|-|-|
|**Id**|21792b6c-c986-4ffc-85de-df9da54b52fa|
|**Display String**|Manage threat indicators this app creates or owns|
|**Description**|Allows the app to create threat indicators, and fully manage those threat indicators (read, update and delete), without a signed-in user.  It cannot update any threat indicators it does not own.|
## Resources
### [resultInfo ](https://docs.microsoft.com/graph/api/resources/resultinfo?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description          |
| :------- | :----- | :------------------  |
| code     | Int32 | The result code.     |
| message  | String | The message.         |
| subcode  | Int32 | The result subcode. |
### [security-error-codes](https://docs.microsoft.com/graph/api/resources/security-error-codes?view=graph-rest-1.0&tabs=http)

### [tiindicator](https://docs.microsoft.com/graph/api/resources/tiindicator?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|action|string| The action to apply if the indicator is matched from within the targetProduct security tool. Possible values are: `unknown`, `allow`, `block`, `alert`. **Required.**|
|activityGroupNames|String collection|The cyber threat intelligence name(s) for the parties responsible for the malicious activity covered by the threat indicator.|
|additionalInformation|String|A catchall area for extra data from the indicator that is not specifically covered by other tiIndicator properties. The security tool specified by targetProduct typically does not utilize this data.|
|azureTenantId|String| Stamped by the system when the indicator is ingested. The Microsoft Entra tenant id of submitting client. **Required.**|
|confidence|Int32|An integer representing the confidence the data within the indicator accurately identifies malicious behavior. Acceptable values are 0 – 100 with 100 being the highest.|
|description|String| Brief description (100 characters or less) of the threat represented by the indicator. **Required.**|
|diamondModel|diamondModel|The area of the Diamond Model in which this indicator exists. Possible values are: `unknown`, `adversary`, `capability`, `infrastructure`, `victim`.|
|expirationDateTime|DateTimeOffset| DateTime string indicating when the Indicator expires. All indicators must have an expiration date to avoid stale indicators persisting in the system. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. **Required.**|
|externalId|String| An identification number that ties the indicator back to the indicator provider’s system (for example, a foreign key). |
|id|String|Created by the system when the indicator is ingested. Generated GUID/unique identifier. Read-only.|
|ingestedDateTime|DateTimeOffset| Stamped by the system when the indicator is ingested. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|isActive|Boolean| Used to deactivate indicators within system. By default, any indicator submitted is set as active. However, providers may submit existing indicators with this set to ‘False’ to deactivate indicators in the system.|
|killChain|killChain collection|A JSON array of strings that describes which point or points on the Kill Chain this indicator targets. See ‘killChain values’ below for exact values. |
|knownFalsePositives|String|Scenarios in which the indicator may cause false positives. This should be human-readable text.|
|lastReportedDateTime|DateTimeOffset|The last time the indicator was seen. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|malwareFamilyNames|String collection|The malware family name associated with an indicator if it exists. Microsoft prefers the Microsoft malware family name if at all possible that can be found via the Windows Defender Security Intelligence threat encyclopedia.|
|passiveOnly|Boolean |Determines if the indicator should trigger an event that is visible to an end-user. When set to ‘true,’ security tools won't notify the end user that a ‘hit’ has occurred. This is most often treated as audit or silent mode by security products where they'll simply log that a match occurred but won't perform the action. Default value is false. |
|severity|Int32| An integer representing the severity of the malicious behavior identified by the data within the indicator. Acceptable values are 0 – 5 where 5 is the most severe and zero isn't severe at all. Default value is 3. |
|tags|String collection|A JSON array of strings that stores arbitrary tags/keywords. |
|targetProduct|String|A string value representing a single security product to which the indicator should be applied. Acceptable values are: `Azure Sentinel`, `Microsoft Defender ATP`. **Required**|
|threatType|threatType| Each indicator must have a valid Indicator Threat Type. Possible values are: `Botnet`, `C2`, `CryptoMining`, `Darknet`, `DDoS`, `MaliciousUrl`, `Malware`, `Phishing`, `Proxy`, `PUA`, `WatchList`. **Required.** |
|tlpLevel|tlpLevel| Traffic Light Protocol value for the indicator. Possible values are: `unknown`, `white`, `green`, `amber`, `red`. **R
