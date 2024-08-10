# Policy.ReadWrite.TrustFramework

> Allows the app to read and write your organization's trust framework policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /trustFramework/policies/{id}](https://docs.microsoft.com/graph/api/trustframeworkpolicy-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /trustFramework/policies/](https://docs.microsoft.com/graph/api/trustframework-list-trustframeworkpolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /trustFramework/policies/{id}/$value](https://docs.microsoft.com/graph/api/trustframeworkpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /trustFramework/policies](https://docs.microsoft.com/graph/api/trustframework-post-trustframeworkpolicy?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PUT /trustFramework/policies/{id}/$value](https://docs.microsoft.com/graph/api/trustframework-put-trustframeworkpolicy?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|cefba324-1a70-4a6e-9c1d-fd670b7ae392|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's trust framework policies|
|**Description**|Allows the app to read and write your organization's trust framework policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|79a677f7-b79d-40d0-a36a-3e6f8688dd7a|
|**Display String**|Read and write your organization's trust framework policies|
|**Description**|Allows the app to read and write your organization's trust framework policies without a signed in user.|
## Resources
### [trustFrameworkPolicy ](https://docs.microsoft.com/graph/api/resources/trustframeworkpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|id|String|The ID of the policy.|
