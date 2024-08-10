# EduCurricula.Read.All

> Allows the app to read all modules and resources, without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /education/classes/{class-id}/modules/{module-id}/resources/{resource-id}](https://docs.microsoft.com/graph/api/educationmoduleresource-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /education/classes/{id}/modules](https://docs.microsoft.com/graph/api/educationclass-list-modules?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /education/classes/{id}/modules/{id}](https://docs.microsoft.com/graph/api/educationmodule-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /education/classes/{id}/modules/{id}/resources](https://docs.microsoft.com/graph/api/educationmodule-list-resources?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|6cdb464c-3a03-40f8-900b-4cb7ea1da9c0|
|**Display String**|Read all class modules and resources|
|**Description**|Allows the app to read all modules and resources, without a signed-in user.|
## Resources
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
