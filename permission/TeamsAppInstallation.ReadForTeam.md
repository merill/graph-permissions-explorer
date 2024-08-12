# TeamsAppInstallation.ReadForTeam

> Allows the app to read the Teams apps that are installed in teams the signed-in user can access. Does not give the ability to read application-specific settings.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /teams/{id}/installedApps/{id}](https://docs.microsoft.com/graph/api/team-get-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/installedApps](https://docs.microsoft.com/graph/api/team-list-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/permissionGrants](https://docs.microsoft.com/graph/api/team-list-permissiongrants?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5248dcb1-f83b-4ec3-9f4d-a4428a961a72|
|**Consent Type**|Admin|
|**Display String**|Read installed Teams apps in teams|
|**Description**|Allows the app to read the Teams apps that are installed in teams the signed-in user can access. Does not give the ability to read application-specific settings.|
## Resources
### [resourceSpecificPermissionGrant ](https://docs.microsoft.com/graph/api/resources/resourcespecificpermissiongrant?view=graph-rest-1.0&tabs=http)
| Property        | Type          | Description                                                                           |
| :-------------- | :------------ | :------------------------------------------------------------------------------------ |
| clientId        | string        | ID of the Microsoft Entra app that has been granted access. Read-only.                            |
| clientAppId     | string        | ID of the service principal of the Microsoft Entra app that has been granted access. Read-only.   |
| deletedDateTime | dateTimeOffset| Not used.                                                                             |
| id              | string        | The unique identifier of the resource-specific permission grant. Read-only.           |
| resourceAppId   | string        | ID of the Microsoft Entra app that is hosting the resource. Read-only.                        |
| permissionType  | string        | The type of permission. Possible values are: `Application`, `Delegated`. Read-only. |
| permission      | string        | The name of the resource-specific permission. Read-only.                                                |
### [team ](https://docs.microsoft.com/graph/api/resources/team?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| id | string | The unique identifier of the team. The group has the same ID as the team. This property is read-only, and is inherited from the base entity type. |
|classification|string| An optional label. Typically describes the data or business sensitivity of the team. Must match one of a pre-configured set in the tenant's directory. |
|classSettings|teamClassSettings |Configure settings of a class. Available only when the team represents a class.|
|createdDateTime|dateTimeOffset|Timestamp at which the team was created.|
|description|string| An optional description for the team. Maximum length: 1024 characters. |
|displayName|string| The name of the team. |
|funSettings|teamFunSettings |Settings to configure use of Giphy, memes, and stickers in the team.|
|guestSettings|teamGuestSettings |Settings to configure whether guests can create, update, or delete channels in the team.|
|internalId | string | A unique ID for the team that has been used in a few places such as the audit log/Office 365 Management Activity API. |
|isArchived|Boolean|Whether this team is in read-only mode. |
|memberSettings|teamMemberSettings |Settings to configure whether members can perform certain actions, for example, create channels and add bots, in the team.|
|messagingSettings|teamMessagingSettings |Settings to configure messaging and mentions in the team.|
|specialization|teamSpecialization| Optional. Indicates whether the team is intended for a particular use case.  Each team specialization has access to unique behaviors and experiences targeted to its use case. |
|summary|teamSummary| Contains summary information about the team, including number of owners, members, and guests. |
|tenantId |string | The ID of the Microsoft Entra tenant. |
|visibility|teamVisibilityType| The visibility of the group and team. Defaults to Public. |
|webUrl|string (readonly) | A hyperlink that will go to the team in the Microsoft Teams client. This is the URL that you get when you right-click a team in the Microsoft Teams client and select **G
### [teamsAppInstallation ](https://docs.microsoft.com/graph/api/resources/teamsappinstallation?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
|consentedPermissionSet|teamsAppPermissionSet|The set of resource-specific permissions consented to while installing or upgrading the teamsApp.|
| id                  | string   | A unique ID (not the Teams app ID). |
### [teamworkBot ](https://docs.microsoft.com/graph/api/resources/teamworkbot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the bot associated with the specific teamsAppDefinition. This value is usually a GUID.|