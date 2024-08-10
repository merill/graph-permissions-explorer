# PrintJob.Manage.All

> Allows the application to perform advanced operations like redirecting a print job to another printer without a signed-in user. Also allows the application to read and update the metadata of print jobs.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[PATCH /print/printers/{id}/jobs/{id}](https://docs.microsoft.com/graph/api/printjob-update?view=graph-rest-beta&tabs=http)|
|V1|A|[PATCH /print/printers/{printerId}/jobs/{printJobId}](https://docs.microsoft.com/graph/api/printjob-update?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /print/printers/{id}/jobs/{id}/abort](https://docs.microsoft.com/graph/api/printjob-abort?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /print/printers/{id}/jobs/{id}/redirect](https://docs.microsoft.com/graph/api/printjob-redirect?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /print/printers/{printerId}/jobs/{printJobId}/abort](https://docs.microsoft.com/graph/api/printjob-abort?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /print/printers/{printerId}/jobs/{printJobId}/redirect](https://docs.microsoft.com/graph/api/printjob-redirect?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|58a52f47-9e36-4b17-9ebe-ce4ef7f3e6c8|
|**Display String**|Perform advanced operations on print jobs|
|**Description**|Allows the application to perform advanced operations like redirecting a print job to another printer without a signed-in user. Also allows the application to read and update the metadata of print jobs.|
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
