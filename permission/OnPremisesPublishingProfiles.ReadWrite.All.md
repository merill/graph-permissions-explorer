# OnPremisesPublishingProfiles.ReadWrite.All

> Allows the app to manage hybrid identity service configuration by creating, viewing, updating and deleting on-premises published resources, on-premises agents and agent groups, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /onPremisesPublishingProfiles/{profile-id}/publishedResources/{resource-id}/agentGroups/{agentGroup-id}/$ref](https://docs.microsoft.com/graph/api/publishedresource-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/publishedResources](https://docs.microsoft.com/graph/api/publishedresource-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/publishedResources/{resource-id}](https://docs.microsoft.com/graph/api/publishedresource-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /onPremisesPublishingProfiles/{profile-id}/publishedResources/{resource-id}](https://docs.microsoft.com/graph/api/publishedresource-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /onPremisesPublishingProfiles/{profile-id}/publishedResources](https://docs.microsoft.com/graph/api/publishedresource-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /onPremisesPublishingProfiles/{profile-id}/publishedResources/{resource-id}/agentGroups/$ref](https://docs.microsoft.com/graph/api/publishedresource-post-agentgroups?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8c4d5184-71c2-4bf8-bb9d-bc3378c9ad42|
|**Consent Type**|Admin|
|**Display String**|Manage on-premises published resources|
|**Description**|Allows the app to manage hybrid identity service configuration by creating, viewing, updating and deleting on-premises published resources, on-premises agents and agent groups, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|0b57845e-aa49-4e6f-8109-ce654fffa618|
|**Display String**|Manage on-premises published resources|
|**Description**|Allows the app to create, view, update and delete on-premises published resources, on-premises agents and agent groups, as part of a hybrid identity configuration, without a signed in user.|
## Resources
### [onPremisesAgentGroup ](https://docs.microsoft.com/graph/api/resources/onpremisesagentgroup?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|displayName|String|Display name of the **onPremisesAgentGroup**.|
|id|String| The object ID of the **onPremisesAgentGroup**. Read-only.|
|isDefault|Boolean|Indicates if the **onPremisesAgentGroup** is the default agent group. Only a single agent group can be the default **onPremisesAgentGroup** and is set by the system.|
|publishingType|String| Possible values are: `applicationProxy`, `exchangeOnline`, `authentication`, `provisioning`, `adAdministration`.|
### [publishedResource ](https://docs.microsoft.com/graph/api/resources/publishedresource?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|displayName|String| Display Name of the publishedResource.|
|id|String| The object id of the publishedResource. Read-only.|
|publishingType|String| Possible values are: `applicationProxy`, `exchangeOnline`, `authentication`, `provisioning`, `adAdministration`.|
|resourceName|String|Name of the publishedResource.|
