# PendingExternalUserProfile.ReadWrite.All

> Allows the app to read and write available properties of pending external user profiles, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /directory/pendingExternalUserProfiles/{id}](https://docs.microsoft.com/graph/api/directory-delete-pendingexternaluserprofiles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directory/pendingExternalUserProfiles/{id}](https://docs.microsoft.com/graph/api/pendingexternaluserprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /directory/pendingExternalUserProfiles/{id}](https://docs.microsoft.com/graph/api/pendingexternaluserprofile-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|93a1fb28-c908-4826-904e-0c74ad352b73|
|**Consent Type**|Admin|
|**Display String**|Read and write pending external user profiles|
|**Description**|Allows the app to read and write available properties of pending external user profiles, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|8363c2b8-6ff7-420b-9966-c5884c2d48bc|
|**Display String**|Read and write all pending external user profiles|
|**Description**|Allows the app to read and write available properties of pending external user profiles, without a signed-in user.|
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
### [physicalOfficeAddress ](https://docs.microsoft.com/graph/api/resources/physicalofficeaddress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|city|String|The city.|
|countryOrRegion|String|The country or region. It's a free-format string value, for example, "United States".|
|officeLocation  | String | Office location such as building and office number for an organizational contact.  |
|postalCode|String|The postal code.|
|state|String|The state.|
|street|String|The street.|
