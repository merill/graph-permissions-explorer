# ServiceHealth.Read.All

> Allows the app to read your tenant's service health information on behalf of the signed-in user. Health information may include service issues or service health overviews.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /admin/serviceAnnouncement/healthOverviews](https://docs.microsoft.com/graph/api/serviceannouncement-list-healthoverviews?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/healthOverviews/{ServiceName}](https://docs.microsoft.com/graph/api/servicehealth-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/issues](https://docs.microsoft.com/graph/api/serviceannouncement-list-issues?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/issues/{serviceHealthIssueId}](https://docs.microsoft.com/graph/api/servicehealthissue-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/serviceAnnouncement/issues/{serviceHealthIssueId}/incidentReport](https://docs.microsoft.com/graph/api/servicehealthissue-incidentreport?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|55896846-df78-47a7-aa94-8d3d4442ca7f|
|**Consent Type**|Admin|
|**Display String**|Read service health|
|**Description**|Allows the app to read your tenant's service health information on behalf of the signed-in user. Health information may include service issues or service health overviews.|
## Application Permission
|||
|-|-|
|**Id**|79c261e0-fe76-4144-aad5-bdc68fbe4037|
|**Display String**|Read service health|
|**Description**|Allows the app to read your tenant's service health information, without a signed-in user. Health information may include service issues or service health overviews.|
## Resources
### [serviceHealth ](https://docs.microsoft.com/graph/api/resources/servicehealth?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The service ID.|
|service|String|The service name. Use the list healthOverviews operation to get exact string names for services subscribed by the tenant.|
|status|serviceHealthStatus|Show the overall service health status. Possible values are: `serviceOperational`, `investigating`, `restoringService`, `verifyingService`, `serviceRestored`, `postIncidentReviewPublished`, `serviceDegradation`, `serviceInterruption`, `extendedRecovery`, `falsePositive`, `investigationSuspended`, `resolved`, `mitigatedExternal`, `mitigated`, `resolvedExternal`, `confirmed`, `reported`, `unknownFutureValue`. For more information, see serviceHealthStatus values.|
### [serviceHealthIssue ](https://docs.microsoft.com/graph/api/resources/servicehealthissue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|classification|serviceHealthClassificationType|The type of service health issue. Possible values are: `advisory`, `incident`, `unknownFutureValue`.|
|details|Collection(keyValuePair)|Additional details about service health issue. This property doesn't support filters. Inherited from serviceAnnouncementBase.|
|endDateTime|DateTimeOffset|The end time of the service issue. Inherited from serviceAnnouncementBase.|
|feature|String|The feature name of the service issue.|
|featureGroup|String|The feature group name of the service issue.|
|id|String|The id of the service issue. Inherited from serviceAnnouncementBase.|
|impactDescription|String|The description of the service issue impact.|
|isResolved|Boolean|Indicates whether the issue is resolved.|
|lastModifiedDateTime|DateTimeOffset|The last modified time of the issue. Inherited from serviceAnnouncementBase.|
|origin|serviceHealthOrigin|Indicates the origin of the service issue. Possible values are: `microsoft`, `thirdParty`, `customer`, `unknownFutureValue`.|
|posts|Collection(serviceHealthIssuePost)|Collection of historical posts for the service issue.|
|service|String|Indicates the service affected by the issue.|
|startDateTime|DateTimeOffset|The start time of the service issue. Inherited from serviceAnnouncementBase.|
|status|serviceHealthStatus|The status of the service issue. Possible values are: `serviceOperational`, `investigating`, `restoringService`, `verifyingService`, `serviceRestored`, `postIncidentReviewPublished`, `serviceDegradation`, `serviceInterruption`, `extendedRecovery`, `falsePositive`, `investigationSuspended`, `resolved`, `mitigatedExternal`, `mitigated`, `resolvedExternal`, `confirmed`, `reported`, `unknownFutureValue`. See more in the table below.|
|title|String|The title of the service issue. Inherited from serviceAnnouncementBase.|
