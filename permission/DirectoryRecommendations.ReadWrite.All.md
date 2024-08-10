# DirectoryRecommendations.ReadWrite.All

> Allows the app to read and update Azure AD recommendations, on behalf of the signed-in user. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /directory/recommendations](https://docs.microsoft.com/graph/api/directory-list-recommendation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/recommendations/{recommendationId}](https://docs.microsoft.com/graph/api/recommendation-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/recommendations/{recommendationId}/impactedResources](https://docs.microsoft.com/graph/api/recommendation-list-impactedresources?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/recommendations/{recommendationId}/impactedResources/{impactedResourceId}](https://docs.microsoft.com/graph/api/impactedresource-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/recommendations/tenantSecureScores](https://docs.microsoft.com/graph/api/recommendation-tenantsecurescores?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/complete](https://docs.microsoft.com/graph/api/recommendation-complete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/dismiss](https://docs.microsoft.com/graph/api/recommendation-dismiss?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/impactedResources/{impactedResourceId}/complete](https://docs.microsoft.com/graph/api/impactedresource-complete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/impactedResources/{impactedResourceId}/dismiss](https://docs.microsoft.com/graph/api/impactedresource-dismiss?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/impactedResources/{impactedResourceId}/postpone](https://docs.microsoft.com/graph/api/impactedresource-postpone?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/impactedResources/{impactedResourceId}/reactivate](https://docs.microsoft.com/graph/api/impactedresource-reactivate?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/postpone](https://docs.microsoft.com/graph/api/recommendation-postpone?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /directory/recommendations/{recommendationId}/reactivate](https://docs.microsoft.com/graph/api/recommendation-reactivate?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f37235e8-90a0-4189-93e2-e55b53867ccd|
|**Consent Type**|Admin|
|**Display String**|Read and update Azure AD recommendations|
|**Description**|Allows the app to read and update Azure AD recommendations, on behalf of the signed-in user. |
## Application Permission
|||
|-|-|
|**Id**|0e9eea12-4f01-45f6-9b8d-3ea4c8144158|
|**Display String**|Read and update all Azure AD recommendations|
|**Description**|Allows the app to read and update all Azure AD recommendations, without a signed-in user. |
## Resources
### [impactedResource ](https://docs.microsoft.com/graph/api/resources/impactedresource?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|addedDateTime|DateTimeOffset|The date and time when the impactedResource object was initially associated with the recommendation.|
|additionalDetails|keyValue collection|Additional information unique to the impactedResource to help contextualize the recommendation.|
|apiUrl|String|The URL link to the corresponding Microsoft Entra resource.|
|displayName|String|Friendly name of the Microsoft Entra resource.|
|id|String|A unique identifier of the impacted Microsoft Entra resource.|
|lastModifiedBy|String|Name of the user or service that last updated the **status**.|
|lastModifiedDateTime|String|The date and time when the **status** was last updated.|
|owner|String|The user responsible for maintaining the resource.|
|portalUrl|String|The URL link to the corresponding Microsoft Entra admin center page of the resource.|
|postponeUntilDateTime|DateTimeOffset|The future date and time when the **status** of a postponed impactedResource will be `active` again.|
|rank|Int32|Indicates the importance of the resource. A resource with a rank equal to 1 is of the highest importance.|
|recommendationId|String|The unique identifier of the recommendation that the resource is associated with.|
|resourceType|String|Indicates the type of Microsoft Entra resource. Examples include `user`, `application`.|
|status|recommendationStatus|Indicates whether a resource needs to be addressed. The possible values are: `active`, `completedBySystem`, `completedByUser`, `dismissed`, `postponed`, `unknownFutureValue`. By default, a recommendation's **status** is set to `active` when the recommendation is first generated. **Status** is set to `completedBySystem` when our service detects that a resource which was once active no longer applies.|
|subjectId|String|The related unique identifier, depending on the **r
### [recommendation ](https://docs.microsoft.com/graph/api/resources/recommendation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionSteps|actionStep collection|List of actions to take to complete a recommendation. Inherited from recommendationBase.|
|benefits|String|An explanation of why completing the recommendation will benefit you. Corresponds to the *Value* section of a recommendation shown in the Microsoft Entra admin center. Inherited from recommendationBase.|
|category|recommendationCategory|Indicates the category of intelligent guidance that the recommendation falls under. The possible values are: `identityBestPractice`, `identitySecureScore`, `unknownFutureValue`. Inherited from recommendationBase. <br><br> Supports `$filter`(`eq`).|
|createdDateTime|DateTimeOffset|The date and time when the recommendation was detected as applicable to your directory. Inherited from recommendationBase.|
|currentScore|Double|The number of points the tenant has attained. Only applies to recommendations with **category** set to `identitySecureScore`. Inherited from recommendationBase.|
|displayName|String|The title of the recommendation. Inherited from recommendationBase.|
|featureAreas|recommendationFeatureAreas collection|The directory feature that the recommendation is related to. Inherited from recommendationBase. <br><br> Supports `$filter`(`eq`).|
|id|String|The unique identifier for the recommendation object generated for your tenant. This is a concatenation of your tenant ID and a Microsoft Entra ID-assigned nickname for the recommendation. For example, `7918d4b5-0442-4a97-be2d-36f9f9962ece_Microsoft.Identity.IAM.Insights.ThirdPartyApps`. Inherited from recommendationBase.|
|impactStartDateTime|DateTimeOffset|The future date and time when a recommendation should be completed. Inherited from recommendationBase.|
|impactType|String|    Indicates the scope of impact of a recommendation. `Tenant level` indicates that the recommendation impacts the whole tenant. Other possible values include `users`, `applications`. Inherited from recommendationBase.|
|insights|String|Describes why a recommendation uniquely applies to your directory. Corresponds to the *Description* section of a recommendation shown in the Microsoft Entra admin center. Inherited from recommendationBase.|
|lastCheckedDateTime|DateTimeOffset|The most recent date and time a recommendation was deemed applicable to your directory. Inherited from recommendationBase.|
|lastModifiedBy|String|Name of the user who last updated the **status** of the recommendation. Inherited from recommendationBase.|
|lastModifiedDateTime|DateTimeOffset|    The date and time the **status** of a recommendation was last updated. Inherited from recommendationBase.|
|maxScore|Double|The maximum number of points attainable. Only applies to recommendations with **category** set to `identitySecureScore`. Inherited from recommendationBase.|
|postponeUntilDateTime|DateTimeOffset|The future date and time when the **status** of a postponed recommendation will be `active` again. Inherited from recommendationBase.|
|priority|recommendationPriority|Indicates the time sensitivity for a recommendation to be completed. Microsoft auto assigns this value. The possible values are: `low`, `medium`, `high`. Inherited from recommendationBase. Read-only. <br><br> Supports `$filter`(`eq`).|
|recommendationType|recommendationType|Friendly shortname to identify the recommendation. The possible values are: `adfsAppsMigration`, `enableDesktopSSO`, `enablePHS`, `enableProvisioning`, `switchFromPerUserMFA`, `tenantMFA`, `thirdPartyApps`, `turnOffPerUserMFA`, `useAuthenticatorApp`, `useMyApps`, `staleApps`, `staleAppCreds`, `applicationCredentialExpiry`, `servicePrincipalKeyExpiry`, `adminMFAV2`, `blockLegacyAuthentication`, `integratedApps`, `mfaRegistrationV2`, `pwagePolicyNew`, `passwordHashSync`, `oneAdmin`, `roleOverlap`, `selfServicePasswordReset`, `signinRiskPolicy`, `userRiskPolicy`, `verifyAppPublisher`, `privateLinkForAAD`, `appRoleAssignmentsGroups`, `appRoleAssignmentsUsers`, `managedIdentity`, `overprivilegedApps`, `unknownFutureValue`, `longLivedCredentials`, `aadConnectDeprecated`, `adalToMsalMigration`, `ownerlessApps`, `inactiveGuests`, `aadGraphDeprecationApplication`, `aadGraphDeprecationServicePrincipal`, `mfaServerDeprecation`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `longLivedCredentials` , `aadConnectDeprecated` , `adalToMsalMigration` , `ownerlessApps` , `inactiveGuests` , `aadGraphDeprecationApplication` , `aadGraphDeprecationServicePrincipal` , `mfaServerDeprecation`. Inherited from recommendationBase. <br><br> Currently, only a limited number are available. For more information, see Types of recommendations. Supports `$filter`(`eq`).|
|releaseType|releaseType|The current release type of the recommendation. The possible values are: `preview`, `generallyAvailable`, `unknownFutureValue`. Inherited from recommendationBase. |
|remediationImpact|String|Description of the impact on users of the remediation. Only applies to recommendations with **category** set to `identitySecureScore`. Inherited from recommendationBase.|
|status|recommendationStatus|    Indicates the status of the recommendation based on user or system action. The possible values are: `active`, `completedBySystem`, `completedByUser`, `dismissed`, `postponed`, `unknownFutureValue`. By default, a recommendation's **s
### [secureScore ](https://docs.microsoft.com/graph/api/resources/securescore?view=graph-rest-1.0&tabs=http)
|Property |Type |Description |
|:--|:--|:--|
|	activeUserCount	|	Int32	|	Active user count of the given tenant.	|
|	averageComparativeScores |	averageComparativeScore collection	|Average score by different scopes (for example, average by industry, average by seating) and control category (Identity, Data, Device, Apps, Infrastructure) within the scope.	|
|	azureTenantId	|	String	|	GUID string for tenant ID.	|
|	controlScores |	controlScore collection	|	Contains tenant scores for a set of controls.	|
|	createdDateTime	|	DateTimeOffset	|	When the report was created.  |
|	currentScore	|	Double	|	Tenant current attained score on specified date.	|
|	enabledServices |	String collection	|	Microsoft-provided services for the tenant (for example, Exchange online, Skype, Sharepoint).	|
|id |String|Provider-generated GUID/unique identifier. Read-only. Required.|
|	licensedUserCount	|	Int32	|	Licensed user count of the given tenant.	|
|	maxScore |	Double	|	Tenant maximum possible score on specified date.	|
|vendorInformation |securityVendorInformation|Complex type containing details about the security product/service vendor, provider, and subprovider (for example, vendor=Microsoft; provider=SecureScore). Required.|
### [tenantSecureScore ](https://docs.microsoft.com/graph/api/resources/tenantsecurescore?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createDateTime|DateTimeOffset|When this Secure Score was created.|
|tenantMaxScore|Int64|The maximum historical Secure Score for the tenant.|
|tenantScore|Int64|The Secure Score.|
