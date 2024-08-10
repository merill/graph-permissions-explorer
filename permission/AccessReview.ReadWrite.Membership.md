# AccessReview.ReadWrite.Membership

> Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings for group and app memberships that the signed-in user has access to in the organization.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /accessReviews/{reviewId}](https://docs.microsoft.com/graph/api/accessreview-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /accessReviews/{reviewId}/reviewers/{userId}](https://docs.microsoft.com/graph/api/accessreview-removereviewer?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /accessReviews?$filter=businessFlowTemplateId eq {businessFlowTemplate-id}&$top={pagesize}&$skip=0](https://docs.microsoft.com/graph/api/accessreview-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /accessReviews/{reviewId}](https://docs.microsoft.com/graph/api/accessreview-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /accessReviews/{reviewId}/decisions](https://docs.microsoft.com/graph/api/accessreview-listdecisions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /accessReviews/{reviewId}/myDecisions](https://docs.microsoft.com/graph/api/accessreview-listmydecisions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /accessReviews/{reviewId}/reviewers](https://docs.microsoft.com/graph/api/accessreview-listreviewers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /businessFlowTemplates](https://docs.microsoft.com/graph/api/businessflowtemplate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /accessReviews/{reviewId}](https://docs.microsoft.com/graph/api/accessreview-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /accessReviews](https://docs.microsoft.com/graph/api/accessreview-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /accessReviews/{reviewId}/applyDecisions](https://docs.microsoft.com/graph/api/accessreview-apply?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /accessReviews/{reviewId}/resetDecisions](https://docs.microsoft.com/graph/api/accessreview-reset?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /accessReviews/{reviewId}/reviewers](https://docs.microsoft.com/graph/api/accessreview-addreviewer?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /accessReviews/{reviewId}/sendReminder](https://docs.microsoft.com/graph/api/accessreview-sendreminder?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /accessReviews/{reviewId}/stop](https://docs.microsoft.com/graph/api/accessreview-stop?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5af8c3f5-baca-439a-97b0-ea58a435e269|
|**Consent Type**|Admin|
|**Display String**|Manage access reviews for group and app memberships|
|**Description**|Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings for group and app memberships that the signed-in user has access to in the organization.|
## Application Permission
|||
|-|-|
|**Id**|18228521-a591-40f1-b215-5fad4488c117|
|**Display String**|Manage access reviews for group and app memberships|
|**Description**|Allows the app to read, update, delete and perform actions on access reviews, reviewers, decisions and settings in the organization for group and app memberships, without a signed-in user.|
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
### [accessreviewrecurrencesettings](https://docs.microsoft.com/graph/api/resources/accessreviewrecurrencesettings?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :------- | :--- | :---------- |
| recurrenceType | String | The recurrence interval. Possible values: `onetime`, `weekly`, `monthly`, `quarterly`, `halfyearly` or `annual`.                                                                   |
| recurrenceEndType | String | How the recurrence ends. Possible values: `never`, `endBy`, `occurrences`, or `recurrenceCount`. If it's `never`, then there's no explicit end of the recurrence series. If it's `endBy`, then the recurrence ends at a certain date. If it's `occurrences`, then the series ends after `recurrenceCount` instances of the review have completed. |
| durationInDays | Int32 | The duration in days for recurrence. |
| recurrenceCount | Int32 | The count of recurrences, if the value of **r
### [accessreviews-root](https://docs.microsoft.com/graph/api/resources/accessreviews-root?view=graph-rest-1.0&tabs=http)

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
