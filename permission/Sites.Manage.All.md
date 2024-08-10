# Sites.Manage.All

> Allows the application to create or delete document libraries and lists in all site collections on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/contenttype-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /me/drive/items/{id}/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /me/drive/root:/{item-path}:/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /sites/{site-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /sites/{site-id}/contentTypes/{contentType-id}](https://docs.microsoft.com/graph/api/contenttype-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /sites/{site-id}/contentTypes/{contentType-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /sites/{site-id}/lists/{list-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}](https://docs.microsoft.com/graph/api/contenttype-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /sites/{site-id}/lists/{list-id}/permissions/{permissionId}](https://docs.microsoft.com/graph/api/list-delete-permissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions/{documentSetVersionId}](https://docs.microsoft.com/graph/api/documentsetversion-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/columns](https://docs.microsoft.com/graph/api/site-list-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/contentTypes](https://docs.microsoft.com/graph/api/site-list-contenttypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/contentTypes/{contentType-id}](https://docs.microsoft.com/graph/api/contenttype-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/contentTypes/{contentType-id}/columns](https://docs.microsoft.com/graph/api/contenttype-list-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/contentTypes/{contentType-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/columns](https://docs.microsoft.com/graph/api/list-list-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/contentTypes](https://docs.microsoft.com/graph/api/list-list-contenttypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}](https://docs.microsoft.com/graph/api/contenttype-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}/columns](https://docs.microsoft.com/graph/api/contenttype-list-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}](https://docs.microsoft.com/graph/api/listitem-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}?expand=fields](https://docs.microsoft.com/graph/api/listitem-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}?expand=fields(select=Column1,Column2)](https://docs.microsoft.com/graph/api/listitem-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/listitem-list-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/permissions/{permission-id}](https://docs.microsoft.com/graph/api/listitem-get-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/permissions](https://docs.microsoft.com/graph/api/list-list-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/permissions/](https://docs.microsoft.com/graph/api/list-get-permissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/contentTypes/getCompatibleHubContentTypes](https://docs.microsoft.com/graph/api/contenttype-getcompatiblehubcontenttypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/getApplicableContentTypesForList](https://docs.microsoft.com/graph/api/site-getapplicablecontenttypesforlist?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/contentTypes/getCompatibleHubContentTypes](https://docs.microsoft.com/graph/api/contenttype-getcompatiblehubcontenttypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions](https://docs.microsoft.com/graph/api/listitem-list-documentsetversions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions/{documentSetVersionId}](https://docs.microsoft.com/graph/api/documentsetversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/operations](https://docs.microsoft.com/graph/api/list-list-operations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/lists/{listId}/operations/{richLongRunningOperation-ID}](https://docs.microsoft.com/graph/api/richlongrunningoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/operations](https://docs.microsoft.com/graph/api/site-list-operations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/operations/{richLongRunningOperation-ID}](https://docs.microsoft.com/graph/api/richlongrunningoperation-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /sites/{sitesId}/contentModels/{contentModelId}](https://docs.microsoft.com/graph/api/contentmodel-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{sitesId}/contentModels/{contentModelId}/getAppliedDrives](https://docs.microsoft.com/graph/api/contentmodel-getapplieddrives?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{sitesId}/contentModels/getByName](https://docs.microsoft.com/graph/api/contentmodel-getbyname?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /sites/{site-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /sites/{site-id}/contentTypes/{contentType-id}](https://docs.microsoft.com/graph/api/contenttype-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /sites/{site-id}/contentTypes/{contentType-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /sites/{site-id}/lists/{list-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}](https://docs.microsoft.com/graph/api/contenttype-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}/columns/{column-id}](https://docs.microsoft.com/graph/api/columndefinition-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /sites/{site-id}/lists/{list-id}/items/{item-id}/permissions/{permission-id}](https://docs.microsoft.com/graph/api/listitem-update-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /sites/{site-id}/lists/{list-id}/permissions/{permissionId}](https://docs.microsoft.com/graph/api/list-update-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /drives/{drive-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /groups/{group-id}/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/columns](https://docs.microsoft.com/graph/api/site-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/contentTypes](https://docs.microsoft.com/graph/api/site-post-contenttypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/contentTypes/{contentType-id}/columns](https://docs.microsoft.com/graph/api/contenttype-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/items/{item-id}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/listitemversion-restore?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/lists](https://docs.microsoft.com/graph/api/list-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/lists/{list-id}/columns](https://docs.microsoft.com/graph/api/list-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/lists/{list-id}/contentTypes/{contentType-id}/columns](https://docs.microsoft.com/graph/api/contenttype-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/lists/{list-id}/contentTypes/addCopy](https://docs.microsoft.com/graph/api/contenttype-addcopy?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /sites/{site-id}/lists/{list-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/listitem-post-permissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/lists/{list-id}/items/{item-id}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/listitemversion-restore?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/contentTypes/{contentTypeId}/associateWithHubSites](https://docs.microsoft.com/graph/api/contenttype-associatewithhubsites?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /sites/{siteId}/contentTypes/{contentTypeId}/copyToDefaultContentLocation](https://docs.microsoft.com/graph/api/contenttype-copytodefaultcontentlocation?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/contentTypes/{contentTypeId}/copyToDefaultContentLocation ](https://docs.microsoft.com/graph/api/contenttype-copytodefaultcontentlocation?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/contentTypes/addCopyFromContentTypeHub](https://docs.microsoft.com/graph/api/contenttype-addcopyfromcontenttypehub?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /sites/{siteId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/lists/{listId}/contentTypes/addCopyFromContentTypeHub](https://docs.microsoft.com/graph/api/contenttype-addcopyfromcontenttypehub?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions](https://docs.microsoft.com/graph/api/listitem-post-documentsetversions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/lists/{listId}/items/{itemId}/documentSetVersions/{documentSetVersionId}/restore](https://docs.microsoft.com/graph/api/documentsetversion-restore?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /sites/{sitesId}/contentModels/{contentModelId}/removeFromDrive](https://docs.microsoft.com/graph/api/contentmodel-removefromdrive?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /sites/{sitesId}/documentProcessingJobs](https://docs.microsoft.com/graph/api/site-post-documentprocessingjobs?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /sites/f2d90359-865b-4b6c-8848-d2722dd630e5/lists/1d702d60-503c-4924-abfd-028c65fc89ed/permissions](https://docs.microsoft.com/graph/api/list-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{userId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|65e50fdc-43b7-4915-933e-e8138f11f40a|
|**Consent Type**|User|
|**Display String**|Create, edit, and delete items and lists in all site collections|
|**Description**|Allows the application to create or delete document libraries and lists in all site collections on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|0c0bf378-bf22-4481-8f81-9e89a9b4960a|
|**Display String**|Create, edit, and delete items and lists in all site collections|
|**Description**|Allows the app to create or delete document libraries and lists in all site collections without a signed in user.|
## Resources
### [columnDefinition ](https://docs.microsoft.com/graph/api/resources/columndefinition?view=graph-rest-1.0&tabs=http)

### [contentModel ](https://docs.microsoft.com/graph/api/resources/contentmodel?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|Identity of the user, device, or applicationthat created the item. Read-only.|
|createdDateTime|DateTimeOffset|Date and time of item creation. Read-only.|
|id|String|The ID of the content model. Read-only.|
|lastModifiedBy|identitySet|	Identity of the user, device, or application that modified the item. Read-only.|
|lastModifiedDateTime|DateTimeOffset|Date and time of item last modification. Read-only.|
|modelType|contentModelType|The type of the **contentModel**. The possible values are: `teachingMethod`, `layoutMethod`, `freeformSelectionMethod`, `prebuiltContractModel`, `prebuiltInvoiceModel`, `prebuiltReceiptModel`, `unknownFutureValue`.|
|name|String|The name of the **c
### [contentModelUsage ](https://docs.microsoft.com/graph/api/resources/contentmodelusage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|Identity of the user, device, or application that first applied the contentModel to the library.|
|createdDateTime|DateTimeOffset|Date and time of the contentModel is first applied.|
|driveId|String|The ID of the drive where the contentModel is applied.|
|lastModifiedBy|identitySet|Identity of the user, device, or application that last applied the contentModel to the library.|
|lastModifiedDateTime|DateTimeOffset|Date and time of the contentModel is last applied.|
|modelId|String|The ID of the contentModel.|
|modelVersion|String|The version of the current applied contentModel.|
### [contentType ](https://docs.microsoft.com/graph/api/resources/contenttype?view=graph-rest-1.0&tabs=http)
| Property     | Type                 | Description|
|:------------------|:---------------------|:----------------------------------|
| associatedHubsUrls         | String collection | List of canonical URLs for hub sites with which this content type is associated to. This will contain all hub sites where this content type is queued to be enforced or is already enforced. Enforcing a content type means that the content type is applied to the lists in the enforced sites.|
| description       | string               | The descriptive text for the item.|
| documentSet         | documentSet][]      | [Document Set metadata.|
| documentTemplate    | [documentSetContent][] | Document template metadata. To make sure that documents have consistent content across a site and its subsites, you can associate a Word, Excel, or PowerPoint template with a site content type.|
| group             | string               | The name of the group this content type belongs to. Helps organize related content types.|
| hidden            | Boolean              | Indicates whether the content type is hidden in the list's 'New' menu.|
| id                | string               | The unique identifier of the content type.|
| inheritedFrom   | [itemReference][]    | If this content type is inherited from another scope (like a site), provides a reference to the item where the content type is defined.|
| isBuiltIn            | Boolean| Specifies if a content type is a built-in content type. |
| name              | string               | The name of the content type.|
| order             | [contentTypeOrder][] | Specifies the order in which the content type appears in the selection UI.|
| parentId          | string               | The unique identifier of the content type.|
| propagateChanges     | Boolean              | If `true`, any changes made to the content type are pushed to inherited content types and lists that implement the content type.|
| readOnly          | Boolean              | If `true`, the content type can't be modified unless this value is first set to `false`.|
| sealed            | Boolean              | If `true`, the content type can't be modified by users or through push-down operations. Only site collection administrators can seal or unseal content types.|
### [documentProcessingJob ](https://docs.microsoft.com/graph/api/resources/documentprocessingjob?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of item creation. Read-only.|
|Id|String|The ID of the document processing job. Read-only.|
|jobType|documentProcessingJobType|The document processing job type. The possible values are: `file`, `folder`|
|listItemUniqueId|String|The listItemUniqueId of the file, or folder to process. Use GET driveItem resource operation and read  sharepointIds property to get listItemUniqueId.|
|status|documentProcessingJobStatus|The document processing Job status. The possible values are: `inProgress`, `completed`, `failed`, `unknownFutureValue`.|
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
### [driveItem ](https://docs.microsoft.com/graph/api/resources/driveitem?view=graph-rest-1.0&tabs=http)
| Property             | Type               | Description
|:---------------------|:-------------------|:---------------------------------
| audio                | [audio][]          | Audio metadata, if the item is an audio file. Read-only. Read-only. Only on OneDrive Personal.
| bundle               | [bundle][]         | Bundle metadata, if the item is a bundle. Read-only.
| content              | Stream             | The content stream, if the item represents a file.
| createdBy            | [identitySet][]    | Identity of the user, device, and application that created the item. Read-only.
| createdDateTime      | DateTimeOffset     | Date and time of item creation. Read-only.
| cTag                 | String             | An eTag for the content of the item. This eTag isn't changed if only the metadata is changed. **Note** This property isn't returned if the item is a folder. Read-only.
| deleted              | [deleted][]        | Information about the deleted state of the item. Read-only.
| description          | String             | Provides a user-visible description of the item. Read-write. Only on OneDrive Personal.
| eTag                 | String             | eTag for the entire item (metadata + content). Read-only.
| file                 | [file][]           | File metadata, if the item is a file. Read-only.
| fileSystemInfo       | [fileSystemInfo][] | File system information on client. Read-write.
| folder               | [folder][]         | Folder metadata, if the item is a folder. Read-only.
| id                   | String             | The unique identifier of the item within the Drive. Read-only.
| image                | [image][]          | Image metadata, if the item is an image. Read-only.
| lastModifiedBy       | [identitySet][]    | Identity of the user, device, and application that last modified the item. Read-only.
| lastModifiedDateTime | DateTimeOffset     | Date and time the item was last modified. Read-only.
| location             | [geoCoordinates][] | Location metadata, if the item has location data. Read-only.
| malware              | [malware][]        | Malware metadata, if the item was detected to contain malware. Read-only.
| name                 | String             | The name of the item (filename and extension). Read-write.
| package              | [package][]        | If present, indicates that this item is a package instead of a folder or file. Packages are treated like files in some contexts and folders in others. Read-only.
| parentReference      | [itemReference][]  | Parent information, if the item has a parent. Read-write.
| pendingOperations    | [pendingOperations][] | If present, indicates that one or more operations that might affect the state of the driveItem are pending completion. Read-only.
| photo                | [photo][]          | Photo metadata, if the item is a photo. Read-only.
| publication          | [publicationFacet][] | Provides information about the published or checked-out state of an item, in locations that support such actions. This property isn't returned by default. Read-only. |
| remoteItem           | [remoteItem][]     | Remote item data, if the item is shared from a drive other than the one being accessed. Read-only.
| root                 | [root][]           | If this property is non-null, it indicates that the driveItem is the top-most driveItem in the drive.
| searchResult         | [searchResult][]   | Search metadata, if the item is from a search result. Read-only.
| shared               | [shared][]         | Indicates that the item was shared with others and provides information about the shared state of the item. Read-only.
| sharepointIds        | [sharepointIds][]  | Returns identifiers useful for SharePoint REST compatibility. Read-only.
| size                 | Int64              | Size of the item in bytes. Read-only.
| specialFolder        | [specialFolder][]  | If the current item is also available as a special folder, this facet is returned. Read-only.
| video                | [video][]          | Video metadata, if the item is a video. Read-only.
| webDavUrl            | String             | WebDAV compatible URL for the item.
| webUrl               | String             | URL that displays the resource in the browser. Read-only.

### [itemReference ](https://docs.microsoft.com/graph/api/resources/itemreference?view=graph-rest-1.0&tabs=http)
| Property      | Type              | Description
|:--------------|:------------------|:-----------------------------------------
| driveId       | String            | Unique identifier of the drive instance that contains the driveItem. Only returned if the item is located in a [drive][]. Read-only.
| driveType     | String            | Identifies the type of drive. Only returned if the item is located in a [drive][]. See [drive][] resource for values.
| id            | String            | Unique identifier of the driveItem in the drive or a listItem in a list. Read-only.
| name          | String            | The name of the item being referenced. Read-only.
| path          | String            | Percent-encoded path that can be used to navigate to the item. Read-only.
| shareId       | String            | A unique identifier for a shared resource that can be accessed via the [Shares][] API.
| sharepointIds | [sharepointIds][] | Returns identifiers useful for SharePoint REST compatibility. Read-only.
| siteId        | String            | For OneDrive for Business and SharePoint, this property represents the ID of the site that contains the parent document library of the driveItem resource or the parent list of the listItem resource. The value is the same as the id property of that site][] resource. It is an [opaque string that consists of three identifiers of the site. <br>For OneDrive, this property is not populated.

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
### [listItem ](https://docs.microsoft.com/graph/api/resources/listitem?view=graph-rest-1.0&tabs=http)
| Property    | Type                | Description                        |
|:------------|:--------------------|:-----------------------------------|
| contentType | [contentTypeInfo][] | The content type of this list item |
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
### [richLongRunningOperation ](https://docs.microsoft.com/graph/api/resources/richlongrunningoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when this operation was created.|
|error|publicError| Error that caused the operation to fail.|
|id|String|Unique identifier for the operation. Inherited from entity.|
|lastActionDateTime|DateTimeOffset| The date and time when the last action was performed on this operation.|
|percentageComplete|Int32|A value between 0 and 100 that indicates the progress of the operation.|
|resourceId|String|The unique identifier for the result.|
|resourceLocation|String|The canonical URL of the resource.|
|status|longRunningOperationStatus|The status of the long-running operation. Possible values are: `notStarted`, `running`, `succeeded`, `failed`, `unknownFutureValue`.|
|statusDetail|String|The detail about the status value.|
|type|String| The type of the operation.|
### [SharePointIds ](https://docs.microsoft.com/graph/api/resources/sharepointids?view=graph-rest-1.0&tabs=http)
| Property         | Type         | Description
|:-----------------|:-------------|:-------------------------------------------
| listId           | string       | The unique identifier (guid) for the item's list in SharePoint.
| listItemId       | string       | An integer identifier for the item within the containing list.
| listItemUniqueId | string       | The unique identifier (guid) for the item within OneDrive for Business or a SharePoint site.
| siteId           | string       | The unique identifier (guid) for the item's site collection (SPSite).
| siteUrl          | string (url) | The SharePoint URL for the site that contains the item.
| tenantId         | string       | The unique identifier (guid) for the tenancy.
| webId            | string       | The unique identifier (guid) for the item's site (SPWeb).

### [site ](https://docs.microsoft.com/graph/api/resources/site?view=graph-rest-1.0&tabs=http)
| Property            | Type                                | Description                                                                                    |
| :----------------------- | :---------------------------------- | :--------------------------------------------------------------------------------------------- |
| **createdDateTime**      | DateTimeOffset                      | The date and time the item was created. Read-only.                                             |
| **description**          | string                              | The descriptive text for the site.                                                             |
| **displayName**          | string                              | The full title for the site. Read-only.                                                        |
| **eTag**                 | string                              | ETag for the item. Read-only.                                                                  |
| **id**                   | string                              | The unique identifier of the item. Read-only.                                                  |
| **isPersonalSite**       | bool                                | Identifies whether the site is personal or not. Read-only.                                                  |
| **lastModifiedDateTime** | DateTimeOffset                      | The date and time the item was last modified. Read-only.                                       |
| **name**                 | string                              | The name/title of the item.                                                                  |
| **root**                 | root                     | If present, provides the root site in the site collection. Read-only.            |
| **sharepointIds**        | sharepointIds   | Returns identifiers useful for SharePoint REST compatibility. Read-only.                       |
| **siteCollection**       | siteCollection | Provides details about the site's site collection. Available only on the root site. Read-only. |
| **webUrl**               | string (url)                        | URL that displays the item in the browser. Read-only.                                          |
### [workbookNamedItem ](https://docs.microsoft.com/graph/api/resources/workbooknameditem?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|comment|String|The comment associated with this name.|
|name|String|The name of the object. Read-only.|
|scope|String|Indicates whether the name is scoped to the workbook or to a specific worksheet. Read-only.|
|type|String|The type of reference is associated with the name. Possible values are: `String`, `Integer`, `Double`, `Boolean`, `Range`. Read-only.|
|value|String|The formula that the name is defined to refer to. For example, `=Sheet14!$B$2:$H$12` and `=4.75`. Read-only.|
|visible|Boolean|Indicates whether the object is visible.|
