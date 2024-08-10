# PrintJob.Create

> Allows the application to create print jobs on behalf of the signed-in user and upload document content to print jobs that the signed-in user created.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /print/services](https://docs.microsoft.com/graph/api/print-list-services?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/services/{id}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints/{name}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints/{printServiceEndpointId}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /print/printers/{id}/jobs/{id}/documents/{id}/createUploadSession](https://docs.microsoft.com/graph/api/printdocument-createuploadsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /print/printers/{printerId}/jobs](https://docs.microsoft.com/graph/api/printer-post-jobs?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /print/shares/{id}/jobs/{id}/start](https://docs.microsoft.com/graph/api/printjob-start?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /print/shares/{printerShareId}/jobs/{printJobId}/start](https://docs.microsoft.com/graph/api/printjob-start?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST print/printers/{id}/jobs](https://docs.microsoft.com/graph/api/printer-post-jobs?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|21f0d9c0-9f13-48b3-94e0-b6b231c7d320|
|**Consent Type**|User|
|**Display String**|Create print jobs|
|**Description**|Allows the application to create print jobs on behalf of the signed-in user and upload document content to print jobs that the signed-in user created.|
## Resources
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
### [printerCapabilities ](https://docs.microsoft.com/graph/api/resources/printercapabilities?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|bottomMargins|Int32 collection|A list of supported bottom margins(in microns) for the printer.|
|collation|Boolean|True if the printer supports collating when printing muliple copies of a multi-page document; false otherwise.|
|colorModes|printColorMode collection|The color modes supported by the printer. Valid values are described in the following table.|
|contentTypes|String collection|A list of supported content (MIME) types that the printer supports. It is not guaranteed that the Universal Print service supports printing all of these MIME types.|
|copiesPerJob|integerRange|The range of copies per job supported by the printer.|
|dpis|Int32 collection|The list of print resolutions in DPI that are supported by the printer.|
|duplexModes|printDuplexMode collection|The list of duplex modes that are supported by the printer. Valid values are described in the following table.|
|feedOrientations|printerFeedOrientation collection|The list of feed orientations that are supported by the printer.|
|finishings|printFinishing collection|Finishing processes the printer supports for a printed document.|
|inputBins|String collection|Supported input bins for the printer.|
|isColorPrintingSupported|Boolean|True if color printing is supported by the printer; false otherwise. Read-only.|
|isPageRangeSupported|Boolean|True if the printer supports printing by page ranges; false otherwise.|
|leftMargins|Int32 collection|A list of supported left margins(in microns) for the printer.|
|mediaColors|String collection|The media (i.e., paper) colors supported by the printer.|
|mediaSizes|String collection|The media sizes supported by the printer. Supports standard size names for ISO and ANSI media sizes. Valid values are in the following table.|
|mediaTypes|String collection|The media types supported by the printer.|
|multipageLayouts|printMultipageLayout collection|The presentation directions supported by the printer. Supported values are described in the following table.|
|orientations|printOrientation collection|The print orientations supported by the printer. Valid values are described in the following table.|
|outputBins|String collection|The printer's supported output bins (trays).|
|pagesPerSheet|Int32 collection|Supported number of Input Pages to impose upon a single Impression.|
|qualities|printQuality collection|The print qualities supported by the printer.|
|queueBufferSizeInBytes|Int32|The maximum print job queue size that can be stored by the printer.|
|rightMargins|Int32 collection|A list of supported right margins(in microns) for the printer.|
|scalings|printScaling collection|Supported print scalings.|
|supportsFitPdfToPage|Boolean|True if the printer supports scaling PDF pages to match the print media size; false otherwise.|
|topMargins|Int32 collection|A list of supported top margins(in microns) for the printer.|
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
### [uploadSession ](https://docs.microsoft.com/graph/api/resources/uploadsession?view=graph-rest-1.0&tabs=http)
| Property	     | Type              |Description
|:-------------------|:------------------|:------------------------------------
| expirationDateTime | DateTimeOffset    | The date and time in UTC that the upload session will expire. The complete file must be uploaded before this expiration time is reached.|
| nextExpectedRanges | String collection | A collection of byte ranges that the server is missing for the file. These ranges are zero indexed and of the format "start-end" (for example "0-26" to indicate the first 27 bytes of the file). When uploading files as Outlook attachments, instead of a collection of ranges, this property always indicates a single value "{start}", the location in the file where the next upload should begin.|
| uploadUrl          | String            | The URL endpoint that accepts PUT requests for byte ranges of the file.|
