# SecurityIdentitiesHealth.ReadWrite.All

> Allows the app to read and write identity security health issues on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[PATCH /security/identities/healthIssues/{healthIssueId}](https://docs.microsoft.com/graph/api/security-healthissue-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|53e51eec-2d9b-4990-97f3-c9aa5d5652c3|
|**Consent Type**|Admin|
|**Display String**|Read and write identity security health issues|
|**Description**|Allows the app to read and write identity security health issues on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|ab03ddd5-7ae4-4f2e-8af8-86654f7e0a27|
|**Display String**|Read and write all identity security health issues|
|**Description**|Allows the app to read and write identity security health issues without a signed-in user.|
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
