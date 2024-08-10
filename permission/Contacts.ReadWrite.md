# Contacts.ReadWrite

> Allows the app to create, read, update, and delete user contacts. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/contactFolders/{id}](https://docs.microsoft.com/graph/api/contactfolder-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/contacts/{id}](https://docs.microsoft.com/graph/api/contact-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/contactFolders/{id}](https://docs.microsoft.com/graph/api/contactfolder-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/contacts/{id}](https://docs.microsoft.com/graph/api/contact-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactFolders](https://docs.microsoft.com/graph/api/user-list-contactfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactFolders/{id}](https://docs.microsoft.com/graph/api/contactfolder-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactFolders/{id}/childFolders](https://docs.microsoft.com/graph/api/contactfolder-list-childfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactFolders/{id}/contacts](https://docs.microsoft.com/graph/api/contactfolder-list-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactFolders/{id}/contacts/delta](https://docs.microsoft.com/graph/api/contact-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactFolders/delta](https://docs.microsoft.com/graph/api/contactfolder-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contacts](https://docs.microsoft.com/graph/api/user-list-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contacts/{id}](https://docs.microsoft.com/graph/api/contact-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /team/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactFolders](https://docs.microsoft.com/graph/api/user-list-contactfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactFolders/{id}](https://docs.microsoft.com/graph/api/contactfolder-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactFolders/{id}/childFolders](https://docs.microsoft.com/graph/api/contactfolder-list-childfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactFolders/{id}/contacts](https://docs.microsoft.com/graph/api/contactfolder-list-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contacts](https://docs.microsoft.com/graph/api/user-list-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contacts/{id}](https://docs.microsoft.com/graph/api/contact-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id}/contactFolders/{id}/contacts/delta](https://docs.microsoft.com/graph/api/contact-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id}/contactFolders/delta](https://docs.microsoft.com/graph/api/contactfolder-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contactFolders/{id}](https://docs.microsoft.com/graph/api/contactfolder-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contacts/{id}](https://docs.microsoft.com/graph/api/contact-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contactFolders/{id}](https://docs.microsoft.com/graph/api/contactfolder-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contacts/{id}](https://docs.microsoft.com/graph/api/contact-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/contactFolders](https://docs.microsoft.com/graph/api/user-post-contactfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/contactFolders/{contactFolderId}/contacts](https://docs.microsoft.com/graph/api/user-post-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/contactFolders/{id}/childFolders](https://docs.microsoft.com/graph/api/contactfolder-post-childfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/contactFolders/{id}/contacts](https://docs.microsoft.com/graph/api/contactfolder-post-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/contacts](https://docs.microsoft.com/graph/api/user-post-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/contactFolders](https://docs.microsoft.com/graph/api/user-post-contactfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/contactFolders/{contactFolderId}/contacts](https://docs.microsoft.com/graph/api/user-post-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/contactFolders/{id}/childFolders](https://docs.microsoft.com/graph/api/contactfolder-post-childfolders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/contactFolders/{id}/contacts](https://docs.microsoft.com/graph/api/contactfolder-post-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/contacts](https://docs.microsoft.com/graph/api/user-post-contacts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|d56682ec-c09e-4743-aaf4-1a3aac4caa21|
|**Consent Type**|User|
|**Display String**|Have full access to user contacts |
|**Description**|Allows the app to create, read, update, and delete user contacts. |
## Application Permission
|||
|-|-|
|**Id**|6918b873-d17a-4dc1-b314-35f528134491|
|**Display String**|Read and write contacts in all mailboxes|
|**Description**|Allows the app to create, read, update, and delete all contacts in all mailboxes without a signed-in user.|
## Resources
### [contact ](https://docs.microsoft.com/graph/api/resources/contact?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|assistantName|String|The name of the contact's assistant.|
|birthday|DateTimeOffset|The contact's birthday. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|businessAddress|PhysicalAddress|The contact's business address.|
|businessHomePage|String|The business home page of the contact.|
|businessPhones|String collection|The contact's business phone numbers.|
|categories|String collection|The categories associated with the contact.|
|changeKey|String|Identifies the version of the contact. Every time the contact is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object.|
|children|String collection|The names of the contact's children.|
|companyName|String|The name of the contact's company.|
|createdDateTime|DateTimeOffset|The time the contact was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|department|String|The contact's department.|
|displayName|String|The contact's display name. You can specify the display name in a create or update operation. Note that later updates to other properties may cause an automatically generated value to overwrite the displayName value you have specified. To preserve a pre-existing value, always include it as displayName in an update operation.|
|emailAddresses|EmailAddress collection|The contact's email addresses.|
|fileAs|String|The name the contact is filed under.|
|generation|String|The contact's suffix.|
|givenName|String|The contact's given name.|
|homeAddress|PhysicalAddress|The contact's home address.|
|homePhones|String collection|The contact's home phone numbers.|
|id|String|The contact's unique identifier. !INCLUDE [outlook-beta-id] Read-only.|
|imAddresses|String collection|The contact's instant messaging (IM) addresses.|
|initials|String|The contact's initials.|
|jobTitle|String|The contact’s job title.|
|lastModifiedDateTime|DateTimeOffset|The time the contact was modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|manager|String|The name of the contact's manager.
|middleName|String|The contact's middle name.|
|mobilePhone|String|The contact's mobile phone number.|
|nickName|String|The contact's nickname.|
|officeLocation|String|The location of the contact's office.|
|otherAddress|PhysicalAddress|Other addresses for the contact.|
|parentFolderId|String|The ID of the contact's parent folder.|
|personalNotes|String|The user's notes about the contact.|
|profession|String|The contact's profession.|
|spouseName|String|The name of the contact's spouse/partner.|
|surname|String|The contact's surname.|
|title|String|The contact's title.|
|yomiCompanyName|String|The phonetic Japanese company name of the contact.|
|yomiGivenName|String|The phonetic Japanese given name (first name) of the contact.|
|yomiSurname|String|The phonetic Japanese surname (last name)  of the contact.|
### [contactFolder ](https://docs.microsoft.com/graph/api/resources/contactfolder?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|displayName|String|The folder's display name.|
|id|String|Unique identifier of the contact folder. Read-only.|
|parentFolderId|String|The ID of the folder's parent folder.|
### [emailAddress ](https://docs.microsoft.com/graph/api/resources/emailaddress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|address|String|The email address of the person or entity.|
|name|String|The display name of the person or entity.|
### [mailFolder ](https://docs.microsoft.com/graph/api/resources/mailfolder?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------|:-----|:------------|
|childFolderCount|Int32|The number of immediate child mailFolders in the current mailFolder.|
|displayName|String|The mailFolder's display name.|
|id|String|The mailFolder's unique identifier.|
|isHidden|Boolean|Indicates whether the mailFolder is hidden. This property can be set only when creating the folder. Find more information in Hidden mail folders.|
|parentFolderId|String|The unique identifier for the mailFolder's parent mailFolder.|
|totalItemCount|Int32|The number of items in the mailFolder.|
|unreadItemCount|Int32|The number of items in the mailFolder marked as unread.|
### [phone ](https://docs.microsoft.com/graph/api/resources/phone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|number|string|The phone number.|
|type|phoneType|The type of phone number. The possible values are: `home`, `business`, `mobile`, `other`, `assistant`, `homeFax`, `businessFax`, `otherFax`, `pager`, `radio`.|
### [physicalAddress ](https://docs.microsoft.com/graph/api/resources/physicaladdress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|city|String|The city.|
|countryOrRegion|String|The country or region. It's a free-format string value, for example, "United States".|
|postalCode|String|The postal code.|
|state|String|The state.|
|street|String|The street.|
### [profilePhoto ](https://docs.microsoft.com/graph/api/resources/profilephoto?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|Read-only.|
|height|int32|The height of the photo. Read-only.|
|width|int32|The width of the photo. Read-only.|
### [typedEmailAddress ](https://docs.microsoft.com/graph/api/resources/typedemailaddress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|address|String|The email address of a contact.|
|name|String|The display name of a contact.|
|type |String |The type of email address. Possible values are: `unknown`, `work`, `personal`, `main`, `other`. The default value is `unknown`, which means **address** has not been set as a specific type. |
|otherLabel |String  |To specify a custom type of email address, set **t
### [website ](https://docs.microsoft.com/graph/api/resources/website?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|address|string|The URL of the website.|
|displayName|string|The display name of the web site.|
|type|websiteType| The possible values are: `other`, `home`, `work`, `blog`, `profile`.|
