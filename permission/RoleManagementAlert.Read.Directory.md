# RoleManagementAlert.Read.Directory

> Allows the app to read the role-based access control (RBAC) alerts for your company's directory, on behalf of the signed-in user. This includes reading alert statuses, alert definitions, alert configurations and incidents that lead to an alert.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alertConfigurations?$filter=scopeId eq 'scopeId' and scopeType eq 'scopeType'](https://docs.microsoft.com/graph/api/rolemanagementalert-list-alertconfigurations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alertConfigurations/{unifiedRoleManagementAlertConfigurationId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementalertconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alertDefinitions?$filter=scopeId eq 'scopeId' and scopeType eq 'scopeType'](https://docs.microsoft.com/graph/api/rolemanagementalert-list-alertdefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alertDefinitions/{unifiedRoleManagementAlertDefinitionId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementalertdefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alerts?$filter=scopeId eq 'scopeId' and scopeType eq 'scopeType'](https://docs.microsoft.com/graph/api/rolemanagementalert-list-alerts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alerts/{unifiedRoleManagementAlertId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementalert-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alerts/{unifiedRoleManagementAlertId}/alertIncidents](https://docs.microsoft.com/graph/api/unifiedrolemanagementalert-list-alertincidents?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/alerts/{unifiedRoleManagementAlertId}/alertIncidents/{unifiedRoleManagementAlertIncidentId}](https://docs.microsoft.com/graph/api/unifiedrolemanagementalertincident-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /identityGovernance/roleManagementAlerts/operations/{longRunningOperationId}](https://docs.microsoft.com/graph/api/longrunningoperation-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|cce71173-f76d-446e-97ff-efb2d82e11b1|
|**Consent Type**|Admin|
|**Display String**|Read all alert data for your company's directory|
|**Description**|Allows the app to read the role-based access control (RBAC) alerts for your company's directory, on behalf of the signed-in user. This includes reading alert statuses, alert definitions, alert configurations and incidents that lead to an alert.|
## Application Permission
|||
|-|-|
|**Id**|ef31918f-2d50-4755-8943-b8638c0a077e|
|**Display String**|Read all alert data for your company's directory|
|**Description**|Allows the app to read all role-based access control (RBAC) alerts for your company's directory, without a signed-in user. This includes reading alert statuses, alert definitions, alert configurations and incidents that lead to an alert.|
## Resources
### [invalidLicenseAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/invalidlicensealertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
### [invalidLicenseAlertIncident ](https://docs.microsoft.com/graph/api/resources/invalidlicensealertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier for the alert incident. For example, it could be a role assignment ID if the incident represents a role assignment. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|tenantLicenseStatus|String|Status of the tenant's Microsoft Entra ID P2 license.|
### [longRunningOperation ](https://docs.microsoft.com/graph/api/resources/longrunningoperation?view=graph-rest-1.0&tabs=http)

### [noMfaOnRoleActivationAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/nomfaonroleactivationalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
### [noMfaOnRoleActivationAlertIncident ](https://docs.microsoft.com/graph/api/resources/nomfaonroleactivationalertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier for an alert incident. For example, it could be a role assignment ID if the incident represents a role assignment. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|roleDisplayName|String|The name of the Microsoft Entra ID directory role.|
|roleTemplateId|String|The globally unique identifier for a directory role.|
### [redundantAssignmentAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/redundantassignmentalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|duration|Duration|The number of days without activation to look back on from current timestamp.|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
### [redundantAssignmentAlertIncident ](https://docs.microsoft.com/graph/api/resources/redundantassignmentalertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assigneeDisplayName|String|Display name of the subject that the incident applies to.|
|assigneeId|String|The identifier of the subject that the incident applies to.|
|assigneeUserPrincipalName|String|User principal name of the subject that the incident applies to. Applies to user principals only. |
|id|String|The identifier for an alert incident. For example, it could be a role assignment ID if the incident represents a role assignment. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|lastActivationDateTime|DateTimeOffset|Date and time of the last activation of the eligible assignment.|
|roleDefinitionId|String|The identifier for the directory role definition that's in scope of this incident.|
|roleDisplayName|String|The display name for the directory role.|
|roleTemplateId|String|The globally unique identifier for the directory role.|
### [rolesAssignedOutsidePrivilegedIdentityManagementAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/rolesassignedoutsideprivilegedidentitymanagementalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
### [sequentialActivationRenewalsAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/sequentialactivationrenewalsalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
|sequentialActivationCounterThreshold|Int32|The minimum number of activations within the timeIntervalBetweenActivations period to trigger an alert.|
|timeIntervalBetweenActivations|Duration|Time interval between activations to trigger an alert.|
### [sequentialActivationRenewalsAlertIncident ](https://docs.microsoft.com/graph/api/resources/sequentialactivationrenewalsalertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activationCount|Int32|The length of sequential activation of the same role.|
|assigneeDisplayName|String|Display name of the subject that the incident applies to.|
|assigneeId|String|The identifier of the subject that the incident applies to.|
|assigneeUserPrincipalName|String|User principal name of the subject that the incident applies to. Applies to user principals.|
|id|String|The identifier for an alert incident. For example, it could be a role assignment id if the incident represents a role assignment Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|roleDefinitionId|String|The identifier for the directory role definition that's in scope of this incident.|
|roleDisplayName|String|The display name for the directory role.|
|roleTemplateId|String|The globally unique identifier for the directory role.|
|sequenceEndDateTime|DateTimeOffset|End date time of the sequential activation event.|
|sequenceStartDateTime|DateTimeOffset|Start date time of the sequential activation event.|
### [staleSignInAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/stalesigninalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|duration|Duration|The number of days to look back from current timestamp within which the account hasn't signed in.|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
### [staleSignInAlertIncident ](https://docs.microsoft.com/graph/api/resources/stalesigninalertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assigneeDisplayName|String|Display name of the subject that the incident applies to.|
|assigneeId|String|The identifier of the subject that the incident applies to.|
|assigneeUserPrincipalName|String|User principal name of the subject that the incident applies to. Applies to user principals.|
|assignmentCreatedDateTime|DateTimeOffset|Date and time of assignment creation.|
|id|String|The identifier for an alert incident. For example, it could be a role assignment id if the incident represents a role assignment Inherited from entity. Supports `$filter` (`eq`, `ne`).|
|lastSignInDateTime|DateTimeOffset|Date and time of last sign in.|
|roleDefinitionId|String|The identifier for the directory role definition that's in scope of this incident.|
|roleDisplayName|String|The display name for the directory role.|
|roleTemplateId|String|The globally unique identifier for the directory role.|
### [tooManyGlobalAdminsAssignedToTenantAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/toomanyglobaladminsassignedtotenantalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|globalAdminCountThreshold|Int32| The threshold for the number of accounts assigned the Global Administrator role in the tenant. Triggers an alert if the number of global administrators in the tenant reaches or crosses this threshold value. |
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger this alert. Inherited from unifiedRoleManagementAlertConfiguration.|
|percentageOfGlobalAdminsOutOfRolesThreshold|Int32|Threshold of the percentage of global administrators out of all the role assignments in the tenant. Triggers an alert if the percentage in the tenant reaches or crosses this threshold value.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Inherited from unifiedRoleManagementAlertConfiguration. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. Inherited from unifiedRoleManagementAlertConfiguration.|
### [tooManyGlobalAdminsAssignedToTenantAlertIncident ](https://docs.microsoft.com/graph/api/resources/toomanyglobaladminsassignedtotenantalertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assigneeDisplayName|String|Display name of the subject that the incident applies to.|
|assigneeId|String|The identifier of the subject that the incident applies to.|
|assigneeUserPrincipalName|String|User principal name of the subject that the incident applies to. Applies to user principals.|
|id|String|The identifier for the alert incident. For example, it could be a role assignment ID if the incident represents a role assignment. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
### [unifiedRoleManagementAlert ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementalert?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Supports `$filter` (`eq`, `ne`).|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|incidentCount|Int32|The number of incidents triggered in the tenant and relating to the alert. Can only be a positive integer.|
|isActive|Boolean|`false` by default. `true` if the alert is active.|
|lastModifiedDateTime|DateTimeOffset|The date time when the alert configuration was updated or new incidents generated.|
|lastScannedDateTime|DateTimeOffset|The date time when the tenant was last scanned for incidents that trigger this alert.|
|scopeId|String|The identifier of the scope where the alert is related. `/` is the only supported one for the tenant. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. |
### [unifiedRoleManagementAlertConfiguration ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementalertconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertDefinitionId|String|The identifier of an alert definition. Supports `$filter` (`eq`, `ne`).|
|id|String|The identifier of the alert configuration. Inherited from entity.|
|isEnabled|Boolean|`true` if the alert is enabled. Setting it to `false` disables PIM scanning the tenant to identify instances that trigger the alert.|
|scopeId|String|The identifier of the scope to which the alert is related. Only `/` is supported to represent the tenant scope. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. |
### [unifiedRoleManagementAlertDefinition ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementalertdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of the alert.|
|displayName|String|The friendly display name that renders in Privileged Identity Management (PIM) alerts in the Microsoft Entra admin center.|
|howToPrevent|String|Long-form text that indicates the ways to prevent the alert from being triggered in your tenant.|
|id|String|The identifier of the alert definition. Inherited from entity.|
|isConfigurable|Boolean|`true` if the alert configuration can be customized in the tenant, and `false` otherwise. For example, the number and percentage thresholds of the 'There are too many global administrators' alert can be configured by users, while the 'This organization doesn't have Microsoft Entra ID P2' can't be configured, because the criteria are restricted.|
|isRemediatable|Boolean|`true` if the alert can be remediated, and `false` otherwise.|
|mitigationSteps|String|The methods to mitigate the alert when it's triggered in the tenant. For example, to mitigate the 'There are too many global administrators', you could remove redundant privileged role assignments. |
|scopeId|String|The identifier of the scope where the alert is related. `/` is the only supported one for the tenant. Supports `$filter` (`eq`, `ne`).|
|scopeType|String|The type of scope where the alert is created. `DirectoryRole` is the only currently supported scope type for Microsoft Entra roles. |
|securityImpact|String|Security impact of the alert. For example, it could be information leaks or unauthorized access.|
|severityLevel|alertSeverity|Severity level of the alert. The possible values are: `unknown`, `informational`, `low`, `medium`, `high`, `unknownFutureValue`.|
### [unifiedRoleManagementAlertIncident ](https://docs.microsoft.com/graph/api/resources/unifiedrolemanagementalertincident?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The identifier of the alert incident. Inherited from entity. Supports `$filter` (`eq`, `ne`).|
