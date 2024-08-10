# Teamwork.Read.All

> Allows the app to read the teamwork settings of the organization, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /teamwork](https://docs.microsoft.com/graph/api/teamwork-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|594f4bb6-c083-4cf9-8aa8-213823bdf351|
|**Consent Type**|Admin|
|**Display String**|Read organizational teamwork settings|
|**Description**|Allows the app to read the teamwork settings of the organization, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|75bcfbce-a647-4fba-ad51-b63d73b210f4|
|**Display String**|Read organizational teamwork settings|
|**Description**|Allows the app to read all teamwork settings of the organization without a signed-in user.|
## Resources
### [teamwork ](https://docs.microsoft.com/graph/api/resources/teamwork?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
|id|string|The default teamwork identifier.|
|isTeamsEnabled|Boolean|Indicates whether Microsoft Teams is enabled for the organization.|  
|region|string|Represents the region of the organization or the tenant. The **r
