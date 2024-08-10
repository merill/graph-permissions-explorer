# FileStorageContainer.Selected

> Allows the application to utilize the file storage container platform to manage containers on behalf of the signed in user. The specific file storage containers and the permissions granted to them will be configured in Microsoft 365 by the developer of each container type.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /deletedStorageContainers/{containerId}](https://docs.microsoft.com/graph/api/filestorage-delete-deletedcontainers?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /storage/fileStorage/containers/{containerId}](https://docs.microsoft.com/graph/api/filestorage-delete-containers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /storage/fileStorage/containers/{containerId}/permissions/{permissionId}](https://docs.microsoft.com/graph/api/filestoragecontainer-delete-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deletedStorageContainers?$filter=containerTypeId eq {containerTypeId}](https://docs.microsoft.com/graph/api/filestorage-list-deletedcontainers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deletedStorageContainers/{containerId}](https://docs.microsoft.com/graph/api/filestorage-get-deletedcontainers?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /drives/{driveId}](https://docs.microsoft.com/graph/api/filestoragecontainer-get-drive?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers?$filter=containerTypeId eq {containerTypeId}](https://docs.microsoft.com/graph/api/filestorage-list-containers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers?$filter=containerTypeId eq {containerTypeId} and viewpoint/effectiveRole eq 'principalOwner'](https://docs.microsoft.com/graph/api/filestorage-list-containers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers/{containerId}](https://docs.microsoft.com/graph/api/filestoragecontainer-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers/{containerId}/customProperties](https://docs.microsoft.com/graph/api/filestoragecontainer-list-customproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers/{containerId}/customProperties/{propertyName}](https://docs.microsoft.com/graph/api/filestoragecontainer-list-customproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers/{containerId}/drive](https://docs.microsoft.com/graph/api/filestoragecontainer-get-drive?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /storage/fileStorage/containers/{containerId}/permissions](https://docs.microsoft.com/graph/api/filestoragecontainer-list-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /storageContainers/{containerId}/columns](https://docs.microsoft.com/graph/api/filestoragecontainer-list-columns?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /storageContainers/{containerId}/recycleBin/items](https://docs.microsoft.com/graph/api/filestoragecontainer-list-recyclebin-items?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /storage/fileStorage/containers/{containerId}](https://docs.microsoft.com/graph/api/filestoragecontainer-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /storage/fileStorage/containers/{containerId}/customProperties](https://docs.microsoft.com/graph/api/filestoragecontainer-update-customproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /storage/fileStorage/containers/{containerId}/permissions/{permissionId}](https://docs.microsoft.com/graph/api/filestoragecontainer-update-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deletedStorageContainers/{containerId}/restore](https://docs.microsoft.com/graph/api/filestoragecontainer-restore?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /storage/fileStorage/containers](https://docs.microsoft.com/graph/api/filestoragecontainer-post?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /storage/fileStorage/containers/{containerId}/activate](https://docs.microsoft.com/graph/api/filestoragecontainer-activate?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /storage/fileStorage/containers/{containerId}/permissions](https://docs.microsoft.com/graph/api/filestoragecontainer-post-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /storage/fileStorage/containers/{fileStorageContainerId}/permissions](https://docs.microsoft.com/graph/api/filestoragecontainer-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /storageContainers/{containerId}/columns](https://docs.microsoft.com/graph/api/filestoragecontainer-post-columns?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /storageContainers/{containerId}/lock](https://docs.microsoft.com/graph/api/filestoragecontainer-lock?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /storageContainers/{containerId}/permanentDelete](https://docs.microsoft.com/graph/api/filestoragecontainer-permanentdelete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /storageContainers/{containerId}/recycleBin/items/delete](https://docs.microsoft.com/graph/api/filestoragecontainer-delete-recyclebin-items?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /storageContainers/{containerId}/recycleBin/items/restore](https://docs.microsoft.com/graph/api/filestoragecontainer-restore-recyclebin-items?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /storageContainers/{containerId}/unlock](https://docs.microsoft.com/graph/api/filestoragecontainer-unlock?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|085ca537-6565-41c2-aca7-db852babc212|
|**Consent Type**|Admin|
|**Display String**|Access selected file storage containers|
|**Description**|Allows the application to utilize the file storage container platform to manage containers on behalf of the signed in user. The specific file storage containers and the permissions granted to them will be configured in Microsoft 365 by the developer of each container type.|
## Application Permission
|||
|-|-|
|**Id**|40dc41bc-0f7e-42ff-89bd-d9516947e474|
|**Display String**|Access selected file storage containers|
|**Description**|Allows the application to utilize the file storage container platform to manage containers, without a signed-in user. The specific file storage containers and the permissions granted to them will be configured in Microsoft 365 by the developer of each container type.|
## Resources
### [booleanColumn ](https://docs.microsoft.com/graph/api/resources/booleancolumn?view=graph-rest-1.0&tabs=http)

### [ChoiceColumn ](https://docs.microsoft.com/graph/api/resources/choicecolumn?view=graph-rest-1.0&tabs=http)

### [columnDefinition ](https://docs.microsoft.com/graph/api/resources/columndefinition?view=graph-rest-1.0&tabs=http)

### [CurrencyColumn ](https://docs.microsoft.com/graph/api/resources/currencycolumn?view=graph-rest-1.0&tabs=http)

### [DateTimeColumn ](https://docs.microsoft.com/graph/api/resources/datetimecolumn?view=graph-rest-1.0&tabs=http)

### [drive ](https://docs.microsoft.com/graph/api/resources/drive?view=graph-rest-1.0&tabs=http)
| Property             | Type                          | Description                                                                                                                                                                                                                      |
| :------------------- | :---------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| createdBy            | [identitySet][]               | Identity of the user, device, or application which created the item. Read-only.                                                                                                                                                  |
| createdDateTime      | dateTimeOffset                | Date and time of item creation. Read-only.                                                                                                                                                                                       |
| description          | String                        | Provide a user-visible description of the drive. Read-write.
| driveType            | String                        | Describes the type of drive represented by this resource. OneDrive personal drives will return `personal`. OneDrive for Business will return `business`. SharePoint document libraries will return `documentLibrary`. Read-only. |
| id                   | String                        | The unique identifier of the drive. Read-only.                                                                                                                                                                                   |
| lastModifiedBy       | [identitySet][]               | Identity of the user, device, and application which last modified the item. Read-only.                                                                                                                                           |
| lastModifiedDateTime | dateTimeOffset                | Date and time the item was last modified. Read-only.                                                                                                                                                                             |
| name                 | string                        | The name of the item. Read-write.                                                                                                                                                                                                |
| owner                | identitySet | Optional. The user account that owns the drive. Read-only.                                                                                                                                                                       |
| quota                | quota             | Optional. Information about the drive's storage space quota. Read-only.                                                                                                                                                          |
| sharepointIds        | [sharepointIds][]             | Returns identifiers useful for SharePoint REST compatibility. Read-only. This property is not returned by default and must be selected using the `$select` query parameter.  |
| system               | [systemFacet][]               | If present, indicates that this is a system-managed drive. Read-only.
| webUrl               | string (url)                  | URL that displays the resource in the browser. Read-only.                                                                                                                                                                        |
### [enums](https://docs.microsoft.com/graph/api/resources/enums?view=graph-rest-1.0&tabs=http)

### [fileStorageContainer ](https://docs.microsoft.com/graph/api/resources/filestoragecontainer?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|containerTypeId|Guid|Container type ID of the **fileStorageContainer**. For details about container types, see Container Types. Each container must have only one container type. Read-only.|
|createdDateTime|DateTimeOffset|Date and time of the **fileStorageContainer** creation. Read-only.|
|customProperties|fileStorageContainerCustomPropertyDictionary|Custom property collection for the **fileStorageContainer**. Read-write.|
|description|String|Provides a user-visible description of the **fileStorageContainer**. Read-write.|
|displayName|String|The display name of the **fileStorageContainer**. Read-write.|
|id|String|The unique stable identifier of the **filerStorageContainer**. Read-only.|
|status|fileStorageContainerStatus|Status of the **fileStorageContainer**. Containers are created as inactive and require activation. Inactive containers are subjected to automatic deletion in 24 hours. The possible values are: `inactive `,  `active `. Read-only.|
|viewpoint|fileStorageContainerViewpoint|Data specific to the current user. Read-only.|
### [fileStorageContainerCustomPropertyDictionary ](https://docs.microsoft.com/graph/api/resources/filestoragecontainercustompropertydictionary?view=graph-rest-1.0&tabs=http)

### [fileStorageContainerCustomPropertyValue ](https://docs.microsoft.com/graph/api/resources/filestoragecontainercustompropertyvalue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isSearchable|Boolean|Indicates whether the custom property is searchable. Optional. The default value is `false`.|
|value|String|Value of the custom property. Required.|
### [fileStorageContainerSettings ](https://docs.microsoft.com/graph/api/resources/filestoragecontainersettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isOcrEnabled|Boolean|Indicates whether OCR is enabled for a given container. If OCR is enabled on a container, OCR extraction is performed for recently added or updated documents (of supported document types) and the extracted fields are added to the metadata of the document. This enables end-user search and search-driven solutions.|
### [hyperlinkOrPictureColumn ](https://docs.microsoft.com/graph/api/resources/hyperlinkorpicturecolumn?view=graph-rest-1.0&tabs=http)
| Property      | Type               | Description|
|:-------------------|:-------------------|:----------------------------------------------|
| isPicture       | Boolean             | Specifies whether the display format used for URL columns is an image or a hyperlink. |
### [NumberColumn ](https://docs.microsoft.com/graph/api/resources/numbercolumn?view=graph-rest-1.0&tabs=http)

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
### [PersonOrGroupColumn ](https://docs.microsoft.com/graph/api/resources/personorgroupcolumn?view=graph-rest-1.0&tabs=http)

### [recycleBin ](https://docs.microsoft.com/graph/api/resources/recyclebin?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                                                                                                              |
|:---------|:-------|:-------------------------------------------------------------------------------------------------------------------------|
|id| String | The unique identifier for the **r
### [recycleBinItem ](https://docs.microsoft.com/graph/api/resources/recyclebinitem?view=graph-rest-1.0&tabs=http)
| Property            | Type           | Description                                                                                                                                                                                                      |
|:--------------------|:---------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| deletedDateTime     | DateTimeOffset | Date and time when the item was deleted. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| deletedFromLocation | String         | Relative URL of the list or folder that originally contained the item.                                                                                                                                           |
| id                  | String         | Unique identifier of the delete transaction. Inherited from baseItem.                                                                                                                             |
| name                | String         | Name of the item. Inherited from baseItem.                                                                                                                                                        |
| size                | Int64          | Size of the item in bytes.                                                                                                                                                                                       |
### [sharePointIdentitySet ](https://docs.microsoft.com/graph/api/resources/sharepointidentityset?view=graph-rest-1.0&tabs=http)
| Property    | Type                   | Description |
|:------------|:-----------------------|:----------------------------------------------------------- |
| application | [identity][]           | The application associated with this action. Optional. |
| device      | [identity][]           | The device associated with this action. Optional. |
| group       | [identity][]           | The group associated with this action. Optional. |
| user        | [identity][]           | The user associated with this action. Optional. |
| siteGroup   | [sharePointIdentity][] | The SharePoint group associated with this action. Optional. |
| siteUser    | [sharePointIdentity][] | The SharePoint user associated with this action. Optional. |
### [TextColumn ](https://docs.microsoft.com/graph/api/resources/textcolumn?view=graph-rest-1.0&tabs=http)

