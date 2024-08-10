# Policy.Read.ConditionalAccess

> Allows the app to read your organization's conditional access policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /identity/conditionalAccess/authenticationContextClassReferences/{authenticationContextClassReferenceId}](https://docs.microsoft.com/graph/api/authenticationcontextclassreference-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /identity/conditionalAccess/authenticationContextClassReferences/{id}](https://docs.microsoft.com/graph/api/authenticationcontextclassreference-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationContextClassReferences](https://docs.microsoft.com/graph/api/conditionalaccessroot-list-authenticationcontextclassreferences?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identity/conditionalAccess/authenticationContextClassReferences/{id}](https://docs.microsoft.com/graph/api/authenticationcontextclassreference-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|633e0fce-8c58-4cfb-9495-12bbd5a24f7c|
|**Consent Type**|User|
|**Display String**|Read your organization's conditional access policies|
|**Description**|Allows the app to read your organization's conditional access policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|37730810-e9ba-4e46-b07e-8ca78d182097|
|**Display String**|Read your organization's conditional access policies|
|**Description**|Allows the app to read your organization's conditional access policies, without a signed-in user.|
## Resources
### [authenticationContextClassReference ](https://docs.microsoft.com/graph/api/resources/authenticationcontextclassreference?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String| A short explanation of the policies that are enforced by authenticationContextClassReference. This value should be used to provide secondary text to describe the authentication context class reference when building user-facing admin experiences. For example, a selection UX.|
|displayName|String| The display name is the friendly name of the authenticationContextClassReference object. This value should be used to identify the authentication context class reference when building user-facing admin experiences. For example, a selection UX.|
|id|String| Identifier used to reference the authentication context class. The ID is used to trigger step-up authentication for the referenced authentication requirements and is the value that will be issued in the `acrs` claim of an access token. This value in the claim is used to verify that the required authentication context has been satisfied. The allowed values are `c1` through `c25`. <br/> Supports `$filter` (`eq`).|
|isAvailable|Boolean| Indicates whether the authenticationContextClassReference has been published by the security admin and is ready for use by apps. When it's set to `false`, it shouldn't be shown in authentication context selection UX, or used to protect app resources. It's shown and available for Conditional Access policy authoring. The default value is `false`. <br/> Supports `$filter` (`eq`). |
