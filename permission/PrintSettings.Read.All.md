# PrintSettings.Read.All

> Allows the application to read tenant-wide print settings on behalf of the signed-in user.
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
|V1|D|[GET /print/settings](https://docs.microsoft.com/graph/api/print-get-settings?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|490f32fd-d90f-4dd7-a601-ff6cdc1a3f6c|
|**Consent Type**|Admin|
|**Display String**|Read tenant-wide print settings|
|**Description**|Allows the application to read tenant-wide print settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|b5991872-94cf-4652-9765-29535087c6d8|
|**Display String**|Read tenant-wide print settings|
|**Description**|Allows the application to read tenant-wide print settings without a signed-in user.|
## Resources
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
### [printSettings ](https://docs.microsoft.com/graph/api/resources/printsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|documentConversionEnabled|Boolean|Specifies whether document conversion is enabled for the tenant. If document conversion is enabled, Universal Print service will automatically convert documents into a format compatible with the printer (xps to pdf) when needed.|
