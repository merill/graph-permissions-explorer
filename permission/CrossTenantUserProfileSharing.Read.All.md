# CrossTenantUserProfileSharing.Read.All

> Allows the application to list and query any shared user profile information associated with the current tenant on behalf of the signed-in user.  It also permits the application to export external user data (e.g. customer content or system-generated logs), for any user associated with the current tenant on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /directory/inboundSharedUserProfiles](https://docs.microsoft.com/graph/api/directory-list-inboundshareduserprofiles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/inboundSharedUserProfiles/{userId}](https://docs.microsoft.com/graph/api/inboundshareduserprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/outboundSharedUserProfiles](https://docs.microsoft.com/graph/api/directory-list-outboundshareduserprofiles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/outboundSharedUserProfiles/{userId}](https://docs.microsoft.com/graph/api/outboundshareduserprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/outboundSharedUserProfiles/{userId}/tenants](https://docs.microsoft.com/graph/api/outboundshareduserprofile-list-tenants?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/inboundSharedUserProfiles/{userId}/exportPersonalData](https://docs.microsoft.com/graph/api/inboundshareduserprofile-exportpersonaldata?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|759dcd16-3c90-463c-937e-abf89f991c18|
|**Consent Type**|Admin|
|**Display String**|Read all shared cross-tenant user profiles and export their data|
|**Description**|Allows the application to list and query any shared user profile information associated with the current tenant on behalf of the signed-in user.  It also permits the application to export external user data (e.g. customer content or system-generated logs), for any user associated with the current tenant on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|8b919d44-6192-4f3d-8a3b-f86f8069ae3c|
|**Display String**|Read all shared cross-tenant user profiles and export their data|
|**Description**|Allows the application to list and query any shared user profile information associated with the current tenant without a signed-in user.  It also permits the application to export external user data (e.g. customer content or system-generated logs), for any user associated with the current tenant without a signed-in user.|
## Resources
### [inboundSharedUserProfile ](https://docs.microsoft.com/graph/api/resources/inboundshareduserprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| displayName | String | The name displayed in the address book for the user at the time when the sharing record was created. Read-only. |
| homeTenantId | String | The home tenant id of the external user. Read-only. |
| userId | String | The object id of the external user. Read-only. |
| userPrincipalName | String | The user principal name (UPN) of the external user. Read-only. |
### [outboundSharedUserProfile ](https://docs.microsoft.com/graph/api/resources/outboundshareduserprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| userId | String | The object id of the external user. Read-only. |
### [tenantReference ](https://docs.microsoft.com/graph/api/resources/tenantreference?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| tenantId | String | The identifier of the Microsoft Entra tenant. Read-only. Key. |
