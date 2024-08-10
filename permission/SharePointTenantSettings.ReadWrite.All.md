# SharePointTenantSettings.ReadWrite.All

> Allows the application to read and change the tenant-level settings of SharePoint and OneDrive on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /admin/sharepoint/settings](https://docs.microsoft.com/graph/api/sharepointsettings-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /admin/sharepoint/settings](https://docs.microsoft.com/graph/api/sharepointsettings-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|aa07f155-3612-49b8-a147-6c590df35536|
|**Consent Type**|Admin|
|**Display String**|Read and change SharePoint and OneDrive tenant settings|
|**Description**|Allows the application to read and change the tenant-level settings of SharePoint and OneDrive on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|19b94e34-907c-4f43-bde9-38b1909ed408|
|**Display String**|Read and change SharePoint and OneDrive tenant settings|
|**Description**|Allows the application to read and change the tenant-level settings of SharePoint and OneDrive, without a signed-in user.|
## Resources
### [idleSessionSignOut ](https://docs.microsoft.com/graph/api/resources/idlesessionsignout?view=graph-rest-1.0&tabs=http)
| Property              | Type     | Description                                                                               |
|:----------------------|:---------|:------------------------------------------------------------------------------------------|
| isEnabled             | Boolean  | Indicates whether the idle session sign-out policy is enabled.                            |
| signOutAfterInSeconds | Int64    | Number of seconds of inactivity after which a user is signed out.                         |
| warnAfterInSeconds    | Int64    | Number of seconds of inactivity after which a user is notified that they'll be signed out.|
### [sharepointSettings ](https://docs.microsoft.com/graph/api/resources/sharepointsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| allowedDomainGuidsForSyncApp                       | GUID collection              | Collection of trusted domain GUIDs for the OneDrive sync app.                                                                                                                                                  |
| availableManagedPathsForSiteCreation               | String collection            | Collection of managed paths available for site creation. Read-only.                                                                                                                                            |
| deletedUserPersonalSiteRetentionPeriodInDays       | Int32                        | The number of days for preserving a deleted user's OneDrive.                                                                                                                                                   |
| excludedFileExtensionsForSyncApp                   | String collection            | Collection of file extensions not uploaded by the OneDrive sync app.                                                                                                                                           |
| idleSessionSignOut                                 | microsoft.graph.idleSessionSignOut | Specifies the idle session sign-out policies for the tenant.                                                                                               |
| imageTaggingOption                                 | microsoft.graph.imageTaggingChoice | Specifies the image tagging option for the tenant. Possible values are: `disabled`, `basic`, `enhanced`.                                   |
| isCommentingOnSitePagesEnabled                     | Boolean                      | Indicates whether comments are allowed on modern site pages in SharePoint.                                                                                                                                     |
| isFileActivityNotificationEnabled                  | Boolean                      | Indicates whether push notifications are enabled for OneDrive events.                                                                                                                                          |
| isLegacyAuthProtocolsEnabled                       | Boolean                      | Indicates whether legacy authentication protocols are enabled for the tenant.                                                                                                                                  |
| isLoopEnabled                                      | Boolean                      | Indicates whether if Fluid Framework is allowed on SharePoint sites.                                                                                                                                            |
| isMacSyncAppEnabled                                | Boolean                      | Indicates whether files can be synced using the OneDrive sync app for Mac.                                                                                                                                     |
| isRequireAcceptingUserToMatchInvitedUserEnabled    | Boolean                      | Indicates whether guests must sign in using the same account to which sharing invitations are sent.                                                                                                            |
| isResharingByExternalUsersEnabled                  | Boolean                      | Indicates whether guests are allowed to reshare files, folders, and sites they don't own.                                                                                                                      |
| isSharePointMobileNotificationEnabled              | Boolean                      | Indicates whether mobile push notifications are enabled for SharePoint.                                                                                                                                        |
| isSharePointNewsfeedEnabled                        | Boolean                      | Indicates whether the newsfeed is allowed on the modern site pages in SharePoint.                                                                                                                              |
| isSiteCreationEnabled                              | Boolean                      | Indicates whether users are allowed to create sites.                                                                                                                                                           |
| isSiteCreationUIEnabled                            | Boolean                      | Indicates whether the UI commands for creating sites are shown.                                                                                                                                                |
| isSitePagesCreationEnabled                         | Boolean                      | Indicates whether creating new modern pages is allowed on SharePoint sites.                                                                                                                                    |
| isSitesStorageLimitAutomatic                       | Boolean                      | Indicates whether site storage space is automatically managed or if specific storage limits are set per site.                                                                                                  |
| isSyncButtonHiddenOnPersonalSite                   | Boolean                      | Indicates whether the sync button in OneDrive is hidden.                                                                                                                                                       |
| isUnmanagedSyncAppForTenantRestricted              | Boolean                      | Indicates whether users are allowed to sync files only on PCs joined to specific domains.                                                                                                                      |
| personalSiteDefaultStorageLimitInMB                | Int64                        | The default OneDrive storage limit for all new and existing users who are assigned a qualifying license. Measured in megabytes (MB).                                                                           |
| sharingAllowedDomainList                           | String collection            | Collection of email domains that are allowed for sharing outside the organization.                                                                                                                             |
| sharingBlockedDomainList                           | String collection            | Collection of email domains that are blocked for sharing outside the organization.                                                                                                                             |
| sharingCapability                                  | microsoft.graph.sharingCapabilities          | Sharing capability for the tenant. Possible values are: `disabled`, `externalUserSharingOnly`, `externalUserAndGuestSharing`, `existingExternalUserSharingOnly`.    |
| sharingDomainRestrictionMode                       | microsoft.graph.sharingDomainRestrictionMode | Specifies the external sharing mode for domains. Possible values are: `none`, `allowList`, `blockList`.                                                    |
| siteCreationDefaultManagedPath                     | String                       | The value of the team site managed path. This is the path under which new team sites will be created.                                                                                                          |
| siteCreationDefaultStorageLimitInMB                | Int32                        | The default storage quota for a new site upon creation. Measured in megabytes (MB).                                                                                                                            |
| tenantDefaultTimezone                              | String                       | The default timezone of a tenant for newly created sites. For a list of possible values, see SPRegionalSettings.TimeZones property.                                      |
