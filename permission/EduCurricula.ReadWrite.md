# EduCurricula.ReadWrite

> Allows the app to read and write user's modules and resources on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[](https://docs.microsoft.com/graph/api/educationmodule-publish?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /education/classes/{class-id}/modules/{module-id}/resources/{resource-id}](https://docs.microsoft.com/graph/api/educationmoduleresource-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /education/classes/{id}/modules/{id}](https://docs.microsoft.com/graph/api/educationmodule-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /education/classes/{class-id}/modules/{module-id}/resources/{resource-id}](https://docs.microsoft.com/graph/api/educationmoduleresource-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /education/classes/{id}/modules](https://docs.microsoft.com/graph/api/educationclass-list-modules?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /education/classes/{id}/modules/{id}](https://docs.microsoft.com/graph/api/educationmodule-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /education/classes/{id}/modules/{id}/resources](https://docs.microsoft.com/graph/api/educationmodule-list-resources?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /education/classes/{class-id}/modules/{module-id}](https://docs.microsoft.com/graph/api/educationmodule-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /education/classes/{class-id}/modules/{module-id}/resources/{resource-id}](https://docs.microsoft.com/graph/api/educationmoduleresource-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /education/classes/{class-id}/modules/{module-id}/resources](https://docs.microsoft.com/graph/api/educationmodule-post-resources?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /education/classes/{classId}/modules/{moduleId}/setUpResourcesFolder](https://docs.microsoft.com/graph/api/educationmodule-setupresourcesfolder?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /education/classes/{id}/modules](https://docs.microsoft.com/graph/api/educationclass-post-module?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /education/classes/{id}/modules/{id}/pin](https://docs.microsoft.com/graph/api/educationmodule-pin?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /education/classes/{id}/modules/{id}/publish](https://docs.microsoft.com/graph/api/educationmodule-publish?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /education/classes/{id}/modules/{id}/unpin](https://docs.microsoft.com/graph/api/educationmodule-unpin?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4793c53b-df34-44fd-8d26-d15c517732f5|
|**Consent Type**|Admin|
|**Display String**|Read and write the user's class modules and resources|
|**Description**|Allows the app to read and write user's modules and resources on behalf of the signed-in user.|
## Resources
### [educationChannelResource ](https://docs.microsoft.com/graph/api/resources/educationchannelresource?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                  |
| :------- | :----- | :--------------------------- |
| url      | String | URL of the channel resource. |
### [educationClass ](https://docs.microsoft.com/graph/api/resources/educationclass?view=graph-rest-1.0&tabs=http)
| Property             | Type                                           | Description                                                        |
| :------------------- | :--------------------------------------------- | :----------------------------------------------------------------- |
| classCode            | String                                         | Class code used by the school to identify the class.               |
| createdBy            | identitySet     | Entity who created the class                                       |
| description          | String                                         | Description of the class.                                          |
| displayName          | String                                         | Name of the class.                                                 |
| externalId           | String                                         | ID of the class from the syncing system.                           |
| externalSource       | educationExternalSource                        | How this class was created. Possible values are: `sis`, `manual`.  |
| externalSourceDetail | String                                         | The name of the external source this resource was generated from. |
| externalName         | String                                         | Name of the class in the syncing system.                           |
| grade                | String                                         | Grade level of the class.                                          |
| id                   | String                                         | Object identifier. Inherited from entity. |
| mailNickname         | String                                         | Mail name for sending email to all members, if this is enabled.    |
| term                 | educationTerm | Term for this class.                                               |
### [educationExcelResource ](https://docs.microsoft.com/graph/api/resources/educationexcelresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the resource.|
|fileUrl|String|Pointer to the Excel file object.|
|lastModifiedBy|identitySet|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [educationExternalResource ](https://docs.microsoft.com/graph/api/resources/educationexternalresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the resource.|
|lastModifiedBy|identitySet|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|webUrl|String|Location of the resource. Required.|
### [educationFileResource ](https://docs.microsoft.com/graph/api/resources/educationfileresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the resource.|
|fileUrl|String|Location on disk of the file resource.|
|lastModifiedBy|identitySet|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [educationLinkedAssignmentResource ](https://docs.microsoft.com/graph/api/resources/educationlinkedassignmentresource?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                   |
| :------- | :----- | :---------------------------- |
| url      | String | URL of the actual assignment. |
### [educationLinkResource ](https://docs.microsoft.com/graph/api/resources/educationlinkresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resource was added.|
|displayName|string|The display name of the resource.|
|lastModifiedBy|identitySet|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|link|String|URL to the resource.|
### [educationMediaResource ](https://docs.microsoft.com/graph/api/resources/educationmediaresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this resource.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the user who added resource.|
|fileUrl|String|Location of the file on shared point folder. Required|
|lastModifiedBy|identitySet|The last user to modify the resource|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [educationModule ](https://docs.microsoft.com/graph/api/resources/educationmodule?view=graph-rest-1.0&tabs=http)
| Property             | Type                          | Description                                                                                                                                                                                                         |
| :------------------- | :---------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| createdBy            | identitySet | The display name of the user that created the **module**.                                                                                                                                                           |
| createdDateTime      | DateTimeOffset                | Date time the **module** was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`       |
| description          | String                        | Description of the **module**.                                                                                                                                                                                      |
| displayName          | String                        | Name of the **module**.                                                                                                                                                                                             |
| id                   | String                        | The unique identifier for the **module**. Inherited from entity. Read-only.                                                                                                               |
| isPinned             | Boolean                       | Indicates whether the module is pinned or not.                                                                                                                                                                      |
| lastModifiedBy       | identitySet | The last user that modified the **module**.                                                                                                                                                                         |
| lastModifiedDateTime | DateTimeOffset                | Date time the **module** was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z` |
| resourcesFolderUrl   | string                        | Folder URL where all the file resources for this **module** are stored.                                                                                                                                             |
| status               | string                        | Status of the **m
### [educationModuleResource ](https://docs.microsoft.com/graph/api/resources/educationmoduleresource?view=graph-rest-1.0&tabs=http)
| Property | Type                                      | Description                                                |
| :------- | :---------------------------------------- | :--------------------------------------------------------- |
| id       | String                                    | ID of this resource. Read-only.                            |
| resource | educationResource | Resource object that is with this module. |
### [educationPowerPointResource ](https://docs.microsoft.com/graph/api/resources/educationpowerpointresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the resource.|
|fileUrl|String|Location of the file on disk.|
|lastModifiedBy|identitySet|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [educationWordResource ](https://docs.microsoft.com/graph/api/resources/educationwordresource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the resource.|
|fileUrl|String|Location of the file on disk.|
|lastModifiedBy|identitySet|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
