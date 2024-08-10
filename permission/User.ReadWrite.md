# User.ReadWrite

> Allows the app to read your profile. It also allows the app to update your profile information on your behalf.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /me/profile](https://docs.microsoft.com/graph/api/profile-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/account/{id}](https://docs.microsoft.com/graph/api/useraccountinformation-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/addresses/{id}](https://docs.microsoft.com/graph/api/itemaddress-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/anniversaries/{id}](https://docs.microsoft.com/graph/api/personanniversary-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/awards/{id}](https://docs.microsoft.com/graph/api/personaward-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/certifications/{id}](https://docs.microsoft.com/graph/api/personcertification-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/educationalActivities/{id} ](https://docs.microsoft.com/graph/api/educationalactivity-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/emails/{id}](https://docs.microsoft.com/graph/api/itememail-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/interests/{id}](https://docs.microsoft.com/graph/api/personinterest-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/languages/{id}](https://docs.microsoft.com/graph/api/languageproficiency-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/names/{id}](https://docs.microsoft.com/graph/api/personname-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/notes/{id}](https://docs.microsoft.com/graph/api/personannotation-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/patents/{id}](https://docs.microsoft.com/graph/api/itempatent-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/phones/{itemPhoneId}](https://docs.microsoft.com/graph/api/itemphone-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/positions/{id}](https://docs.microsoft.com/graph/api/workposition-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/projects/{id}](https://docs.microsoft.com/graph/api/projectparticipation-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/publications/{id}](https://docs.microsoft.com/graph/api/itempublication-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/skills/{id}](https://docs.microsoft.com/graph/api/skillproficiency-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/webAccounts/{id}](https://docs.microsoft.com/graph/api/webaccount-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/profile/websites/{id}](https://docs.microsoft.com/graph/api/personwebsite-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /me/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile](https://docs.microsoft.com/graph/api/profile-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/account/{id}](https://docs.microsoft.com/graph/api/useraccountinformation-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/addresses/{id}](https://docs.microsoft.com/graph/api/itemaddress-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/anniversaries/{id}](https://docs.microsoft.com/graph/api/personanniversary-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/awards/{id}](https://docs.microsoft.com/graph/api/personaward-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/certifications/{id}](https://docs.microsoft.com/graph/api/personcertification-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/educationalActivities/{id}](https://docs.microsoft.com/graph/api/educationalactivity-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/emails/{id}](https://docs.microsoft.com/graph/api/itememail-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/interests/{id}](https://docs.microsoft.com/graph/api/personinterest-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/languages/{id}](https://docs.microsoft.com/graph/api/languageproficiency-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/names/{id}](https://docs.microsoft.com/graph/api/personname-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/notes/{id}](https://docs.microsoft.com/graph/api/personannotation-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/patents/{id}](https://docs.microsoft.com/graph/api/itempatent-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/positions/{id}](https://docs.microsoft.com/graph/api/workposition-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/projects/{id}](https://docs.microsoft.com/graph/api/projectparticipation-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/publications/{id}](https://docs.microsoft.com/graph/api/itempublication-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/skills/{id}](https://docs.microsoft.com/graph/api/skillproficiency-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/webAccounts/{id}](https://docs.microsoft.com/graph/api/webaccount-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/profile/websites/{id}](https://docs.microsoft.com/graph/api/personwebsite-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{id | userPrincipalName}/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /users/{userId}/profile/phones/{itemPhoneId}](https://docs.microsoft.com/graph/api/itemphone-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /groups/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me](https://docs.microsoft.com/graph/api/user-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/createdObjects](https://docs.microsoft.com/graph/api/user-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/profile](https://docs.microsoft.com/graph/api/profile-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/account](https://docs.microsoft.com/graph/api/profile-list-accounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/account/{id}](https://docs.microsoft.com/graph/api/useraccountinformation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/addresses](https://docs.microsoft.com/graph/api/profile-list-addresses?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/addresses/{id}](https://docs.microsoft.com/graph/api/itemaddress-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/anniversaries](https://docs.microsoft.com/graph/api/profile-list-anniversaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/anniversaries/{id}](https://docs.microsoft.com/graph/api/personanniversary-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/awards](https://docs.microsoft.com/graph/api/profile-list-awards?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/awards/{id}](https://docs.microsoft.com/graph/api/personaward-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/certifications](https://docs.microsoft.com/graph/api/profile-list-certifications?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/certifications/{id}](https://docs.microsoft.com/graph/api/personcertification-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/educationalActivities](https://docs.microsoft.com/graph/api/profile-list-educationalactivities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/educationalActivities/{id}](https://docs.microsoft.com/graph/api/educationalactivity-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/emails](https://docs.microsoft.com/graph/api/profile-list-emails?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/emails/{id}](https://docs.microsoft.com/graph/api/itememail-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/interests](https://docs.microsoft.com/graph/api/profile-list-interests?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/interests/{id}](https://docs.microsoft.com/graph/api/personinterest-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/languages](https://docs.microsoft.com/graph/api/profile-list-languages?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/languages/{id}](https://docs.microsoft.com/graph/api/languageproficiency-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/names](https://docs.microsoft.com/graph/api/profile-list-names?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/names/{id}](https://docs.microsoft.com/graph/api/personname-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/notes](https://docs.microsoft.com/graph/api/profile-list-notes?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/notes/{id}](https://docs.microsoft.com/graph/api/personannotation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/patents](https://docs.microsoft.com/graph/api/profile-list-patents?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/patents/{id}](https://docs.microsoft.com/graph/api/itempatent-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/phones](https://docs.microsoft.com/graph/api/profile-list-phones?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/phones/{id}](https://docs.microsoft.com/graph/api/itemphone-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/positions](https://docs.microsoft.com/graph/api/profile-list-positions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/positions/{id}](https://docs.microsoft.com/graph/api/workposition-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/projects](https://docs.microsoft.com/graph/api/profile-list-projects?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/projects/{id}](https://docs.microsoft.com/graph/api/projectparticipation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/publications](https://docs.microsoft.com/graph/api/profile-list-publications?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/publications/{id}](https://docs.microsoft.com/graph/api/itempublication-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/skills](https://docs.microsoft.com/graph/api/profile-list-skills?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/skills/{id}](https://docs.microsoft.com/graph/api/skillproficiency-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/webAccounts](https://docs.microsoft.com/graph/api/profile-list-webaccounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/webAccounts/{id}](https://docs.microsoft.com/graph/api/webaccount-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/websites](https://docs.microsoft.com/graph/api/profile-list-websites?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/profile/websites/{id}](https://docs.microsoft.com/graph/api/personwebsite-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/responsibilities](https://docs.microsoft.com/graph/api/profile-list-responsibilities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/settings/contactMergeSuggestions](https://docs.microsoft.com/graph/api/contactmergesuggestions-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/settings/itemInsights](https://docs.microsoft.com/graph/api/userinsightssettings-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /team/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/createdObjects](https://docs.microsoft.com/graph/api/user-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile](https://docs.microsoft.com/graph/api/profile-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/account](https://docs.microsoft.com/graph/api/profile-list-accounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/account/{id}](https://docs.microsoft.com/graph/api/useraccountinformation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/addresses](https://docs.microsoft.com/graph/api/profile-list-addresses?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/addresses/{id}](https://docs.microsoft.com/graph/api/itemaddress-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/anniversaries](https://docs.microsoft.com/graph/api/profile-list-anniversaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/anniversaries/{id}](https://docs.microsoft.com/graph/api/personanniversary-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/awards](https://docs.microsoft.com/graph/api/profile-list-awards?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/awards/{id}](https://docs.microsoft.com/graph/api/personaward-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/certifications](https://docs.microsoft.com/graph/api/profile-list-certifications?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/certifications/{id}](https://docs.microsoft.com/graph/api/personcertification-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/educationalActivities](https://docs.microsoft.com/graph/api/profile-list-educationalactivities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/educationalActivities/{id}](https://docs.microsoft.com/graph/api/educationalactivity-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/emails](https://docs.microsoft.com/graph/api/profile-list-emails?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/emails/{id}](https://docs.microsoft.com/graph/api/itememail-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/interests](https://docs.microsoft.com/graph/api/profile-list-interests?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/interests/{id}](https://docs.microsoft.com/graph/api/personinterest-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/languages](https://docs.microsoft.com/graph/api/profile-list-languages?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/languages/{id}](https://docs.microsoft.com/graph/api/languageproficiency-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/names](https://docs.microsoft.com/graph/api/profile-list-names?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/names/{id}](https://docs.microsoft.com/graph/api/personname-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/notes](https://docs.microsoft.com/graph/api/profile-list-notes?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/notes/{id}](https://docs.microsoft.com/graph/api/personannotation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/patents](https://docs.microsoft.com/graph/api/profile-list-patents?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/patents/{id}](https://docs.microsoft.com/graph/api/itempatent-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/phones](https://docs.microsoft.com/graph/api/profile-list-phones?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/positions](https://docs.microsoft.com/graph/api/profile-list-positions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/positions/{id}](https://docs.microsoft.com/graph/api/workposition-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/projects](https://docs.microsoft.com/graph/api/profile-list-projects?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/projects/{id}](https://docs.microsoft.com/graph/api/projectparticipation-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/publications](https://docs.microsoft.com/graph/api/profile-list-publications?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/publications/{id}](https://docs.microsoft.com/graph/api/itempublication-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/skills](https://docs.microsoft.com/graph/api/profile-list-skills?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/skills/{id}](https://docs.microsoft.com/graph/api/skillproficiency-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/webAccounts](https://docs.microsoft.com/graph/api/profile-list-webaccounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/webAccounts/{id}](https://docs.microsoft.com/graph/api/webaccount-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/websites](https://docs.microsoft.com/graph/api/profile-list-websites?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/profile/websites/{id}](https://docs.microsoft.com/graph/api/personwebsite-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/responsibilities](https://docs.microsoft.com/graph/api/profile-list-responsibilities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId}/profile/phones/{id}](https://docs.microsoft.com/graph/api/itemphone-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{userId}/settings/itemInsights](https://docs.microsoft.com/graph/api/userinsightssettings-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId}/usageRights](https://docs.microsoft.com/graph/api/user-list-usagerights?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/profile/account/{id}](https://docs.microsoft.com/graph/api/useraccountinformation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/addresses/{id}](https://docs.microsoft.com/graph/api/itemaddress-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/anniversaries/{id}](https://docs.microsoft.com/graph/api/personanniversary-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/awards/{id}](https://docs.microsoft.com/graph/api/personaward-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/certifications/{id}](https://docs.microsoft.com/graph/api/personcertification-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/educationalActivities/{id}](https://docs.microsoft.com/graph/api/educationalactivity-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/emails/{id}](https://docs.microsoft.com/graph/api/itememail-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/interests/{id}](https://docs.microsoft.com/graph/api/personinterest-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/languages/{id}](https://docs.microsoft.com/graph/api/languageproficiency-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/names/{id}](https://docs.microsoft.com/graph/api/personname-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/notes/{id}](https://docs.microsoft.com/graph/api/personannotation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/patents/{id}](https://docs.microsoft.com/graph/api/itempatent-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/phones/{id}](https://docs.microsoft.com/graph/api/itemphone-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/positions/{id}](https://docs.microsoft.com/graph/api/workposition-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/projects/{id}](https://docs.microsoft.com/graph/api/projectparticipation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/publications/{id}](https://docs.microsoft.com/graph/api/itempublication-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/skills/{id}](https://docs.microsoft.com/graph/api/skillproficiency-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/webAccounts/{id}](https://docs.microsoft.com/graph/api/webaccount-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/profile/websites/{id}](https://docs.microsoft.com/graph/api/personwebsite-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /me/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/settings](https://docs.microsoft.com/graph/api/usersettings-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/settings/contactMergeSuggestions](https://docs.microsoft.com/graph/api/contactmergesuggestions-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/settings/itemInsights](https://docs.microsoft.com/graph/api/userinsightssettings-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/account/{id}](https://docs.microsoft.com/graph/api/useraccountinformation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/addresses/{id}](https://docs.microsoft.com/graph/api/itemaddress-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/anniversaries/{id}](https://docs.microsoft.com/graph/api/personanniversary-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/awards/{id}](https://docs.microsoft.com/graph/api/personaward-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/certifications/{id}](https://docs.microsoft.com/graph/api/personcertification-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/educationalActivities/{id}](https://docs.microsoft.com/graph/api/educationalactivity-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/emails/{id}](https://docs.microsoft.com/graph/api/itememail-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/interests/{id}](https://docs.microsoft.com/graph/api/personinterest-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/languages/{id}](https://docs.microsoft.com/graph/api/languageproficiency-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/names/{id}](https://docs.microsoft.com/graph/api/personname-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/notes/{id}](https://docs.microsoft.com/graph/api/personannotation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/patents/{id}](https://docs.microsoft.com/graph/api/itempatent-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/positions/{id}](https://docs.microsoft.com/graph/api/workposition-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/projects/{id}](https://docs.microsoft.com/graph/api/projectparticipation-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/publications/{id}](https://docs.microsoft.com/graph/api/itempublication-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/skills/{id}](https://docs.microsoft.com/graph/api/skillproficiency-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/webAccounts/{id}](https://docs.microsoft.com/graph/api/webaccount-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/profile/websites/{id}](https://docs.microsoft.com/graph/api/personwebsite-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{id | userPrincipalName}/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /users/{userId}/profile/phones/{id}](https://docs.microsoft.com/graph/api/itemphone-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /users/{userId}/settings/itemInsights](https://docs.microsoft.com/graph/api/userinsightssettings-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/invalidateAllRefreshTokens](https://docs.microsoft.com/graph/api/user-invalidateallrefreshtokens?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/account](https://docs.microsoft.com/graph/api/profile-post-accounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/addresses](https://docs.microsoft.com/graph/api/profile-post-addresses?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/anniversaries](https://docs.microsoft.com/graph/api/profile-post-anniversaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/awards](https://docs.microsoft.com/graph/api/profile-post-awards?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/certifications](https://docs.microsoft.com/graph/api/profile-post-certifications?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/educationalActivities](https://docs.microsoft.com/graph/api/profile-post-educationalactivities?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/emails](https://docs.microsoft.com/graph/api/profile-post-emails?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/interests](https://docs.microsoft.com/graph/api/profile-post-interests?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/languages](https://docs.microsoft.com/graph/api/profile-post-languages?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/names](https://docs.microsoft.com/graph/api/profile-post-names?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/notes](https://docs.microsoft.com/graph/api/profile-post-notes?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/patents](https://docs.microsoft.com/graph/api/profile-post-patents?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/phones](https://docs.microsoft.com/graph/api/profile-post-phones?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/positions](https://docs.microsoft.com/graph/api/profile-post-positions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/projects](https://docs.microsoft.com/graph/api/profile-post-projects?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/publications](https://docs.microsoft.com/graph/api/profile-post-publications?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/skills](https://docs.microsoft.com/graph/api/profile-post-skills?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/webAccounts](https://docs.microsoft.com/graph/api/profile-post-webaccounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/profile/websites](https://docs.microsoft.com/graph/api/profile-post-websites?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/responsibilities](https://docs.microsoft.com/graph/api/profile-post-responsibilities?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/translateExchangeIds](https://docs.microsoft.com/graph/api/user-translateexchangeids?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/invalidateAllRefreshTokens](https://docs.microsoft.com/graph/api/user-invalidateallrefreshtokens?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/account](https://docs.microsoft.com/graph/api/profile-post-accounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/addresses](https://docs.microsoft.com/graph/api/profile-post-addresses?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/anniversaries](https://docs.microsoft.com/graph/api/profile-post-anniversaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/awards](https://docs.microsoft.com/graph/api/profile-post-awards?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/certifications](https://docs.microsoft.com/graph/api/profile-post-certifications?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/educationalActivities](https://docs.microsoft.com/graph/api/profile-post-educationalactivities?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/emails](https://docs.microsoft.com/graph/api/profile-post-emails?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/interests](https://docs.microsoft.com/graph/api/profile-post-interests?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/languages](https://docs.microsoft.com/graph/api/profile-post-languages?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/names](https://docs.microsoft.com/graph/api/profile-post-names?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/notes](https://docs.microsoft.com/graph/api/profile-post-notes?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/patents](https://docs.microsoft.com/graph/api/profile-post-patents?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/positions](https://docs.microsoft.com/graph/api/profile-post-positions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/projects](https://docs.microsoft.com/graph/api/profile-post-projects?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/publications](https://docs.microsoft.com/graph/api/profile-post-publications?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/skills](https://docs.microsoft.com/graph/api/profile-post-skills?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/webAccounts](https://docs.microsoft.com/graph/api/profile-post-webaccounts?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/profile/websites](https://docs.microsoft.com/graph/api/profile-post-websites?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/responsibilities](https://docs.microsoft.com/graph/api/profile-post-responsibilities?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/user-retryserviceprovisioning?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/translateExchangeIds](https://docs.microsoft.com/graph/api/user-translateexchangeids?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{userId}/profile/phones](https://docs.microsoft.com/graph/api/profile-post-phones?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/validatePassword](https://docs.microsoft.com/graph/api/user-validatepassword?view=graph-rest-beta&tabs=http)|
|V1|D|[PUT /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /me/settings/regionalAndLanguageSettings](https://docs.microsoft.com/graph/api/regionalandlanguagesettings-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PUT /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /users/{user-id | userPrincipalName}/settings/regionalAndLanguageSettings](https://docs.microsoft.com/graph/api/regionalandlanguagesettings-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b4e74841-8e56-480b-be8b-910348b18b4c|
|**Consent Type**|User|
|**Display String**|Read and write access to user profile|
|**Description**|Allows the app to read your profile. It also allows the app to update your profile information on your behalf.|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [assignedLicense ](https://docs.microsoft.com/graph/api/resources/assignedlicense?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|disabledPlans|Guid collection|A collection of the unique identifiers for plans that have been disabled. IDs are available in **servicePlans** > **servicePlanId** in the tenant's subscribedSkus or **serviceStatus** > **servicePlanId** in the tenant's companySubscription. |
|skuId|Guid|The unique identifier for the SKU. Corresponds to the **s
### [companyDetail ](https://docs.microsoft.com/graph/api/resources/companydetail?view=graph-rest-1.0&tabs=http)
| Property       | Type                                | Description                                            |
|:---------------|:------------------------------------|:-------------------------------------------------------|
|address         |physicalAddress| Address of the company.                                |
|companyCode     |String                               | Legal entity number of the company or its subdivision. For information on how to set the value for the **companyCode**, see profileSourceAnnotation.|
|department      |String                               | Department Name within a company.                      |
|displayName     |String                               | Company name.                                          |
|officeLocation  |String                               | Office Location of the person referred to.             |
|pronunciation   |String                               | Pronunciation guide for the company name.              |
|webUrl          |String                               | Link to the company home page.                         |
### [contactMergeSuggestions ](https://docs.microsoft.com/graph/api/resources/contactmergesuggestions?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabled|Boolean|`true` if the duplicate contact merge suggestions feature is enabled for the user; `false` if the feature is disabled. Default value is `true`.|
### [convertIdResult ](https://docs.microsoft.com/graph/api/resources/convertidresult?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------|:-----|:------------|
| errorDetails | genericError | An error object indicating the reason for the conversion failure. This value isn't present if the conversion succeeded. |
| sourceId | String | The identifier that was converted. This value is the original, un-converted identifier. |
| targetId | String | The converted identifier. This value isn't present if the conversion failed. |
### [customSecurityAttributeValue ](https://docs.microsoft.com/graph/api/resources/customsecurityattributevalue?view=graph-rest-1.0&tabs=http)

### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [educationalActivity ](https://docs.microsoft.com/graph/api/resources/educationalactivity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|completionMonthYear|Date|The month and year the user graduated or completed the activity. |
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|endMonthYear|Date|The month and year the user completed the educational activity referenced.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|institution|institutionData|Contains details of the institution studied at. |
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|program|educationalActivityDetail|Contains extended information about the program or course.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|startMonthYear|Date|The month and year the user commenced the activity referenced.|
### [educationalActivityDetail ](https://docs.microsoft.com/graph/api/resources/educationalactivitydetail?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description                                                   |
|:-------------|:------------|:--------------------------------------------------------------|
|abbreviation  |String       |Shortened name of the degree or program (example: PhD, MBA)    |
|activities    |String       |Extracurricular activities undertaken alongside the program.   |
|awards        |String       |Any awards or honors associated with the program.              |
|description   |String       |Short description of the program provided by the user.         |
|displayName   |String       |Long-form name of the program that the user has provided.      |
|fieldsOfStudy |String       |Majors and minors associated with the program. (if applicable) |
|grade         |String       |The final grade, class, GPA or score.                          |
|notes         |String       |Additional notes the user has provided.                        |
|webUrl        |String       |Link to the degree or program page.                            |
### [employeeOrgData ](https://docs.microsoft.com/graph/api/resources/employeeorgdata?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
| division | String | The name of the division in which the user works. <br><br>Returned only on `$select`. Supports `$filter`. |
| costCenter | String | The cost center associated with the user. <br><br>Returned only on `$select`. Supports `$filter`. |
### [entity ](https://docs.microsoft.com/graph/api/resources/entity?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| The unique identifier for an entity. Read-only.|
### [GeoCoordinates ](https://docs.microsoft.com/graph/api/resources/geocoordinates?view=graph-rest-1.0&tabs=http)
| Property  | Type   | Description
|:----------|:-------|:--------------------------------------------------------
| altitude  | Double | Optional. The altitude (height), in feet,  above sea level for the item. Read-only.
| latitude  | Double | Optional. The latitude, in decimal, for the item. Read-only.
| longitude | Double | Optional. The longitude, in decimal, for the item. Read-only.

### [identitySet ](https://docs.microsoft.com/graph/api/resources/identityset?view=graph-rest-1.0&tabs=http)
| Property    | Type                    | Description                                            |
|:------------|:------------------------|:-------------------------------------------------------|
| application | identity | Optional. The application associated with this action.  |
| applicationInstance | identity | Optional. The application instance associated with this action.  |
| conversation| identity | Optional. The team or channel associated with this action.       |
| conversationIdentityType| identity | Optional. Indicates whether the **conversation** property identifies a team or channel.|
| device      | identity | Optional. The device associated with this action.       |
| encrypted       | identity | Optional. The encrypted identity associated with this action. |
| onPremises       | identity | Optional. The on-premises identity associated with this action. |
| guest       | identity | Optional. The guest identity associated with this action. |
| phone       | identity | Optional. The phone number associated with this action. |
| user        | identity | Optional. The user associated with this action.         |
### [inferenceData ](https://docs.microsoft.com/graph/api/resources/inferencedata?view=graph-rest-1.0&tabs=http)
| Property              | Type        | Description                                                                     |
|:----------------------|:------------|:--------------------------------------------------------------------------------|
|confidenceScore        |Double       | Confidence score reflecting the accuracy of the data inferred about the user.   |
|userHasVerifiedAccuracy|Boolean      | Records if the user has confirmed this inference as being True or False.        |
### [institutionData ](https://docs.microsoft.com/graph/api/resources/institutiondata?view=graph-rest-1.0&tabs=http)
| Property     | Type                                 | Description                                              |
|:-------------|:-------------------------------------|:---------------------------------------------------------|
|description   |String                                |Short description of the institution the user studied at. |
|displayName   |String                                |Name of the institution the user studied at.              |
|location      |physicalAddress |Address or location of the institute.                     |
|webUrl        |String                                |Link to the institution or department homepage.           |
### [itemAddress ](https://docs.microsoft.com/graph/api/resources/itemaddress?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|detail|physicalAddress|Details about the address itself.|
|displayName|String|Friendly name the user has assigned to this address. |
|geoCoordinates|geoCoordinates|The geocoordinates of the address.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
### [itemBody ](https://docs.microsoft.com/graph/api/resources/itembody?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|content|String|The content of the item.|
|contentType|bodyType|The type of the content. Possible values are `text` and `html`.|
### [itemEmail ](https://docs.microsoft.com/graph/api/resources/itememail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|address|String|The email address itself.|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|displayName|String|The name or label a user has associated with a particular email address.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|type|emailType|The type of email address. Possible values are: `unknown`, `work`, `personal`, `main`, `other`.|
### [itemFacet ](https://docs.microsoft.com/graph/api/resources/itemfacet?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|allowedAudiences|The audiences that are able to see the values contained within the associated entity. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created.|
|id|String|Identifier used for individually addressing an entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created.|
|source|personDataSource|Where the values within an entity originated if synced from another service.|
|sources|profileSourceAnnotation collection|Where the values within an entity originated if synced from another source.|
### [itemInsights ](https://docs.microsoft.com/graph/api/resources/iteminsights?view=graph-rest-1.0&tabs=http)

### [itemPatent ](https://docs.microsoft.com/graph/api/resources/itempatent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description|String|Descpription of the patent or filing. |
|displayName|String|Title of the patent or filing. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|isPending        |Boolean     |Indicates the patent is pending.        |
|issuedDate       |Date        |The date that the patent was granted.   |
|issuingAuthority |String      |Authority which granted the patent.     |
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|number           |String      |The patent number.                      |
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|webUrl           |String      |URL referencing the patent or filing. |
### [itemPhone ](https://docs.microsoft.com/graph/api/resources/itemphone?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|displayName|String|Friendly name the user has assigned this phone number. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|number|String|Phone number provided by the user.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|type|phoneType|The type of phone number within the object. Possible values are: `home`, `business`, `mobile`, `other`, `assistant`, `homeFax`, `businessFax`, `otherFax`, `pager`, `radio`.|
### [itemPublication ](https://docs.microsoft.com/graph/api/resources/itempublication?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description    |String      |Description of the publication.                   |
|displayName    |String      |Title of the publication.                         |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|publishedDate  |Date        |The date that the publication was published.      |
|publisher      |String      |Publication or publisher for the publication.     |
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|thumbnailUrl   |String      |URL referencing a thumbnail of the publication.   |
|webUrl         |String      |URL referencing the publication.                  |
### [languageProficiency ](https://docs.microsoft.com/graph/api/resources/languageproficiency?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|displayName|String|Contains the long-form name for the language. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|reading|languageProficiencyLevel|Represents the users reading comprehension for the language represented by the object. Possible values are: `elementary`, `conversational`, `limitedWorking`, `professionalWorking`, `fullProfessional`, `nativeOrBilingual`, `unknownFutureValue`.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|spoken|languageProficiencyLevel|Represents the users spoken proficiency for the language represented by the object. Possible values are: `elementary`, `conversational`, `limitedWorking`, `professionalWorking`, `fullProfessional`, `nativeOrBilingual`, `unknownFutureValue`.|
|tag|String|Contains the four-character BCP47 name for the language (en-US, no-NB, en-AU).|
|written|languageProficiencyLevel|Represents the users written proficiency for the language represented by the object. Possible values are: `elementary`, `conversational`, `limitedWorking`, `professionalWorking`, `fullProfessional`, `nativeOrBilingual`, `unknownFutureValue`.|
### [localeInfo ](https://docs.microsoft.com/graph/api/resources/localeinfo?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|displayName|string|A name representing the user's locale in natural language, for example, "English (United States)".|
|locale|string|A locale representation for the user, which includes the user's preferred language and country/region. For example, "en-us". The language component follows 2-letter codes as defined in ISO 639-1, and the country component follows 2-letter codes as defined in ISO 3166-1 alpha-2.|
### [objectIdentity ](https://docs.microsoft.com/graph/api/resources/objectidentity?view=graph-rest-1.0&tabs=http)
| Property       | Type    | Description |
|:---------------|:--------|:------------|
|signInType|String|Specifies the user sign-in types in your directory, such as `emailAddress`, `userName`, `federated`, or `userPrincipalName`. `federated` represents a unique identifier for a user from an issuer that can be in any format chosen by the issuer. Setting or updating a `userPrincipalName` identity updates the value of the **userPrincipalName** property on the user object. The validations performed on the `userPrincipalName` property on the user object, for example, verified domains and acceptable characters, are performed when setting or updating a `userPrincipalName` identity. Extra validation is enforced on **issuerAssignedId** when the sign-in type is set to `emailAddress` or `userName`. This property can also be set to any custom string. <br> For more information about filtering behavior for this property, see Filtering on the identities property of a user.|
|issuer|String|Specifies the issuer of the identity, for example `facebook.com`. 512 character limit. <br><br>For local accounts (where **signInType** isn't `federated`), this property is the local default domain name for the tenant, for example `contoso.com`. <br> For guests from other Microsoft Entra organizations, this is the domain of the federated organization, for example `contoso.com`. For more information about filtering behavior for this property, see Filtering on the identities property of a user.|
|issuerAssignedId|String|Specifies the unique identifier assigned to the user by the issuer. 64 character limit. The combination of **i
### [onPremisesExtensionAttributes ](https://docs.microsoft.com/graph/api/resources/onpremisesextensionattributes?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|extensionAttribute1|String| First customizable extension attribute. |
|extensionAttribute2|String| Second customizable extension attribute. |
|extensionAttribute3|String| Third customizable extension attribute. |
|extensionAttribute4|String| Fourth customizable extension attribute. |
|extensionAttribute5|String| Fifth customizable extension attribute. |
|extensionAttribute6|String| Sixth customizable extension attribute. |
|extensionAttribute7|String| Seventh customizable extension attribute. |
|extensionAttribute8|String| Eighth customizable extension attribute. |
|extensionAttribute9|String| Ninth customizable extension attribute. |
|extensionAttribute10|String| Tenth customizable extension attribute. |
|extensionAttribute11|String| Eleventh customizable extension attribute. |
|extensionAttribute12|String| Twelfth customizable extension attribute. |
|extensionAttribute13|String| Thirteenth customizable extension attribute. |
|extensionAttribute14|String| Fourteenth customizable extension attribute. |
|extensionAttribute15|String| Fifteenth customizable extension attribute. |
### [organization ](https://docs.microsoft.com/graph/api/resources/organization?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-------- |:---- |:----------- |
| assignedPlans | assignedPlan collection | The collection of service plans associated with the tenant. Not nullable. |
| businessPhones | String collection | Telephone number for the organization. Although this property is a string collection, only one number can be set. |
| city | String | City name of the address for the organization. |
| country | String | Country or region name of the address for the organization. |
| countryLetterCode | String | Country or region abbreviation for the organization in ISO 3166-2 format. |
| createdDateTime | DateTimeOffset | Timestamp of when the organization was created. The value can't be modified and is automatically populated when the organization is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| defaultUsageLocation | String | Two-letter ISO 3166 country code indicating the default service usage location of an organization. |
| deletedDateTime | DateTimeOffset | Represents date and time of when the Microsoft Entra tenant was deleted using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| displayName | String | The display name for the tenant. |
| id | String | The tenant ID, a unique identifier representing the organization (or tenant). Inherited from directoryObject. Key. Not nullable. Read-only. |
| isMultipleDataLocationsForServicesEnabled | Boolean | `true` if organization is Multi-Geo enabled; **false** if the organization isn't Multi-Geo enabled; **null** (default). Read-only. For more information, see OneDrive Online Multi-Geo. |
| marketingNotificationEmails | String collection | Not nullable. |
| onPremisesLastSyncDateTime | DateTimeOffset | The time and date at which the tenant was last synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
| onPremisesSyncEnabled | Boolean | `true` if this object is synced from an on-premises directory; `false` if this object was originally synced from an on-premises directory but is no longer synced. Nullable. `null` if this object isn't synced from on-premises active directory (default). |
| partnerTenantType | partnerTenantType | The type of partnership this tenant has with Microsoft. The possible values are: `microsoftSupport`, `syndicatePartner`, `breadthPartner`, `breadthPartnerDelegatedAdmin`, `resellerPartnerDelegatedAdmin`, `valueAddedResellerPartnerDelegatedAdmin`, `unknownFutureValue`. Nullable. For more information about the possible types, see partnerTenantType values.|
| postalCode | String | Postal code of the address for the organization. |
| preferredLanguage | String | The preferred language for the organization. Should follow ISO 639-1 Code; for example, `en`. |
| privacyProfile | privacyProfile | The privacy profile of an organization. |
| provisionedPlans | ProvisionedPlan collection | Not nullable. |
| securityComplianceNotificationMails | String collection | Not nullable.|
| securityComplianceNotificationPhones | String collection| Not nullable.|
| state | String | State name of the address for the organization. |
| street | String | Street name of the address for organization. |
| technicalNotificationMails | String collection | Not nullable. |
| tenantType | String | Not nullable. Can be one of the following types: <li> `AAD` - An enterprise identity access management (IAM) service that serves business-to-employee and business-to-business (B2B) scenarios. <li> `AAD B2C` An identity access management (IAM) service that serves business-to-consumer (B2C) scenarios.  <li> `CIAM` - A customer identity & access management (CIAM) solution that provides an integrated platform to serve consumers, partners, and citizen scenarios. |
| verifiedDomains | VerifiedDomain collection | The collection of domains associated with this tenant. Not nullable. |
### [passwordProfile ](https://docs.microsoft.com/graph/api/resources/passwordprofile?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|forceChangePasswordNextSignIn|Boolean| `true` if the user must change their password on the next sign-in; otherwise `false`.|
|forceChangePasswordNextSignInWithMfa|Boolean| If `true`, at next sign-in, the user must perform a multifactor authentication (MFA) before being forced to change their password. The behavior is identical to **forceChangePasswordNextSignIn** except that the user is required to first perform a multifactor authentication before password change. After a password change, this property will be automatically reset to `false`. If not set, default is `false`. |
|password|String|The password for the user. This property is required when a user is created. It can be updated, but the user will be required to change the password on the next sign-in. The password must satisfy minimum requirements as specified by the user's **p
### [passwordValidationInformation ](https://docs.microsoft.com/graph/api/resources/passwordvalidationinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isValid|Boolean| Specifies whether the password is valid based on the calculation of the results in the **validationResults** property. Not nullable. Read-only. |
|validationResults|validationResult collection| The list of password validation rules and whether the password passed those rules. Not nullable. Read-only. |
### [personAnniversary ](https://docs.microsoft.com/graph/api/resources/personanniversary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|date|Date|Contains the date associated with the anniversary type.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|type|anniversaryType|The type of anniversary the date represents. Possible values are: `birthday`, `wedding`, `unknownFutureValue`.|
### [personAnnotation ](https://docs.microsoft.com/graph/api/resources/personannotation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|detail|itemBody|Contains the detail of the note itself.|
|displayName|String|Contains a friendly name for the note.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
### [personAward ](https://docs.microsoft.com/graph/api/resources/personaward?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description|String|Descpription of the award or honor. |
|displayName|String|Name of the award or honor. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|issuedDate|Date|The date that the award or honor was granted. |
|issuingAuthority|String|Authority which granted the award or honor.  |
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|thumbnailUrl|String|URL referencing a thumbnail of the award or honor.  |
|webUrl|String|URL referencing the award or honor. |
### [personCertification ](https://docs.microsoft.com/graph/api/resources/personcertification?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|certificationId  |String      |The referenceable identifier for the certification. |
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description      |String      |Description of the certification.                   |
|displayName      |String      |Title of the certification.                         |
|endDate          |Date        |The date that the certification expires.            |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|issuedDate       |Date        |The date that the certification was issued.         |
|issuingAuthority |String      |Authority which granted the certification.          |
|issuingCompany   |String      |Company which granted the certification.          |
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|startDate        |Date        |The date that the certification became valid.       |
|thumbnailUrl     |String      |URL referencing a thumbnail of the certification.   |
|webUrl           |String      |URL referencing the certification.                  |
### [personDataSource ](https://docs.microsoft.com/graph/api/resources/persondatasource?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|type|String|The type of data source.|
### [personInterest ](https://docs.microsoft.com/graph/api/resources/personinterest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|categories|String collection|Contains categories a user has associated with the interest (for example, personal, recipies). |
|collaborationTags|String collection|Contains experience scenario tags a user has associated with the interest. Allowed values in the collection are: `askMeAbout`, `ableToMentor`, `wantsToLearn`, `wantsToImprove`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description|String|Contains a description of the interest.|
|displayName|String|Contains a friendly name for the interest.  |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|webUrl|String|Contains a link to a web page or resource about the interest. |
### [personName ](https://docs.microsoft.com/graph/api/resources/personname?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|displayName|String|Provides an ordered rendering of firstName and lastName depending on the locale of the user or their device.|
|first|String|First name of the user.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|initials|String|Initials of the user.|
|languageTag|String|Contains the name for the language (en-US, no-NB, en-AU) following IETF BCP47 format.   |
|last|String|Last name of the user.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|maiden|String|Maiden name of the user. |
|middle|String|Middle name of the user.|
|nickname|String|Nickname of the user.|
|pronunciation|yomiPersonName|Guidance on how to pronounce the users name.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|suffix|String|Designators used after the users name (eg: PhD.)  |
|title|String|Honorifics used to prefix a users name (eg: Dr, Sir, Madam, Mrs.)|
### [personResponsibility ](https://docs.microsoft.com/graph/api/resources/personresponsibility?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|collaborationTags|String collection|Contains experience scenario tags a user has associated with the interest. Allowed values in the collection are: `askMeAbout`, `ableToMentor`, `wantsToLearn`, `wantsToImprove`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description|String|Description of the responsibility.|
|displayName|String|Contains a friendly name for the responsibility. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|webUrl|String|Contains a link to a web page or resource about the responsibility.|
### [personWebsite ](https://docs.microsoft.com/graph/api/resources/personwebsite?view=graph-rest-1.0&tabs=http)
| Property     | Type              | Description                                                                                   |
|:-------------|:------------------|:----------------------------------------------------------------------------------------------|
|categories    |String collection  | Contains categories a user has associated with the website (for example, personal, recipes).  |
|description   |String             | Contains a description of the website.                                                        |
|displayName   |String             | Contains a friendly name for the website.                                                     |
|webUrl        |String             | Contains a link to the website itself.                                                        |
### [physicalAddress ](https://docs.microsoft.com/graph/api/resources/physicaladdress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|city|String|The city.|
|countryOrRegion|String|The country or region. It's a free-format string value, for example, "United States".|
|postalCode|String|The postal code.|
|state|String|The state.|
|street|String|The street.|
### [positionDetail ](https://docs.microsoft.com/graph/api/resources/positiondetail?view=graph-rest-1.0&tabs=http)
| Property       | Type                             | Description                                                           |
|:---------------|:---------------------------------|:----------------------------------------------------------------------|
|company         |companyDetail | Detail about the company or employer.                                 |
|description     |String                            | Description of the position in question.                              |
|endMonthYear    |Date                              | When the position ended.                                              |
|jobTitle        |String                            | The title held when in that position.                                 |
|layer           |Int32                             | The place where the employee is within the organizational hierarchy.      |
|level           |String                            | The employee’s experience or management level.                        |
|role            |String                            | The role the position entailed.                                       |
|startMonthYear  |Date                              | The start month and year of the position.                             |
|summary         |String                            | summary of the position.                                         |
### [profile ](https://docs.microsoft.com/graph/api/resources/profile?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id            |String       | Read-only.  |
### [profilePhoto ](https://docs.microsoft.com/graph/api/resources/profilephoto?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|Read-only.|
|height|int32|The height of the photo. Read-only.|
|width|int32|The width of the photo. Read-only.|
### [projectParticipation ](https://docs.microsoft.com/graph/api/resources/projectparticipation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|categories|String collection|Contains categories a user has associated with the project (for example, digital transformation, oil rig). |
|client|companyDetail|Contains detailed information about the client the project was for. |
|collaborationTags|String collection|Contains experience scenario tags a user has associated with the interest. Allowed values in the collection are: `askMeAbout`, `ableToMentor`, `wantsToLearn`, `wantsToImprove`.|
|colleagues|relatedPerson collection|Lists people that also worked on the project. |
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|detail|positionDetail|Contains detail about the user's role on the project.|
|displayName|String|Contains a friendly name for the project.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|sponsors|relatedPerson collection|The Person or people who sponsored the project.    |
### [regionalAndLanguageSettings ](https://docs.microsoft.com/graph/api/resources/regionalandlanguagesettings?view=graph-rest-1.0&tabs=http)
| Property                   | Type                                                  | Description                                                                                                                                                         |
|----------------------------|-------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| defaultDisplayLanguage     | localeInfo                           | The  user's preferred user interface language (menus, buttons, ribbons, warning messages) for Microsoft web applications.<br><br>Returned by default. Not nullable. |
| authoringLanguages         | localeInfo collection                                 | Prioritized list of languages the user reads and authors in.<br><br>Returned by default. Not nullable.                                                              |
| defaultTranslationLanguage | localeInfo                 | The language a user expects to have documents, emails, and messages translated into.<br><br>Returned by default.                                                    |
| defaultSpeechInputLanguage | localeInfo                 | The language a user expected to use as input for text to speech scenarios.<br><br>Returned by default.                                                              |
| defaultRegionalFormat      | localeInfo            | The locale that drives the default date, time, and calendar formatting.<br><br>Returned by default.                                                                 |
| regionalFormatOverrides    | regionalFormatOverrides | Allows a user to override their defaultRegionalFormat with field specific formats.<br><br>Returned by default.                                                      |
| translationPreferences     | translationPreferences   | The user's preferred settings when consuming translated documents, emails, messages, and websites.<br><br>Returned by default. Not nullable.                                       |
### [relatedPerson ](https://docs.microsoft.com/graph/api/resources/relatedperson?view=graph-rest-1.0&tabs=http)
| Property        | Type        | Description                                                                                                                                                                                                                                     |
|:----------------|:------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|displayName      |String       | Name of the person.                                                                                                                                                                                                                             |
|relationship     |String       | Possible values are: `manager`, `colleague`, `directReport`, `dotLineReport`, `assistant`, `dotLineManager`, `alternateContact`, `friend`, `spouse`, `sibling`, `child`, `parent`, `sponsor`, `emergencyContact`, `other`, `unknownFutureValue`.|
|userId           |String       | The user's directory object ID (Microsoft Entra ID or CID).                                                                                                                                                                                       |
|userPrincipalName|String       | Email address or reference to person within the organization.                                                                                                                                                                                       |
### [serviceInformation ](https://docs.microsoft.com/graph/api/resources/serviceinformation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description                                                      |
|:-------------|:------------|:-----------------------------------------------------------------|
|name          | String      | The name of the cloud service (for example, Twitter, Instagram). |
|webUrl        | String      | Contains the URL for the service being referenced.               |
### [skillProficiency ](https://docs.microsoft.com/graph/api/resources/skillproficiency?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|categories|String collection|Contains categories a user has associated with the skill (for example, personal, professional, hobby). |
|collaborationTags|String collection|Contains experience scenario tags a user has associated with the interest. Allowed values in the collection are: `askMeAbout`, `ableToMentor`, `wantsToLearn`, `wantsToImprove`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|displayName|String|Contains a friendly name for the skill. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|proficiency|skillProficiencyLevel|Detail of the users proficiency with this skill. Possible values are: `elementary`, `limitedWorking`, `generalProfessional`, `advancedProfessional`, `expert`, `unknownFutureValue`.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|webUrl|String|Contains a link to an information source about the skill. |
### [usageRight ](https://docs.microsoft.com/graph/api/resources/usageright?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|catalogId|String|Product id corresponding to the usage right.|
|id|String|The id of the usage right.|
|serviceIdentifier|String|Identifier of the service corresponding to the usage right.|
|state|usageRightState|The state of the usage right. Possible values are: `active`, `inactive`, `warning`, `suspended`.|
### [user ](https://docs.microsoft.com/graph/api/resources/user?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|aboutMe|String|A freeform text entry field for the user to describe themselves. Returned only on `$select`.|
|accountEnabled|Boolean| `true` if the account is enabled; otherwise, `false`. This property is required when a user is created. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).    |
|ageGroup|ageGroup|Sets the age group of the user. Allowed values: `null`, `Minor`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|assignedLicenses|assignedLicense collection|The licenses that are assigned to the user, including inherited (group-based) licenses. This property doesn't differentiate between directly assigned and inherited licenses. Use the **licenseAssignmentStates** property to identify the directly assigned and inherited licenses. Not nullable. Returned only on `$select`. Supports `$filter` (`eq`, `not`, `/$count eq 0`, `/$count ne 0`).           |
|assignedPlans|assignedPlan collection|The plans that are assigned to the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq` and `not`). |
|birthday|DateTimeOffset|The birthday of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|businessPhones|String collection|The telephone numbers for the user. NOTE: Although it's a string collection, only one number can be set for this property. Read-only for users synced from the on-premises directory. <br><br>Returned by default. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|city|String|The city where the user is located. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|companyName | String | The name of the company that the user is associated with. This property can be useful for describing the company that a guest comes from. The maximum length is 64 characters.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|consentProvidedForMinor|consentProvidedForMinor|Sets whether consent was obtained for minors. Allowed values: `null`, `Granted`, `Denied`, and `NotRequired`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|country|String|The country/region where the user is located; for example, `US` or `UK`. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|createdDateTime | DateTimeOffset |The date and time the user was created, in ISO 8601 format and UTC. The value can't be modified and is automatically populated when the entity is created. Nullable. For on-premises users, the value represents when they were first created in Microsoft Entra ID. Property is `null` for some users created before June 2018 and on-premises users that were synced to Microsoft Entra ID before June 2018. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| creationType | String | Indicates whether the user account was created through one of the following methods: <br/> <ul><li>As a regular school or work account (`null`). <li>As an external account (`Invitation`). <li>As a local account for an Azure Active Directory B2C tenant (`LocalAccount`). <li>Through self-service sign-up by an internal user using email verification (`EmailVerified`). <li>Through self-service sign-up by a guest signing up through a link that is part of a user flow (`SelfServiceSignUp`).</ul> <br>Read-only.<br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). The filter value is case-sensitive.|
|deletedDateTime| DateTimeOffset | The date and time the user was deleted. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
|department|String|The name of the department in which the user works. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, and `eq` on `null` values).|
|displayName|String|The name displayed in the address book for the user. This value is usually the combination of the user's first name, middle initial, and family name. This property is required when a user is created and it can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$orderby`, and `$search`.|
| employeeHireDate | DateTimeOffset |The date and time when the user was hired or will start work in a future hire. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeLeaveDateTime | DateTimeOffset | The date and time when the user left or will leave the organization. <br><br>To read this property, the calling app must be assigned the *User-LifeCycleInfo.Read.All* permission. To write this property, the calling app must be assigned the *User.Read.All* and *User-LifeCycleInfo.ReadWrite.All* permissions. To read this property in delegated scenarios, the admin needs at least one of the following Microsoft Entra roles: *Lifecycle Workflows Administrator*, *Global Reader*. To write this property in delegated scenarios, the admin needs the *Global Administrator* role. <br><br>Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`). <br><br>For more information, see Configure the employeeLeaveDateTime property for a user.|
| employeeId | String | The employee identifier assigned to the user by the organization. The maximum length is 16 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|employeeOrgData|employeeOrgData |Represents organization data (for example, division and costCenter) associated with a user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeType | String | Captures enterprise worker type. For example, `Employee`, `Contractor`, `Consultant`, or `Vendor`. Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`).|
|externalUserState|String|For a guest invited to the tenant using the invitation API, this property represents the invited user's invitation status. For invited users, the state can be `PendingAcceptance` or `Accepted`, or `null` for all other users. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|externalUserStateChangeDateTime|DateTimeOffset|Shows the timestamp for the latest change to the **externalUserState** property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|faxNumber|String|The fax number of the user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|givenName|String|The given name (first name) of the user. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| hireDate | DateTimeOffset | The hire date of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`. <br> **Note:** This property is specific to SharePoint in Microsoft 365. We recommend using the native **employeeHireDate** property to set and update hire date values using Microsoft Graph APIs. |
|id|String|The unique identifier for the user. Should be treated as an opaque identifier. Inherited from directoryObject. Key. Not nullable. Read-only. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
|identities|objectIdentity collection| Represents the identities that can be used to sign in to this user account. Microsoft (also known as a local account), organizations, or social identity providers such as Facebook, Google, and Microsoft can provide identity and tie it to a user account. It might contain multiple items with the same **signInType** value. <br><br>Returned only on `$select`. <br><br> Supports `$filter` (`eq`) with limitations. <!--Supports `$filter` (`eq`) including on `null` values, only where the **signInType** is not `userPrincipalName`.-->|
|imAddresses|String collection|The instant message voice-over IP (VOIP) session initiation protocol (SIP) addresses for the user. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|interests|String collection|A list for the user to describe their interests. <br><br>Returned only on `$select`.|
|isResourceAccount|Boolean| Don't use – reserved for future use.|
|jobTitle|String|The user's job title. Maximum length is 128 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|lastPasswordChangeDateTime| DateTimeOffset | The time when this Microsoft Entra user last changed their password or when their password was created, whichever date the latest action was performed. The date and time information uses ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|legalAgeGroupClassification|legalAgeGroupClassification| Used by enterprise applications to determine the legal age group of the user. This property is read-only and calculated based on **ageGroup** and **consentProvidedForMinor** properties. Allowed values: `null`, `MinorWithOutParentalConsent`, `MinorWithParentalConsent`, `MinorNoParentalConsentRequired`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`.|
|licenseAssignmentStates|licenseAssignmentState collection|State of license assignments for this user. Also indicates licenses that are directly assigned or the user inherited through group memberships. Read-only. <br><br>Returned only on `$select`.|
|mail|String|The SMTP address for the user, for example, `jeff@contoso.com`. Changes to this property update the user's **proxyAddresses** collection to include the value as an SMTP address. This property can't contain accent characters. <br/> **NOTE:** We don't recommend updating this property for Azure AD B2C user profiles. Use the **otherMails** property instead. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, and `eq` on `null` values).|
|mailboxSettings|mailboxSettings|Settings for the primary mailbox of the signed-in user. You can get or update settings for sending automatic replies to incoming messages, locale, and time zone. <br><br>Returned only on `$select`.|
|mailNickname|String|The mail alias for the user. This property must be specified when a user is created. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|mobilePhone|String|The primary cellular telephone number for the user. Read-only for users synced from the on-premises directory. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values) and `$search`. |
|mySite|String|The URL for the user's site. <br><br>Returned only on `$select`.|
|officeLocation|String|The office location in the user's place of business. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|onPremisesDistinguishedName|String| Contains the on-premises Active Directory `distinguished name` or `DN`. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. |
|onPremisesDomainName|String| Contains the on-premises `domainFQDN`, also called dnsDomainName synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`.|
|onPremisesExtensionAttributes|onPremisesExtensionAttributes|Contains extensionAttributes1-15 for the user. These extension attributes are also known as Exchange custom attributes 1-15. <br><li>For an **onPremisesSyncEnabled** user, the source of authority for this set of properties is the on-premises and is read-only. </li><li>For a cloud-only user (where **onPremisesSyncEnabled** is `false`), these properties can be set during the creation or update of a user object.  </li><li>For a cloud-only user previously synced from on-premises Active Directory, these properties are read-only in Microsoft Graph but can be fully managed through the Exchange Admin Center or the Exchange Online V2 module in PowerShell.</li><br> Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|onPremisesImmutableId|String|This property is used to associate an on-premises Active Directory user account to their Microsoft Entra user object. This property must be specified when creating a new user account in the Graph if you're using a federated domain for the user's **userPrincipalName** (UPN) property. **NOTE:** The **$** and **\_** characters can't be used when specifying this property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).                            |
|onPremisesLastSyncDateTime|DateTimeOffset|Indicates the last time at which the object was synced with the on-premises directory; for example: `2013-02-16T03:04:54Z`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).|
|onPremisesProvisioningErrors|onPremisesProvisioningError collection| Errors when using Microsoft synchronization product during provisioning. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|onPremisesSamAccountName|String| Contains the on-premises `samAccountName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|onPremisesSecurityIdentifier|String|Contains the on-premises security identifier (SID) for the user that was synchronized from on-premises to the cloud. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq` including on `null` values). |
|onPremisesSyncEnabled|Boolean| `true` if this user object is currently being synced from an on-premises Active Directory (AD); otherwise the user isn't being synced and can be managed in Microsoft Entra ID. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|onPremisesUserPrincipalName|String| Contains the on-premises `userPrincipalName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|otherMails|String collection| A list of other email addresses for the user; for example: `["bob@contoso.com", "Robert@fabrikam.com"]`. <br>NOTE: This property can't contain accent characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|passwordPolicies|String|Specifies password policies for the user. This value is an enumeration with one possible value being `DisableStrongPassword`, which allows weaker passwords than the default policy to be specified. `DisablePasswordExpiration` can also be specified. The two might be specified together; for example: `DisablePasswordExpiration, DisableStrongPassword`. <br><br>Returned only on `$select`. For more information on the default password policies, see Microsoft Entra password policies. Supports `$filter` (`ne`, `not`, and `eq` on `null` values).|
|passwordProfile|passwordProfile|Specifies the password profile for the user. The profile contains the user's password. This property is required when a user is created. The password in the profile must satisfy minimum requirements as specified by the **passwordPolicies** property. By default, a strong password is required. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|pastProjects|String collection|A list for the user to enumerate their past projects. <br><br>Returned only on `$select`.|
|postalCode|String|The postal code for the user's postal address. The postal code is specific to the user's country/region. In the United States of America, this attribute contains the ZIP code. Maximum length is 40 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| preferredDataLocation | String | The preferred data location for the user. For more information, see OneDrive Online Multi-Geo.|
|preferredLanguage|String|The preferred language for the user. The preferred language format is based on RFC 4646. The name is a combination of an ISO 639 two-letter lowercase culture code associated with the language, and an ISO 3166 two-letter uppercase subculture code associated with the country or region. Example: "en-US", or "es-ES". <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values)|
|preferredName|String|The preferred name for the user. **Not Supported. This attribute returns an empty string.**<br><br>Returned only on `$select`.|
|provisionedPlans|provisionedPlan collection|The plans that are provisioned for the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|proxyAddresses|String collection|For example: `"SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. Changes to the **mail** property update this collection to include the value as an SMTP address. For more information, see [mail and proxyAddresses properties. The proxy address prefixed with `SMTP` (capitalized) is the primary proxy address, while those addresses prefixed with `smtp` are the secondary proxy addresses. For Azure AD B2C accounts, this property has a limit of 10 unique addresses. Read-only in Microsoft Graph; you can update this property only through the Microsoft 365 admin center. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|refreshTokensValidFromDateTime|DateTimeOffset|Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. <br><br>Returned only on `$select`. Read-only. |
|responsibilities|String collection|A list for the user to enumerate their responsibilities. <br><br>Returned only on `$select`.|
| serviceProvisioningErrors    | serviceProvisioningError collection       | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a user object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance).  |
|schools|String collection|A list for the user to enumerate the schools they attended. <br><br>Returned only on `$select`.|
|securityIdentifier| String | Security identifier (SID) of the user, used in Windows scenarios. <br><br>Read-only. Returned by default. <br>Supports `$select` and `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
|showInAddressList|Boolean|**Do not use in Microsoft Graph. Manage this property through the Microsoft 365 admin center instead.** Represents whether the user should be included in the Outlook global address list. See Known issue.|
|signInActivity | signInActivity | Get the last signed-in date and request ID of the sign-in for a given user. Read-only.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`) *but not with any other filterable properties*. <br><br>**Note:** <br/><li>Details for this property require a Microsoft Entra ID P1 or P2 license and the **AuditLog.Read.All** permission.<li>This property isn't returned for a user who never signed in or last signed in before April 2020.|
|signInSessionsValidFromDateTime|DateTimeOffset| Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. Read-only. Use revokeSignInSessions to reset. <br><br>Returned only on `$select`.|
|skills|String collection|A list for the user to enumerate their skills. <br><br>Returned only on `$select`.|
|state|String|The state or province in the user's address. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|streetAddress|String|The street address of the user's place of business. Maximum length is 1,024 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|surname|String|The user's surname (family name or last name). Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|usageLocation|String|A two-letter country code (ISO standard 3166). Required for users that are assigned licenses due to legal requirements to check for availability of services in countries. Examples include: `US`, `JP`, and `GB`. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|userPrincipalName|String|The user principal name (UPN) of the user. The UPN is an Internet-style sign-in name for the user based on the Internet standard RFC 822. By convention, this value should map to the user's email name. The general format is alias@domain, where the domain must be present in the tenant's collection of verified domains. This property is required when a user is created. The verified domains for the tenant can be accessed from the **verifiedDomains** property of organization.<br>NOTE: This property can't contain accent characters. Only the following characters are allowed `A - Z`, `a - z`, `0 - 9`, ` ' . - _ ! # ^ ~`. For the complete list of allowed characters, see username policies. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`) and `$orderby`.
|userType|String|A string value that can be used to classify user types in your directory. The possible values are `Member` and `Guest`. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). **N
### [userAccountInformation ](https://docs.microsoft.com/graph/api/resources/useraccountinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|ageGroup|String|Shows the age group of user. Allowed values `null`, `minor`, `notAdult` and `adult` are generated by the directory and can't be changed.|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|countryCode|String|Contains the two-character country code associated with the users' account.  |
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|preferredLanguageTag|localeInfo|Contains the language the user has associated as preferred for the account.   |
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|userPrincipalName|String|The user principal name (UPN) of the user associated with the account.   |
### [userInsightsSettings ](https://docs.microsoft.com/graph/api/resources/userinsightssettings?view=graph-rest-1.0&tabs=http)
| Property  | Type     | Description                                                                                                                                                         |
|-----------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| isEnabled | Boolean  | `True` if the user's **i
### [users](https://docs.microsoft.com/graph/api/resources/users?view=graph-rest-1.0&tabs=http)
|Property |Description |
|:----------|:-------------|
|id | The unique identifier for the user.|
|businessPhones | The user's phone numbers.|
|displayName | The name displayed in the address book for the user.|
|givenName| The first name of the user. |
|jobTitle | The user's job title.|
|mail| The user's email address. |
|mobilePhone | The user's cellphone number.|
|officeLocation | The user's physical office location.|
|preferredLanguage | The user's language of preference.|
|surname| The last name of the user. |
|userPrincipalName| The user's principal name. |
### [userSettings ](https://docs.microsoft.com/graph/api/resources/usersettings?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contributionToContentDiscoveryAsOrganizationDisabled|Boolean|Reflects the organization level setting controlling delegate access to the trending API. When set to true, the organization doesn't have access to Office Delve. The relevancy of the content displayed in Microsoft 365, for example in Suggested sites in SharePoint Home and the Discover view in OneDrive for work or school is affected for the whole organization. This setting is read-only and can only be changed by administrators in the SharePoint admin center.|
|contributionToContentDiscoveryDisabled|Boolean|When set to true, the delegate access to the user's trending API is disabled. When set to true, documents in the user's Office Delve are disabled. When set to true, the relevancy of the content displayed in Microsoft 365, for example in Suggested sites in SharePoint Home and the Discover view in OneDrive for work or school is affected. Users can control this setting in Office Delve. |
|id|String|Unique identifier of the user setting. Read-only. Inherited from entity.|
|windows|windowsSetting collection|The Windows settings of the user stored in the cloud.|
### [webAccount ](https://docs.microsoft.com/graph/api/resources/webaccount?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|description|String|Contains the description the user has provided for the account on the service being referenced.|
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|service|serviceInformation| Contains basic detail about the service that is being associated. |
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
|statusMessage|String|Contains a status message from the cloud service if provided or synchronized. |
|userId|String|The user name  displayed for the webaccount.  |
|webUrl|String|Contains a link to the user's profile on the cloud service if one exists.|
### [workPosition ](https://docs.microsoft.com/graph/api/resources/workposition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|String|The audiences that are able to see the values contained within the entity. Inherited from itemFacet. Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|categories|String collection|Categories that the user has associated with this position.|
|colleagues|relatedPerson collection|Colleagues that are associated with this position.|
|createdBy|identitySet|Provides the identifier of the user and/or application that created the entity. Inherited from itemFacet.|
|createdDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|detail|positionDetail|Contains detailed information about the position. |
|id|String|Identifier used for individually addressing the entity. Inherited from entity|
|inference|inferenceData|Contains inference detail if the entity is inferred by the creating or modifying application. Inherited from itemFacet.|
|isCurrent|Boolean|Denotes whether or not the position is current.|
|lastModifiedBy|identitySet|Provides the identifier of the user and/or application that last modified the entity. Inherited from itemFacet.|
|lastModifiedDateTime|DateTimeOffset|Provides the dateTimeOffset for when the entity was created. Inherited from itemFacet.|
|manager|relatedPerson|Contains detail of the user's manager in this position.|
|source|personDataSource|Where the values originated if synced from another service. Inherited from itemFacet.|
### [yomiPersonName ](https://docs.microsoft.com/graph/api/resources/yomipersonname?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description                                             |
|:-------------|:------------|:--------------------------------------------------------|
|displayName   |String       | Composite of first and last name pronunciation guides.  |
|first         |String       | Pronunciation guide for the first name of the user.     |
|last          |String       | Pronunciation guide for the last name of the user.      |
|maiden        |String       | Pronunciation guide for the maiden name of the user.    |
|middle        |String       | Pronunciation guide for the middle name of the user.    |
