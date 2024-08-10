# BackupRestore-Restore.Read.All

> Allows the app to read restore sessions, on behalf of the signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /solutions/backupRestore/exchangeRestoreSessions/{exchangeRestoreSessionId}/mailboxRestoreArtifacts](https://docs.microsoft.com/graph/api/exchangerestoresession-list-mailboxrestoreartifacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/oneDriveForBusinessRestoreSessions/{oneDriveForBusinessRestoreSessionId}/driveRestoreArtifacts](https://docs.microsoft.com/graph/api/onedriveforbusinessrestoresession-list-driverestoreartifacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/restorePoints?$expand=protectionUnit($filter=id eq '{ProtectionUnitID}')&$filter=protectionDateTime lt YYYY-MM-DDTHH:mm:ssZ](https://docs.microsoft.com/graph/api/backuprestoreroot-list-restorepoints?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/restoreSessions](https://docs.microsoft.com/graph/api/backuprestoreroot-list-restoresessions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/restoreSessions/{restoreSessionBaseId}](https://docs.microsoft.com/graph/api/restoresessionbase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/sharePointRestoreSessions/{sharePointRestoreSessionId}/siteRestoreArtifacts](https://docs.microsoft.com/graph/api/sharepointrestoresession-list-siterestoreartifacts?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|94b36f78-434f-4904-8c08-421d9a9c1dc2|
|**Consent Type**|Admin|
|**Display String**|Read restore sessions|
|**Description**|Allows the app to read restore sessions, on behalf of the signed in user.|
## Application Permission
|||
|-|-|
|**Id**|87853aa5-0372-4710-b34b-cef27bb7156e|
|**Display String**|Read all restore sessions|
|**Description**|Allows the app to read all restore sessions, without a signed-in user.|
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
