# PartnerBilling.Read.All

> Allows the app to read all of billing data from Microsoft for your company's tenant, on behalf of the signed-in user. This includes reading billed and unbilled Usage and Invoice reconciliation data.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /reports/partners/billing/manifests/{id}](https://docs.microsoft.com/graph/api/partners-billing-manifest-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/partners/billing/operations/{id}](https://docs.microsoft.com/graph/api/partners-billing-operation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /reports/partners/billing/reconciliation/billed/export](https://docs.microsoft.com/graph/api/partners-billing-billedreconciliation-export?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /reports/partners/billing/usage/billed/export](https://docs.microsoft.com/graph/api/partners-billing-billedusage-export?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /reports/partners/billing/usage/unbilled/export](https://docs.microsoft.com/graph/api/partners-billing-unbilledusage-export?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8804798e-5934-4e30-8ce3-ef88257cecd4|
|**Consent Type**|Admin|
|**Display String**|Read all billing data for your company's tenant|
|**Description**|Allows the app to read all of billing data from Microsoft for your company's tenant, on behalf of the signed-in user. This includes reading billed and unbilled Usage and Invoice reconciliation data.|
## Application Permission
|||
|-|-|
|**Id**|7c3e1994-38ff-4412-a99b-9369f6bb7706|
|**Display String**|Read all billing data for your company's tenant|
|**Description**|Allows the app to read all of billing data from Microsoft for your company's tenant, without a signed-in user. This includes reading billed and unbilled azure usage and invoice reconciliation data.|
## Resources
### [partners-billing-attributeset](https://docs.microsoft.com/graph/api/resources/partners-billing-attributeset?view=graph-rest-1.0&tabs=http)

### [exportSuccessOperation ](https://docs.microsoft.com/graph/api/resources/partners-billing-exportsuccessoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The start time of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from operation.|
|id|String|The unique identifier for the **exportSuccessOperation**. Inherited from operation.|
|lastActionDateTime|DateTimeOffset|The time of the last action of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from operation.|
|status|microsoft.graph.longRunningOperationStatus|The status of the operation. Supports a subset of the values for **l
### [failedOperation ](https://docs.microsoft.com/graph/api/resources/partners-billing-failedoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The start time of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from operation.|
|id|String|The unique identifier for the **failedOperation**. Inherited from operation.|
|lastActionDateTime|DateTimeOffset|The time of the last action of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from operation.|
|status|microsoft.graph.longRunningOperationStatus|The status of the operation. Supports a subset of the values for **l
### [manifest ](https://docs.microsoft.com/graph/api/resources/partners-billing-manifest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|blobCount|Int32|The total file count for this partner tenant ID.|
|blobs|microsoft.graph.partners.billing.blob collection|A collection of blob objects that contain details of all the files for the partner tenant ID.|
|createdDateTime|DateTimeOffset|The date and time when a manifest resource was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|dataFormat|String|The billing data file format. The possible value is: `compressedJSONLines`. Each blob is a compressed file and data in the file is in JSON lines format. Decompress the file to access the data.|
|eTag|String|Version of data represented by the manifest. Any change in **eTag** indicates a new data version.|
|id|String|The unique identifier for the **manifest**. Inherited from entity.|
|partitionType|String|Indicates the division of data. If a given partition has more than the supported number, the data is split into multiple files, each file representing a specific **partitionValue**. By default, the data in the file is partitioned by the number of line items.|
|partnerTenantId|String|The Microsoft Entra tenant ID of the partner.|
|rootDirectory|String|The root directory that contains all the files.|
|sasToken|String|The SAS token for accessing the directory or an individual file in the directory.|
|schemaVersion|String|The version of the manifest schema.|
### [operation ](https://docs.microsoft.com/graph/api/resources/partners-billing-operation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The start time of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String|The unique identifier for the **operation**. Inherited from entity.|
|lastActionDateTime|DateTimeOffset|The time of the last action of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|status|microsoft.graph.longRunningOperationStatus|The status of the operation. Possible values are: `notStarted`, `running`, `completed`, `failed`, `unknownFutureValue`.|
### [runningOperation ](https://docs.microsoft.com/graph/api/resources/partners-billing-runningoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The start time of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from operation.|
|id|String|The unique identifier for the **runningOperation**. Inherited from operation.|
|lastActionDateTime|DateTimeOffset|The time of the last action of the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from operation.|
|status|microsoft.graph.longRunningOperationStatus|The status of the operation. Supports a subset of the values for **l
### [unbilledUsage ](https://docs.microsoft.com/graph/api/resources/partners-billing-unbilledusage?view=graph-rest-1.0&tabs=http)

