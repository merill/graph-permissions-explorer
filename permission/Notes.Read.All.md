# Notes.Read.All

> Allows the app to read OneNote notebooks that the signed-in user has access to in the organization.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /groups/{id}/onenote/notebooks](https://docs.microsoft.com/graph/api/onenote-list-notebooks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/notebooks/{id}](https://docs.microsoft.com/graph/api/notebook-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/notebooks/{id}/sectionGroups](https://docs.microsoft.com/graph/api/notebook-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/notebooks/{id}/sections](https://docs.microsoft.com/graph/api/notebook-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/operations/{id}](https://docs.microsoft.com/graph/api/onenoteoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/pages](https://docs.microsoft.com/graph/api/onenote-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/resources/{id}/content](https://docs.microsoft.com/graph/api/resource-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sectionGroups](https://docs.microsoft.com/graph/api/onenote-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sectionGroups/{id}](https://docs.microsoft.com/graph/api/sectiongroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sectionGroups/{id}/sectionGroups](https://docs.microsoft.com/graph/api/sectiongroup-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sectionGroups/{id}/sections](https://docs.microsoft.com/graph/api/sectiongroup-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sections](https://docs.microsoft.com/graph/api/onenote-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sections/{id}](https://docs.microsoft.com/graph/api/section-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/onenote/sections/{id}/pages](https://docs.microsoft.com/graph/api/section-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/notebooks](https://docs.microsoft.com/graph/api/onenote-list-notebooks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/notebooks/{id}](https://docs.microsoft.com/graph/api/notebook-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/notebooks/{id}/sectionGroups](https://docs.microsoft.com/graph/api/notebook-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/notebooks/{id}/sections](https://docs.microsoft.com/graph/api/notebook-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/notebooks/getRecentNotebooks(includePersonalNotebooks={includePersonalNotebooks})](https://docs.microsoft.com/graph/api/notebook-getrecentnotebooks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/operations/{id}](https://docs.microsoft.com/graph/api/onenoteoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/pages](https://docs.microsoft.com/graph/api/onenote-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/pages/{id}](https://docs.microsoft.com/graph/api/page-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/resources/{id}/content](https://docs.microsoft.com/graph/api/resource-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sectionGroups](https://docs.microsoft.com/graph/api/onenote-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sectionGroups/{id}](https://docs.microsoft.com/graph/api/sectiongroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sectionGroups/{id}/sectionGroups](https://docs.microsoft.com/graph/api/sectiongroup-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sectionGroups/{id}/sections](https://docs.microsoft.com/graph/api/sectiongroup-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sections](https://docs.microsoft.com/graph/api/onenote-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sections/{id}](https://docs.microsoft.com/graph/api/section-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/onenote/sections/{id}/pages](https://docs.microsoft.com/graph/api/section-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/notebooks](https://docs.microsoft.com/graph/api/onenote-list-notebooks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/notebooks/{id}](https://docs.microsoft.com/graph/api/notebook-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/notebooks/{id}/sectionGroups](https://docs.microsoft.com/graph/api/notebook-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/notebooks/{id}/sections](https://docs.microsoft.com/graph/api/notebook-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/operations/{id}](https://docs.microsoft.com/graph/api/onenoteoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/pages](https://docs.microsoft.com/graph/api/onenote-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/resources/{id}/content](https://docs.microsoft.com/graph/api/resource-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sectionGroups](https://docs.microsoft.com/graph/api/onenote-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sectionGroups/{id}](https://docs.microsoft.com/graph/api/sectiongroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sectionGroups/{id}/sectionGroups](https://docs.microsoft.com/graph/api/sectiongroup-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sectionGroups/{id}/sections](https://docs.microsoft.com/graph/api/sectiongroup-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sections](https://docs.microsoft.com/graph/api/onenote-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sections/{id}](https://docs.microsoft.com/graph/api/section-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{id}/onenote/sections/{id}/pages](https://docs.microsoft.com/graph/api/section-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/notebooks](https://docs.microsoft.com/graph/api/onenote-list-notebooks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/notebooks/{id}](https://docs.microsoft.com/graph/api/notebook-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/notebooks/{id}/sectionGroups](https://docs.microsoft.com/graph/api/notebook-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/notebooks/{id}/sections](https://docs.microsoft.com/graph/api/notebook-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/notebooks/getRecentNotebooks(includePersonalNotebooks={includePersonalNotebooks})](https://docs.microsoft.com/graph/api/notebook-getrecentnotebooks?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/operations/{id}](https://docs.microsoft.com/graph/api/onenoteoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/pages](https://docs.microsoft.com/graph/api/onenote-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/resources/{id}/content](https://docs.microsoft.com/graph/api/resource-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sectionGroups](https://docs.microsoft.com/graph/api/onenote-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sectionGroups/{id}](https://docs.microsoft.com/graph/api/sectiongroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sectionGroups/{id}/sectionGroups](https://docs.microsoft.com/graph/api/sectiongroup-list-sectiongroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sectionGroups/{id}/sections](https://docs.microsoft.com/graph/api/sectiongroup-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sections](https://docs.microsoft.com/graph/api/onenote-list-sections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sections/{id}](https://docs.microsoft.com/graph/api/section-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/onenote/sections/{id}/pages](https://docs.microsoft.com/graph/api/section-list-pages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/onenote/notebooks/GetNotebookFromWebUrl](https://docs.microsoft.com/graph/api/notebook-getnotebookfromweburl?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/onenote/notebooks/GetNotebookFromWebUrl](https://docs.microsoft.com/graph/api/notebook-getnotebookfromweburl?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{id}/onenote/notebooks/GetNotebookFromWebUrl](https://docs.microsoft.com/graph/api/notebook-getnotebookfromweburl?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/onenote/notebooks/GetNotebookFromWebUrl](https://docs.microsoft.com/graph/api/notebook-getnotebookfromweburl?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|dfabfca6-ee36-4db2-8208-7a28381419b3|
|**Consent Type**|User|
|**Display String**|Read all OneNote notebooks that user can access|
|**Description**|Allows the app to read OneNote notebooks that the signed-in user has access to in the organization.|
## Application Permission
|||
|-|-|
|**Id**|3aeca27b-ee3a-4c2b-8ded-80376e2134a4|
|**Display String**|Read all OneNote notebooks|
|**Description**|Allows the app to read all the OneNote notebooks in your organization, without a signed-in user.|
## Resources
### [notebook ](https://docs.microsoft.com/graph/api/resources/notebook?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the notebook was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|The name of the notebook.|
|id|String|The unique identifier of the notebook. Read-only.|
|isDefault|Boolean|Indicates whether this is the user's default notebook. Read-only.|
|isShared|Boolean|Indicates whether the notebook is shared. If true, the contents of the notebook can be seen by people other than the owner. Read-only.|
|lastModifiedBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the notebook was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|links|NotebookLinks|Links for opening the notebook. The `oneNoteClientURL` link opens the notebook in the OneNote native client if it's installed. The `oneNoteWebURL` link opens the notebook in OneNote on the web.|
|sectionGroupsUrl|String|The URL for the `sectionGroups` navigation property, which returns all the section groups in the notebook. Read-only.|
|sectionsUrl|String|The URL for the `sections` navigation property, which returns all the sections in the notebook. Read-only.|
|self|String|The endpoint where you can get details about the notebook. Read-only.|
|userRole|onenoteUserRole|Possible values are: `Owner`, `Contributor`, `Reader`, `None`. Owner represents owner-level access to the notebook. Contributor represents read/write access to the notebook. Reader represents read-only access to the notebook. Read-only.|
### [onenoteOperation ](https://docs.microsoft.com/graph/api/resources/onenoteoperation?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdDateTime| DateTimeOffset |The start time of the operation.|
|error|onenoteOperationError|The error returned by the operation.|
|id|string|The operation id. Read-only.|
|lastActionDateTime| DateTimeOffset |The time of the last action of the operation.|
|percentComplete|string|The operation percent complete if the operation is still in `running` status.|
|resourceId|string|The resource id.|
|resourceLocation|string|The resource URI for the object. For example, the resource URI for a copied page or section. |
|status|operationStatus|The current status of the operation: `NotStarted`, `Running`, `Completed`, `Failed`. |
### [onenotePage ](https://docs.microsoft.com/graph/api/resources/onenotepage?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|content|Stream|The page's HTML content.|
|contentUrl|String|The URL for the page's HTML content.  Read-only.|
|createdByAppId|String|The unique identifier of the application that created the page. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the page was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|id|String|The unique identifier of the page.  Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the page was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|level|Int32|The indentation level of the page. Read-only.|
|links|pageLinks|Links for opening the page. The `oneNoteClientURL` link opens the page in the OneNote native client if it 's installed. The `oneNoteWebUrl` link opens the page in OneNote on the web. Read-only.|
|order|Int32|The order of the page within its parent section. Read-only.|
|self|String|The endpoint where you can get details about the page. Read-only.|
|title|String|The title of the page. |
### [onenoteResource ](https://docs.microsoft.com/graph/api/resources/onenoteresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| content | Edm.Stream|The content of the resource.|
| contentUrl | String |The URL for the content stream.|
### [onenoteSection ](https://docs.microsoft.com/graph/api/resources/onenotesection?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the section was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|id|String|The unique identifier of the section.  Read-only.|
|isDefault|Boolean|Indicates whether this is the user's default section. Read-only.|
|lastModifiedBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the section was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|links|sectionLinks|Links for opening the section. The `oneNoteClientURL` link opens the section in the OneNote native client if it's installed. The `oneNoteWebURL` link opens the section in OneNote on the web.|
|displayName|String|The name of the section. |
|pagesUrl|String|The `pages` endpoint where you can get details for all the pages in the section. Read-only.|
|self|String|The endpoint where you can get details about the section. Read-only.|
### [onenotePage ](https://docs.microsoft.com/graph/api/resources/page?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|content|Stream|The page's HTML content.|
|contentUrl|String|The URL for the page's HTML content.  Read-only.|
|createdByAppId|String|The unique identifier of the application that created the page. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the page was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|id|String|The unique identifier of the page.  Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the page was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|level|Int32|The indentation level of the page. Read-only.|
|links|PageLinks|Links for opening the page. The `oneNoteClientURL` link opens the page in the OneNote native client if it 's installed. The `oneNoteWebUrl` link opens the page in OneNote on the web. Read-only.|
|order|Int32|The order of the page within its parent section. Read-only.|
|self|String|The endpoint where you can get details about the page. Read-only.|
|title|String|The title of the page. |
### [recentNotebook ](https://docs.microsoft.com/graph/api/resources/recentnotebook?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|displayName|String|The name of the notebook.|
|lastAccessedTime|DateTimeOffset|The date and time when the notebook was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|links|recentNotebookLinks|Links for opening the notebook. The `oneNoteClientURL` link opens the notebook in the OneNote client, if it's installed. The `oneNoteWebURL` link opens the notebook in OneNote on the web.|
|sourceService|onenoteSourceService|The backend store where the Notebook resides, either `OneDriveForBusiness` or `OneDrive`.|
### [oneNoteResource ](https://docs.microsoft.com/graph/api/resources/resource?view=graph-rest-1.0&tabs=http)
| Property             | Type            | Description
|:---------------------|:----------------|:---------------------------------
| content              | Stream          | The content stream
| contentUrl           | String (url)    | The URL for downloading the content

### [onenoteSection ](https://docs.microsoft.com/graph/api/resources/section?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the section was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|The name of the section. |
|id|String|The unique identifier of the section.  Read-only.|
|isDefault|Boolean|Indicates whether this is the user's default section. Read-only.|
|lastModifiedBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the section was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|links|SectionLinks|Links for opening the section. The `oneNoteClientURL` link opens the section in the OneNote native client if it's installed. The `oneNoteWebURL` link opens the section in OneNote on the web.|
|pagesUrl|String|The `pages` endpoint where you can get details for all the pages in the section. Read-only.|
|self|String|The endpoint where you can get details about the section. Read-only.|
### [sectionGroup ](https://docs.microsoft.com/graph/api/resources/sectiongroup?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|createdDateTime|DateTimeOffset|The date and time when the section group was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|displayName|String|The name of the section group.|
|id|String|The unique identifier of the section group. Read-only.|
|lastModifiedBy|identitySet|Identity of the user, device, and application which created the item. Read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the section group was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|sectionGroupsUrl|String|The URL for the `sectionGroups` navigation property, which returns all the section groups in the section group. Read-only.|
|sectionsUrl|String|The URL for the `sections` navigation property, which returns all the sections in the section group. Read-only.|
|self|String|The endpoint where you can get details about the section group. Read-only.|
