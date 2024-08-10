# SubjectRightsRequest.Read.All

> Allows the app to read subject rights requests on behalf of the signed-in user
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /privacy/subjectRightsRequests](https://docs.microsoft.com/graph/api/subjectrightsrequest-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /privacy/subjectRightsRequests/{subjectRightsRequestId}](https://docs.microsoft.com/graph/api/subjectrightsrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /privacy/subjectRightsRequests/{subjectRightsRequestId}/getFinalAttachment](https://docs.microsoft.com/graph/api/subjectrightsrequest-getfinalattachment?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /privacy/subjectRightsRequests/{subjectRightsRequestId}/getFinalReport](https://docs.microsoft.com/graph/api/subjectrightsrequest-getfinalreport?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /privacy/subjectRightsRequests/{subjectRightsRequestId}/notes](https://docs.microsoft.com/graph/api/subjectrightsrequest-list-notes?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /privacy/subjectRightsRequests/4EF5E3E6-545B-4B5F-A8B4-FF4F9980D7A9/getFinalReport](https://docs.microsoft.com/graph/api/subjectrightsrequest-getfinalreport?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/subjectRightsRequests](https://docs.microsoft.com/graph/api/subjectrightsrequest-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/subjectRightsRequests/{subjectRightsRequestId}](https://docs.microsoft.com/graph/api/subjectrightsrequest-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/subjectRightsRequests/{subjectRightsRequestId}/getFinalAttachment](https://docs.microsoft.com/graph/api/subjectrightsrequest-getfinalattachment?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /security/subjectRightsRequests/{subjectRightsRequestId}/getFinalReport](https://docs.microsoft.com/graph/api/subjectrightsrequest-getfinalreport?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /security/subjectRightsRequests/{subjectRightsRequestId}/notes](https://docs.microsoft.com/graph/api/subjectrightsrequest-list-notes?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/subjectRightsRequests/4EF5E3E6-545B-4B5F-A8B4-FF4F9980D7A9/getFinalReport](https://docs.microsoft.com/graph/api/subjectrightsrequest-getfinalreport?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9c3af74c-fd0f-4db4-b17a-71939e2a9d77|
|**Consent Type**|Admin|
|**Display String**|Read subject rights requests|
|**Description**|Allows the app to read subject rights requests on behalf of the signed-in user|
## Application Permission
|||
|-|-|
|**Id**|ee1460f0-368b-4153-870a-4e1ca7e72c42|
|**Display String**|Read all subject rights requests|
|**Description**|Allows the app to read subject rights requests without a signed-in user.|
## Resources
### [authoredNote ](https://docs.microsoft.com/graph/api/resources/authorednote?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|author|identity|Identity information about the note's author.|
|content|itemBody|The content of the note.|
|createdDateTime|DateTimeOffset|The date and time when the entity was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
