# BackupRestore-Configuration.Read.All

> Allows the app to read the backup configuration, and list of Microsoft 365 service resources to be backed up, on behalf of the signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /solutions/backupRestore/driveProtectionUnits](https://docs.microsoft.com/graph/api/backuprestoreroot-list-driveprotectionunits?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/exchangeProtectionPolicies/{exchangeProtectionPolicyId}/mailboxInclusionRules](https://docs.microsoft.com/graph/api/exchangeprotectionpolicy-list-mailboxinclusionrules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/exchangeProtectionPolicies/{exchangeProtectionPolicyId}/mailboxInclusionRules/{mailboxProtectionRuleId}](https://docs.microsoft.com/graph/api/protectionrulebase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/exchangeProtectionPolicies/{exchangeProtectionPolicyId}/mailboxProtectionUnits/](https://docs.microsoft.com/graph/api/backuprestoreroot-list-mailboxprotectionunits?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/mailboxProtectionUnits](https://docs.microsoft.com/graph/api/backuprestoreroot-list-mailboxprotectionunits?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/oneDriveForBusinessProtectionPolicies/{oneDriveForBusinessProtectionPolicyId}/driveInclusionRules](https://docs.microsoft.com/graph/api/onedriveforbusinessprotectionpolicy-list-driveinclusionrules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/oneDriveForBusinessProtectionPolicies/{oneDriveForBusinessProtectionPolicyId}/driveInclusionRules/{driveProtectionRuleId}](https://docs.microsoft.com/graph/api/protectionrulebase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/oneDriveForBusinessProtectionPolicies/{oneDriveForBusinessProtectionPolicyId}/driveProtectionUnits](https://docs.microsoft.com/graph/api/backuprestoreroot-list-driveprotectionunits?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/protectionPolicies](https://docs.microsoft.com/graph/api/backuprestoreroot-list-protectionpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/protectionPolicies/{protectionPolicyBaseId}](https://docs.microsoft.com/graph/api/protectionpolicybase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/protectionUnits/{protectionUnitBaseId}](https://docs.microsoft.com/graph/api/protectionunitbase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/sharePointProtectionPolicies/{sharePointProtectionPolicyId}/siteInclusionRules](https://docs.microsoft.com/graph/api/sharepointprotectionpolicy-list-siteinclusionrules?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/sharePointProtectionPolicies/{sharePointProtectionPolicyId}/siteInclusionRules/{siteProtectionRuleId}](https://docs.microsoft.com/graph/api/protectionrulebase-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/sharePointProtectionPolicies/{sharePointProtectionPolicyId}/siteProtectionUnits](https://docs.microsoft.com/graph/api/backuprestoreroot-list-siteprotectionunits?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/backupRestore/siteProtectionUnits](https://docs.microsoft.com/graph/api/backuprestoreroot-list-siteprotectionunits?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|444ed4b6-0554-4dc6-8e9c-3f9a34ee3ff6|
|**Consent Type**|Admin|
|**Display String**|Read backup configuration policies|
|**Description**|Allows the app to read the backup configuration, and list of Microsoft 365 service resources to be backed up, on behalf of the signed in user.|
## Application Permission
|||
|-|-|
|**Id**|5fbb5982-3230-4882-93c0-2167523ce0c2|
|**Display String**|Read all backup configuration policies|
|**Description**|Allows the app to read all backup configurations, and lists of Microsoft 365 service resources to be backed up, without a signed-in user.|
## Resources
### [driveProtectionRule ](https://docs.microsoft.com/graph/api/resources/driveprotectionrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated with the policy.|
|createdBy|identitySet entitySet|The identity of the person who created the rule.|
|createdDateTime|DateTimeOffset|The date and time that the rule was created.|
|driveExpression|String|Contains a drive expression. For examples, see driveExpression examples.|
|error|publicError|If the operation fails, contains the details of the error.|
|isAutoApplyEnabled|Boolean|Indicates whether the protection rule is static or dynamic. Static rules run once; dynamic rules listen to all changes in the system and update the protection unit list.|
|lastModifiedBy|identitySet|Identity of the person who last modified this rule.|
|lastModifiedDateTime|DateTimeOffset|The timestamp of the last modification to this rule.|
|status|protectionRuleStatus|The status of the protection rule. The following are the possible values: `draft`, `active`, `completed`, `completedWithErrors`, `unknownFutureValue`.|
### [driveProtectionUnit ](https://docs.microsoft.com/graph/api/resources/driveprotectionunit?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The identity of person who created the protection unit. Inherited from protectionUnitBase.|
|createdDateTime|DateTimeOffset|The time of creation of the protection unit. Inherited from protectionUnitBase.|
|directoryObjectId|String|ID of the directory object.|
|displayName|String|Display name of the directory object.|
|email|String|Email associated with the directory object.|
|error|publicError|Details of the error if the enablement/disablement of the protection unit fails. Inherited from protectionUnitBase.|
|id|String|Unique identifier of the protection policy associated with this protection unit.|
|lastModifiedBy|identitySet|The identity of person who last modified the protection unit. Inherited from protectionUnitBase.|
|lastModifiedDateTime|DateTimeOffset|The time of last modification of the protection unit. Inherited from protectionUnitBase.|
|policyId|String|Unique identifier of the protection policy associated with this protection unit. Inherited from protectionUnitBase.|
|status|protectionUnitStatus|The individual enablement/disablement/removal status of the protection unit. Inherited from protectionUnitBase. The possible values are: `protectRequested`, `protected`, `unprotectRequested`, `unprotected`, `removeRequested`, `unknownFutureValue`.|
### [exchangeProtectionPolicy ](https://docs.microsoft.com/graph/api/resources/exchangeprotectionpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated to the policy.|
|displayName|String|Name of the policy to be created. |
|createdDateTime|DateTimeOffset|The time of creation of the policy.|
|createdBy|identitySet|The identity of person who created the policy.|
|lastModifiedBy|identitySet|The identity of the person who last modified the policy.|
|lastModifiedDateTime|DateTimeOffset|The timestamp of the last modification of the policy.|
|status|protectionPolicyStatus|Status of the policy. This value is an aggregated status of the protection units. The possible values are: `inactive`, `activeWithErrors`, `updating`, `active`, `unknownFutureValue`.|
### [mailboxProtectionRule ](https://docs.microsoft.com/graph/api/resources/mailboxprotectionrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated with the policy.|
|createdBy|identitySet|The identity of the person who created the rule.|
|createdDateTime|DateTimeOffset|The date and time that the rule was created.|
|error|publicError|Contains error details if an operation on a rule expression fails.|
|isAutoApplyEnabled|Boolean|Indicates whether the protection rule is static or dynamic. Static rules run one time and dynamic rules listen to all changes in the system and update the protection unit list.|
|lastModifiedBy|identitySet|Identity of the person who last modified this rule.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of last modification to the rule.|
|mailboxExpression|String|Contains a mailbox expression. For examples, see mailboxExpression examples.|
|status|protectionRuleStatus|Status of the protection rule. The possible values are: `draft`, `active`, `completed`, `completedWithErrors`, `unknownFutureValue`.|
### [mailboxProtectionUnit ](https://docs.microsoft.com/graph/api/resources/mailboxprotectionunit?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The identity of person who created the protection unit. Inherited from protectionUnitBase.|
|createdDateTime|DateTimeOffset|The time of creation of the protection unit. Inherited from protectionUnitBase.|
|directoryObjectId|String|The ID of the directory object.|
|displayName|String|Display name of the directory object.|
|email|String|Email address associated with the directory object.|
|error|publicError|Contains error details if enabling or disabling the protection unit fails. Inherited from protectionUnitBase.|
|id|String|Unique identifier of the protection policy associated with this protection unit.|
|lastModifiedBy|identitySet|The identity of person who last modified the protection unit. Inherited from protectionUnitBase.|
|lastModifiedDateTime|DateTimeOffset|The time the protection unit was last modified. Inherited from protectionUnitBase.|
|policyId|String|Unique identifier of the protection policy associated with this protection unit. Inherited from protectionUnitBase.|
|status|protectionUnitStatus|The individual enable, disable, or removal status of the protection unit. Inherited from protectionUnitBase.The possible values are: `protectRequested`, `protected`, `unprotectRequested`, `unprotected`, `removeRequested`, `unknownFutureValue`.|
### [oneDriveForBusinessProtectionPolicy ](https://docs.microsoft.com/graph/api/resources/onedriveforbusinessprotectionpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated with the policy.|
|displayName|String|The name of the policy to be created.|
|createdDateTime|DateTimeOffset|The time of creation of the policy.|
|createdBy|identitySet|The identity of person who created the policy.|
|lastModifiedBy|identitySet|The identity of the person who last modified the policy.|
|lastModifiedDateTime|DateTimeOffset|The timestamp of the last modification of the policy.|
|status|protectionPolicyStatus|Status of the policy. The value is the aggregated status of the protection units. The possible values are: `inactive`, `activeWithErrors`, `updating`, `active`, `unknownFutureValue`.|
### [protectionPolicyBase ](https://docs.microsoft.com/graph/api/resources/protectionpolicybase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated with the policy.|
|displayName|String|The name of the policy to be created.|
|createdDateTime|DateTimeOffset|The time of creation of the policy.|
|createdBy|identitySet|The identity of person who created the policy.|
|lastModifiedBy|identitySet|The identity of the person who last modified the policy.|
|lastModifiedDateTime|DateTimeOffset|The timestamp of the last modification of the policy.|
|retentionSettings|retentionSetting collection|Contains the retention setting details for the policy.|
|status|protectionPolicyStatus|The aggregated status of the protection units associated with the policy. The possible values are: `inactive`, `activeWithErrors`, `updating`, `active`, `unknownFutureValue`.|
### [protectionRuleBase ](https://docs.microsoft.com/graph/api/resources/protectionrulebase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated with the policy.|
|createdBy|identitySet|The identity of person who created the rule.|
|createdDateTime|DateTimeOffset|The time of creation of the rule.|
|error|publicError|Contains error details if an operation on a rule fails.|
|isAutoApplyEnabled|Boolean|Indicates whether the protection rule is static or dynamic.|
|lastModifiedBy|identitySet|The identity of the person who last modified the rule.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification made to the rule.|
|status|protectionRuleStatus|The status of the protection rule. The possible values are: `draft`, `active`, `completed`, `completedWithErrors`, `unknownFutureValue`.|
### [protectionUnitBase ](https://docs.microsoft.com/graph/api/resources/protectionunitbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection unit.|
|policyId|String|The unique identifier of the protection policy based on which protection unit was created.|
|createdBy|identitySet|The identity of person who created the protection unit.|
|createdDateTime|DateTimeOffset|The time of creation of the protection unit.|
|error|publicError|Contains error details if an error occurred while creating a protection unit.|
|lastModifiedBy|identitySet|The identity of person who last modified the protection unit.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification of this protection unit.|
|status|protectionUnitStatus|The status of the protection unit. The possible values are: `protectRequested`, `protected`, `unprotectRequested`, `unprotected`, `removeRequested`, `unknownFutureValue`.|
### [sharePointProtectionPolicy ](https://docs.microsoft.com/graph/api/resources/sharepointprotectionpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated to the policy.|
|displayName|String|The name of the policy being created.|
|createdDateTime|DateTimeOffset|The time of creation of the policy.|
|createdBy|identitySet|The identity of person who created the policy.|
|lastModifiedBy|identitySet|The identity of person who modified the policy.|
|lastModifiedDateTime|DateTimeOffset|The timestamp of the last modification of the policy.|
|retentionSettings|retentionSetting collection|Retention settings for the policy.|
|status|protectionPolicyStatus|The status of the policy. The value is an aggregated status of the protection units. The possible values are: `inactive`, `activeWithErrors`, `updating`, `active`, `unknownFutureValue`.|
### [siteProtectionRule ](https://docs.microsoft.com/graph/api/resources/siteprotectionrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the protection rule associated with the policy.|
|createdBy|identitySet|The identity of the person who created the rule.|
|createdDateTime|DateTimeOffset|The date and time that the rule was created.|
|error|publicError|Contains error details if any operation on a rule expression fails.|
|isAutoApplyEnabled|Boolean|Indicates whether the protection rule is static or dynamic. Static rules run one time and dynamic rules listen to all changes in the system and update the protection unit list.|
|lastModifiedBy|identitySet|Identity of the person who last modified the rule.|
|lastModifiedDateTime|DateTimeOffset|Timestamp of the last modification to the rule.|
|siteExpression|String|Contains a site expression. For examples, see siteExpression example.|
|status|protectionRuleStatus|Status of the protection rule. The possible values are: `draft`, `active`, `completed`, `completedWithErrors`, `unknownFutureValue`.|
### [siteProtectionUnit ](https://docs.microsoft.com/graph/api/resources/siteprotectionunit?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The identity of person who created the protection unit. Inherited from protectionUnitBase.|
|createdDateTime|DateTimeOffset|The time of creation of the protection unit. Inherited from protectionUnitBase.|
|error|publicError|Contains error details if enabling or disabling the protection unit fails. Inherited from protectionUnitBase.|
|id|String|Unique identifier of the protection policy associated with this protection unit.|
|lastModifiedBy|identitySet|The identity of the person who last modified the protection unit. Inherited from protectionUnitBase.|
|lastModifiedDateTime|DateTimeOffset|The time the protection unit was last modified. Inherited from protectionUnitBase.|
|policyId|String|Unique identifier of the protection policy associated with this protection unit. Inherited from protectionUnitBase.|
|siteId|String|Unique identifier of the SharePoint site.|
|siteName|String|Name of the SharePoint site.|
|siteWebUrl|String|The web URL of the SharePoint site.|
|status|protectionUnitStatus|The individual enable, disable, or removal status of the protection unit. Inherited from protectionUnitBase. The possible values are: `protectRequested`, `protected`, `unprotectRequested`, `unprotected`, `removeRequested`, `unknownFutureValue`.|
