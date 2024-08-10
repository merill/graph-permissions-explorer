# DeviceManagementApps.Read.All

> Allows the app to read the properties, group assignments and status of apps, app configurations and app protection policies managed by Microsoft Intune.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET ** Collection URI for microsoft.management.services.api.appVulnerabilityManagedDevice not found](https://docs.microsoft.com/graph/api/intune-partnerintegration-appvulnerabilitymanageddevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Collection URI for microsoft.management.services.api.appVulnerabilityMobileApp not found](https://docs.microsoft.com/graph/api/intune-partnerintegration-appvulnerabilitymobileapp-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Collection URI for microsoft.management.services.api.vulnerableManagedDevice not found](https://docs.microsoft.com/graph/api/intune-partnerintegration-vulnerablemanageddevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Entity URI for microsoft.management.services.api.appVulnerabilityManagedDevice not found](https://docs.microsoft.com/graph/api/intune-partnerintegration-appvulnerabilitymanageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Entity URI for microsoft.management.services.api.appVulnerabilityMobileApp not found](https://docs.microsoft.com/graph/api/intune-partnerintegration-appvulnerabilitymobileapp-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Entity URI for microsoft.management.services.api.vulnerableManagedDevice not found](https://docs.microsoft.com/graph/api/intune-partnerintegration-vulnerablemanageddevice-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement](https://docs.microsoft.com/graph/api/intune-unlock-deviceappmanagement-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections](https://docs.microsoft.com/graph/api/intune-mam-androidmanagedappprotection-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections/{androidManagedAppProtectionId}](https://docs.microsoft.com/graph/api/intune-mam-androidmanagedappprotection-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections/{androidManagedAppProtectionId}/apps](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections/{androidManagedAppProtectionId}/apps/{managedMobileAppId}](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections/{androidManagedAppProtectionId}/assignments](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections/{androidManagedAppProtectionId}/assignments/{targetedManagedAppPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/androidManagedAppProtections/{androidManagedAppProtectionId}/deploymentSummary](https://docs.microsoft.com/graph/api/intune-mam-managedapppolicydeploymentsummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/defaultManagedAppProtections](https://docs.microsoft.com/graph/api/intune-mam-defaultmanagedappprotection-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/defaultManagedAppProtections/{defaultManagedAppProtectionId}](https://docs.microsoft.com/graph/api/intune-mam-defaultmanagedappprotection-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/defaultManagedAppProtections/{defaultManagedAppProtectionId}/apps](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/defaultManagedAppProtections/{defaultManagedAppProtectionId}/apps/{managedMobileAppId}](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/defaultManagedAppProtections/{defaultManagedAppProtectionId}/deploymentSummary](https://docs.microsoft.com/graph/api/intune-mam-managedapppolicydeploymentsummary-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/deviceAppManagementTasks](https://docs.microsoft.com/graph/api/intune-partnerintegration-securityconfigurationtask-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/deviceAppManagementTasks/{deviceAppManagementTaskId}](https://docs.microsoft.com/graph/api/intune-partnerintegration-unmanageddevicediscoverytask-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/enterpriseCodeSigningCertificates](https://docs.microsoft.com/graph/api/intune-apps-enterprisecodesigningcertificate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/enterpriseCodeSigningCertificates/{enterpriseCodeSigningCertificateId}](https://docs.microsoft.com/graph/api/intune-apps-enterprisecodesigningcertificate-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations](https://docs.microsoft.com/graph/api/intune-shared-ioslobappprovisioningconfiguration-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}](https://docs.microsoft.com/graph/api/intune-shared-ioslobappprovisioningconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/assignments](https://docs.microsoft.com/graph/api/intune-apps-ioslobappprovisioningconfigurationassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/assignments/{iosLobAppProvisioningConfigurationAssignmentId}](https://docs.microsoft.com/graph/api/intune-apps-ioslobappprovisioningconfigurationassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/deviceStatuses](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationdevicestatus-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/deviceStatuses/{managedDeviceMobileAppConfigurationDeviceStatusId}](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationdevicestatus-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/groupAssignments](https://docs.microsoft.com/graph/api/intune-apps-mobileappprovisioningconfiggroupassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/groupAssignments/{mobileAppProvisioningConfigGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappprovisioningconfiggroupassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/userStatuses](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationuserstatus-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/iosLobAppProvisioningConfigurations/{iosLobAppProvisioningConfigurationId}/userStatuses/{managedDeviceMobileAppConfigurationUserStatusId}](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationuserstatus-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections](https://docs.microsoft.com/graph/api/intune-mam-iosmanagedappprotection-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections/{iosManagedAppProtectionId}](https://docs.microsoft.com/graph/api/intune-mam-iosmanagedappprotection-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections/{iosManagedAppProtectionId}/apps](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections/{iosManagedAppProtectionId}/apps/{managedMobileAppId}](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections/{iosManagedAppProtectionId}/assignments](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections/{iosManagedAppProtectionId}/assignments/{targetedManagedAppPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/iosManagedAppProtections/{iosManagedAppProtectionId}/deploymentSummary](https://docs.microsoft.com/graph/api/intune-mam-managedapppolicydeploymentsummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppPolicies](https://docs.microsoft.com/graph/api/intune-mam-managedappprotection-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppPolicies/{managedAppPolicyId}](https://docs.microsoft.com/graph/api/intune-mam-managedappconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations](https://docs.microsoft.com/graph/api/intune-mam-iosmanagedappregistration-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}](https://docs.microsoft.com/graph/api/intune-mam-androidmanagedappregistration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/appliedPolicies](https://docs.microsoft.com/graph/api/intune-mam-managedappprotection-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/appliedPolicies/{managedAppPolicyId}](https://docs.microsoft.com/graph/api/intune-mam-managedappconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/intendedPolicies](https://docs.microsoft.com/graph/api/intune-mam-managedappprotection-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/intendedPolicies/{managedAppPolicyId}](https://docs.microsoft.com/graph/api/intune-mam-managedappconfiguration-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/managedAppLogCollectionRequests](https://docs.microsoft.com/graph/api/intune-mam-managedapplogcollectionrequest-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/managedAppLogCollectionRequests/{managedAppLogCollectionRequestId}](https://docs.microsoft.com/graph/api/intune-mam-managedapplogcollectionrequest-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/operations](https://docs.microsoft.com/graph/api/intune-mam-managedappoperation-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/{managedAppRegistrationId}/operations/{managedAppOperationId}](https://docs.microsoft.com/graph/api/intune-mam-managedappoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppRegistrations/getUserIdsWithFlaggedAppRegistration](https://docs.microsoft.com/graph/api/intune-mam-managedappregistration-getuseridswithflaggedappregistration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppStatuses](https://docs.microsoft.com/graph/api/intune-mam-managedappstatusraw-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedAppStatuses/{managedAppStatusId}](https://docs.microsoft.com/graph/api/intune-mam-managedappstatusraw-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/managedEBookCategories](https://docs.microsoft.com/graph/api/intune-books-managedebookcategory-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/managedEBookCategories/{managedEBookCategoryId}](https://docs.microsoft.com/graph/api/intune-books-managedebookcategory-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks](https://docs.microsoft.com/graph/api/intune-books-iosvppebook-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}](https://docs.microsoft.com/graph/api/intune-books-iosvppebook-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/assignments](https://docs.microsoft.com/graph/api/intune-books-managedebookassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/assignments/{managedEBookAssignmentId}](https://docs.microsoft.com/graph/api/intune-books-iosvppebookassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/categories](https://docs.microsoft.com/graph/api/intune-books-managedebookcategory-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/categories/{managedEBookCategoryId}](https://docs.microsoft.com/graph/api/intune-books-managedebookcategory-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/deviceStates](https://docs.microsoft.com/graph/api/intune-books-deviceinstallstate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/deviceStates/{deviceInstallStateId}](https://docs.microsoft.com/graph/api/intune-books-deviceinstallstate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/installSummary](https://docs.microsoft.com/graph/api/intune-books-ebookinstallsummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/userStateSummary](https://docs.microsoft.com/graph/api/intune-books-userinstallstatesummary-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/userStateSummary/{userInstallStateSummaryId}](https://docs.microsoft.com/graph/api/intune-books-userinstallstatesummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/userStateSummary/{userInstallStateSummaryId}/deviceStates](https://docs.microsoft.com/graph/api/intune-books-deviceinstallstate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/managedEBooks/{managedEBookId}/userStateSummary/{userInstallStateSummaryId}/deviceStates/{deviceInstallStateId}](https://docs.microsoft.com/graph/api/intune-books-deviceinstallstate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies](https://docs.microsoft.com/graph/api/intune-mam-mdmwindowsinformationprotectionpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}](https://docs.microsoft.com/graph/api/intune-mam-mdmwindowsinformationprotectionpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}/assignments](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}/assignments/{targetedManagedAppPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}/exemptAppLockerFiles](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}/exemptAppLockerFiles/{windowsInformationProtectionAppLockerFileId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}/protectedAppLockerFiles](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mdmWindowsInformationProtectionPolicies/{mdmWindowsInformationProtectionPolicyId}/protectedAppLockerFiles/{windowsInformationProtectionAppLockerFileId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppCategories](https://docs.microsoft.com/graph/api/intune-apps-mobileappcategory-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppCategories/{mobileAppCategoryId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappcategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfiguration-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/assignments](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/assignments/{managedDeviceMobileAppConfigurationAssignmentId}](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/deviceStatuses](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationdevicestatus-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/deviceStatuses/{managedDeviceMobileAppConfigurationDeviceStatusId}](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationdevicestatus-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/deviceStatusSummary](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationdevicesummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/userStatuses](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationuserstatus-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/userStatuses/{managedDeviceMobileAppConfigurationUserStatusId}](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationuserstatus-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileAppConfigurations/{managedDeviceMobileAppConfigurationId}/userStatusSummary](https://docs.microsoft.com/graph/api/intune-apps-manageddevicemobileappconfigurationusersummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps](https://docs.microsoft.com/graph/api/intune-apps-macoslobapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}](https://docs.microsoft.com/graph/api/intune-apps-androidlobapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/assignments](https://docs.microsoft.com/graph/api/intune-apps-mobileappassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/assignments/{mobileAppAssignmentId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/categories](https://docs.microsoft.com/graph/api/intune-apps-mobileappcategory-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/categories/{mobileAppCategoryId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappcategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/contentVersions](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/contentVersions/{mobileAppContentId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontent-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/contentVersions/{mobileAppContentId}/containedApps](https://docs.microsoft.com/graph/api/intune-apps-windowsuniversalappxcontainedapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/contentVersions/{mobileAppContentId}/containedApps/{mobileContainedAppId}](https://docs.microsoft.com/graph/api/intune-apps-windowsuniversalappxcontainedapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/contentVersions/{mobileAppContentId}/files](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontentfile-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/contentVersions/{mobileAppContentId}/files/{mobileAppContentFileId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontentfile-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/deviceStatuses](https://docs.microsoft.com/graph/api/intune-apps-mobileappinstallstatus-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/deviceStatuses/{mobileAppInstallStatusId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappinstallstatus-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/{mobileAppId}/deviceStatuses/{mobileAppInstallStatusId}/app](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/{mobileAppId}/deviceStatuses/{mobileAppInstallStatusId}/app/getRelatedAppStates](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-getrelatedappstates?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/{mobileAppId}/getRelatedAppStates](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-getrelatedappstates?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/installSummary](https://docs.microsoft.com/graph/api/intune-apps-mobileappinstallsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.iosVppApp/assignedLicenses](https://docs.microsoft.com/graph/api/intune-apps-iosvppappassigneddevicelicense-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.iosVppApp/assignedLicenses/{iosVppAppAssignedLicenseId}](https://docs.microsoft.com/graph/api/intune-apps-iosvppappassigneduserlicense-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.macOsVppApp/assignedLicenses](https://docs.microsoft.com/graph/api/intune-apps-macosvppappassignedlicense-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.macOsVppApp/assignedLicenses/{macOsVppAppAssignedLicenseId}](https://docs.microsoft.com/graph/api/intune-apps-macosvppappassignedlicense-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.managedMobileLobApp/contentVersions](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.managedMobileLobApp/contentVersions/{mobileAppContentId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontent-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.microsoftStoreForBusinessApp/containedApps](https://docs.microsoft.com/graph/api/intune-apps-windowsuniversalappxcontainedapp-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.microsoftStoreForBusinessApp/containedApps/{mobileContainedAppId}](https://docs.microsoft.com/graph/api/intune-apps-windowsuniversalappxcontainedapp-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.mobileLobApp/contentVersions](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.mobileLobApp/contentVersions/{mobileAppContentId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappcontent-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.windowsUniversalAppX/committedContainedApps](https://docs.microsoft.com/graph/api/intune-apps-windowsuniversalappxcontainedapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/microsoft.graph.windowsUniversalAppX/committedContainedApps/{mobileContainedAppId}](https://docs.microsoft.com/graph/api/intune-apps-windowsuniversalappxcontainedapp-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/relationships](https://docs.microsoft.com/graph/api/intune-apps-mobileapprelationship-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/relationships/{mobileAppRelationshipId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappsupersedence-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/userStatuses](https://docs.microsoft.com/graph/api/intune-apps-userappinstallstatus-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/userStatuses/{userAppInstallStatusId}](https://docs.microsoft.com/graph/api/intune-apps-userappinstallstatus-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/{mobileAppId}/userStatuses/{userAppInstallStatusId}/app](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/{mobileAppId}/userStatuses/{userAppInstallStatusId}/app/getRelatedAppStates](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-getrelatedappstates?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/userStatuses/{userAppInstallStatusId}/deviceStatuses](https://docs.microsoft.com/graph/api/intune-apps-mobileappinstallstatus-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/{mobileAppId}/userStatuses/{userAppInstallStatusId}/deviceStatuses/{mobileAppInstallStatusId}](https://docs.microsoft.com/graph/api/intune-apps-mobileappinstallstatus-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/getMobileAppCount](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-getmobileappcount?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/mobileApps/getPublishingConstraints](https://docs.microsoft.com/graph/api/intune-apps-mobileapp-getpublishingconstraints?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceAppManagement/mobileApps/getTopMobileApps](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-gettopmobileapps?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/symantecCodeSigningCertificate](https://docs.microsoft.com/graph/api/intune-apps-symanteccodesigningcertificate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedappconfiguration-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedappconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/apps](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/apps/{managedMobileAppId}](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/assignments](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/assignments/{targetedManagedAppPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/deploymentSummary](https://docs.microsoft.com/graph/api/intune-mam-managedapppolicydeploymentsummary-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/settings](https://docs.microsoft.com/graph/api/intune-mam-devicemanagementconfigurationsetting-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/settings/{deviceManagementConfigurationSettingId}](https://docs.microsoft.com/graph/api/intune-mam-devicemanagementconfigurationsetting-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/settings/{deviceManagementConfigurationSettingId}/settingDefinitions](https://docs.microsoft.com/graph/api/intune-mam-devicemanagementconfigurationsimplesettingcollectiondefinition-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/settings/{deviceManagementConfigurationSettingId}/settingDefinitions/{deviceManagementConfigurationSettingDefinitionId}](https://docs.microsoft.com/graph/api/intune-mam-devicemanagementconfigurationredirectsettingdefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}/assignments](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicyassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}/assignments/{windowsDefenderApplicationControlSupplementalPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}/deploySummary](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicydeploymentsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}/deviceStatuses](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicydeploymentstatus-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}/deviceStatuses/{windowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId}](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicydeploymentstatus-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/wdacSupplementalPolicies/{windowsDefenderApplicationControlSupplementalPolicyId}/deviceStatuses/{windowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId}/policy](https://docs.microsoft.com/graph/api/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsInformationProtectionDeviceRegistrations](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectiondeviceregistration-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsInformationProtectionDeviceRegistrations/{windowsInformationProtectionDeviceRegistrationId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectiondeviceregistration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionpolicy-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionpolicy-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}/assignments](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}/assignments/{targetedManagedAppPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}/exemptAppLockerFiles](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}/exemptAppLockerFiles/{windowsInformationProtectionAppLockerFileId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}/protectedAppLockerFiles](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/windowsInformationProtectionPolicies/{windowsInformationProtectionPolicyId}/protectedAppLockerFiles/{windowsInformationProtectionAppLockerFileId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionapplockerfile-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsInformationProtectionWipeActions](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionwipeaction-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsInformationProtectionWipeActions/{windowsInformationProtectionWipeActionId}](https://docs.microsoft.com/graph/api/intune-mam-windowsinformationprotectionwipeaction-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections](https://docs.microsoft.com/graph/api/intune-mam-windowsmanagedappprotection-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections/{windowsManagedAppProtectionId}](https://docs.microsoft.com/graph/api/intune-mam-windowsmanagedappprotection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections/{windowsManagedAppProtectionId}/apps](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections/{windowsManagedAppProtectionId}/apps/{managedMobileAppId}](https://docs.microsoft.com/graph/api/intune-mam-managedmobileapp-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections/{windowsManagedAppProtectionId}/assignments](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections/{windowsManagedAppProtectionId}/assignments/{targetedManagedAppPolicyAssignmentId}](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedapppolicyassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagedAppProtections/{windowsManagedAppProtectionId}/deploymentSummary](https://docs.microsoft.com/graph/api/intune-mam-managedapppolicydeploymentsummary-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement](https://docs.microsoft.com/graph/api/intune-auditing-devicemanagement-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/auditEvents](https://docs.microsoft.com/graph/api/intune-auditing-auditevent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/auditEvents/{auditEventId}](https://docs.microsoft.com/graph/api/intune-auditing-auditevent-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/auditEvents/getAuditActivityTypes](https://docs.microsoft.com/graph/api/intune-auditing-auditevent-getauditactivitytypes?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/auditEvents/getAuditCategories](https://docs.microsoft.com/graph/api/intune-auditing-auditevent-getauditcategories?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/configManagerCollections](https://docs.microsoft.com/graph/api/intune-partnerintegration-configmanagercollection-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/configManagerCollections/{configManagerCollectionId}](https://docs.microsoft.com/graph/api/intune-partnerintegration-configmanagercollection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/configManagerCollections/getPolicySummary](https://docs.microsoft.com/graph/api/intune-partnerintegration-configmanagercollection-getpolicysummary?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/intuneBrandingProfiles](https://docs.microsoft.com/graph/api/intune-wip-intunebrandingprofile-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/intuneBrandingProfiles/{intuneBrandingProfileId}](https://docs.microsoft.com/graph/api/intune-wip-intunebrandingprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/intuneBrandingProfiles/{intuneBrandingProfileId}/assignments](https://docs.microsoft.com/graph/api/intune-wip-intunebrandingprofileassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/intuneBrandingProfiles/{intuneBrandingProfileId}/assignments/{intuneBrandingProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-wip-intunebrandingprofileassignment-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/reports](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/cachedReportConfigurations](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementcachedreportconfiguration-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/cachedReportConfigurations/{deviceManagementCachedReportConfigurationId}](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementcachedreportconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/reports/exportJobs](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementexportjob-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/reports/exportJobs/{deviceManagementExportJobId}](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementexportjob-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/reportSchedules](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreportschedule-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/reportSchedules/{deviceManagementReportScheduleId}](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreportschedule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsInformationProtectionAppLearningSummaries](https://docs.microsoft.com/graph/api/intune-wip-windowsinformationprotectionapplearningsummary-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsInformationProtectionAppLearningSummaries/{windowsInformationProtectionAppLearningSummaryId}](https://docs.microsoft.com/graph/api/intune-wip-windowsinformationprotectionapplearningsummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsInformationProtectionNetworkLearningSummaries](https://docs.microsoft.com/graph/api/intune-wip-windowsinformationprotectionnetworklearningsummary-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsInformationProtectionNetworkLearningSummaries/{windowsInformationProtectionNetworkLearningSummaryId}](https://docs.microsoft.com/graph/api/intune-wip-windowsinformationprotectionnetworklearningsummary-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users](https://docs.microsoft.com/graph/api/intune-mam-user-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{usersId}](https://docs.microsoft.com/graph/api/intune-mam-user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{usersId}/getManagedAppDiagnosticStatuses](https://docs.microsoft.com/graph/api/intune-mam-user-getmanagedappdiagnosticstatuses?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{usersId}/getManagedAppPolicies](https://docs.microsoft.com/graph/api/intune-mam-user-getmanagedapppolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/isManagedAppUserBlocked](https://docs.microsoft.com/graph/api/intune-mam-user-ismanagedappuserblocked?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/getManagedAppBlockedUsers](https://docs.microsoft.com/graph/api/intune-mam-user-getmanagedappblockedusers?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceAppManagement/androidManagedAppProtections/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-androidmanagedappprotection-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceAppManagement/iosLobAppProvisioningConfigurations/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-ioslobappprovisioningconfiguration-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceAppManagement/iosManagedAppProtections/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-iosmanagedappprotection-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceAppManagement/mdmWindowsInformationProtectionPolicies/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-mdmwindowsinformationprotectionpolicy-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceAppManagement/mobileApps/createCatalogApp](https://docs.microsoft.com/graph/api/intune-apps-mobileapp-createcatalogapp?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceAppManagement/mobileApps/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-mobileapp-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceAppManagement/targetedManagedAppConfigurations/{targetedManagedAppConfigurationId}/changeSettings](https://docs.microsoft.com/graph/api/intune-mam-targetedmanagedappconfiguration-changesettings?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceAppManagement/targetedManagedAppConfigurations/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-targetedmanagedappconfiguration-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getCachedReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getcachedreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getCompliancePolicyNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getcompliancepolicynoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getCompliancePolicyNonComplianceSummaryReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getcompliancepolicynoncompliancesummaryreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getComplianceSettingNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getcompliancesettingnoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getConfigurationPolicyNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getconfigurationpolicynoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getConfigurationPolicyNonComplianceSummaryReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getconfigurationpolicynoncompliancesummaryreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getConfigurationSettingNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getconfigurationsettingnoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceManagementIntentPerSettingContributingProfiles](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicemanagementintentpersettingcontributingprofiles?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceManagementIntentSettingsReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicemanagementintentsettingsreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicenoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDevicePoliciesComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicepoliciescompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDevicePolicySettingsComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicepolicysettingscompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDevicesStatusByPolicyPlatformComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicesstatusbypolicyplatformcompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDevicesStatusBySettingReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicesstatusbysettingreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceStatusByCompliacePolicyReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicestatusbycompliacepolicyreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceStatusByCompliancePolicySettingReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicestatusbycompliancepolicysettingreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceStatusSummaryByCompliacePolicyReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicestatussummarybycompliacepolicyreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDeviceStatusSummaryByCompliancePolicySettingsReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdevicestatussummarybycompliancepolicysettingsreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getDevicesWithoutCompliancePolicyReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getdeviceswithoutcompliancepolicyreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getHistoricalReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-gethistoricalreport?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/reports/getMobileApplicationManagementAppConfigurationReport](https://docs.microsoft.com/graph/api/intune-mam-devicemanagementreports-getmobileapplicationmanagementappconfigurationreport?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/reports/getMobileApplicationManagementAppRegistrationSummaryReport](https://docs.microsoft.com/graph/api/intune-mam-devicemanagementreports-getmobileapplicationmanagementappregistrationsummaryreport?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getNoncompliantDevicesAndSettingsReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getnoncompliantdevicesandsettingsreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getPolicyNonComplianceMetadata](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getpolicynoncompliancemetadata?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getPolicyNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getpolicynoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getPolicyNonComplianceSummaryReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getpolicynoncompliancesummaryreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getReportFilters](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getreportfilters?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/reports/getSettingComplianceAggReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getsettingcomplianceaggreport?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getSettingNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getsettingnoncompliancereport?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{usersId}/wipeManagedAppRegistrationsByAzureAdDeviceId](https://docs.microsoft.com/graph/api/intune-mam-user-wipemanagedappregistrationsbyazureaddeviceid?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4edf5f54-4666-44af-9de9-0144fb4b6e8c|
|**Consent Type**|Admin|
|**Display String**|Read Microsoft Intune apps|
|**Description**|Allows the app to read the properties, group assignments and status of apps, app configurations and app protection policies managed by Microsoft Intune.|
## Application Permission
|||
|-|-|
|**Id**|7a6ee1e7-141e-4cec-ae74-d9db155731ff|
|**Display String**|Read Microsoft Intune apps|
|**Description**|Allows the app to read the properties, group assignments and status of apps, app configurations and app protection policies managed by Microsoft Intune, without a signed-in user.|
## Resources
### [androidForWorkApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidforworkapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|packageId|String|The package identifier. This property is read-only.|
|appIdentifier|String|The Identity Name. This property is read-only.|
|usedLicenseCount|Int32|The number of VPP licenses in use.|
|totalLicenseCount|Int32|The total number of VPP licenses.|
|appStoreUrl|String|The Play for Work Store app URL.|
### [androidForWorkMobileAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidforworkmobileappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedDeviceMobileAppConfiguration|
|targetedMobileApps|String collection|the associated app. Inherited from managedDeviceMobileAppConfiguration|
|roleScopeTagIds|String collection|List of Scope Tags for this App configuration entity. Inherited from managedDeviceMobileAppConfiguration|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from managedDeviceMobileAppConfiguration|
|description|String|Admin provided description of the Device Configuration. Inherited from managedDeviceMobileAppConfiguration|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from managedDeviceMobileAppConfiguration|
|displayName|String|Admin provided name of the device configuration. Inherited from managedDeviceMobileAppConfiguration|
|version|Int32|Version of the device configuration. Inherited from managedDeviceMobileAppConfiguration|
|packageId|String|Android For Work app configuration package id.|
|payloadJson|String|Android For Work app configuration JSON payload.|
|permissionActions|androidPermissionAction collection|List of Android app permissions and corresponding permission actions.|
|profileApplicability|androidProfileApplicability|Android Enterprise profile applicability (AndroidWorkProfile, DeviceOwner, or default (applies to both)). Possible values are: `default`, `androidWorkProfile`, `androidDeviceOwner`.|
|connectedAppsEnabled|Boolean|Setting to specify whether to allow ConnectedApps experience for this app.|
### [androidLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidlobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|packageId|String|The package identifier.|
|minimumSupportedOperatingSystem|androidMinimumOperatingSystem|The value for the minimum applicable operating system.|
|versionName|String|The version name of Android Line of Business (LoB) app.|
|versionCode|String|The version code of Android Line of Business (LoB) app.|
### [androidManagedStoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidmanagedstoreapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|packageId|String|The package identifier. This property is read-only.|
|appIdentifier|String|The Identity Name.|
|usedLicenseCount|Int32|The number of VPP licenses in use. This property is read-only.|
|totalLicenseCount|Int32|The total number of VPP licenses. This property is read-only.|
|appStoreUrl|String|The Play for Work Store app URL. This property is read-only.|
|isPrivate|Boolean|Indicates whether the app is only available to a given enterprise's users. This property is read-only.|
|isSystemApp|Boolean|Indicates whether the app is a preinstalled system app.|
|appTracks|androidManagedStoreAppTrack collection|The tracks that are visible to this enterprise. This property is read-only.|
|supportsOemConfig|Boolean|Whether this app supports OEMConfig policy. This property is read-only.|
### [androidManagedStoreAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidmanagedstoreappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedDeviceMobileAppConfiguration|
|targetedMobileApps|String collection|the associated app. Inherited from managedDeviceMobileAppConfiguration|
|roleScopeTagIds|String collection|List of Scope Tags for this App configuration entity. Inherited from managedDeviceMobileAppConfiguration|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from managedDeviceMobileAppConfiguration|
|description|String|Admin provided description of the Device Configuration. Inherited from managedDeviceMobileAppConfiguration|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from managedDeviceMobileAppConfiguration|
|displayName|String|Admin provided name of the device configuration. Inherited from managedDeviceMobileAppConfiguration|
|version|Int32|Version of the device configuration. Inherited from managedDeviceMobileAppConfiguration|
|packageId|String|Android Enterprise app configuration package id.|
|payloadJson|String|Android Enterprise app configuration JSON payload.|
|permissionActions|androidPermissionAction collection|List of Android app permissions and corresponding permission actions.|
|appSupportsOemConfig|Boolean|Whether or not this AppConfig is an OEMConfig policy. This property is read-only.|
|profileApplicability|androidProfileApplicability|Android Enterprise profile applicability (AndroidWorkProfile, DeviceOwner, or default (applies to both)). Possible values are: `default`, `androidWorkProfile`, `androidDeviceOwner`.|
|connectedAppsEnabled|Boolean|Setting to specify whether to allow ConnectedApps experience for this app.|
### [androidManagedStoreWebApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidmanagedstorewebapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|packageId|String|The package identifier. This property is read-only. Inherited from androidManagedStoreApp|
|appIdentifier|String|The Identity Name. Inherited from androidManagedStoreApp|
|usedLicenseCount|Int32|The number of VPP licenses in use. This property is read-only. Inherited from androidManagedStoreApp|
|totalLicenseCount|Int32|The total number of VPP licenses. This property is read-only. Inherited from androidManagedStoreApp|
|appStoreUrl|String|The Play for Work Store app URL. This property is read-only. Inherited from androidManagedStoreApp|
|isPrivate|Boolean|Indicates whether the app is only available to a given enterprise's users. This property is read-only. Inherited from androidManagedStoreApp|
|isSystemApp|Boolean|Indicates whether the app is a preinstalled system app. Inherited from androidManagedStoreApp|
|appTracks|androidManagedStoreAppTrack collection|The tracks that are visible to this enterprise. This property is read-only. Inherited from androidManagedStoreApp|
|supportsOemConfig|Boolean|Whether this app supports OEMConfig policy. This property is read-only. Inherited from androidManagedStoreApp|
### [androidStoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-androidstoreapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|packageId|String|The package identifier.|
|appStoreUrl|String|The Android app store URL.|
|minimumSupportedOperatingSystem|androidMinimumOperatingSystem|The value for the minimum applicable operating system.|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-apps-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-apps-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [enterpriseCodeSigningCertificate ](https://docs.microsoft.com/graph/api/resources/intune-apps-enterprisecodesigningcertificate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the certificate, assigned upon creation. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported. Read-only.|
|content|Binary|The Windows Enterprise Code-Signing Certificate in the raw data format. Set to null once certificate has been uploaded and other properties have been populated.|
|status|certificateStatus|Whether the Certificate Status Provisioned or not Provisioned. Possible values are: notProvisioned, provisioned. Default is notProvisioned. Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported. Possible values are: `notProvisioned`, `provisioned`.|
|subjectName|String|The subject name for the cert. This might contain information such as country (C), state or province (S), locality (L), common name of the cert (CN), organization (O), and organizational unit (OU). Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported.|
|subject|String|The subject value for the cert. This might contain information such as country (C), state or province (S), locality (L), common name of the cert (CN), organization (O), and organizational unit (OU). Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported.|
|issuerName|String|The issuer name for the cert. This might contain information such as country (C), state or province (S), locality (L), common name of the cert (CN), organization (O), and organizational unit (OU). Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported.|
|issuer|String|The issuer value for the cert. This might contain information such as country (C), state or province (S), locality (L), common name of the cert (CN), organization (O), and organizational unit (OU). Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported.|
|expirationDateTime|DateTimeOffset|The cert expiration date and time (using ISO 8601 format, in UTC time). Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported.|
|uploadDateTime|DateTimeOffset|The date time of CodeSigning Cert when it is uploaded (using ISO 8601 format, in UTC time). Uploading a valid cert file through the Intune admin console will automatically populate this value in the HTTP response. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported.|
### [iosiPadOSWebClip ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosipadoswebclip?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appUrl|String|Indicates iOS/iPadOS web clip app URL. Example: "https://www.contoso.com"|
|useManagedBrowser|Boolean|Whether or not to use managed browser. When TRUE, the app will be required to be opened in Microsoft Edge. When FALSE, the app will not be required to be opened in Microsoft Edge. By default, this property is set to FALSE.|
### [iosLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-ioslobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|bundleId|String|The Identity Name.|
|applicableDeviceType|iosDeviceType|The iOS architecture for which this app can run on.|
|minimumSupportedOperatingSystem|iosMinimumOperatingSystem|The value for the minimum applicable operating system.|
|expirationDateTime|DateTimeOffset|The expiration time.|
|versionNumber|String|The version number of iOS Line of Business (LoB) app.|
|buildNumber|String|The build number of iOS Line of Business (LoB) app.|
### [iosLobAppProvisioningConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-apps-ioslobappprovisioningconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the LOB app provisioning configuration. This id is assigned during creation of the configuration. Supports: $filter, $select, $top, $OrderBy, $skip. $Search is not supported. Read-only.|
|expirationDateTime|DateTimeOffset|Optional profile expiration date and time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default.|
|payloadFileName|String|Payload file name (*.mobileprovision | *.xml).|
|payload|Binary|Payload. (UTF8 encoded byte array)|
|roleScopeTagIds|String collection|List of Scope Tags for this iOS LOB app provisioning configuration entity.|
|createdDateTime|DateTimeOffset|DateTime the object was created.|
|description|String|Admin provided description of the Device Configuration.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|displayName|String|Admin provided name of the device configuration.|
|version|Int32|Version of the device configuration.|
### [iosLobAppProvisioningConfigurationAssignment ](https://docs.microsoft.com/graph/api/resources/intune-apps-ioslobappprovisioningconfigurationassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|target|deviceAndAppManagementAssignmentTarget|The target group assignment defined by the admin.|
### [iosMobileAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosmobileappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedDeviceMobileAppConfiguration|
|targetedMobileApps|String collection|the associated app. Inherited from managedDeviceMobileAppConfiguration|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from managedDeviceMobileAppConfiguration|
|description|String|Admin provided description of the Device Configuration. Inherited from managedDeviceMobileAppConfiguration|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from managedDeviceMobileAppConfiguration|
|displayName|String|Admin provided name of the device configuration. Inherited from managedDeviceMobileAppConfiguration|
|version|Int32|Version of the device configuration. Inherited from managedDeviceMobileAppConfiguration|
|encodedSettingXml|Binary|mdm app configuration Base64 binary.|
|settings|appConfigurationSettingItem collection|app configuration setting items.|
### [iosStoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosstoreapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|bundleId|String|The Identity Name.|
|appStoreUrl|String|The Apple App Store URL|
|applicableDeviceType|iosDeviceType|The iOS architecture for which this app can run on.|
|minimumSupportedOperatingSystem|iosMinimumOperatingSystem|The value for the minimum applicable operating system.|
### [iosVppApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosvppapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|usedLicenseCount|Int32|The number of VPP licenses in use.|
|totalLicenseCount|Int32|The total number of VPP licenses.|
|releaseDateTime|DateTimeOffset|The VPP application release date and time.|
|appStoreUrl|String|The store URL.|
|licensingType|vppLicensingType|The supported License Type.|
|applicableDeviceType|iosDeviceType|The applicable iOS Device Type.|
|vppTokenOrganizationName|String|The organization associated with the Apple Volume Purchase Program Token|
|vppTokenAccountType|vppTokenAccountType|The type of volume purchase program which the given Apple Volume Purchase Program Token is associated with. Possible values are: `business`, `education`. Possible values are: `business`, `education`.|
|vppTokenAppleId|String|The Apple Id associated with the given Apple Volume Purchase Program Token.|
|bundleId|String|The Identity Name.|
### [iosVppAppAssignedDeviceLicense ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosvppappassigneddevicelicense?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from iosVppAppAssignedLicense|
|userEmailAddress|String|The user email address. Inherited from iosVppAppAssignedLicense|
|userId|String|The user ID. Inherited from iosVppAppAssignedLicense|
|userName|String|The user name. Inherited from iosVppAppAssignedLicense|
|userPrincipalName|String|The user principal name. Inherited from iosVppAppAssignedLicense|
|managedDeviceId|String|The managed device ID.|
|deviceName|String|The device name.|
### [iosVppAppAssignedLicense ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosvppappassignedlicense?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only.|
|userEmailAddress|String|The user email address.|
|userId|String|The user ID.|
|userName|String|The user name.|
|userPrincipalName|String|The user principal name.|
### [iosVppAppAssignedUserLicense ](https://docs.microsoft.com/graph/api/resources/intune-apps-iosvppappassigneduserlicense?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from iosVppAppAssignedLicense|
|userEmailAddress|String|The user email address. Inherited from iosVppAppAssignedLicense|
|userId|String|The user ID. Inherited from iosVppAppAssignedLicense|
|userName|String|The user name. Inherited from iosVppAppAssignedLicense|
|userPrincipalName|String|The user principal name. Inherited from iosVppAppAssignedLicense|
### [macOSDmgApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosdmgapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. This property is read-only. Inherited from mobileLobApp|
|primaryBundleId|String|The bundleId of the primary .app in the DMG (Apple Disk Image). This maps to the CFBundleIdentifier in the app's bundle configuration.|
|primaryBundleVersion|String|The version of the primary .app in the DMG (Apple Disk Image). This maps to the CFBundleShortVersion in the app's bundle configuration.|
|includedApps|macOSIncludedApp collection|The list of .apps expected to be installed by the DMG (Apple Disk Image). This collection can contain a maximum of 500 elements.|
|ignoreVersionDetection|Boolean|When TRUE, indicates that the app's version will NOT be used to detect if the app is installed on a device. When FALSE, indicates that the app's version will be used to detect if the app is installed on a device. Set this to true for apps that use a self update feature. The default value is FALSE.|
|minimumSupportedOperatingSystem|macOSMinimumOperatingSystem|ComplexType macOSMinimumOperatingSystem that indicates the minimum operating system applicable for the application.|
### [macOSLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macoslobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|bundleId|String|The primary bundleId of the package.|
|minimumSupportedOperatingSystem|macOSMinimumOperatingSystem|ComplexType macOSMinimumOperatingSystem that indicates the minimum operating system applicable for the application.|
|buildNumber|String|The build number of the package. This should match the package CFBundleShortVersionString of the .pkg file.|
|versionNumber|String|The version number of the package. This should match the package CFBundleVersion in the packageinfo file.|
|childApps|macOSLobChildApp collection|List of ComplexType macOSLobChildApp objects. Represents the apps expected to be installed by the package.|
|md5HashChunkSize|Int32|The chunk size for MD5 hash. This is '0' or empty if the package was uploaded directly. If the Intune App Wrapping Tool is used to create a .intunemac, this value can be found inside the Detection.xml file.|
|md5Hash|String collection|The MD5 hash codes. This is empty if the package was uploaded directly. If the Intune App Wrapping Tool is used to create a .intunemac, this value can be found inside the Detection.xml file.|
|ignoreVersionDetection|Boolean|When TRUE, indicates that the app's version will NOT be used to detect if the app is installed on a device. When FALSE, indicates that the app's version will be used to detect if the app is installed on a device. Set this to true for apps that use a self update feature.|
|installAsManaged|Boolean|When TRUE, indicates that the app will be installed as managed (requires macOS 11.0 and other managed package restrictions). When FALSE, indicates that the app will be installed as unmanaged.|
### [macOSMdatpApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosmdatpapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. Inherited from mobileApp|
### [macOSMicrosoftDefenderApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosmicrosoftdefenderapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
### [macOSMicrosoftEdgeApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosmicrosoftedgeapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|channel|microsoftEdgeChannel|The channel to install on target devices. Possible values are: `dev`, `beta`, `stable`, `unknownFutureValue`.|
### [macOSOfficeSuiteApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosofficesuiteapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
### [macOSPkgApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macospkgapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. This property is read-only. Inherited from mobileLobApp|
|primaryBundleId|String|The bundleId of the primary app in the PKG. This maps to the CFBundleIdentifier in the app's bundle configuration.|
|primaryBundleVersion|String|The version of the primary app in the PKG. This maps to the CFBundleShortVersion in the app's bundle configuration.|
|includedApps|macOSIncludedApp collection|The list of apps expected to be installed by the PKG. This collection can contain a maximum of 500 elements.|
|ignoreVersionDetection|Boolean|When TRUE, indicates that the app's version will NOT be used to detect if the app is installed on a device. When FALSE, indicates that the app's version will be used to detect if the app is installed on a device. Set this to true for apps that use a self update feature. The default value is FALSE.|
|minimumSupportedOperatingSystem|macOSMinimumOperatingSystem|ComplexType macOSMinimumOperatingSystem that indicates the minimum operating system applicable for the application.|
|preInstallScript|macOSAppScript|ComplexType macOSAppScript the contains the post-install script for the app. This will execute on the macOS device after the app is installed.|
|postInstallScript|macOSAppScript|ComplexType macOSAppScript the contains the post-install script for the app. This will execute on the macOS device after the app is installed.|
### [macOsVppApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosvppapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|usedLicenseCount|Int32|The number of VPP licenses in use.|
|totalLicenseCount|Int32|The total number of VPP licenses.|
|releaseDateTime|DateTimeOffset|The VPP application release date and time.|
|appStoreUrl|String|The store URL.|
|licensingType|vppLicensingType|The supported License Type.|
|vppTokenOrganizationName|String|The organization associated with the Apple Volume Purchase Program Token|
|vppTokenAccountType|vppTokenAccountType|The type of volume purchase program which the given Apple Volume Purchase Program Token is associated with. Possible values are: `business`, `education`. Possible values are: `business`, `education`.|
|vppTokenAppleId|String|The Apple Id associated with the given Apple Volume Purchase Program Token.|
|bundleId|String|The Identity Name.|
|vppTokenId|String|Identifier of the VPP token associated with this app.|
|revokeLicenseActionResults|macOsVppAppRevokeLicensesActionResult collection|Results of revoke license actions on this app.|
### [macOsVppAppAssignedLicense ](https://docs.microsoft.com/graph/api/resources/intune-apps-macosvppappassignedlicense?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only.|
|userEmailAddress|String|The user email address.|
|userId|String|The user ID.|
|userName|String|The user name.|
|userPrincipalName|String|The user principal name.|
### [macOSWebClip ](https://docs.microsoft.com/graph/api/resources/intune-apps-macoswebclip?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|appUrl|String|The web app URL starting with http:// or https://, such as https://learn.microsoft.com/mem/.|
|fullScreenEnabled|Boolean|Whether or not to open the web clip as a full-screen web app. Defaults to false. If TRUE, opens the web clip as a full-screen web app. If FALSE, the web clip opens inside of another app.|
|preComposedIconEnabled|Boolean|Whether or not the icon for the app is precomosed. Defaults to false. If TRUE, prevents SpringBoard from adding "shine" to the icon. If FALSE, SpringBoard can add "shine".|
### [managedAndroidLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-managedandroidlobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appAvailability|managedAppAvailability|The Application's availability. Inherited from managedApp. Possible values are: `global`, `lineOfBusiness`.|
|version|String|The Application's version. Inherited from managedApp|
|committedContentVersion|String|The internal committed content version. Inherited from managedMobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from managedMobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from managedMobileLobApp|
|packageId|String|The package identifier.|
|minimumSupportedOperatingSystem|androidMinimumOperatingSystem|The value for the minimum applicable operating system.|
|versionName|String|The version name of managed Android Line of Business (LoB) app.|
|versionCode|String|The version code of managed Android Line of Business (LoB) app.|
### [managedAndroidStoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-managedandroidstoreapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appAvailability|managedAppAvailability|The Application's availability. Inherited from managedApp. Possible values are: `global`, `lineOfBusiness`.|
|version|String|The Application's version. Inherited from managedApp|
|packageId|String|The app's package ID.|
|appStoreUrl|String|The Android AppStoreUrl.|
|minimumSupportedOperatingSystem|androidMinimumOperatingSystem|The value for the minimum supported operating system.|
### [managedApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-managedapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appAvailability|managedAppAvailability|The Application's availability. Possible values are: `global`, `lineOfBusiness`.|
|version|String|The Application's version.|
### [managedDeviceMobileAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-apps-manageddevicemobileappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|targetedMobileApps|String collection|the associated app.|
|createdDateTime|DateTimeOffset|DateTime the object was created.|
|description|String|Admin provided description of the Device Configuration.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|displayName|String|Admin provided name of the device configuration.|
|version|Int32|Version of the device configuration.|
### [managedDeviceMobileAppConfigurationAssignment ](https://docs.microsoft.com/graph/api/resources/intune-apps-manageddevicemobileappconfigurationassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the entity.|
|target|deviceAndAppManagementAssignmentTarget|Assignment target that the T&C policy is assigned to.|
### [managedDeviceMobileAppConfigurationDeviceStatus ](https://docs.microsoft.com/graph/api/resources/intune-apps-manageddevicemobileappconfigurationdevicestatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|deviceDisplayName|String|Device name of the DevicePolicyStatus.|
|userName|String|The User Name that is being reported|
|deviceModel|String|The device model that is being reported|
|complianceGracePeriodExpirationDateTime|DateTimeOffset|The DateTime when device compliance grace period expires|
|status|complianceStatus|Compliance status of the policy report. Possible values are: `unknown`, `notApplicable`, `compliant`, `remediated`, `nonCompliant`, `error`, `conflict`, `notAssigned`.|
|lastReportedDateTime|DateTimeOffset|Last modified date time of the policy report.|
|userPrincipalName|String|UserPrincipalName.|
### [managedDeviceMobileAppConfigurationDeviceSummary ](https://docs.microsoft.com/graph/api/resources/intune-apps-manageddevicemobileappconfigurationdevicesummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|pendingCount|Int32|Number of pending devices|
|notApplicableCount|Int32|Number of not applicable devices|
|successCount|Int32|Number of succeeded devices|
|errorCount|Int32|Number of error devices|
|failedCount|Int32|Number of failed devices|
|lastUpdateDateTime|DateTimeOffset|Last update time|
|configurationVersion|Int32|Version of the policy for that overview|
### [managedDeviceMobileAppConfigurationUserStatus ](https://docs.microsoft.com/graph/api/resources/intune-apps-manageddevicemobileappconfigurationuserstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|userDisplayName|String|User name of the DevicePolicyStatus.|
|devicesCount|Int32|Devices count for that user.|
|status|complianceStatus|Compliance status of the policy report. Possible values are: `unknown`, `notApplicable`, `compliant`, `remediated`, `nonCompliant`, `error`, `conflict`, `notAssigned`.|
|lastReportedDateTime|DateTimeOffset|Last modified date time of the policy report.|
|userPrincipalName|String|UserPrincipalName.|
### [managedDeviceMobileAppConfigurationUserSummary ](https://docs.microsoft.com/graph/api/resources/intune-apps-manageddevicemobileappconfigurationusersummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|pendingCount|Int32|Number of pending Users|
|notApplicableCount|Int32|Number of not applicable users|
|successCount|Int32|Number of succeeded Users|
|errorCount|Int32|Number of error Users|
|failedCount|Int32|Number of failed Users|
|lastUpdateDateTime|DateTimeOffset|Last update time|
|configurationVersion|Int32|Version of the policy for that overview|
### [managedIOSLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-managedioslobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appAvailability|managedAppAvailability|The Application's availability. Inherited from managedApp. Possible values are: `global`, `lineOfBusiness`.|
|version|String|The Application's version. Inherited from managedApp|
|committedContentVersion|String|The internal committed content version. Inherited from managedMobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from managedMobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from managedMobileLobApp|
|bundleId|String|The Identity Name.|
|applicableDeviceType|iosDeviceType|The iOS architecture for which this app can run on.|
|minimumSupportedOperatingSystem|iosMinimumOperatingSystem|The value for the minimum applicable operating system.|
|expirationDateTime|DateTimeOffset|The expiration time.|
|versionNumber|String|The version number of managed iOS Line of Business (LoB) app.|
|buildNumber|String|The build number of managed iOS Line of Business (LoB) app.|
### [managedIOSStoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-managediosstoreapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appAvailability|managedAppAvailability|The Application's availability. Inherited from managedApp. Possible values are: `global`, `lineOfBusiness`.|
|version|String|The Application's version. Inherited from managedApp|
|bundleId|String|The app's Bundle ID.|
|appStoreUrl|String|The Apple AppStoreUrl.|
|applicableDeviceType|iosDeviceType|The iOS architecture for which this app can run on.|
|minimumSupportedOperatingSystem|iosMinimumOperatingSystem|The value for the minimum supported operating system.|
### [managedMobileLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-managedmobilelobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appAvailability|managedAppAvailability|The Application's availability. Inherited from managedApp. Possible values are: `global`, `lineOfBusiness`.|
|version|String|The Application's version. Inherited from managedApp|
|committedContentVersion|String|The internal committed content version.|
|fileName|String|The name of the main Lob application file.|
|size|Int64|The total size, including all uploaded files.|
### [microsoftStoreForBusinessApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-microsoftstoreforbusinessapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|usedLicenseCount|Int32|The number of Microsoft Store for Business licenses in use.|
|totalLicenseCount|Int32|The total number of Microsoft Store for Business licenses.|
|productKey|String|The app product key|
|licenseType|microsoftStoreForBusinessLicenseType|The app license type. Possible values are: `offline`, `online`.|
|packageIdentityName|String|The app package identifier|
### [microsoftStoreForBusinessContainedApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-microsoftstoreforbusinesscontainedapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileContainedApp|
|appUserModelId|String|The app user model ID of the contained app of a MicrosoftStoreForBusinessApp.|
### [mobileApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|displayName|String|The admin provided or imported title of the app.|
|description|String|The description of the app.|
|publisher|String|The publisher of the app.|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon.|
|createdDateTime|DateTimeOffset|The date and time the app was created.|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified.|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin.|
|privacyInformationUrl|String|The privacy statement Url.|
|informationUrl|String|The more information Url.|
|owner|String|The owner of the app.|
|developer|String|The developer of the app.|
|notes|String|Notes for the app.|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Possible values are: `notPublished`, `processing`, `published`.|
### [mobileAppAssignment ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|intent|installIntent|The install intent defined by the admin. Possible values are: `available`, `required`, `uninstall`, `availableWithoutEnrollment`.|
|target|deviceAndAppManagementAssignmentTarget|The target group assignment defined by the admin.|
|settings|mobileAppAssignmentSettings|The settings for target assignment defined by the admin.|
### [mobileAppCategory ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappcategory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key of the entity.|
|displayName|String|The name of the app category.|
|lastModifiedDateTime|DateTimeOffset|The date and time the mobileAppCategory was last modified.|
### [mobileAppContent ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappcontent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The app content version.|
### [mobileAppContentFile ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappcontentfile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|azureStorageUri|String|The Azure Storage URI.|
|isCommitted|Boolean|A value indicating whether the file is committed.|
|id|String|The File Id.|
|createdDateTime|DateTimeOffset|The time the file was created.|
|name|String|the file name.|
|size|Int64|The size of the file prior to encryption.|
|sizeEncrypted|Int64|The size of the file after encryption.|
|azureStorageUriExpirationDateTime|DateTimeOffset|The time the Azure storage Uri expires.|
|manifest|Binary|The manifest information.|
|uploadState|mobileAppContentFileUploadState|The state of the current upload request. Possible values are: `success`, `transientError`, `error`, `unknown`, `azureStorageUriRequestSuccess`, `azureStorageUriRequestPending`, `azureStorageUriRequestFailed`, `azureStorageUriRequestTimedOut`, `azureStorageUriRenewalSuccess`, `azureStorageUriRenewalPending`, `azureStorageUriRenewalFailed`, `azureStorageUriRenewalTimedOut`, `commitFileSuccess`, `commitFilePending`, `commitFileFailed`, `commitFileTimedOut`.|
### [mobileAppDependency ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappdependency?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The relationship entity id. Inherited from mobileAppRelationship|
|targetId|String|The target mobile app's app id. Inherited from mobileAppRelationship|
|targetDisplayName|String|The target mobile app's display name. This property is read-only. Inherited from mobileAppRelationship|
|targetDisplayVersion|String|The target mobile app's display version. This property is read-only. Inherited from mobileAppRelationship|
|targetPublisher|String|The target mobile app's publisher. This property is read-only. Inherited from mobileAppRelationship|
|targetType|mobileAppRelationshipType|The type of relationship indicating whether the target is a parent or child. This property is read-only. Inherited from mobileAppRelationship. Possible values are: `child`, `parent`.|
|dependencyType|mobileAppDependencyType|The type of dependency relationship between the parent and child apps. Possible values are: `detect`, `autoInstall`.|
|dependentAppCount|Int32|The total number of apps that directly or indirectly depend on the parent app. This property is read-only.|
|dependsOnAppCount|Int32|The total number of apps the child app directly or indirectly depends on. This property is read-only.|
### [mobileAppInstallStatus ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappinstallstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|deviceName|String|Device name|
|deviceId|String|Device ID|
|lastSyncDateTime|DateTimeOffset|Last sync date time|
|mobileAppInstallStatusValue|resultantAppState|The install state of the app. Possible values are: `installed`, `failed`, `notInstalled`, `uninstallFailed`, `pendingInstall`, `unknown`, `notApplicable`.|
|installState|resultantAppState|The install state of the app. Possible values are: `installed`, `failed`, `notInstalled`, `uninstallFailed`, `pendingInstall`, `unknown`, `notApplicable`.|
|installStateDetail|resultantAppStateDetail|The install state detail of the app. Possible values are: `noAdditionalDetails`, `dependencyFailedToInstall`, `dependencyWithRequirementsNotMet`, `dependencyPendingReboot`, `dependencyWithAutoInstallDisabled`, `supersededAppUninstallFailed`, `supersededAppUninstallPendingReboot`, `removingSupersededApps`, `iosAppStoreUpdateFailedToInstall`, `vppAppHasUpdateAvailable`, `userRejectedUpdate`, `uninstallPendingReboot`, `supersedingAppsDetected`, `supersededAppsDetected`, `seeInstallErrorCode`, `autoInstallDisabled`, `managedAppNoLongerPresent`, `userRejectedInstall`, `userIsNotLoggedIntoAppStore`, `untargetedSupersedingAppsDetected`, `appRemovedBySupersedence`, `seeUninstallErrorCode`, `pendingReboot`, `installingDependencies`, `contentDownloaded`, `supersedingAppsNotApplicable`, `powerShellScriptRequirementNotMet`, `registryRequirementNotMet`, `fileSystemRequirementNotMet`, `platformNotApplicable`, `minimumCpuSpeedNotMet`, `minimumLogicalProcessorCountNotMet`, `minimumPhysicalMemoryNotMet`, `minimumOsVersionNotMet`, `minimumDiskSpaceNotMet`, `processorArchitectureNotApplicable`.|
|errorCode|Int32|The error code for install or uninstall failures.|
|osVersion|String|OS Version|
|osDescription|String|OS Description|
|userName|String|Device User Name|
|userPrincipalName|String|User Principal Name|
|displayVersion|String|Human readable version of the application|
### [mobileAppInstallSummary ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappinstallsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|installedDeviceCount|Int32|Number of Devices that have successfully installed this app.|
|failedDeviceCount|Int32|Number of Devices that have failed to install this app.|
|notApplicableDeviceCount|Int32|Number of Devices that are not applicable for this app.|
|notInstalledDeviceCount|Int32|Number of Devices that does not have this app installed.|
|pendingInstallDeviceCount|Int32|Number of Devices that have been notified to install this app.|
|installedUserCount|Int32|Number of Users whose devices have all succeeded to install this app.|
|failedUserCount|Int32|Number of Users that have 1 or more device that failed to install this app.|
|notApplicableUserCount|Int32|Number of Users whose devices were all not applicable for this app.|
|notInstalledUserCount|Int32|Number of Users that have 1 or more devices that did not install this app.|
|pendingInstallUserCount|Int32|Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.|
### [mobileAppProvisioningConfigGroupAssignment ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappprovisioningconfiggroupassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|targetGroupId|String|The ID of the AAD group in which the app provisioning configuration is being targeted.|
|id|String|Key of the entity.|
### [mobileAppPublishingConstraints ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileapppublishingconstraints?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|win32LobAppConstraints|win32LobAppPublishingConstraints|Contains properties for Win32 LOB app publishing constraints.|
### [mobileAppRelationship ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileapprelationship?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The relationship entity id.|
|targetId|String|The target mobile app's app id.|
|targetDisplayName|String|The target mobile app's display name. This property is read-only.|
|targetDisplayVersion|String|The target mobile app's display version. This property is read-only.|
|targetPublisher|String|The target mobile app's publisher. This property is read-only.|
|targetType|mobileAppRelationshipType|The type of relationship indicating whether the target is a parent or child. This property is read-only. Possible values are: `child`, `parent`.|
### [mobileAppRelationshipState ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileapprelationshipstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|sourceIds|String collection|The collection of source mobile app's ids.|
|targetId|String|The related target app's id.|
|targetDisplayName|String|The related target app's display name.|
|deviceId|String|The corresponding device id.|
|installState|resultantAppState|The install state of the app of target app. Possible values are: `installed`, `failed`, `notInstalled`, `uninstallFailed`, `pendingInstall`, `unknown`, `notApplicable`.|
|installStateDetail|resultantAppStateDetail|The install state detail of the app. Possible values are: `noAdditionalDetails`, `dependencyFailedToInstall`, `dependencyWithRequirementsNotMet`, `dependencyPendingReboot`, `dependencyWithAutoInstallDisabled`, `supersededAppUninstallFailed`, `supersededAppUninstallPendingReboot`, `removingSupersededApps`, `iosAppStoreUpdateFailedToInstall`, `vppAppHasUpdateAvailable`, `userRejectedUpdate`, `uninstallPendingReboot`, `supersedingAppsDetected`, `supersededAppsDetected`, `seeInstallErrorCode`, `autoInstallDisabled`, `managedAppNoLongerPresent`, `userRejectedInstall`, `userIsNotLoggedIntoAppStore`, `untargetedSupersedingAppsDetected`, `appRemovedBySupersedence`, `seeUninstallErrorCode`, `pendingReboot`, `installingDependencies`, `contentDownloaded`, `supersedingAppsNotApplicable`, `powerShellScriptRequirementNotMet`, `registryRequirementNotMet`, `fileSystemRequirementNotMet`, `platformNotApplicable`, `minimumCpuSpeedNotMet`, `minimumLogicalProcessorCountNotMet`, `minimumPhysicalMemoryNotMet`, `minimumOsVersionNotMet`, `minimumDiskSpaceNotMet`, `processorArchitectureNotApplicable`.|
|errorCode|Int32|The error code for install or uninstall failures of target app.|
|targetLastSyncDateTime|DateTimeOffset|The last sync time of the target app.|
### [mobileAppSupersedence ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobileappsupersedence?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The relationship entity id. Inherited from mobileAppRelationship|
|targetId|String|The target mobile app's app id. Inherited from mobileAppRelationship|
|targetDisplayName|String|The target mobile app's display name. This property is read-only. Inherited from mobileAppRelationship|
|targetDisplayVersion|String|The target mobile app's display version. This property is read-only. Inherited from mobileAppRelationship|
|targetPublisher|String|The target mobile app's publisher. This property is read-only. Inherited from mobileAppRelationship|
|targetType|mobileAppRelationshipType|The type of relationship indicating whether the target is a parent or child. This property is read-only. Inherited from mobileAppRelationship. Possible values are: `child`, `parent`.|
|supersedenceType|mobileAppSupersedenceType|The supersedence relationship type between the parent and child apps. Possible values are: `update`, `replace`.|
|supersededAppCount|Int32|The total number of apps directly or indirectly superseded by the child app. This property is read-only.|
|supersedingAppCount|Int32|The total number of apps directly or indirectly superseding the parent app. This property is read-only.|
### [mobileContainedApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobilecontainedapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [mobileLobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-mobilelobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version.|
|fileName|String|The name of the main Lob application file.|
|size|Int64|The total size, including all uploaded files.|
### [officeSuiteApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-officesuiteapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|autoAcceptEula|Boolean|The value to accept the EULA automatically on the enduser's device.|
|productIds|officeProductId collection|The Product Ids that represent the Office365 Suite SKU.|
|excludedApps|excludedApps|The property to represent the apps which are excluded from the selected Office365 Product Id.|
|useSharedComputerActivation|Boolean|The property to represent that whether the shared computer activation is used not for Office365 app suite.|
|updateChannel|officeUpdateChannel|The property to represent the Office365 Update Channel. Possible values are: `none`, `current`, `deferred`, `firstReleaseCurrent`, `firstReleaseDeferred`, `monthlyEnterprise`.|
|officeSuiteAppDefaultFileFormat|officeSuiteDefaultFileFormatType|The property to represent the Office365 default file format type. Possible values are: `notConfigured`, `officeOpenXMLFormat`, `officeOpenDocumentFormat`, `unknownFutureValue`.|
|officePlatformArchitecture|windowsArchitecture|The property to represent the Office365 app suite version. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`, `arm64`.|
|localesToInstall|String collection|The property to represent the locales which are installed when the apps from Office365 is installed. It uses standard RFC 6033. Ref: https://technet.microsoft.com/library/cc179219(v=office.16).aspx|
|installProgressDisplayLevel|officeSuiteInstallProgressDisplayLevel|To specify the level of display for the Installation Progress Setup UI on the Device. Possible values are: `none`, `full`.|
|shouldUninstallOlderVersionsOfOffice|Boolean|The property to determine whether to uninstall existing Office MSI if an Office365 app suite is deployed to the device or not.|
|targetVersion|String|The property to represent the specific target version for the Office365 app suite that should be remained deployed on the devices.|
|updateVersion|String|The property to represent the update version in which the specific target version is available for the Office365 app suite.|
|officeConfigurationXml|Binary|The property to represent the XML configuration file that can be specified for Office ProPlus Apps. Takes precedence over all other properties. When present, the XML configuration file will be used to create the app.|
### [symantecCodeSigningCertificate ](https://docs.microsoft.com/graph/api/resources/intune-apps-symanteccodesigningcertificate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key of the entity. This property is read-only.|
|content|Binary|The Windows Symantec Code-Signing Certificate in the raw data format.|
|status|certificateStatus|The Cert Status Provisioned or not Provisioned. Possible values are: `notProvisioned`, `provisioned`.|
|password|String|The Password required for .pfx file.|
|subjectName|String|The Subject Name for the cert.|
|subject|String|The Subject value for the cert.|
|issuerName|String|The Issuer Name for the cert.|
|issuer|String|The Issuer value for the cert.|
|expirationDateTime|DateTimeOffset|The Cert Expiration Date.|
|uploadDateTime|DateTimeOffset|The Type of the CodeSigning Cert as Symantec Cert.|
### [userAppInstallStatus ](https://docs.microsoft.com/graph/api/resources/intune-apps-userappinstallstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|userName|String|User name.|
|userPrincipalName|String|User Principal Name.|
|installedDeviceCount|Int32|Installed Device Count.|
|failedDeviceCount|Int32|Failed Device Count.|
|notInstalledDeviceCount|Int32|Not installed device count.|
### [webApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-webapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appUrl|String|The web app URL. This property cannot be PATCHed.|
|useManagedBrowser|Boolean|Whether or not to use managed browser. This property is only applicable for Android and IOS.|
### [win32LobApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-win32lobapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|installCommandLine|String|The command line to install this app|
|uninstallCommandLine|String|The command line to uninstall this app|
|applicableArchitectures|windowsArchitecture|The Windows architecture(s) for which this app can run on. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`.|
|minimumFreeDiskSpaceInMB|Int32|The value for the minimum free disk space which is required to install this app.|
|minimumMemoryInMB|Int32|The value for the minimum physical memory which is required to install this app.|
|minimumNumberOfProcessors|Int32|The value for the minimum number of processors which is required to install this app.|
|minimumCpuSpeedInMHz|Int32|The value for the minimum CPU speed which is required to install this app.|
|rules|win32LobAppRule collection|The detection and requirement rules for this app.|
|installExperience|win32LobAppInstallExperience|The install experience for this app.|
|returnCodes|win32LobAppReturnCode collection|The return codes for post installation behavior.|
|msiInformation|win32LobAppMsiInformation|The MSI details if this Win32 app is an MSI app.|
|setupFilePath|String|The relative path of the setup file in the encrypted Win32LobApp package.|
|minimumSupportedWindowsRelease|String|The value for the minimum supported windows release.|
### [windowsAppX ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsappx?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|applicableArchitectures|windowsArchitecture|The Windows architecture(s) on which this app can run. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`; default value is `none`. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`.|
|identityName|String|The identity name of the uploaded app package. For example: "Contoso.DemoApp".|
|identityPublisherHash|String|The identity publisher hash of the uploaded app package. This is the hash of the publisher from the manifest. For example: "AB82CD0XYZ".|
|identityResourceIdentifier|String|The identity resource identifier of the uploaded app package. For example: "TestResourceId".|
|isBundle|Boolean|When TRUE, indicates that the app is a bundle. When FALSE, indicates that the app is not a bundle. By default, property is set to FALSE.|
|minimumSupportedOperatingSystem|windowsMinimumOperatingSystem|The value for the minimum applicable operating system. Valid values for a WindowsAppX app include `v8_0`, `v8_1` and `v10_0`. If the app is a bundle, the minimum supported OS has to be at least `v8_1`.|
|identityVersion|String|The identity version of the uploaded app package. For example: "1.0.0.0".|
### [windowsMicrosoftEdgeApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsmicrosoftedgeapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|channel|microsoftEdgeChannel|The channel to install on target devices. The possible values are dev, beta, and stable. By default, this property is set to dev. Possible values are: `dev`, `beta`, `stable`, `unknownFutureValue`.|
|displayLanguageLocale|String|The language locale to use when the Edge app displays text to the user.|
### [windowsMobileMSI ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsmobilemsi?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|commandLine|String|The command line.|
|productCode|String|The product code.|
|productVersion|String|The product version of Windows Mobile MSI Line of Business (LoB) app.|
|ignoreVersionDetection|Boolean|A boolean to control whether the app's version will be used to detect the app after it is installed on a device. Set this to true for Windows Mobile MSI Line of Business (LoB) apps that use a self update feature.|
### [windowsPhone81AppX ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsphone81appx?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. This property is read-only. Inherited from mobileLobApp|
|applicableArchitectures|windowsArchitecture|The Windows architecture(s) for which this app can run on. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`, `arm64`.|
|identityName|String|The Identity Name.|
|identityPublisherHash|String|The Identity Publisher Hash.|
|identityResourceIdentifier|String|The Identity Resource Identifier.|
|minimumSupportedOperatingSystem|windowsMinimumOperatingSystem|The value for the minimum applicable operating system.|
|phoneProductIdentifier|String|The Phone Product Identifier.|
|phonePublisherId|String|The Phone Publisher Id.|
|identityVersion|String|The identity version.|
### [windowsPhone81AppXBundle ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsphone81appxbundle?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. This property is read-only. Inherited from mobileLobApp|
|applicableArchitectures|windowsArchitecture|The Windows architecture(s) for which this app can run on. Inherited from windowsPhone81AppX. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`, `arm64`.|
|identityName|String|The Identity Name. Inherited from windowsPhone81AppX|
|identityPublisherHash|String|The Identity Publisher Hash. Inherited from windowsPhone81AppX|
|identityResourceIdentifier|String|The Identity Resource Identifier. Inherited from windowsPhone81AppX|
|minimumSupportedOperatingSystem|windowsMinimumOperatingSystem|The value for the minimum applicable operating system. Inherited from windowsPhone81AppX|
|phoneProductIdentifier|String|The Phone Product Identifier. Inherited from windowsPhone81AppX|
|phonePublisherId|String|The Phone Publisher Id. Inherited from windowsPhone81AppX|
|identityVersion|String|The identity version. Inherited from windowsPhone81AppX|
|appXPackageInformationList|windowsPackageInformation collection|The list of AppX Package Information.|
### [windowsPhone81StoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsphone81storeapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|appStoreUrl|String|The Windows Phone 8.1 app store URL.|
### [windowsPhoneXAP ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsphonexap?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. This property is read-only. Inherited from mobileLobApp|
|minimumSupportedOperatingSystem|windowsMinimumOperatingSystem|The value for the minimum applicable operating system.|
|productIdentifier|String|The Product Identifier.|
|identityVersion|String|The identity version.|
### [windowsStoreApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsstoreapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|appStoreUrl|String|The Windows app store URL.|
### [windowsUniversalAppX ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsuniversalappx?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|committedContentVersion|String|The internal committed content version. Inherited from mobileLobApp|
|fileName|String|The name of the main Lob application file. Inherited from mobileLobApp|
|size|Int64|The total size, including all uploaded files. Inherited from mobileLobApp|
|applicableArchitectures|windowsArchitecture|The Windows architecture(s) for which this app can run on. Possible values are: `none`, `x86`, `x64`, `arm`, `neutral`.|
|applicableDeviceTypes|windowsDeviceType|The Windows device type(s) for which this app can run on. Possible values are: `none`, `desktop`, `mobile`, `holographic`, `team`.|
|identityName|String|The Identity Name.|
|identityPublisherHash|String|The Identity Publisher Hash.|
|identityResourceIdentifier|String|The Identity Resource Identifier.|
|isBundle|Boolean|Whether or not the app is a bundle.|
|minimumSupportedOperatingSystem|windowsMinimumOperatingSystem|The value for the minimum applicable operating system.|
|identityVersion|String|The identity version.|
### [windowsUniversalAppXContainedApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowsuniversalappxcontainedapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileContainedApp|
|appUserModelId|String|The app user model ID of the contained app of a WindowsUniversalAppX app.|
### [windowsWebApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-windowswebapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|appUrl|String|Indicates the Windows web app URL. Example: "https://www.contoso.com"|
### [winGetApp ](https://docs.microsoft.com/graph/api/resources/intune-apps-wingetapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. This property is read-only. Inherited from mobileApp|
|displayName|String|The admin provided or imported title of the app. Inherited from mobileApp|
|description|String|The description of the app. Inherited from mobileApp|
|publisher|String|The publisher of the app. Inherited from mobileApp|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon. Inherited from mobileApp|
|createdDateTime|DateTimeOffset|The date and time the app was created. This property is read-only. Inherited from mobileApp|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified. This property is read-only. Inherited from mobileApp|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin. Inherited from mobileApp|
|privacyInformationUrl|String|The privacy statement Url. Inherited from mobileApp|
|informationUrl|String|The more information Url. Inherited from mobileApp|
|owner|String|The owner of the app. Inherited from mobileApp|
|developer|String|The developer of the app. Inherited from mobileApp|
|notes|String|Notes for the app. Inherited from mobileApp|
|uploadState|Int32|The upload state. Possible values are: 0 - `Not Ready`, 1 - `Ready`, 2 - `Processing`. This property is read-only. Inherited from mobileApp|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. This property is read-only. Inherited from mobileApp. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group. This property is read-only. Inherited from mobileApp|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app. Inherited from mobileApp|
|dependentAppCount|Int32|The total number of dependencies the child app has. This property is read-only. Inherited from mobileApp|
|supersedingAppCount|Int32|The total number of apps this app directly or indirectly supersedes. This property is read-only. Inherited from mobileApp|
|supersededAppCount|Int32|The total number of apps this app is directly or indirectly superseded by. This property is read-only. Inherited from mobileApp|
|manifestHash|String|Hash of package metadata properties used to validate that the application matches the metadata in the source repository.|
|packageIdentifier|String|The PackageIdentifier from the WinGet source repository REST API. This also maps to the Id when using the WinGet client command line application. Required at creation time, cannot be modified on existing objects.|
|installExperience|winGetAppInstallExperience|The install experience settings associated with this application, which are used to ensure the desired install experiences on the target device are taken into account. This includes the account type (System or User) that actions should be run as on target devices. Required at creation time.|
### [auditEvent ](https://docs.microsoft.com/graph/api/resources/intune-auditing-auditevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|displayName|String|Event display name.|
|componentName|String|Component name.|
|actor|auditActor|AAD user and application that are associated with the audit event.|
|activity|String|Friendly name of the activity.|
|activityDateTime|DateTimeOffset|The date time in UTC when the activity was performed.|
|activityType|String|The type of activity that was being performed.|
|activityOperationType|String|The HTTP operation type of the activity.|
|activityResult|String|The result of the activity.|
|correlationId|Guid|The client request Id that is used to correlate activity within the system.|
|resources|auditResource collection|Resources being modified.|
|category|String|Audit category.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-auditing-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-books-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [deviceInstallState ](https://docs.microsoft.com/graph/api/resources/intune-books-deviceinstallstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|deviceName|String|Device name.|
|deviceId|String|Device Id.|
|lastSyncDateTime|DateTimeOffset|Last sync date and time.|
|installState|installState|The install state of the eBook. Possible values are: `notApplicable`, `installed`, `failed`, `notInstalled`, `uninstallFailed`, `unknown`.|
|errorCode|String|The error code for install failures.|
|osVersion|String|OS Version.|
|osDescription|String|OS Description.|
|userName|String|Device User Name.|
### [eBookInstallSummary ](https://docs.microsoft.com/graph/api/resources/intune-books-ebookinstallsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|installedDeviceCount|Int32|Number of Devices that have successfully installed this book.|
|failedDeviceCount|Int32|Number of Devices that have failed to install this book.|
|notInstalledDeviceCount|Int32|Number of Devices that does not have this book installed.|
|installedUserCount|Int32|Number of Users whose devices have all succeeded to install this book.|
|failedUserCount|Int32|Number of Users that have 1 or more device that failed to install this book.|
|notInstalledUserCount|Int32|Number of Users that did not install this book.|
### [iosVppEBook ](https://docs.microsoft.com/graph/api/resources/intune-books-iosvppebook?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedEBook|
|displayName|String|Name of the eBook. Inherited from managedEBook|
|description|String|Description. Inherited from managedEBook|
|publisher|String|Publisher. Inherited from managedEBook|
|publishedDateTime|DateTimeOffset|The date and time when the eBook was published. Inherited from managedEBook|
|largeCover|mimeContent|Book cover. Inherited from managedEBook|
|createdDateTime|DateTimeOffset|The date and time when the eBook file was created. Inherited from managedEBook|
|lastModifiedDateTime|DateTimeOffset|The date and time when the eBook was last modified. Inherited from managedEBook|
|informationUrl|String|The more information Url. Inherited from managedEBook|
|privacyInformationUrl|String|The privacy statement Url. Inherited from managedEBook|
|vppTokenId|Guid|The Vpp token ID.|
|appleId|String|The Apple ID associated with Vpp token.|
|vppOrganizationName|String|The Vpp token's organization name.|
|genres|String collection|Genres.|
|language|String|Language.|
|seller|String|Seller.|
|totalLicenseCount|Int32|Total license count.|
|usedLicenseCount|Int32|Used license count.|
### [iosVppEBookAssignment ](https://docs.microsoft.com/graph/api/resources/intune-books-iosvppebookassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedEBookAssignment|
|target|deviceAndAppManagementAssignmentTarget|The assignment target for eBook. Inherited from managedEBookAssignment|
|installIntent|installIntent|The install intent for eBook. Inherited from managedEBookAssignment. Possible values are: `available`, `required`, `uninstall`, `availableWithoutEnrollment`.|
### [managedEBook ](https://docs.microsoft.com/graph/api/resources/intune-books-managedebook?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|displayName|String|Name of the eBook.|
|description|String|Description.|
|publisher|String|Publisher.|
|publishedDateTime|DateTimeOffset|The date and time when the eBook was published.|
|largeCover|mimeContent|Book cover.|
|createdDateTime|DateTimeOffset|The date and time when the eBook file was created.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the eBook was last modified.|
|informationUrl|String|The more information Url.|
|privacyInformationUrl|String|The privacy statement Url.|
### [managedEBookAssignment ](https://docs.microsoft.com/graph/api/resources/intune-books-managedebookassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|target|deviceAndAppManagementAssignmentTarget|The assignment target for eBook.|
|installIntent|installIntent|The install intent for eBook. Possible values are: `available`, `required`, `uninstall`, `availableWithoutEnrollment`.|
### [managedEBookCategory ](https://docs.microsoft.com/graph/api/resources/intune-books-managedebookcategory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key of the entity.|
|displayName|String|The name of the eBook category.|
|lastModifiedDateTime|DateTimeOffset|The date and time the ManagedEBookCategory was last modified.|
### [userInstallStateSummary ](https://docs.microsoft.com/graph/api/resources/intune-books-userinstallstatesummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|userName|String|User name.|
|installedDeviceCount|Int32|Installed Device Count.|
|failedDeviceCount|Int32|Failed Device Count.|
|notInstalledDeviceCount|Int32|Not installed device count.|
### [androidManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-androidmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. Inherited from managedAppProtection|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet. Inherited from managedAppProtection|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use. Inherited from managedAppProtection|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Inherited from managedAppProtection. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked. Inherited from managedAppProtection|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required. Inherited from managedAppProtection|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android) Inherited from managedAppProtection|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files. Inherited from managedAppProtection|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. Inherited from managedAppProtection|
|pinRequired|Boolean|Indicates whether an app-level pin is required. Inherited from managedAppProtection|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped. Inherited from managedAppProtection|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked. Inherited from managedAppProtection|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True Inherited from managedAppProtection|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Inherited from managedAppProtection. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True. Inherited from managedAppProtection|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data. Inherited from managedAppProtection|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device. Inherited from managedAppProtection|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps. Inherited from managedAppProtection|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True. Inherited from managedAppProtection|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set. Inherited from managedAppProtection|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. Inherited from managedAppProtection|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app. Inherited from managedAppProtection|
|managedBrowser|managedBrowserType|Indicates in which managed browser(s) that internet links should be opened. When this property is configured, ManagedBrowserToOpenLinksRequired should be true. Inherited from managedAppProtection. Possible values are: `notConfigured`, `microsoftEdge`.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from targetedManagedAppProtection|
|screenCaptureBlocked|Boolean|Indicates whether a managed user can take screen captures of managed apps|
|disableAppEncryptionIfDeviceEncryptionIsEnabled|Boolean|When this setting is enabled, app level encryption is disabled if device level encryption is enabled|
|encryptAppData|Boolean|Indicates whether application data for managed apps should be encrypted|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|minimumRequiredPatchVersion|String|Define the oldest required Android security patch level a user can have to gain secure access to the app.|
|minimumWarningPatchVersion|String|Define the oldest recommended Android security patch level a user can have for secure access to the app.|
|customBrowserPackageId|String|Unique identifier of the preferred custom browser to open weblink on Android. When this property is configured, ManagedBrowserToOpenLinksRequired should be true.|
|customBrowserDisplayName|String|Friendly name of the preferred custom browser to open weblink on Android. When this property is configured, ManagedBrowserToOpenLinksRequired should be true.|
### [androidManagedAppRegistration ](https://docs.microsoft.com/graph/api/resources/intune-mam-androidmanagedappregistration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of creation Inherited from managedAppRegistration|
|lastSyncDateTime|DateTimeOffset|Date and time of last the app synced with management service. Inherited from managedAppRegistration|
|applicationVersion|String|App version Inherited from managedAppRegistration|
|managementSdkVersion|String|App management SDK version Inherited from managedAppRegistration|
|platformVersion|String|Operating System version Inherited from managedAppRegistration|
|deviceType|String|Host device type Inherited from managedAppRegistration|
|deviceTag|String|App management SDK generated tag, which helps relate apps hosted on the same device. Not guaranteed to relate apps in all conditions. Inherited from managedAppRegistration|
|deviceName|String|Host device name Inherited from managedAppRegistration|
|flaggedReasons|managedAppFlaggedReason collection|Zero or more reasons an app registration is flagged. E.g. app running on rooted device Inherited from managedAppRegistration|
|userId|String|The user Id to who this app registration belongs. Inherited from managedAppRegistration|
|appIdentifier|mobileAppIdentifier|The app package Identifier Inherited from managedAppRegistration|
|id|String|Key of the entity. Inherited from managedAppRegistration|
|version|String|Version of the entity. Inherited from managedAppRegistration|
### [defaultManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-defaultmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. Inherited from managedAppProtection|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet. Inherited from managedAppProtection|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use. Inherited from managedAppProtection|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Inherited from managedAppProtection. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked. Inherited from managedAppProtection|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required. Inherited from managedAppProtection|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android) Inherited from managedAppProtection|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files. Inherited from managedAppProtection|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. Inherited from managedAppProtection|
|pinRequired|Boolean|Indicates whether an app-level pin is required. Inherited from managedAppProtection|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped. Inherited from managedAppProtection|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked. Inherited from managedAppProtection|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True Inherited from managedAppProtection|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Inherited from managedAppProtection. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True. Inherited from managedAppProtection|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data. Inherited from managedAppProtection|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device. Inherited from managedAppProtection|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps. Inherited from managedAppProtection|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True. Inherited from managedAppProtection|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set. Inherited from managedAppProtection|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. Inherited from managedAppProtection|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app. Inherited from managedAppProtection|
|managedBrowser|managedBrowserType|Indicates in which managed browser(s) that internet links should be opened. When this property is configured, ManagedBrowserToOpenLinksRequired should be true. Inherited from managedAppProtection. Possible values are: `notConfigured`, `microsoftEdge`.|
|appDataEncryptionType|managedAppDataEncryptionType|Type of encryption which should be used for data in a managed app. (iOS Only). Possible values are: `useDeviceSettings`, `afterDeviceRestart`, `whenDeviceLockedExceptOpenFiles`, `whenDeviceLocked`.|
|screenCaptureBlocked|Boolean|Indicates whether screen capture is blocked. (Android only)|
|encryptAppData|Boolean|Indicates whether managed-app data should be encrypted. (Android only)|
|disableAppEncryptionIfDeviceEncryptionIsEnabled|Boolean|When this setting is enabled, app level encryption is disabled if device level encryption is enabled. (Android only)|
|minimumRequiredSdkVersion|String|Versions less than the specified version will block the managed app from accessing company data. (iOS Only)|
|customSettings|keyValuePair collection|A set of string key and string value pairs to be sent to the affected users, unalterned by this service|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|minimumRequiredPatchVersion|String|Define the oldest required Android security patch level a user can have to gain secure access to the app. (Android only)|
|minimumWarningPatchVersion|String|Define the oldest recommended Android security patch level a user can have for secure access to the app. (Android only)|
|faceIdBlocked|Boolean|Indicates whether use of the FaceID is allowed in place of a pin if PinRequired is set to True. (iOS Only)|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-mam-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [deviceManagementConfigurationChoiceSettingCollectionDefinition ](https://docs.microsoft.com/graph/api/resources/intune-mam-devicemanagementconfigurationchoicesettingcollectiondefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|options|deviceManagementConfigurationOptionDefinition collection|Options for the setting that can be selected Inherited from deviceManagementConfigurationChoiceSettingDefinition|
|defaultOptionId|String|Default option for choice setting Inherited from deviceManagementConfigurationChoiceSettingDefinition|
|maximumCount|Int32|Maximum number of choices in the collection|
|minimumCount|Int32|Minimum number of choices in the collection|
### [deviceManagementConfigurationSetting ](https://docs.microsoft.com/graph/api/resources/intune-mam-devicemanagementconfigurationsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
### [deviceManagementConfigurationSettingGroupCollectionDefinition ](https://docs.microsoft.com/graph/api/resources/intune-mam-devicemanagementconfigurationsettinggroupcollectiondefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|childIds|String collection|Dependent child settings to this group of settings Inherited from deviceManagementConfigurationSettingGroupDefinition|
|dependentOn|deviceManagementConfigurationDependentOn collection|List of Dependencies for the setting group Inherited from deviceManagementConfigurationSettingGroupDefinition|
|dependedOnBy|deviceManagementConfigurationSettingDependedOnBy collection|List of child settings that depend on this setting Inherited from deviceManagementConfigurationSettingGroupDefinition|
|maximumCount|Int32|Maximum number of setting group count in the collection|
|minimumCount|Int32|Minimum number of setting group count in the collection|
### [deviceManagementConfigurationSimpleSettingCollectionDefinition ](https://docs.microsoft.com/graph/api/resources/intune-mam-devicemanagementconfigurationsimplesettingcollectiondefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|valueDefinition|deviceManagementConfigurationSettingValueDefinition|Definition of the value for this setting Inherited from deviceManagementConfigurationSimpleSettingDefinition|
|defaultValue|deviceManagementConfigurationSettingValue|Default setting value for this setting Inherited from deviceManagementConfigurationSimpleSettingDefinition|
|dependentOn|deviceManagementConfigurationDependentOn collection|list of parent settings this setting is dependent on Inherited from deviceManagementConfigurationSimpleSettingDefinition|
|dependedOnBy|deviceManagementConfigurationSettingDependedOnBy collection|list of child settings that depend on this setting Inherited from deviceManagementConfigurationSimpleSettingDefinition|
|maximumCount|Int32|Maximum number of simple settings in the collection|
|minimumCount|Int32|Minimum number of simple settings in the collection|
### [deviceManagementReports ](https://docs.microsoft.com/graph/api/resources/intune-mam-devicemanagementreports?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
### [iosManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-iosmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. Inherited from managedAppProtection|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet. Inherited from managedAppProtection|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use. Inherited from managedAppProtection|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Inherited from managedAppProtection. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked. Inherited from managedAppProtection|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required. Inherited from managedAppProtection|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android) Inherited from managedAppProtection|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files. Inherited from managedAppProtection|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. Inherited from managedAppProtection|
|pinRequired|Boolean|Indicates whether an app-level pin is required. Inherited from managedAppProtection|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped. Inherited from managedAppProtection|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked. Inherited from managedAppProtection|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True Inherited from managedAppProtection|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Inherited from managedAppProtection. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True. Inherited from managedAppProtection|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data. Inherited from managedAppProtection|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device. Inherited from managedAppProtection|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps. Inherited from managedAppProtection|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True. Inherited from managedAppProtection|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set. Inherited from managedAppProtection|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. Inherited from managedAppProtection|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app. Inherited from managedAppProtection|
|managedBrowser|managedBrowserType|Indicates in which managed browser(s) that internet links should be opened. When this property is configured, ManagedBrowserToOpenLinksRequired should be true. Inherited from managedAppProtection. Possible values are: `notConfigured`, `microsoftEdge`.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from targetedManagedAppProtection|
|appDataEncryptionType|managedAppDataEncryptionType|Type of encryption which should be used for data in a managed app. Possible values are: `useDeviceSettings`, `afterDeviceRestart`, `whenDeviceLockedExceptOpenFiles`, `whenDeviceLocked`.|
|minimumRequiredSdkVersion|String|Versions less than the specified version will block the managed app from accessing company data.|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|faceIdBlocked|Boolean|Indicates whether use of the FaceID is allowed in place of a pin if PinRequired is set to True.|
|customBrowserProtocol|String|A custom browser protocol to open weblink on iOS. When this property is configured, ManagedBrowserToOpenLinksRequired should be true.|
### [iosManagedAppRegistration ](https://docs.microsoft.com/graph/api/resources/intune-mam-iosmanagedappregistration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of creation Inherited from managedAppRegistration|
|lastSyncDateTime|DateTimeOffset|Date and time of last the app synced with management service. Inherited from managedAppRegistration|
|applicationVersion|String|App version Inherited from managedAppRegistration|
|managementSdkVersion|String|App management SDK version Inherited from managedAppRegistration|
|platformVersion|String|Operating System version Inherited from managedAppRegistration|
|deviceType|String|Host device type Inherited from managedAppRegistration|
|deviceTag|String|App management SDK generated tag, which helps relate apps hosted on the same device. Not guaranteed to relate apps in all conditions. Inherited from managedAppRegistration|
|deviceName|String|Host device name Inherited from managedAppRegistration|
|flaggedReasons|managedAppFlaggedReason collection|Zero or more reasons an app registration is flagged. E.g. app running on rooted device Inherited from managedAppRegistration|
|userId|String|The user Id to who this app registration belongs. Inherited from managedAppRegistration|
|appIdentifier|mobileAppIdentifier|The app package Identifier Inherited from managedAppRegistration|
|id|String|Key of the entity. Inherited from managedAppRegistration|
|version|String|Version of the entity. Inherited from managedAppRegistration|
### [managedAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|customSettings|keyValuePair collection|A set of string key and string value pairs to be sent to apps for users to whom the configuration is scoped, unalterned by this service|
### [managedAppDiagnosticStatus ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappdiagnosticstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|validationName|String|The validation friendly name|
|state|String|The state of the operation|
|mitigationInstruction|String|Instruction on how to mitigate a failed validation|
### [managedAppLogCollectionRequest ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedapplogcollectionrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the managed app log collection request. This id is assigned during request creation time. Read-only.|
|managedAppRegistrationId|String|The unique identifier of the app instance for which diagnostic logs were collected. Read-only.|
|status|String|Indicates the status for the app log collection request - pending, completed or failed. Default is pending.|
|requestedBy|String|The user principal name associated with the request for the managed application log collection. Read-only.|
|requestedByUserPrincipalName|String|The user principal name associated with the request for the managed application log collection. Read-only.|
|requestedDateTime|DateTimeOffset|DateTime of when the log upload request was received. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only.|
|completedDateTime|DateTimeOffset|DateTime of when the log upload request was completed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default. Read-only.|
|userLogUploadConsent|managedAppLogUploadConsent|Indicates whether the user associated with the device provided consent for the log collection. The user must consent before the diagnostic logs can be collected. accepted means the user consented. declined means the user declined. unknown is the default value. The Log Collection Request must be completed within 24 hours or it will be abandoned and deleted. Read-only. Possible values are: `unknown`, `declined`, `accepted`, `unknownFutureValue`.|
|uploadedLogs|managedAppLogUpload collection|The collection of log upload results as reported by each component on the device. Such components can be the application itself, the Mobile Application Management (MAM) SDK, and other on-device components that are requested to upload diagnostic logs. Read-only.|
|version|String|Version of the entity.|
### [managedAppOperation ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The operation name.|
|lastModifiedDateTime|DateTimeOffset|The last time the app operation was modified.|
|state|String|The current state of the operation|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [managedAppPolicy ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedapppolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name.|
|description|String|The policy's description.|
|createdDateTime|DateTimeOffset|The date and time the policy was created.|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified.|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [managedAppPolicyDeploymentSummary ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedapppolicydeploymentsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Not yet documented|
|configurationDeployedUserCount|Int32|Not yet documented|
|lastRefreshTime|DateTimeOffset|Not yet documented|
|configurationDeploymentSummaryPerApp|managedAppPolicyDeploymentSummaryPerApp collection|Not yet documented|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [managedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet.|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet.|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use.|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked.|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required.|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android)|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files.|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped.|
|pinRequired|Boolean|Indicates whether an app-level pin is required.|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped.|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked.|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True.|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data.|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device.|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps.|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True.|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set.|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data.|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data.|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data.|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app.|
|managedBrowser|managedBrowserType|Indicates in which managed browser(s) that internet links should be opened. When this property is configured, ManagedBrowserToOpenLinksRequired should be true. Possible values are: `notConfigured`, `microsoftEdge`.|
### [managedAppRegistration ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappregistration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of creation|
|lastSyncDateTime|DateTimeOffset|Date and time of last the app synced with management service.|
|applicationVersion|String|App version|
|managementSdkVersion|String|App management SDK version|
|platformVersion|String|Operating System version|
|deviceType|String|Host device type|
|deviceTag|String|App management SDK generated tag, which helps relate apps hosted on the same device. Not guaranteed to relate apps in all conditions.|
|deviceName|String|Host device name|
|flaggedReasons|managedAppFlaggedReason collection|Zero or more reasons an app registration is flagged. E.g. app running on rooted device|
|userId|String|The user Id to who this app registration belongs.|
|appIdentifier|mobileAppIdentifier|The app package Identifier|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [managedAppStatus ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Friendly name of the status report.|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [managedAppStatusRaw ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedappstatusraw?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Friendly name of the status report. Inherited from managedAppStatus|
|id|String|Key of the entity. Inherited from managedAppStatus|
|version|String|Version of the entity. Inherited from managedAppStatus|
|content|Json|Status report content.|
### [managedMobileApp ](https://docs.microsoft.com/graph/api/resources/intune-mam-managedmobileapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|mobileAppIdentifier|mobileAppIdentifier|The identifier for an app with it's operating system type.|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [mdmWindowsInformationProtectionPolicy ](https://docs.microsoft.com/graph/api/resources/intune-mam-mdmwindowsinformationprotectionpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|enforcementLevel|windowsInformationProtectionEnforcementLevel|WIP enforcement level.See the Enum definition for supported values Inherited from windowsInformationProtection. Possible values are: `noProtection`, `encryptAndAuditOnly`, `encryptAuditAndPrompt`, `encryptAuditAndBlock`.|
|enterpriseDomain|String|Primary enterprise domain Inherited from windowsInformationProtection|
|enterpriseProtectedDomainNames|windowsInformationProtectionResourceCollection collection|List of enterprise domains to be protected Inherited from windowsInformationProtection|
|protectionUnderLockConfigRequired|Boolean|Specifies whether the protection under lock feature (also known as encrypt under pin) should be configured Inherited from windowsInformationProtection|
|dataRecoveryCertificate|windowsInformationProtectionDataRecoveryCertificate|Specifies a recovery certificate that can be used for data recovery of encrypted files. This is the same as the data recovery agent(DRA) certificate for encrypting file system(EFS) Inherited from windowsInformationProtection|
|revokeOnUnenrollDisabled|Boolean|This policy controls whether to revoke the WIP keys when a device unenrolls from the management service. If set to 1 (Don't revoke keys), the keys will not be revoked and the user will continue to have access to protected files after unenrollment. If the keys are not revoked, there will be no revoked file cleanup subsequently. Inherited from windowsInformationProtection|
|rightsManagementServicesTemplateId|Guid|TemplateID GUID to use for RMS encryption. The RMS template allows the IT admin to configure the details about who has access to RMS-protected file and how long they have access Inherited from windowsInformationProtection|
|azureRightsManagementServicesAllowed|Boolean|Specifies whether to allow Azure RMS encryption for WIP Inherited from windowsInformationProtection|
|iconsVisible|Boolean|Determines whether overlays are added to icons for WIP protected files in Explorer and enterprise only app tiles in the Start menu. Starting in Windows 10, version 1703 this setting also configures the visibility of the WIP icon in the title bar of a WIP-protected app Inherited from windowsInformationProtection|
|protectedApps|windowsInformationProtectionApp collection|Protected applications can access enterprise data and the data handled by those applications are protected with encryption Inherited from windowsInformationProtection|
|exemptApps|windowsInformationProtectionApp collection|Exempt applications can also access enterprise data, but the data handled by those applications are not protected. This is because some critical enterprise applications may have compatibility problems with encrypted data. Inherited from windowsInformationProtection|
|enterpriseNetworkDomainNames|windowsInformationProtectionResourceCollection collection|This is the list of domains that comprise the boundaries of the enterprise. Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to Inherited from windowsInformationProtection|
|enterpriseProxiedDomains|windowsInformationProtectionProxiedDomainCollection collection|Contains a list of Enterprise resource domains hosted in the cloud that need to be protected. Connections to these resources are considered enterprise data. If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80). A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy Inherited from windowsInformationProtection|
|enterpriseIPRanges|windowsInformationProtectionIPRangeCollection collection|Sets the enterprise IP ranges that define the computers in the enterprise network. Data that comes from those computers will be considered part of the enterprise and protected. These locations will be considered a safe destination for enterprise data to be shared to Inherited from windowsInformationProtection|
|enterpriseIPRangesAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list and not to use heuristics to attempt to find other subnets. Default is false Inherited from windowsInformationProtection|
|enterpriseProxyServers|windowsInformationProtectionResourceCollection collection|This is a list of proxy servers. Any server not on this list is considered non-enterprise Inherited from windowsInformationProtection|
|enterpriseInternalProxyServers|windowsInformationProtectionResourceCollection collection|This is the comma-separated list of internal proxy servers. For example, "157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59". These proxies have been configured by the admin to connect to specific resources on the Internet. They are considered to be enterprise network locations. The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies Inherited from windowsInformationProtection|
|enterpriseProxyServersAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list of proxies and not try to detect other work proxies. Default is false Inherited from windowsInformationProtection|
|neutralDomainResources|windowsInformationProtectionResourceCollection collection|List of domain names that can used for work or personal resource Inherited from windowsInformationProtection|
|indexingEncryptedStoresOrItemsBlocked|Boolean|This switch is for the Windows Search Indexer, to allow or disallow indexing of items Inherited from windowsInformationProtection|
|smbAutoEncryptedFileExtensions|windowsInformationProtectionResourceCollection collection|Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary Inherited from windowsInformationProtection|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from windowsInformationProtection|
### [targetedManagedAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-mam-targetedmanagedappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|customSettings|keyValuePair collection|A set of string key and string value pairs to be sent to apps for users to whom the configuration is scoped, unalterned by this service Inherited from managedAppConfiguration|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not.|
### [targetedManagedAppPolicyAssignment ](https://docs.microsoft.com/graph/api/resources/intune-mam-targetedmanagedapppolicyassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Id|
|target|deviceAndAppManagementAssignmentTarget|Identifier for deployment to a group or app|
### [targetedManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-targetedmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. Inherited from managedAppProtection|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet. Inherited from managedAppProtection|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use. Inherited from managedAppProtection|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Inherited from managedAppProtection. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked. Inherited from managedAppProtection|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required. Inherited from managedAppProtection|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android) Inherited from managedAppProtection|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files. Inherited from managedAppProtection|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. Inherited from managedAppProtection|
|pinRequired|Boolean|Indicates whether an app-level pin is required. Inherited from managedAppProtection|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped. Inherited from managedAppProtection|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked. Inherited from managedAppProtection|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True Inherited from managedAppProtection|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Inherited from managedAppProtection. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True. Inherited from managedAppProtection|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data. Inherited from managedAppProtection|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device. Inherited from managedAppProtection|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps. Inherited from managedAppProtection|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True. Inherited from managedAppProtection|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set. Inherited from managedAppProtection|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. Inherited from managedAppProtection|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app. Inherited from managedAppProtection|
|managedBrowser|managedBrowserType|Indicates in which managed browser(s) that internet links should be opened. When this property is configured, ManagedBrowserToOpenLinksRequired should be true. Inherited from managedAppProtection. Possible values are: `notConfigured`, `microsoftEdge`.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not.|
### [user ](https://docs.microsoft.com/graph/api/resources/intune-mam-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The user identifier.|
### [windowsInformationProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsinformationprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|enforcementLevel|windowsInformationProtectionEnforcementLevel|WIP enforcement level.See the Enum definition for supported values. Possible values are: `noProtection`, `encryptAndAuditOnly`, `encryptAuditAndPrompt`, `encryptAuditAndBlock`.|
|enterpriseDomain|String|Primary enterprise domain|
|enterpriseProtectedDomainNames|windowsInformationProtectionResourceCollection collection|List of enterprise domains to be protected|
|protectionUnderLockConfigRequired|Boolean|Specifies whether the protection under lock feature (also known as encrypt under pin) should be configured|
|dataRecoveryCertificate|windowsInformationProtectionDataRecoveryCertificate|Specifies a recovery certificate that can be used for data recovery of encrypted files. This is the same as the data recovery agent(DRA) certificate for encrypting file system(EFS)|
|revokeOnUnenrollDisabled|Boolean|This policy controls whether to revoke the WIP keys when a device unenrolls from the management service. If set to 1 (Don't revoke keys), the keys will not be revoked and the user will continue to have access to protected files after unenrollment. If the keys are not revoked, there will be no revoked file cleanup subsequently.|
|rightsManagementServicesTemplateId|Guid|TemplateID GUID to use for RMS encryption. The RMS template allows the IT admin to configure the details about who has access to RMS-protected file and how long they have access|
|azureRightsManagementServicesAllowed|Boolean|Specifies whether to allow Azure RMS encryption for WIP|
|iconsVisible|Boolean|Determines whether overlays are added to icons for WIP protected files in Explorer and enterprise only app tiles in the Start menu. Starting in Windows 10, version 1703 this setting also configures the visibility of the WIP icon in the title bar of a WIP-protected app|
|protectedApps|windowsInformationProtectionApp collection|Protected applications can access enterprise data and the data handled by those applications are protected with encryption|
|exemptApps|windowsInformationProtectionApp collection|Exempt applications can also access enterprise data, but the data handled by those applications are not protected. This is because some critical enterprise applications may have compatibility problems with encrypted data.|
|enterpriseNetworkDomainNames|windowsInformationProtectionResourceCollection collection|This is the list of domains that comprise the boundaries of the enterprise. Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to|
|enterpriseProxiedDomains|windowsInformationProtectionProxiedDomainCollection collection|Contains a list of Enterprise resource domains hosted in the cloud that need to be protected. Connections to these resources are considered enterprise data. If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80). A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy|
|enterpriseIPRanges|windowsInformationProtectionIPRangeCollection collection|Sets the enterprise IP ranges that define the computers in the enterprise network. Data that comes from those computers will be considered part of the enterprise and protected. These locations will be considered a safe destination for enterprise data to be shared to|
|enterpriseIPRangesAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list and not to use heuristics to attempt to find other subnets. Default is false|
|enterpriseProxyServers|windowsInformationProtectionResourceCollection collection|This is a list of proxy servers. Any server not on this list is considered non-enterprise|
|enterpriseInternalProxyServers|windowsInformationProtectionResourceCollection collection|This is the comma-separated list of internal proxy servers. For example, "157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59". These proxies have been configured by the admin to connect to specific resources on the Internet. They are considered to be enterprise network locations. The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies|
|enterpriseProxyServersAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list of proxies and not try to detect other work proxies. Default is false|
|neutralDomainResources|windowsInformationProtectionResourceCollection collection|List of domain names that can used for work or personal resource|
|indexingEncryptedStoresOrItemsBlocked|Boolean|This switch is for the Windows Search Indexer, to allow or disallow indexing of items|
|smbAutoEncryptedFileExtensions|windowsInformationProtectionResourceCollection collection|Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not.|
### [windowsInformationProtectionAppLockerFile ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsinformationprotectionapplockerfile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The friendly name|
|fileHash|String|SHA256 hash of the file|
|file|Binary|File as a byte array|
|id|String|Key of the entity.|
|version|String|Version of the entity.|
### [windowsInformationProtectionDeviceRegistration ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsinformationprotectiondeviceregistration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|userId|String|UserId associated with this device registration record.|
|deviceRegistrationId|String|Device identifier for this device registration record.|
|deviceName|String|Device name.|
|deviceType|String|Device type, for example, Windows laptop VS Windows phone.|
|deviceMacAddress|String|Device Mac address.|
|lastCheckInDateTime|DateTimeOffset|Last checkin time of the device.|
### [windowsInformationProtectionPolicy ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsinformationprotectionpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|enforcementLevel|windowsInformationProtectionEnforcementLevel|WIP enforcement level.See the Enum definition for supported values Inherited from windowsInformationProtection. Possible values are: `noProtection`, `encryptAndAuditOnly`, `encryptAuditAndPrompt`, `encryptAuditAndBlock`.|
|enterpriseDomain|String|Primary enterprise domain Inherited from windowsInformationProtection|
|enterpriseProtectedDomainNames|windowsInformationProtectionResourceCollection collection|List of enterprise domains to be protected Inherited from windowsInformationProtection|
|protectionUnderLockConfigRequired|Boolean|Specifies whether the protection under lock feature (also known as encrypt under pin) should be configured Inherited from windowsInformationProtection|
|dataRecoveryCertificate|windowsInformationProtectionDataRecoveryCertificate|Specifies a recovery certificate that can be used for data recovery of encrypted files. This is the same as the data recovery agent(DRA) certificate for encrypting file system(EFS) Inherited from windowsInformationProtection|
|revokeOnUnenrollDisabled|Boolean|This policy controls whether to revoke the WIP keys when a device unenrolls from the management service. If set to 1 (Don't revoke keys), the keys will not be revoked and the user will continue to have access to protected files after unenrollment. If the keys are not revoked, there will be no revoked file cleanup subsequently. Inherited from windowsInformationProtection|
|rightsManagementServicesTemplateId|Guid|TemplateID GUID to use for RMS encryption. The RMS template allows the IT admin to configure the details about who has access to RMS-protected file and how long they have access Inherited from windowsInformationProtection|
|azureRightsManagementServicesAllowed|Boolean|Specifies whether to allow Azure RMS encryption for WIP Inherited from windowsInformationProtection|
|iconsVisible|Boolean|Determines whether overlays are added to icons for WIP protected files in Explorer and enterprise only app tiles in the Start menu. Starting in Windows 10, version 1703 this setting also configures the visibility of the WIP icon in the title bar of a WIP-protected app Inherited from windowsInformationProtection|
|protectedApps|windowsInformationProtectionApp collection|Protected applications can access enterprise data and the data handled by those applications are protected with encryption Inherited from windowsInformationProtection|
|exemptApps|windowsInformationProtectionApp collection|Exempt applications can also access enterprise data, but the data handled by those applications are not protected. This is because some critical enterprise applications may have compatibility problems with encrypted data. Inherited from windowsInformationProtection|
|enterpriseNetworkDomainNames|windowsInformationProtectionResourceCollection collection|This is the list of domains that comprise the boundaries of the enterprise. Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to Inherited from windowsInformationProtection|
|enterpriseProxiedDomains|windowsInformationProtectionProxiedDomainCollection collection|Contains a list of Enterprise resource domains hosted in the cloud that need to be protected. Connections to these resources are considered enterprise data. If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80). A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy Inherited from windowsInformationProtection|
|enterpriseIPRanges|windowsInformationProtectionIPRangeCollection collection|Sets the enterprise IP ranges that define the computers in the enterprise network. Data that comes from those computers will be considered part of the enterprise and protected. These locations will be considered a safe destination for enterprise data to be shared to Inherited from windowsInformationProtection|
|enterpriseIPRangesAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list and not to use heuristics to attempt to find other subnets. Default is false Inherited from windowsInformationProtection|
|enterpriseProxyServers|windowsInformationProtectionResourceCollection collection|This is a list of proxy servers. Any server not on this list is considered non-enterprise Inherited from windowsInformationProtection|
|enterpriseInternalProxyServers|windowsInformationProtectionResourceCollection collection|This is the comma-separated list of internal proxy servers. For example, "157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59". These proxies have been configured by the admin to connect to specific resources on the Internet. They are considered to be enterprise network locations. The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies Inherited from windowsInformationProtection|
|enterpriseProxyServersAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list of proxies and not try to detect other work proxies. Default is false Inherited from windowsInformationProtection|
|neutralDomainResources|windowsInformationProtectionResourceCollection collection|List of domain names that can used for work or personal resource Inherited from windowsInformationProtection|
|indexingEncryptedStoresOrItemsBlocked|Boolean|This switch is for the Windows Search Indexer, to allow or disallow indexing of items Inherited from windowsInformationProtection|
|smbAutoEncryptedFileExtensions|windowsInformationProtectionResourceCollection collection|Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary Inherited from windowsInformationProtection|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from windowsInformationProtection|
|revokeOnMdmHandoffDisabled|Boolean|New property in RS2, pending documentation|
|mdmEnrollmentUrl|String|Enrollment url for the MDM|
|windowsHelloForBusinessBlocked|Boolean|Boolean value that sets Windows Hello for Business as a method for signing into Windows.|
|pinMinimumLength|Int32|Integer value that sets the minimum number of characters required for the PIN. Default value is 4. The lowest number you can configure for this policy setting is 4. The largest number you can configure must be less than the number configured in the Maximum PIN length policy setting or the number 127, whichever is the lowest.|
|pinUppercaseLetters|windowsInformationProtectionPinCharacterRequirements|Integer value that configures the use of uppercase letters in the Windows Hello for Business PIN. Default is NotAllow. Possible values are: `notAllow`, `requireAtLeastOne`, `allow`.|
|pinLowercaseLetters|windowsInformationProtectionPinCharacterRequirements|Integer value that configures the use of lowercase letters in the Windows Hello for Business PIN. Default is NotAllow. Possible values are: `notAllow`, `requireAtLeastOne`, `allow`.|
|pinSpecialCharacters|windowsInformationProtectionPinCharacterRequirements|Integer value that configures the use of special characters in the Windows Hello for Business PIN. Valid special characters for Windows Hello for Business PIN gestures include: ! " # $ % & ' ( ) * + , - . / : ; < = > ? @ \[ \ \] ^ _ ` { | } ~. Default is NotAllow. Possible values are: `notAllow`, `requireAtLeastOne`, `allow`.|
|pinExpirationDays|Int32|Integer value specifies the period of time (in days) that a PIN can be used before the system requires the user to change it. The largest number you can configure for this policy setting is 730. The lowest number you can configure for this policy setting is 0. If this policy is set to 0, then the user's PIN will never expire. This node was added in Windows 10, version 1511. Default is 0.|
|numberOfPastPinsRemembered|Int32|Integer value that specifies the number of past PINs that can be associated to a user account that can't be reused. The largest number you can configure for this policy setting is 50. The lowest number you can configure for this policy setting is 0. If this policy is set to 0, then storage of previous PINs is not required. This node was added in Windows 10, version 1511. Default is 0.|
|passwordMaximumAttemptCount|Int32|The number of authentication failures allowed before the device will be wiped. A value of 0 disables device wipe functionality. Range is an integer X where 4 <= X <= 16 for desktop and 0 <= X <= 999 for mobile devices.|
|minutesOfInactivityBeforeDeviceLock|Int32|Specifies the maximum amount of time (in minutes) allowed after the device is idle that will cause the device to become PIN or password locked.   Range is an integer X where 0 <= X <= 999.|
|daysWithoutContactBeforeUnenroll|Int32|Offline interval before app data is wiped (days) |
### [windowsInformationProtectionWipeAction ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsinformationprotectionwipeaction?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|status|actionState|Wipe action status. Possible values are: `none`, `pending`, `canceled`, `active`, `done`, `failed`, `notSupported`.|
|targetedUserId|String|The UserId being targeted by this wipe action.|
|targetedDeviceRegistrationId|String|The DeviceRegistrationId being targeted by this wipe action.|
|targetedDeviceName|String|Targeted device name.|
|targetedDeviceMacAddress|String|Targeted device Mac address.|
|lastCheckInDateTime|DateTimeOffset|Last checkin time of the device that was targeted by this wipe action.|
### [windowsManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from managedAppPolicy|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|isAssigned|Boolean|When TRUE, indicates that the policy is deployed to some inclusion groups. When FALSE, indicates that the policy is not deployed to any inclusion groups. Default value is FALSE.|
|deployedAppCount|Int32|Indicates the total number of applications for which the current policy is deployed.|
|printBlocked|Boolean|When TRUE, indicates that printing is blocked from managed apps. When FALSE, indicates that printing is allowed from managed apps. Default value is FALSE.|
|allowedInboundDataTransferSources|windowsManagedAppDataTransferLevel|Indicates the sources from which data is allowed to be transferred. Some possible values are allApps or none. Possible values are: `allApps`, `none`.|
|allowedOutboundClipboardSharingLevel|windowsManagedAppClipboardSharingLevel|Indicates the level to which the clipboard may be shared across org & non-org resources. Some possible values are anyDestinationAnySource or none. Possible values are: `anyDestinationAnySource`, `none`.|
|allowedOutboundDataTransferDestinations|windowsManagedAppDataTransferLevel|Indicates the destinations to which data is allowed to be transferred. Some possible values are allApps or none. Possible values are: `allApps`, `none`.|
|appActionIfUnableToAuthenticateUser|managedAppRemediationAction|If set, it will specify what action to take in the case where the user is unable to checkin because their authentication token is invalid. This happens when the user is deleted or disabled in AAD. Some possible values are block or wipe. If this property is not set, no action will be taken. Possible values are: `block`, `wipe`, `warn`.|
|maximumAllowedDeviceThreatLevel|managedAppDeviceThreatLevel|Maximum allowed device threat level, as reported by the Mobile Threat Defense app. Possible values are: `notConfigured`, `secured`, `low`, `medium`, `high`.|
|mobileThreatDefenseRemediationAction|managedAppRemediationAction|Determines what action to take if the mobile threat defense threat threshold isn't met. Some possible values are block or wipe. Warn isn't a supported value for this property. Possible values are: `block`, `wipe`, `warn`.|
|minimumRequiredSdkVersion|String|Versions less than the specified version will block the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|minimumWipeSdkVersion|String|Versions less than the specified version will wipe the managed app and the associated company data. For example: '8.1.0' or '13.1.1'.|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|minimumWipeOsVersion|String|Versions less than the specified version will wipe the managed app and the associated company data. For example: '8.1.0' or '13.1.1'.|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|minimumWipeAppVersion|String|Versions less than the specified version will wipe the managed app and the associated company data. For example: '8.1.0' or '13.1.1'.|
|maximumRequiredOsVersion|String|Versions bigger than the specified version will block the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|maximumWarningOsVersion|String|Versions bigger than the specified version will result in warning message on the managed app from accessing company data. For example: '8.1.0' or '13.1.1'.|
|maximumWipeOsVersion|String|Versions bigger than the specified version will wipe the managed app and the associated company data. For example: '8.1.0' or '13.1.1'.|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. For example, P5D indicates that the interval is 5 days in duration. A timespan value of PT0S indicates that managed data will never be wiped when the device is not connected to the internet.|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. For example, PT5M indicates that the interval is 5 minutes in duration. A timespan value of PT0S indicates that access will be blocked immediately when the device is not connected to the internet.|
### [windowsManagedAppRegistration ](https://docs.microsoft.com/graph/api/resources/intune-mam-windowsmanagedappregistration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date and time of creation Inherited from managedAppRegistration|
|lastSyncDateTime|DateTimeOffset|Date and time of last the app synced with management service. Inherited from managedAppRegistration|
|applicationVersion|String|App version Inherited from managedAppRegistration|
|managementSdkVersion|String|App management SDK version Inherited from managedAppRegistration|
|platformVersion|String|Operating System version Inherited from managedAppRegistration|
|deviceType|String|Host device type Inherited from managedAppRegistration|
|deviceTag|String|App management SDK generated tag, which helps relate apps hosted on the same device. Not guaranteed to relate apps in all conditions. Inherited from managedAppRegistration|
|deviceName|String|Host device name Inherited from managedAppRegistration|
|managedDeviceId|String|The Managed Device identifier of the host device. Value could be empty even when the host device is managed. Inherited from managedAppRegistration|
|azureADDeviceId|String|The Azure Active Directory Device identifier of the host device. Value could be empty even when the host device is Azure Active Directory registered. Inherited from managedAppRegistration|
|deviceModel|String|The device model for the current app registration  Inherited from managedAppRegistration|
|deviceManufacturer|String|The device manufacturer for the current app registration  Inherited from managedAppRegistration|
|flaggedReasons|managedAppFlaggedReason collection|Zero or more reasons an app registration is flagged. E.g. app running on rooted device Inherited from managedAppRegistration|
|userId|String|The user Id to who this app registration belongs. Inherited from managedAppRegistration|
|appIdentifier|mobileAppIdentifier|The app package Identifier Inherited from managedAppRegistration|
|id|String|Key of the entity. Inherited from managedAppRegistration|
|version|String|Version of the entity. Inherited from managedAppRegistration|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
|microsoftStoreForBusinessLastSuccessfulSyncDateTime|DateTimeOffset|The last time the apps from the Microsoft Store for Business were synced successfully for the account.|
|isEnabledForMicrosoftStoreForBusiness|Boolean|Whether the account is enabled for syncing applications from the Microsoft Store for Business.|
|microsoftStoreForBusinessLanguage|String|The locale information used to sync applications from the Microsoft Store for Business. Cultures that are specific to a country/region. The names of these cultures follow RFC 4646 (Windows Vista and later). The format is <languagecode2>-<country/regioncode2>, where <languagecode2> is a lowercase two-letter code derived from ISO 639-1 and <country/regioncode2> is an uppercase two-letter code derived from ISO 3166. For example, en-US for English (United States) is a specific culture.|
|microsoftStoreForBusinessLastCompletedApplicationSyncTime|DateTimeOffset|The last time an application sync from the Microsoft Store for Business was completed.|
### [appVulnerabilityManagedDevice ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-appvulnerabilitymanageddevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key, and AAD device ID.|
|managedDeviceId|String|The Intune managed device ID.|
|displayName|String|The device name.|
|lastSyncDateTime|DateTimeOffset|The created date.|
### [appVulnerabilityMobileApp ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-appvulnerabilitymobileapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key.|
|mobileAppId|String|The Intune mobile app ID.|
|displayName|String|The device name.|
|createdDateTime|DateTimeOffset|The created date.|
|lastModifiedDateTime|DateTimeOffset|The last modified date.|
|mobileAppType|String|The app type.|
|version|String|The app version.|
### [appVulnerabilityTask ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-appvulnerabilitytask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key. Inherited from deviceAppManagementTask|
|displayName|String|The name. Inherited from deviceAppManagementTask|
|description|String|The description. Inherited from deviceAppManagementTask|
|createdDateTime|DateTimeOffset|The created date. Inherited from deviceAppManagementTask|
|dueDateTime|DateTimeOffset|The due date. Inherited from deviceAppManagementTask|
|category|deviceAppManagementTaskCategory|The category. Inherited from deviceAppManagementTask. Possible values are: `unknown`, `advancedThreatProtection`.|
|priority|deviceAppManagementTaskPriority|The priority. Inherited from deviceAppManagementTask. Possible values are: `none`, `high`, `low`.|
|creator|String|The email address of the creator. Inherited from deviceAppManagementTask|
|creatorNotes|String|Notes from the creator. Inherited from deviceAppManagementTask|
|assignedTo|String|The name or email of the admin this task is assigned to. Inherited from deviceAppManagementTask|
|status|deviceAppManagementTaskStatus|The status. Inherited from deviceAppManagementTask. Possible values are: `unknown`, `pending`, `active`, `completed`, `rejected`.|
|appName|String|The app name.|
|appPublisher|String|The app publisher.|
|appVersion|String|The app version.|
|mitigationType|appVulnerabilityTaskMitigationType|The mitigation type. Possible values are: `unknown`, `update`, `uninstall`, `securityConfiguration`.|
|insights|String|Information about the mitigation.|
|managedDeviceCount|Int32|The number of vulnerable devices.|
|mobileAppCount|Int32|The number of vulnerable mobile apps.|
|remediation|String|The remediation steps.|
### [configManagerCollection ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-configmanagercollection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key for the ConfigManager Collection.|
|displayName|String|The DisplayName.|
|collectionIdentifier|String|The collection identifier in SCCM.|
|hierarchyName|String|The HierarchyName.|
|hierarchyIdentifier|String|The Hierarchy Identifier.|
|createdDateTime|DateTimeOffset|The created date.|
|lastModifiedDateTime|DateTimeOffset|The last modified date.|
### [configManagerPolicySummary ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-configmanagerpolicysummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|targetedDeviceCount|Int32|The number of devices targeted by the policy.|
|compliantDeviceCount|Int32|The number of devices evaluated to be compliant by the policy.|
|nonCompliantDeviceCount|Int32|The number of devices evaluated to be noncompliant by the policy.|
|failedDeviceCount|Int32|The number of devices that failed to be evaluated by the policy.|
|pendingDeviceCount|Int32|The number of devices that have acknowledged the policy but are pending evaluation.|
|enforcedDeviceCount|Int32|The number of devices that have have been remediated by the policy.|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [deviceAppManagementTask ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-deviceappmanagementtask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key.|
|displayName|String|The name.|
|description|String|The description.|
|createdDateTime|DateTimeOffset|The created date.|
|dueDateTime|DateTimeOffset|The due date.|
|category|deviceAppManagementTaskCategory|The category. Possible values are: `unknown`, `advancedThreatProtection`.|
|priority|deviceAppManagementTaskPriority|The priority. Possible values are: `none`, `high`, `low`.|
|creator|String|The email address of the creator.|
|creatorNotes|String|Notes from the creator.|
|assignedTo|String|The name or email of the admin this task is assigned to.|
|status|deviceAppManagementTaskStatus|The status. Possible values are: `unknown`, `pending`, `active`, `completed`, `rejected`.|
### [securityConfigurationTask ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-securityconfigurationtask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key. Inherited from deviceAppManagementTask|
|displayName|String|The name. Inherited from deviceAppManagementTask|
|description|String|The description. Inherited from deviceAppManagementTask|
|createdDateTime|DateTimeOffset|The created date. Inherited from deviceAppManagementTask|
|dueDateTime|DateTimeOffset|The due date. Inherited from deviceAppManagementTask|
|category|deviceAppManagementTaskCategory|The category. Inherited from deviceAppManagementTask. Possible values are: `unknown`, `advancedThreatProtection`.|
|priority|deviceAppManagementTaskPriority|The priority. Inherited from deviceAppManagementTask. Possible values are: `none`, `high`, `low`.|
|creator|String|The email address of the creator. Inherited from deviceAppManagementTask|
|creatorNotes|String|Notes from the creator. Inherited from deviceAppManagementTask|
|assignedTo|String|The name or email of the admin this task is assigned to. Inherited from deviceAppManagementTask|
|status|deviceAppManagementTaskStatus|The status. Inherited from deviceAppManagementTask. Possible values are: `unknown`, `pending`, `active`, `completed`, `rejected`.|
|endpointSecurityPolicy|endpointSecurityConfigurationType|The endpoint security policy type. Possible values are: `unknown`, `antivirus`, `diskEncryption`, `firewall`, `endpointDetectionAndResponse`, `attackSurfaceReduction`, `accountProtection`.|
|applicablePlatform|endpointSecurityConfigurationApplicablePlatform|The applicable platform. Possible values are: `unknown`, `macOS`, `windows10AndLater`, `windows10AndWindowsServer`.|
|endpointSecurityPolicyProfile|endpointSecurityConfigurationProfileType|The endpoint security policy profile. Possible values are: `unknown`, `antivirus`, `windowsSecurity`, `bitLocker`, `fileVault`, `firewall`, `firewallRules`, `endpointDetectionAndResponse`, `deviceControl`, `appAndBrowserIsolation`, `exploitProtection`, `webProtection`, `applicationControl`, `attackSurfaceReductionRules`, `accountProtection`.|
|insights|String|Information about the mitigation.|
|managedDeviceCount|Int32|The number of vulnerable devices. Valid values 0 to 65536|
|intendedSettings|keyValuePair collection|The intended settings and their values.|
### [unmanagedDeviceDiscoveryTask ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-unmanageddevicediscoverytask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key. Inherited from deviceAppManagementTask|
|displayName|String|The name. Inherited from deviceAppManagementTask|
|description|String|The description. Inherited from deviceAppManagementTask|
|createdDateTime|DateTimeOffset|The created date. Inherited from deviceAppManagementTask|
|dueDateTime|DateTimeOffset|The due date. Inherited from deviceAppManagementTask|
|category|deviceAppManagementTaskCategory|The category. Inherited from deviceAppManagementTask. Possible values are: `unknown`, `advancedThreatProtection`.|
|priority|deviceAppManagementTaskPriority|The priority. Inherited from deviceAppManagementTask. Possible values are: `none`, `high`, `low`.|
|creator|String|The email address of the creator. Inherited from deviceAppManagementTask|
|creatorNotes|String|Notes from the creator. Inherited from deviceAppManagementTask|
|assignedTo|String|The name or email of the admin this task is assigned to. Inherited from deviceAppManagementTask|
|status|deviceAppManagementTaskStatus|The status. Inherited from deviceAppManagementTask. Possible values are: `unknown`, `pending`, `active`, `completed`, `rejected`.|
|unmanagedDevices|unmanagedDevice collection|Unmanaged devices discovered in the network.|
### [vulnerableManagedDevice ](https://docs.microsoft.com/graph/api/resources/intune-partnerintegration-vulnerablemanageddevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The entity key, and AAD device ID.|
|managedDeviceId|String|The Intune managed device ID.|
|displayName|String|The device name.|
|lastSyncDateTime|DateTimeOffset|The last sync date.|
### [hasPayloadLinkResultItem ](https://docs.microsoft.com/graph/api/resources/intune-policyset-haspayloadlinkresultitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|payloadId|String|Key of the Payload, In the format of Guid.|
|hasLink|Boolean|Indicate whether a payload has any link or not.|
|error|String|Exception information indicates if check for this item was successful or not.Empty string for no error.|
|sources|deviceAndAppManagementAssignmentSource collection|The reason where the link comes from.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-reporting-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
### [deviceManagementCachedReportConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-reporting-devicemanagementcachedreportconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity.|
|reportName|String|Name of the report.|
|filter|String|Filters applied on report creation.|
|select|String collection|Columns selected from the report.|
|orderBy|String collection|Ordering of columns in the report.|
|metadata|String|Caller-managed metadata associated with the report.|
|status|deviceManagementReportStatus|Status of the cached report. Possible values are: `unknown`, `notStarted`, `inProgress`, `completed`, `failed`.|
|lastRefreshDateTime|DateTimeOffset|Time that the cached report was last refreshed.|
|expirationDateTime|DateTimeOffset|Time that the cached report expires.|
### [deviceManagementExportJob ](https://docs.microsoft.com/graph/api/resources/intune-reporting-devicemanagementexportjob?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
|reportName|String|Name of the report|
|filter|String|Filters applied on the report|
|select|String collection|Columns selected from the report|
|format|deviceManagementReportFileFormat|Format of the exported report. Possible values are: `csv`, `pdf`, `json`, `unknownFutureValue`.|
|snapshotId|String|A snapshot is an identifiable subset of the dataset represented by the ReportName. A sessionId or CachedReportConfiguration id can be used here. If a sessionId is specified, Filter, Select, and OrderBy are applied to the data represented by the sessionId. Filter, Select, and OrderBy cannot be specified together with a CachedReportConfiguration id.|
|localizationType|deviceManagementExportJobLocalizationType|Configures how the requested export job is localized. Possible values are: `localizedValuesAsAdditionalColumn`, `replaceLocalizableValues`.|
|status|deviceManagementReportStatus|Status of the export job. Possible values are: `unknown`, `notStarted`, `inProgress`, `completed`, `failed`.|
|url|String|Temporary location of the exported report|
|requestDateTime|DateTimeOffset|Time that the exported report was requested|
|expirationDateTime|DateTimeOffset|Time that the exported report expires|
### [deviceManagementReports ](https://docs.microsoft.com/graph/api/resources/intune-reporting-devicemanagementreports?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
### [deviceManagementReportSchedule ](https://docs.microsoft.com/graph/api/resources/intune-reporting-devicemanagementreportschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
|reportScheduleName|String|Name of the schedule|
|subject|String|Subject of the scheduled reports that are delivered|
|emails|String collection|Emails to which the scheduled reports are delivered|
|recurrence|deviceManagementScheduledReportRecurrence|Frequency of scheduled report delivery. Possible values are: `none`, `daily`, `weekly`, `monthly`.|
|startDateTime|DateTimeOffset|Time that the delivery of the scheduled reports starts|
|endDateTime|DateTimeOffset|Time that the delivery of the scheduled reports ends|
|userId|String|The Id of the User who created the report|
|reportName|String|Name of the report|
|filter|String|Filters applied on the report|
|select|String collection|Columns selected from the report|
|orderBy|String collection|Ordering of columns in the report|
|format|deviceManagementReportFileFormat|Format of the scheduled report. Possible values are: `csv`, `pdf`.|
### [androidManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-shared-androidmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. Inherited from managedAppProtection|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet. Inherited from managedAppProtection|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use. Inherited from managedAppProtection|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Inherited from managedAppProtection. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked. Inherited from managedAppProtection|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required. Inherited from managedAppProtection|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app. Inherited from managedAppProtection|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files. Inherited from managedAppProtection|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. Inherited from managedAppProtection|
|pinRequired|Boolean|Indicates whether an app-level pin is required. Inherited from managedAppProtection|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped. Inherited from managedAppProtection|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked. Inherited from managedAppProtection|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True Inherited from managedAppProtection|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Inherited from managedAppProtection. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True. Inherited from managedAppProtection|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data. Inherited from managedAppProtection|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device. Inherited from managedAppProtection|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps. Inherited from managedAppProtection|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True. Inherited from managedAppProtection|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set. Inherited from managedAppProtection|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. Inherited from managedAppProtection|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app. Inherited from managedAppProtection|
|minimumWipeOsVersion|String|Versions less than or equal to the specified version will wipe the managed app and the associated company data. Inherited from managedAppProtection|
|minimumWipeAppVersion|String|Versions less than or equal to the specified version will wipe the managed app and the associated company data. Inherited from managedAppProtection|
|appActionIfDeviceComplianceRequired|managedAppRemediationAction|Defines a managed app behavior, either block or wipe, when the device is either rooted or jailbroken, if DeviceComplianceRequired is set to true. Inherited from managedAppProtection. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfMaximumPinRetriesExceeded|managedAppRemediationAction|Defines a managed app behavior, either block or wipe, based on maximum number of incorrect pin retry attempts. Inherited from managedAppProtection. Possible values are: `block`, `wipe`, `warn`.|
|pinRequiredInsteadOfBiometricTimeout|Duration|Timeout in minutes for an app pin instead of non biometrics passcode Inherited from managedAppProtection|
|allowedOutboundClipboardSharingExceptionLength|Int32|Specify the number of characters that may be cut or copied from Org data and accounts to any application. This setting overrides the AllowedOutboundClipboardSharingLevel restriction. Default value of '0' means no exception is allowed. Inherited from managedAppProtection|
|notificationRestriction|managedAppNotificationRestriction|Specify app notification restriction Inherited from managedAppProtection. Possible values are: `allow`, `blockOrganizationalData`, `block`.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from targetedManagedAppProtection|
|targetedAppManagementLevels|appManagementLevel|The intended app management levels for this policy Inherited from targetedManagedAppProtection. Possible values are: `unspecified`, `unmanaged`, `mdm`, `androidEnterprise`.|
|screenCaptureBlocked|Boolean|Indicates whether a managed user can take screen captures of managed apps|
|disableAppEncryptionIfDeviceEncryptionIsEnabled|Boolean|When this setting is enabled, app level encryption is disabled if device level encryption is enabled|
|encryptAppData|Boolean|Indicates whether application data for managed apps should be encrypted|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|minimumRequiredPatchVersion|String|Define the oldest required Android security patch level a user can have to gain secure access to the app.|
|minimumWarningPatchVersion|String|Define the oldest recommended Android security patch level a user can have for secure access to the app.|
|exemptedAppPackages|keyValuePair collection|App packages in this list will be exempt from the policy and will be able to receive data from managed apps.|
|minimumWipePatchVersion|String|Android security patch level  less than or equal to the specified value will wipe the managed app and the associated company data.|
|allowedAndroidDeviceManufacturers|String|Semicolon seperated list of device manufacturers allowed, as a string, for the managed app to work.|
|appActionIfAndroidDeviceManufacturerNotAllowed|managedAppRemediationAction|Defines a managed app behavior, either block or wipe, if the specified device manufacturer is not allowed. Possible values are: `block`, `wipe`, `warn`.|
|requiredAndroidSafetyNetDeviceAttestationType|androidManagedAppSafetyNetDeviceAttestationType|Defines the Android SafetyNet Device Attestation requirement for a managed app to work. Possible values are: `none`, `basicIntegrity`, `basicIntegrityAndDeviceCertification`.|
|appActionIfAndroidSafetyNetDeviceAttestationFailed|managedAppRemediationAction|Defines a managed app behavior, either warn or block, if the specified Android SafetyNet Attestation requirment fails. Possible values are: `block`, `wipe`, `warn`.|
|requiredAndroidSafetyNetAppsVerificationType|androidManagedAppSafetyNetAppsVerificationType|Defines the Android SafetyNet Apps Verification requirement for a managed app to work. Possible values are: `none`, `enabled`.|
|appActionIfAndroidSafetyNetAppsVerificationFailed|managedAppRemediationAction|Defines a managed app behavior, either warn or block, if the specified Android App Verification requirment fails. Possible values are: `block`, `wipe`, `warn`.|
|customBrowserPackageId|String|Unique identifier of a custom browser to open weblink on Android.|
|customBrowserDisplayName|String|Friendly name of the preferred custom browser to open weblink on Android.|
|minimumRequiredCompanyPortalVersion|String|Minimum version of the Company portal that must be installed on the device or app access will be blocked|
|minimumWarningCompanyPortalVersion|String|Minimum version of the Company portal that must be installed on the device or the user will receive a warning|
|minimumWipeCompanyPortalVersion|String|Minimum version of the Company portal that must be installed on the device or the company data on the app will be wiped|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-shared-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|**Onboarding**|
|isEnabledForMicrosoftStoreForBusiness|Boolean|Whether the account is enabled for syncing applications from the Microsoft Store for Business.|
|microsoftStoreForBusinessLanguage|String|The locale information used to sync applications from the Microsoft Store for Business. Cultures that are specific to a country/region. The names of these cultures follow RFC 4646 (Windows Vista and later). The format is <languagecode2>-<country/regioncode2>, where <languagecode2> is a lowercase two-letter code derived from ISO 639-1 and <country/regioncode2> is an uppercase two-letter code derived from ISO 3166. For example, en-US for English (United States) is a specific culture.|
|microsoftStoreForBusinessLastCompletedApplicationSyncTime|DateTimeOffset|The last time an application sync from the Microsoft Store for Business was completed.|
|microsoftStoreForBusinessLastSuccessfulSyncDateTime|DateTimeOffset|The last time the apps from the Microsoft Store for Business were synced successfully for the account.|
|microsoftStoreForBusinessPortalSelection|microsoftStoreForBusinessPortalSelectionOptions|The end user portal information is used to sync applications from the Microsoft Store for Business to Intune Company Portal. There are three options to pick from \['Company portal only', 'Company portal and private store', 'Private store only'\]. Possible values are: `none`, `companyPortal`, `privateStore`.|
### [deviceManagementConfigurationChoiceSettingDefinition ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagementconfigurationchoicesettingdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|options|deviceManagementConfigurationOptionDefinition collection|Options for the setting that can be selected|
|defaultOptionId|String|Default option for choice setting|
### [deviceManagementConfigurationRedirectSettingDefinition ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagementconfigurationredirectsettingdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|deepLink|String|A deep link that points to the specific location in the Intune console where feature support must be managed from.|
|redirectMessage|String|A message that explains that clicking the link will redirect the user to a supported page to manage the settings.|
|redirectReason|String|Indicates the reason for redirecting the user to an alternative location in the console.  For example: WiFi profiles are not supported in the settings catalog and must be created with a template policy.|
### [deviceManagementConfigurationSettingDefinition ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagementconfigurationsettingdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on|
|infoUrls|String collection|List of links more info for the setting can be found at|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not|
|baseUri|String|Base CSP Path|
|offsetUri|String|Offset CSP Path from Base|
|rootDefinitionId|String|Root setting definition if the setting is a child setting.|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP)|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information.|
|id|String|Identifier for item|
|description|String|Description of the item|
|helpText|String|Help text of the item|
|name|String|Name of the item|
|displayName|String|Display name of the item|
|version|String|Item Version|
### [deviceManagementConfigurationSettingGroupDefinition ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagementconfigurationsettinggroupdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|childIds|String collection|Dependent child settings to this group of settings|
|dependentOn|deviceManagementConfigurationDependentOn collection|List of Dependencies for the setting group|
|dependedOnBy|deviceManagementConfigurationSettingDependedOnBy collection|List of child settings that depend on this setting|
### [deviceManagementConfigurationSimpleSettingDefinition ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagementconfigurationsimplesettingdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|applicability|deviceManagementConfigurationSettingApplicability|Details which device setting is applicable on Inherited from deviceManagementConfigurationSettingDefinition|
|accessTypes|deviceManagementConfigurationSettingAccessTypes|Read/write access mode of the setting Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `add`, `copy`, `delete`, `get`, `replace`, `execute`.|
|keywords|String collection|Tokens which to search settings on Inherited from deviceManagementConfigurationSettingDefinition|
|infoUrls|String collection|List of links more info for the setting can be found at Inherited from deviceManagementConfigurationSettingDefinition|
|occurrence|deviceManagementConfigurationSettingOccurrence|Indicates whether the setting is required or not Inherited from deviceManagementConfigurationSettingDefinition|
|baseUri|String|Base CSP Path Inherited from deviceManagementConfigurationSettingDefinition|
|offsetUri|String|Offset CSP Path from Base Inherited from deviceManagementConfigurationSettingDefinition|
|rootDefinitionId|String|Root setting definition if the setting is a child setting. Inherited from deviceManagementConfigurationSettingDefinition|
|categoryId|String|Specifies the area group under which the setting is configured in a specified configuration service provider (CSP) Inherited from deviceManagementConfigurationSettingDefinition|
|settingUsage|deviceManagementConfigurationSettingUsage|Setting type, for example, configuration and compliance Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `configuration`, `compliance`.|
|uxBehavior|deviceManagementConfigurationControlType|Setting control type representation in the UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `default`, `dropdown`, `smallTextBox`, `largeTextBox`, `toggle`, `multiheaderGrid`, `contextPane`.|
|visibility|deviceManagementConfigurationSettingVisibility|Setting visibility scope to UX Inherited from deviceManagementConfigurationSettingDefinition. Possible values are: `none`, `settingsCatalog`, `template`.|
|referredSettingInformationList|deviceManagementConfigurationReferredSettingInformation collection|List of referred setting information. Inherited from deviceManagementConfigurationSettingDefinition|
|id|String|Identifier for item Inherited from deviceManagementConfigurationSettingDefinition|
|description|String|Description of the item Inherited from deviceManagementConfigurationSettingDefinition|
|helpText|String|Help text of the item Inherited from deviceManagementConfigurationSettingDefinition|
|name|String|Name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|displayName|String|Display name of the item Inherited from deviceManagementConfigurationSettingDefinition|
|version|String|Item Version Inherited from deviceManagementConfigurationSettingDefinition|
|valueDefinition|deviceManagementConfigurationSettingValueDefinition|Definition of the value for this setting|
|defaultValue|deviceManagementConfigurationSettingValue|Default setting value for this setting|
|dependentOn|deviceManagementConfigurationDependentOn collection|list of parent settings this setting is dependent on|
|dependedOnBy|deviceManagementConfigurationSettingDependedOnBy collection|list of child settings that depend on this setting|
### [iosLobAppProvisioningConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-shared-ioslobappprovisioningconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|expirationDateTime|DateTimeOffset|Optional profile expiration date and time.|
|payloadFileName|String|Payload file name (*.mobileprovision | *.xml).|
|payload|Binary|Payload. (UTF8 encoded byte array)|
|roleScopeTagIds|String collection|List of Scope Tags for this iOS LOB app provisioning configuration entity.|
|createdDateTime|DateTimeOffset|DateTime the object was created.|
|description|String|Admin provided description of the Device Configuration.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|displayName|String|Admin provided name of the device configuration.|
|version|Int32|Version of the device configuration.|
### [iosManagedAppProtection ](https://docs.microsoft.com/graph/api/resources/intune-shared-iosmanagedappprotection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|periodOfflineBeforeAccessCheck|Duration|The period after which access is checked when the device is not connected to the internet. Inherited from managedAppProtection|
|periodOnlineBeforeAccessCheck|Duration|The period after which access is checked when the device is connected to the internet. Inherited from managedAppProtection|
|allowedInboundDataTransferSources|managedAppDataTransferLevel|Sources from which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|allowedOutboundDataTransferDestinations|managedAppDataTransferLevel|Destinations to which data is allowed to be transferred. Inherited from managedAppProtection. Possible values are: `allApps`, `managedApps`, `none`.|
|organizationalCredentialsRequired|Boolean|Indicates whether organizational credentials are required for app use. Inherited from managedAppProtection|
|allowedOutboundClipboardSharingLevel|managedAppClipboardSharingLevel|The level to which the clipboard may be shared between apps on the managed device. Inherited from managedAppProtection. Possible values are: `allApps`, `managedAppsWithPasteIn`, `managedApps`, `blocked`.|
|dataBackupBlocked|Boolean|Indicates whether the backup of a managed app's data is blocked. Inherited from managedAppProtection|
|deviceComplianceRequired|Boolean|Indicates whether device compliance is required. Inherited from managedAppProtection|
|managedBrowserToOpenLinksRequired|Boolean|Indicates whether internet links should be opened in the managed browser app. Inherited from managedAppProtection|
|saveAsBlocked|Boolean|Indicates whether users may use the "Save As" menu item to save a copy of protected files. Inherited from managedAppProtection|
|periodOfflineBeforeWipeIsEnforced|Duration|The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped. Inherited from managedAppProtection|
|pinRequired|Boolean|Indicates whether an app-level pin is required. Inherited from managedAppProtection|
|maximumPinRetries|Int32|Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped. Inherited from managedAppProtection|
|simplePinBlocked|Boolean|Indicates whether simplePin is blocked. Inherited from managedAppProtection|
|minimumPinLength|Int32|Minimum pin length required for an app-level pin if PinRequired is set to True Inherited from managedAppProtection|
|pinCharacterSet|managedAppPinCharacterSet|Character set which may be used for an app-level pin if PinRequired is set to True. Inherited from managedAppProtection. Possible values are: `numeric`, `alphanumericAndSymbol`.|
|periodBeforePinReset|Duration|TimePeriod before the all-level pin must be reset if PinRequired is set to True. Inherited from managedAppProtection|
|allowedDataStorageLocations|managedAppDataStorageLocation collection|Data storage locations where a user may store managed data. Inherited from managedAppProtection|
|contactSyncBlocked|Boolean|Indicates whether contacts can be synced to the user's device. Inherited from managedAppProtection|
|printBlocked|Boolean|Indicates whether printing is allowed from managed apps. Inherited from managedAppProtection|
|fingerprintBlocked|Boolean|Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True. Inherited from managedAppProtection|
|disableAppPinIfDevicePinIsSet|Boolean|Indicates whether use of the app pin is required if the device pin is set. Inherited from managedAppProtection|
|minimumRequiredOsVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningOsVersion|String|Versions less than the specified version will result in warning message on the managed app from accessing company data. Inherited from managedAppProtection|
|minimumRequiredAppVersion|String|Versions less than the specified version will block the managed app from accessing company data. Inherited from managedAppProtection|
|minimumWarningAppVersion|String|Versions less than the specified version will result in warning message on the managed app. Inherited from managedAppProtection|
|minimumWipeOsVersion|String|Versions less than or equal to the specified version will wipe the managed app and the associated company data. Inherited from managedAppProtection|
|minimumWipeAppVersion|String|Versions less than or equal to the specified version will wipe the managed app and the associated company data. Inherited from managedAppProtection|
|appActionIfDeviceComplianceRequired|managedAppRemediationAction|Defines a managed app behavior, either block or wipe, when the device is either rooted or jailbroken, if DeviceComplianceRequired is set to true. Inherited from managedAppProtection. Possible values are: `block`, `wipe`, `warn`.|
|appActionIfMaximumPinRetriesExceeded|managedAppRemediationAction|Defines a managed app behavior, either block or wipe, based on maximum number of incorrect pin retry attempts. Inherited from managedAppProtection. Possible values are: `block`, `wipe`, `warn`.|
|pinRequiredInsteadOfBiometricTimeout|Duration|Timeout in minutes for an app pin instead of non biometrics passcode Inherited from managedAppProtection|
|allowedOutboundClipboardSharingExceptionLength|Int32|Specify the number of characters that may be cut or copied from Org data and accounts to any application. This setting overrides the AllowedOutboundClipboardSharingLevel restriction. Default value of '0' means no exception is allowed. Inherited from managedAppProtection|
|notificationRestriction|managedAppNotificationRestriction|Specify app notification restriction Inherited from managedAppProtection. Possible values are: `allow`, `blockOrganizationalData`, `block`.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from targetedManagedAppProtection|
|targetedAppManagementLevels|appManagementLevel|The intended app management levels for this policy Inherited from targetedManagedAppProtection. Possible values are: `unspecified`, `unmanaged`, `mdm`, `androidEnterprise`.|
|appDataEncryptionType|managedAppDataEncryptionType|Type of encryption which should be used for data in a managed app. Possible values are: `useDeviceSettings`, `afterDeviceRestart`, `whenDeviceLockedExceptOpenFiles`, `whenDeviceLocked`.|
|minimumRequiredSdkVersion|String|Versions less than the specified version will block the managed app from accessing company data.|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|faceIdBlocked|Boolean|Indicates whether use of the FaceID is allowed in place of a pin if PinRequired is set to True.|
|exemptedAppProtocols|keyValuePair collection|Apps in this list will be exempt from the policy and will be able to receive data from managed apps.|
|minimumWipeSdkVersion|String|Versions less than the specified version will block the managed app from accessing company data.|
|allowedIosDeviceModels|String|Semicolon seperated list of device models allowed, as a string, for the managed app to work.|
|appActionIfIosDeviceModelNotAllowed|managedAppRemediationAction|Defines a managed app behavior, either block or wipe, if the specified device model is not allowed. Possible values are: `block`, `wipe`, `warn`.|
|filterOpenInToOnlyManagedApps|Boolean|Defines if open-in operation is supported from the managed app to the filesharing locations selected. This setting only applies when AllowedOutboundDataTransferDestinations is set to ManagedApps and DisableProtectionOfManagedOutboundOpenInData is set to False.|
|disableProtectionOfManagedOutboundOpenInData|Boolean|Disable protection of data transferred to other apps through IOS OpenIn option. This setting is only allowed to be True when AllowedOutboundDataTransferDestinations is set to ManagedApps.|
|protectInboundDataFromUnknownSources|Boolean|Protect incoming data from unknown source. This setting is only allowed to be True when AllowedInboundDataTransferSources is set to AllApps.|
|customBrowserProtocol|String|A custom browser protocol to open weblink on iOS.|
### [mdmWindowsInformationProtectionPolicy ](https://docs.microsoft.com/graph/api/resources/intune-shared-mdmwindowsinformationprotectionpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|enforcementLevel|windowsInformationProtectionEnforcementLevel|WIP enforcement level.See the Enum definition for supported values Inherited from windowsInformationProtection. Possible values are: `noProtection`, `encryptAndAuditOnly`, `encryptAuditAndPrompt`, `encryptAuditAndBlock`.|
|enterpriseDomain|String|Primary enterprise domain Inherited from windowsInformationProtection|
|enterpriseProtectedDomainNames|windowsInformationProtectionResourceCollection collection|List of enterprise domains to be protected Inherited from windowsInformationProtection|
|protectionUnderLockConfigRequired|Boolean|Specifies whether the protection under lock feature (also known as encrypt under pin) should be configured Inherited from windowsInformationProtection|
|dataRecoveryCertificate|windowsInformationProtectionDataRecoveryCertificate|Specifies a recovery certificate that can be used for data recovery of encrypted files. This is the same as the data recovery agent(DRA) certificate for encrypting file system(EFS) Inherited from windowsInformationProtection|
|revokeOnUnenrollDisabled|Boolean|This policy controls whether to revoke the WIP keys when a device unenrolls from the management service. If set to 1 (Don't revoke keys), the keys will not be revoked and the user will continue to have access to protected files after unenrollment. If the keys are not revoked, there will be no revoked file cleanup subsequently. Inherited from windowsInformationProtection|
|rightsManagementServicesTemplateId|Guid|TemplateID GUID to use for RMS encryption. The RMS template allows the IT admin to configure the details about who has access to RMS-protected file and how long they have access Inherited from windowsInformationProtection|
|azureRightsManagementServicesAllowed|Boolean|Specifies whether to allow Azure RMS encryption for WIP Inherited from windowsInformationProtection|
|iconsVisible|Boolean|Determines whether overlays are added to icons for WIP protected files in Explorer and enterprise only app tiles in the Start menu. Starting in Windows 10, version 1703 this setting also configures the visibility of the WIP icon in the title bar of a WIP-protected app Inherited from windowsInformationProtection|
|protectedApps|windowsInformationProtectionApp collection|Protected applications can access enterprise data and the data handled by those applications are protected with encryption Inherited from windowsInformationProtection|
|exemptApps|windowsInformationProtectionApp collection|Exempt applications can also access enterprise data, but the data handled by those applications are not protected. This is because some critical enterprise applications may have compatibility problems with encrypted data. Inherited from windowsInformationProtection|
|enterpriseNetworkDomainNames|windowsInformationProtectionResourceCollection collection|This is the list of domains that comprise the boundaries of the enterprise. Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to Inherited from windowsInformationProtection|
|enterpriseProxiedDomains|windowsInformationProtectionProxiedDomainCollection collection|Contains a list of Enterprise resource domains hosted in the cloud that need to be protected. Connections to these resources are considered enterprise data. If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80). A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy Inherited from windowsInformationProtection|
|enterpriseIPRanges|windowsInformationProtectionIPRangeCollection collection|Sets the enterprise IP ranges that define the computers in the enterprise network. Data that comes from those computers will be considered part of the enterprise and protected. These locations will be considered a safe destination for enterprise data to be shared to Inherited from windowsInformationProtection|
|enterpriseIPRangesAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list and not to use heuristics to attempt to find other subnets. Default is false Inherited from windowsInformationProtection|
|enterpriseProxyServers|windowsInformationProtectionResourceCollection collection|This is a list of proxy servers. Any server not on this list is considered non-enterprise Inherited from windowsInformationProtection|
|enterpriseInternalProxyServers|windowsInformationProtectionResourceCollection collection|This is the comma-separated list of internal proxy servers. For example, "157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59". These proxies have been configured by the admin to connect to specific resources on the Internet. They are considered to be enterprise network locations. The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies Inherited from windowsInformationProtection|
|enterpriseProxyServersAreAuthoritative|Boolean|Boolean value that tells the client to accept the configured list of proxies and not try to detect other work proxies. Default is false Inherited from windowsInformationProtection|
|neutralDomainResources|windowsInformationProtectionResourceCollection collection|List of domain names that can used for work or personal resource Inherited from windowsInformationProtection|
|indexingEncryptedStoresOrItemsBlocked|Boolean|This switch is for the Windows Search Indexer, to allow or disallow indexing of items Inherited from windowsInformationProtection|
|smbAutoEncryptedFileExtensions|windowsInformationProtectionResourceCollection collection|Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary Inherited from windowsInformationProtection|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not. Inherited from windowsInformationProtection|
### [mobileApp ](https://docs.microsoft.com/graph/api/resources/intune-shared-mobileapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|displayName|String|The admin provided or imported title of the app.|
|description|String|The description of the app.|
|publisher|String|The publisher of the app.|
|largeIcon|mimeContent|The large icon, to be displayed in the app details and used for upload of the icon.|
|createdDateTime|DateTimeOffset|The date and time the app was created.|
|lastModifiedDateTime|DateTimeOffset|The date and time the app was last modified.|
|isFeatured|Boolean|The value indicating whether the app is marked as featured by the admin.|
|privacyInformationUrl|String|The privacy statement Url.|
|informationUrl|String|The more information Url.|
|owner|String|The owner of the app.|
|developer|String|The developer of the app.|
|notes|String|Notes for the app.|
|uploadState|Int32|The upload state.|
|publishingState|mobileAppPublishingState|The publishing state for the app. The app cannot be assigned unless the app is published. Possible values are: `notPublished`, `processing`, `published`.|
|isAssigned|Boolean|The value indicating whether the app is assigned to at least one group.|
|roleScopeTagIds|String collection|List of scope tag ids for this mobile app.|
|dependentAppCount|Int32|The total number of dependencies the child app has.|
### [targetedManagedAppConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-shared-targetedmanagedappconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from managedAppPolicy|
|displayName|String|Policy display name. Inherited from managedAppPolicy|
|description|String|The policy's description. Inherited from managedAppPolicy|
|createdDateTime|DateTimeOffset|The date and time the policy was created. Inherited from managedAppPolicy|
|lastModifiedDateTime|DateTimeOffset|Last time the policy was modified. Inherited from managedAppPolicy|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from managedAppPolicy|
|version|String|Version of the entity. Inherited from managedAppPolicy|
|customSettings|keyValuePair collection|A set of string key and string value pairs to be sent to apps for users to whom the configuration is scoped, unalterned by this service Inherited from managedAppConfiguration|
|deployedAppCount|Int32|Count of apps to which the current policy is deployed.|
|isAssigned|Boolean|Indicates if the policy is deployed to any inclusion groups or not.|
### [user ](https://docs.microsoft.com/graph/api/resources/intune-shared-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the user.|
|**Onboarding**|
|deviceEnrollmentLimit|Int32|The limit on the maximum number of devices that the user is permitted to enroll. Allowed values are 5 or 1000.|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-unlock-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [windowsDefenderApplicationControlSupplementalPolicy ](https://docs.microsoft.com/graph/api/resources/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the Windows Defender Application Control Supplemental Policy. This id is assigned during creation of the policy.|
|displayName|String|The display name of the Windows Defender Application Control Supplemental Policy.|
|description|String|The description of the Windows Defender Application Control Supplemental Policy.|
|content|Binary|Indicates the content of the Windows Defender Application Control Supplemental Policy in byte array format.|
|contentFileName|String|Indicates the file name associated with the content of the Windows Defender Application Control Supplemental Policy.|
|version|String|Indicates the Windows Defender Application Control Supplemental Policy's version.|
|creationDateTime|DateTimeOffset|Indicates the created date and time when the Windows Defender Application Control Supplemental Policy was uploaded.|
|lastModifiedDateTime|DateTimeOffset|Indicates the last modified date and time of the Windows Defender Application Control Supplemental Policy.|
|roleScopeTagIds|String collection|List of Scope Tags for the Windows Defender Application Control Supplemental Policy entity.|
### [windowsDefenderApplicationControlSupplementalPolicyAssignment ](https://docs.microsoft.com/graph/api/resources/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicyassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|target|deviceAndAppManagementAssignmentTarget|The target group assignment defined by the admin.|
### [windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus ](https://docs.microsoft.com/graph/api/resources/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicydeploymentstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|deviceName|String|Device name.|
|deviceId|String|Device ID.|
|lastSyncDateTime|DateTimeOffset|Last sync date time.|
|osVersion|String|Windows OS Version.|
|osDescription|String|Windows OS Version Description.|
|deploymentStatus|windowsDefenderApplicationControlSupplementalPolicyStatuses|The deployment state of the policy. Possible values are: `unknown`, `success`, `tokenError`, `notAuthorizedByToken`, `policyNotFound`.|
|userName|String|The name of the user of this device.|
|userPrincipalName|String|User Principal Name.|
|policyVersion|String|Human readable version of the WindowsDefenderApplicationControl supplemental policy.|
### [windowsDefenderApplicationControlSupplementalPolicyDeploymentSummary ](https://docs.microsoft.com/graph/api/resources/intune-unlock-windowsdefenderapplicationcontrolsupplementalpolicydeploymentsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|deployedDeviceCount|Int32|Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.|
|failedDeviceCount|Int32|Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-wip-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
### [intuneBrandingProfile ](https://docs.microsoft.com/graph/api/resources/intune-wip-intunebrandingprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile Key|
|profileName|String|Name of the profile|
|profileDescription|String|Description of the profile|
|isDefaultProfile|Boolean|Boolean that represents whether the profile is used as default or not|
|createdDateTime|DateTimeOffset|Time when the BrandingProfile was created|
|lastModifiedDateTime|DateTimeOffset|Time when the BrandingProfile was last modified|
|displayName|String|Company/organization name that is displayed to end users|
|themeColor|rgbColor|Primary theme color used in the Company Portal applications and web portal|
|showLogo|Boolean|Boolean that represents whether the administrator-supplied logo images are shown or not|
|showDisplayNameNextToLogo|Boolean|Boolean that represents whether the administrator-supplied display name will be shown next to the logo image or not|
|themeColorLogo|mimeContent|Logo image displayed in Company Portal apps which have a theme color background behind the logo|
|lightBackgroundLogo|mimeContent|Logo image displayed in Company Portal apps which have a light background behind the logo|
|landingPageCustomizedImage|mimeContent|Customized image displayed in Company Portal apps landing page|
|contactITName|String|Name of the person/organization responsible for IT support|
|contactITPhoneNumber|String|Phone number of the person/organization responsible for IT support|
|contactITEmailAddress|String|E-mail address of the person/organization responsible for IT support|
|contactITNotes|String|Text comments regarding the person/organization responsible for IT support|
|onlineSupportSiteUrl|String|URL to the company/organization’s IT helpdesk site|
|onlineSupportSiteName|String|Display name of the company/organization’s IT helpdesk site|
|privacyUrl|String|URL to the company/organization’s privacy policy|
|customPrivacyMessage|String|Text comments regarding what the admin doesn't have access to on the device|
|customCanSeePrivacyMessage|String|Text comments regarding what the admin has access to on the device|
|customCantSeePrivacyMessage|String|Text comments regarding what the admin doesn't have access to on the device|
|isRemoveDeviceDisabled|Boolean|Boolean that represents whether the adminsistrator has disabled the 'Remove Device' action on corporate owned devices.|
|isFactoryResetDisabled|Boolean|Boolean that represents whether the adminsistrator has disabled the 'Factory Reset' action on corporate owned devices.|
|companyPortalBlockedActions|companyPortalBlockedAction collection|Collection of blocked actions on the company portal as per platform and device ownership types.|
|disableDeviceCategorySelection|Boolean|Boolean that indicates if Device Category Selection will be shown in Company Portal|
|showAzureADEnterpriseApps|Boolean|Boolean that indicates if AzureAD Enterprise Apps will be shown in Company Portal|
|showOfficeWebApps|Boolean|Boolean that indicates if Office WebApps will be shown in Company Portal|
|showConfigurationManagerApps|Boolean|Boolean that indicates if Configuration Manager Apps will be shown in Company Portal|
|sendDeviceOwnershipChangePushNotification|Boolean|Boolean that indicates if a push notification is sent to users when their device ownership type changes from personal to corporate|
|enrollmentAvailability|enrollmentAvailabilityOptions|Customized device enrollment flow displayed to the end user . Possible values are: `availableWithPrompts`, `availableWithoutPrompts`, `unavailable`.|
|disableClientTelemetry|Boolean|Applies to telemetry sent from all clients to the Intune service. When disabled, all proactive troubleshooting and issue warnings within the client are turned off, and telemetry settings appear inactive or hidden to the device user.|
|roleScopeTagIds|String collection|List of scope tags assigned to the branding profile|
### [intuneBrandingProfileAssignment ](https://docs.microsoft.com/graph/api/resources/intune-wip-intunebrandingprofileassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the entity.|
|target|deviceAndAppManagementAssignmentTarget|Assignment target that the branding profile is assigned to.|
### [windowsInformationProtectionAppLearningSummary ](https://docs.microsoft.com/graph/api/resources/intune-wip-windowsinformationprotectionapplearningsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the WindowsInformationProtectionAppLearningSummary.|
|applicationName|String|Application Name|
|applicationType|applicationType|Application Type. Possible values are: `universal`, `desktop`.|
|deviceCount|Int32|Device Count|
### [windowsInformationProtectionNetworkLearningSummary ](https://docs.microsoft.com/graph/api/resources/intune-wip-windowsinformationprotectionnetworklearningsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the WindowsInformationProtectionNetworkLearningSummary.|
|url|String|Website url|
|deviceCount|Int32|Device Count|
