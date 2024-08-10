# SecurityIdentitiesHealth.Read.All

> Allows the app to read all the identity security health issues of signed user
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /security/identities/healthIssues](https://docs.microsoft.com/graph/api/security-identitycontainer-list-healthissues?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/identities/healthIssues/{healthIssueId}](https://docs.microsoft.com/graph/api/security-healthissue-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|a0d0da43-a6df-4416-b63d-99c79991aae8|
|**Consent Type**|Admin|
|**Display String**|Read identity security health issues|
|**Description**|Allows the app to read all the identity security health issues of signed user|
## Application Permission
|||
|-|-|
|**Id**|f8dcd971-5d83-4e1e-aa95-ef44611ad351|
|**Display String**|Read all identity security health issues|
|**Description**|Allows the app to read all the identity security health issues without a signed-in user.|
## Resources
### [healthIssue ](https://docs.microsoft.com/graph/api/resources/security-healthissue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|additionalInformation|String collection|Contains additional information about the issue, such as a list of items to fix.|
|createdDateTime|DateTimeOffset|The date and time of when the health issue was generated.|
|description|String|Contains more detailed information about the health issue.|
|displayName|String|The display name of the health issue.|
|domainNames|String collection|A list of the fully qualified domain names of the domains or the sensors the health issue is related to.|
|healthIssueType|microsoft.graph.security.healthIssueType|The type of the health issue. The possible values are: `sensor`, `global`, `unknownFutureValue`. For a list of all health issues and their identifiers, see Microsoft Defender for Identity health issues. |
|ID|String|A unique identifier that represents the health issue.|
|issueTypeId|String|The type identifier of the health issue. For a list of all health issues and their identifiers, see Microsoft Defender for Identity health issues.|
|lastModifiedDateTime|DateTimeOffset|The date and time of when the health issue was last updated.|
|recommendations|String collection|This field contains a list of recommended actions that can be taken to resolve the issue effectively and efficiently. These actions might include how to investigate the issue further. Not limited to prewritten responses.|
|recommendedActionCommands|String collection|Contains a list of commands from the product's PowerShell module that can be used to resolve the issue, if available. If there aren't any commands that can be used to solve the issue, this field is empty. The commands, if present, provide a quick and efficient way to address the issue. The commands run in order for the single recommended fix.|
|sensorDNSNames|String collection|A list of the dns names of the sensors the health issue is related to.|
|severity|microsoft.graph.security.healthIssueSeverity|The severity of the health issue. The possible values are: `low`, `medium`, `high`, `unknownFutureValue`.|
|status|microsoft.graph.security.healthIssueStatus|The status of the health issue. The possible values are: `open`, `closed`, `suppressed`, `unknownFutureValue`.|
