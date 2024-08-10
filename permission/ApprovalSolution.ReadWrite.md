# ApprovalSolution.ReadWrite

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /solutions/approval](https://docs.microsoft.com/graph/api/approvalsolution-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/approvalItems](https://docs.microsoft.com/graph/api/approvalsolution-list-approvalitems?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/approvalItems/{approvalItemId}](https://docs.microsoft.com/graph/api/approvalitem-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/approvalItems/{approvalItemId}/requests](https://docs.microsoft.com/graph/api/approvalitem-list-requests?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/approvalItems/{approvalItemId}/requests/{approvalItemRequestId}](https://docs.microsoft.com/graph/api/approvalitemrequest-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/approvalItems/{approvalItemId}/responses](https://docs.microsoft.com/graph/api/approvalitem-list-responses?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/approvalItems/{approvalItemId}/responses/{approvalItemResponseId}](https://docs.microsoft.com/graph/api/approvalitemresponse-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/approval/operations/{approvalOperationId}](https://docs.microsoft.com/graph/api/approvaloperation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /solutions/approval/approvalItems](https://docs.microsoft.com/graph/api/approvalsolution-post-approvalitems?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /solutions/approval/approvalItems/{approvalItemId}/cancel](https://docs.microsoft.com/graph/api/approvalitem-cancel?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /solutions/approval/approvalItems/{approvalItemId}/responses](https://docs.microsoft.com/graph/api/approvalitem-post-responses?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /solutions/approval/provision](https://docs.microsoft.com/graph/api/approvalsolution-provision?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
### [approvalIdentitySet ](https://docs.microsoft.com/graph/api/resources/approvalidentityset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|group|identity|The Microsoft Entra group associated with the approval item.|
|user|identity|The user associated with the approval item. Inherited from identitySet.|
### [approvalItem ](https://docs.microsoft.com/graph/api/resources/approvalitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowCancel|Boolean|Indicates whether the approval item can be canceled.|
|allowEmailNotification|Boolean|Indicates whether email notification is enabled.|
|approvalType|approvalItemType|The workflow type of the approval item. The possible values are: `basic`, `basicAwaitAll`, `custom`, `customAwaitAll`. Required.|
|approvers|approvalIdentitySet collection|The identity of the principals to whom the approval item was initially assigned. Required.|
|completedDateTime|DateTimeOffset|Approval request completion date and time. Read-only.|
|createdDateTime|DateTimeOffset|Creation date and time of the approval request. Read-only.|
|description|String|The description of the approval request.|
|displayName|String|The displayName of the approval request. Required.|
|id|String|The unique id for the approval item. Read-only.|
|owner|approvalIdentitySet|The identity set of the principal who owns the approval item. Only provide a value for this property when creating an approval item on behalf of the principal. If the owner field isn't provided, the user information from the user context is used.|
|responsePrompts|String collection|Approval response prompts. Only provide a value for this property when creating a custom approval item. For custom approval items, supply two response prompt strings. The default response prompts are "Approve" and "Reject".|
|result|String|The result field is only populated once the approval item is in its final state. The result of the approval item is based on the approvalType. For basic approval items, the result is either "Approved" or "Rejected". For custom approval items, the result could either be a single response or multiple responses separated by a semi-colon. Read-only.|
|state|approvalItemState|The approval item state. The possible values are: `canceled`, `created`, `pending`, `completed`. Read-only.|
|viewPoint|approvalItemViewPoint|Represents user viewpoints data on the ApprovalItem. The data includes the users roles regarding the approval item. Read-only.|
### [approvalItemRequest ](https://docs.microsoft.com/graph/api/resources/approvalitemrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|approver|approvalIdentitySet|The identity set of the principal assigned to this request.|
|createdDateTime|DateTimeOffset|Creation date and time for the request.|
|isReassigned|Boolean|Indicates whether a request was reassigned.|
|reassignedFrom|approvalIdentitySet|The identity set of the principal who reassigned the request.|
### [approvalItemResponse ](https://docs.microsoft.com/graph/api/resources/approvalitemresponse?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|comments|String|The comment made by the approver.|
|createdBy|approvalIdentitySet|The identity set of the approver.|
|createdDateTime|DateTimeOffset|Creation date and time of the response.|
|owners|approvalIdentitySet collection|The identity set of the principal who owns the approval item.|
|response|String|Approver response based on the response options. The default response options are "Approved" and "Rejected". The approval item creator can also define custom response options during approval item creation.|
### [approvalOperation ](https://docs.microsoft.com/graph/api/resources/approvaloperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when the operation was created.|
|error|publicError|The error if the operation failed.|
|lastActionDateTime|DateTimeOffset|The date and time when this operation was most recently updated.|
|resourceLocation|String|The URL for the resource that was newly created or acted upon.|
|status|approvalOperationStatus|The status of the operation. The possible values are: `scheduled`, `inProgress`, `succeeded`, `failed`, `timeout`, `unknownFutureValue`.|
### [approvalSolution ](https://docs.microsoft.com/graph/api/resources/approvalsolution?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|provisioningStatus|provisionState|The approval provisioning status for a tenant on an environment. The possible values are: `notProvisioned`, `provisioningInProgress`, `provisioningFailed`, `provisioningCompleted`, `unknownFutureValue`.|
