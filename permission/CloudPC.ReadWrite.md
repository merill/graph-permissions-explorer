# CloudPC.ReadWrite

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /me/cloudPCs/{cloudPCId}/getFrontlineCloudPcAccessState](https://docs.microsoft.com/graph/api/cloudpc-getfrontlinecloudpcaccessstate?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
### [cloudPC ](https://docs.microsoft.com/graph/api/resources/cloudpc?view=graph-rest-1.0&tabs=http)
|Property|Type| Description                                                                                                                                                                                                                                                                                                         |
|:---|:---|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|aadDeviceId|String| The Microsoft Entra device ID for the Cloud PC, also known as the Azure Active Directory (Azure AD) device ID, that consists of 32 characters in a GUID format. Generated on a VM joined to Microsoft Entra ID. Read-only.                                                                                                                                                                      |
|displayName|String| The display name for the Cloud PC. Maximum length is 64 characters. Read-only. You can use the cloudPC: rename API to modify the Cloud PC name.                                                                                                                                                                                   |
|gracePeriodEndDateTime|DateTimeOffset| The date and time when the grace period ends and reprovisioning or deprovisioning happen. Required only if the status is `inGracePeriod`. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                       |
|id|String| The unique identifier of the customer-facing Cloud PC entity that consists of 32 characters in a GUID format. Read-only. Inherited from entity.                                                                                                                                                                                                                  |
|imageDisplayName|String| The name of the operating system image used for the Cloud PC. Maximum length is 50 characters. Only letters (A-Z, a-z), numbers (0-9), and special characters (-,_,.) are allowed for this property. The property value can't begin or end with an underscore. Read-only.|
|lastModifiedDateTime|DateTimeOffset| The last modified date and time of the Cloud PC. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                                                                                       |
|managedDeviceId|String| The Intune enrolled device ID for the Cloud PC that consists of 32 characters in a GUID format. The **managedDeviceId** property of Windows 365 Business Cloud PCs is always null as Windows 365 Business Cloud PCs aren't Intune-enrolled automatically by Windows 365. Read-only.                                                                         |
|managedDeviceName|String| The Intune enrolled device name for the Cloud PC. The **managedDeviceName** property of Windows 365 Business Cloud PCs is always null as Windows 365 Business Cloud PCs aren't Intune-enrolled automatically by Windows 365. Read-only.                                                                                                   |
|onPremisesConnectionName|String| The on-premises connection that applied during the provisioning of Cloud PCs. Read-only.                                                                                                                                                                                                                                |
|provisioningPolicyId|String| The provisioning policy ID for the Cloud PC that consists of 32 characters in a GUID format. A policy defines the type of Cloud PC the user wants to create. Read-only.                                                                                                                                                                                                                                                                        |
|provisioningPolicyName|String| The provisioning policy that applied during the provisioning of Cloud PCs. Maximum length is 120 characters. Read-only.                                                                                                                                                                                                      |
|provisioningType|cloudPcProvisioningType| The type of licenses to be used when provisioning Cloud PCs using this policy. Possible values are: `dedicated`, `shared`, `unknownFutureValue`. The default value is `dedicated`.                                                                                                                                      |
|servicePlanId|String| The service plan ID for the Cloud PC that consists of 32 characters in a GUID format. For more information about service plans, see Product names and service plan identifiers for licensing. Read-only.                                                                                               
|servicePlanName|String| The service plan name for the customer-facing Cloud PC entity. Read-only.                                                                                                                                                                                                                                     |
|userPrincipalName|String| The user principal name (UPN) of the user assigned to the Cloud PC. Maximum length is 113 characters. For more information on username policies, see Password policies and account restrictions in Microsoft Entra ID. Read-only.                       |
### [cloudPcProvisioningPolicy ](https://docs.microsoft.com/graph/api/resources/cloudpcprovisioningpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alternateResourceUrl|String|The URL of the alternate resource that links to this provisioning policy. Read-only.|
|cloudPcGroupDisplayName|String|The display name of the Cloud PC group that the Cloud PCs reside in. Read-only.|
|cloudPcNamingTemplate|String|The template used to name Cloud PCs provisioned using this policy. The template can contain custom text and replacement tokens, including `%USERNAME:x%` and `%RAND:x%`, which represent the user's name and a randomly generated number, respectively. For example, `CPC-%USERNAME:4%-%RAND:5%` means that the name of the Cloud PC starts with `CPC-`, followed by a four-character username, a `-` character, and then five random characters. The total length of the text generated by the template can't exceed 15 characters. Supports `$filter`, `$select`, and `$orderby`.|
|description|String|The provisioning policy description. Supports `$filter`, `$select`, and `$orderBy`. |
|displayName|String|The display name for the provisioning policy.|
|domainJoinConfigurations|cloudPcDomainJoinConfiguration collection|Specifies a list ordered by priority on how Cloud PCs join Microsoft Entra ID (Azure AD). Supports `$select`.|
|enableSingleSignOn|Boolean|`True` if the provisioned Cloud PC can be accessed by single sign-on. `False` indicates that the provisioned Cloud PC doesn't support this feature. The default value is `false`. Windows 365 users can use single sign-on to authenticate to Microsoft Entra ID with passwordless options (for example, FIDO keys) to access their Cloud PC. Optional.|
|gracePeriodInHours|Int32|The number of hours to wait before reprovisioning/deprovisioning happens. Read-only.|
|id|String|The unique identifier associated with the provisioning policy. This ID is auto populated during the creation of a new provisioning policy. Supports `$filter`, `$select`, and `$orderBy`. Read-only. Inherited from entity. |
|imageDisplayName|String|The display name of the operating system image that is used for provisioning. For example, `Windows 11 Preview + Microsoft 365 Apps 23H2 23H2`. Supports `$filter`, `$select`, and `$orderBy`. |
|imageId|String|The unique identifier that represents an operating system image that is used for provisioning new Cloud PCs. The format for a gallery type image is: {publisherName_offerName_skuName}. Supported values for each of the parameters are:<ul><li>publisher: `Microsoftwindowsdesktop`</li> <li>offer: `windows-ent-cpc`</li> <li>sku: `21h1-ent-cpc-m365`, `21h1-ent-cpc-os`, `20h2-ent-cpc-m365`, `20h2-ent-cpc-os`, `20h1-ent-cpc-m365`, `20h1-ent-cpc-os`, `19h2-ent-cpc-m365`, and `19h2-ent-cpc-os`</li></ul> Supports `$filter`, `$select`, and `$orderBy`.|
|imageType|cloudPcProvisioningPolicyImageType|The type of operating system image (custom or gallery) that is used for provisioning on Cloud PCs. Possible values are: `gallery`, `custom`. The default value is `gallery`. Supports $filter, $select, and $orderBy.|
|localAdminEnabled|Boolean|When `true`, the local admin is enabled for Cloud PCs; `false` indicates that the local admin isn't enabled for Cloud PCs. The default value is `false`. Supports `$filter`, `$select`, and `$orderBy`.|
|microsoftManagedDesktop|microsoftManagedDesktop|The specific settings to **microsoftManagedDesktop** that enables Microsoft Managed Desktop customers to get device managed experience for Cloud PC. To enable **microsoftManagedDesktop** to provide more value, an admin needs to specify certain settings in it. Supports `$filter`, `$select`, and `$orderBy`.|
|provisioningType|cloudPcProvisioningType|Specifies the type of license used when provisioning Cloud PCs using this policy. By default, the license type is `dedicated` if the **provisioningType** isn't specified when you create the **cloudPcProvisioningPolicy**. You can't change this property after the **cloudPcProvisioningPolicy** was created. Possible values are: `dedicated`, `shared`, `unknownFutureValue`.|
|windowsSetting|cloudPcWindowsSetting|Indicates a specific Windows setting to configure during the creation of Cloud PCs for this provisioning policy. Supports `$select`. |
