# Printer.Read.All

> Allows the application to read printers on behalf of the signed-in user. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /print/printers](https://docs.microsoft.com/graph/api/print-list-printers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /print/printers/{id}](https://docs.microsoft.com/graph/api/printer-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/printers/{id}/getCapabilities](https://docs.microsoft.com/graph/api/printer-getcapabilities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/printers/{id}/taskTriggers](https://docs.microsoft.com/graph/api/printer-list-tasktriggers?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/printers/{id}/taskTriggers/{id}](https://docs.microsoft.com/graph/api/printtasktrigger-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/printers/{printerId}/taskTriggers](https://docs.microsoft.com/graph/api/printer-list-tasktriggers?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/printers/{printerId}/taskTriggers/{printTaskTriggerId}](https://docs.microsoft.com/graph/api/printtasktrigger-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services](https://docs.microsoft.com/graph/api/print-list-services?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/services/{id}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints/{name}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints/{printServiceEndpointId}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /print/shares/{id}/printer](https://docs.microsoft.com/graph/api/printer-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|3a736c8a-018e-460a-b60c-863b2683e8bf|
|**Consent Type**|Admin|
|**Display String**|Read printers|
|**Description**|Allows the application to read printers on behalf of the signed-in user. |
## Application Permission
|||
|-|-|
|**Id**|9709bb33-4549-49d4-8ed9-a8f65e45bb0f|
|**Display String**|Read printers|
|**Description**|Allows the application to read printers without a signed-in user. |
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
### [printTaskTrigger ](https://docs.microsoft.com/graph/api/resources/printtasktrigger?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|event|printEvent|The Universal Print event that causes a new printTask to be triggered. Valid values are described in the following table.|
|id|String|The printTaskTrigger's identifier. Read-only.|
