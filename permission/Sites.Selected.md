# Sites.Selected

> Allow the application to access a subset of site collections on behalf of the signed-in user.  The specific site collections and the permissions granted will be configured in SharePoint Online.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions/{documentSetVersionId}](https://docs.microsoft.com/graph/api/documentsetversion-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions](https://docs.microsoft.com/graph/api/listitem-list-documentsetversions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions/{documentSetVersionId}](https://docs.microsoft.com/graph/api/documentsetversion-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /drives/{drive-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /groups/{group-id}/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /sites/{siteId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions](https://docs.microsoft.com/graph/api/listitem-post-documentsetversions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions/{documentSetVersionId}/restore](https://docs.microsoft.com/graph/api/documentsetversion-restore?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{userId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f89c84ef-20d0-4b54-87e9-02e856d66d53|
|**Consent Type**|User|
|**Display String**|Access selected Sites, on behalf of the signed-in user|
|**Description**|Allow the application to access a subset of site collections on behalf of the signed-in user.  The specific site collections and the permissions granted will be configured in SharePoint Online.|
## Application Permission
|||
|-|-|
|**Id**|883ea226-0bf2-4a8f-9f9d-92c9162a727d|
|**Display String**|Access selected site collections|
|**Description**|Allow the application to access a subset of site collections without a signed in user.  The specific site collections and the permissions granted will be configured in SharePoint Online.|
## Resources
### [documentSetVersion ](https://docs.microsoft.com/graph/api/resources/documentsetversion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| comment | string | Comment about the captured version.|
| createdBy   | identitySet | User who captured the version.|
| createdDateTime     | dateTime | Date and time when this version was created.|
| id                  | string                                               | The ID of the version. Read-only. Inherited from listItemVersion.|
| items     | documentSetVersionItem collection | Items within the document set that are captured as part of this version.|
| lastModifiedBy       | identitySet           | Identity of the user which last modified the version. Read-only. Inherited from listItemVersion.|
| lastModifiedDateTime | dateTimeOffset          | Date and time when the version was last modified. Read-only. Inherited from listItemVersion.     |
| published            | publicationFacet | Indicates the publication status of this particular version. Read-only. Inherited from listItemVersion.|
| shouldCaptureMinorVersion | Boolean  | If `true`, minor versions of items are also captured; otherwise, only major versions are captured. The default value is `false`.|
### [List ](https://docs.microsoft.com/graph/api/resources/list?view=graph-rest-1.0&tabs=http)
| Property             | Type                              | Description                                                                                           |
|:---------------------|:----------------------------------|:------------------------------------------------------------------------------------------------------|
| createdBy            | identitySet     | Identity of the creator of this item. Read-only. Inherited from baseItem.              |
| createdDateTime      | DateTimeOffset                    | The date and time when the item was created. Read-only. Inherited from baseItem.       |
| description          | String                            | The descriptive text for the item. Inherited from baseItem.                            |
| displayName          | String                            | The displayable title of the list.                                                                    |
| eTag                 | String                            | ETag for the item. Inherited from baseItem.                                            |
| id                   | String                            | The unique identifier of the item. Read-only. Inherited from baseItem.                 |
| lastModifiedBy       | identitySet     | Identity of the last modifier of this item. Read-only. Inherited from baseItem.        |
| lastModifiedDateTime | DateTimeOffset                    | The date and time when the item was last modified. Read-only. Inherited from baseItem. |
| list                 | listInfo           | Contains more details about the list.                                                                 |
| name                 | String                            | The name of the item. Read-only. Inherited from baseItem.                              |
| parentReference      | itemReference | Parent information if the item has a parent. Read-write. Inherited from baseItem.      |
| sharepointIds        | sharepointIds | Returns identifiers useful for SharePoint REST compatibility. Read-only.                              |
| system               | systemFacet     | If present, indicates that the list is system-managed. Read-only.                                     |
| webUrl               | String                            | URL that displays the item in the browser. Read-only. Inherited from baseItem.         |
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
