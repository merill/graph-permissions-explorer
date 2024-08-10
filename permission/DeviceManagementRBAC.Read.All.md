# DeviceManagementRBAC.Read.All

> Allows the app to read the properties relating to the Microsoft Intune Role-Based Access Control (RBAC) settings.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /deviceManagement](https://docs.microsoft.com/graph/api/intune-rbac-devicemanagement-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/getAssignedRoleDetails](https://docs.microsoft.com/graph/api/intune-rbac-devicemanagement-getassignedroledetails?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceManagement/getAssignedRoleIdsForLoggedInUser](https://docs.microsoft.com/graph/api/intune-shared-devicemanagement-getassignedroleidsforloggedinuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/getEffectivePermissions](https://docs.microsoft.com/graph/api/intune-rbac-devicemanagement-geteffectivepermissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/getRoleScopeTagsByIds](https://docs.microsoft.com/graph/api/intune-rbac-devicemanagement-getrolescopetagsbyids?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/getRoleScopeTagsByResource](https://docs.microsoft.com/graph/api/intune-rbac-devicemanagement-getrolescopetagsbyresource?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalPolicies](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalpolicy-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalPolicies/{operationApprovalPolicyId}](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalPolicies/getApprovableOperations](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalpolicy-getapprovableoperations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalPolicies/getOperationsRequiringApproval](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalpolicy-getoperationsrequiringapproval?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalPolicies/retrieveApprovableOperations](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalpolicy-retrieveapprovableoperations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalPolicies/retrieveOperationsRequiringApproval](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalpolicy-retrieveoperationsrequiringapproval?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalRequests](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalRequests/{operationApprovalRequestId}](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalRequests/retrieveMyRequestById](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-retrievemyrequestbyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/operationApprovalRequests/retrieveMyRequests](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-retrievemyrequests?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/resourceOperations](https://docs.microsoft.com/graph/api/intune-rbac-resourceoperation-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/resourceOperations/{resourceOperationId}](https://docs.microsoft.com/graph/api/intune-rbac-resourceoperation-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/resourceOperations/{resourceOperationId}/getScopesForUser](https://docs.microsoft.com/graph/api/intune-rbac-resourceoperation-getscopesforuser?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleAssignments](https://docs.microsoft.com/graph/api/intune-rbac-deviceandappmanagementroleassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleAssignments/{deviceAndAppManagementRoleAssignmentId}](https://docs.microsoft.com/graph/api/intune-rbac-deviceandappmanagementroleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleDefinitions](https://docs.microsoft.com/graph/api/intune-rbac-roledefinition-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}](https://docs.microsoft.com/graph/api/intune-rbac-roledefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments](https://docs.microsoft.com/graph/api/intune-rbac-roleassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}](https://docs.microsoft.com/graph/api/intune-rbac-roleassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/microsoft.graph.deviceAndAppManagementRoleAssignment/roleScopeTags](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/microsoft.graph.deviceAndAppManagementRoleAssignment/roleScopeTags/{roleScopeTagId}](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/microsoft.graph.deviceAndAppManagementRoleAssignment/roleScopeTags/{roleScopeTagId}/assignments](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetagautoassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/microsoft.graph.deviceAndAppManagementRoleAssignment/roleScopeTags/{roleScopeTagId}/assignments/{roleScopeTagAutoAssignmentId}](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetagautoassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/microsoft.graph.deviceAndAppManagementRoleAssignment/roleScopeTags/hasCustomRoleScopeTag](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-hascustomrolescopetag?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/roleDefinition](https://docs.microsoft.com/graph/api/intune-rbac-roledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleScopeTags](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleScopeTags/{roleScopeTagId}](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/roleScopeTags/hasCustomRoleScopeTag](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-hascustomrolescopetag?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/scopedForResource](https://docs.microsoft.com/graph/api/intune-rbac-devicemanagement-scopedforresource?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement](https://docs.microsoft.com/graph/api/intune-rbac-rolemanagement-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPc/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplicationmultiple-list-roleassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignmentmultiple-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/deviceManagement](https://docs.microsoft.com/graph/api/intune-rbac-rbacapplicationmultiple-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/operationApprovalRequests/{operationApprovalRequestId}/approve](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-approve?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/operationApprovalRequests/{operationApprovalRequestId}/cancelApproval](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-cancelapproval?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/operationApprovalRequests/{operationApprovalRequestId}/reject](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-reject?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/operationApprovalRequests/cancelMyRequest](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-cancelmyrequest?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/operationApprovalRequests/retrieveRequestStatus](https://docs.microsoft.com/graph/api/intune-rbac-operationapprovalrequest-retrieverequeststatus?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/roleDefinitions/{roleDefinitionId}/roleAssignments/{roleAssignmentId}/microsoft.graph.deviceAndAppManagementRoleAssignment/roleScopeTags/getRoleScopeTagsById](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-getrolescopetagsbyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/roleScopeTags/getRoleScopeTagsById](https://docs.microsoft.com/graph/api/intune-rbac-rolescopetag-getrolescopetagsbyid?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|49f0cc30-024c-4dfd-ab3e-82e137ee5431|
|**Consent Type**|Admin|
|**Display String**|Read Microsoft Intune RBAC settings|
|**Description**|Allows the app to read the properties relating to the Microsoft Intune Role-Based Access Control (RBAC) settings.|
## Application Permission
|||
|-|-|
|**Id**|58ca0d9a-1575-47e1-a3cb-007ef2e4583b|
|**Display String**|Read Microsoft Intune RBAC settings|
|**Description**|Allows the app to read the properties relating to the Microsoft Intune Role-Based Access Control (RBAC) settings, without a signed-in user.|
## Resources
### [deviceAndAppManagementAssignedRoleDetails ](https://docs.microsoft.com/graph/api/resources/intune-rbac-deviceandappmanagementassignedroledetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|roleDefinitionIds|String collection|Role Definition IDs for the specifc Role Definitions assigned to a user. This property is read-only.|
|roleAssignmentIds|String collection|Role Assignment IDs for the specifc Role Assignments assigned to a user. This property is read-only.|
### [deviceAndAppManagementRoleAssignment ](https://docs.microsoft.com/graph/api/resources/intune-rbac-deviceandappmanagementroleassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This is read-only and automatically generated. Inherited from roleAssignment|
|displayName|String|The display or friendly name of the role Assignment. Inherited from roleAssignment|
|description|String|Description of the Role Assignment. Inherited from roleAssignment|
|resourceScopes|String collection|List of ids of role scope member security groups.  These are IDs from Azure Active Directory. Inherited from roleAssignment|
|members|String collection|The list of ids of role member security groups. These are IDs from Azure Active Directory.|
### [deviceAndAppManagementRoleDefinition ](https://docs.microsoft.com/graph/api/resources/intune-rbac-deviceandappmanagementroledefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This is read-only and automatically generated. Inherited from roleDefinition|
|displayName|String|Display Name of the Role definition. Inherited from roleDefinition|
|description|String|Description of the Role definition. Inherited from roleDefinition|
|rolePermissions|rolePermission collection|List of Role Permissions this role is allowed to perform. These must match the actionName that is defined as part of the rolePermission. Inherited from roleDefinition|
|isBuiltIn|Boolean|Type of Role. Set to True if it is built-in, or set to False if it is a custom role definition. Inherited from roleDefinition|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-rbac-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
### [operationApprovalPolicy ](https://docs.microsoft.com/graph/api/resources/intune-rbac-operationapprovalpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the policy. This ID is assigned at when the policy is created. Read-only. This property is read-only.|
|displayName|String|Indicates the display name of the policy. Maximum length of the display name is 128 characters. This property is required when the policy is created, and is defined by the IT Admins to identify the policy.|
|description|String|Indicates the description of the policy. Maximum length of the description is 1024 characters. This property is not required, but can be used by the IT Admin to describe the policy.|
|lastModifiedDateTime|DateTimeOffset|Indicates the last DateTime that the policy was modified. The value cannot be modified and is automatically populated whenever values in the request are updated. For example, when the 'policyType' property changes from `apps` to `scripts`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only. This property is read-only.|
|policyType|operationApprovalPolicyType|The policy type for the OperationApprovalPolicy. Possible values are: `unknown`, `app`, `script`, `operationApprovalPolicy`. Possible values are: `unknown`, `deviceAction`, `deviceWipe`, `deviceRetire`, `deviceRetireNonCompliant`, `deviceDelete`, `deviceLock`, `deviceErase`, `deviceDisableActivationLock`, `windowsEnrollment`, `compliancePolicy`, `configurationPolicy`, `appProtectionPolicy`, `policySet`, `filter`, `endpointSecurityPolicy`, `app`, `script`, `role`, `deviceResetPasscode`, `customOrganizationalMessage`, `unknownFutureValue`, `operationApprovalPolicy`.|
|policyPlatform|operationApprovalPolicyPlatform|Indicates the applicable platform for the policy. Possible values are: `notApplicable`, `androidDeviceAdministrator`, `androidEnterprise`, `iOSiPadOS`, `macOS`, `windows10AndLater`, `windows81AndLater`, `windows10X`. Default value is `notApplicable`. Possible values are: `notApplicable`, `androidDeviceAdministrator`, `androidEnterprise`, `iOSiPadOS`, `macOS`, `windows10AndLater`, `windows81AndLater`, `windows10X`, `unknownFutureValue`.|
|policySet|operationApprovalPolicySet|Indicates areas of the Intune UX that could support MAA UX for the current logged in IT Admin. This property is required, and is defined by the IT Admins in order to correctly show the expected experience.|
|approverGroupIds|String collection|The Microsoft Entra ID (Azure AD) security group IDs for the approvers for the policy. This property is required when the policy is created, and is defined by the IT Admins to define the possible approvers for the policy.|
### [operationApprovalPolicySet ](https://docs.microsoft.com/graph/api/resources/intune-rbac-operationapprovalpolicyset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|policyType|operationApprovalPolicyType|The policy type for the OperationApprovalPolicy. This property is required when the policy set is created, and uniquely identifies areas of the Intune UX that could support MAA when used in conjection with the `policyPlatform` property. Possible values are: `unknown`, `app`, `script`, `operationApprovalPolicy`. Read-only. This property is read-only. Possible values are: `unknown`, `deviceAction`, `deviceWipe`, `deviceRetire`, `deviceRetireNonCompliant`, `deviceDelete`, `deviceLock`, `deviceErase`, `deviceDisableActivationLock`, `windowsEnrollment`, `compliancePolicy`, `configurationPolicy`, `appProtectionPolicy`, `policySet`, `filter`, `endpointSecurityPolicy`, `app`, `script`, `role`, `deviceResetPasscode`, `customOrganizationalMessage`, `unknownFutureValue`, `operationApprovalPolicy`.|
|policyPlatform|operationApprovalPolicyPlatform|The applicable platform(s) for the OperationApprovalPolicy. This property is required when the policy set is created, and uniquely identifies the platform(s) that could support MAA when used in conjection with the `policyType` property. Possible values are: `notApplicable`, `androidDeviceAdministrator`, `androidEnterprise`, `iOSiPadOS`, `macOS`, `windows10AndLater`, `windows81AndLater`, `windows10X`. Read-only. This property is read-only. Possible values are: `notApplicable`, `androidDeviceAdministrator`, `androidEnterprise`, `iOSiPadOS`, `macOS`, `windows10AndLater`, `windows81AndLater`, `windows10X`, `unknownFutureValue`.|
### [operationApprovalRequest ](https://docs.microsoft.com/graph/api/resources/intune-rbac-operationapprovalrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the request. This ID is assigned at when the request is created. Read-only.|
|requestDateTime|DateTimeOffset|Indicates the DateTime that the request was made. The value cannot be modified and is automatically populated when the request is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only. This property is read-only.|
|expirationDateTime|DateTimeOffset|Indicates the DateTime when any action on the approval request is no longer permitted. The value cannot be modified and is automatically populated when the request is created using expiration offset values defined in the service controllers. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only. This property is read-only.|
|lastModifiedDateTime|DateTimeOffset|Indicates the last DateTime that the request was modified. The value cannot be modified and is automatically populated whenever values in the request are updated. For example, when the 'status' property changes from `needsApproval` to `approved`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only. This property is read-only.|
|requestor|identitySet|The identity of the requestor as an Identity Set. Optionally contains the application ID, the device ID and the User ID. See information about this type here: https://learn.microsoft.com/graph/api/resources/identityset?view=graph-rest-1.0. Read-only. This property is read-only.|
|approver|identitySet|The identity of the approver as an Identity Set. Optionally contains the application ID, the device ID and the User ID. See information about this type here: https://learn.microsoft.com/graph/api/resources/identityset?view=graph-rest-1.0. Read-only. This property is read-only.|
|status|operationApprovalRequestStatus|The current approval status of the request. Possible values are: `unknown`, `needsApproval`, `approved`, `rejected`, `cancelled`, `completed`, `expired`. Default value is `unknown`. Read-only. This property is read-only. Possible values are: `unknown`, `needsApproval`, `approved`, `rejected`, `cancelled`, `completed`, `expired`, `unknownFutureValue`.|
|requestJustification|String|Indicates the justification for creating the request. Maximum length of justification is 1024 characters. For example: 'Needed for Feb 2023 application baseline updates.' Read-only. This property is read-only.|
|approvalJustification|String|Indicates the justification for approving or rejecting the request. Maximum length of justification is 1024 characters. For example: 'Approved per Change 23423 - needed for Feb 2023 application baseline updates.' Read-only. This property is read-only.|
|requiredOperationApprovalPolicyTypes|operationApprovalPolicyType collection|Indicates the approval policy types required by the request in order for the request to be approved or rejected. Read-only. This property is read-only.|
### [operationApprovalRequestEntityStatus ](https://docs.microsoft.com/graph/api/resources/intune-rbac-operationapprovalrequestentitystatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|requestId|String|The unique identifier of the OperationApprovalRequest. This property cannot be modified and is required when the entity status is created. Read-only. This property is read-only.|
|requestExpirationDateTime|DateTimeOffset|Indicates the DateTime when any action on the OperationApprovalRequest is no longer permitted. The value cannot be modified and is automatically populated when the request is created using expiration offset values defined in the service controllers. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only. This property is read-only.|
|requestStatus|operationApprovalRequestStatus|The current approval status of the OperationApprovalRequest. Possible values are: `unknown`, `needsApproval`, `approved`, `rejected`, `cancelled`, `completed`, `expired`. Default value is `unknown`. Read-only. This property is read-only. Possible values are: `unknown`, `needsApproval`, `approved`, `rejected`, `cancelled`, `completed`, `expired`, `unknownFutureValue`.|
|entityLocked|Boolean|The status of the Entity connected to the OperationApprovalRequest in regard to changes, whether further requests are allowed or if the Entity is locked. When `true`, a lock is present on the Entity and no approval requests can be currently made for it. When `false`, the Entity is not locked and approval requests are allowed. Default value is `false`. Read-only. This property is read-only.|
### [intune-rbac-operationapprovalsource](https://docs.microsoft.com/graph/api/resources/intune-rbac-operationapprovalsource?view=graph-rest-1.0&tabs=http)

### [rbacApplicationMultiple ](https://docs.microsoft.com/graph/api/resources/intune-rbac-rbacapplicationmultiple?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
### [resourceOperation ](https://docs.microsoft.com/graph/api/resources/intune-rbac-resourceoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the Resource Operation. Read-only, automatically generated.|
|resourceName|String|Name of the Resource this operation is performed on.|
|actionName|String|Type of action this operation is going to perform. The actionName should be concise and limited to as few words as possible.|
|description|String|Description of the resource operation. The description is used in mouse-over text for the operation when shown in the Azure Portal.|
### [roleAssignment ](https://docs.microsoft.com/graph/api/resources/intune-rbac-roleassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This is read-only and automatically generated.|
|displayName|String|The display or friendly name of the role Assignment.|
|description|String|Description of the Role Assignment.|
|resourceScopes|String collection|List of ids of role scope member security groups.  These are IDs from Azure Active Directory.|
### [roleDefinition ](https://docs.microsoft.com/graph/api/resources/intune-rbac-roledefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This is read-only and automatically generated.|
|displayName|String|Display Name of the Role definition.|
|description|String|Description of the Role definition.|
|rolePermissions|rolePermission collection|List of Role Permissions this role is allowed to perform. These must match the actionName that is defined as part of the rolePermission.|
|isBuiltIn|Boolean|Type of Role. Set to True if it is built-in, or set to False if it is a custom role definition.|
### [roleManagement ](https://docs.microsoft.com/graph/api/resources/intune-rbac-rolemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|
### [rolePermission ](https://docs.microsoft.com/graph/api/resources/intune-rbac-rolepermission?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|resourceActions|resourceAction collection|Resource Actions each containing a set of allowed and not allowed permissions.|
### [roleScopeTag ](https://docs.microsoft.com/graph/api/resources/intune-rbac-rolescopetag?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This is read-only and automatically generated. This property is read-only.|
|displayName|String|The display or friendly name of the Role Scope Tag.|
|description|String|Description of the Role Scope Tag.|
|isBuiltIn|Boolean|Description of the Role Scope Tag. This property is read-only.|
### [roleScopeTagAutoAssignment ](https://docs.microsoft.com/graph/api/resources/intune-rbac-rolescopetagautoassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only.|
|target|deviceAndAppManagementAssignmentTarget|The auto-assignment target for the specific Role Scope Tag.|
### [unifiedRoleAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appScopeId|String|Identifier of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by a resource application only. For the entitlement management provider, use this property to specify a catalog. For example, `/AccessPackageCatalog/beedadfe-01d5-4025-910b-84abb9369997`. Supports `$filter` (`eq`, `in`). For example, `/roleManagement/entitlementManagement/roleAssignments?$filter=appScopeId eq '/AccessPackageCatalog/{catalog id}'`.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications, unlike app scopes that are defined and understood by a resource application only. Supports `$filter` (`eq`, `in`).|
|id|String| The unique identifier for the unifiedRoleAssignment. Key, not nullable, Read-only. |
|principalId|String| Identifier of the principal to which the assignment is granted. Supported principals are users, role-assignable groups, and service principals. Supports `$filter` (`eq`, `in`). |
|roleDefinitionId|String| Identifier of the unifiedRoleDefinition the assignment is for. Read-only. Supports `$filter` (`eq`, `in`). |
### [unifiedRoleAssignmentMultiple ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignmentmultiple?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| appScopeIds | String collection | Ids of the app specific scopes when the assignment scopes are app specific. The scopes of an assignment determine the set of resources for which the principal has access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. App scopes are scopes that are defined and understood by this application only. |
| description | String | Description of the role assignment. |
| directoryScopeIds | String collection | Ids of the directory objects that represent the scopes of the assignment. The scopes of an assignment determine the set of resources for which the principals have been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. App scopes are scopes that are defined and understood by this application only. |
| displayName | String | Name of the role assignment. Required. |
| id | String | The unique identifier for the **unifiedRoleAssignmentMultiple** object. Key, not nullable, Read-only. |
| principalIds | String collection | Identifiers of the principals to which the assignment is granted. Supports `$filter` (`any` operator only). |
| roleDefinitionId | String | Identifier of the unifiedRoleDefinition the assignment is for. |
### [unifiedRoleDefinition ](https://docs.microsoft.com/graph/api/resources/unifiedroledefinition?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String| The description for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. |
|displayName|String| The display name for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. Required.  Supports $filter (`eq`, `in`).|
|id|String| The unique identifier for the role definition. Key, not nullable, Read-only. Inherited from entity. Supports $filter (`eq`, `in`). |
|isBuiltIn|Boolean| Flag indicating whether the role definition is part of the default set included in Microsoft Entra or a custom definition. Read-only. Supports $filter (`eq`, `in`). |
|isEnabled|Boolean| Flag indicating whether the role is enabled for assignment. If `false` the role is not available for assignment. Read-only when **isBuiltIn** is true. |
|resourceScopes|String collection| List of the scopes or permissions the role definition applies to. Currently only `/` is supported. Read-only when **isBuiltIn** is true. **DO NOT USE. This will be deprecated soon. Attach scope to role assignment.** | 
|rolePermissions|unifiedRolePermission collection| List of permissions included in the role. Read-only when **isBuiltIn** is `true`. Required. |
|templateId|String| Custom template identifier that can be set when **isBuiltIn** is `false` but is read-only when **isBuiltIn** is `true`. This identifier is typically used if one needs an identifier to be the same across different directories. |
|version|String| Indicates version of the role definition. Read-only when **i
