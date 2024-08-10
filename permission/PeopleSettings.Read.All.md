# PeopleSettings.Read.All

> Allows the application to read tenant-wide people settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /admin/people](https://docs.microsoft.com/graph/api/peopleadminsettings-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/people/itemInsights](https://docs.microsoft.com/graph/api/peopleadminsettings-list-iteminsights?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /admin/people/photoUpdateSettings](https://docs.microsoft.com/graph/api/photoupdatesettings-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /admin/people/profileCardProperties](https://docs.microsoft.com/graph/api/peopleadminsettings-list-profilecardproperties?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /admin/people/profileCardProperties/{id}](https://docs.microsoft.com/graph/api/profilecardproperty-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/people/pronouns](https://docs.microsoft.com/graph/api/peopleadminsettings-list-pronouns?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ec762c5f-388b-4b16-8693-ac1efbc611bc|
|**Consent Type**|Admin|
|**Display String**|Read tenant-wide people settings|
|**Description**|Allows the application to read tenant-wide people settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|ef02f2e7-e22d-4c77-8614-8f765683b86e|
|**Display String**|Read all tenant-wide people settings|
|**Description**|Allows the application to read tenant-wide people settings without a signed-in user.|
## Resources
### [insightsSettings ](https://docs.microsoft.com/graph/api/resources/insightssettings?view=graph-rest-1.0&tabs=http)
| Property   | Type|Description|
|:---------------|:--------|:----------|
|disabledForGroup|String| The ID of a Microsoft Entra group, of which the specified type of insights are disabled for its members. The default value is `null`. Optional.|
|isEnabledInOrganization|Boolean| `true` if insights of the specified type are enabled for the organization; `false` if insights of the specified type are disabled for all users without exceptions. The default value is `true`. Optional.|
### [peopleAdminSettings ](https://docs.microsoft.com/graph/api/resources/peopleadminsettings?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                                                                                     |
|:---------|:-------|:------------------------------------------------------------------------------------------------|
| id       | String | The unique identifier for a **p
### [photoUpdateSettings ](https://docs.microsoft.com/graph/api/resources/photoupdatesettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String| The unique identifier for a peopleAdminSettings object. Inherited from entity.|
|source|String| Specifies the types of photo updates permitted. The possible values are: `cloud`, `onPremises`, `unknownFutureValue`.|
|allowedRoles|String collection|Contains a list of roles to perform edit operations in the cloud. Optional.|
### [profileCardProperty ](https://docs.microsoft.com/graph/api/resources/profilecardproperty?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                        | Description |
|:---------------------|:------------------------------------------------------------|:------------|
|annotations           |profileCardAnnotation collection | Allows an administrator to set a custom display label for the directory property and localize it for the users in their tenant.|
|directoryPropertyName |String                                                       | Identifies a **p
### [pronounsSettings ](https://docs.microsoft.com/graph/api/resources/pronounssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabledInOrganization|Boolean| `true` to enable pronouns in the organization; otherwise, `false`. The default value is `false`, and pronouns are disabled.|
