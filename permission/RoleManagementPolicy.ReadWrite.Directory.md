# RoleManagementPolicy.ReadWrite.Directory

> Allows the app to read, update, and delete policies for privileged role-based access control (RBAC) assignments of your company's directory, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /policies/roleManagementPolicies?$filter=scopeId eq '/' and scopeType eq 'DirectoryRole'](https://docs.microsoft.com/graph/api/policyroot-list-rolemanagementpolicies?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/effectiveRules](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-list-effectiverules?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/rules](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-list-rules?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/rules/{unifiedRoleManagementPolicyRuleId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicyrule-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /policies/roleManagementPolicyAssignments?$filter=scopeId eq '/' and scopeType eq 'DirectoryRole'](https://docs.microsoft.com/graph/api/policyroot-list-rolemanagementpolicyassignments?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /policies/roleManagementPolicyAssignments/{unifiedRoleManagementPolicyAssignmentId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /policies/roleManagementPolicies/{unifiedRoleManagementPolicyId}/rules/{unifiedRoleManagementPolicyRuleId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementpolicyrule-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1ff1be21-34eb-448c-9ac9-ce1f506b2a68|
|**Consent Type**|Admin|
|**Display String**|Read, update, and delete all policies for privileged role assignments of your company's directory|
|**Description**|Allows the app to read, update, and delete policies for privileged role-based access control (RBAC) assignments of your company's directory, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|31e08e0a-d3f7-4ca2-ac39-7343fb83e8ad|
|**Display String**|Read, update, and delete all policies for privileged role assignments of your company's directory|
|**Description**|Allows the app to read, update, and delete policies for privileged role-based access control (RBAC) assignments of your company's directory, without a signed-in user.|
## Resources
### [approvalSettings ](https://docs.microsoft.com/graph/api/resources/approvalsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|approvalMode|String|One of `SingleStage`, `Serial`, `Parallel`, `NoApproval` (default). `NoApproval` is used when `isApprovalRequired` is `false`.|
|approvalStages|unifiedApprovalStage collection|If approval is required, the one or two elements of this collection define each of the stages of approval. An empty array if no approval is required.|
|isApprovalRequired|Boolean|Indicates whether approval is required for requests in this policy.|
|isApprovalRequiredForExtension|Boolean|Indicates whether approval is required for a user to extend their assignment.|
|isRequestorJustificationRequired|Boolean|Indicates whether the requestor is required to supply a justification in their request.|
### [unifiedRoleManagementPolicy ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Description for the policy.|
|displayName|String|Display name for the policy.|
|id|String|Unique identifier for the policy.|
|isOrganizationDefault|Boolean|This can only be set to `true` for a single tenant-wide policy which will apply to all scopes and roles. Set the scopeId to `/` and scopeType to `Directory`. Supports `$filter` (`eq`, `ne`).|
|lastModifiedBy|identity|The identity who last modified the role setting.|
|lastModifiedDateTime|DateTimeOffset|The time when the role setting was last modified.|
|scopeId|String|The identifier of the scope where the policy is created. Can be `/` for the tenant or a group ID. Required.|
|scopeType|String|The type of the scope where the policy is created. One of `Directory`, `DirectoryRole`, `Group`. Required.|
### [unifiedRoleManagementPolicyApprovalRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyapprovalrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity.|
|setting|approvalSettings|The settings for approval of the role assignment.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the approval rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the policy assignment. The ID is typically a concatenation of the **unifiedRoleManagementPolicy** ID and the **roleDefinitionId** separated by an underscore.|
|policyId|String|The id of the policy. Inherited from entity.|
|roleDefinitionId|String|For Microsoft Entra roles policy, it's the identifier of the role definition object where the policy applies. For PIM for groups membership and ownership, it's either `member` or `owner`. Supports $filter (`eq`).|
|scopeId|String|The identifier of the scope where the policy is assigned.  Can be `/` for the tenant or a group ID. Required.|
|scopeType|String|The type of the scope where the policy is assigned. One of `Directory`, `DirectoryRole`, `Group`. Required.|
### [unifiedRoleManagementPolicyAuthenticationContextRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyauthenticationcontextrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|claimValue|String|The value of the authentication context claim.|
|id|String|Identifier for the rule. Inherited from entity.|
|isEnabled|Boolean| Determines whether this rule is enabled.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that the enablement rule targets. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyEnablementRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyenablementrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|enabledRules|String collection|The collection of rules that are enabled for this policy rule. For example, `MultiFactorAuthentication`, `Ticketing`, and `Justification`.|
|id|String|Identifier for the rule. Inherited from entity.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the enablement rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyExpirationRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyexpirationrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity.|
|isExpirationRequired|Boolean|Indicates whether expiration is required or if it's a permanently active assignment or eligibility. |
|maximumDuration|Duration| The maximum duration allowed for eligibility or assignment that isn't permanent. Required when **isExpirationRequired** is `true`. |
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the expiration rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyNotificationRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicynotificationrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity.|
|isDefaultRecipientsEnabled|Boolean|Indicates whether a default recipient will receive the notification email.|
|notificationLevel|String|The level of notification. The possible values are `None`, `Critical`, `All`.|
|notificationRecipients|String collection|The list of recipients of the email notifications.|
|notificationType|String|The type of notification. Only `Email` is supported.|
|recipientType|String|The type of recipient of the notification. The possible values are `Requestor`, `Approver`, `Admin`.|
|target|unifiedRoleManagementPolicyRuleTarget|Defines details of the scope that's targeted by the notification rule. The details can include the principal type, the role assignment type, and actions affecting a role. Inherited from unifiedRoleManagementPolicyRule. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyRule ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the rule. Inherited from entity. Read-only.|
|target|unifiedRoleManagementPolicyRuleTarget| Defines details of scope that's targeted by role management policy rule. The details can include the principal type, the role assignment type, and actions affecting a role. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementPolicyRuleTarget ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementpolicyruletarget?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|caller|String|The type of caller that's the target of the policy rule. Allowed values are: `None`, `Admin`, `EndUser`.|
|enforcedSettings|String collection|The list of role settings that are enforced and cannot be overridden by child scopes. Use `All` for all settings.|
|inheritableSettings|String collection|The list of role settings that can be inherited by child scopes. Use `All` for all settings.|
|level|String|The role assignment type that's the target of policy rule. Allowed values are: `Eligibility`, `Assignment`.	|
|operations|String collection|The role management operations that are the target of the policy rule. Allowed values are: `All`, `Activate`, `Deactivate`, `Assign`, `Update`, `Remove`, `Extend`, `Renew`.|
