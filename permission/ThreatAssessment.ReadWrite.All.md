# ThreatAssessment.ReadWrite.All

> Allows an app to read your organization's threat assessment requests on behalf of the signed-in user. Also allows the app to create new requests to assess threats received by your organization on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /informationProtection/threatAssessmentRequests](https://docs.microsoft.com/graph/api/informationprotection-list-threatassessmentrequests?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /informationProtection/threatAssessmentRequests/{id}](https://docs.microsoft.com/graph/api/threatassessmentrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /informationProtection/threatAssessmentRequests](https://docs.microsoft.com/graph/api/informationprotection-post-threatassessmentrequests?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|cac97e40-6730-457d-ad8d-4852fddab7ad|
|**Consent Type**|Admin|
|**Display String**|Read and write threat assessment requests|
|**Description**|Allows an app to read your organization's threat assessment requests on behalf of the signed-in user. Also allows the app to create new requests to assess threats received by your organization on behalf of the signed-in user.|
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
