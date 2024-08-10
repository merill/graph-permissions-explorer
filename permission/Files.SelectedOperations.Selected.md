# Files.SelectedOperations.Selected

> Allow the application to access files explicitly permissioned to the application on behalf of the signed in user.  The specific files and the permissions granted will be configured in SharePoint Online or OneDrive.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[POST /drives/{drive-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /groups/{group-id}/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /sites/{siteId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{userId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ef2779dc-ef1b-4211-8310-8a0ac2450081|
|**Consent Type**|Admin|
|**Display String**|Access selected Files, on behalf of the signed-in user|
|**Description**|Allow the application to access files explicitly permissioned to the application on behalf of the signed in user.  The specific files and the permissions granted will be configured in SharePoint Online or OneDrive.|
## Application Permission
|||
|-|-|
|**Id**|bd61925e-3bf4-4d62-bc0b-06b06c96d95c|
|**Display String**|Access selected Files without a signed in user.|
|**Description**|Allow the application to access a subset of files without a signed in user.  The specific files and the permissions granted will be configured in SharePoint Online or OneDrive.|
## Resources
### [Permission ](https://docs.microsoft.com/graph/api/resources/permission?view=graph-rest-1.0&tabs=http)
| Property                         | Type                                      | Description |
|:---------------------------------|:------------------------------------------|:-----------------
| expirationDateTime               | DateTimeOffset                            | A format of yyyy-MM-ddTHH:mm:ssZ of DateTimeOffset indicates the expiration time of the permission. DateTime.MinValue indicates there's no expiration set for this permission. Optional. |
| id                               | String                                    | The unique identifier of the permission among all permissions on the item. Read-only. |
| hasPassword                      | Boolean                                   | Indicates whether the password is set for this permission. This property only appears in the response. Optional. Read-only. For OneDrive Personal only.. |
| grantedTo (deprecated)           | IdentitySet             | For user type permissions, the details of the users and applications for this permission. Read-only. |
| grantedToIdentities (deprecated) | Collection(IdentitySet) | For type permissions, the details of the users to whom permission was granted. Read-only. |
| grantedToIdentitiesV2            | Collection([SharePointIdentitySet][]) | For link type permissions, the details of the users to whom permission was granted. Read-only. |
| grantedToV2                      | [SharePointIdentitySet][]                 | For user type permissions, the details of the users and applications for this permission. Read-only. |
| inheritedFrom                    | ItemReference         | Provides a reference to the ancestor of the current permission, if it's inherited from an ancestor. Read-only. |
| invitation                       | [SharingInvitation][]                     | Details of any associated sharing invitation for this permission. Read-only. |
| link                             | [SharingLink][]                           | Provides the link details of the current permission, if it's a link type permission. Read-only. |
| roles                            | Collection of String                      | The type of permission, for example, `read`. See below for the full list of roles. Read-only. |
| shareId                          | String                                    | A unique token that can be used to access this shared item via the **shares** API. Read-only. |
