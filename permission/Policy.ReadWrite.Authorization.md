# Policy.ReadWrite.Authorization

> Allows the app to read and write your organization's authorization policy on behalf of the signed-in user.  For example, authorization policies can control some of the permissions that the out-of-the-box user role has by default.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /groupSettings/{groupSettingId}](https://docs.microsoft.com/graph/api/groupsetting-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /settings/{directorySettingId}](https://docs.microsoft.com/graph/api/directorysetting-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /policies/authorizationPolicy](https://docs.microsoft.com/graph/api/authorizationpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groupSettings/{groupSettingId}](https://docs.microsoft.com/graph/api/groupsetting-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /policies/authorizationPolicy](https://docs.microsoft.com/graph/api/authorizationpolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /policies/authorizationPolicy/authorizationPolicy](https://docs.microsoft.com/graph/api/authorizationpolicy-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /settings/{directorySettingId}](https://docs.microsoft.com/graph/api/directorysetting-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|edd3c878-b384-41fd-95ad-e7407dd775be|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's authorization policy|
|**Description**|Allows the app to read and write your organization's authorization policy on behalf of the signed-in user.  For example, authorization policies can control some of the permissions that the out-of-the-box user role has by default.|
## Application Permission
|||
|-|-|
|**Id**|fb221be6-99f2-473f-bd32-01c6a0e9ca3b|
|**Display String**|Read and write your organization's authorization policy|
|**Description**|Allows the app to read and write your organization's authorization policy without a signed in user. For example, authorization policies can control some of the permissions that the out-of-the-box user role has by default.|
## Resources
### [authorizationPolicy ](https://docs.microsoft.com/graph/api/resources/authorizationpolicy?view=graph-rest-1.0&tabs=http)
| Property | Type | Description | 
|-|-|-|
|allowEmailVerifiedUsersToJoinOrganization|Boolean| Indicates whether a user can join the tenant by email validation. | 
|allowInvitesFrom|allowInvitesFrom|Indicates who can invite guests to the organization. Possible values are: `none`, `adminsAndGuestInviters`, `adminsGuestInvitersAndAllMembers`, `everyone`.  `everyone` is the default setting for all cloud environments except US Government. For more information, see allowInvitesFrom values. |
|allowUserConsentForRiskyApps|Boolean| Indicates whether user consent for risky apps is allowed. We recommend keeping allowUserConsentForRiskyApps as `false`. Default value is `false`. |
|allowedToSignUpEmailBasedSubscriptions|Boolean| Indicates whether users can sign up for email based subscriptions. | 
|allowedToUseSSPR|Boolean|  Indicates whether administrators of the tenant can use the Self-Service Password Reset (SSPR). For more information, see Self-service password reset for administrators. | 
|blockMsolPowerShell|Boolean| To disable the use of MSOL PowerShell, set this property to `true`. This also disables user-based access to the legacy service endpoint used by MSOL PowerShell. This doesn't affect Microsoft Entra Connect or Microsoft Graph. | 
|defaultUserRolePermissions|defaultUserRolePermissions| Specifies certain customizable permissions for default user role. | 
|description|String| Description of this policy.|
|displayName|String| Display name for this policy. |    
|guestUserRoleId|Guid| Represents role templateId for the role that should be granted to guests. Currently following roles are supported:  *User* (`a0b1b346-4d3e-4e8b-98f8-753987be4970`), *Guest User* (`10dae51f-b6af-4016-8d66-8c2a99b929b3`), and *Restricted Guest User* (`2af84b1e-32c8-42b7-82bc-daa82404023b`). |
|id|String| ID of the authorization policy. Required. Read-only.|
### [defaultUserRolePermissions ](https://docs.microsoft.com/graph/api/resources/defaultuserrolepermissions?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-------- |:---- |:----------- |
| allowedToCreateApps | Boolean | Indicates whether the default user role can create applications. This setting corresponds to the _Users can register applications_ setting in the User settings menu in the Microsoft Entra admin center. |  
| allowedToCreateSecurityGroups | Boolean | Indicates whether the default user role can create security groups. This setting corresponds to the following menus in the Microsoft Entra admin center: <br/><li> _The Users can create security groups in Microsoft Entra admin centers, API or PowerShell_ setting in the Group settings menu. <li> _Users can create security groups_ setting in the User settings menu. |  
| allowedToCreateTenants | Boolean | Indicates whether the default user role can create tenants. This setting corresponds to the _Restrict non-admin users from creating tenants_ setting in the User settings menu in the Microsoft Entra admin center. <br/><br/> When this setting is `false`, users assigned the Tenant Creator role can still create tenants.| 
|permissionGrantPoliciesAssigned|String collection|Indicates if user consent to apps is allowed, and if it is, which permission to grant consent and which app consent policy (permissionGrantPolicy) govern the permission for users to grant consent. Value should be in the format `managePermissionGrantsForSelf.{id}`, where `{id}` is the **id** of a built-in or custom app consent policy. An empty list indicates user consent to apps is disabled. |
| allowedToReadBitlockerKeysForOwnedDevice | Boolean | Indicates whether the registered owners of a device can read their own BitLocker recovery keys with default user role. |
| allowedToReadOtherUsers | Boolean | Indicates whether the default user role can read other users. **D
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
### [groupSetting ](https://docs.microsoft.com/graph/api/resources/groupsetting?view=graph-rest-1.0&tabs=http)
| Property    | Type                                       | Description                                                                                                                                                             |
| :---------- | :----------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| displayName | String                                     | Display name of this group of settings, which comes from the associated template.                                                                                       |
| id          | String                                     | Unique identifier for these settings. Read-only.                                                                                                                        |
| templateId  | String                                     | Unique identifier for the tenant-level groupSettingTemplates object that's been customized for this group-level settings object. Read-only.  |
| values      | settingValue collection | Collection of name-value pairs corresponding to the **n
### [settingValue ](https://docs.microsoft.com/graph/api/resources/settingvalue?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
|name|String| Name of the setting (as defined by the groupSettingTemplate). |
|value|String| Value of the setting. |
