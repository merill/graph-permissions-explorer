# User.ReadWrite.All

> Allows the app to read and write the full set of profile properties, reports, and managers of other users in your organization, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-delete?view=graph-rest-1.0&tabs=http)|
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
|V1|A,D|[DELETE /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-delete?view=graph-rest-1.0&tabs=http)|
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
|V1|A,D|[DELETE /users/{id}/manager/$ref](https://docs.microsoft.com/graph/api/user-delete-manager?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id}/sponsors/{id}/$ref](https://docs.microsoft.com/graph/api/user-delete-sponsors?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /users/{userId}/profile/phones/{itemPhoneId}](https://docs.microsoft.com/graph/api/itemphone-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /groups/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me](https://docs.microsoft.com/graph/api/user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/createdObjects](https://docs.microsoft.com/graph/api/user-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/directReports](https://docs.microsoft.com/graph/api/user-list-directreports?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/joinedTeams](https://docs.microsoft.com/graph/api/user-list-joinedteams?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/licenseDetails](https://docs.microsoft.com/graph/api/user-list-licensedetails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/manager](https://docs.microsoft.com/graph/api/user-list-manager?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/ownedDevices](https://docs.microsoft.com/graph/api/user-list-owneddevices?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/ownedObjects](https://docs.microsoft.com/graph/api/user-list-ownedobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[GET /me/registeredDevices](https://docs.microsoft.com/graph/api/user-list-registereddevices?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/responsibilities](https://docs.microsoft.com/graph/api/profile-list-responsibilities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/settings/](https://docs.microsoft.com/graph/api/usersettings-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /organization/{organizationId}/settings/itemInsights](https://docs.microsoft.com/graph/api/organizationsettings-list-iteminsights?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /organization/{organizationId}/settings/peopleInsights](https://docs.microsoft.com/graph/api/organizationsettings-list-peopleinsights?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /team/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users](https://docs.microsoft.com/graph/api/user-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | user-principal-name}/joinedTeams](https://docs.microsoft.com/graph/api/user-list-joinedteams?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/createdObjects](https://docs.microsoft.com/graph/api/user-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/directReports](https://docs.microsoft.com/graph/api/user-list-directreports?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/manager](https://docs.microsoft.com/graph/api/user-list-manager?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/ownedDevices](https://docs.microsoft.com/graph/api/user-list-owneddevices?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/ownedObjects](https://docs.microsoft.com/graph/api/user-list-ownedobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-get?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[GET /users/{id | userPrincipalName}/registeredDevices](https://docs.microsoft.com/graph/api/user-list-registereddevices?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/responsibilities](https://docs.microsoft.com/graph/api/profile-list-responsibilities?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{id | userPrincipalName}/responsibilities/{id}](https://docs.microsoft.com/graph/api/personresponsibility-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/sponsors](https://docs.microsoft.com/graph/api/user-list-sponsors?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/licenseDetails](https://docs.microsoft.com/graph/api/user-list-licensedetails?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId}/profile/phones/{id}](https://docs.microsoft.com/graph/api/itemphone-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{userId}/settings/shiftPreferences](https://docs.microsoft.com/graph/api/shiftpreferences-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{userId}/usageRights](https://docs.microsoft.com/graph/api/user-list-usagerights?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/delta](https://docs.microsoft.com/graph/api/user-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
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
|Beta|D|[PATCH /organization/{organizationId}/settings/contactInsights](https://docs.microsoft.com/graph/api/insightssettings-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[PATCH /users/{userId}/settings/shiftPreferences](https://docs.microsoft.com/graph/api/shiftpreferences-put?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /directoryObjects/{id}/checkMemberGroups](https://docs.microsoft.com/graph/api/directoryobject-checkmembergroups?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /directoryObjects/{id}/checkMemberObjects](https://docs.microsoft.com/graph/api/directoryobject-checkmemberobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directoryObjects/{id}/getMemberObjects](https://docs.microsoft.com/graph/api/directoryobject-getmemberobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /invitations](https://docs.microsoft.com/graph/api/invitation-post?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[POST /me/revokeSignInSessions](https://docs.microsoft.com/graph/api/user-revokesigninsessions?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/translateExchangeIds](https://docs.microsoft.com/graph/api/user-translateexchangeids?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users](https://docs.microsoft.com/graph/api/user-post-users?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/assignLicense](https://docs.microsoft.com/graph/api/user-assignlicense?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[POST /users/{id | userPrincipalName}/revokeSignInSessions](https://docs.microsoft.com/graph/api/user-revokesigninsessions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/reprocessLicenseAssignment](https://docs.microsoft.com/graph/api/user-reprocesslicenseassignment?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/user-retryserviceprovisioning?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/sponsors/$ref](https://docs.microsoft.com/graph/api/user-post-sponsors?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/translateExchangeIds](https://docs.microsoft.com/graph/api/user-translateexchangeids?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{userId}/profile/phones](https://docs.microsoft.com/graph/api/profile-post-phones?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{usersId}/convertExternalToInternalMemberUser](https://docs.microsoft.com/graph/api/user-convertexternaltointernalmemberuser?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/validatePassword](https://docs.microsoft.com/graph/api/user-validatepassword?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /me/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /me/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /me/settings/regionalAndLanguageSettings](https://docs.microsoft.com/graph/api/regionalandlanguagesettings-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /users/{id | userPrincipalName}/contactfolders/{contactFolderId}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /users/{id | userPrincipalName}/contacts/{id}/photo/$value](https://docs.microsoft.com/graph/api/profilephoto-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /users/{id}/manager/$ref](https://docs.microsoft.com/graph/api/user-post-manager?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /users/{user-id | userPrincipalName}/settings/regionalAndLanguageSettings](https://docs.microsoft.com/graph/api/regionalandlanguagesettings-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PUT /users/{userId}/settings/shiftPreferences](https://docs.microsoft.com/graph/api/shiftpreferences-put?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|204e0828-b5ca-4ad8-b9f3-f32a958e7cc4|
|**Consent Type**|Admin|
|**Display String**|Read and write all users' full profiles|
|**Description**|Allows the app to read and write the full set of profile properties, reports, and managers of other users in your organization, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|741f803b-c850-494e-b5df-cde7c675a1ca|
|**Display String**|Read and write all users' full profiles|
|**Description**|Allows the app to read and update user profiles without a signed in user.|
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
### [convertIdResult ](https://docs.microsoft.com/graph/api/resources/convertidresult?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------|:-----|:------------|
| errorDetails | genericError | An error object indicating the reason for the conversion failure. This value isn't present if the conversion succeeded. |
| sourceId | String | The identifier that was converted. This value is the original, un-converted identifier. |
| targetId | String | The converted identifier. This value isn't present if the conversion failed. |
### [customSecurityAttributeValue ](https://docs.microsoft.com/graph/api/resources/customsecurityattributevalue?view=graph-rest-1.0&tabs=http)

### [device ](https://docs.microsoft.com/graph/api/resources/device?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|accountEnabled|Boolean| `true` if the account is enabled; otherwise, `false`. Required. Default is `true`. <br/><br/> Supports `$filter` (`eq`, `ne`, `not`, `in`). Only callers with at least the Cloud Device Administrator role can set this property.|
|alternativeSecurityIds|alternativeSecurityId collection| For internal use only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|approximateLastSignInDateTime|DateTimeOffset| The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values) and `$orderby`. |
|complianceExpirationDateTime|DateTimeOffset| The timestamp when the device is no longer deemed compliant. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
|deviceCategory|String|User-defined property set by Intune to automatically add devices to groups and simplify managing devices.|
|deviceId|String| Unique identifier set by Azure Device Registration Service at the time of registration. This alternate key can be used to reference the device object. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`).|
|deviceMetadata|String| For internal use only. Set to `null`. |
|deviceOwnership|String|Ownership of the device. Intune sets this property. Possible values are: `unknown`, `company`, `personal`.|
|deviceVersion|Int32| For internal use only. |
|displayName|String|The display name for the device. Required. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`.  |
|enrollmentProfileName|String|Enrollment profile applied to the device. For example, `Apple Device Enrollment Profile`, `Device enrollment - Corporate device identifiers`, or `Windows Autopilot profile name`. This property is set by Intune.|
|enrollmentType|String|Enrollment type of the device. Intune sets this property. Possible values are: `unknown`, `userEnrollment`, `deviceEnrollmentManager`, `appleBulkWithUser`, `appleBulkWithoutUser`, `windowsAzureADJoin`, `windowsBulkUserless`, `windowsAutoEnrollment`, `windowsBulkAzureDomainJoin`, `windowsCoManagement`, `windowsAzureADJoinUsingDeviceAuth`,`appleUserEnrollment`, `appleUserEnrollmentWithServiceAccount`. <br/><br/>**NOTE:** This property might return other values apart from those listed.|
| extensionAttributes | onPremisesExtensionAttributes | Contains extension attributes 1-15 for the device. The individual extension attributes aren't selectable. These properties are mastered in the cloud and can be set during creation or update of a device object in Microsoft Entra ID. <br><br>Supports `$filter` (`eq`, `not`, `startsWith`, and `eq` on `null` values). |
|id|String|The unique identifier for the device. Inherited from directoryObject. Key, Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|isCompliant|Boolean|`true` if the device complies with Mobile Device Management (MDM) policies; otherwise, `false`. Read-only. This can only be updated by Intune for any device OS type or by an approved MDM app for Windows OS devices. Supports `$filter` (`eq`, `ne`, `not`).|
|isManaged|Boolean|`true` if the device is managed by a Mobile Device Management (MDM) app; otherwise, `false`. This can only be updated by Intune for any device OS type or by an approved MDM app for Windows OS devices. Supports `$filter` (`eq`, `ne`, `not`). |
|manufacturer|String| Manufacturer of the device. Read-only. |
|isRooted|Boolean|`true` if the device is rooted or jail-broken. This property can only be updated by Intune.|
|managementType|String|The management channel of the device. This property is set by Intune. Possible values are: `eas`, `mdm`, `easMdm`, `intuneClient`, `easIntuneClient`, `configurationManagerClient`, `configurationManagerClientMdm`, `configurationManagerClientMdmEas`, `unknown`, `jamf`, `googleCloudDevicePolicyController`.|
|mdmAppId|String|Application identifier used to register device into MDM. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`).|
|model|String| Model of the device. Read-only. |
|onPremisesLastSyncDateTime|DateTimeOffset|The last time at which the object was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z` Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).|
|onPremisesSecurityIdentifier|String|The on-premises security identifier (SID) for the user who was synchronized from on-premises to the cloud. Read-only. Returned only on `$select`. Supports `$filter` (`eq`).|
|onPremisesSyncEnabled|Boolean|`true` if this object is synced from an on-premises directory; `false` if this object was originally synced from an on-premises directory but is no longer synced; `null` if this object has never been synced from an on-premises directory (default). Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). |
|operatingSystem|String| The type of operating system on the device. Required. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`, and `eq` on `null` values). |
|operatingSystemVersion|String|The version of the operating system on the device. Required. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`, and `eq` on `null` values). |
|physicalIds|String collection| For internal use only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`,`/$count eq 0`, `/$count ne 0`). |
|profileType|deviceProfileType|The profile type of the device. Possible values: `RegisteredDevice` (default), `SecureVM`, `Printer`, `Shared`, `IoT`.|
|registrationDateTime|DateTimeOffset|Date and time of when the device was registered. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|systemLabels|String collection| List of labels applied to the device by the system. Supports `$filter` (`/$count eq 0`, `/$count ne 0`). |
|trustType|String| Type of trust for the joined device. Read-only. Possible values:  `Workplace` (indicates *b
### [directory ](https://docs.microsoft.com/graph/api/resources/directory?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                                                                                                                                              |
| :------- | :----- | :------------------------------------------------------------------------------------------------------------------------------------------------------- |
| id       | String | A unique identifier for the object; for example, `12345678-9abc-def0-1234-56789abcde`. Key. Not nullable. Read-only. Inherited from entity. |
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

### [group ](https://docs.microsoft.com/graph/api/resources/group?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-|:-|:-|
| allowExternalSenders | Boolean | Indicates if people external to the organization can send messages to the group. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| assignedLabels | assignedLabel collection | The list of sensitivity label pairs (label ID, label name) associated with a Microsoft 365 group. <br><br>Returned only on `$select`. |
| assignedLicenses | assignedLicense collection | The licenses that are assigned to the group. <br><br>Returned only on `$select`. Supports `$filter` (`eq`).Read-only. |
| autoSubscribeNewMembers | Boolean | Indicates if new members added to the group are autosubscribed to receive email notifications. You can set this property in a PATCH request for the group; don't set it in the initial POST request that creates the group. Default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| classification | String | Describes a classification for the group (such as low, medium, or high business impact). Valid values for this property are defined by creating a ClassificationList setting value, based on the template definition.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| createdDateTime | DateTimeOffset | Timestamp of when the group was created. The value can't be modified and is automatically populated when the group is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. |
| deletedDateTime | DateTimeOffset | For some Microsoft Entra objects (user, group, application), if the object is deleted, it's first logically deleted, and this property is updated with the date and time when the object was deleted. Otherwise this property is `null`. If the object is restored, this property is updated to `null`. Inherited from directoryObject.  |
| description | String | An optional description for the group. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| displayName | String | The display name for the group. This property is required when a group is created and can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| expirationDateTime | DateTimeOffset | Timestamp of when the group is set to expire. It's `null` for security groups, but for Microsoft 365 groups, it represents when the group is set to expire as defined in the groupLifecyclePolicy. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| groupTypes | String collection | Specifies the group type and its membership. <br><br>If the collection contains `Unified`, the group is a Microsoft 365 group; otherwise, it's either a security group or a distribution group. For details, see groups overview.<br><br>If the collection includes `DynamicMembership`, the group has dynamic membership; otherwise, membership is static. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| hasMembersWithLicenseErrors | Boolean | Indicates whether there are members in this group that have license errors from its group-based license assignment. <br><br>This property is never returned on a GET operation. You can use it as a $filter argument to get groups that have members with license errors (that is, filter for this property being true). See an example. <br><br>Supports `$filter` (`eq`). |
| hideFromAddressLists | Boolean | True if the group isn't displayed in certain parts of the Outlook UI: the **Address Book**, address lists for selecting message recipients, and the **Browse Groups** dialog for searching groups; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| hideFromOutlookClients | Boolean | True if the group isn't displayed in Outlook clients, such as Outlook for Windows and Outlook on the web; otherwise, false. The default value is `false`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| id | String | The unique identifier for the group. <br><br>Returned by default. Inherited from directoryObject. Key. Not nullable. Read-only.<br><br>Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| isArchived | Boolean | When a group is associated with a team, this property determines whether the team is in read-only mode.<br/>To read this property, use the `/group/{groupId}/team` endpoint or the Get team API. To update this property, use the archiveTeam and unarchiveTeam APIs. |
| isAssignableToRole | Boolean | Indicates whether this group can be assigned to a Microsoft Entra role. Optional. <br><br>This property can only be set while creating the group and is immutable. If set to `true`, the **securityEnabled** property must also be set to `true`, **visibility** must be `Hidden`, and the group can't be a dynamic group (that is, **groupTypes** can't contain `DynamicMembership`). <br/><br/>Only callers with at least the Privileged Role Administrator role can set this property. The caller must also be assigned the _RoleManagement.ReadWrite.Directory_ permission to set this property or update the membership of such groups. For more, see Using a group to manage Microsoft Entra role assignments<br><br>Using this feature requires a Microsoft Entra ID P1 license. Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| isSubscribedByMail | Boolean | Indicates whether the signed-in user is subscribed to receive email conversations. The default value is `true`. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| licenseProcessingState | String | Indicates the status of the group license assignment to all group members. The default value is `false`. Read-only. Possible values: `QueuedForProcessing`, `ProcessingInProgress`, and `ProcessingComplete`.<br><br>Returned only on `$select`. Read-only. |
| mail | String | The SMTP address for the group, for example, "serviceadmins@contoso.com". <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| mailEnabled | Boolean | Specifies whether the group is mail-enabled. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`). |
| mailNickname | String | The mail alias for the group, unique for Microsoft 365 groups in the organization. Maximum length is 64 characters. This property can contain only characters in the ASCII character set 0 - 127 except the following characters: ` @ () \ [] " ; : <> , SPACE`. <br><br>Required. Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| membershipRule | String | The rule that determines members for this group if the group is a dynamic group (groupTypes contains `DynamicMembership`). For more information about the syntax of the membership rule, see Membership Rules syntax. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`). |
| membershipRuleProcessingState | String | Indicates whether the dynamic membership processing is on or paused. Possible values are `On` or `Paused`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| onPremisesDomainName | String | Contains the on-premises **domain FQDN**, also called **dnsDomainName** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesLastSyncDateTime | DateTimeOffset | Indicates the last time at which the group was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
| onPremisesNetBiosName | String | Contains the on-premises **netBios name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Read-only. |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | Errors when using Microsoft synchronization product during provisioning. <br><br>Returned by default. Supports `$filter` (`eq`, `not`). |
| onPremisesSamAccountName | String | Contains the on-premises **SAM account name** synchronized from the on-premises directory. The property is only populated for customers synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect.<br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`). Read-only. |
| onPremisesSecurityIdentifier | String | Contains the on-premises security identifier (SID) for the group synchronized from on-premises to the cloud. Read-only. <br><br>Returned by default. Supports `$filter` (`eq` including on `null` values). |
| onPremisesSyncEnabled | Boolean | `true` if this group is synced from an on-premises directory; `false` if this group was originally synced from an on-premises directory but is no longer synced; **null** if this object has never synced from an on-premises directory (default). <br><br>Returned by default. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). |
| preferredDataLocation | String | The preferred data location for the Microsoft 365 group. By default, the group inherits the group creator's preferred data location. To set this property, the calling app must be granted the *Directory.ReadWrite.All* permission and the user be assigned at least one of the following Microsoft Entra roles: <br><ul>User Account Administrator <li>Directory Writer <li> Exchange Administrator <li> SharePoint Administrator </ul><br/> For more information about this property, see OneDrive Online Multi-Geo. <br><br>Nullable. Returned by default. |
| preferredLanguage | String | The preferred language for a Microsoft 365 group. Should follow ISO 639-1 Code; for example, `en-US`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values). |
| proxyAddresses | String collection | Email addresses for the group that direct to the same group mailbox. For example: `["SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. The **any** operator is required to filter expressions on multi-valued properties. <br><br>Returned by default. Read-only. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`). |
| renewedDateTime | DateTimeOffset | Timestamp of when the group was last renewed. This value can't be modified directly and is only updated via the renew service action. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). Read-only. |
| securityEnabled | Boolean | Specifies whether the group is a security group. Required. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
| securityIdentifier | String | Security identifier of the group, used in Windows scenarios. Read-only. <br><br>Returned by default. |
| serviceProvisioningErrors | serviceProvisioningError collection | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a group object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance). |
| theme | string | Specifies a Microsoft 365 group's color theme. Possible values are `Teal`, `Purple`, `Green`, `Blue`, `Pink`, `Orange`, or `Red`. <br><br>Returned by default. |
| uniqueName | String | The unique identifier that can be assigned to a group and used as an alternate key. Immutable. Read-only. |
| unseenCount | Int32 | Count of conversations that received new posts since the signed-in user last visited the group. <br><br>Returned only on `$select`. Supported only on the Get group API (`GET /groups/{ID}`). |
| visibility | String | Specifies the group join policy and group content visibility for groups. Possible values are: `Private`, `Public`, or `HiddenMembership`. `HiddenMembership` can be set only for Microsoft 365 groups when the groups are created. It can't be updated later. Other values of visibility can be updated after group creation.<br> If visibility value isn't specified during group creation on Microsoft Graph, a security group is created as `Private` by default, and the Microsoft 365 group is `Public`. Groups assignable to roles are always `Private`. To learn more, see group visibility options. <br><br>Returned by default. Nullable. |
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
### [insightsSettings ](https://docs.microsoft.com/graph/api/resources/insightssettings?view=graph-rest-1.0&tabs=http)
| Property   | Type|Description|
|:---------------|:--------|:----------|
|disabledForGroup|String| The ID of a Microsoft Entra group, of which the specified type of insights are disabled for its members. The default value is `null`. Optional.|
|isEnabledInOrganization|Boolean| `true` if insights of the specified type are enabled for the organization; `false` if insights of the specified type are disabled for all users without exceptions. The default value is `true`. Optional.|
### [institutionData ](https://docs.microsoft.com/graph/api/resources/institutiondata?view=graph-rest-1.0&tabs=http)
| Property     | Type                                 | Description                                              |
|:-------------|:-------------------------------------|:---------------------------------------------------------|
|description   |String                                |Short description of the institution the user studied at. |
|displayName   |String                                |Name of the institution the user studied at.              |
|location      |physicalAddress |Address or location of the institute.                     |
|webUrl        |String                                |Link to the institution or department homepage.           |
### [invitation ](https://docs.microsoft.com/graph/api/resources/invitation?view=graph-rest-1.0&tabs=http)
| Property| Type|Description|
|:---|:---|:---|
|invitedUserDisplayName|String|The display name of the user being invited.|
|invitedUserEmailAddress|String|The email address of the user being invited. Required. The following special characters aren't permitted in the email address:<br><ul><li>Tilde (`~`)</li><li>Exclamation point (`!`)</li><li>Number sign (`#`)</li><li>Dollar sign (`$`)</li><li>Percent (`%`)</li><li>Circumflex (`^`)</li><li>Ampersand (`&`)</li><li>Asterisk (`*`)</li><li>Parentheses (`( )`)</li><li>Plus sign (`+`)</li><li>Equal sign (`=`)</li><li>Brackets (`[ ]`)</li><li>Braces (`{ }`)</li><li>Backslash (`\`)</li><li>Slash mark (`/`)</li><li>Pipe (`\|`)</li><li>Semicolon (`;`)</li><li>Colon (`:`)</li><li>Quotation marks (`"`)</li><li>Angle brackets (`< >`)</li><li>Question mark (`?`)</li><li>Comma (`,`)</li></ul><br>However, the following exceptions apply:<br><ul><li>A period (`.`) or a hyphen (`-`) is permitted anywhere in the user name, except at the beginning or end of the name.</li><li>An underscore (`_`) is permitted anywhere in the user name, including at the beginning or end of the name.</li></ul>|
|invitedUserMessageInfo|invitedUserMessageInfo|Contains configuration for the message being sent to the invited user, including customizing message text, language, and cc recipient list.|
|invitedUserType|String|The userType of the user being invited. By default, this is `Guest`. You can invite as `Member` if you're a company administrator. |
|inviteRedirectUrl|String|The URL the user should be redirected to after the invitation is redeemed. Required.|
|inviteRedeemUrl|String|The URL the user can use to redeem their invitation. Read-only.|
|resetRedemption|Boolean|Reset the user's redemption status and reinvite a user while retaining their user identifier, group memberships, and app assignments. This property allows you to enable a user to sign-in using a different email address from the one in the previous invitation. When `true`, the **invitedUser**/**id** relationship is required. For more information about using this property, see Reset redemption status for a guest user.|
|sendInvitationMessage|Boolean|Indicates whether an email should be sent to the user being invited. The default is `false`.|
|status|String|The status of the invitation. Possible values are: `PendingAcceptance`, `Completed`, `InProgress`, and `Error`.|
### [invitedUserMessageInfo ](https://docs.microsoft.com/graph/api/resources/invitedusermessageinfo?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|ccRecipients|recipient collection|Additional recipients the invitation message should be sent to. Currently only one additional recipient is supported.|
|customizedMessageBody|String|Customized message body you want to send if you don't want the default message.|
|messageLanguage|String|The language you want to send the default message in. If the customizedMessageBody is specified, this property is ignored, and the message is sent using the customizedMessageBody. The language format should be in ISO 639. The default is en-US.|
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
### [licenseDetails ](https://docs.microsoft.com/graph/api/resources/licensedetails?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| The unique identifier for the license detail object. Read-only. Key. Not nullable. |
|servicePlans|servicePlanInfo collection| Information about the service plans assigned with the license. Read-only. Not nullable. |
|skuId|Guid| Unique identifier (GUID) for the service SKU. Equal to the **skuId** property on the related subscribedSku object. Read-only. |
|skuPartNumber|String| Unique SKU display name. Equal to the **s
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
### [orgContact ](https://docs.microsoft.com/graph/api/resources/orgcontact?view=graph-rest-1.0&tabs=http)
| Property                     | Type                                                                     | Description                                                                                                                                                                                                                                                                                                                        |
|:-----------------------------|:-------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| addresses                    | physicalOfficeAddress collection             | Postal addresses for this organizational contact. For now a contact can only have one physical address.                                                                                                                                                                                                                            |
| companyName                  | String                                                                   | Name of the company that this organizational contact belongs to.  Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                          |
| department                   | String                                                                   | The name for the department in which the contact works.  Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                   |
| displayName                  | String                                                                   | Display name for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values), `$search`, and `$orderby`.                                                                                                                                                                                   |
| givenName                    | String                                                                   | First name for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                                |
| id                           | String                                                                   | Unique identifier for this organizational contact.  Supports `$filter` (`eq`, `ne`, `not`, `in`).                                                                                                                                                                                                                                  |
| jobTitle                     | String                                                                   | Job title for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                                 |
| mail                         | String                                                                   | The SMTP address for the contact, for example, "jeff@contoso.com". Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                             |
| mailNickname                 | String                                                                   | Email alias (portion of email address pre-pending the @ symbol) for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                           |
| serviceProvisioningErrors    | serviceProvisioningError collection       | Errors published by a federated service describing a non-transient, service-specific error regarding the properties or link from an organizational contact object . <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance).  |
| onPremisesLastSyncDateTime   | DateTimeOffset                                                           | Date and time when this organizational contact was last synchronized from on-premises AD. This date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).                             |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | List of any synchronization provisioning errors for this organizational contact. Supports `$filter` (`eq`, `not` for **category** and **propertyCausingError**), `/$count eq 0`, `/$count ne 0`.                                                                                                                                                                                                                 |
| onPremisesSyncEnabled        | Boolean                                                                  | `true` if this object is synced from an on-premises directory; `false` if this object was originally synced from an on-premises directory but is no longer synced and now mastered in Exchange; `null` if this object has never been synced from an on-premises directory (default). <br/> <br/> Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` for `null` values). |
| phones                       | phone collection                                             | List of phones for this organizational contact. Phone types can be mobile, business, and businessFax. Only one of each type can ever be present in the collection.                                                                                                                                                                 |
| proxyAddresses               | String collection                                                        | For example: "SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com". The **any** operator is required for filter expressions on multi-valued properties. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `/$count eq 0`, `/$count ne 0`).                                                                                                              |
| surname                      | String                                                                   | Last name for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                                 |
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
### [servicePrincipal ](https://docs.microsoft.com/graph/api/resources/serviceprincipal?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
| accountEnabled |Boolean| `true` if the service principal account is enabled; otherwise, `false`. If set to `false`, then no users are able to sign in to this app, even if they're assigned to it. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| addIns | addIn collection | Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams may set the addIns property for its "FileHandler" functionality. This lets services like Microsoft 365 call the application in the context of a document the user is working on.|
|alternativeNames|String collection| Used to retrieve service principals by subscription, identify resource group and full resource IDs for managed identities. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|appDescription|String|The description exposed by the associated application.|
|appDisplayName|String|The display name exposed by the associated application.|
|appId|String|The unique identifier for the associated application (its **appId** property). Alternate key. Supports `$filter` (`eq`, `ne`, `not`, `in`, `startsWith`).|
|applicationTemplateId|String|Unique identifier of the applicationTemplate. Supports `$filter` (`eq`, `not`, `ne`). Read-only. `null` if the service principal wasn't created from an application template.|
|appOwnerOrganizationId|Guid|Contains the tenant ID where the application is registered. This is applicable only to service principals backed by applications. Supports `$filter` (`eq`, `ne`, `NOT`, `ge`, `le`).|
|appRoleAssignmentRequired|Boolean|Specifies whether users or other service principals need to be granted an app role assignment for this service principal before users can sign in or apps can get tokens. The default value is `false`. Not nullable. <br><br>Supports `$filter` (`eq`, `ne`, `NOT`). |
|appRoles|appRole collection|The roles exposed by the application that's linked to this service principal. For more information, see the **appRoles** property definition on the application entity. Not nullable. |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). Filter value is case sensitive.|
| deletedDateTime | DateTimeOffset | The date and time the service principal was deleted. Read-only. |
| description | String | Free text field to provide an internal end-user facing description of the service principal. End-user portals such MyApps displays the application description in this field. The maximum allowed size is 1,024 characters. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`.|
| disabledByMicrosoftStatus | String | Specifies whether Microsoft has disabled the registered application. Possible values are: `null` (default value), `NotDisabled`, and `DisabledDueToViolationOfServicesAgreement` (reasons include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement). <br><br> Supports `$filter` (`eq`, `ne`, `not`).  |
|displayName|String|The display name for the service principal. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
|homepage|String|Home page or landing page of the application.|
|id|String|The unique identifier for the service principal. Inherited from directoryObject. Key. Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| info | informationalUrl | Basic profile information of the acquired application such as app's marketing, support, terms of service and privacy statement URLs. The terms of service and privacy statement are surfaced to users through the user consent experience. For more info, see How to: Add Terms of service and privacy statement for registered Microsoft Entra apps. <br><br>Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values).  |
|keyCredentials|keyCredential collection|The collection of key credentials associated with the service principal. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`).            |
|loginUrl|String|Specifies the URL where the service provider redirects the user to Microsoft Entra ID to authenticate. Microsoft Entra ID uses the URL to launch the application from Microsoft 365 or the Microsoft Entra My Apps. When blank, Microsoft Entra ID performs IdP-initiated sign-on for applications configured with SAML-based single sign-on. The user launches the application from Microsoft 365, the Microsoft Entra My Apps, or the Microsoft Entra SSO URL.|
|logoutUrl|String| Specifies the URL that the Microsoft's authorization service uses to sign out a user using OpenID Connect front-channel, back-channel, or SAML sign out protocols.|
|notes|String|Free text field to capture information about the service principal, typically used for operational purposes. Maximum allowed size is 1,024 characters.|
|notificationEmailAddresses|String collection|Specifies the list of email addresses where Microsoft Entra ID sends a notification when the active certificate is near the expiration date. This is only for the certificates used to sign the SAML token issued for Microsoft Entra Gallery applications.|
|oauth2PermissionScopes|permissionScope collection|The delegated permissions exposed by the application. For more information, see the **oauth2PermissionScopes** property on the application entity's **api** property. Not nullable.|
| passwordCredentials | passwordCredential collection|The collection of password credentials associated with the application. Not nullable.|
|preferredSingleSignOnMode|string|Specifies the single sign-on mode configured for this application. Microsoft Entra ID uses the preferred single sign-on mode to launch the application from Microsoft 365 or the My Apps portal. The supported values are `password`, `saml`, `notSupported`, and `oidc`.|
|preferredTokenSigningKeyThumbprint|String|This property can be used on SAML applications (apps that have **preferredSingleSignOnMode** set to `saml`) to control which certificate is used to sign the SAML responses. For applications that aren't SAML, don't write or otherwise rely on this property.|
|replyUrls|String collection|The URLs that user tokens are sent to for sign in with the associated application, or the redirect URIs that OAuth 2.0 authorization codes and access tokens are sent to for the associated application. Not nullable. |
|resourceSpecificApplicationPermissions|resourceSpecificPermission collection|The resource-specific application permissions exposed by this application. Currently, resource-specific permissions are only supported for Teams apps accessing to specific chats and teams using Microsoft Graph. Read-only.|
|samlSingleSignOnSettings|samlSingleSignOnSettings|The collection for settings related to saml single sign-on.|
|servicePrincipalNames|String collection|Contains the list of **identifiersUris**, copied over from the associated application. Additional values can be added to hybrid applications. These values can be used to identify the permissions exposed by this app within Microsoft Entra ID. For example,<ul><li>Client apps can specify a resource URI that is based on the values of this property to acquire an access token, which is the URI returned in the "aud" claim.</li></ul><br>The any operator is required for filter expressions on multi-valued properties. Not nullable. <br><br> Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|servicePrincipalType|String|Identifies whether the service principal represents an application, a managed identity, or a legacy application. This is set by Microsoft Entra ID internally. The **servicePrincipalType** property can be set to three different values: <ul><li>__Application__ - A service principal that represents an application or service. The **appId** property identifies the associated app registration, and matches the **appId** of an application, possibly from a different tenant. If the associated app registration is missing, tokens aren't issued for the service principal.</li><li>__ManagedIdentity__ - A service principal that represents a managed identity. Service principals representing managed identities can be granted access and permissions, but can't be updated or modified directly.</li><li>__Legacy__ - A service principal that represents an app created before app registrations, or through legacy experiences. A legacy service principal can have credentials, service principal names, reply URLs, and other properties that are editable by an authorized user, but doesn't have an associated app registration. The **appId** value doesn't associate the service principal with an app registration. The service principal can only be used in the tenant where it was created.</li><li>__SocialIdp__ - For internal use. </ul>|
| signInAudience | String | Specifies the Microsoft accounts that are supported for the current application. Read-only. <br><br>Supported values are:<ul><li>`AzureADMyOrg`: Users with a Microsoft work or school account in my organization's Microsoft Entra tenant (single-tenant).</li><li>`AzureADMultipleOrgs`: Users with a Microsoft work or school account in any organization's Microsoft Entra tenant (multitenant).</li><li>`AzureADandPersonalMicrosoftAccount`: Users with a personal Microsoft account, or a work or school account in any organization's Microsoft Entra tenant.</li><li>`PersonalMicrosoftAccount`: Users with a personal Microsoft account only.</li></ul> |
|tags|String collection| Custom strings that can be used to categorize and identify the service principal. Not nullable. The value is the union of strings set here and on the associated application entity's **tags** property.<br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
| tokenEncryptionKeyId |String|Specifies the keyId of a public key from the keyCredentials collection. When configured, Microsoft Entra ID issues tokens for this application encrypted using the key specified by this property. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.|
| verifiedPublisher          | verifiedPublisher                            | Specifies the verified publisher of the application that's linked to this service principal.

### [shiftPreferences ](https://docs.microsoft.com/graph/api/resources/shiftpreferences?view=graph-rest-1.0&tabs=http)
|Property          |Type           |Description                                                                                                                                      |
|--------------|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| availability | shiftAvailability collection | Availability of the user to be scheduled for work and its recurrence pattern. |
| createdDateTime | `Edm.DateTimeOffset` | Timestamp corresponding to when the entity was created. |
| id | `Edm.String` | The identifier of the entity. |
| lastModifiedBy | identitySet | Identity of the person who last modified the entity. |
| lastModifiedDateTime | `Edm.DateTimeOffset` | Timestamp corresponding to when the entity was last modified. |
| @odata.etag | `Edm.String` | The change key for the entity. |
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
### [team ](https://docs.microsoft.com/graph/api/resources/team?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| id | string | The unique identifier of the team. The group has the same ID as the team. This property is read-only, and is inherited from the base entity type. |
|classification|string| An optional label. Typically describes the data or business sensitivity of the team. Must match one of a pre-configured set in the tenant's directory. |
|classSettings|teamClassSettings |Configure settings of a class. Available only when the team represents a class.|
|createdDateTime|dateTimeOffset|Timestamp at which the team was created.|
|description|string| An optional description for the team. Maximum length: 1024 characters. |
|displayName|string| The name of the team. |
|funSettings|teamFunSettings |Settings to configure use of Giphy, memes, and stickers in the team.|
|guestSettings|teamGuestSettings |Settings to configure whether guests can create, update, or delete channels in the team.|
|internalId | string | A unique ID for the team that has been used in a few places such as the audit log/Office 365 Management Activity API. |
|isArchived|Boolean|Whether this team is in read-only mode. |
|memberSettings|teamMemberSettings |Settings to configure whether members can perform certain actions, for example, create channels and add bots, in the team.|
|messagingSettings|teamMessagingSettings |Settings to configure messaging and mentions in the team.|
|specialization|teamSpecialization| Optional. Indicates whether the team is intended for a particular use case.  Each team specialization has access to unique behaviors and experiences targeted to its use case. |
|summary|teamSummary| Contains summary information about the team, including number of owners, members, and guests. |
|tenantId |string | The ID of the Microsoft Entra tenant. |
|visibility|teamVisibilityType| The visibility of the group and team. Defaults to Public. |
|webUrl|string (readonly) | A hyperlink that will go to the team in the Microsoft Teams client. This is the URL that you get when you right-click a team in the Microsoft Teams client and select **G
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
