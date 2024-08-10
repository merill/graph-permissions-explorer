# PrinterShare.ReadBasic.All

> Allows the application to read basic information about printer shares on behalf of the signed-in user. Does not allow reading access control information.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/print/recentPrinterShares](https://docs.microsoft.com/graph/api/print-list-recentprintershares?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/printers/{id}](https://docs.microsoft.com/graph/api/printer-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/printers/{printerId}/shares](https://docs.microsoft.com/graph/api/printer-list-shares?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/printers/{printerId}/shares/{printerShareId}](https://docs.microsoft.com/graph/api/printershare-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services](https://docs.microsoft.com/graph/api/print-list-services?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/services/{id}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints/{name}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints/{printServiceEndpointId}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/shares](https://docs.microsoft.com/graph/api/print-list-shares?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/shares/{id}/printer](https://docs.microsoft.com/graph/api/printer-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/shares/{printerShareId}](https://docs.microsoft.com/graph/api/printershare-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5fa075e9-b951-4165-947b-c63396ff0a37|
|**Consent Type**|User|
|**Display String**|Read basic information about printer shares|
|**Description**|Allows the application to read basic information about printer shares on behalf of the signed-in user. Does not allow reading access control information.|
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
