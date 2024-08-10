# PrintConnector.Read.All

> Allows the application to read print connectors on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /print/connectors](https://docs.microsoft.com/graph/api/print-list-connectors?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/connectors/{id}](https://docs.microsoft.com/graph/api/printconnector-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/connectors/{printConnectorId}](https://docs.microsoft.com/graph/api/printconnector-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/printers/{id}/connectors](https://docs.microsoft.com/graph/api/printer-list-connectors?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/printers/{printerId}/connectors](https://docs.microsoft.com/graph/api/printer-list-connectors?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services](https://docs.microsoft.com/graph/api/print-list-services?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /print/services/{id}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/services/{id}/endpoints/{name}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}](https://docs.microsoft.com/graph/api/printservice-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints](https://docs.microsoft.com/graph/api/printservice-list-endpoints?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /print/services/{printServiceId}/endpoints/{printServiceEndpointId}](https://docs.microsoft.com/graph/api/printserviceendpoint-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|d69c2d6d-4f72-4f99-a6b9-663e32f8cf68|
|**Consent Type**|Admin|
|**Display String**|Read print connectors|
|**Description**|Allows the application to read print connectors on behalf of the signed-in user.|
## Resources
### [printConnector ](https://docs.microsoft.com/graph/api/resources/printconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appVersion|String|The connector's version.|
|displayName|String|The name of the connector.|
|fullyQualifiedDomainName|String|The connector machine's hostname.|
|id|String| Read-only.|
|location|printerLocation|The physical and/or organizational location of the connector.|
|operatingSystem|String|The connector machine's operating system version.|
|registeredBy|userIdentity|The user who registered the connector.|
|registeredDateTime|DateTimeOffset|The DateTimeOffset when the connector was registered.|
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
