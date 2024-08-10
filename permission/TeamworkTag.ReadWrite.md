# TeamworkTag.ReadWrite

> Allows the app to read and write tags in Teams, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /teams/{team-id}/tags/{teamworkTag-id}](https://docs.microsoft.com/graph/api/teamworktag-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /teams/{team-Id}/tags/{teamworkTag-Id}](https://docs.microsoft.com/graph/api/teamworktag-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /teams/{team-id}/tags/{teamworkTag-id}/members/{teamworkTagMember-id}](https://docs.microsoft.com/graph/api/teamworktagmember-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /teams/{team-Id}/tags/{teamworkTag-Id}/members/{teamworkTagMember-Id}](https://docs.microsoft.com/graph/api/teamworktagmember-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /teams/{team-id}/tags](https://docs.microsoft.com/graph/api/teamworktag-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /teams/{team-Id}/tags](https://docs.microsoft.com/graph/api/teamworktag-list?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /teams/{team-id}/tags/{teamworkTag-id}](https://docs.microsoft.com/graph/api/teamworktag-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /teams/{team-Id}/tags/{teamworkTag-Id}](https://docs.microsoft.com/graph/api/teamworktag-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /teams/{team-id}/tags/{teamworkTag-id}/members](https://docs.microsoft.com/graph/api/teamworktagmember-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /teams/{team-Id}/tags/{teamworkTag-Id}/members](https://docs.microsoft.com/graph/api/teamworktagmember-list?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /teams/{team-id}/tags/{teamworkTag-id}/members/{teamworkTagMember-id}](https://docs.microsoft.com/graph/api/teamworktagmember-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /teams/{team-Id}/tags/{teamworkTag-Id}/members/{teamworkTagMember-Id}](https://docs.microsoft.com/graph/api/teamworktagmember-get?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /teams/{team-id}/tags/{teamworkTag-id}](https://docs.microsoft.com/graph/api/teamworktag-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /teams/{team-Id}/tags/{teamworkTag-Id}](https://docs.microsoft.com/graph/api/teamworktag-update?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /teams/{team-id}/tags](https://docs.microsoft.com/graph/api/teamworktag-post?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /teams/{team-Id}/tags](https://docs.microsoft.com/graph/api/teamworktag-post?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|539dabd7-b5b6-4117-b164-d60cd15a8671|
|**Consent Type**|Admin|
|**Display String**|Read and write tags in Teams|
|**Description**|Allows the app to read and write tags in Teams, on behalf of the signed-in user.|
## Resources
### [teamworkTag ](https://docs.microsoft.com/graph/api/resources/teamworktag?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of the tag as it appears to the user in Microsoft Teams. A **teamworkTag** can't have more than 200 **teamworkTagMembers**.|
|displayName|String|The name of the tag as it appears to the user in Microsoft Teams.|
|id|String|The unique identifier for the tag. Inherited from entity.|
|memberCount|Int32|The number of users assigned to the tag.|
|tagType|teamworkTagType|The type of the tag. Default is standard.|
|teamId|String|ID of the team in which the tag is defined.|
### [teamworkTagMember ](https://docs.microsoft.com/graph/api/resources/teamworktagmember?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The member's display name.|
|id|String|The unique identifier for the member. Inherited from entity.|
|tenantId|String|The ID of the tenant that the tag member is a part of.|
|userId|String|The user ID of the member.|
