# TermStore.ReadWrite.All

> Allows the app to read or modify data that the signed-in user has access to. This includes all sets, groups and terms in the term store.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /sites/{site-id}/termStore/groups/{group-id}](https://docs.microsoft.com/graph/api/termstore-group-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}](https://docs.microsoft.com/graph/api/termstore-term-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /termStore/groups/{groupId}](https://docs.microsoft.com/graph/api/termstore-group-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /termStore/sets/{setId}](https://docs.microsoft.com/graph/api/termstore-set-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /termStore/sets/{setId}/terms/{termId}](https://docs.microsoft.com/graph/api/termstore-term-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE sites/{site-id}/termStore/sets/{set-id}](https://docs.microsoft.com/graph/api/termstore-set-delete?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[PATCH /sites/{site-id}/termStore/sets/{set-id}](https://docs.microsoft.com/graph/api/termstore-set-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}](https://docs.microsoft.com/graph/api/termstore-term-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /termStore](https://docs.microsoft.com/graph/api/termstore-store-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /termStore/sets/{setId}](https://docs.microsoft.com/graph/api/termstore-set-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /termStore/sets/{setId}/terms/{termId}](https://docs.microsoft.com/graph/api/termstore-term-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH sites/{site-id}/termStore](https://docs.microsoft.com/graph/api/termstore-store-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{site-id}/termStore/groups](https://docs.microsoft.com/graph/api/termstore-group-post?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{site-id}/termStore/sets](https://docs.microsoft.com/graph/api/termstore-set-post?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{site-id}/termStore/sets/{set-id}/children](https://docs.microsoft.com/graph/api/termstore-term-post?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}/children](https://docs.microsoft.com/graph/api/termstore-term-post?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{site-id}/termStore/sets/{set-id}/terms/{term-id}/relations](https://docs.microsoft.com/graph/api/termstore-relation-post?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /termStore/groups](https://docs.microsoft.com/graph/api/termstore-group-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /termStore/sets](https://docs.microsoft.com/graph/api/termstore-set-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /termStore/sets/{setId}/children](https://docs.microsoft.com/graph/api/termstore-term-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /termStore/sets/{setId}/terms/{termId}/children](https://docs.microsoft.com/graph/api/termstore-term-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /termStore/sets/{setId}/terms/{termId}/relations](https://docs.microsoft.com/graph/api/termstore-relation-post?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|6c37c71d-f50f-4bff-8fd3-8a41da390140|
|**Consent Type**|Admin|
|**Display String**|Read and write term store data|
|**Description**|Allows the app to read or modify data that the signed-in user has access to. This includes all sets, groups and terms in the term store.|
## Application Permission
|||
|-|-|
|**Id**|f12eb8d6-28e3-46e6-b2c0-b7e4dc69fc95|
|**Display String**|Read and write all term store data|
|**Description**|Allows the app to read, edit or write all term store data, without a signed-in user. This includes all sets, groups and terms in the term store.|
## Resources
### [keyValue ](https://docs.microsoft.com/graph/api/resources/keyvalue?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|key|string| Key for the key-value pair. |
|value|string| Value for the key-value pair.|
### [Group ](https://docs.microsoft.com/graph/api/resources/termstore-group?view=graph-rest-1.0&tabs=http)
| Property             | Type               | Description                        |
|:---------------------|:-------------------|:------------------------------------
| createdDateTime      | DateTimeOffset     | Date and time of the group creation. Read-only. |
| description          | string             | Description that gives details on the term usage. |
| displayName          | string             | Name of the group. |
| id                   | string             | Unique identifier of the group. Read-Only. |
| parentSiteId         | string             | ID of the parent site of this group. |
| scope                | string             | Returns the type of the group. Possible values are: `global`, `system`, and `siteCollection`. |
### [localizedDescription ](https://docs.microsoft.com/graph/api/resources/termstore-localizeddescription?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description in the localized language.|
|languageTag|String|The language tag for the label.|
### [localizedLabel ](https://docs.microsoft.com/graph/api/resources/termstore-localizedlabel?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isDefault|Boolean|Indicates whether the label is the default label.|
|languageTag|String|The language tag for the label.|
|name|String|The name of the label.|
### [localizedName ](https://docs.microsoft.com/graph/api/resources/termstore-localizedname?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|languageTag|String|The language tag for the label.|
|name|String|The name in the localized language.|
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
