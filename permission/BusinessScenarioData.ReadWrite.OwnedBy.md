# BusinessScenarioData.ReadWrite.OwnedBy

> Allows the app to fully manage all data associated with the business scenarios it owns. Data access and changes will be attributed to the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /solutions/businessScenarios/{businessScenarioId}/planner/tasks/{businessScenarioTaskId}](https://docs.microsoft.com/graph/api/businessscenarioplanner-delete-tasks?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}/planner/tasks](https://docs.microsoft.com/graph/api/businessscenarioplanner-list-tasks?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}/planner/tasks/{businessScenarioTaskId}](https://docs.microsoft.com/graph/api/businessscenariotask-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /solutions/businessScenarios/{businessScenarioId}/planner/tasks/{businessScenarioTaskId}](https://docs.microsoft.com/graph/api/businessscenariotask-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /solutions/businessScenarios/{businessScenarioId}/planner/getPlan](https://docs.microsoft.com/graph/api/businessscenarioplanner-getplan?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /solutions/businessScenarios/{businessScenarioId}/planner/tasks](https://docs.microsoft.com/graph/api/businessscenarioplanner-post-tasks?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|19932d57-2952-4c60-8634-3655c79fc527|
|**Consent Type**|Admin|
|**Display String**|Read and write all data for business scenarios this app creates or owns|
|**Description**|Allows the app to fully manage all data associated with the business scenarios it owns. Data access and changes will be attributed to the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|f2d21f22-5d80-499e-91cc-0a8a4ce16f54|
|**Display String**|Read and write data for all business scenarios this app creates or owns|
|**Description**|Allows the app to fully manage the data associated with the business scenarios it owns, without a signed-in user.|
## Resources
### [businessScenario ](https://docs.microsoft.com/graph/api/resources/businessscenario?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The identity of the user who created the scenario.|
|createdDateTime|DateTimeOffset|The date and time when the scenario was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|Display name of the scenario.|
|id|String|The unique identifier for the scenario. Inherited from entity.|
|lastModifiedBy|identitySet|The identity of the user who last modified the scenario.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the scenario was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|ownerAppIds|String collection|Identifiers of applications that are authorized to work with this scenario.|
|uniqueName|String|Unique name of the scenario. To avoid conflicts, the recommended value for the unique name is a reverse domain name format, owned by the author of the scenario. For example, a scenario authored by *C
### [businessScenarioPlanReference ](https://docs.microsoft.com/graph/api/resources/businessscenarioplanreference?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the **plannerPlan**. Inherited from entity. Read-only.|
|title|String|The title property of the **p
### [businessScenarioProperties ](https://docs.microsoft.com/graph/api/resources/businessscenarioproperties?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|externalBucketId|String|The identifier for the bucketDefinition configured in the plannerPlanConfiguration for the scenario. The task will be placed in the corresponding plannerBucket in the target plan. Required.|
|externalContextId|String|The identifier for the context of the task. Context is an application controlled value, and tasks can be queried by their **externalContextId**. Optional.|
|externalObjectId|String|Application-specific identifier for the task. Every task for the same scenario must have a unique identifier specified for this property. Required.|
|externalObjectVersion|String|Application-specific version of the task. Optional.|
|webUrl|String|The URL to the application-specific experience for this task. Optional.|
### [businessScenarioTask ](https://docs.microsoft.com/graph/api/resources/businessscenariotask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activeChecklistItemCount|Int32|Number of checklist items with value set to `false`, representing incomplete items. Inherited from plannerTask.|
|appliedCategories|plannerAppliedCategories|The categories to which the task has been applied. For possible values, see plannerAppliedCategories. Inherited from plannerTask.|
|assigneePriority|String|Hint used to order items of this type in a list view. For details about the supported format, see Using order hints in Planner. Inherited from plannerTask.|
|assignments|plannerAssignments|The set of assignees the task is assigned to. Inherited from plannerTask.|
|bucketId|String|Bucket ID to which the task belongs. Inherited from plannerTask.|
|businessScenarioProperties|businessScenarioProperties|Scenario-specific properties of the task. **externalObjectId** and **externalBucketId** properties must be specified when creating a task.|
|checklistItemCount|Int32|Number of checklist items that are present on the task. Inherited from plannerTask.|
|completedBy|identitySet|Identity of the user who completed the task. Inherited from plannerTask. Read-Only.|
|completedDateTime|DateTimeOffset|Date and time at which the **percentComplete** of the task is set to `100`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from plannerTask. Read-only.|
|conversationThreadId|String|Thread ID of the conversation on the task. This property contains the ID of the conversation thread object created in the **group**. Inherited from plannerTask.|
|createdBy|identitySet|Identity of the user who created the task. Inherited from plannerTask. Read-Only.|
|createdDateTime|DateTimeOffset|Date and time at which the task is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z` Inherited from plannerTask. Read-only.|
|creationSource|plannerTaskCreation|Contains information about the origin of the task. Inherited from plannerTask.|
|dueDateTime|DateTimeOffset|Date and time at which the task is due. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from plannerTask.|
|hasDescription|Boolean|`True` indicates that the details object of the task has a nonempty description; otherwise, `false`. Inherited from plannerTask. Read-only.|
|id|String|The unique identifier for the task. Inherited from entity. Read-only.|
|orderHint|String|Hint used to order items of this type in a list view. For details about the supported format, see Using order hints in Planner. Inherited from plannerTask.|
|percentComplete|Int32|Percentage of task completion. When set to `100`, the task is considered completed. Inherited from plannerTask.|
|planId|String|Identifier of the plan to which the task belongs. Inherited from plannerTask.|
|previewType|plannerPreviewType|This sets the type of preview that shows up on the task. Possible values are: `automatic`, `noPreview`, `checklist`, `description`, `reference`. Inherited from plannerTask.|
|priority|Int32|Priority of the task. Valid range of values is between `0` and `10` (inclusive), with increasing value being lower priority (`0` has the highest priority and `10` has the lowest priority).  Currently, Planner interprets values `0` and `1` as "urgent", `2`, `3`, and `4` as "important", `5`, `6`, and `7` as "medium", and `8`, `9`, and `10` as "low".  Currently, Planner sets the value `1` for "urgent", `3` for "important", `5` for "medium", and `9` for "low". Inherited from plannerTask.|
|referenceCount|Int32|Number of external references that exist on the task. Inherited from plannerTask.|
|startDateTime|DateTimeOffset|Date and time at which the task starts. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from plannerTask.|
|target|businessScenarioTaskTargetBase|Target of the task that specifies where the task should be placed. Must be specified when creating a task.|
|title|String|Title of the task. Inherited from plannerTask.|
### [businessScenarioTaskTargetBase ](https://docs.microsoft.com/graph/api/resources/businessscenariotasktargetbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|taskTargetKind|plannerTaskTargetKind|Represents the kind of the target. The possible values are: `group`, `unknownFutureValue`.|
### [group ](https://docs.microsoft.com/graph/api/resources/group?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-|:-|:-|
| allowExternalSenders | Boolean | Indicates if people external to the organization can send messages to the group. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| assignedLabels | assignedLabel collection | The list of sensitivity label pairs (label ID, label name) associated with a Microsoft 365 group. <br><br>Returned only on `$select`. |
| assignedLicenses | assignedLicense collection | The licenses that are assigned to the group. <br><br>Returned only on `$select`. Supports `$filter` (`eq`).Read-only. |
| autoSubscribeNewMembers | Boolean | Indicates if new members added to the group are autosubscribed to receive email notifications. You can set this property in a PATCH request for the group; don't set it in the initial POST request that creates the group. Default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| classification | String | Describes a classification for the group (such as low, medium, or high business impact). Valid values for this property are defined by creating a ClassificationList setting value, based on the template definition.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| createdDateTime | DateTimeOffset | Timestamp of when the group was created. The value can't be modified and is automatically populated when the group is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. |
| deletedDateTime | DateTimeOffset | For some Microsoft Entra objects (user, group, application), if the object is deleted, it's first logically deleted, and this property is updated with the date and time when the object was deleted. Otherwise this property is `null`. If the object is restored, this property is updated to `null`. Inherited from directoryObject.  |
| description | String | An optional description for the group. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| displayName | String | The display name for the group. This property is required when a group is created and can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| expirationDateTime | DateTimeOffset | Timestamp of when the group is set to expire. It's `null` for security groups, but for Microsoft 365 groups, it represents when the group is set to expire as defined in the groupLifecyclePolicy. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| groupTypes | String collection | Specifies the group type and its membership. <br><br>If the collection contains `Unified`, the group is a Microsoft 365 group; otherwise, it's either a security group or a distribution group. For details, see groups overview.<br><br>If the collection includes `DynamicMembership`, the group has dynamic membership; otherwise, membership is static. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| hasMembersWithLicenseErrors | Boolean | Indicates whether there are members in this group that have license errors from its group-based license assignment. <br><br>This property is never returned on a GET operation. You can use it as a $filter argument to get groups that have members with license errors (that is, filter for this property being true). See an example. <br><br>Supports `$filter` (`eq`). |
| hideFromAddressLists | Boolean | True if the group isn't displayed in certain parts of the Outlook UI: the **Address Book**, address lists for selecting message recipients, and the **Browse Groups** dialog for searching groups; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| hideFromOutlookClients | Boolean | True if the group isn't displayed in Outlook clients, such as Outlook for Windows and Outlook on the web; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| id | String | The unique identifier for the group. <br><br>Returned by default. Inherited from directoryObject. Key. Not nullable. Read-only.<br><br>Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| isArchived | Boolean | When a group is associated with a team, this property determines whether the team is in read-only mode.<br/>To read this property, use the `/group/{groupId}/team` endpoint or the Get team API. To update this property, use the archiveTeam and unarchiveTeam APIs. |
| isAssignableToRole | Boolean | Indicates whether this group can be assigned to a Microsoft Entra role. Optional. <br><br>This property can only be set while creating the group and is immutable. If set to `true`, the **securityEnabled** property must also be set to `true`, **visibility** must be `Hidden`, and the group can't be a dynamic group (that is, **groupTypes** can't contain `DynamicMembership`). <br/><br/>Only callers with at least the Privileged Role Administrator role can set this property. The caller must also be assigned the _RoleManagement.ReadWrite.Directory_ permission to set this property or update the membership of such groups. For more, see Using a group to manage Microsoft Entra role assignments<br><br>Using this feature requires a Microsoft Entra ID P1 license. Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| isSubscribedByMail | Boolean | Indicates whether the signed-in user is subscribed to receive email conversations. The default value is `true`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| licenseProcessingState | String | Indicates the status of the group license assignment to all group members. The default value is `false`. Read-only. Possible values: `QueuedForProcessing`, `ProcessingInProgress`, and `ProcessingComplete`.<br><br>Returned only on `$select`. Read-only. |
| mail | String | The SMTP address for the group, for example, "serviceadmins@contoso.com". <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| mailEnabled | Boolean | Specifies whether the group is mail-enabled. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| mailNickname | String | The mail alias for the group, unique for Microsoft 365 groups in the organization. Maximum length is 64 characters. This property can contain only characters in the ASCII character set 0 - 127 except the following characters: ` @ () \ [] " ; : <> , SPACE`. <br><br>Required. Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| membershipRule | String | The rule that determines members for this group if the group is a dynamic group (groupTypes contains `DynamicMembership`). For more information about the syntax of the membership rule, see Membership Rules syntax. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| membershipRuleProcessingState | String | Indicates whether the dynamic membership processing is on or paused. Possible values are `On` or `Paused`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| onPremisesDomainName | String | Contains the on-premises **domain FQDN**, also called **dnsDomainName** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesLastSyncDateTime | DateTimeOffset | Indicates the last time at which the group was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
| onPremisesNetBiosName | String | Contains the on-premises **netBios name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | Errors when using Microsoft synchronization product during provisioning. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| onPremisesSamAccountName | String | Contains the on-premises **SAM account name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`). Read-only. |
| onPremisesSecurityIdentifier | String | Contains the on-premises security identifier (SID) for the group synchronized from on-premises to the cloud. Read-only. <br><br>Returned by default. Supports `$filter` (`eq` including on `null` values). |
| onPremisesSyncEnabled | Boolean | `true` if this group is synced from an on-premises directory; `false` if this group was originally synced from an on-premises directory but is no longer synced; **null** if this object has never synced from an on-premises directory (default). <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). |
| preferredDataLocation | String | The preferred data location for the Microsoft 365 group. By default, the group inherits the group creator's preferred data location. To set this property, the calling app must be granted the *Directory.ReadWrite.All* permission and the user be assigned at least one of the following Microsoft Entra roles: <br><ul>User Account Administrator <li>Directory Writer <li> Exchange Administrator <li> SharePoint Administrator </ul><br/> For more information about this property, see OneDrive Online Multi-Geo. <br><br>Nullable. Returned by default. |
| preferredLanguage | String | The preferred language for a Microsoft 365 group. Should follow ISO 639-1 Code; for example, `en-US`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| proxyAddresses | String collection | Email addresses for the group that direct to the same group mailbox. For example: `["SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. The **any** operator is required to filter expressions on multi-valued properties. <br><br>Returned by default. Read-only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`). |
| renewedDateTime | DateTimeOffset | Timestamp of when the group was last renewed. This value can't be modified directly and is only updated via the renew service action. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| securityEnabled | Boolean | Specifies whether the group is a security group. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| securityIdentifier | String | Security identifier of the group, used in Windows scenarios. Read-only. <br><br>Returned by default. |
| serviceProvisioningErrors | serviceProvisioningError collection | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a group object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance). |
| theme | string | Specifies a Microsoft 365 group's color theme. Possible values are `Teal`, `Purple`, `Green`, `Blue`, `Pink`, `Orange`, or `Red`. <br><br>Returned by default. |
| uniqueName | String | The unique identifier that can be assigned to a group and used as an alternate key. Immutable. Read-only. |
| unseenCount | Int32 | Count of conversations that received new posts since the signed-in user last visited the group. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| visibility | String | Specifies the group join policy and group content visibility for groups. Possible values are: `Private`, `Public`, or `HiddenMembership`. `HiddenMembership` can be set only for Microsoft 365 groups when the groups are created. It can't be updated later. Other values of visibility can be updated after group creation.<br> If visibility value isn't specified during group creation on Microsoft Graph, a security group is created as `Private` by default, and the Microsoft 365 group is `Public`. Groups assignable to roles are always `Private`. To learn more, see group visibility options. <br><br>Returned by default. Nullable. |
### [planner-order-hint-format](https://docs.microsoft.com/graph/api/resources/planner-order-hint-format?view=graph-rest-1.0&tabs=http)

### [plannerAppliedCategories ](https://docs.microsoft.com/graph/api/resources/plannerappliedcategories?view=graph-rest-1.0&tabs=http)

### [plannerAssignments ](https://docs.microsoft.com/graph/api/resources/plannerassignments?view=graph-rest-1.0&tabs=http)

### [plannerPlan ](https://docs.microsoft.com/graph/api/resources/plannerplan?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|container|plannerPlanContainer|Identifies the container of the plan. Specify only the **url**, the **containerId** and **type**, or all properties. After it's set, this property can’t be updated. Required.|
|createdBy|identitySet|Read-only. The user who created the plan.|
|createdDateTime|DateTimeOffset|Read-only. Date and time at which the plan is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|id|String| Read-only. ID of the plan. It's 28 characters long and case-sensitive. Format validation is done on the service.|
|owner (deprecated) |String| Use the **container** property instead. ID of the group that owns the plan. After it's set, this property can’t be updated. This property won't return a valid group ID if the container of the plan isn't a group.|
|title|String|Required. Title of the plan.|
### [plannerTask ](https://docs.microsoft.com/graph/api/resources/plannertask?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|activeChecklistItemCount|Int32|Number of checklist items with value set to `false`, representing incomplete items.|
|appliedCategories|plannerAppliedCategories|The categories to which the task has been applied. See applied Categories for possible values.|
|assigneePriority|String|Hint used to order items of this type in a list view. The format is defined as outlined here.|
|assignments|plannerAssignments|The set of assignees the task is assigned to.|
|bucketId|String|Bucket ID to which the task belongs. The bucket needs to be in the plan that the task is in. It's 28 characters long and case-sensitive. Format validation is done on the service. |
|checklistItemCount|Int32|Number of checklist items that are present on the task.|
|completedBy|identitySet|Identity of the user that completed the task.|
|completedDateTime|DateTimeOffset|Read-only. Date and time at which the `'percentComplete'` of the task is set to `'100'`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|conversationThreadId|String|Thread ID of the conversation on the task. This is the ID of the conversation thread object created in the group.|
|createdBy|identitySet|Identity of the user that created the task.|
|createdDateTime|DateTimeOffset|Read-only. Date and time at which the task is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|dueDateTime|DateTimeOffset|Date and time at which the task is due. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|hasDescription|Boolean|Read-only. Value is `true` if the details object of the task has a nonempty description and `false` otherwise.|
|id|String|Read-only. ID of the task. It's 28 characters long and case-sensitive. Format validation is done on the service.|
|orderHint|String|Hint used to order items of this type in a list view. The format is defined as outlined here.|
|percentComplete|Int32|Percentage of task completion. When set to `100`, the task is considered completed. |
|planId|String|Plan ID to which the task belongs.|
|previewType|String|This sets the type of preview that shows up on the task. The possible values are: `automatic`, `noPreview`, `checklist`, `description`, `reference`.|
|priority|Int32|Priority of the task. The valid range of values is between `0` and `10`, with the increasing value being lower priority (`0` has the highest priority and `10` has the lowest priority).  Currently, Planner interprets values `0` and `1` as "urgent", `2`, `3` and `4` as "important", `5`, `6`, and `7` as "medium", and `8`, `9`, and `10` as "low".  Additionally, Planner sets the value `1` for "urgent", `3` for "important", `5` for "medium", and `9` for "low".|
|referenceCount|Int32|Number of external references that exist on the task.|
|startDateTime|DateTimeOffset|Date and time at which the task starts. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|title|String|Title of the task.|
### [tasks-identifiers-disclaimer](https://docs.microsoft.com/graph/api/resources/tasks-identifiers-disclaimer?view=graph-rest-1.0&tabs=http)

