# AccessReview.ReadWrite.All

> Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings that the signed-in user has access to in the organization.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /accessReviews/{reviewId}](https://docs.microsoft.com/graph/api/accessreview-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /accessReviews/{reviewId}/reviewers/{userId}](https://docs.microsoft.com/graph/api/accessreview-removereviewer?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /identityGovernance/accessReviews/definitions/{review-id}](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /accessReviews?$filter=businessFlowTemplateId eq {businessFlowTemplate-id}&$top={pagesize}&$skip=0](https://docs.microsoft.com/graph/api/accessreview-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /accessReviews/{reviewId}](https://docs.microsoft.com/graph/api/accessreview-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /accessReviews/{reviewId}/decisions](https://docs.microsoft.com/graph/api/accessreview-listdecisions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /accessReviews/{reviewId}/myDecisions](https://docs.microsoft.com/graph/api/accessreview-listmydecisions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /accessReviews/{reviewId}/reviewers](https://docs.microsoft.com/graph/api/accessreview-listreviewers?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /businessFlowTemplates](https://docs.microsoft.com/graph/api/businessflowtemplate-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions](https://docs.microsoft.com/graph/api/accessreviewset-list-definitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}](https://docs.microsoft.com/graph/api/accessreviewinstance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/contactedReviewers](https://docs.microsoft.com/graph/api/accessreviewinstance-list-contactedreviewers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/decisions](https://docs.microsoft.com/graph/api/accessreviewinstance-list-decisions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/decisions/{accessReviewInstanceDecisionItemId}](https://docs.microsoft.com/graph/api/accessreviewinstancedecisionitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/decisions/filterByCurrentUser(on='reviewer')](https://docs.microsoft.com/graph/api/accessreviewinstancedecisionitem-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stages](https://docs.microsoft.com/graph/api/accessreviewinstance-list-stages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stages/{accessReviewStageId}](https://docs.microsoft.com/graph/api/accessreviewstage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stages/{accessReviewStageId}/decisions](https://docs.microsoft.com/graph/api/accessreviewstage-list-decisions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stages/filterByCurrentUser(on='reviewer')](https://docs.microsoft.com/graph/api/accessreviewstage-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/filterByCurrentUser(on='reviewer')](https://docs.microsoft.com/graph/api/accessreviewinstance-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/accessReviews/definitions/{definition-id}/instances](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-list-instances?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/accessReviews/definitions/{definition-id}/instances/{instance-id}](https://docs.microsoft.com/graph/api/accessreviewinstance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/accessReviews/definitions/{review-id}](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/definitions/filterByCurrentUser(on='reviewer')](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-filterbycurrentuser?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/historyDefinitions](https://docs.microsoft.com/graph/api/accessreviewset-list-historydefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/historyDefinitions/{accessReviewHistoryDefinitionId}/instances](https://docs.microsoft.com/graph/api/accessreviewhistorydefinition-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/accessReviews/historyDefinitions/{definition-id}](https://docs.microsoft.com/graph/api/accessreviewhistorydefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/pendingAccessReviewInstances](https://docs.microsoft.com/graph/api/accessreviewinstance-pendingaccessreviewinstances?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/pendingAccessReviewInstances/{instance-id}/decisions](https://docs.microsoft.com/graph/api/accessreviewinstancedecisionitem-listpendingapproval?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /accessReviews/{reviewId}](https://docs.microsoft.com/graph/api/accessreview-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/decisions/{accessReviewInstanceDecisionItemId}](https://docs.microsoft.com/graph/api/accessreviewinstancedecisionitem-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stages/{accessReviewStageId}](https://docs.microsoft.com/graph/api/accessreviewstage-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST  /identityGovernance/accessReviews/definitions/{definition-id}/instances/{instance-id}/stopApplyDecisions](https://docs.microsoft.com/graph/api/accessreviewinstance-stopapplydecisions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /accessReviews](https://docs.microsoft.com/graph/api/accessreview-create?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /accessReviews/{reviewId}/applyDecisions](https://docs.microsoft.com/graph/api/accessreview-apply?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /accessReviews/{reviewId}/resetDecisions](https://docs.microsoft.com/graph/api/accessreview-reset?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /accessReviews/{reviewId}/reviewers](https://docs.microsoft.com/graph/api/accessreview-addreviewer?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /accessReviews/{reviewId}/sendReminder](https://docs.microsoft.com/graph/api/accessreview-sendreminder?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /accessReviews/{reviewId}/stop](https://docs.microsoft.com/graph/api/accessreview-stop?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/accessReviews/decisions/filterByCurrentUser(on='reviewer')/recordAllDecisions](https://docs.microsoft.com/graph/api/accessreviewinstancedecisionitem-recordalldecisions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions](https://docs.microsoft.com/graph/api/accessreviewset-post-definitions?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/acceptRecommendations](https://docs.microsoft.com/graph/api/accessreviewinstance-acceptrecommendations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/applyDecisions](https://docs.microsoft.com/graph/api/accessreviewinstance-applydecisions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/batchRecordDecisions](https://docs.microsoft.com/graph/api/accessreviewinstance-batchrecorddecisions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/resetDecisions](https://docs.microsoft.com/graph/api/accessreviewinstance-resetdecisions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/sendReminder](https://docs.microsoft.com/graph/api/accessreviewinstance-sendreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stages/{accessReviewStageId}/stop](https://docs.microsoft.com/graph/api/accessreviewstage-stop?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}/stop](https://docs.microsoft.com/graph/api/accessreviewinstance-stop?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /identityGovernance/accessReviews/definitions/{definition-id}/instances/{instance-id}/applyDecisions](https://docs.microsoft.com/graph/api/accessreviewinstance-applydecisions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/accessReviews/definitions/{definition-id}/instances/{instance-id}/stop](https://docs.microsoft.com/graph/api/accessreviewinstance-stop?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /identityGovernance/accessReviews/definitions/{definitionId}/instances/{instanceId}/sendReminder](https://docs.microsoft.com/graph/api/accessreviewinstance-sendreminder?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/historyDefinitions](https://docs.microsoft.com/graph/api/accessreviewset-post-historydefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/accessReviews/historyDefinitions/{accessReviewHistoryDefinitionId}/instances/{accessReviewHistoryInstanceId}/generateDownloadUri](https://docs.microsoft.com/graph/api/accessreviewhistoryinstance-generatedownloaduri?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /me/pendingAccessReviewInstances/{accessReviewInstanceId}/batchRecordDecisions](https://docs.microsoft.com/graph/api/accessreviewinstance-batchrecorddecisions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/pendingAccessReviewInstances/{instance-id}/acceptRecommendations](https://docs.microsoft.com/graph/api/accessreviewinstance-acceptrecommendations?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /identityGovernance/accessReviews/definitions/{accessReviewScheduleDefinitionId}/instances/{accessReviewInstanceId}](https://docs.microsoft.com/graph/api/accessreviewinstance-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /identityGovernance/accessReviews/definitions/{review-id}](https://docs.microsoft.com/graph/api/accessreviewscheduledefinition-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|e4aa47b9-9a69-4109-82ed-36ec70d85ff1|
|**Consent Type**|Admin|
|**Display String**|Manage all access reviews that user can access|
|**Description**|Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings that the signed-in user has access to in the organization.|
## Application Permission
|||
|-|-|
|**Id**|ef5f7d5c-338f-44b0-86c3-351f46c8bb5f|
|**Display String**|Manage all access reviews|
|**Description**|Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings in the organization, without a signed-in user.|
## Resources
### [accessreview](https://docs.microsoft.com/graph/api/resources/accessreview?view=graph-rest-1.0&tabs=http)
| Property | Type    | Description |
|:-------- |:---- |:----------- |
| id | String | The feature-assigned unique identifier of an access review. |
| displayName | String | The access review name. Required on create. |
| startDateTime | DateTimeOffset | The date and time when the review is scheduled to be start. This date can be in the future.  Required on create. |
| endDateTime | DateTimeOffset | The DateTime when the review is scheduled to end. This must be at least one day later than the start date. Required on create. |
| status | String | This read-only field specifies the status of an accessReview. The typical states include `Initializing`, `NotStarted`, `Starting`,`InProgress`, `Completing`, `Completed`, `AutoReviewing`, and `AutoReviewed`. |
| description | String | The description provided by the access review creator, to show to the reviewers. |
| businessFlowTemplateId | String | The business flow template identifier. Required on create. This value is case sensitive. |
| reviewerType | String | The relationship type of reviewer to the target object, one of: `self`, `delegated`, `entityOwners`. Required on create. | 
| createdBy | userIdentity | The user who created this review. |
| reviewedEntity | identity | The object for which the access review is reviewing the access rights assignments. This identity can be the group for the review of memberships of users in a group, or the app for a review of assignments of users to an application. Required on create. | 
| settings | accessReviewSettings | The settings of an accessReview, see type definition below. |
### [accessreviewdecision](https://docs.microsoft.com/graph/api/resources/accessreviewdecision?view=graph-rest-1.0&tabs=http)
| Property                        | Type                         | Description                                                                                            |
| :------------------------------ | :-----------------------     | :----------------------------------------------------------------------------------------------------- |
| `id`                            |`String`                      | The ID of the decision within the access review.                                                                                    |
| `accessReviewId`                |`String`                      | The feature-generated ID of the access review.                                                                                      |
| `reviewedBy`                    |userIdentity| The identity of the reviewer. If the recommendation was used as the review, the userPrincipalName is empty.                                                                                     |
| `reviewedDate`                  |`DateTimeOffset`              | The date and time the most recent review for this access right was supplied.                                                                        |
| `reviewResult`                  |`String`                      | The result of the review, one of `NotReviewed`, `Deny`, `DontKnow` or `Approve`.                                                                                   |
| `justification`                 |`String`                      | The reviewer's business justification, if supplied.                                                                        |
| `appliedBy`                     |userIdentity| When the review completes, if the results were manually applied, the user identity of the user who applied the decision. If the review was autoapplied, the userPrincipalName is empty.                                                         |
| `appliedDateTime`               |`DateTimeOffset`              | The date and time when the review decision was applied.                                                         |
| `applyResult`                   |`String`                      | The outcome of applying the decision, one of: `NotApplied`, `Success`, `Failed`, `NotFound`, `NotSupported`.                     |
| `accessRecommendation`          |`String`                      | The feature- generated recommendation shown to the reviewer, one of: `Approve`, `Deny`, `NotAvailable`. |
### [accessReviewHistoryDefinition ](https://docs.microsoft.com/graph/api/resources/accessreviewhistorydefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|userIdentity| User who created this review history definition. |
|createdDateTime|DateTimeOffset|Timestamp when the access review definition was created.|
|decisions|String collection|Determines which review decisions will be included in the fetched review history data if specified. Optional on create. All decisions are included by default if no decisions are provided on create. Possible values are: `approve`, `deny`, `dontKnow`, `notReviewed`, and `notNotified`.|
|displayName|String|Name for the access review history data collection. Required.|
|id|String|The assigned unique identifier of an access review history definition.|
|reviewHistoryPeriodEndDateTime|DateTimeOffset| A timestamp. Reviews ending on or before this date will be included in the fetched history data. Only required if **scheduleSettings** isn't defined. |
|reviewHistoryPeriodStartDateTime|DateTimeOffset|A timestamp. Reviews starting on or before this date will be included in the fetched history data. Only required if **scheduleSettings** isn't defined.|
| scheduleSettings  |accessReviewHistoryScheduleSettings| The settings for a recurring access review history definition series. Only required if **reviewHistoryPeriodStartDateTime** or **reviewHistoryPeriodEndDateTime** aren't defined. Not supported yet.|
|scopes|accessReviewScope collection|Used to scope what reviews are included in the fetched history data. Fetches reviews whose scope matches with this provided scope. Required.|
|status| accessReviewHistoryStatus|Represents the status of the review history data collection. The possible values are: `done`, `inProgress`, `error`, `requested`, `unknownFutureValue`.|
### [accessReviewHistoryInstance ](https://docs.microsoft.com/graph/api/resources/accessreviewhistoryinstance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|downloadUri|String|Uri that can be used to retrieve review history data. This URI will be active for 24 hours after being generated. Required.|
|expirationDateTime|DateTimeOffset|Timestamp when this instance and associated data expires and the history is deleted. Required.|
|fulfilledDateTime|DateTimeOffset|Timestamp when all of the available data for this instance was collected and is set after this instance's status is set to `done`. Required.|
|id|String|The assigned unique identifier of an access review history instance. Read-only. Required.|
|reviewHistoryPeriodEndDateTime|DateTimeOffset|Timestamp reviews ending on or before this date will be included in the fetched history data.|
|reviewHistoryPeriodStartDateTime|DateTimeOffset|Timestamp reviews starting on or after this date will be included in the fetched history data.|
|runDateTime|DateTimeOffset|Timestamp when the instance's history data is scheduled to be generated.|
|status|accessReviewHistoryStatus|Represents the status of the review history data collection. The possible values are: `done`, `inProgress`, `error`, `requested`, `unknownFutureValue`. Once the **s
### [accessReviewInstance ](https://docs.microsoft.com/graph/api/resources/accessreviewinstance?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :-------------------------| :---------------------------------- | :---------- |
| endDateTime | DateTimeOffset | DateTime when review instance is scheduled to end.The DatetimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$select`. Read-only.|
| fallbackReviewers   |accessReviewReviewerScope collection| This collection of reviewer scopes is used to define the list of fallback reviewers. These fallback reviewers will be notified to take action if no users are found from the list of reviewers specified. This could occur when either the group owner is specified as the reviewer but the group owner does not exist, or manager is specified as reviewer but a user's manager does not exist. Supports `$select`.|
| id | String | Unique identifier of the instance. Supports `$select`. Read-only.|
| reviewers   |accessReviewReviewerScope collection| This collection of access review scopes is used to define who the reviewers are. Supports `$select`. For examples of options for assigning reviewers, see Assign reviewers to your access review definition using the Microsoft Graph API.|
| scope | accessReviewScope | Created based on **scope** and **instanceEnumerationScope** at the accessReviewScheduleDefinition level. Defines the scope of users reviewed in a group. Supports `$select` and `$filter` (`contains` only). Read-only. |
| startDateTime | DateTimeOffset | DateTime when review instance is scheduled to start. May be in the future. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$select`. Read-only. |
| status | String | Specifies the status of an accessReview. Possible values: `Initializing`, `NotStarted`, `Starting`, `InProgress`, `Completing`, `Completed`, `AutoReviewing`, and `AutoReviewed`. Supports `$select`, `$orderby`, and `$filter` (`eq` only). Read-only.|
### [accessReviewInstanceDecisionItem ](https://docs.microsoft.com/graph/api/resources/accessreviewinstancedecisionitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessReviewId|String|The identifier of the accessReviewInstance parent. Supports `$select`. Read-only.|
|appliedBy|userIdentity|The identifier of the user who applied the decision. Read-only.|
|appliedDateTime|DateTimeOffset|The timestamp when the approval decision was applied.`00000000-0000-0000-0000-000000000000` if the assigned reviewer hasn't applied the decision or it was automatically applied. The DatetimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.  Supports `$select`. Read-only.|
|applyResult|String|The result of applying the decision. Possible values: `New`, `AppliedSuccessfully`, `AppliedWithUnknownFailure`, `AppliedSuccessfullyButObjectNotFound` and `ApplyNotSupported`. Supports `$select`, `$orderby`, and `$filter` (`eq` only). Read-only.|
|decision|String|Result of the review. Possible values: `Approve`, `Deny`, `NotReviewed`, or `DontKnow`. Supports `$select`, `$orderby`, and `$filter` (`eq` only). |
|id|String| The identifier of the decision. Inherited from entity. Supports `$select`. Read-only.|
|justification|String|Justification left by the reviewer when they made the decision.|
|principal|identity|Every decision item in an access review represents a principal's access to a resource. This property represents details of the principal. For example, if a decision item represents access of User "Bob" to Group "Sales" - The principal is "Bob" and the resource is "Sales". Principals can be of two types - userIdentity and servicePrincipalIdentity. Supports `$select`. Read-only.|
|principalLink|String|A link to the principal object. For example, `https://graph.microsoft.com/v1.0/users/a6c7aecb-cbfd-4763-87ef-e91b4bd509d9`. Read-only.|
|recommendation|String|A system-generated recommendation for the approval decision based off last interactive sign-in to tenant. The value is `Approve` if the sign-in is fewer than 30 days after the start of review, `Deny` if the sign-in is greater than 30 days after, or `NoInfoAvailable`. Possible values: `Approve`, `Deny`, or `NoInfoAvailable`. Supports `$select`, `$orderby`, and `$filter` (`eq` only). Read-only.|
|resource|accessReviewInstanceDecisionItemResource|Every decision item in an access review represents a principal's access to a resource. This property represents details of the resource. For example, if a decision item represents access of User "Bob" to Group "Sales" - The principal is Bob and the resource is "Sales". Resources can be of multiple types. See accessReviewInstanceDecisionItemResource. Read-only.|
|resourceLink|String|A link to the resource. For example, `https://graph.microsoft.com/v1.0/servicePrincipals/c86300f3-8695-4320-9f6e-32a2555f5ff8`. Supports `$select`. Read-only.|
|reviewedBy|userIdentity| The identifier of the reviewer.`00000000-0000-0000-0000-000000000000` if the assigned reviewer hasn't reviewed. Supports `$select`. Read-only.|
|reviewedDateTime|DateTimeOffset| The timestamp when the review decision occurred. Supports `$select`. Read-only.|
### [accessReviewQueryScope ](https://docs.microsoft.com/graph/api/resources/accessreviewqueryscope?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|query|String|The query representing what will be reviewed in an access review.|
|queryRoot|String|In the scenario where reviewers need to be specified dynamically, this property is used to indicate the relative source of the query. This property is only required if a relative query is specified. For example, `./manager`.|
|queryType|String|Indicates the type of query. Types include `MicrosoftGraph` and `ARM`.|
### [accessreviewrecurrencesettings](https://docs.microsoft.com/graph/api/resources/accessreviewrecurrencesettings?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :------- | :--- | :---------- |
| recurrenceType | String | The recurrence interval. Possible values: `onetime`, `weekly`, `monthly`, `quarterly`, `halfyearly` or `annual`.                                                                   |
| recurrenceEndType | String | How the recurrence ends. Possible values: `never`, `endBy`, `occurrences`, or `recurrenceCount`. If it's `never`, then there's no explicit end of the recurrence series. If it's `endBy`, then the recurrence ends at a certain date. If it's `occurrences`, then the series ends after `recurrenceCount` instances of the review have completed. |
| durationInDays | Int32 | The duration in days for recurrence. |
| recurrenceCount | Int32 | The count of recurrences, if the value of **r
### [accessReviewReviewer ](https://docs.microsoft.com/graph/api/resources/accessreviewreviewer?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :-------------------------| :---------- | :---------- |
| createdDateTime | DateTimeOffset | The date when the reviewer was added for the access review. |
| displayName | String | Name of reviewer. |
| id | String | Identifier of the reviewer. Inherited from entity. |
| userPrincipalName | String | User principal name of the reviewer. |
### [accessReviewReviewerScope ](https://docs.microsoft.com/graph/api/resources/accessreviewreviewerscope?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :-------------------------| :---------- | :---------- |
| query | String | The query specifying who will be the reviewer.|
| queryRoot | String | In the scenario where reviewers need to be specified dynamically, this property is used to indicate the relative source of the query. This property is only required if a relative query, for example, `./manager`, is specified. Possible value: `decisions`. |
| queryType | String | The type of query. Examples include `MicrosoftGraph` and `ARM`. |
### [accessreviews-root](https://docs.microsoft.com/graph/api/resources/accessreviews-root?view=graph-rest-1.0&tabs=http)

### [accessReviewScheduleDefinition ](https://docs.microsoft.com/graph/api/resources/accessreviewscheduledefinition?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :------------------| :-------------- | :---------- |
| additionalNotificationRecipients   |accessReviewNotificationRecipientItem collection| Defines the list of additional users or group members to be notified of the access review progress. |
| backupReviewers (deprecated) |accessReviewReviewerScope collection| This collection of reviewer scopes is used to define the list of fallback reviewers. These fallback reviewers are notified to take action if no users are found from the list of reviewers specified. This could occur when either the group owner is specified as the reviewer but the group owner doesn't exist, or manager is specified as reviewer but a user's manager doesn't exist.  Supports `$select`. <br>**Note:** This property has been replaced by **fallbackReviewers**. However, specifying either **backupReviewers** or **fallbackReviewers** automatically populates the same values to the other property. |
| createdBy  |userIdentity  | User who created this review. Read-only. |
| createdDateTime  |DateTimeOffset  | Timestamp when the access review series was created. Supports `$select`. Read-only. |
| descriptionForAdmins  |String  |  Description provided by review creators to provide more context of the review to admins. Supports `$select`. |
| descriptionForReviewers |String | Description provided  by review creators to provide more context of the review to reviewers. Reviewers see this description in the email sent to them requesting their review. Email notifications support up to 256 characters. Supports `$select`. |
| displayName | String   | Name of the access review series. Supports `$select` and `$orderby`. Required on create. |
| fallbackReviewers   |accessReviewReviewerScope collection| This collection of reviewer scopes is used to define the list of fallback reviewers. These fallback reviewers are notified to take action if no users are found from the list of reviewers specified. This could occur when either the group owner is specified as the reviewer but the group owner doesn't exist, or manager is specified as reviewer but a user's manager doesn't exist. See accessReviewReviewerScope. Replaces **backupReviewers**. Supports `$select`. <br/><br/>**NOTE:** The value of this property will be ignored if fallback reviewers are assigned through the **stageSettings** property. |
| id | String | The feature-assigned unique identifier of an access review. Supports `$select`. Read-only.|
| instanceEnumerationScope|accessReviewScope  | This property is required when scoping a review to guest users' access across all Microsoft 365 groups and determines which Microsoft 365 groups are reviewed. Each group becomes a unique **accessReviewInstance** of the access review series.  For supported scopes, see accessReviewScope. Supports `$select`. For examples of options for configuring instanceEnumerationScope, see Configure the scope of your access review definition using the Microsoft Graph API. |
| lastModifiedDateTime | DateTimeOffset   | Timestamp when the access review series was last modified. Supports `$select`. Read-only.|
| reviewers   |accessReviewReviewerScope collection| This collection of access review scopes is used to define who are the reviewers. The reviewers property is only updatable if individual users are assigned as reviewers. Required on create. Supports `$select`. For examples of options for assigning reviewers, see Assign reviewers to your access review definition using the Microsoft Graph API. <br/><br/>**NOTE:** The value of this property will be ignored if reviewers are assigned through the **stageSettings** property.  |
| scope  |accessReviewScope  | Defines the entities whose access is reviewed. For supported scopes, see accessReviewScope. Required on create. Supports `$select` and `$filter` (`contains` only). For examples of options for configuring scope, see Configure the scope of your access review definition using the Microsoft Graph API. |
| settings  |accessReviewScheduleSettings| The settings for an access review series, see type definition below. Supports `$select`. Required on create. |
|stageSettings|accessReviewStageSettings collection| Required only for a multi-stage access review to define the stages and their settings. You can break down each review instance into up to three sequential stages, where each stage can have a different set of reviewers, fallback reviewers, and settings. Stages are created sequentially based on the **dependsOn** property. Optional.  <br/><br/>When this property is defined, its settings are used instead of the corresponding settings in the accessReviewScheduleDefinition object and its **settings**, **reviewers**, and **fallbackReviewers** properties. |
| status  |String   | This read-only field specifies the status of an access review. The typical states include `Initializing`, `NotStarted`, `Starting`, `InProgress`, `Completing`, `Completed`, `AutoReviewing`, and `AutoReviewed`.  <br>Supports `$select`, `$orderby`, and `$filter` (`eq` only). Read-only. |
### [accessReviewScheduleSettings ](https://docs.microsoft.com/graph/api/resources/accessreviewschedulesettings?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description |
| :---------------| :---------- | :---------- |
| applyActions|accessReviewApplyAction collection | Optional field. Describes the  actions to take once a review is complete. There are two types that are currently supported: `removeAccessApplyAction` (default) and `disableAndDeleteUserApplyAction`. Field only needs to be specified in the case of `disableAndDeleteUserApplyAction`. |
| autoApplyDecisionsEnabled|Boolean | Indicates whether decisions are automatically applied. When set to `false`, an admin must apply the decisions manually once the reviewer completes the access review. When set to `true`, decisions are applied automatically after the access review instance duration ends, whether or not the reviewers have responded. Default value is `false`. <br/><br/> **CAUTION:** If both **autoApplyDecisionsEnabled** and **defaultDecisionEnabled** are `true`, all access for the principals to the resource risks being revoked if the reviewers fail to respond.|
| decisionHistoriesForReviewersEnabled|Boolean| Indicates whether decisions on previous access review stages are available for reviewers on an **accessReviewInstance** with multiple subsequent stages. If not provided, the default is disabled (`false`).|
| defaultDecision|String | Decision chosen if **defaultDecisionEnabled** is enabled. Can be one of `Approve`, `Deny`, or `Recommendation`. |
| defaultDecisionEnabled|Boolean | Indicates whether the default decision is enabled or disabled when reviewers do not respond. Default value is `false`. <br/><br/> **CAUTION:** If both **autoApplyDecisionsEnabled** and **defaultDecisionEnabled** are `true`, all access for the principals to the resource risks being revoked if the reviewers fail to respond.|
| instanceDurationInDays|Int32 | Duration of an access review instance in days. <br/>**NOTE:** If the **stageSettings** of the accessReviewScheduleDefinition object is defined, its **durationInDays** setting will be used instead of the value of this property. |
| justificationRequiredOnApproval|Boolean | Indicates whether reviewers are required to provide justification with their decision. Default value is `false`. |
| mailNotificationsEnabled|Boolean | Indicates whether emails are enabled or disabled. Default value is `false`.               |
| recommendationsEnabled|Boolean | Indicates whether decision recommendations are enabled or disabled. <br/>**NOTE:** If the **stageSettings** of the accessReviewScheduleDefinition object is defined, its **recommendationsEnabled** setting will be used instead of the value of this property. |
| recurrence|patternedRecurrence | Detailed settings for recurrence using the standard Outlook recurrence object. <br/><br/>**Note:** Only **dayOfMonth**, **interval**, and **type** (`weekly`, `absoluteMonthly`) properties are supported. Use the property **startDate** on **recurrenceRange** to determine the day the review starts. |
| reminderNotificationsEnabled|Boolean  | Indicates whether reminders are enabled or disabled. Default value is `false`.  |
| recommendationLookBackDuration | Duration| Optional field. Indicates the period of inactivity (with respect to the start date of the review instance) that recommendations will be configured from. The recommendation will be to `deny` if the user is inactive during the look-back duration. For reviews of groups and Microsoft Entra roles, any duration is accepted. For reviews of applications, 30 days is the maximum duration. If not specified, the duration is 30 days. <br/><br/>**NOTE:** If the **stageSettings** of the accessReviewScheduleDefinition object is defined, its **recommendationLookBackDuration** setting will be used instead of the value of this property. |
| recommendationInsightSettings|accessReviewRecommendationInsightSetting collection | Optional. Describes the types of insights that aid reviewers to make access review decisions. <br/><br/>**N
### [accessReviewScope ](https://docs.microsoft.com/graph/api/resources/accessreviewscope?view=graph-rest-1.0&tabs=http)

### [accessReviewStage ](https://docs.microsoft.com/graph/api/resources/accessreviewstage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|endDateTime|DateTimeOffset|The date and time in ISO 8601 format and UTC time when the review stage is scheduled to end. This property is the cumulative total of the **durationInDays** for all stages. Read-only. |
|fallbackReviewers|accessReviewReviewerScope collection|This collection of reviewer scopes is used to define the list of fallback reviewers. These fallback reviewers are notified to take action if no users are found from the list of reviewers specified. This could occur when either the group owner is specified as the reviewer but the group owner doesn't exist, or manager is specified as reviewer but a user's manager doesn't exist.|
|id|String|Unique identifier of the stage. Read-only.|
|reviewers|accessReviewReviewerScope collection|This collection of access review scopes is used to define who the reviewers are. For examples of options for assigning reviewers, see Assign reviewers to your access review definition using the Microsoft Graph API.|
|startDateTime|DateTimeOffset|The date and time in ISO 8601 format and UTC time when the review stage is scheduled to start. Read-only. |
|status|String|Specifies the status of an accessReviewStage. Possible values: `Initializing`, `NotStarted`, `Starting`, `InProgress`, `Completing`, `Completed`, `AutoReviewing`, and `AutoReviewed`. Supports `$orderby`, and `$filter` (`eq` only). Read-only.|
### [accessReviewStageSettings ](https://docs.microsoft.com/graph/api/resources/accessreviewstagesettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|decisionsThatWillMoveToNextStage|String collection|Indicate which decisions will go to the next stage. Can be a subset of `Approve`, `Deny`, `Recommendation`, or `NotReviewed`. If not provided, all decisions will go to the next stage. Optional. |
|dependsOn|String collection| Defines the sequential or parallel order of the stages and depends on the **stageId**. Only sequential stages are currently supported. For example, if **stageId** is `2`, then **dependsOn** must be `1`. If **stageId** is `1`, don't specify **dependsOn**. Required if **stageId** isn't `1`. |
|durationInDays|Int32|The duration of the stage. Required.  <br/><br/>**NOTE:** The cumulative value of this property across all stages <br/> 1. Will override the instanceDurationInDays setting on the accessReviewScheduleDefinition object. <br/>2. Can't exceed the length of one recurrence. That is, if the review recurs weekly, the cumulative **durationInDays** can't exceed 7. |
|fallbackReviewers|accessReviewReviewerScope collection|If provided, the fallback reviewers are asked to complete a review if the primary reviewers don't exist. For example, if managers are selected as **reviewers** and a principal under review doesn't have a manager in Microsoft Entra ID, the fallback reviewers are asked to review that principal. <br/><br/>**NOTE:** The value of this property overrides the corresponding setting on the accessReviewScheduleDefinition object.|
|recommendationsEnabled|Boolean|Indicates whether showing recommendations to reviewers is enabled. Required. <br/><br/>**NOTE:** The value of this property overrides override the corresponding setting on the accessReviewScheduleDefinition object.|
| recommendationInsightsSettings | accessReviewRecommendationInsightSetting collection | Determines which recommendations to show to reviewers. <br/><br/>**NOTE:** The value of this property overrides the corresponding setting on the accessReviewScheduleDefinition object.|
| recommendationLookBackDuration | Duration| Optional field. Indicates the time period of inactivity (with respect to the start date of the review instance) that recommendations will be configured from. The recommendation is to `deny` if the user is inactive during the look back duration. For reviews of groups and Microsoft Entra roles, any duration is accepted. For reviews of applications, 30 days is the maximum duration. If not specified, the duration is 30 days. <br/><br/>**NOTE:** The value of this property overrides the corresponding setting on the accessReviewScheduleDefinition object. |
|reviewers|accessReviewReviewerScope collection|Defines who the reviewers are. If none is specified, the review is a self-review (users review their own access).  For examples of options for assigning reviewers, see Assign reviewers to your access review definition using the Microsoft Graph API. <br/><br/>**NOTE:** The value of this property overrides the corresponding setting on the accessReviewScheduleDefinition. |
|stageId|String|Unique identifier of the **a
### [accessreviewsv2-overview](https://docs.microsoft.com/graph/api/resources/accessreviewsv2-overview?view=graph-rest-1.0&tabs=http)

### [businessflowtemplate](https://docs.microsoft.com/graph/api/resources/businessflowtemplate?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
| id                     |String                | The feature-assigned identifier of the business flow template. These values are case sensitive.                                      |
| displayName            |String                | The name of the business flow template                                                             |
### [identity ](https://docs.microsoft.com/graph/api/resources/identity?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                                                                                                                                                                                                                                                           |
|:------------|:-------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| displayName         | String | The display name of the identity.<br/><br/>For drive items, the display name might not always be available or up to date. For example, if a user changes their display name the API might show the new value in a future response, but the items associated with the user don't show up as changed when using delta.       |
| id                  | String | Unique identifier for the identity or actor. For example, in the access reviews decisions API, this property might record the **id** of the principal, that is, the group, user, or application that's subject to review. |
| tenantId            | String | Unique identity of the tenant. Optional.                                    |
| thumbnails          | thumbnailSet | Keyed collection of thumbnail resources. Optional. Applies to drive items, for example. |
### [programcontrol](https://docs.microsoft.com/graph/api/resources/programcontrol?view=graph-rest-1.0&tabs=http)
| Property | Type    | Description |
|:-------- |:---- |:----------- |
| id | String | The feature-assigned identifier of the link between program and control. |
| programId | String | The programId of the program this control is a part of. Required on create. |
| controlId | String | The controlId of the control, in particular the identifier of an access review. Required on create. |
| controlTypeId | String | The programControlType identifies the type of program control - for example, a control linking to guest access reviews. Required on create. |
| displayName | String | The name of the control. |
| status | String | The life cycle status of the control. |
| createdDateTime | DateTimeOffset | The creation date and time of the program control. |
| owner | userIdentity | The user who created the program control. |
| resource | programResource | The resource, a group or an app, targeted by this program control's access review. |
### [userIdentity ](https://docs.microsoft.com/graph/api/resources/useridentity?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| displayName | String | The display name of the identity. This might not always be available or up-to-date.    |
| id          | String | Unique identifier for the identity. Nullable. When the unique identifier is unavailable, the **displayName** property is provided for the identity, but the **id** property isn't included in the response. |
| ipAddress   | String | Indicates the client IP address associated with the user performing the activity (audit log only).|
| userPrincipalName | String  | The **u
