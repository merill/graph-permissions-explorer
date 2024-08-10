# DelegatedAdminRelationship.Read.All

> Allows the app to read details of delegated admin relationships with customers like access details (that includes roles) and the duration as well as specific role assignments to security groups on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /tenantRelationships/delegatedAdminCustomers](https://docs.microsoft.com/graph/api/tenantrelationship-list-delegatedadmincustomers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminCustomers/{delegatedAdminCustomerId}](https://docs.microsoft.com/graph/api/delegatedadmincustomer-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminCustomers/{delegatedAdminCustomerId}/serviceManagementDetails](https://docs.microsoft.com/graph/api/delegatedadmincustomer-list-servicemanagementdetails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships](https://docs.microsoft.com/graph/api/tenantrelationship-list-delegatedadminrelationships?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}](https://docs.microsoft.com/graph/api/delegatedadminrelationship-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}/accessAssignments](https://docs.microsoft.com/graph/api/delegatedadminrelationship-list-accessassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}/accessAssignments/{delegatedAdminAccessAssignmentId}](https://docs.microsoft.com/graph/api/delegatedadminaccessassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}/operations](https://docs.microsoft.com/graph/api/delegatedadminrelationship-list-operations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}/operations/{delegatedAdminRelationshipOperationId}](https://docs.microsoft.com/graph/api/delegatedadminrelationshipoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}/requests](https://docs.microsoft.com/graph/api/delegatedadminrelationship-list-requests?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/delegatedAdminRelationships/{delegatedAdminRelationshipId}/requests/{delegatedAdminRelationshipRequestId}](https://docs.microsoft.com/graph/api/delegatedadminrelationshiprequest-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|0c0064ea-477b-4130-82a5-4c2cc4ff68aa|
|**Consent Type**|Admin|
|**Display String**|Read Delegated Admin relationships with customers|
|**Description**|Allows the app to read details of delegated admin relationships with customers like access details (that includes roles) and the duration as well as specific role assignments to security groups on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|f6e9e124-4586-492f-adc0-c6f96e4823fd|
|**Display String**|Read Delegated Admin relationships with customers|
|**Description**|Allows the app to read details of delegated admin relationships with customers like access details (that includes roles) and the duration as well as specific role assignments to security groups without a signed-in user.|
## Resources
### [delegatedAdminAccessAssignment ](https://docs.microsoft.com/graph/api/resources/delegatedadminaccessassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessContainer|delegatedAdminAccessContainer|The access container through which members are assigned access. For example, a security group.|
|accessDetails|delegatedAdminAccessDetails|The access details containing the identifiers of the administrative roles that the partner is assigned in the customer tenant.|
|createdDateTime|DateTimeOffset|The date and time in ISO 8601 format and in UTC time when the access assignment was created. Read-only.|
|id|String|The unique identifier of the access assignment. Read-only. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time in ISO 8601 and in UTC time when this access assignment was last modified. Read-only.|
|status|delegatedAdminAccessAssignmentStatus|The status of the access assignment. Read-only. The possible values are: `pending`, `active`, `deleting`, `deleted`, `error`, `unknownFutureValue`.|
### [delegatedAdminCustomer ](https://docs.microsoft.com/graph/api/resources/delegatedadmincustomer?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The Microsoft Entra ID display name of the customer tenant. Read-only. Supports `$orderby`. |
|id|String|The Microsoft Entra ID-assigned unique identifier of the customer. Read-only. Inherited from entity.|
|tenantId|String|The Microsoft Entra ID-assigned tenant ID of the customer. Read-only.|
### [delegatedAdminRelationship ](https://docs.microsoft.com/graph/api/resources/delegatedadminrelationship?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessDetails|delegatedAdminAccessDetails|The access details that contain the identifiers of the administrative roles that the partner admin is requesting in the customer tenant.|
|activatedDateTime|DateTimeOffset|The date and time in ISO 8601 format and in UTC time when the relationship became active. Read-only.|
|autoExtendDuration|Duration| The duration by which the validity of the relationship is automatically extended, denoted in ISO 8601 format. Supported values are: `P0D`, `PT0S`, `P180D`. The default value is `PT0S`. `PT0S` indicates that the relationship expires when the **endDateTime** is reached and it isn't automatically extended.|
|createdDateTime|DateTimeOffset|The date and time in ISO 8601 format and in UTC time when the relationship was created. Read-only.|
|customer|delegatedAdminRelationshipCustomerParticipant|The display name and unique identifier of the customer of the relationship. This is configured either by the partner at the time the relationship is created or by the system after the customer approves the relationship. Can't be changed by the customer.|
|displayName|String|The display name of the relationship used for ease of identification. Must be unique across *all* delegated admin relationships of the partner and is set by the partner only when the relationship is in the `created` status and can't be changed by the customer. Maximum length is 50 characters.|
|duration|Duration|The duration of the relationship in ISO 8601 format. Must be a value between `P1D` and `P2Y` inclusive. This is set by the partner only when the relationship is in the `created` status and can't be changed by the customer.|
|endDateTime|DateTimeOffset|The date and time in ISO 8601 format and in UTC time when the **status** of relationship changes to either `terminated` or `expired`. Calculated as `endDateTime = activatedDateTime + duration`. Read-only.|
|id|String|The unique identifier of the relationship. Read-only. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time in ISO 8601 format and in UTC time when the relationship was last modified. Read-only.|
|status|delegatedAdminRelationshipStatus|The status of the relationship. Read Only. The possible values are: `activating`, `active`, `approvalPending`, `approved`, `created`, `expired`, `expiring`, `terminated`, `terminating`, `terminationRequested`, `unknownFutureValue`. Supports `$orderby`.|
### [delegatedAdminRelationshipOperation ](https://docs.microsoft.com/graph/api/resources/delegatedadminrelationshipoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The time in ISO 8601 format and in UTC time when the long-running operation was created. Read-only.|
|data|String|The data (payload) for the operation. Read-only.|
|id|String|The unique identifier of the delegated admin long-running operation. Read-only. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The time in ISO 8601 format and in UTC time when the long-running operation was last modified. Read-only.|
|operationType|delegatedAdminRelationshipOperationType|The type of long-running operation. The possible values are: `delegatedAdminAccessAssignmentUpdate`, `unknownFutureValue`,`delegatedAdminRelationshipUpdate`. Read-only. You must use the `Prefer: include-unknown-enum-members` request header to get the following value from this evolvable enum: `delegatedAdminRelationshipUpdate`.|
|status|longRunningOperationStatus|The status of the operation. Read-only. The possible values are: `notStarted`, `running`, `succeeded`, `failed`, `unknownFutureValue`. Read-only. Supports `$orderby`.|
### [delegatedAdminRelationshipRequest ](https://docs.microsoft.com/graph/api/resources/delegatedadminrelationshiprequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|delegatedAdminRelationshipRequestAction|The action to be performed on the delegated admin relationship. The possible values are: `lockForApproval`, `approve`, `terminate`, `unknownFutureValue`, `reject`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `reject`. For a partner to finalize a relationship in the `created` **status**, set the **action** to `lockForApproval`. For a partner to terminate a relationship in the `active` **status**, set the **action** to `terminate`. For an indirect reseller to approve a relationship created by an indirect provider in the `approvalPending` **status**, set the **action** to `approve`. For an indirect reseller to reject a relationship created by an indirect provider in the `approvalPending` **status**, set the **action** to `reject`.|
|createdDateTime|DateTimeOffset|The date and time in ISO 8601 format and in UTC time when the relationship request was created. Read-only. |
|id|String|The unique identifier of the relationship request. Read-only. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time in ISO 8601 format and UTC time when this relationship request was last modified. Read-only.|
|status|delegatedAdminRelationshipRequestStatus|The status of the request. Read-only. The possible values are: `created`, `pending`, `succeeded`, `failed`, `unknownFutureValue`.|
### [delegatedAdminServiceManagementDetail ](https://docs.microsoft.com/graph/api/resources/delegatedadminservicemanagementdetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of a managed service. Read-only.|
|serviceManagementUrl|String|The URL of the management portal for the managed service. Read-only.|
|serviceName|String|The name of a managed service. Read-only.|
### [resellerDelegatedAdminRelationship ](https://docs.microsoft.com/graph/api/resources/resellerdelegatedadminrelationship?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accessDetails|delegatedAdminAccessDetails|The access details that contain the identifiers of the administrative roles that the partner administrator requests in the customer tenant. Inherited from delegatedAdminRelationship.|
|activatedDateTime|DateTimeOffset|The date and time when the relationship was activated. Read-only. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from delegatedAdminRelationship.|
|autoExtendDuration|Duration| The duration by which the validity of the relationship is automatically extended, denoted in ISO 8601 format. Supported values are: `P0D`, `PT0S`, `P180D`. The default value is `PT0S`. `PT0S` indicates that the relationship expires when the **endDateTime** is reached and it isn't automatically extended. Inherited from delegatedAdminRelationship.|
|createdDateTime|DateTimeOffset|The date and time when the relationship was created. Read-only. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from delegatedAdminRelationship.|
|customer|delegatedAdminRelationshipCustomerParticipant|The display name and unique identifier of the customer of the relationship. This is configured either by the partner at the time the relationship is created or by the system after the customer approves the relationship. Cannot be changed by the customer. Inherited from delegatedAdminRelationship.|
|displayName|String|The display name of the relationship used for ease of identification. Must be unique across *all* delegated admin relationships of the partner. This is set by the partner only when the relationship is in the `created` **status** and cannot be changed by the customer. Inherited from delegatedAdminRelationship.|
|duration|Duration|The duration of the relationship in ISO 8601 format. Must be a value between `P1D` and `P2Y` inclusive. This is set by the partner only when the relationship is in the `created` **status** and cannot be changed by the customer. Inherited from delegatedAdminRelationship.|
|endDateTime|DateTimeOffset|The date and time when the **status** of the relationship changes to either `terminated` or `expired`. Calculated as `endDateTime = activatedDateTime + duration`. Read-only. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from delegatedAdminRelationship.|
|id|String|The unique identifier of the relationship. Read-only. Inherited from delegatedAdminRelationship.|
|indirectProviderTenantId|String|The tenant ID of the indirect provider partner who created the relationship for the indirect reseller partner.|
|isPartnerConsentPending|Boolean|Indicates the indirect reseller partner consent status. `true` indicates that the partner has yet to review the relationship; `false` indicates that the partner has already provided consent by approving or rejecting the relationship.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the relationship was last modified. Read-only. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from delegatedAdminRelationship.|
|status|delegatedAdminRelationshipStatus|The status of the relationship. Read-only. The possible values are: `activating`, `active`, `approvalPending`, `approved`, `created`, `expired`, `expiring`, `terminated`, `terminating`, `terminationRequested`, `unknownFutureValue`. Supports `$orderBy`. Inherited from delegatedAdminRelationship.|
