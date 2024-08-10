# BitlockerKey.ReadBasic.All

> Allows the app to read basic BitLocker key properties on behalf of the signed-in user, for their owned devices. Does not allow read of the recovery key itself.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /informationProtection/bitlocker/recoveryKeys](https://docs.microsoft.com/graph/api/bitlocker-list-recoverykeys?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /informationProtection/bitlocker/recoveryKeys/{bitlockeryRecoveryKeyId}](https://docs.microsoft.com/graph/api/bitlockerrecoverykey-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5a107bfc-4f00-4e1a-b67e-66451267bc68|
|**Consent Type**|Admin|
|**Display String**|Read BitLocker keys basic information|
|**Description**|Allows the app to read basic BitLocker key properties on behalf of the signed-in user, for their owned devices. Does not allow read of the recovery key itself.|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [bitlockerRecoveryKey ](https://docs.microsoft.com/graph/api/resources/bitlockerrecoverykey?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when the key was originally backed up to Microsoft Entra ID. Not nullable.|
|deviceId|String|Identifier of the device the BitLocker key is originally backed up from. Supports `$filter` (`eq`).|
|id|String|The unique identifier for the BitLocker key.|
|key|String|The BitLocker recovery key. Returned only on `$select`. Not nullable.|
|volumeType|volumeType|Indicates the type of volume the BitLocker key is associated with. The possible values are: `1` (for `operatingSystemVolume`), `2` (for `fixedDataVolume`), `3` (for `removableDataVolume`), and `4` (for `unknownFutureValue`).|
