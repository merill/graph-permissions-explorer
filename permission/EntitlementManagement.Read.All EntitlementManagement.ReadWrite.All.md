# EntitlementManagement.Read.All EntitlementManagement.ReadWrite.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[POST /identityGovernance/entitlementManagement/catalogs/{catalogId}/customWorkflowExtensions](https://docs.microsoft.com/graph/api/accesspackagecatalog-post-accesspackagecustomworkflowextensions?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [accessPackageAssignmentRequestWorkflowExtension ](https://docs.microsoft.com/graph/api/resources/accesspackageassignmentrequestworkflowextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. For example, using OAuth client credentials flow. Inherited from customCalloutExtension.|
|callbackConfiguration|customExtensionCallbackConfiguration|The callback configuration for a custom extension.|
|clientConfiguration|customExtensionClientConfiguration| HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|createdBy|String|The userPrincipalName of the user or identity of the subject that created this resource. Read-only.|
|createdDateTime|DateTimeOffset|When the object was created.|
|description|String|Description for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension.|
|displayName|String|Display name for the customAccessPackageWorkflowExtension object. Inherited from customCalloutExtension.|
|endpointConfiguration|customExtensionEndpointConfiguration|The type and details for configuring the endpoint to call the logic app's workflow. Inherited from customCalloutExtension.|
|id|String|Read-only.|
|lastModifiedBy|String|The userPrincipalName of the identity that last modified the object. |
|lastModifiedDateTime|DateTimeOffset|When the object was last modified.|
### [accessPackageCatalog ](https://docs.microsoft.com/graph/api/resources/accesspackagecatalog?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|catalogType|accessPackageCatalogType|Whether the catalog is created by a user or entitlement management. The possible values are: `userManaged`, `serviceDefault`, `serviceManaged`, `unknownFutureValue`.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|description|String|The description of the access package catalog.|
|displayName|String|The display name of the access package catalog.|
|id|String|Read-only.|
|isExternallyVisible|Boolean|Whether the access packages in this catalog can be requested by users outside of the tenant.|
|modifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
|state|accessPackageCatalogState|Has the value `published` if the access packages are available for management. The possible values are: `unpublished`, `published`, `unknownFutureValue`.|
### [customExtensionAuthenticationConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionauthenticationconfiguration?view=graph-rest-1.0&tabs=http)

### [customExtensionCallbackConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensioncallbackconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|timeoutDuration|Duration|The maximum duration in ISO 8601 format that Microsoft Entra ID will wait for a resume action for the callout it sent to the logic app. The valid range for custom extensions in lifecycle workflows is five minutes to three hours. The valid range for custom extensions in entitlement management is between 5 minutes and 14 days. For example, `PT3H` refers to three hours, `P3D` refers to three days, `PT10M` refers to ten minutes.|
### [customExtensionEndpointConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionendpointconfiguration?view=graph-rest-1.0&tabs=http)

