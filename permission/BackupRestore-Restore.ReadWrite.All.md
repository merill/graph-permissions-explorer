# BackupRestore-Restore.ReadWrite.All

> Allows the app to search the backup snapshots for Microsoft 365 resources, and restore Microsoft 365 resources from a backed up snapshot, on behalf of the signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /solutions/backupRestore/restoreSessions/{restoreSessionBaseId}](https://docs.microsoft.com/graph/api/restoresessionbase-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/restorePoints?$expand=protectionUnit($filter=id eq '{ProtectionUnitID}')&$filter=protectionDateTime lt YYYY-MM-DDTHH:mm:ssZ](https://docs.microsoft.com/graph/api/backuprestoreroot-list-restorepoints?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /solutions/backupRestore/exchangeRestoreSessions/{exchangeRestoreSessionId}](https://docs.microsoft.com/graph/api/exchangerestoresession-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /solutions/backupRestore/oneDriveForBusinessRestoreSessions/{oneDriveForBusinessRestoreSessionId}](https://docs.microsoft.com/graph/api/onedriveforbusinessrestoresession-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /solutions/backupRestore/sharePointRestoreSessions/{sharePointRestoreSessionId}](https://docs.microsoft.com/graph/api/sharepointrestoresession-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /solutions/backupRestore/exchangeRestoreSessions](https://docs.microsoft.com/graph/api/backuprestoreroot-post-exchangerestoresessions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /solutions/backupRestore/oneDriveForBusinessRestoreSessions](https://docs.microsoft.com/graph/api/backuprestoreroot-post-onedriveforbusinessrestoresessions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /solutions/backupRestore/restoreSessions/{restoreSessionBaseId}/activate](https://docs.microsoft.com/graph/api/restoresessionbase-activate?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /solutions/backupRestore/sharePointRestoreSessions](https://docs.microsoft.com/graph/api/backuprestoreroot-post-sharepointrestoresessions?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9f89e109-94b9-4c9b-b4fc-98cdaa54f574|
|**Consent Type**|Admin|
|**Display String**|Read restore sessions and start restore sessions from backups|
|**Description**|Allows the app to search the backup snapshots for Microsoft 365 resources, and restore Microsoft 365 resources from a backed up snapshot, on behalf of the signed in user.|
## Application Permission
|||
|-|-|
|**Id**|bebd0841-a3d8-4313-a51d-731112c8ee41|
|**Display String**|Read restore all sessions and start restore sessions from backups|
|**Description**|Allows the app to search all backup snapshots for Microsoft 365 resources, and restore Microsoft 365 resources from a backed up snapshot, without a signed-in user.|
## Resources
### [driveRestoreArtifact ](https://docs.microsoft.com/graph/api/resources/driverestoreartifact?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore artifact.|
|completionDateTime|DateTimeOffset|The time when restoration of restore artifact is completed. Inherited from restoreArtifactBase.|
|destinationType|destinationType|The restoration destination. Inherited from restoreArtifactBase. The possible values are: `new`, `inPlace`, `unknownFutureValue`.|
|error|publicError|Contains error details if the restoration fails. Inherited from restoreArtifactBase.|
|restoredSiteId|String|The new site identifier if **destinationType** is `new`, and the input site ID if the **destinationType** is `inPlace`.|
|restoredSiteName|String|The name of the restored site.|
|restoredSiteWebUrl|String|The web URL of the restored site.|
|startDateTime|DateTimeOffset|The time when the restoration started. Inherited from restoreArtifactBase.|
|status|artifactRestoreStatus|The individual restoration status of the restore artifact. Inherited from restoreArtifactBase. The possible values are: `added`, `scheduling`, `scheduled`, `inProgress`, `succeeded`, `failed`, `unknownFutureValue`.|
### [exchangeRestoreSession ](https://docs.microsoft.com/graph/api/resources/exchangerestoresession?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore session created.|
|completedDateTime|DateTimeOffset|The time of creation of the restore session.|
|createdBy|identitySet|The identity of person who created the restore session.|
|createdDateTime|DateTimeOffset|The time of completion of the restore session.|
|error|publicError|Contains error details if the restore session fails or completes with an error.|
|lastModifiedBy|identitySet|Identity of the person who last modified this restore session.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of last modification of this restore session.|
|status|restoreSessionStatus|Status of the restore session. The value is an aggregated status of the restored artifacts. The possible values are: `draft`, `activating`, `active`, `completedWithError`, `completed`, `unknownFutureValue`, `failed`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `failed`.|
### [granularMailboxRestoreArtifact ](https://docs.microsoft.com/graph/api/resources/granularmailboxrestoreartifact?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|artifactCount|int|.|
|id|String|The unique identifier of the restore artifact.|
|completionDateTime|DateTimeOffset|The time when the restoration of the artifact is completed. Inherited from restoreArtifactBase.|
|destinationType|destinationType|Indicates the restoration destination. Inherited from restoreArtifactBase. The possible values are: `new`, `inPlace`, `unknownFutureValue`.|
|error|publicError|Contains error details if the restoration of the artifact fails. Inherited from restoreArtifactBase.|
|restoredFolderId|String|The new restored folder identifier for the user.|
|restoredFolderName|String|The new restored folder name.|
|searchResponseId|String|.|
|startDateTime|DateTimeOffset|The time when the restoration of the artifact started. Inherited from restoreArtifactBase.|
|status|artifactRestoreStatus|The restoration status of the artifact. Inherited from restoreArtifactBase.T he possible values are: `added`, `scheduling`, `scheduled`, `inProgress`, `succeeded`, `failed`, `unknownFutureValue`.|
### [mailboxRestoreArtifact ](https://docs.microsoft.com/graph/api/resources/mailboxrestoreartifact?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore artifact.|
|completionDateTime|DateTimeOffset|The time when the restoration of the artifact is completed. Inherited from restoreArtifactBase.|
|destinationType|destinationType|Indicates the restoration destination. Inherited from restoreArtifactBase. The possible values are: `new`, `inPlace`, `unknownFutureValue`.|
|error|publicError|Contains error details if the restoration of the artifact fails. Inherited from restoreArtifactBase.|
|restoredFolderId|String|The new restored folder identifier for the user.|
|restoredFolderName|String|The new restored folder name.|
|startDateTime|DateTimeOffset|The time when the restoration of the artifact started. Inherited from restoreArtifactBase.|
|status|artifactRestoreStatus|The restoration status of the artifact. Inherited from restoreArtifactBase.T he possible values are: `added`, `scheduling`, `scheduled`, `inProgress`, `succeeded`, `failed`, `unknownFutureValue`.|
### [oneDriveForBusinessRestoreSession ](https://docs.microsoft.com/graph/api/resources/onedriveforbusinessrestoresession?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore session created.|
|completedDateTime|DateTimeOffset|The time of creation of the restore session.|
|createdBy|identitySet|The identity of person who created the restore session.|
|createdDateTime|DateTimeOffset|The time of completion of the restore session.|
|error|publicError|Contains error details if the restore session fails or completes with an error.|
|lastModifiedBy|identitySet|Identity of the person who last modified this restore session.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification of this restore session.|
|status|restoreSessionStatus|Status of the restore session. The value is an aggregated status of the restored artifacts. The possible values are: `draft`, `activating`, `active`, `completedWithError`, `completed`, `unknownFutureValue`, `failed`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `failed`.|
### [restorePoint ](https://docs.microsoft.com/graph/api/resources/restorepoint?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|ID of the restore point.|
|protectionDateTime|DateTimeOffset|Date time when the restore point was created.|
|expirationDateTime|DateTimeOffset|Expiration date time of the restore point.|
|tags|restorePointTags|The type of the restore point. The possible values are: `none`, `fastRestore`, `unknownFutureValue`.|
### [restoreSessionBase ](https://docs.microsoft.com/graph/api/resources/restoresessionbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore session.|
|completedDateTime|DateTimeOffset|The time of completion of the restore session.|
|createdBy|identitySet|The identity of person who created the restore session.|
|createdDateTime|DateTimeOffset|The time of creation of the restore session.|
|error|publicError|Contains error details if the restore session fails or completes with an error.|
|lastModifiedBy|identitySet|Identity of the person who last modified the restore session.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification of the restore session.|
|status|restoreSessionStatus|Status of the restore session. The value is an aggregated status of the restored artifacts. The possible values are: `draft`, `activating`, `active`, `completedWithError`, `completed`, `unknownFutureValue`, `failed`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `failed`.|
### [sharePointRestoreSession ](https://docs.microsoft.com/graph/api/resources/sharepointrestoresession?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore session.|
|completedDateTime|DateTimeOffset|The time of creation of the restore session.|
|createdBy|identitySet|The identity of person who created the restore session.|
|createdDateTime|DateTimeOffset|The time of completion of the restore session.|
|error|publicError|Contains error details if the restore session fails or is completed with error.|
|lastModifiedBy|identitySet|Identity of the person who last modified this restore session.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of last modification of this restore session.|
|status|restoreSessionStatus|Status of the restore session. The value is an aggregated status of restore artifacts. The possible values are: `draft`, `activating`, `active`, `completedWithError`, `completed`, `unknownFutureValue`, `failed`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `failed`.|
### [siteRestoreArtifact ](https://docs.microsoft.com/graph/api/resources/siterestoreartifact?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the restore artifact.|
|completionDateTime|DateTimeOffset|The time when restoration of restore artifact is completed. Inherited from restoreArtifactBase.|
|destinationType|destinationType|Indicates the restoration destination. Inherited from restoreArtifactBase. The possible values are: `new`, `inPlace`, `unknownFutureValue`.|
|error|publicError|Contains error details if the restoration of the restore artifact fails. Inherited from restoreArtifactBase.|
|restoredSiteId|String|The new site identifier if the value of the **destinationType** property is `new`, and the existing site ID if the value is `inPlace`.|
|restoredSiteName|String|The name of the restored site.|
|restoredSiteWebUrl|String|The web URL of the restored site.|
|startDateTime|DateTimeOffset|The time when restoration of the restore artifact started. Inherited from restoreArtifactBase.|
|status|artifactRestoreStatus|The restoration status of the restore artifact. Inherited from restoreArtifactBase. The possible values are: `added`, `scheduling`, `scheduled`, `inProgress`, `succeeded`, `failed`, `unknownFutureValue`.|
