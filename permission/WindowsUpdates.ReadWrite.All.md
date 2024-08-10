# WindowsUpdates.ReadWrite.All

> Allows the app to read and write all Windows update deployment settings for the organization on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /admin/windows/updates/deploymentAudiences/{deploymentAudienceId}](https://docs.microsoft.com/graph/api/windowsupdates-deploymentaudience-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/deployments/{deploymentId}](https://docs.microsoft.com/graph/api/windowsupdates-deployment-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/resourceConnections/{operationalInsightsConnectionId}](https://docs.microsoft.com/graph/api/windowsupdates-operationalinsightsconnection-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/resourceConnections/{resourceConnectionId}](https://docs.microsoft.com/graph/api/windowsupdates-resourceconnection-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/updatableAssets/{azureADDeviceId}](https://docs.microsoft.com/graph/api/windowsupdates-azureaddevice-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/updatableAssets/{updatableAssetGroupId}](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/updatableAssets/{updatableAssetId}](https://docs.microsoft.com/graph/api/windowsupdates-updatableasset-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/updatePolicies/{updatePolicyId}](https://docs.microsoft.com/graph/api/windowsupdates-updatepolicy-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /admin/windows/updates/updatePolicies/{updatePolicyId}/complianceChanges/{complianceChangeId}](https://docs.microsoft.com/graph/api/windowsupdates-compliancechange-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin//windows/updates/deploymentAudiences/{deploymentAudienceId}/exclusions](https://docs.microsoft.com/graph/api/windowsupdates-deploymentaudience-list-exclusions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin//windows/updates/deploymentAudiences/{deploymentAudienceId}/members](https://docs.microsoft.com/graph/api/windowsupdates-deploymentaudience-list-members?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/catalog/entries](https://docs.microsoft.com/graph/api/windowsupdates-catalog-list-entries?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/deploymentAudiences](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-deploymentaudiences?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/deploymentAudiences/{deploymentAudienceId}](https://docs.microsoft.com/graph/api/windowsupdates-deploymentaudience-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/deployments](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-deployments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/deployments/{deploymentId}](https://docs.microsoft.com/graph/api/windowsupdates-deployment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/products/{id}/GetKnownIssuesByTimeRange(daysInPast={daysInPast},includeAllActive={includeAllActive})](https://docs.microsoft.com/graph/api/windowsupdates-product-getknownissuesbytimerange?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/products/FindByCatalogId(catalogID='catalogID')](https://docs.microsoft.com/graph/api/windowsupdates-product-findbycatalogid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/products/FindByKbNumber(kbNumber={kbNumber})](https://docs.microsoft.com/graph/api/windowsupdates-product-findbykbnumber?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/resourceConnections](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-resourceconnections?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/resourceConnections/{operationalInsightsConnectionId}](https://docs.microsoft.com/graph/api/windowsupdates-operationalinsightsconnection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/resourceConnections/{resourceConnectionId}](https://docs.microsoft.com/graph/api/windowsupdates-resourceconnection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/resourceConnections/microsoft.graph.windowsUpdates.operationalInsightsConnection](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-resourceconnections-operationalinsightsconnection?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-updatableassets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets/{azureADDeviceId}](https://docs.microsoft.com/graph/api/windowsupdates-azureaddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets/{updatableAssetGroupId}](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets/{updatableAssetGroupId}/microsoft.graph.windowsUpdates.updatableAssetGroup/members](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-list-members?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets/{updatableAssetId}](https://docs.microsoft.com/graph/api/windowsupdates-updatableasset-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets/microsoft.graph.windowsUpdates.azureADDevice](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-updatableassets-azureaddevice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatableAssets/microsoft.graph.windowsUpdates.updatableAssetGroup](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-updatableassets-updatableassetgroup?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatePolicies](https://docs.microsoft.com/graph/api/adminwindowsupdates-list-updatepolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatePolicies/{updatePolicyId}](https://docs.microsoft.com/graph/api/windowsupdates-updatepolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatePolicies/{updatePolicyId}/complianceChanges](https://docs.microsoft.com/graph/api/windowsupdates-updatepolicy-list-compliancechanges?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatePolicies/{updatePolicyId}/complianceChanges/{complianceChangeId}](https://docs.microsoft.com/graph/api/windowsupdates-contentapproval-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /admin/windows/updates/updatePolicies/{updatePolicyId}/complianceChanges/microsoft.graph.windowsUpdates.contentApproval](https://docs.microsoft.com/graph/api/windowsupdates-updatepolicy-list-compliancechanges-contentapproval?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/windows/updates/deployments/{deploymentId}](https://docs.microsoft.com/graph/api/windowsupdates-deployment-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/windows/updates/updatePolicies/{updatePolicyId}](https://docs.microsoft.com/graph/api/windowsupdates-updatepolicy-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /admin/windows/updates/updatePolicies/{updatePolicyId}/complianceChanges/{complianceChangeId}](https://docs.microsoft.com/graph/api/windowsupdates-compliancechange-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/deploymentAudiences](https://docs.microsoft.com/graph/api/adminwindowsupdates-post-deploymentaudiences?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/deploymentAudiences/{deploymentAudienceId}/updateAudience](https://docs.microsoft.com/graph/api/windowsupdates-deploymentaudience-updateaudience?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/deployments](https://docs.microsoft.com/graph/api/adminwindowsupdates-post-deployments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/deployments/{deploymentId}/audience/updateAudienceById](https://docs.microsoft.com/graph/api/windowsupdates-deploymentaudience-updateaudiencebyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/resourceConnections](https://docs.microsoft.com/graph/api/adminwindowsupdates-post-resourceconnections-operationalinsightsconnection?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets](https://docs.microsoft.com/graph/api/adminwindowsupdates-post-updatableassets-updatableassetgroup?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/{updatableAssetGroupId}/addMembers](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-addmembers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/{updatableAssetGroupId}/addMembersById](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-addmembersbyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/{updatableAssetGroupId}/removeMembers](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-removemembers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/{updatableAssetGroupId}/removeMembersById](https://docs.microsoft.com/graph/api/windowsupdates-updatableassetgroup-removemembersbyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/enrollAssets](https://docs.microsoft.com/graph/api/windowsupdates-updatableasset-enrollassets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/enrollAssetsById](https://docs.microsoft.com/graph/api/windowsupdates-updatableasset-enrollassetsbyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/unenrollAssets](https://docs.microsoft.com/graph/api/windowsupdates-updatableasset-unenrollassets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatableAssets/unenrollAssetsById](https://docs.microsoft.com/graph/api/windowsupdates-updatableasset-unenrollassetsbyid?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatePolicies](https://docs.microsoft.com/graph/api/adminwindowsupdates-post-updatepolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /admin/windows/updates/updatePolicies/{updatePolicyId}/complianceChanges](https://docs.microsoft.com/graph/api/windowsupdates-updatepolicy-post-compliancechanges-contentapproval?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|11776c0c-6138-4db3-a668-ee621bea2555|
|**Consent Type**|Admin|
|**Display String**|Read and write all Windows update deployment settings|
|**Description**|Allows the app to read and write all Windows update deployment settings for the organization on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7dd1be58-6e76-4401-bf8d-31d1e8180d5b|
|**Display String**|Read and write all Windows update deployment settings|
|**Description**|Allows the app to read and write all Windows update deployment settings for the organization without a signed-in user.|
## Resources
### [azureADDevice ](https://docs.microsoft.com/graph/api/resources/windowsupdates-azureaddevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|enrollments|microsoft.graph.windowsUpdates.updatableAssetEnrollment collection|Specifies areas of the service in which the device is enrolled. Read-only. Returned by default.|
|errors|microsoft.graph.windowsUpdates.updatableAssetError collection|Specifies any errors that prevent the device from being enrolled in update management or receving deployed content. Read-only. Returned by default.|
|id|String|An identifier for the device. Key. Not nullable. Read-only. Returned by default. Inherited from updatableAsset|
### [catalog ](https://docs.microsoft.com/graph/api/resources/windowsupdates-catalog?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|An identifier for the catalog. Read-only.|
### [catalogContent ](https://docs.microsoft.com/graph/api/resources/windowsupdates-catalogcontent?view=graph-rest-1.0&tabs=http)

### [catalogEntry ](https://docs.microsoft.com/graph/api/resources/windowsupdates-catalogentry?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deployableUntilDateTime|DateTimeOffset|The date on which the content is no longer available to deploy using the service. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|The display name of the content. Read-only.|
|id|String|The unique identifier for the catalog entry. Read-only.|
|releaseDateTime|DateTimeOffset|The release date for the content. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
### [complianceChange ](https://docs.microsoft.com/graph/api/resources/windowsupdates-compliancechange?view=graph-rest-1.0&tabs=http)
| Property        | Type           | Description                                                                                                                           |
|:----------------|:---------------|:--------------------------------------------------------------------------------------------------------------------------------------|
| createdDateTime | DateTimeOffset | The date and time when a compliance change was created.                                                                               |
| id              | String         | The unique identifier for the compliance change. Returned by default. Not nullable. Read-only.                                        |
| isRevoked       | Boolean        | `True` indicates that a compliance change is revoked, preventing further application. Revoking a compliance change is a final action. |
| revokedDateTime | DateTimeOffset | The date and time when the compliance change was revoked.                                                                             |
### [complianceChangeRule ](https://docs.microsoft.com/graph/api/resources/windowsupdates-compliancechangerule?view=graph-rest-1.0&tabs=http)
| Property              | Type           | Description                                         |
|:----------------------|:---------------|:----------------------------------------------------|
| createdDateTime       | DateTimeOffset | The date and time when the rule was created.        |
| lastEvaluatedDateTime | DateTimeOffset | The date and time when the rule was last evaluated. |
| lastModifiedDateTime  | DateTimeOffset | The date and time when the rule was last modified.  |
### [contentApproval ](https://docs.microsoft.com/graph/api/resources/windowsupdates-contentapproval?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|microsoft.graph.windowsUpdates.deployableContent|Specifies what content to deploy. Deployable content should be provided as one of the following derived types: microsoft.graph.windowsUpdates.catalogContent.|
|createdDateTime|DateTimeOffset|The date and time when a compliance change was created. Inherited from microsoft.graph.windowsUpdates.complianceChange.|
|deploymentSettings|microsoft.graph.windowsUpdates.deploymentSettings|Settings for governing how to deploy **content**.|
|id|String|The unique identifier for the compliance change. Returned by default. Not nullable. Read-only. Inherited from microsoft.graph.windowsUpdates.complianceChange.|
|isRevoked|Boolean|`True` indicates that a compliance change is revoked, preventing further application. Revoking a compliance change is a final action. Inherited from microsoft.graph.windowsUpdates.complianceChange.|
|revokedDateTime|DateTimeOffset|The date and time when the compliance change was revoked. Inherited from microsoft.graph.windowsUpdates.complianceChange.|
### [deployableContent ](https://docs.microsoft.com/graph/api/resources/windowsupdates-deployablecontent?view=graph-rest-1.0&tabs=http)

### [deployment ](https://docs.microsoft.com/graph/api/resources/windowsupdates-deployment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|microsoft.graph.windowsUpdates.deployableContent|Specifies what content to deploy. Cannot be changed. Returned by default.|
|createdDateTime|DateTimeOffset|The date and time the deployment was created. Returned by default. Read-only.|
|id|String|The unique identifier for the deployment. Returned by default. Key. Not nullable. Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time the deployment was last modified. Returned by default. Read-only.|
|settings|microsoft.graph.windowsUpdates.deploymentSettings|Settings specified on the specific deployment governing how to deploy **content**. Returned by default.|
|state|microsoft.graph.windowsUpdates.deploymentState|Execution status of the deployment. Returned by default.|
### [deploymentAudience ](https://docs.microsoft.com/graph/api/resources/windowsupdates-deploymentaudience?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the deployment audience. Returned by default. Not nullable. Read-only.|
### [deploymentSettings ](https://docs.microsoft.com/graph/api/resources/windowsupdates-deploymentsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|contentApplicability|microsoft.graph.windowsUpdates.contentApplicabilitySettings|Settings for governing whether content is applicable to a device.|
|expedite|microsoft.graph.windowsUpdates.expediteSettings|Settings for governing whether updates should be expedited.|
|monitoring|microsoft.graph.windowsUpdates.monitoringSettings|Settings for governing conditions to monitor and automated actions to take.|
|schedule|microsoft.graph.windowsUpdates.scheduleSettings|Settings for governing how and when the content is rolled out.|
|userExperience|microsoft.graph.windowsUpdates.userExperienceSettings|Settings for governing end user update experience.|
### [deploymentState ](https://docs.microsoft.com/graph/api/resources/windowsupdates-deploymentstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|effectiveValue|microsoft.graph.windowsUpdates.deploymentStateValue|Specifies the state of the deployment. Supports a subset of the values for **deploymentStateValue**. Possible values are: `scheduled`, `offering`, `paused`, `unknownFutureValue`. Read-only.|
|reasons|microsoft.graph.windowsUpdates.deploymentStateReason collection|Specifies the reasons the deployment has its state value. Read-only.|
|requestedValue|microsoft.graph.windowsUpdates.requestedDeploymentStateValue|Specifies the requested state of the deployment. Supports a subset of the values for **r
### [featureUpdateCatalogEntry ](https://docs.microsoft.com/graph/api/resources/windowsupdates-featureupdatecatalogentry?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|buildNumber|String|The build number of the feature update. Read-only.|
|deployableUntilDateTime|DateTimeOffset|The date on which the content is no longer available for deployment using the service. Read-only. Inherited from softwareUpdateCatalogEntry.|
|displayName|String|The display name of the content. Read-only. Inherited from softwareUpdateCatalogEntry.|
|id|String|The unique identifier for the catalog entry. Read-only. Inherited from softwareUpdateCatalogEntry.|
|releaseDateTime|DateTimeOffset|The release date for the content. Read-only. Inherited from softwareUpdateCatalogEntry.|
|version|String|The version of the feature update. Read-only.|
### [knownIssue ](https://docs.microsoft.com/graph/api/resources/windowsupdates-knownissue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of the particular known issue.|
|id|String|The unique identifier for the entry. Read-only.|
|lastUpdatedDateTime|DateTimeOffset|The date and time when the known issue was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|resolvedDateTime|DateTimeOffset| The date and time when the known issue was resolved or mitigated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|startDateTime|DateTimeOffset|The date and time when the known issue was first reported. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|status|microsoft.graph.windowsUpdates.windowsReleaseHealthStatus|The status of the known issue.|
|title|String|The title of the known issue.|
|webViewUrl|String|The URL to the known issue in the Windows Release Health dashboard on Microsoft 365 admin center.|
### [operationalInsightsConnection ](https://docs.microsoft.com/graph/api/resources/windowsupdates-operationalinsightsconnection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|azureResourceGroupName|String|The name of the Azure resource group that contains the Log Analytics workspace.|
|azureSubscriptionId|String|The Azure subscription ID that contains the Log Analytics workspace.|
|id|String|An identifier for the resource connection. Key. Not nullable. Read-only. Returned by default.|
|state|microsoft.graph.windowsUpdates.resourceConnectionState|The state of the connection. The possible values are: `connected`, `notAuthorized`, `notFound`, `unknownFutureValue`.|
|workspaceName|String|The name of the Log Analytics workspace.|
### [product ](https://docs.microsoft.com/graph/api/resources/windowsupdates-product?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|friendlyNames|String collection|The friendly names of the product. For example, `Version 22H2 (OS build 22621)`. Read-only.|
|groupName|String|The name of the product group. For example, `Windows 11`. Read-only.|
|id|String|The unique identifier for the product. Read-only.|
|name|String|The name of the product. For example, `Windows 11, version 22H2`. Read-only.|
### [qualityUpdateCatalogEntry ](https://docs.microsoft.com/graph/api/resources/windowsupdates-qualityupdatecatalogentry?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|catalogName|String|The catalog name of the content. Read-only.|
|cveSeverityInformation|microsoft.graph.windowsUpdates.qualityUpdateCveSeverityInformation|Severity information of the Common Vulnerabilities and Exposures associated with the content.|
|deployableUntilDateTime|DateTimeOffset|The date on which the content is no longer available for deployment using the service. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from softwareUpdateCatalogEntry.|
|displayName|String|The display name of the content. Read-only. Inherited from softwareUpdateCatalogEntry.|
|id|String|The unique identifier for the catalog entry. Read-only. Inherited from softwareUpdateCatalogEntry.|
|isExpeditable|Boolean|Indicates whether the content can be deployed as an expedited quality update. Read-only.|
|qualityUpdateCadence|microsoft.graph.windowsUpdates.qualityUpdateCadence|The publishing cadence of the quality update. Possible values are: `monthly`, `outOfBand`, `unknownFutureValue`. Read-only.|
|qualityUpdateClassification|microsoft.graph.windowsUpdates.qualityUpdateClassification|The classification on the quality update. Possible values are: `all`, `security`, `nonSecurity`, `unknownFutureValue`. Read-only.|
|releaseDateTime|DateTimeOffset|The release date of the content. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Inherited from softwareUpdateCatalogEntry.|
|shortName|String|The short name of the content. Read-only.|
### [resourceConnection ](https://docs.microsoft.com/graph/api/resources/windowsupdates-resourceconnection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|An identifier for the resource connection. Key. Not nullable. Read-only. Returned by default.|
|state|microsoft.graph.windowsUpdates.resourceConnectionState|The state of the connection. The possible values are: `connected`, `notAuthorized`, `notFound`, `unknownFutureValue`.|
### [updatableAsset ](https://docs.microsoft.com/graph/api/resources/windowsupdates-updatableasset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|An identifier for the asset. Key. Not nullable. Read-only. Returned by default.|
### [updatableAssetGroup ](https://docs.microsoft.com/graph/api/resources/windowsupdates-updatableassetgroup?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|An identifier for the group. Key. Not nullable. Read-only. Returned by default. Inherited from microsoft.graph.windowsUpdates.updatableAsset.|
### [updatePolicy ](https://docs.microsoft.com/graph/api/resources/windowsupdates-updatepolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|complianceChangeRules|microsoft.graph.windowsUpdates.complianceChangeRule collection|Rules for governing the automatic creation of compliance changes.|
|createdDateTime|DateTimeOffset|The date and time when the update policy was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|deploymentSettings|microsoft.graph.windowsUpdates.deploymentSettings|Settings for governing how to deploy **content**.|
|id|String|Unique identifier for the update policy.|
