# FileStorageContainer.Manage.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /deletedStorageContainers/{containerId}](https://docs.microsoft.com/graph/api/filestorage-delete-deletedcontainers?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /storage/fileStorage/containers/{containerId}](https://docs.microsoft.com/graph/api/filestorage-delete-containers?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /deletedStorageContainers?$filter=containerTypeId eq {containerTypeId}](https://docs.microsoft.com/graph/api/filestorage-list-deletedcontainers?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /deletedStorageContainers/{containerId}](https://docs.microsoft.com/graph/api/filestorage-get-deletedcontainers?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /deletedStorageContainers/{containerId}/restore](https://docs.microsoft.com/graph/api/filestoragecontainer-restore?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /storageContainers/{containerId}/lock](https://docs.microsoft.com/graph/api/filestoragecontainer-lock?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /storageContainers/{containerId}/permanentDelete](https://docs.microsoft.com/graph/api/filestoragecontainer-permanentdelete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /storageContainers/{containerId}/unlock](https://docs.microsoft.com/graph/api/filestoragecontainer-unlock?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
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
