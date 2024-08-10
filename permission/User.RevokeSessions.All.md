# User.RevokeSessions.All

> Allow the app to revoke all sign in sessions for a user, on behalf of a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[POST /me/invalidateAllRefreshTokens](https://docs.microsoft.com/graph/api/user-invalidateallrefreshtokens?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /me/revokeSignInSessions](https://docs.microsoft.com/graph/api/user-revokesigninsessions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{id | userPrincipalName}/invalidateAllRefreshTokens](https://docs.microsoft.com/graph/api/user-invalidateallrefreshtokens?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/revokeSignInSessions](https://docs.microsoft.com/graph/api/user-revokesigninsessions?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|fc30e98b-8810-4501-81f5-c20a3196387b|
|**Consent Type**|Admin|
|**Display String**|Revoke all sign in sessions for a user|
|**Description**|Allow the app to revoke all sign in sessions for a user, on behalf of a signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|77f3a031-c388-4f99-b373-dc68676a979e|
|**Display String**|Revoke all sign in sessions for a user|
|**Description**|Allow the app to revoke all sign in sessions for a user, without a signed-in user.|
