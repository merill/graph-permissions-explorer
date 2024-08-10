# TeamworkTag.Read.All

> Allows the app to read tags in Teams without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /teams/{team-id}/tags](https://docs.microsoft.com/graph/api/teamworktag-list?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /teams/{team-Id}/tags](https://docs.microsoft.com/graph/api/teamworktag-list?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /teams/{team-id}/tags/{teamworkTag-id}](https://docs.microsoft.com/graph/api/teamworktag-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /teams/{team-Id}/tags/{teamworkTag-Id}](https://docs.microsoft.com/graph/api/teamworktag-get?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /teams/{team-id}/tags/{teamworkTag-id}/members](https://docs.microsoft.com/graph/api/teamworktagmember-list?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /teams/{team-Id}/tags/{teamworkTag-Id}/members](https://docs.microsoft.com/graph/api/teamworktagmember-list?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /teams/{team-id}/tags/{teamworkTag-id}/members/{teamworkTagMember-id}](https://docs.microsoft.com/graph/api/teamworktagmember-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /teams/{team-Id}/tags/{teamworkTag-Id}/members/{teamworkTagMember-Id}](https://docs.microsoft.com/graph/api/teamworktagmember-get?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|b74fd6c4-4bde-488e-9695-eeb100e4907f|
|**Display String**|Read tags in Teams|
|**Description**|Allows the app to read tags in Teams without a signed-in user.|
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
