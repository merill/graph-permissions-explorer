# ProfilePhoto.Read.All

> Allows the app to read all profile photos of users and groups, on behalf of the the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
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
## Delegate Permission
|||
|-|-|
|**Id**|469cd065-729e-4dee-b1fa-d92e0fab6310|
|**Consent Type**|Admin|
|**Display String**|Read profile photo of a user or group|
|**Description**|Allows the app to read all profile photos of users and groups, on behalf of the the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|e24d31aa-e1ab-4c80-85fe-23018690335d|
|**Display String**|Read profile photo of a user or group|
|**Description**|Allows the app to read all profile photos of users and groups, without a signed-in user|
## Resources
### [profilePhoto ](https://docs.microsoft.com/graph/api/resources/profilephoto?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|Read-only.|
|height|int32|The height of the photo. Read-only.|
|width|int32|The width of the photo. Read-only.|
