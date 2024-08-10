# Policy.Read.PermissionGrant

> Allows the app to read policies related to consent and permission grants for applications, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /policies/permissionGrantPolicies](https://docs.microsoft.com/graph/api/permissiongrantpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/permissionGrantPolicies/{id}](https://docs.microsoft.com/graph/api/permissiongrantpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/permissionGrantPolicies/{id}/excludes](https://docs.microsoft.com/graph/api/permissiongrantpolicy-list-excludes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/permissionGrantPolicies/{id}/includes](https://docs.microsoft.com/graph/api/permissiongrantpolicy-list-includes?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /policies/permissionGrantPreApprovalPolicies](https://docs.microsoft.com/graph/api/policyroot-list-permissiongrantpreapprovalpolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /policies/permissionGrantPreApprovalPolicies/{id}](https://docs.microsoft.com/graph/api/permissiongrantpreapprovalpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /servicePrincipals/{id}/permissionGrantPreApprovalPolicies](https://docs.microsoft.com/graph/api/serviceprincipal-list-permissiongrantpreapprovalpolicies?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|414de6ea-2d92-462f-b120-6e2a809a6d01|
|**Consent Type**|Admin|
|**Display String**|Read consent and permission grant policies|
|**Description**|Allows the app to read policies related to consent and permission grants for applications, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|9e640839-a198-48fb-8b9a-013fd6f6cbcd|
|**Display String**|Read consent and permission grant policies|
|**Description**|Allows the app to read policies related to consent and permission grants for applications, without a signed-in user.|
## Resources
### [permissionGrantConditionSet ](https://docs.microsoft.com/graph/api/resources/permissiongrantconditionset?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
| clientApplicationsFromVerifiedPublisherOnly | Boolean | Set to `true` to only match on client applications with a verified publisher. Set to `false` to match on any client app, even if it doesn't have a verified publisher. Default is `false`. |
| clientApplicationIds | String collection | A list of **appId** values for the client applications to match with, or a list with the single value `all` to match any client application. Default is the single value `all`. |
| clientApplicationPublisherIds | String collection | A list of Microsoft Partner Network (MPN) IDs for verified publishers of the client application, or a list with the single value `all` to match with client apps from any publisher. Default is the single value `all`. |
| clientApplicationTenantIds | String collection | A list of Microsoft Entra tenant IDs in which the client application is registered, or a list with the single value `all` to match with client apps registered in any tenant. Default is the single value `all`. |
| id | String | The unique identifier for the permission grant condition set. Key. Read-only. |
| permissionClassification | String | The permission classification for the permission being granted, or `all` to match with any permission classification (including permissions that aren't classified). Default is `all`. |
| permissions | String collection | The list of **id** values for the specific permissions to match with, or a list with the single value `all` to match with any permission. The **id** of delegated permissions can be found in the **oauth2PermissionScopes** property of the API's **servicePrincipal** object. The **id** of application permissions can be found in the **appRoles** property of the API's **servicePrincipal** object. The **id** of resource-specific application permissions can be found in the **resourceSpecificApplicationPermissions** property of the API's **servicePrincipal** object. Default is the single value `all`. |
| permissionType | permissionType | The permission type of the permission being granted. Possible values: `application` for application permissions (for example app roles), or `delegated` for delegated permissions. The value `delegatedUserConsentable` indicates delegated permissions that haven't been configured by the API publisher to require admin consent—this value may be used in built-in permission grant policies, but can't be used in custom permission grant policies. Required. |
| resourceApplication | String | The **a
### [permissionGrantPolicy ](https://docs.microsoft.com/graph/api/resources/permissiongrantpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
| displayName | String |The display name for the permission grant policy.|
| description |String| The description for the permission grant policy.|
| excludes |permissionGrantConditionSet collection| Condition sets that are *excluded* in this permission grant policy. Automatically expanded on `GET`.|
| id | String | The unique identifier for the permission grant policy. The **id** prefix `microsoft-` is reserved for built-in permission grant policies, and may not be used in a custom permission grant policy. Only letters, numbers, hyphens (`-`) and underscores (`_`) are allowed. Key. Not nullable. Required on create. Immutable. |
| includes | permissionGrantConditionSet collection| Condition sets that are *i
### [permissionGrantPreApprovalPolicy ](https://docs.microsoft.com/graph/api/resources/permissiongrantpreapprovalpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|conditions|preApprovalDetail collection|A list of condition sets describing the conditions under which the permission to grant consent for the app has been preapproved.|
|deletedDateTime|DateTimeOffset|Null. Inherited from directoryObject.|
|id|String|The unique identifier for the permission grant preapproval policy. Inherited from entity.|
### [servicePrincipal ](https://docs.microsoft.com/graph/api/resources/serviceprincipal?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
| accountEnabled |Boolean| `true` if the service principal account is enabled; otherwise, `false`. If set to `false`, then no users are able to sign in to this app, even if they're assigned to it. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| addIns | addIn collection | Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams may set the addIns property for its "FileHandler" functionality. This lets services like Microsoft 365 call the application in the context of a document the user is working on.|
|alternativeNames|String collection| Used to retrieve service principals by subscription, identify resource group and full resource IDs for managed identities. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|appDescription|String|The description exposed by the associated application.|
|appDisplayName|String|The display name exposed by the associated application.|
|appId|String|The unique identifier for the associated application (its **appId** property). Alternate key. Supports `$filter` (`eq`, `ne`, `not`, `in`, `startsWith`).|
|applicationTemplateId|String|Unique identifier of the applicationTemplate. Supports `$filter` (`eq`, `not`, `ne`). Read-only. `null` if the service principal wasn't created from an application template.|
|appOwnerOrganizationId|Guid|Contains the tenant ID where the application is registered. This is applicable only to service principals backed by applications. Supports `$filter` (`eq`, `ne`, `NOT`, `ge`, `le`).|
|appRoleAssignmentRequired|Boolean|Specifies whether users or other service principals need to be granted an app role assignment for this service principal before users can sign in or apps can get tokens. The default value is `false`. Not nullable. <br><br>Supports `$filter` (`eq`, `ne`, `NOT`). |
|appRoles|appRole collection|The roles exposed by the application that's linked to this service principal. For more information, see the **appRoles** property definition on the application entity. Not nullable. |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). Filter value is case sensitive.|
| deletedDateTime | DateTimeOffset | The date and time the service principal was deleted. Read-only. |
| description | String | Free text field to provide an internal end-user facing description of the service principal. End-user portals such MyApps displays the application description in this field. The maximum allowed size is 1,024 characters. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`.|
| disabledByMicrosoftStatus | String | Specifies whether Microsoft has disabled the registered application. Possible values are: `null` (default value), `NotDisabled`, and `DisabledDueToViolationOfServicesAgreement` (reasons include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement). <br><br> Supports `$filter` (`eq`, `ne`, `not`).  |
|displayName|String|The display name for the service principal. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
|homepage|String|Home page or landing page of the application.|
|id|String|The unique identifier for the service principal. Inherited from directoryObject. Key. Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| info | informationalUrl | Basic profile information of the acquired application such as app's marketing, support, terms of service and privacy statement URLs. The terms of service and privacy statement are surfaced to users through the user consent experience. For more info, see How to: Add Terms of service and privacy statement for registered Microsoft Entra apps. <br><br>Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values).  |
|keyCredentials|keyCredential collection|The collection of key credentials associated with the service principal. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`).            |
|loginUrl|String|Specifies the URL where the service provider redirects the user to Microsoft Entra ID to authenticate. Microsoft Entra ID uses the URL to launch the application from Microsoft 365 or the Microsoft Entra My Apps. When blank, Microsoft Entra ID performs IdP-initiated sign-on for applications configured with SAML-based single sign-on. The user launches the application from Microsoft 365, the Microsoft Entra My Apps, or the Microsoft Entra SSO URL.|
|logoutUrl|String| Specifies the URL that the Microsoft's authorization service uses to sign out a user using OpenID Connect front-channel, back-channel, or SAML sign out protocols.|
|notes|String|Free text field to capture information about the service principal, typically used for operational purposes. Maximum allowed size is 1,024 characters.|
|notificationEmailAddresses|String collection|Specifies the list of email addresses where Microsoft Entra ID sends a notification when the active certificate is near the expiration date. This is only for the certificates used to sign the SAML token issued for Microsoft Entra Gallery applications.|
|oauth2PermissionScopes|permissionScope collection|The delegated permissions exposed by the application. For more information, see the **oauth2PermissionScopes** property on the application entity's **api** property. Not nullable.|
| passwordCredentials | passwordCredential collection|The collection of password credentials associated with the application. Not nullable.|
|preferredSingleSignOnMode|string|Specifies the single sign-on mode configured for this application. Microsoft Entra ID uses the preferred single sign-on mode to launch the application from Microsoft 365 or the My Apps portal. The supported values are `password`, `saml`, `notSupported`, and `oidc`.|
|preferredTokenSigningKeyThumbprint|String|This property can be used on SAML applications (apps that have **preferredSingleSignOnMode** set to `saml`) to control which certificate is used to sign the SAML responses. For applications that aren't SAML, don't write or otherwise rely on this property.|
|replyUrls|String collection|The URLs that user tokens are sent to for sign in with the associated application, or the redirect URIs that OAuth 2.0 authorization codes and access tokens are sent to for the associated application. Not nullable. |
|resourceSpecificApplicationPermissions|resourceSpecificPermission collection|The resource-specific application permissions exposed by this application. Currently, resource-specific permissions are only supported for Teams apps accessing to specific chats and teams using Microsoft Graph. Read-only.|
|samlSingleSignOnSettings|samlSingleSignOnSettings|The collection for settings related to saml single sign-on.|
|servicePrincipalNames|String collection|Contains the list of **identifiersUris**, copied over from the associated application. Additional values can be added to hybrid applications. These values can be used to identify the permissions exposed by this app within Microsoft Entra ID. For example,<ul><li>Client apps can specify a resource URI that is based on the values of this property to acquire an access token, which is the URI returned in the "aud" claim.</li></ul><br>The any operator is required for filter expressions on multi-valued properties. Not nullable. <br><br> Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|servicePrincipalType|String|Identifies whether the service principal represents an application, a managed identity, or a legacy application. This is set by Microsoft Entra ID internally. The **servicePrincipalType** property can be set to three different values: <ul><li>__Application__ - A service principal that represents an application or service. The **appId** property identifies the associated app registration, and matches the **appId** of an application, possibly from a different tenant. If the associated app registration is missing, tokens aren't issued for the service principal.</li><li>__ManagedIdentity__ - A service principal that represents a managed identity. Service principals representing managed identities can be granted access and permissions, but can't be updated or modified directly.</li><li>__Legacy__ - A service principal that represents an app created before app registrations, or through legacy experiences. A legacy service principal can have credentials, service principal names, reply URLs, and other properties that are editable by an authorized user, but doesn't have an associated app registration. The **appId** value doesn't associate the service principal with an app registration. The service principal can only be used in the tenant where it was created.</li><li>__SocialIdp__ - For internal use. </ul>|
| signInAudience | String | Specifies the Microsoft accounts that are supported for the current application. Read-only. <br><br>Supported values are:<ul><li>`AzureADMyOrg`: Users with a Microsoft work or school account in my organization's Microsoft Entra tenant (single-tenant).</li><li>`AzureADMultipleOrgs`: Users with a Microsoft work or school account in any organization's Microsoft Entra tenant (multitenant).</li><li>`AzureADandPersonalMicrosoftAccount`: Users with a personal Microsoft account, or a work or school account in any organization's Microsoft Entra tenant.</li><li>`PersonalMicrosoftAccount`: Users with a personal Microsoft account only.</li></ul> |
|tags|String collection| Custom strings that can be used to categorize and identify the service principal. Not nullable. The value is the union of strings set here and on the associated application entity's **tags** property.<br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
| tokenEncryptionKeyId |String|Specifies the keyId of a public key from the keyCredentials collection. When configured, Microsoft Entra ID issues tokens for this application encrypted using the key specified by this property. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.|
| verifiedPublisher          | verifiedPublisher                            | Specifies the verified publisher of the application that's linked to this service principal.

