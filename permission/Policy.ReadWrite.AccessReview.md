# Policy.ReadWrite.AccessReview

> Allows the app to read and write your organization's directory access review default policy on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /identityGovernance/accessReviews/policy](https://docs.microsoft.com/graph/api/accessreviewpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /policies/accessReviewPolicy](https://docs.microsoft.com/graph/api/accessreviewpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /identityGovernance/accessReviews/policy](https://docs.microsoft.com/graph/api/accessreviewpolicy-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /policies/accessReviewPolicy](https://docs.microsoft.com/graph/api/accessreviewpolicy-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4f5bc9c8-ea54-4772-973a-9ca119cb0409|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's directory access review default policy|
|**Description**|Allows the app to read and write your organization's directory access review default policy on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|77c863fd-06c0-47ce-a7eb-49773e89d319|
|**Display String**|Read and write your organization's directory access review default policy|
|**Description**|Allows the app to read and write your organization's directory access review default policy without a signed-in user.|
## Resources
### [accessReviewPolicy ](https://docs.microsoft.com/graph/api/resources/accessreviewpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Description for this policy. Read-only.|
|displayName|String|Display name for this policy. Read-only.|
|isGroupOwnerManagementEnabled|Boolean|If `true`, group owners can create and manage access reviews on groups they own.|
