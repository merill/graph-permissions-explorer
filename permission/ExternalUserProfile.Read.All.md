# ExternalUserProfile.Read.All

> Allows the app to read available properties of external user profiles, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /directory/externalUserProfiles/{id}](https://docs.microsoft.com/graph/api/externaluserprofile-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|47167bec-55a7-4caf-9ecc-8d4566e3cfb1|
|**Consent Type**|Admin|
|**Display String**|Read external user profiles|
|**Description**|Allows the app to read available properties of external user profiles, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|1987d7a0-d602-4262-ab90-cfdd43b37545|
|**Display String**|Read all external user profiles|
|**Description**|Allows the app to read available properties of external user profiles, without a signed-in user.|
## Resources
### [externalUserProfile ](https://docs.microsoft.com/graph/api/resources/externaluserprofile?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|address|physicalOfficeAddress|The office address of the external user profile. Inherited from externalProfile.|
|createdBy|String|The object ID of the user who created the external user profile. Inherited from externalProfile. Read-only. Not nullable. |
|createdDateTime|DateTimeOffset|Date and time when this external user was created. Inherited from externalProfile. Not nullable. Read-only. |
|companyName|String|The company name of the external user profile. Inherited from externalProfile. Supports `$filter` (`eq`, `startswith`). |
|deletedDateTime|DateTimeOffset|Date and time when this external user profile was deleted. Always `null` when the object isn't deleted. Inherited from externalProfile. |
|department|String|The department of the external user profile. Inherited from externalProfile. |
|displayName|String|The display name of the external user profile. Inherited from externalProfile.|
|id|String|The unique identifier for the external user profile. For example, 12345678-9abc-def0-1234-56789abcde. The value of the **id** property is often but not exclusively in the form of a GUID; treat it as an opaque identifier and don't rely on it being a GUID. Key. Not nullable. Read-only.|
|isDiscoverable|Boolean|Represents whether the external user profile is discoverable in the directory. When `true`, this external profile shows up in Teams search. When `false`, this external profile doesn't show up in Teams search. Inherited from externalProfile. |
|isEnabled|Boolean|Represents whether the external user profile is enabled in the directory. This property is peer to the `accountEnabled` property on the User object. |
|jobTitle|String|The job title of the external user profile. Inherited from externalProfile.|
|phoneNumber|String|The phone number of the external user profile. Must be in E164 format. Inherited from externalProfile.|
|supervisorId|String|The object ID of the supervisor of the external user profile. Inherited from externalProfile. Supports `$filter` (`eq`, `startswith`).|
