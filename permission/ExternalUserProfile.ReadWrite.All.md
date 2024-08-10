# ExternalUserProfile.ReadWrite.All

> Allows the app to read and write available properties of external user profiles, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /directory/externalUserProfiles/{id}](https://docs.microsoft.com/graph/api/directory-delete-externaluserprofiles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/externalUserProfiles/{id}](https://docs.microsoft.com/graph/api/externaluserprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /directory/externalUserProfiles/{id}](https://docs.microsoft.com/graph/api/externaluserprofile-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c6068dc7-a791-46a4-a811-b8228e6649ab|
|**Consent Type**|Admin|
|**Display String**|Read and write external user profiles|
|**Description**|Allows the app to read and write available properties of external user profiles, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|761327c9-d819-4c08-9a5f-874cd2826608|
|**Display String**|Read and write all external user profiles|
|**Description**|Allows the app to read and write available properties of external user profiles, without a signed-in user.|
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
### [physicalOfficeAddress ](https://docs.microsoft.com/graph/api/resources/physicalofficeaddress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|city|String|The city.|
|countryOrRegion|String|The country or region. It's a free-format string value, for example, "United States".|
|officeLocation  | String | Office location such as building and office number for an organizational contact.  |
|postalCode|String|The postal code.|
|state|String|The state.|
|street|String|The street.|
