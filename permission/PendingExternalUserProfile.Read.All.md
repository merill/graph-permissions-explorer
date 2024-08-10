# PendingExternalUserProfile.Read.All

> Allows the app to read available properties of pending external user profiles, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /directory/pendingExternalUserProfiles/{id}](https://docs.microsoft.com/graph/api/pendingexternaluserprofile-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|d88fd3fb-53d3-4c1c-8c39-787fcac2ed7a|
|**Consent Type**|Admin|
|**Display String**|Read pending external user profiles|
|**Description**|Allows the app to read available properties of pending external user profiles, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|bdfb26d9-bb36-49be-9b4c-b8cbf4b05808|
|**Display String**|Read all pending external user profiles|
|**Description**|Allows the app to read available properties of pending external user profiles, without a signed-in user.|
## Resources
### [pendingExternalUserProfile ](https://docs.microsoft.com/graph/api/resources/pendingexternaluserprofile?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|address|physicalOfficeAddress|The office address of the pending external user profile. Inherited from externalProfile.|
|createdBy|String|The object ID of the user or principal who created the pending external user profile or invited the external user. Inherited from externalProfile. Read-only. Not nullable. |
|createdDateTime|DateTimeOffset|Date and time when this pending external user profile was created. Inherited from externalProfile. Not nullable. Read-only. |
|companyName|String|The company name of the pending external user profile. Inherited from externalProfile. Supports the `$filter` (`eq`, `startswith`) query parameter.  |
|deletedDateTime|DateTimeOffset|Date and time when the pending external user profile was deleted. Always `null` when the object isn't deleted. Inherited from externalProfile. |
|department|String|The department of the pending external user profile. Inherited from externalProfile. |
|displayName|String|The display name of the pending external user profile. Inherited from externalProfile.|
|id|String|The unique identifier for the pending external user profile. Not nullable. Read-only.|
|isDiscoverable|Boolean|Represents whether the pending external user profile is discoverable in the directory. When `true`, this external profile shows up in Teams search. Inherited from externalProfile.|
|isEnabled|Boolean|Represents whether the pending external user profile is enabled in the directory. Inherited from externalProfile.|
|jobTitle|String|The job title of the external user profile. Inherited from externalProfile.|
|phoneNumber|String|The phone number of the pending external user profile. Must be in E.164 format. Inherited from externalProfile.|
|supervisorId|String|The object ID of the supervisor of the pending external user profile. Inherited from externalProfile. Supports the `$filter` (`eq`, `startswith`) query parameter.|
