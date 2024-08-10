# SecurityActions.Read.All

> Allows the app to read security actions, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[GET /security/securityActions](https://docs.microsoft.com/graph/api/securityactions-list?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /security/securityActions/{id}](https://docs.microsoft.com/graph/api/securityaction-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1638cddf-07a4-4de2-8645-69c96cacad73|
|**Consent Type**|Admin|
|**Display String**|Read your organization's security actions|
|**Description**|Allows the app to read security actions, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|5e0edab9-c148-49d0-b423-ac253e121825|
|**Display String**|Read your organization's security actions|
|**Description**|Allows the app to read security actions, without a signed-in user.|
## Resources
### [securityAction ](https://docs.microsoft.com/graph/api/resources/securityaction?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|actionReason|String|Reason for invoking this action.|
|appId|String|The Application ID of the calling application that submitted (POST) the action. The appId should be extracted from the auth token and not entered manually by the calling application.|
|azureTenantId|String|Azure tenant ID of the entity to determine which tenant the entity belongs to (multi-tenancy support). The azureTenantId should be extracted from the auth token and not entered manually by the calling application.|
|clientContext|String|Unique client context string. Can have a maximum of 256 characters.|
|completedDateTime|DateTimeOffset|Timestamp when the action was completed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|createdDateTime|DateTimeOffset|Timestamp when the action is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|errorInfo|resultInfo| Error info when the action fails.|
|id|String| Created by the system when the action is ingested. Generated GUID/unique identifier. Read-only.|
|lastActionDateTime|DateTimeOffset| Timestamp when this action was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|name|String| Action name.|
|parameters|keyValuePair collection| Collection of parameters (key-value pairs) necessary to invoke the action, for example, URL or fileHash to block.). **Required**.|
|states|securityActionState collection|Collection of securityActionState to keep the history of an action.|
|status|string| Status of the action. Possible values are: `NotStarted`, `Running`, `Completed`, `Failed`.|
|user|String| The user principal name of the signed-in user that submitted  (POST) the action. The user should be extracted from the auth token and not entered manually by the calling application.|
|vendorInformation|securityVendorInformation|Complex Type containing details about the Security product/service vendor, provider, and sub-provider (for example, vendor=Microsoft; provider=Windows Defender ATP; sub-provider=AppLocker).|
