# User-ConvertToInternal.ReadWrite.All

> Allow the app to convert an external user to an internal member user, on behalf of signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[POST /users/{usersId}/convertExternalToInternalMemberUser](https://docs.microsoft.com/graph/api/user-convertexternaltointernalmemberuser?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|550e695c-7511-40f4-ac79-e8fb9c82552d|
|**Consent Type**|Admin|
|**Display String**|Convert an external user to internal memeber user|
|**Description**|Allow the app to convert an external user to an internal member user, on behalf of signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|9d952b72-f741-4b40-9185-8c53076c2339|
|**Display String**|Convert an external user to internal member user|
|**Description**|Allow the app to convert an external user to an internal member user, without a signed-in user.|
## Resources
### [passwordProfile ](https://docs.microsoft.com/graph/api/resources/passwordprofile?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|forceChangePasswordNextSignIn|Boolean| `true` if the user must change their password on the next sign-in; otherwise `false`.|
|forceChangePasswordNextSignInWithMfa|Boolean| If `true`, at next sign-in, the user must perform a multifactor authentication (MFA) before being forced to change their password. The behavior is identical to **forceChangePasswordNextSignIn** except that the user is required to first perform a multifactor authentication before password change. After a password change, this property will be automatically reset to `false`. If not set, default is `false`. |
|password|String|The password for the user. This property is required when a user is created. It can be updated, but the user will be required to change the password on the next sign-in. The password must satisfy minimum requirements as specified by the user's **p
