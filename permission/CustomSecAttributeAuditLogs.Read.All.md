# CustomSecAttributeAuditLogs.Read.All

> Allows the app to read audit logs for events that contain information about custom security attributes, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /auditLogs/customSecurityAttributeAudits](https://docs.microsoft.com/graph/api/auditlogroot-list-customsecurityattributeaudits?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /auditLogs/customSecurityAttributeAudits/{customSecurityAttributeAuditId}](https://docs.microsoft.com/graph/api/customsecurityattributeaudit-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1fcdeaab-b519-44dd-bffc-ed1fd15a24e0|
|**Consent Type**|Admin|
|**Display String**|Read custom security attribute audit logs|
|**Description**|Allows the app to read audit logs for events that contain information about custom security attributes, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|2a4f026d-e829-4e84-bdbf-d981a2703059|
|**Display String**|Read all custom security attribute audit logs|
|**Description**|Allows the app to read all audit logs for events that contain information about custom security attributes, without a signed-in user.|
## Resources
### [customSecurityAttributeAudit ](https://docs.microsoft.com/graph/api/resources/customsecurityattributeaudit?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activityDateTime|DateTimeOffset| Indicates the date and time the activity was performed. The Timestamp type is always in UTC time. For example, midnight UTC on Jan 1, 2024 is `2024-01-01T00:00:00Z`. Supports `$filter` (`eq`, `ge`, `le`).|
|activityDisplayName|String|Indicates the activity name or the operation name. For example: "Add custom security attribute definition in an attribute set" or "Update attribute values assigned to a user." For a list of activities logged, refer to Microsoft Entra audit log categories and activities. Supports `$filter` (`eq`, `startswith`).|
|additionalDetails|keyValue collection|Indicates additional details on the activity.|
|category|String|Indicates the resource category that's targeted by the activity. Custom security attribute activities are logged in a single category: `AttributeManagement`. |
|correlationId|String|Indicates a unique ID that helps correlate activities that span across various services. Can be used to trace logs across services.|
|id|String|Indicates the unique ID for the activity. Inherited from entity.|
|initiatedBy|auditActivityInitiator|Indicates information about the user or app initiated the activity. Supports `$filter` (`eq`) for **user/id**, **user/displayName**, **user/userPrincipalName**, **app/appId**, **app/displayName**; and `$filter` (`startswith`) for **user/userPrincipalName**.|
|loggedByService|String|Indicates information on which service initiated the activity. For example: `Core Directory`. Supports `$filter` (`eq`).|
|operationType|String|Indicates the type of operation that was performed. The possible values include but aren't limited to the following: `Add`, `Assign`, `Update`, `Unassign`, and `Delete`.|
|result|operationResult|Indicates the result of the activity. The possible values are: `success`, `failure`, `timeout`, `unknownFutureValue`.|
|resultReason|String|Indicates the reason for failure if the **result** is `failure` or `timeout`.|
|targetResources|targetResource collection|Indicates information on which resource was changed due to the activity. The target resource type can be `User`, `App`, or `Other`. Supports `$filter` (`eq`) for **id** and **displayName**; and `$filter` (`startswith`) for **displayName**. |
|userAgent|String|Type of user agent used by a user in the activity.|
