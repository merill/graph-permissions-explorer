# WorkforceIntegration.ReadWrite.All

> Allows the app to manage workforce integrations, to synchronize data from Microsoft Teams Shifts, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /teamwork/workforceIntegrations/{workforceIntegrationId}](https://docs.microsoft.com/graph/api/workforceintegration-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teamwork/workforceIntegrations](https://docs.microsoft.com/graph/api/workforceintegration-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teamwork/workforceIntegrations/{workforceIntegrationId}](https://docs.microsoft.com/graph/api/workforceintegration-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /teamwork/workforceIntegrations/{workforceIntegrationId}](https://docs.microsoft.com/graph/api/workforceintegration-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teamwork/workforceIntegrations](https://docs.microsoft.com/graph/api/workforceintegration-post?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|08c4b377-0d23-4a8b-be2a-23c1c1d88545|
|**Consent Type**|Admin|
|**Display String**|Read and write workforce integrations|
|**Description**|Allows the app to manage workforce integrations, to synchronize data from Microsoft Teams Shifts, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|202bf709-e8e6-478e-bcfd-5d63c50b68e3|
|**Display String**|Read and write workforce integrations|
|**Description**|Allows the app to manage workforce integrations to synchronize data from Microsoft Teams Shifts, without a signed-in user.|
## Resources
### [workforceIntegration ](https://docs.microsoft.com/graph/api/resources/workforceintegration?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|apiVersion|Int32|API version for the call back URL. Start with 1.|
|displayName|String|Name of the workforce integration.|
|encryption|workforceIntegrationEncryption|The workforce integration encryption resource.|
|isActive|Boolean|Indicates whether this workforce integration is currently active and available.|
|supportedEntities|workforceIntegrationSupportedEntities | The Shifts entities supported for synchronous change notifications. Shifts will make a call back to the url provided on client changes on those entities added here. By default, no entities are supported for change notifications. Possible values are: `none`, `shift`, `swapRequest`, `userShiftPreferences`, `openshift`, `openShiftRequest`, `offerShiftRequest`, `unknownFutureValue`.|
|url|String| Workforce Integration URL for callbacks from the Shifts service.|
