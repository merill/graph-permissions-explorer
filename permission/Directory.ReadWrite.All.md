# Directory.ReadWrite.All

> Allows the app to read and write data in your organization's directory, such as users, and groups.  It does not allow the app to delete users or groups, or reset user passwords.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/user-reprocesslicenseassignment?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /appCatalogs/teamsApps/{id}](https://docs.microsoft.com/graph/api/teamsapp-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications(appId='{appId}')/extensionProperties/{extensionPropertyId}](https://docs.microsoft.com/graph/api/extensionproperty-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications(appId='{appId}')/owners/{id}/$ref](https://docs.microsoft.com/graph/api/application-delete-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{application ObjectId}/extensionProperties/{extensionPropertyId}](https://docs.microsoft.com/graph/api/extensionproperty-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /applications/{id}/owners/{id}/$ref](https://docs.microsoft.com/graph/api/application-delete-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groupLifecyclePolicies/{id}](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groups/{id}/members/{id}/$ref](https://docs.microsoft.com/graph/api/group-delete-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groups/{id}/owners/{id}/$ref](https://docs.microsoft.com/graph/api/group-delete-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groupSettings/{groupSettingId}](https://docs.microsoft.com/graph/api/groupsetting-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /oauth2PermissionGrants/{id}](https://docs.microsoft.com/graph/api/oauth2permissiongrant-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /oAuth2PermissionGrants/{id}](https://docs.microsoft.com/graph/api/oauth2permissiongrant-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /onPremisesPublishingProfiles/{profile-id}/agents/{agent-id}](https://docs.microsoft.com/graph/api/onpremisesagentgroup-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /onPremisesPublishingProfiles/{profile-id}/agents/{agent-id}/agentGroups/{agentGroup-id}/$ref](https://docs.microsoft.com/graph/api/onpremisesagent-delete-agentgroups?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /onPremisesPublishingProfiles/applicationProxy/connectorGroups/{id}](https://docs.microsoft.com/graph/api/connectorgroup-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /policies/featureRolloutPolicies/{id}](https://docs.microsoft.com/graph/api/featurerolloutpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /policies/featureRolloutPolicies/{policyId}/appliesTo/{directoryObjectId}/$ref](https://docs.microsoft.com/graph/api/featurerolloutpolicy-delete-appliesto?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /roleManagement/deviceManagement/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-delete?view=graph-rest-1.0&tabs=http)|
|V1|A|[DELETE /schemaExtensions/{id}](https://docs.microsoft.com/graph/api/schemaextension-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')](https://docs.microsoft.com/graph/api/serviceprincipal-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals(appId='{appId}')/owners/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{id}](https://docs.microsoft.com/graph/api/serviceprincipal-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /serviceprincipals/{id}/owners/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-owners?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /servicePrincipals/{id}/owners/{id}/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-owners?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-delete-remotedesktopsecurityconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration/targetDeviceGroups/{targetDeviceGroupId}/$ref](https://docs.microsoft.com/graph/api/remotedesktopsecurityconfiguration-delete-targetdevicegroups?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /settings/{directorySettingId}](https://docs.microsoft.com/graph/api/directorysetting-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /teams/{team-id}/channels/{channel-id}](https://docs.microsoft.com/graph/api/channel-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /teams/{team-id}/channels/{channel-id}/tabs/{tab-id}](https://docs.microsoft.com/graph/api/channel-delete-tabs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /teams/{team-id}/installedApps/{app-installation-id}](https://docs.microsoft.com/graph/api/team-delete-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id}/manager/$ref](https://docs.microsoft.com/graph/api/user-delete-manager?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id}/sponsors/{id}/$ref](https://docs.microsoft.com/graph/api/user-delete-sponsors?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /administrativeUnits](https://docs.microsoft.com/graph/api/directory-list-administrativeunits?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/members](https://docs.microsoft.com/graph/api/administrativeunit-list-members?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/members/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get-members?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/members/$ref](https://docs.microsoft.com/graph/api/administrativeunit-list-members?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/scopedRoleMembers](https://docs.microsoft.com/graph/api/administrativeunit-list-scopedrolemembers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/{id}/scopedRoleMembers/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get-scopedrolemembers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /administrativeUnits/delta](https://docs.microsoft.com/graph/api/administrativeunit-delta?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /appCatalogs/teamsApps](https://docs.microsoft.com/graph/api/appcatalogs-list-teamsapps?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /applications](https://docs.microsoft.com/graph/api/application-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')](https://docs.microsoft.com/graph/api/application-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')/extensionProperties](https://docs.microsoft.com/graph/api/application-list-extensionproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications(appId='{appId}')/owners](https://docs.microsoft.com/graph/api/application-list-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{application ObjectId}/extensionProperties](https://docs.microsoft.com/graph/api/application-list-extensionproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{applicationObjectId}](https://docs.microsoft.com/graph/api/application-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/{id}/owners](https://docs.microsoft.com/graph/api/application-list-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /applications/delta](https://docs.microsoft.com/graph/api/application-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts](https://docs.microsoft.com/graph/api/orgcontact-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}](https://docs.microsoft.com/graph/api/orgcontact-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/directReports](https://docs.microsoft.com/graph/api/orgcontact-list-directreports?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/manager](https://docs.microsoft.com/graph/api/orgcontact-get-manager?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/memberOf](https://docs.microsoft.com/graph/api/orgcontact-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/delta](https://docs.microsoft.com/graph/api/orgcontact-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contracts](https://docs.microsoft.com/graph/api/contract-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contracts/{id}](https://docs.microsoft.com/graph/api/contract-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices](https://docs.microsoft.com/graph/api/device-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices(deviceId='{deviceId}')](https://docs.microsoft.com/graph/api/device-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices(deviceId='{deviceId}')/memberOf](https://docs.microsoft.com/graph/api/device-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices(deviceId='{deviceId}')/registeredOwners](https://docs.microsoft.com/graph/api/device-list-registeredowners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices(deviceId='{deviceId}')/registeredUsers](https://docs.microsoft.com/graph/api/device-list-registeredusers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices(deviceId='{deviceId}')/transitiveMemberOf](https://docs.microsoft.com/graph/api/device-list-transitivememberof?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /devices(deviceId='{deviceId}')/usageRights](https://docs.microsoft.com/graph/api/device-list-usagerights?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /devices/{id | userPrincipalName}/transitiveMemberOf](https://docs.microsoft.com/graph/api/device-list-transitivememberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices/{id}](https://docs.microsoft.com/graph/api/device-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices/{id}/memberOf](https://docs.microsoft.com/graph/api/device-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices/{id}/registeredOwners](https://docs.microsoft.com/graph/api/device-list-registeredowners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /devices/{id}/registeredUsers](https://docs.microsoft.com/graph/api/device-list-registeredusers?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /devices/{id}/transitiveMemberOf](https://docs.microsoft.com/graph/api/device-list-transitivememberof?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /devices/{objectId}/usageRights](https://docs.microsoft.com/graph/api/device-list-usagerights?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits](https://docs.microsoft.com/graph/api/directory-list-administrativeunits?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/members](https://docs.microsoft.com/graph/api/administrativeunit-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/members/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/members/$ref](https://docs.microsoft.com/graph/api/administrativeunit-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/scopedRoleMembers](https://docs.microsoft.com/graph/api/administrativeunit-list-scopedrolemembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directory/administrativeUnits/{id}/scopedRoleMembers/{id}](https://docs.microsoft.com/graph/api/administrativeunit-get-scopedrolemembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles](https://docs.microsoft.com/graph/api/directoryrole-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles(roleTemplateId='{roleTemplateId}')](https://docs.microsoft.com/graph/api/directoryrole-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles(roleTemplateId='{roleTemplateId}')/members](https://docs.microsoft.com/graph/api/directoryrole-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles(roleTemplateId='{roleTemplateId}')/scopedMembers](https://docs.microsoft.com/graph/api/directoryrole-list-scopedmembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles/{role-id}](https://docs.microsoft.com/graph/api/directoryrole-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles/{role-id}/members](https://docs.microsoft.com/graph/api/directoryrole-list-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryroles/{role-id}/scopedMembers](https://docs.microsoft.com/graph/api/directoryrole-list-scopedmembers?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoles/delta](https://docs.microsoft.com/graph/api/directoryrole-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoleTemplates](https://docs.microsoft.com/graph/api/directoryroletemplate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /directoryRoleTemplates/{id}](https://docs.microsoft.com/graph/api/directoryroletemplate-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /directorySettingTemplates](https://docs.microsoft.com/graph/api/directorysettingtemplate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /directorySettingTemplates/{id}](https://docs.microsoft.com/graph/api/directorysettingtemplate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /groupLifecyclePolicies](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groupLifecyclePolicies/{id}](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups](https://docs.microsoft.com/graph/api/group-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}](https://docs.microsoft.com/graph/api/group-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/appRoleAssignments](https://docs.microsoft.com/graph/api/group-list-approleassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/groupLifecyclePolicies](https://docs.microsoft.com/graph/api/group-list-grouplifecyclepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/memberOf](https://docs.microsoft.com/graph/api/group-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/transitiveMemberOf](https://docs.microsoft.com/graph/api/group-list-transitivememberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/delta](https://docs.microsoft.com/graph/api/group-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groupSettings](https://docs.microsoft.com/graph/api/group-list-settings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groupSettings/{groupSettingId}](https://docs.microsoft.com/graph/api/groupsetting-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groupSettingTemplates](https://docs.microsoft.com/graph/api/groupsettingtemplate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groupSettingTemplates/{id}](https://docs.microsoft.com/graph/api/groupsettingtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me](https://docs.microsoft.com/graph/api/user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/createdObjects](https://docs.microsoft.com/graph/api/user-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/directReports](https://docs.microsoft.com/graph/api/user-list-directreports?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/joinedTeams](https://docs.microsoft.com/graph/api/user-list-joinedteams?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/licenseDetails](https://docs.microsoft.com/graph/api/user-list-licensedetails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/manager](https://docs.microsoft.com/graph/api/user-list-manager?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/ownedDevices](https://docs.microsoft.com/graph/api/user-list-owneddevices?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/ownedObjects](https://docs.microsoft.com/graph/api/user-list-ownedobjects?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/registeredDevices](https://docs.microsoft.com/graph/api/user-list-registereddevices?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/scopedRoleMemberOf ](https://docs.microsoft.com/graph/api/user-list-scopedrolememberof?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /oauth2PermissionGrants](https://docs.microsoft.com/graph/api/oauth2permissiongrant-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /oauth2PermissionGrants/{id}](https://docs.microsoft.com/graph/api/oauth2permissiongrant-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /oauth2PermissionGrants/delta](https://docs.microsoft.com/graph/api/oauth2permissiongrant-delta?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/](https://docs.microsoft.com/graph/api/onpremisespublishingprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/agentGroups](https://docs.microsoft.com/graph/api/onpremisesagentgroup-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/agents](https://docs.microsoft.com/graph/api/onpremisesagent-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/agents/{agent-id}](https://docs.microsoft.com/graph/api/onpremisesagentgroup-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/{profile-id}/agents/{agent-id}?$expand=agentGroups](https://docs.microsoft.com/graph/api/onpremisesagent-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectorGroups](https://docs.microsoft.com/graph/api/connectorgroup-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectorGroups/{id}](https://docs.microsoft.com/graph/api/connectorgroup-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectorGroups/{id}/applications](https://docs.microsoft.com/graph/api/connectorgroup-list-applications?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectorGroups/{id}/members](https://docs.microsoft.com/graph/api/connectorgroup-list-members?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectors](https://docs.microsoft.com/graph/api/connector-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectors/{id}](https://docs.microsoft.com/graph/api/connector-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /onPremisesPublishingProfiles/applicationProxy/connectors/{id}/memberOf](https://docs.microsoft.com/graph/api/connector-list-memberof?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /organization](https://docs.microsoft.com/graph/api/organization-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}](https://docs.microsoft.com/graph/api/organization-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /policies/adminConsentRequestPolicy](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /policies/featureRolloutPolicies](https://docs.microsoft.com/graph/api/featurerolloutpolicies-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /policies/featureRolloutPolicies/{id}](https://docs.microsoft.com/graph/api/featurerolloutpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplication-list-roleassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /roleManagement/directory/transitiveRoleAssignments?$filter=principalId eq '{principalId}'](https://docs.microsoft.com/graph/api/rbacapplication-list-transitiveroleassignments?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /servicePrincipals](https://docs.microsoft.com/graph/api/serviceprincipal-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')](https://docs.microsoft.com/graph/api/serviceprincipal-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/appRoleAssignedTo](https://docs.microsoft.com/graph/api/serviceprincipal-list-approleassignedto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/appRoleAssignments](https://docs.microsoft.com/graph/api/serviceprincipal-list-approleassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/createdObjects](https://docs.microsoft.com/graph/api/serviceprincipal-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/memberOf](https://docs.microsoft.com/graph/api/serviceprincipal-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/oauth2PermissionGrants](https://docs.microsoft.com/graph/api/serviceprincipal-list-oauth2permissiongrants?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/ownedObjects](https://docs.microsoft.com/graph/api/serviceprincipal-list-ownedobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/owners](https://docs.microsoft.com/graph/api/serviceprincipal-list-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{appId}')/transitiveMemberOf](https://docs.microsoft.com/graph/api/serviceprincipal-list-transitivememberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals(appId='{client-servicePrincipal-appId}')/appRoleAssignments/{appRoleAssignment-id}](https://docs.microsoft.com/graph/api/approleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{client-serviceprincipal-id}/appRoleAssignments/{appRoleAssignment-id}](https://docs.microsoft.com/graph/api/approleassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}](https://docs.microsoft.com/graph/api/serviceprincipal-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/appRoleAssignedTo](https://docs.microsoft.com/graph/api/serviceprincipal-list-approleassignedto?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/appRoleAssignments](https://docs.microsoft.com/graph/api/serviceprincipal-list-approleassignments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/createdObjects](https://docs.microsoft.com/graph/api/serviceprincipal-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/memberOf](https://docs.microsoft.com/graph/api/serviceprincipal-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/oauth2PermissionGrants](https://docs.microsoft.com/graph/api/serviceprincipal-list-oauth2permissiongrants?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/ownedObjects](https://docs.microsoft.com/graph/api/serviceprincipal-list-ownedobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/owners](https://docs.microsoft.com/graph/api/serviceprincipal-list-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/transitiveMemberOf](https://docs.microsoft.com/graph/api/serviceprincipal-list-transitivememberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration](https://docs.microsoft.com/graph/api/remotedesktopsecurityconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration/targetDeviceGroups](https://docs.microsoft.com/graph/api/remotedesktopsecurityconfiguration-list-targetdevicegroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration/targetDeviceGroups/{targetDeviceGroupId}](https://docs.microsoft.com/graph/api/targetdevicegroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/delta](https://docs.microsoft.com/graph/api/serviceprincipal-delta?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /settings](https://docs.microsoft.com/graph/api/group-list-settings?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /settings/{directorySettingId}](https://docs.microsoft.com/graph/api/directorysetting-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /subscribedSkus](https://docs.microsoft.com/graph/api/subscribedsku-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /subscribedSkus/{id}](https://docs.microsoft.com/graph/api/subscribedsku-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{id}/channels/{id}/tabs](https://docs.microsoft.com/graph/api/channel-list-tabs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{id}/installedApps/{id}](https://docs.microsoft.com/graph/api/team-get-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{team-id}](https://docs.microsoft.com/graph/api/team-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{team-id}/channels](https://docs.microsoft.com/graph/api/channel-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{team-id}/channels/{channel-id}](https://docs.microsoft.com/graph/api/channel-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /teams/{team-id}/channels/{channel-id}/tabs](https://docs.microsoft.com/graph/api/channel-list-tabs?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /teams/{team-id}/channels/{channel-id}/tabs/{tab-id}](https://docs.microsoft.com/graph/api/channel-get-tabs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /teams/{team-id}/installedApps](https://docs.microsoft.com/graph/api/team-list-installedapps?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users](https://docs.microsoft.com/graph/api/user-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | user-principal-name}/joinedTeams](https://docs.microsoft.com/graph/api/user-list-joinedteams?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/createdObjects](https://docs.microsoft.com/graph/api/user-list-createdobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/directReports](https://docs.microsoft.com/graph/api/user-list-directreports?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/manager](https://docs.microsoft.com/graph/api/user-list-manager?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/ownedDevices](https://docs.microsoft.com/graph/api/user-list-owneddevices?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/ownedObjects](https://docs.microsoft.com/graph/api/user-list-ownedobjects?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/registeredDevices](https://docs.microsoft.com/graph/api/user-list-registereddevices?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id}/licenseDetails](https://docs.microsoft.com/graph/api/user-list-licensedetails?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{id}/scopedRoleMemberOf](https://docs.microsoft.com/graph/api/user-list-scopedrolememberof?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{user-id}/licenseDetails/getTeamsLicensingDetails](https://docs.microsoft.com/graph/api/licensedetails-getteamslicensingdetails?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{userId}/usageRights](https://docs.microsoft.com/graph/api/user-list-usagerights?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/delta](https://docs.microsoft.com/graph/api/user-delta?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /devices(deviceId='{deviceId}')](https://docs.microsoft.com/graph/api/device-update?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /devices/{id}](https://docs.microsoft.com/graph/api/device-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groupLifecyclePolicies/{id}](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/(uniqueName='uniqueName')](https://docs.microsoft.com/graph/api/group-upsert?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/{id}](https://docs.microsoft.com/graph/api/group-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groupSettings/{groupSettingId}](https://docs.microsoft.com/graph/api/groupsetting-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /oauth2PermissionGrants/{id}](https://docs.microsoft.com/graph/api/oauth2permissiongrant-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /onPremisesPublishingProfiles/{profile-id}/agentGroups/{agentGroup-id}](https://docs.microsoft.com/graph/api/onpremisesagentgroup-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /onPremisesPublishingProfiles/{profile-id}/hybridAgentUpdaterConfiguration](https://docs.microsoft.com/graph/api/onpremisespublishingprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /onPremisesPublishingProfiles/applicationProxy/connectorGroups/{id}](https://docs.microsoft.com/graph/api/connectorgroup-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /policies/featureRolloutPolicies/{id}](https://docs.microsoft.com/graph/api/featurerolloutpolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /roleManagement/deviceManagement/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-update?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /schemaExtensions/{id}](https://docs.microsoft.com/graph/api/schemaextension-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /servicePrincipals(appId='{appId}')](https://docs.microsoft.com/graph/api/serviceprincipal-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /servicePrincipals(appId='appId')](https://docs.microsoft.com/graph/api/serviceprincipal-upsert?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /servicePrincipals/{id}](https://docs.microsoft.com/graph/api/serviceprincipal-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration](https://docs.microsoft.com/graph/api/remotedesktopsecurityconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration/targetDeviceGroups/{targetDeviceGroupId}](https://docs.microsoft.com/graph/api/targetdevicegroup-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /settings/{directorySettingId}](https://docs.microsoft.com/graph/api/directorysetting-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /teams/{id}/channels/{id}/members/{id}](https://docs.microsoft.com/graph/api/conversationmember-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /teams/{id}/members/{id}](https://docs.microsoft.com/graph/api/conversationmember-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /teams/{team-id}](https://docs.microsoft.com/graph/api/team-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /teams/{team-id}/channels/{channel-id}](https://docs.microsoft.com/graph/api/channel-patch?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /teams/{team-id}/channels/{channel-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/channel-update-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /teams/{team-id}/channels/{channel-id}/tabs/{tab-id}](https://docs.microsoft.com/graph/api/channel-patch-tabs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /teams/{team-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/team-update-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}](https://docs.microsoft.com/graph/api/user-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /administrativeUnits/{id}/members/$ref](https://docs.microsoft.com/graph/api/administrativeunit-post-members?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /appCatalogs/teamsApps](https://docs.microsoft.com/graph/api/teamsapp-publish?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /appCatalogs/teamsApps/{id}/appDefinitions](https://docs.microsoft.com/graph/api/teamsapp-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/addKey](https://docs.microsoft.com/graph/api/application-addkey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/addPassword](https://docs.microsoft.com/graph/api/application-addpassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/extensionProperties](https://docs.microsoft.com/graph/api/application-post-extensionproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/owners/$ref](https://docs.microsoft.com/graph/api/application-post-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/removeKey](https://docs.microsoft.com/graph/api/application-removekey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications(appId='{appId}')/removePassword](https://docs.microsoft.com/graph/api/application-removepassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{application ObjectId}/extensionProperties](https://docs.microsoft.com/graph/api/application-post-extensionproperty?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/addKey](https://docs.microsoft.com/graph/api/application-addkey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/addPassword](https://docs.microsoft.com/graph/api/application-addpassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/owners/$ref](https://docs.microsoft.com/graph/api/application-post-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/removeKey](https://docs.microsoft.com/graph/api/application-removekey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applications/{id}/removePassword](https://docs.microsoft.com/graph/api/application-removepassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /applicationTemplates/{applicationTemplate-id}/instantiate](https://docs.microsoft.com/graph/api/applicationtemplate-instantiate?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /contacts/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/orgcontact-retryserviceprovisioning?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /directory/administrativeUnits/{id}/members/$ref](https://docs.microsoft.com/graph/api/administrativeunit-post-members?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directoryObjects/{id}/checkMemberGroups](https://docs.microsoft.com/graph/api/directoryobject-checkmembergroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directoryObjects/{id}/checkMemberObjects](https://docs.microsoft.com/graph/api/directoryobject-checkmemberobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directoryObjects/{id}/getMemberGroups](https://docs.microsoft.com/graph/api/directoryobject-getmembergroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directoryObjects/{id}/getMemberObjects](https://docs.microsoft.com/graph/api/directoryobject-getmemberobjects?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /directoryObjects/validateProperties](https://docs.microsoft.com/graph/api/directoryobject-validateproperties?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groupLifecyclePolicies](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-post-grouplifecyclepolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groupLifecyclePolicies/{id}/addGroup](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-addgroup?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groupLifecyclePolicies/{id}/removeGroup](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-removegroup?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /groupLifecyclePolicies/renewGroup](https://docs.microsoft.com/graph/api/grouplifecyclepolicy-renewgroup?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /groups](https://docs.microsoft.com/graph/api/group-post-groups?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /groups/{groupsId}/deletePasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/group-deletepasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /groups/{groupsId}/getPasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/group-getpasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /groups/{id}/assignLicense](https://docs.microsoft.com/graph/api/group-assignlicense?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/owners/$ref](https://docs.microsoft.com/graph/api/group-post-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/renew](https://docs.microsoft.com/graph/api/group-renew?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/group-retryserviceprovisioning?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groupSettings](https://docs.microsoft.com/graph/api/group-post-settings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /invitations](https://docs.microsoft.com/graph/api/invitation-post?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/invalidateAllRefreshTokens](https://docs.microsoft.com/graph/api/user-invalidateallrefreshtokens?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/revokeSignInSessions](https://docs.microsoft.com/graph/api/user-revokesigninsessions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /oauth2PermissionGrants](https://docs.microsoft.com/graph/api/oauth2permissiongrant-post?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /onPremisesPublishingProfiles/{profile-id}/agentGroups](https://docs.microsoft.com/graph/api/onpremisesagentgroup-post?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /onPremisesPublishingProfiles/{profile-id}/agents/{agent-id}/agentGroups/$ref](https://docs.microsoft.com/graph/api/onpremisesagent-post-agentgroups?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /onPremisesPublishingProfiles/applicationProxy/connectorGroups](https://docs.microsoft.com/graph/api/connectorgroup-post-connectorgroups?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /onPremisesPublishingProfiles/applicationProxy/connectorGroups/{id}/members/$ref](https://docs.microsoft.com/graph/api/connectorgroup-post-members?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /onPremisesPublishingProfiles/applicationProxy/connectors/{id}/memberOf/$ref](https://docs.microsoft.com/graph/api/connector-post-memberof?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /orgContacts/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/orgcontact-retryserviceprovisioning?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /policies/featureRolloutPolicies](https://docs.microsoft.com/graph/api/featurerolloutpolicies-post?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /policies/featureRolloutPolicies/{id}/appliesTo/$ref](https://docs.microsoft.com/graph/api/featurerolloutpolicy-post-appliesto?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /roleManagement/deviceManagement/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-post-roledefinitions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-post-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /schemaExtensions](https://docs.microsoft.com/graph/api/schemaextension-post-schemaextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals](https://docs.microsoft.com/graph/api/serviceprincipal-post-serviceprincipals?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/addKey](https://docs.microsoft.com/graph/api/serviceprincipal-addkey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/addPassword](https://docs.microsoft.com/graph/api/serviceprincipal-addpassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/addTokenSigningCertificate](https://docs.microsoft.com/graph/api/serviceprincipal-addtokensigningcertificate?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /servicePrincipals(appId='{appId}')/createPasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-createpasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /servicePrincipals(appId='{appId}')/deletePasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-deletepasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /servicePrincipals(appId='{appId}')/getPasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-getpasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/owners/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-owners?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /serviceprincipals(appId='{appId}')/removeKey](https://docs.microsoft.com/graph/api/serviceprincipal-removekey?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/removeKey](https://docs.microsoft.com/graph/api/serviceprincipal-removekey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals(appId='{appId}')/removePassword](https://docs.microsoft.com/graph/api/serviceprincipal-removepassword?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /servicePrincipals(appId='{appId}')/updatePasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-updatepasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /serviceprincipals/{id}/addKey](https://docs.microsoft.com/graph/api/serviceprincipal-addkey?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /servicePrincipals/{id}/addKey](https://docs.microsoft.com/graph/api/serviceprincipal-addkey?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/addPassword](https://docs.microsoft.com/graph/api/serviceprincipal-addpassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/addTokenSigningCertificate](https://docs.microsoft.com/graph/api/serviceprincipal-addtokensigningcertificate?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /servicePrincipals/{id}/createPasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-createpasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /servicePrincipals/{id}/deletePasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-deletepasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /servicePrincipals/{id}/getPasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-getpasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/owners/$ref](https://docs.microsoft.com/graph/api/serviceprincipal-post-owners?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /serviceprincipals/{id}/removeKey](https://docs.microsoft.com/graph/api/serviceprincipal-removekey?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/removePassword](https://docs.microsoft.com/graph/api/serviceprincipal-removepassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema/directories/{directoryId}/discover](https://docs.microsoft.com/graph/api/synchronization-directorydefinition-discover?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /servicePrincipals/{id}/updatePasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/serviceprincipal-updatepasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration](https://docs.microsoft.com/graph/api/serviceprincipal-post-remotedesktopsecurityconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /servicePrincipals/{servicePrincipalsId}/remoteDesktopSecurityConfiguration/targetDeviceGroups](https://docs.microsoft.com/graph/api/remotedesktopsecurityconfiguration-post-targetdevicegroups?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /settings](https://docs.microsoft.com/graph/api/group-post-settings?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /teams](https://docs.microsoft.com/graph/api/team-post?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /teams/{id}/archive](https://docs.microsoft.com/graph/api/team-archive?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /teams/{id}/channels/{id}/tabs](https://docs.microsoft.com/graph/api/channel-post-tabs?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /teams/{id}/clone](https://docs.microsoft.com/graph/api/team-clone?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /teams/{id}/unarchive](https://docs.microsoft.com/graph/api/team-unarchive?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /teams/{team-id}/channels](https://docs.microsoft.com/graph/api/channel-post?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /teams/{team-id}/channels/{channel-id}/tabs](https://docs.microsoft.com/graph/api/channel-post-tabs?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /teams/{team-id}/installedApps](https://docs.microsoft.com/graph/api/team-post-installedapps?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /teams/{team-id}/installedApps/{app-installation-id}/upgrade](https://docs.microsoft.com/graph/api/team-teamsappinstallation-upgrade?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users](https://docs.microsoft.com/graph/api/user-post-users?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/assignLicense](https://docs.microsoft.com/graph/api/user-assignlicense?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{id | userPrincipalName}/invalidateAllRefreshTokens](https://docs.microsoft.com/graph/api/user-invalidateallrefreshtokens?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{id | userPrincipalName}/revokeSignInSessions](https://docs.microsoft.com/graph/api/user-revokesigninsessions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/reprocessLicenseAssignment](https://docs.microsoft.com/graph/api/user-reprocesslicenseassignment?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/user-retryserviceprovisioning?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id}/sponsors/$ref](https://docs.microsoft.com/graph/api/user-post-sponsors?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{usersId}/deletePasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/user-deletepasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /users/{usersId}/getPasswordSingleSignOnCredentials](https://docs.microsoft.com/graph/api/user-getpasswordsinglesignoncredentials?view=graph-rest-beta&tabs=http)|
|Beta|D|[PUT /applications/{id}/connectorGroup/$ref](https://docs.microsoft.com/graph/api/connectorgroup-post-applications?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /groups/{id}/team](https://docs.microsoft.com/graph/api/team-put-teams?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /policies/adminConsentRequestPolicy](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PUT /policies/adminConsentRequestPolicy ](https://docs.microsoft.com/graph/api/adminconsentrequestpolicy-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PUT /users/{id}/manager/$ref](https://docs.microsoft.com/graph/api/user-post-manager?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c5366453-9fb0-48a5-a156-24f0c49a4b84|
|**Consent Type**|Admin|
|**Display String**|Read and write directory data|
|**Description**|Allows the app to read and write data in your organization's directory, such as users, and groups.  It does not allow the app to delete users or groups, or reset user passwords.|
## Application Permission
|||
|-|-|
|**Id**|19dbc75e-c2e2-444c-a770-ec69d8559fc7|
|**Display String**|Read and write directory data|
|**Description**|Allows the app to read and write data in your organization's directory, such as users, and groups, without a signed-in user.  Does not allow user or group deletion.|
## Resources
### [accessReviewReviewerScope ](https://docs.microsoft.com/graph/api/resources/accessreviewreviewerscope?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| :-------------------------| :---------- | :---------- |
| query | String | The query specifying who will be the reviewer.|
| queryRoot | String | In the scenario where reviewers need to be specified dynamically, this property is used to indicate the relative source of the query. This property is only required if a relative query, for example, `./manager`, is specified. Possible value: `decisions`. |
| queryType | String | The type of query. Examples include `MicrosoftGraph` and `ARM`. |
### [addIn ](https://docs.microsoft.com/graph/api/resources/addin?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|GUID|The unique identifier for the **addIn** object.|
|properties|keyValue collection|The collection of key-value pairs that define parameters that the consuming service can use or call. You must specify this property when performing a POST or a PATCH operation on the **addIns** collection. Required.|
|type|string|The unique name for the functionality exposed by the app. |
### [adminConsentRequestPolicy ](https://docs.microsoft.com/graph/api/resources/adminconsentrequestpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabled|Boolean|Specifies whether the admin consent request feature is enabled or disabled. Required.|
|notifyReviewers|Boolean|Specifies whether reviewers will receive notifications. Required.|
|remindersEnabled|Boolean|Specifies whether reviewers will receive reminder emails. Required.|
|requestDurationInDays|Int32|Specifies the duration the request is active before it automatically expires if no decision is applied.|
|reviewers|accessReviewReviewerScope collection|The list of reviewers for the admin consent. Required.|
|version|Int32|Specifies the version of this policy. When the policy is updated, this version is updated. Read-only.|
### [administrativeUnit ](https://docs.microsoft.com/graph/api/resources/administrativeunit?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|description|String|An optional description for the administrative unit. Supports `$filter` (`eq`, `ne`, `in`, `startsWith`), `$search`.|
|displayName|String|Display name for the administrative unit. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`.|
|id|String|Unique identifier for the administrative unit. Read-only. Supports `$filter` (`eq`).|
|visibility|String|Controls whether the administrative unit and its members are hidden or public. Can be set to `HiddenMembership`. If not set (value is `null`), the default behavior is public. When set to `HiddenMembership`, only members of the administrative unit can list other members of the administrative unit.|
### [application ](https://docs.microsoft.com/graph/api/resources/application?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| addIns | addIn collection| Defines custom behavior that a consuming service can use to call an app in specific contexts. For example, applications that can render file streams can set the addIns property for its "FileHandler" functionality. This lets services like Microsoft 365 call the application in the context of a document the user is working on. |
| api | apiApplication | Specifies settings for an application that implements a web API. |
| appId | String | The unique identifier for the application that is assigned to an application by Microsoft Entra ID. Not nullable. Read-only. Alternate key. Supports `$filter` (`eq`).  |
| applicationTemplateId | String | Unique identifier of the applicationTemplate. Supports `$filter` (`eq`, `not`, `ne`). Read-only. `null` if the app wasn't created from an application template.|
| appRoles | appRole collection | The collection of roles defined for the application. With app role assignments, these roles can be assigned to users, groups, or service principals associated with other applications. Not nullable. |
|certification|certification|Specifies the certification status of the application.|
| createdDateTime | DateTimeOffset | The date and time the application was registered. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. <br><br> Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, and `eq` on `null` values) and `$orderby`. |
| deletedDateTime | DateTimeOffset | The date and time the application was deleted. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| description | String | Free text field to provide a description of the application object to end users. The maximum allowed size is 1,024 characters. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `startsWith`) and `$search`. |
| disabledByMicrosoftStatus | String | Specifies whether Microsoft has disabled the registered application. Possible values are: `null` (default value), `NotDisabled`, and `DisabledDueToViolationOfServicesAgreement` (reasons include suspicious, abusive, or malicious activity, or a violation of the Microsoft Services Agreement). <br><br> Supports `$filter` (`eq`, `ne`, `not`). |
| displayName | String | The display name for the application. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$search`, and `$orderby`. |
| groupMembershipClaims | String | Configures the `groups` claim issued in a user or OAuth 2.0 access token that the application expects. To set this attribute, use one of the following valid string values: `None`, `SecurityGroup` (for security groups and Microsoft Entra roles), `All` (this gets all of the security groups, distribution groups, and Microsoft Entra directory roles that the signed-in user is a member of). |
| id | String | Unique identifier for the application object. This property is referred to as **Object ID** in the Microsoft Entra admin center. Inherited from directoryObject. Key. Not nullable. Read-only. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
| identifierUris | String collection | Also known as App ID URI, this value is set when an application is used as a resource app. The identifierUris acts as the prefix for the scopes you reference in your API's code, and it must be globally unique. You can use the default value provided, which is in the form `api://<appId>`, or specify a more readable URI like `https://contoso.com/api`. For more information on valid identifierUris patterns and best practices, see Microsoft Entra application registration security best practices. Not nullable. <br><br>Supports `$filter` (`eq`, `ne`, `ge`, `le`, `startsWith`).|
| info | informationalUrl | Basic profile information of the application such as  app's marketing, support, terms of service and privacy statement URLs. The terms of service and privacy statement are surfaced to users through the user consent experience. For more info, see How to: Add Terms of service and privacy statement for registered Microsoft Entra apps. <br><br>Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, and `eq` on `null` values). |
| isDeviceOnlyAuthSupported | Boolean | Specifies whether this application supports device authentication without a user. The default is `false`.  |
| isFallbackPublicClient | Boolean | Specifies the fallback application type as public client, such as an installed application running on a mobile device. The default value is `false`, which means the fallback application type is confidential client such as a web app. There are certain scenarios where Microsoft Entra ID can't determine the client application type. For example, the ROPC flow where it's configured without specifying a redirect URI. In those cases, Microsoft Entra ID interprets the application type based on the value of this property.|
| keyCredentials | keyCredential collection | The collection of key credentials associated with the application. Not nullable. Supports `$filter` (`eq`, `not`, `ge`, `le`). |
| logo | Stream | The main logo for the application. Not nullable. |
| nativeAuthenticationApisEnabled | nativeAuthenticationApisEnabled | Specifies whether the Native Authentication APIs are enabled for the application. The possible values are: `none` and `all`. Default is `none`. For more information, see Native Authentication. |
| notes | String | Notes relevant for the management of the application. |
| oauth2RequiredPostResponse | Boolean | Specifies whether, as part of OAuth 2.0 token requests, Microsoft Entra ID allows POST requests, as opposed to GET requests. The default is `false`, which specifies that only GET requests are allowed. |
| optionalClaims | optionalClaims | Application developers can configure optional claims in their Microsoft Entra applications to specify the claims that are sent to their application by the Microsoft security token service. For more information, see How to: Provide optional claims to your app.|
| parentalControlSettings | parentalControlSettings |Specifies parental control settings for an application. |
| passwordCredentials | passwordCredential collection|The collection of password credentials associated with the application. Not nullable.|
| publicClient | publicClientApplication | Specifies settings for installed clients such as desktop or mobile devices. |
| publisherDomain | String | The verified publisher domain for the application. Read-only. For more information, see How to: Configure an application's publisher domain. Supports `$filter` (`eq`, `ne`, `ge`, `le`, `startsWith`).|
| requestSignatureVerification | requestSignatureVerification| Specifies whether this application requires Microsoft Entra ID to verify the signed authentication requests.|
| requiredResourceAccess |requiredResourceAccess collection| Specifies the resources that the application needs to access. This property also specifies the set of delegated permissions and application roles that it needs for each of those resources. This configuration of access to the required resources drives the consent experience. <br/><br/>No more than 50 resource services (APIs) can be configured. Beginning mid-October 2021, the total number of required permissions must not exceed 400. For more information, see Limits on requested permissions per app. Not nullable. <br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`).|
| samlMetadataUrl | String | The URL where the service exposes SAML metadata for federation. This property is valid only for single-tenant applications. Nullable. |
| serviceManagementReference | String | References application or service contact information from a Service or Asset Management database. Nullable. |
| servicePrincipalLockConfiguration | servicePrincipalLockConfiguration | Specifies whether sensitive properties of a multitenant application should be locked for editing after the application is provisioned in a tenant. Nullable. `null` by default. |
| signInAudience | String | Specifies the Microsoft accounts that are supported for the current application. The possible values are: `AzureADMyOrg` (default), `AzureADMultipleOrgs`, `AzureADandPersonalMicrosoftAccount`, and `PersonalMicrosoftAccount`. See more in the table. <br/><br/>The value of this object also limits the number of permissions an app can request. For more information, see Limits on requested permissions per app. <br><br>The value for this property has implications on other app object properties. As a result, if you change this property, you might need to change other properties first. For more information, see Validation differences for signInAudience.<br><br>Supports `$filter` (`eq`, `ne`, `not`).|
| spa                     | spaApplication                            | Specifies settings for a single-page application, including sign out URLs and redirect URIs for authorization codes and access tokens. |
| tags |String collection| Custom strings that can be used to categorize and identify the application. Not nullable. Strings added here will also appear in the **tags** property of any associated service principals.<br><br>Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`) and `$search`.|
| tokenEncryptionKeyId |String|Specifies the keyId of a public key from the keyCredentials collection. When configured, Microsoft Entra ID encrypts all the tokens it emits by using the key this property points to. The application code that receives the encrypted token must use the matching private key to decrypt the token before it can be used for the signed-in user.|
| uniqueName | String | The unique identifier that can be assigned to an application and used as an alternate key. Immutable. Read-only. |
| verifiedPublisher          | verifiedPublisher                            | Specifies the verified publisher of the application. For more information about how publisher verification helps support application security, trustworthiness, and compliance, see Publisher verification.|
| web |webApplication| Specifies settings for a web application. |
### [applicationServicePrincipal ](https://docs.microsoft.com/graph/api/resources/applicationserviceprincipal?view=graph-rest-1.0&tabs=http)
| Property         | Type                                                 | Description                                                     |
| :--------------- | :--------------------------------------------------- | :-------------------------------------------------------------- |
| application      | application           | Represents an application registered in Microsoft Entra ID. |
| servicePrincipal | servicePrincipal | Represents an instance of an application in a directory.        |
### [applicationTemplate ](https://docs.microsoft.com/graph/api/resources/applicationtemplate?view=graph-rest-1.0&tabs=http)
| Property                   | Type              | Description                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :------------------------- | :---------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| categories                 | String collection | The list of categories for the application. Supported values can be: `Collaboration`, `Business Management`, `Consumer`, `Content management`, `CRM`, `Data services`, `Developer services`, `E-commerce`, `Education`, `ERP`, `Finance`, `Health`, `Human resources`, `IT infrastructure`, `Mail`, `Management`, `Marketing`, `Media`, `Productivity`, `Project management`, `Telecommunications`, `Tools`, `Travel`, and `Web design & hosting`. |
| description                | String            | A description of the application.                                                                                                                                                                                                                                                                                                                                                                                                               |
| displayName                | String            | The name of the application.                                                                                                                                                                                                                                                                                                                                                                                                                    |
| homePageUrl                | String            | The home page URL of the application.                                                                                                                                                                                                                                                                                                                                                                                                           |
| id                         | String            | Unique identifier for the application. Read-only.                                                                                                                                                                                                                                                                                                                                                                                               |
| logoUrl                    | String            | The URL to get the logo for this application.                                                                                                                                                                                                                                                                                                                                                                                                   |
| publisher                  | String            | The name of the publisher for this application.                                                                                                                                                                                                                                                                                                                                                                                                 |
| supportedProvisioningTypes | String collection | The list of provisioning modes supported by this application. The only valid value is `sync`.                                                                                                                                                                                                                                                                                                                                                   |
| supportedSingleSignOnModes | String collection | The list of single sign-on modes supported by this application. The supported values are `oidc`, `password`, `saml`, and `notSupported`.                                                                                                                                                                                                                                                                                                            |
### [appRole ](https://docs.microsoft.com/graph/api/resources/approle?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|allowedMemberTypes|String collection|Specifies whether this app role can be assigned to users and groups (by setting to `"User"]`), to other application's (by setting to `["Application"]`, or both (by setting to `["User", "Application"]`). App roles supporting assignment to other applications' service principals are also known as [application permissions. The "Application" value is only supported for app roles defined on **application** entities.|
|description|String|The description for the app role. This is displayed when the app role is being assigned and, if the app role functions as an application permission, during  consent experiences.|
|displayName|String|Display name for the permission that appears in the app role assignment and consent experiences.|
|id|Guid|Unique role identifier inside the **appRoles** collection. When creating a new app role, a new GUID identifier must be provided. |
|isEnabled|Boolean|When creating or updating an app role, this must be set to **true** (which is the default). To delete a role, this must first be set to **false**.  At that point, in a subsequent call, this role may be removed.|
|origin|String| Specifies if the app role is defined on the application object or on the servicePrincipal entity. Must _not_ be included in any POST or PATCH requests. Read-only. |
|value|String|Specifies the value to include in the `roles` claim in ID tokens and access tokens authenticating an assigned user or service principal. Must not exceed 120 characters in length. Allowed characters are `:` `!` `#` `$` `%` `&` `'` `(` `)` `*` `+` `,` `-` `.` `/` `:` `;` <code>&lt;</code> `=` <code>&gt;</code> `?` `@` `[` `]` `^` `+` `_` <code>&#96;</code> `{` <code>&#124;</code> `}` `~`, and characters in the ranges `0-9`, `A-Z` and `a-z`. Any other character, including the space character, aren't allowed. May not begin with `.`. |
### [appRoleAssignment ](https://docs.microsoft.com/graph/api/resources/approleassignment?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| appRoleId | Guid | The identifier (**id**) for the app role that's assigned to the principal. This app role must be exposed in the **appRoles** property on the resource application's service principal (**resourceId**). If the resource application hasn't declared any app roles, a default app role ID of `00000000-0000-0000-0000-000000000000` can be specified to signal that the principal is assigned to the resource app without any specific app roles. Required on create.  |
| createdDateTime | DateTimeOffset | The time when the app role assignment was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.  |
| deletedDateTime | DateTimeOffset | The date and time when the app role assignment was deleted. Always `null` for an appRoleAssignment object that hasn't been deleted. Inherited from directoryObject. |
| id | String | A unique identifier for the **appRoleAssignment** key. Not nullable. Read-only. |
| principalDisplayName | String |The display name of the user, group, or service principal that was granted the app role assignment. Read-only. Supports `$filter` (`eq` and `startswith`). |
| principalId | Guid | The unique identifier (**id**) for the user, security group, or service principal being granted the app role. Security groups with dynamic memberships are supported. Required on create.  |
| principalType | String | The type of the assigned principal. This can either be `User`, `Group`, or `ServicePrincipal`. Read-only.  |
| resourceDisplayName | String | The display name of the resource app's service principal to which the assignment is made.  |
| resourceId | Guid |The unique identifier (**i
### [assignedLabel ](https://docs.microsoft.com/graph/api/resources/assignedlabel?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                               |
| :---------- | :----- | :---------------------------------------- |
| displayName | String | The display name of the label. Read-only. |
| labelId     | String | The unique identifier of the label.       |
### [assignedLicense ](https://docs.microsoft.com/graph/api/resources/assignedlicense?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|disabledPlans|Guid collection|A collection of the unique identifiers for plans that have been disabled. IDs are available in **servicePlans** > **servicePlanId** in the tenant's subscribedSkus or **serviceStatus** > **servicePlanId** in the tenant's companySubscription. |
|skuId|Guid|The unique identifier for the SKU. Corresponds to the **s
### [channel ](https://docs.microsoft.com/graph/api/resources/channel?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|createdDateTime|dateTimeOffset|Read only. Timestamp at which the channel was created.|
|description|String|Optional textual description for the channel.|
|displayName|String|Channel name as it will appear to the user in Microsoft Teams. The maximum length is 50 characters.|
|email|String| The email address for sending messages to the channel. Read-only.|
|id|String|The channel's unique identifier. Read-only.|
|isArchived| Boolean | Indicates whether the channel is archived. Read-only. |
|isFavoriteByDefault|Boolean|Indicates whether the channel should be marked as recommended for all members of the team to show in their channel list. **Note:** All recommended channels automatically show in the channels list for education and frontline worker users. The property can only be set programmatically via the Create team method. The default value is `false`.|
|membershipType|channelMembershipType|The type of the channel. Can be set during creation and can't be changed. The possible values are: `standard`, `private`, `unknownFutureValue`, `shared`. The default value is `standard`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `shared`.|
|tenantId |string | The ID of the Microsoft Entra tenant. |
|webUrl|String|A hyperlink that will go to the channel in Microsoft Teams. This is the URL that you get when you right-click a channel in Microsoft Teams and select Get link to channel. This URL should be treated as an opaque blob, and not parsed. Read-only.|
|summary|channelSummary|Contains summary information about the channel, including number of owners, members, guests, and an indicator for members from other tenants. The **s
### [channelModerationSettings ](https://docs.microsoft.com/graph/api/resources/channelmoderationsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowNewMessageFromBots|Boolean|Indicates whether bots are allowed to post messages.|
|allowNewMessageFromConnectors|Boolean|Indicates whether connectors are allowed to post messages.|
|replyRestriction|replyRestriction|Indicates who is allowed to reply to the teams channel. Possible values are: `everyone`, `authorAndModerators`, `unknownFutureValue`.|
|userNewMessageRestriction|userNewMessageRestriction|Indicates who is allowed to post messages to teams channel. Possible values are: `everyone`, `everyoneExceptGuests`, `moderators`, `unknownFutureValue`.|
### [clonableteamparts](https://docs.microsoft.com/graph/api/resources/clonableteamparts?view=graph-rest-1.0&tabs=http)

### [connector ](https://docs.microsoft.com/graph/api/resources/connector?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|externalIp|String| The external IP address as detected by the connector server. Read-only. |
|id|String| The unique identifier of the connector. Read-only. |
|machineName|String| The name of the computer on which the connector is installed and runs on. |
|status|connectorStatus| Indicates the status of the connector. The possible values are: `active`, `inactive`. Read-only. |
|version|String|The version of the connector.|
### [connectorGroup ](https://docs.microsoft.com/graph/api/resources/connectorgroup?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|connectorGroupType|connectorGroupType| Indicates the type of hybrid agent. This pre-set by the system. Possible values are: `applicationProxy`, `syncFabric`. Read-only. |
|id|string| Unique identifier for this connectorGroup. Read-only. |
|isDefault|Boolean| Indicates if the connectorGroup is the default connectorGroup. Only a single connector group can be the default connectorGroup and this is pre-set by the system. Read-only. |
|name|string| The name associated with the connectorGroup. |
|region|connectorGroupRegion| The region the connectorGroup is assigned to and will optimize traffic for. This region can only be set if **n
### [Contract ](https://docs.microsoft.com/graph/api/resources/contract?view=graph-rest-1.0&tabs=http)
| Property   | Type | Description |
|:---------------|:--------|:----------|
|contractType|String|Type of contract. Possible values are:  `SyndicationPartner`, `BreadthPartner`, `ResellerPartner`. See more in the table below.|
|customerId|Guid|The unique identifier for the customer tenant referenced by this partnership. Corresponds to the id property of the customer tenant's organization resource. |
|defaultDomainName|String|A copy of the customer tenant's default domain name. The copy is made when the partnership with the customer is established. It isn't automatically updated if the customer tenant's default domain name changes.|
|displayName|String|A copy of the customer tenant's display name. The copy is made when the partnership with the customer is established. It is not automatically updated if the customer tenant's display name changes.|
|id|String| The unique identifier for the partnership. Key, read-only |
### [conversationMember ](https://docs.microsoft.com/graph/api/resources/conversationmember?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|displayName| string | The display name of the user. |
|id|String| Read-only. Unique ID of the user.|
|roles| string collection | The roles for that user. This property contains additional qualifiers only when relevant - for example, if the member has `owner` privileges, the **roles** property contains `owner` as one of the values. Similarly, if the member is an in-tenant guest, the **roles** property contains `guest` as one of the values. A basic member should not have any values specified in the **roles** property. An Out-of-tenant external member is assigned the `owner` role.|
|visibleHistoryStartDateTime| DateTimeOffset | The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat. |
### [credential ](https://docs.microsoft.com/graph/api/resources/credential?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|fieldId|String|The name of the field for this credential. e.g, username or password or phoneNumber. This is defined by the application. Must match what is in the html field on singleSignOnSettings/password object.|
|type|String|The type for this credential. Valid values: username, password, or other.|
|value|String|The value for this credential. e.g, mysuperhiddenpassword. Note the value for passwords is write-only, the value can never be read back.|
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
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [directoryRole ](https://docs.microsoft.com/graph/api/resources/directoryrole?view=graph-rest-1.0&tabs=http)
| Property   | Type | Description |
|:---------------|:--------|:----------|
|description|String|The description for the directory role. Read-only. Supports `$filter` (`eq`), `$search`, `$select`. |
|displayName|String|The display name for the directory role. Read-only. Supports `$filter` (`eq`), `$search`, `$select`. |
|id|String|The unique identifier for the directory role. Inherited from directoryObject. Key, Not nullable, Read-only. Supports `$filter` (`eq`), `$select`.|
|roleTemplateId|String| The **i
### [directoryRoleTemplate ](https://docs.microsoft.com/graph/api/resources/directoryroletemplate?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|description|String|The description to set for the directory role. Read-only.|
|displayName|String|The display name to set for the directory role. Read-only. |
|id|String|The unique identifier for the template. Inherited from directoryObject. You specify the **i
### [directorySetting ](https://docs.microsoft.com/graph/api/resources/directorysetting?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|displayName|string|Display name of this group of settings, which comes from the associated template. Read-only.|
|id|string| Unique identifier for these settings. Read-only.|
|templateId|string| Unique identifier for the template used to create this group of settings. Read-only.|
|values|settingValue collection| Collection of name-value pairs corresponding to the name and defaultValue properties in the referenced directorySettingTemplates object.|
### [directorySettingTemplate ](https://docs.microsoft.com/graph/api/resources/directorysettingtemplate?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|description|string|Description of the template. Read-only.|
|displayName|string|Display name of the template. Read-only. |
|id|string| Unique identifier for the template. Read-only.|
|values|settingTemplateValue collection| Collection of settingTemplateValues that list the set of available settings, defaults, and types that make up this template. Read-only. |
### [employeeOrgData ](https://docs.microsoft.com/graph/api/resources/employeeorgdata?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
| division | String | The name of the division in which the user works. <br><br>Returned only on `$select`. Supports `$filter`. |
| costCenter | String | The cost center associated with the user. <br><br>Returned only on `$select`. Supports `$filter`. |
### [extensionproperty](https://docs.microsoft.com/graph/api/resources/extensionproperty?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appDisplayName|String| Display name of the application object on which this extension property is defined. Read-only. |
|dataType|String| Specifies the data type of the value the extension property can hold. Following values are supported. <ul><li>`Binary` - 256 bytes maximum</li><li>`Boolean`</li><li>`DateTime` - Must be specified in ISO 8601 format. Will be stored in UTC.</li><li>`Integer` - 32-bit value.</li><li>`LargeInteger` - 64-bit value.</li><li>`String` - 256 characters maximum</li></ul>Not nullable. For multivalued directory extensions, these limits apply per value in the collection. |
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. Inherited from directoryObject.|
|isSyncedFromOnPremises|Boolean| Indicates if this extension property was synced from on-premises active directory using Microsoft Entra Connect. Read-only. |
|name|String| Name of the extension property. Not nullable. Supports `$filter` (`eq`).|
|isMultiValued|Boolean| Defines the directory extension as a multi-valued property. When `true`, the directory extension property can store a collection of objects of the **dataType**; for example, a collection of string types such as `"extension_b7b1c57b532f40b8b5ed4b7a7ba67401_jobGroupTracker": ["String 1", "String 2"]`. The default value is `false`. Supports `$filter` (`eq`).|
|targetObjects|String collection| Following values are supported. Not nullable. <ul><li>`User`</li><li>`Group`</li><li>`AdministrativeUnit`</li><li>`Application`</li><li>`Device`</li><li>`Organization`</li></ul>|
### [extensionSchemaProperty ](https://docs.microsoft.com/graph/api/resources/extensionschemaproperty?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|name|String| The name of the strongly typed property defined as part of a schema extension.|
|type|String| The type of the property that is defined as part of a schema extension.  Allowed values are `Binary`, `Boolean`, `DateTime`, `Integer`, or `String`. For more information, see Supported property data types.|
### [featureRolloutPolicy ](https://docs.microsoft.com/graph/api/resources/featurerolloutpolicy?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String|A description for this feature rollout policy.|
|displayName|String|The display name for this  feature rollout policy.|
|feature|stagedFeatureName| Possible values are: `passthroughAuthentication`, `seamlessSso`, `passwordHashSync`, `emailAsAlternateId`, `unknownFutureValue`, `certificateBasedAuthentication`, `multiFactorAuthentication`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value or values in this evolvable enum: `certificateBasedAuthentication`, `multiFactorAuthentication`. For more information about the prerequisites for the enabled features, see Prerequisites for enabled features.|
|id|String| Read-only.|
|isAppliedToOrganization|Boolean|Indicates whether this feature rollout policy should be applied to the entire organization.|
|isEnabled|Boolean|Indicates whether the feature rollout is enabled.|
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
### [groupLifecyclePolicy ](https://docs.microsoft.com/graph/api/resources/grouplifecyclepolicy?view=graph-rest-1.0&tabs=http)
| Property                    | Type   | Description                                                                                                                                                |
| :-------------------------- | :----- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| alternateNotificationEmails | String | List of email address to send notifications for groups without owners. Multiple email address can be defined by separating email address with a semicolon. |
| groupLifetimeInDays         | Int32  | Number of days before a group expires and needs to be renewed. Once renewed, the group expiration is extended by the number of days defined.               |
| id                          | String | A unique identifier for a policy. Read-only.                                                                                                               |
| managedGroupTypes           | String | The group type for which the expiration policy applies. Possible values are **A
### [groupSetting ](https://docs.microsoft.com/graph/api/resources/groupsetting?view=graph-rest-1.0&tabs=http)
| Property    | Type                                       | Description                                                                                                                                                             |
| :---------- | :----------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| displayName | String                                     | Display name of this group of settings, which comes from the associated template.                                                                                       |
| id          | String                                     | Unique identifier for these settings. Read-only.                                                                                                                        |
| templateId  | String                                     | Unique identifier for the tenant-level groupSettingTemplates object that's been customized for this group-level settings object. Read-only.  |
| values      | settingValue collection | Collection of name-value pairs corresponding to the **n
### [groupSettingTemplate ](https://docs.microsoft.com/graph/api/resources/groupsettingtemplate?view=graph-rest-1.0&tabs=http)
| Property    | Type                                                       | Description                                                                                                                                                                                                                          |
| :---------- | :--------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| description | String                                                     | Description of the template.                                                                                                                                                                                                         |
| displayName | String                                                     | Display name of the template. The template named `Group.Unified` can be used to configure tenant-wide Microsoft 365 group settings, while the template named `Group.Unified.Guest` can be used to configure group-specific settings. |
| id          | String                                                     | Unique identifier for the template. Read-only.                                                                                                                                                                                       |
| values      | settingTemplateValue collection | Collection of settingTemplateValues that list the set of available settings, defaults and types that make up this template.                                                                                                          |
### [groupWritebackConfiguration ](https://docs.microsoft.com/graph/api/resources/groupwritebackconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabled|Boolean|Indicates whether writeback of cloud groups to on-premises Active Directory is enabled. Nullable. Default value is `true` for Microsoft 365 groups and `false` for security groups. Inherited from writebackConfiguration.|
|onPremisesGroupType|String|Indicates the target on-premises group type the cloud object is written back as. Nullable. The possible values are: `universalDistributionGroup`, `universalSecurityGroup`, `universalMailEnabledSecurityGroup`.<ol><li>If the cloud group is a unified (Microsoft 365) group, this property can be one of the following: `universalDistributionGroup`, `universalSecurityGroup`, `universalMailEnabledSecurityGroup`. </li><li>Microsoft Entra security groups can be written back as `universalSecurityGroup`. </li><li>If **i
### [hybridAgentUpdaterConfiguration ](https://docs.microsoft.com/graph/api/resources/hybridagentupdaterconfiguration?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|allowUpdateConfigurationOverride|Boolean|Indicates if updater configuration will be skipped and the agent will receive an update when the next version of the agent is available.|
|deferUpdateDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|updateWindow|updateWindow|The time window during which the agent can receive updates.|
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
### [keyCredential ](https://docs.microsoft.com/graph/api/resources/keycredential?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|customKeyIdentifier|Binary| A 40-character binary type that can be used to identify the credential. Optional. When not provided in the payload, defaults to the thumbprint of the certificate. |
| displayName | String | Friendly name for the key. Optional. |
|endDateTime|DateTimeOffset|The date and time at which the credential expires. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|key|Binary| The certificate's raw data in byte array converted to Base64 string. Returned only on `$select` for a single object, that is, `GET applications/{applicationId}?$select=keyCredentials` or `GET servicePrincipals/{servicePrincipalId}?$select=keyCredentials`; otherwise, it is always `null`. <br/><br> From a *.cer* certificate, you can read the key using the **Convert.ToBase64String()** method. For more information, see Get the certificate key.|
|keyId|Guid|The unique identifier (GUID) for the key.|
|startDateTime|DateTimeOffset|The date and time at which the credential becomes valid.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|type|String|The type of key credential; for example, `Symmetric`, `AsymmetricX509Cert`.|
|usage|String|A string that describes the purpose for which the key can be used; for example, `Verify`.|
### [licenseDetails ](https://docs.microsoft.com/graph/api/resources/licensedetails?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| The unique identifier for the license detail object. Read-only. Key. Not nullable. |
|servicePlans|servicePlanInfo collection| Information about the service plans assigned with the license. Read-only. Not nullable. |
|skuId|Guid| Unique identifier (GUID) for the service SKU. Equal to the **skuId** property on the related subscribedSku object. Read-only. |
|skuPartNumber|String| Unique SKU display name. Equal to the **s
### [oAuth2PermissionGrant ](https://docs.microsoft.com/graph/api/resources/oauth2permissiongrant?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| clientId | String | The object **id** (*not* **appId**) of the client service principal for the application that's authorized to act on behalf of a signed-in user when accessing an API. Required. Supports `$filter` (`eq` only). |
| consentType | String | Indicates if authorization is granted for the client application to impersonate all users or only a specific user. *AllPrincipals* indicates authorization to impersonate all users. *Principal* indicates authorization to impersonate a specific user. Consent on behalf of all users can be granted by an administrator. Nonadmin users might be authorized to consent on behalf of themselves in some cases, for some delegated permissions. Required. Supports `$filter` (`eq` only). |
| id | String | Unique identifier for the **oAuth2PermissionGrant**. Read-only.|
| principalId | String | The **id** of the user on behalf of whom the client is authorized to access the resource, when **consentType** is *Principal*. If **consentType** is *AllPrincipals* this value is null. Required when **consentType** is *Principal*. Supports `$filter` (`eq` only).|
| resourceId | String | The **id** of the resource service principal to which access is authorized. This identifies the API that the client is authorized to attempt to call on behalf of a signed-in user. Supports `$filter` (`eq` only). |
| scope | String | A space-separated list of the claim values for delegated permissions that should be included in access tokens for the resource application (the API). For example, `openid User.Read GroupMember.Read.All`. Each claim value should match the **v
### [objectIdentity ](https://docs.microsoft.com/graph/api/resources/objectidentity?view=graph-rest-1.0&tabs=http)
| Property       | Type    | Description |
|:---------------|:--------|:------------|
|signInType|String|Specifies the user sign-in types in your directory, such as `emailAddress`, `userName`, `federated`, or `userPrincipalName`. `federated` represents a unique identifier for a user from an issuer that can be in any format chosen by the issuer. Setting or updating a `userPrincipalName` identity updates the value of the **userPrincipalName** property on the user object. The validations performed on the `userPrincipalName` property on the user object, for example, verified domains and acceptable characters, are performed when setting or updating a `userPrincipalName` identity. Extra validation is enforced on **issuerAssignedId** when the sign-in type is set to `emailAddress` or `userName`. This property can also be set to any custom string. <br> For more information about filtering behavior for this property, see Filtering on the identities property of a user.|
|issuer|String|Specifies the issuer of the identity, for example `facebook.com`. 512 character limit. <br><br>For local accounts (where **signInType** isn't `federated`), this property is the local default domain name for the tenant, for example `contoso.com`. <br> For guests from other Microsoft Entra organizations, this is the domain of the federated organization, for example `contoso.com`. For more information about filtering behavior for this property, see Filtering on the identities property of a user.|
|issuerAssignedId|String|Specifies the unique identifier assigned to the user by the issuer. 64 character limit. The combination of **i
### [onPremisesAgent ](https://docs.microsoft.com/graph/api/resources/onpremisesagent?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|externalIp|String|The external IP address as detected by the service for the agent machine. Read-only|
|id|String| The object id of the onPremisesAgent. Read-only.|
|machineName|String|The name of the machine that the agent is running on. Read-only|
|status|agentStatus| Possible values are: `active`, `inactive`.|
|supportedPublishingTypes|String collection| Possible values are: `applicationProxy`, `exchangeOnline`, `authentication`, `provisioning`, `adAdministration`.|
### [onPremisesAgentGroup ](https://docs.microsoft.com/graph/api/resources/onpremisesagentgroup?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|displayName|String|Display name of the **onPremisesAgentGroup**.|
|id|String| The object ID of the **onPremisesAgentGroup**. Read-only.|
|isDefault|Boolean|Indicates if the **onPremisesAgentGroup** is the default agent group. Only a single agent group can be the default **onPremisesAgentGroup** and is set by the system.|
|publishingType|String| Possible values are: `applicationProxy`, `exchangeOnline`, `authentication`, `provisioning`, `adAdministration`.|
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
### [onPremisesPublishingProfile ](https://docs.microsoft.com/graph/api/resources/onpremisespublishingprofile?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|hybridAgentUpdaterConfiguration|hybridAgentUpdaterConfiguration| Represents a **hybridAgentUpdaterConfiguration** object.|
|id|String| Represents a publishing type. Possible values are: `applicationProxy`, `exchangeOnline`, `authentication`, `provisioning`, `adAdministration`. Read-only.|
|isEnabled|Boolean| Represents if Microsoft Entra application proxy is enabled for the tenant. |
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
### [passwordCredential ](https://docs.microsoft.com/graph/api/resources/passwordcredential?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| customKeyIdentifier | Binary | Do not use. |
| displayName | String | Friendly name for the password. Optional. |
| endDateTime | DateTimeOffset | The date and time at which the password expires represented using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Optional. |
| hint | String | Contains the first three characters of the password. Read-only. |
| keyId | Guid | The unique identifier for the password. |
| secretText | String | Read-only; Contains the strong passwords generated by Microsoft Entra ID that are 16-64 characters in length. The generated password value is only returned during the initial POST request to addPassword. There is no way to retrieve this password in the future. |
| startDateTime | DateTimeOffset | The date and time at which the password becomes valid. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Optional. |
### [passwordProfile ](https://docs.microsoft.com/graph/api/resources/passwordprofile?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|forceChangePasswordNextSignIn|Boolean| `true` if the user must change their password on the next sign-in; otherwise `false`.|
|forceChangePasswordNextSignInWithMfa|Boolean| If `true`, at next sign-in, the user must perform a multifactor authentication (MFA) before being forced to change their password. The behavior is identical to **forceChangePasswordNextSignIn** except that the user is required to first perform a multifactor authentication before password change. After a password change, this property will be automatically reset to `false`. If not set, default is `false`. |
|password|String|The password for the user. This property is required when a user is created. It can be updated, but the user will be required to change the password on the next sign-in. The password must satisfy minimum requirements as specified by the user's **p
### [passwordSingleSignOnCredentialSet ](https://docs.microsoft.com/graph/api/resources/passwordsinglesignoncredentialset?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|credentials|credential collection| A list of credential objects that define the complete sign in flow.|
|id|String|The ID of the user or group this credential set belongs to.|
### [remoteDesktopSecurityConfiguration ](https://docs.microsoft.com/graph/api/resources/remotedesktopsecurityconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the RDS security configuration. Inherited from entity.|
|isRemoteDesktopProtocolEnabled|Boolean|Determines if Microsoft Entra ID RDS authentication protocol for RDP is enabled.|
### [samlSingleSignOnSettings ](https://docs.microsoft.com/graph/api/resources/samlsinglesignonsettings?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
|relayState|String| The relative URI the service provider would redirect to after completion of the single sign-on flow. |
### [schemaextension](https://docs.microsoft.com/graph/api/resources/schemaextension?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|description|String|Description for the schema extension. Supports `$filter` (`eq`).|
|id|String|The unique identifier for the schema extension definition. <br>You can assign a value in one of two ways: <ul><li>Concatenate the name of one of your verified domains with a name for the schema extension to form a unique string in this format, \{_&#65279;domainName_\}\_\{_&#65279;schemaName_\}. As an example, `contoso_mySchema`. </li><li>Provide a schema name, and let Microsoft Graph use that schema name to complete the **id** assignment in this format: ext\{_&#65279;8-random-alphanumeric-chars_\}\_\{_&#65279;schema-name_\}. An example would be `extkvbmkofy_mySchema`.</li></ul>This property cannot be changed after creation. Supports `$filter` (`eq`). **Note:** We recommend that your **id** starts with an alphabetic letter between A-Z because query capabilities might be limited for IDs that begin with integers. <br/><br/> Supports `$filter` (`eq`). |
|owner|String| The `appId` of the application that is the owner of the schema extension. The owner of the schema definition must be explicitly specified during the Create and Update operations, or it will be implied and auto-assigned by Microsoft Entra ID as follows: <br/><ul><li>In delegated access: <ul><li>The signed-in user must be the owner of the app that calls Microsoft Graph to create the schema extension definition. </li></ul> <ul><li>If the signed-in user isn't the owner of the calling app, they must explicitly specify the **owner** property, and assign it the **appId** of an app that they own.</li></ul></li></ul> <ul><li>In app-only access: <ul><li> The **owner** property isn't required in the request body. Instead, the calling app is assigned ownership of the schema extension.</li></ul></li></ul> </br>So, for example, if creating a new schema extension definition using Graph Explorer, you **must** supply the owner property. Once set, this property is read-only and cannot be changed. Supports `$filter` (`eq`).|
|properties|extensionSchemaProperty collection|The collection of property names and types that make up the schema extension definition.|
|status|String|The lifecycle state of the schema extension. Possible states are `InDevelopment`, `Available`, and `Deprecated`. Automatically set to `InDevelopment` on creation. For more information about the possible state transitions and behaviors, see Schema extensions lifecycle. Supports `$filter` (`eq`).|
|targetTypes|String collection|Set of Microsoft Graph types (that can support extensions) that the schema extension can be applied to. Select from **a
### [scopedRoleMembership ](https://docs.microsoft.com/graph/api/resources/scopedrolemembership?view=graph-rest-1.0&tabs=http)
| Property   | Type | Description |
|:---------------|:--------|:----------|
|administrativeUnitId|string|Unique identifier for the administrative unit that the directory role is scoped to|
|ID|string| Unique identifier for the scoped-role membership. Read-only.|
|roleId|string| Unique identifier for the directory role that the member is in.|
|roleMemberInfo|identity| Role member identity information. Represents the user that is a member of this scoped-role.|
### [selfSignedCertificate ](https://docs.microsoft.com/graph/api/resources/selfsignedcertificate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description
|:---|:---|:---|
|customKeyIdentifier|Binary| Custom key identifier. |
|displayName | String | The friendly name for the key. |
|endDateTime|DateTimeOffset|The date and time at which the credential expires. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`.|
|key|Binary| The value for the key credential. Should be a Base-64 encoded value. |
|keyId|Guid|The unique identifier (GUID) for the key.|
|startDateTime|DateTimeOffset|The date and time at which the credential becomes valid. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on January 1, 2014 is `2014-01-01T00:00:00Z`. |
|type|String|The type of key credential. `AsymmetricX509Cert`.|
|usage|String|A string that describes the purpose for which the key can be used. The possible value is `Verify`.|
|thumbprint| String | The thumbprint value for the key.|
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

### [settingValue ](https://docs.microsoft.com/graph/api/resources/settingvalue?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
|name|String| Name of the setting (as defined by the groupSettingTemplate). |
|value|String| Value of the setting. |
### [subscribedSku ](https://docs.microsoft.com/graph/api/resources/subscribedsku?view=graph-rest-1.0&tabs=http)
| Property         | Type                                             | Description                                                                                                                                                                                                                                               |
| :--------------- | :----------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| accountId        | String                                           | The unique ID of the account this SKU belongs to.                                                                                                                                                                                                         |
| accountName      | String                                           | The name of the account this SKU belongs to.                                                                                                                                                                                                              |
| appliesTo        | String                                           | The target class for this SKU. Only SKUs with target class `User` are assignable. Possible values are: `User`, `Company`.                                                                                                                                          |
| capabilityStatus | String                                           | `Enabled` indicates that the **prepaidUnits** property has at least one unit that is enabled. `LockedOut` indicates that the customer canceled their subscription. Possible values are: `Enabled`, `Warning`, `Suspended`, `Deleted`, `LockedOut`. |
| consumedUnits    | Int32                                            | The number of licenses that have been assigned.                                                                                                                                                                                                           |
| id               | String                                           | The unique identifier for the subscribed sku object. Key, not nullable.                                                                                                                                                                                   |
| prepaidUnits     | licenseUnitsDetail      | Information about the number and status of prepaid licenses.                                                                                                                                                                                              |
| servicePlans     | servicePlanInfo collection | Information about the service plans that are available with the SKU. Not nullable.                                                                                                                                                                         |
| skuId            | Guid                                             | The unique identifier (GUID) for the service SKU.                                                                                                                                                                                                         |
| skuPartNumber    | String                                           | The SKU part number; for example: `AAD_PREMIUM` or `RMSBASIC`. To get a list of commercial subscriptions that an organization has acquired, see List subscribedSkus.                                                      |
| subscriptionIds | String collection                                    | A list of all subscription IDs associated with this SKU.                                                                                                                                                                                                  |
### [directoryDefinition ](https://docs.microsoft.com/graph/api/resources/synchronization-directorydefinition?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|id           |String     |Directory identifier. Not nullable. Inherited from entity.|
|name           |String     |Name of the directory. Must be unique within the synchronization schema. Not nullable.|
|objects        |objectDefinition collection    |Collection of objects supported by the directory.|
|readOnly|Boolean| Whether this object is read-only.|
|version|String|Read only value that indicates version discovered. `null` if discovery hasn't yet occurred.|
|discoveryDateTime|DateTimeOffset| Represents the discovery date and time using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|discoverabilities|directoryDefinitionDiscoverabilities| Read-only value indicating what type of discovery the app supports. The possible values are: `None`, `AttributeNames`, `AttributeDataTypes`, `AttributeReadOnly`, `ReferenceAttributes`, `UnknownFutureValue`. This is a multi-valued object.|
### [targetDeviceGroup ](https://docs.microsoft.com/graph/api/resources/targetdevicegroup?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name for the target device group.|
|id|String|Object identifier of the group. Inherited from entity.|
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
### [teamsApp ](https://docs.microsoft.com/graph/api/resources/teamsapp?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| displayName                | string   | The name of the catalog app provided by the app developer in the Microsoft Teams zip app package. |
| distributionMethod  | teamsAppDistributionMethod     | The method of distribution for the app. Read-only.|
| externalId          | string   | The ID of the catalog provided by the app developer in the Microsoft Teams zip app package. |
| id                  | string   | The app ID generated for the catalog is different from the developer-provided ID found within the Microsoft Teams zip app package. The **e
### [teamsAppDefinition ](https://docs.microsoft.com/graph/api/resources/teamsappdefinition?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| description         | string   | Verbose description of the application. |
| displayName         | string   | The name of the app provided by the app developer. |
| id                  | string   | A unique ID (not the Teams app ID). |
| publishingState| string|The published status of a specific version of a Teams app. Possible values are:</br>`submitted`—The specific version of the Teams app has been submitted and is under review. </br>`published`—The request to publish the specific version of the Teams app has been approved by the admin and the app is published. </br> `rejected`—The admin rejected the request to publish the specific version of the Teams app. |
| shortDescription    | string   | Short description of the application. |
| teamsAppId          | string   | The ID from the Teams app manifest. |
| version             | string   | The version number of the application. |
|authorization|teamsAppAuthorization|Authorization requirements specified in the Teams app manifest.|
### [teamsAppInstallation ](https://docs.microsoft.com/graph/api/resources/teamsappinstallation?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
|consentedPermissionSet|teamsAppPermissionSet|The set of resource-specific permissions consented to while installing or upgrading the teamsApp.|
| id                  | string   | A unique ID (not the Teams app ID). |
### [teamsAppPermissionSet ](https://docs.microsoft.com/graph/api/resources/teamsapppermissionset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|resourceSpecificPermissions|teamsAppResourceSpecificPermission collection|A collection of resource-specific permissions.|
### [teamsAsyncOperation ](https://docs.microsoft.com/graph/api/resources/teamsasyncoperation?view=graph-rest-1.0&tabs=http)
| Property | Type	| Description |
|:---------------|:--------|:----------|
|attemptsCount|Int32|Number of times the operation was attempted before being marked successful or failed.|
|createdDateTime|DateTimeOffset |Time when the operation was created.|
|error|operationError|Any error that causes the async operation to fail.|
|id|string |Unique operation ID.|
|lastActionDateTime|DateTimeOffset |Time when the async operation was last updated.|
|operationType|teamsAsyncOperationType |Denotes the type of operation described. Possible values are: `invalid`, `cloneTeam`, `archiveTeam`, `unarchiveTeam`, `createTeam`, `unknownFutureValue`, `teamifyGroup`, `createChannel`, `archiveChannel`, `unarchiveChannel`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values in this evolvable enum: `teamifyGroup`, `createChannel`, `archiveChannel`, `unarchiveChannel`. |
|status|teamsAsyncOperationStatus| Operation status.|
|targetResourceId|String |The ID of the object that's created or modified as result of this async operation, typically a team.|
|targetResourceLocation|string|The location of the object that's created or modified as result of this async operation. This URL should be treated as an opaque value and not parsed into its component paths.|
### [teamsLicensingDetails ](https://docs.microsoft.com/graph/api/resources/teamslicensingdetails?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
|hasTeamsLicense|Boolean|Indicates whether the user has a valid license to use Microsoft Teams.|
### [teamsTab ](https://docs.microsoft.com/graph/api/resources/teamstab?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---------------|:--------|:----------|
|  configuration        |   teamsTabConfiguration |  Container for custom settings applied to a tab. The tab is considered configured only once this property is set.     |
|  displayName            |   string                  |  Name of the tab.     |
|  id              |   string                  |  Identifier that uniquely identifies a specific instance of a channel tab. Read only.     |
|  webUrl          |   string                  |  Deep link URL of the tab instance. Read only.     |
### [teamvisibilitytype](https://docs.microsoft.com/graph/api/resources/teamvisibilitytype?view=graph-rest-1.0&tabs=http)

### [teamworkBot ](https://docs.microsoft.com/graph/api/resources/teamworkbot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The ID of the bot associated with the specific teamsAppDefinition. This value is usually a GUID.|
### [unifiedRoleAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appScopeId|String|Identifier of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by a resource application only. For the entitlement management provider, use this property to specify a catalog. For example, `/AccessPackageCatalog/beedadfe-01d5-4025-910b-84abb9369997`. Supports `$filter` (`eq`, `in`). For example, `/roleManagement/entitlementManagement/roleAssignments?$filter=appScopeId eq '/AccessPackageCatalog/{catalog id}'`.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications, unlike app scopes that are defined and understood by a resource application only. Supports `$filter` (`eq`, `in`).|
|id|String| The unique identifier for the unifiedRoleAssignment. Key, not nullable, Read-only. |
|principalId|String| Identifier of the principal to which the assignment is granted. Supported principals are users, role-assignable groups, and service principals. Supports `$filter` (`eq`, `in`). |
|roleDefinitionId|String| Identifier of the unifiedRoleDefinition the assignment is for. Read-only. Supports `$filter` (`eq`, `in`). |
### [unifiedRoleDefinition ](https://docs.microsoft.com/graph/api/resources/unifiedroledefinition?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|description|String| The description for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. |
|displayName|String| The display name for the unifiedRoleDefinition. Read-only when **isBuiltIn** is `true`. Required.  Supports $filter (`eq`, `in`).|
|id|String| The unique identifier for the role definition. Key, not nullable, Read-only. Inherited from entity. Supports $filter (`eq`, `in`). |
|isBuiltIn|Boolean| Flag indicating whether the role definition is part of the default set included in Microsoft Entra or a custom definition. Read-only. Supports $filter (`eq`, `in`). |
|isEnabled|Boolean| Flag indicating whether the role is enabled for assignment. If `false` the role is not available for assignment. Read-only when **isBuiltIn** is true. |
|resourceScopes|String collection| List of the scopes or permissions the role definition applies to. Currently only `/` is supported. Read-only when **isBuiltIn** is true. **DO NOT USE. This will be deprecated soon. Attach scope to role assignment.** | 
|rolePermissions|unifiedRolePermission collection| List of permissions included in the role. Read-only when **isBuiltIn** is `true`. Required. |
|templateId|String| Custom template identifier that can be set when **isBuiltIn** is `false` but is read-only when **isBuiltIn** is `true`. This identifier is typically used if one needs an identifier to be the same across different directories. |
|version|String| Indicates version of the role definition. Read-only when **i
### [unifiedRolePermission ](https://docs.microsoft.com/graph/api/resources/unifiedrolepermission?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|allowedResourceActions|String collection| Set of tasks that can be performed on a resource. Required. |
|condition|String| Optional constraints that must be met for the permission to be effective. Not supported for custom roles.|
|excludedResourceActions|String collection| Set of tasks that may not be performed on a resource. Not yet supported. |
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
