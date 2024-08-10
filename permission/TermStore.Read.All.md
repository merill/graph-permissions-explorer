# TermStore.Read.All

> Allows the app to read the term store data that the signed-in user has access to. This includes all sets, groups and terms in the term store.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /sites/{site-id}/termStore](https://docs.microsoft.com/graph/api/termstore-store-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/groups](https://docs.microsoft.com/graph/api/termstore-list-groups?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/groups/{group-id}](https://docs.microsoft.com/graph/api/termstore-group-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/groups/{group-id}/sets/{set-id}/terms/{term-id}](https://docs.microsoft.com/graph/api/termstore-term-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/sets/{set-id}](https://docs.microsoft.com/graph/api/termstore-set-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/sets/{set-id}/children](https://docs.microsoft.com/graph/api/termstore-term-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/sets/{set-id}/relations](https://docs.microsoft.com/graph/api/termstore-term-list-relations?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}](https://docs.microsoft.com/graph/api/termstore-term-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}/children](https://docs.microsoft.com/graph/api/termstore-term-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}/relations](https://docs.microsoft.com/graph/api/termstore-term-list-relations?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /termStore](https://docs.microsoft.com/graph/api/termstore-store-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/groups](https://docs.microsoft.com/graph/api/termstore-list-groups?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/groups/{group-id}](https://docs.microsoft.com/graph/api/termstore-group-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/groups/{group-id}/sets/{set-id}/terms/{term-id}](https://docs.microsoft.com/graph/api/termstore-term-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/groups/{groupId}/sets](https://docs.microsoft.com/graph/api/termstore-group-list-sets?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/sets/{set-id}](https://docs.microsoft.com/graph/api/termstore-set-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/sets/{set-id}/terms/{term-id}](https://docs.microsoft.com/graph/api/termstore-term-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/sets/{setId}/children](https://docs.microsoft.com/graph/api/termstore-term-list-children?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/sets/{setId}/relations](https://docs.microsoft.com/graph/api/termstore-term-list-relations?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/sets/{setId}/terms/{termId}/children](https://docs.microsoft.com/graph/api/termstore-term-list-children?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /termStore/sets/{setId}/terms/{termId}/relations](https://docs.microsoft.com/graph/api/termstore-term-list-relations?view=graph-rest-beta&tabs=http)|
|V1|D|[GET sites/{site-id}/termStore/groups/{group-id}/sets](https://docs.microsoft.com/graph/api/termstore-group-list-sets?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|297f747b-0005-475b-8fef-c890f5152b38|
|**Consent Type**|Admin|
|**Display String**|Read term store data|
|**Description**|Allows the app to read the term store data that the signed-in user has access to. This includes all sets, groups and terms in the term store.|
## Application Permission
|||
|-|-|
|**Id**|ea047cc2-df29-4f3e-83a3-205de61501ca|
|**Display String**|Read all term store data|
|**Description**|Allows the app to read all term store data, without a signed-in user. This includes all sets, groups and terms in the term store.|
## Resources
### [Group ](https://docs.microsoft.com/graph/api/resources/termstore-group?view=graph-rest-1.0&tabs=http)
| Property             | Type               | Description                        |
|:---------------------|:-------------------|:------------------------------------
| createdDateTime      | DateTimeOffset     | Date and time of the group creation. Read-only. |
| description          | string             | Description that gives details on the term usage. |
| displayName          | string             | Name of the group. |
| id                   | string             | Unique identifier of the group. Read-Only. |
| parentSiteId         | string             | ID of the parent site of this group. |
| scope                | string             | Returns the type of the group. Possible values are: `global`, `system`, and `siteCollection`. |
### [relation ](https://docs.microsoft.com/graph/api/resources/termstore-relation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the relation.|
|relationship|microsoft.graph.termStore.relationType|The type of relation. Possible values are: `pin`, `reuse`.|
### [set ](https://docs.microsoft.com/graph/api/resources/termstore-set?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of set creation. Read-only.|
|description|String|Description that gives details on the term usage.|
|id|String|Unique identifier. Read-only.|
|localizedNames|microsoft.graph.termStore.localizedName collection|Name of the set for each languageTag.|
|properties|microsoft.graph.keyValue collection|Custom properties for the set.|
### [store ](https://docs.microsoft.com/graph/api/resources/termstore-store?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|defaultLanguageTag | String | Default language of the term store.|
|id|String | Unique identifier of the term store. Read-only.|
|languageTags | String collection | List of languages for the term store.|
### [term ](https://docs.microsoft.com/graph/api/resources/termstore-term?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of term creation. Read-only.|
|descriptions|microsoft.graph.termStore.localizedDescription collection|Description about term that is dependent on the languageTag.|
|id|String|Unique identifier of term. Read-Only.|
|labels|microsoft.graph.termStore.localizedLabel collection|Label metadata for a term.|
|lastModifiedDateTime|DateTimeOffset|Last date and time of term modification. Read-only.|
|properties|microsoft.graph.keyValue collection|Collection of properties on the term.|
