# WorkforceIntegration.Read.All

> Allows the app to read workforce integrations, to synchronize data from Microsoft Teams Shifts, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /teamwork/workforceIntegrations](https://docs.microsoft.com/graph/api/workforceintegration-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teamwork/workforceIntegrations/{workforceIntegrationId}](https://docs.microsoft.com/graph/api/workforceintegration-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f1ccd5a7-6383-466a-8db8-1a656f7d06fa|
|**Consent Type**|Admin|
|**Display String**|Read workforce integrations|
|**Description**|Allows the app to read workforce integrations, to synchronize data from Microsoft Teams Shifts, on behalf of the signed-in user.|
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
