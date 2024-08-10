# PrintJob.ReadWriteBasic.All

> Allows the application to read and update the metadata of print jobs on behalf of the signed-in user. Does not allow access to print job document content.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /print/printers/{id}/jobs](https://docs.microsoft.com/graph/api/printer-list-jobs?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /print/printers/{id}/jobs/{id}](https://docs.microsoft.com/graph/api/printjob-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /print/printers/{printerId}/jobs](https://docs.microsoft.com/graph/api/printer-list-jobs?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services](https://docs.microsoft.com/graph/api/print-list-services?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/services/{id}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints/{name}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints/{printServiceEndpointId}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /print/shares/{id}/jobs](https://docs.microsoft.com/graph/api/printershare-list-jobs?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /print/shares/{printerShareId}/jobs](https://docs.microsoft.com/graph/api/printershare-list-jobs?view=graph-rest-1.0&tabs=http)|
|Beta|A|[PATCH /print/printers/{id}/jobs/{id}](https://docs.microsoft.com/graph/api/printjob-update?view=graph-rest-beta&tabs=http)|
|V1|A|[PATCH /print/printers/{printerId}/jobs/{printJobId}](https://docs.microsoft.com/graph/api/printjob-update?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /print/printers/{id}/jobs/{id}/abort](https://docs.microsoft.com/graph/api/printjob-abort?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /print/printers/{id}/jobs/{id}/cancel](https://docs.microsoft.com/graph/api/printjob-cancel?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /print/printers/{printerId}/jobs](https://docs.microsoft.com/graph/api/printer-post-jobs?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /print/printers/{printerId}/jobs/{printJobId}/abort](https://docs.microsoft.com/graph/api/printjob-abort?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /print/printers/{printerId}/jobs/{printJobId}/cancel](https://docs.microsoft.com/graph/api/printjob-cancel?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /print/shares/{id}/jobs/{id}/start](https://docs.microsoft.com/graph/api/printjob-start?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /print/shares/{printerShareId}/jobs](https://docs.microsoft.com/graph/api/printershare-post-jobs?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /print/shares/{printerShareId}/jobs/{printJobId}/start](https://docs.microsoft.com/graph/api/printjob-start?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST print/printers/{id}/jobs](https://docs.microsoft.com/graph/api/printer-post-jobs?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST print/shares/{id}/jobs](https://docs.microsoft.com/graph/api/printershare-post-jobs?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|3a0db2f6-0d2a-4c19-971b-49109b19ad3d|
|**Consent Type**|Admin|
|**Display String**|Read and write basic information of print jobs|
|**Description**|Allows the application to read and update the metadata of print jobs on behalf of the signed-in user. Does not allow access to print job document content.|
## Application Permission
|||
|-|-|
|**Id**|57878358-37f4-4d3a-8c20-4816e0d457b1|
|**Display String**|Read and write basic information for print jobs|
|**Description**|Allows the application to read and update the metadata of print jobs without a signed-in user. Does not allow access to print job document content.|
## Resources
### [printDocument ](https://docs.microsoft.com/graph/api/resources/printdocument?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentType|String|The document's content (MIME) type. Read-only.|
|displayName|String|The document's name. Read-only.|
|id|String|The document's identifier. Read-only.|
|size|Int64|The document's size in bytes. Read-only.|
### [printer ](https://docs.microsoft.com/graph/api/resources/printer?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|capabilities|printerCapabilities|The capabilities of the printer associated with this printer share. Inherited from printerBase.|
|defaults|printerDefaults|The printer's default print settings. Inherited from printerBase.|
|displayName|String|The name of the printer. Inherited from printerBase.|
|hasPhysicalDevice|Boolean|True if the printer has a physical device for printing. Read-only.|
|id|String|The document's identifier. Inherited from printerBase. Read-only.|
|isAcceptingJobs|Boolean|True if the printer is currently accepting new print jobs. Inherited from printerBase.|
|isShared|Boolean|True if the printer is shared; false otherwise. Read-only.|
|lastSeenDateTime|DateTimeOffset|The most recent dateTimeOffset when a printer interacted with Universal Print. Read-only.|
|location|printerLocation|The physical and/or organizational location of the printer. Inherited from printerBase.|
|manufacturer|String|The manufacturer reported by the printer. Inherited from printerBase.|
|model|String|The model name reported by the printer. Inherited from printerBase.|
|registeredDateTime|DateTimeOffset|The DateTimeOffset when the printer was registered. Read-only.|
|status|printerStatus|The processing status of the printer, including any errors. Inherited from printerBase.|
### [printerShare ](https://docs.microsoft.com/graph/api/resources/printershare?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowAllUsers|Boolean|If true, all users and groups will be granted access to this printer share. This supersedes the allow lists defined by the **allowedUsers** and **allowedGroups** navigation properties.|
|capabilities|printerCapabilities|The capabilities of the printer associated with this printer share. Inherited from printerBase.|
|createdDateTime|DateTimeOffset|The DateTimeOffset when the printer share was created. Read-only.|
|defaults|printerDefaults|The default print settings of the printer associated with this printer share. Inherited from printerBase.|
|displayName|String|The name of the printer share that print clients should display. Inherited from printerBase.|
|id|String| The printerShare's identifier. Inherited from printerBase. Read-only.|
|isAcceptingJobs|Boolean|Whether the printer associated with this printer share is currently accepting new print jobs. Inherited from printerBase.|
|location|printerLocation|The physical and/or organizational location of the printer associated with this printer share. Inherited from printerBase.|
|manufacturer|String|The manufacturer reported by the printer associated with this printer share. Inherited from printerBase. Read-only.|
|model|String|The model name reported by the printer associated with this printer share. Inherited from printerBase. Read-only.|
|status|printerStatus|The processing status, including any errors, of the printer associated with this printer share.Inherited from printerBase. Read-only.|
|viewPoint|printerShareViewpoint|Additional data for a printer share as viewed by the signed-in user.|
### [printJob ](https://docs.microsoft.com/graph/api/resources/printjob?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|configuration|printJobConfiguration|A group of settings that a printer should use to print a job.|
|createdBy|userIdentity| Read-only. Nullable.|
|createdDateTime|DateTimeOffset|The DateTimeOffset when the job was created. Read-only.|
|id|String|The ID of the print job. Read-only.|
|isFetchable|Edm.Boolean|If true, document can be fetched by printer.|
|redirectedFrom|Edm.String|Contains the source job URL, if the job has been redirected from another printer.|
|redirectedTo|Edm.String|Contains the destination job URL, if the job has been redirected to another printer.|
|status|printJobStatus|The status of the print job. Read-only.|
### [printJobStatus ](https://docs.microsoft.com/graph/api/resources/printjobstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|A human-readable description of the print job's current processing state. Read-only.|
|details|printJobProcessingDetail collection|Additional details for print job state. Valid values are described in the following table. Read-only.|
|isAcquiredByPrinter|Boolean|True if the job was acknowledged by a printer; false otherwise. Read-only.|
|state|printJobProcessingState|The print job's current processing state. Valid values are described in the following table. Read-only.|
### [printService ](https://docs.microsoft.com/graph/api/resources/printservice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the service. Read-only.|
### [printServiceEndpoint ](https://docs.microsoft.com/graph/api/resources/printserviceendpoint?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|A human-readable display name for the endpoint.|
|id|String|A unique name that identifies the service that the endpoint provides. Possible values are: `discovery` (Discovery Service), `notification` (Notification Service), `ipp` (IPP Service), and `registration` (Registration Service). Read-only.|
|uri|String|The URI that can be used to access the service.|
### [printTask ](https://docs.microsoft.com/graph/api/resources/printtask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The printTask's identifier. Read-only.|
|status|printTaskStatus|The current execution status of this printTask. **The calling application is responsible for updating this status when processing is finished, unless the related printJob has been redirected to another printer.** Failure to report completion will result in the related print job being blocked from printing and eventually deleted. |
|parentUrl|String|The URL for the print entity that triggered this task. For example, `https://graph.microsoft.com/v1.0/print/printers/{printerId}/jobs/{jobId}`. Read-only.|
