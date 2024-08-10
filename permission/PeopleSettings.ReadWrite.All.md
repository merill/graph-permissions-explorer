# PeopleSettings.ReadWrite.All

> Allows the application to read and write tenant-wide people settings on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /admin/people/photoUpdateSettings/$ref](https://docs.microsoft.com/graph/api/peopleadminsettings-delete-photoupdatesettings?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /admin/people/profileCardProperties/{id}](https://docs.microsoft.com/graph/api/profilecardproperty-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/people](https://docs.microsoft.com/graph/api/peopleadminsettings-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/people/itemInsights](https://docs.microsoft.com/graph/api/peopleadminsettings-list-iteminsights?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /admin/people/photoUpdateSettings](https://docs.microsoft.com/graph/api/photoupdatesettings-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /admin/people/profileCardProperties](https://docs.microsoft.com/graph/api/peopleadminsettings-list-profilecardproperties?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /admin/people/pronouns](https://docs.microsoft.com/graph/api/peopleadminsettings-list-pronouns?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /admin/people/itemInsights](https://docs.microsoft.com/graph/api/insightssettings-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /admin/people/photoUpdateSettings](https://docs.microsoft.com/graph/api/photoupdatesettings-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /admin/people/profileCardProperties/{id}](https://docs.microsoft.com/graph/api/profilecardproperty-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /admin/people/pronouns](https://docs.microsoft.com/graph/api/pronounssettings-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /admin/people/profileCardProperties](https://docs.microsoft.com/graph/api/peopleadminsettings-post-profilecardproperties?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|e67e6727-c080-415e-b521-e3f35d5248e9|
|**Consent Type**|Admin|
|**Display String**|Read and write tenant-wide people settings|
|**Description**|Allows the application to read and write tenant-wide people settings on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|b6890674-9dd5-4e42-bb15-5af07f541ae1|
|**Display String**|Read and write all tenant-wide people settings|
|**Description**|Allows the application to read and write tenant-wide people settings without a signed-in user.|
## Resources
### [insightsSettings ](https://docs.microsoft.com/graph/api/resources/insightssettings?view=graph-rest-1.0&tabs=http)
| Property   | Type|Description|
|:---------------|:--------|:----------|
|disabledForGroup|String| The ID of a Microsoft Entra group, of which the specified type of insights are disabled for its members. The default value is `null`. Optional.|
|isEnabledInOrganization|Boolean| `true` if insights of the specified type are enabled for the organization; `false` if insights of the specified type are disabled for all users without exceptions. The default value is `true`. Optional.|
### [itemInsights ](https://docs.microsoft.com/graph/api/resources/iteminsights?view=graph-rest-1.0&tabs=http)

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
### [profileCardAnnotation ](https://docs.microsoft.com/graph/api/resources/profilecardannotation?view=graph-rest-1.0&tabs=http)
| Property     | Type                                                            | Description                                                                                                                       |
|:-------------|:----------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------|
|displayName   |String                                                           | If present, the value of this field is used by the profile card as the default property label in the experience (for example, "Cost Center"). |
|localizations |displayNameLocalization collection | Each resource in this collection represents the localized value of the attribute name for a given language, used as the default label for that locale. For example, a user with a `nb-NO` client gets "Kostnadssenter" as the attribute label, rather than "Cost Center."|
### [profileCardProperty ](https://docs.microsoft.com/graph/api/resources/profilecardproperty?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                        | Description |
|:---------------------|:------------------------------------------------------------|:------------|
|annotations           |profileCardAnnotation collection | Allows an administrator to set a custom display label for the directory property and localize it for the users in their tenant.|
|directoryPropertyName |String                                                       | Identifies a **p
### [pronounsSettings ](https://docs.microsoft.com/graph/api/resources/pronounssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabledInOrganization|Boolean| `true` to enable pronouns in the organization; otherwise, `false`. The default value is `false`, and pronouns are disabled.|
