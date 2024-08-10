# ProfilePhoto.ReadWrite.All

> Allows the app to read and write all profile photos of users and groups, on behalf of the the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/photos](https://docs.microsoft.com/graph/api/group-list-photos?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /team/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/joinedGroups/{id}/photos](https://docs.microsoft.com/graph/api/group-list-photos?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f5b24df7-511e-48bb-ae88-643f023b55e1|
|**Consent Type**|Admin|
|**Display String**|Read and write profile photo of a user or group|
|**Description**|Allows the app to read and write all profile photos of users and groups, on behalf of the the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|27baa7f6-5dfb-4ba8-b1d3-1e812c143013|
|**Display String**|Read and write profile photo of a user or group|
|**Description**|Allows the app to read and write all profile photos of users and groups, without a signed-in user|
## Resources
### [profilePhoto ](https://docs.microsoft.com/graph/api/resources/profilephoto?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|Read-only.|
|height|int32|The height of the photo. Read-only.|
|width|int32|The width of the photo. Read-only.|
