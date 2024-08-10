# BackupRestore-Control.Read.All

> Allows the app to read the status of M365 backup service (enable/disable), on behalf of the signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /solutions/backupRestore](https://docs.microsoft.com/graph/api/backuprestoreroot-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/serviceApps](https://docs.microsoft.com/graph/api/backuprestoreroot-list-serviceapps?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/serviceApps/{serviceAppId}](https://docs.microsoft.com/graph/api/serviceapp-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|af598c63-4292-4437-b925-e996354d3854|
|**Consent Type**|Admin|
|**Display String**|Read the status of the M365 backup service|
|**Description**|Allows the app to read the status of M365 backup service (enable/disable), on behalf of the signed in user.|
## Application Permission
|||
|-|-|
|**Id**|6fe20a79-0e15-45a1-b019-834c125993a0|
|**Display String**|Read the status of the M365 backup service|
|**Description**|Allows the app to read the status of M365 backup service (enable/disable), without signed in user|
## Resources
### [backupRestoreRoot ](https://docs.microsoft.com/graph/api/resources/backuprestoreroot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|ID of the Backup Storage service.|
|serviceStatus|serviceStatus|Represents the tenant-level status of the Backup Storage service.|
### [serviceApp ](https://docs.microsoft.com/graph/api/resources/serviceapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|application|identity|The Entra ID application ID.|
|effectiveDateTime|DateTimeOffset|Timestamp of the effective activation of the service app.|
|id|String|The unique identifier of the service app.|
|lastModifiedBy|identitySet|Identity of the person who last modified the entity.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification of the entity.|
|registrationDateTime|DateTimeOffset|Timestamp of the creation of the service app entity.|
|status|serviceAppStatus|The status of the service app. This value indicates whether or not the application can be used to control the backup service. The possible values are: `inactive`, `active`, `pendingActive`, `pendingInactive`, `unknownFutureValue`.|
### [serviceStatus ](https://docs.microsoft.com/graph/api/resources/servicestatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|backupServiceConsumer|backupServiceConsumer|The type of consumer. The possible values are: `unknown`, `firstparty`, `thirdparty`, `unknownFutureValue`.|
|disableReason|disableReason|The reason the service is disabled. The possible values are: `none`, `controllerServiceAppDeleted`, `invalidBillingProfile`, `userRequested`, `unknownFutureValue`.|
|gracePeriodDateTime|DateTimeOffset|The expiration time of the grace period.|
|lastModifiedBy|identitySet|Identity of the person who last modified the entity.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification of the entity.|
|restoreAllowedTillDateTime|DateTimeOffset|The expiration time of the restoration allowed period.|
|status|backupServiceStatus|Status of the service. This value indicates what capabilities can be used. The possible values are: `disabled`, `enabled`, `protectionChangeLocked`, `restoreLocked`, `unknownFutureValue`.|
