# ThreatAssessment.Read.All

> Allows an app to read your organization's threat assessment requests, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /informationProtection/threatAssessmentRequests](https://docs.microsoft.com/graph/api/informationprotection-list-threatassessmentrequests?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /informationProtection/threatAssessmentRequests/{id}](https://docs.microsoft.com/graph/api/threatassessmentrequest-get?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|f8f035bb-2cce-47fb-8bf5-7baf3ecbee48|
|**Display String**|Read threat assessment requests|
|**Description**|Allows an app to read your organization's threat assessment requests, without a signed-in user.|
## Resources
### [threatAssessmentRequest ](https://docs.microsoft.com/graph/api/resources/threatassessmentrequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
| :-------------|:------------|:------------|
|category|threatCategory|The threat category. Possible values are: `spam`, `phishing`, `malware`.|
|contentType|threatAssessmentContentType|The content type of threat assessment. Possible values are: `mail`, `url`, `file`.|
|createdBy|identitySet|The threat assessment request creator.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|expectedAssessment|threatExpectedAssessment|The expected assessment from submitter. Possible values are: `block`, `unblock`.|
|id|String|The threat assessment request ID is a globally unique identifier (GUID).|
|requestSource|threatAssessmentRequestSource|The source of the threat assessment request. Possible values are: `administrator`.|
|status|threatAssessmentStatus|The assessment process status. Possible values are: `pending`, `completed`.|
