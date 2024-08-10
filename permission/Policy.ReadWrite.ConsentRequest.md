# Policy.ReadWrite.ConsentRequest

> Allows the app to read and write your organization's consent requests policy on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /policies/adminConsentRequestPolicy](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /policies/adminConsentRequestPolicy](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /policies/adminConsentRequestPolicy ](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4d135e65-66b8-41a8-9f8b-081452c91774|
|**Consent Type**|Admin|
|**Display String**|Read and write consent request policy|
|**Description**|Allows the app to read and write your organization's consent requests policy on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|999f8c63-0a38-4f1b-91fd-ed1947bdd1a9|
|**Display String**|Read and write your organization's consent request policy|
|**Description**|Allows the app to read and write your organization's consent requests policy without a signed-in user.|
## Resources
### [accessReviewReviewerScope ](https://docs.microsoft.com/graph/api/resources/accessreviewreviewerscope?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :-------------------------| :---------- | :---------- |
| query | String | The query specifying who will be the reviewer.|
| queryRoot | String | In the scenario where reviewers need to be specified dynamically, this property is used to indicate the relative source of the query. This property is only required if a relative query, for example, `./manager`, is specified. Possible value: `decisions`. |
| queryType | String | The type of query. Examples include `MicrosoftGraph` and `ARM`. |
### [adminConsentRequestPolicy ](https://docs.microsoft.com/graph/api/resources/adminconsentrequestpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabled|Boolean|Specifies whether the admin consent request feature is enabled or disabled. Required.|
|notifyReviewers|Boolean|Specifies whether reviewers will receive notifications. Required.|
|remindersEnabled|Boolean|Specifies whether reviewers will receive reminder emails. Required.|
|requestDurationInDays|Int32|Specifies the duration the request is active before it automatically expires if no decision is applied.|
|reviewers|accessReviewReviewerScope collection|The list of reviewers for the admin consent. Required.|
|version|Int32|Specifies the version of this policy. When the policy is updated, this version is updated. Read-only.|
