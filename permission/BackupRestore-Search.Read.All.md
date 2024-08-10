# BackupRestore-Search.Read.All

> Allows the app to search the backup snapshots for Microsoft 365 resources, on behalf of the signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[POST /solutions/backupRestore/restorePoints/search](https://docs.microsoft.com/graph/api/restorepoint-search?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|2b24830f-f435-446f-ab5a-b1e70d9a2eb5|
|**Consent Type**|Admin|
|**Display String**|Search for metadata properties in backup snapshots|
|**Description**|Allows the app to search the backup snapshots for Microsoft 365 resources, on behalf of the signed in user.|
## Application Permission
|||
|-|-|
|**Id**|f6135c51-c766-4be1-9638-ed90c2ed2443|
|**Display String**|Search for metadata properties in all backup snapshots|
|**Description**|Allows the app to search all backup snapshots for Microsoft 365 resources, without a signed-in user.|
## Resources
### [artifactQuery ](https://docs.microsoft.com/graph/api/resources/artifactquery?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|artifactType|restorableArtifact|The type of artifact to search. The possible values are: `message`, `unknownFutureValue`.|
|queryExpression|String|Specifies criteria to retrieve artifacts.|
### [protectionUnitBase ](https://docs.microsoft.com/graph/api/resources/protectionunitbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection unit.|
|policyId|String|The unique identifier of the protection policy based on which protection unit was created.|
|createdBy|identitySet|The identity of person who created the protection unit.|
|createdDateTime|DateTimeOffset|The time of creation of the protection unit.|
|error|publicError|Contains error details if an error occurred while creating a protection unit.|
|lastModifiedBy|identitySet|The identity of person who last modified the protection unit.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification of this protection unit.|
|status|protectionUnitStatus|The status of the protection unit. The possible values are: `protectRequested`, `protected`, `unprotectRequested`, `unprotected`, `removeRequested`, `unknownFutureValue`.|
### [restorePoint ](https://docs.microsoft.com/graph/api/resources/restorepoint?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|ID of the restore point.|
|protectionDateTime|DateTimeOffset|Date time when the restore point was created.|
|expirationDateTime|DateTimeOffset|Expiration date time of the restore point.|
|tags|restorePointTags|The type of the restore point. The possible values are: `none`, `fastRestore`, `unknownFutureValue`.|
### [restorePointSearchResponse ](https://docs.microsoft.com/graph/api/resources/restorepointsearchresponse?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|noResultProtectionUnitIds|String collection|Contains  alist of protection units with no restore points.|
|searchResponseId|String|The unique identifier of the search response.|
|searchResults|restorePointSearchResult collection|Contains a collection of restore points.|
### [timePeriod ](https://docs.microsoft.com/graph/api/resources/timeperiod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|endDateTime|DateTimeOffset|The date time of the end of the time period.|
|startDateTime|DateTimeOffset|The date time of the start of the time period.|
