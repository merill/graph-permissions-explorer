# DeviceManagementServiceConfig.ReadWrite.All

> Allows the app to read and write Microsoft Intune service properties including device enrollment and third party service connection configuration.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /deviceAppManagement/sideLoadingKeys/{sideLoadingKeyId}](https://docs.microsoft.com/graph/api/intune-onboarding-sideloadingkey-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /deviceAppManagement/vppTokens/{vppTokenId}](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-appleuserinitiatedenrollmentprofile-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}/assignments/{appleEnrollmentProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-enrollment-appleenrollmentprofileassignment-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/complianceManagementPartners/{complianceManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-onboarding-compliancemanagementpartner-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/dataSharingConsents/{dataSharingConsentId}](https://docs.microsoft.com/graph/api/intune-devices-datasharingconsent-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/defaultIosEnrollmentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-depiosenrollmentprofile-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/defaultMacOsEnrollmentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-depmacosenrollmentprofile-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles/{enrollmentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/importedAppleDeviceIdentities/{importedAppleDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importedappledeviceidentity-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/derivedCredentials/{deviceManagementDerivedCredentialSettingsId}](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementderivedcredentialsettings-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentplatformrestrictionsconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/assignments/{enrollmentConfigurationAssignmentId}](https://docs.microsoft.com/graph/api/intune-onboarding-enrollmentconfigurationassignment-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/deviceManagementPartners/{deviceManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementpartner-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/exchangeConnectors/{deviceManagementExchangeConnectorId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeconnector-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/importedDeviceIdentities/{importedDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentityresult-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/importedWindowsAutopilotDeviceIdentities/{importedWindowsAutopilotDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importedwindowsautopilotdeviceidentity-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/mobileThreatDefenseConnectors/{mobileThreatDefenseConnectorId}](https://docs.microsoft.com/graph/api/intune-onboarding-mobilethreatdefenseconnector-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}](https://docs.microsoft.com/graph/api/intune-notification-notificationmessagetemplate-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}/localizedNotificationMessages/{localizedNotificationMessageId}](https://docs.microsoft.com/graph/api/intune-notification-localizednotificationmessage-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}](https://docs.microsoft.com/graph/api/intune-rapolicy-windows10xtrustedrootcertificate-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}/assignments/{deviceManagementResourceAccessProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofileassignment-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/telecomExpenseManagementPartners/{telecomExpenseManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-tem-telecomexpensemanagementpartner-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/termsAndConditions/{termsAndConditionsId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses/{termsAndConditionsAcceptanceStatusId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsacceptancestatus-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses/{termsAndConditionsAcceptanceStatusId}/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/termsAndConditions/{termsAndConditionsId}/assignments/{termsAndConditionsAssignmentId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsassignment-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments/{termsAndConditionsGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsgroupassignment-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments/{termsAndConditionsGroupAssignmentId}/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/windowsAutopilotDeploymentProfiles/{windowsAutopilotDeploymentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignments/{windowsAutopilotDeploymentProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeploymentprofileassignment-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/intendedDeploymentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /users/{usersId}](https://docs.microsoft.com/graph/api/intune-onboarding-user-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/sideLoadingKeys](https://docs.microsoft.com/graph/api/intune-onboarding-sideloadingkey-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/sideLoadingKeys/{sideLoadingKeyId}](https://docs.microsoft.com/graph/api/intune-onboarding-sideloadingkey-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/vppTokens](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceAppManagement/vppTokens/{vppTokenId}](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/vppTokens/getLicensesForApp](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-getlicensesforapp?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement](https://docs.microsoft.com/graph/api/intune-tem-devicemanagement-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/applePushNotificationCertificate](https://docs.microsoft.com/graph/api/intune-devices-applepushnotificationcertificate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/applePushNotificationCertificate/downloadApplePushNotificationCertificateSigningRequest](https://docs.microsoft.com/graph/api/intune-devices-applepushnotificationcertificate-downloadapplepushnotificationcertificatesigningrequest?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/appleUserInitiatedEnrollmentProfiles](https://docs.microsoft.com/graph/api/intune-enrollment-appleuserinitiatedenrollmentprofile-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-appleuserinitiatedenrollmentprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}/assignments](https://docs.microsoft.com/graph/api/intune-enrollment-appleenrollmentprofileassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}/assignments/{appleEnrollmentProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-enrollment-appleenrollmentprofileassignment-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/complianceManagementPartners](https://docs.microsoft.com/graph/api/intune-onboarding-compliancemanagementpartner-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/complianceManagementPartners/{complianceManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-onboarding-compliancemanagementpartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/conditionalAccessSettings](https://docs.microsoft.com/graph/api/intune-onboarding-onpremisesconditionalaccesssettings-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/dataSharingConsents](https://docs.microsoft.com/graph/api/intune-devices-datasharingconsent-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/dataSharingConsents/{dataSharingConsentId}](https://docs.microsoft.com/graph/api/intune-devices-datasharingconsent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/defaultIosEnrollmentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-depiosenrollmentprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/defaultMacOsEnrollmentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-depmacosenrollmentprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles](https://docs.microsoft.com/graph/api/intune-enrollment-depenrollmentprofile-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles/{enrollmentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles/{enrollmentProfileId}/exportMobileConfig](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-exportmobileconfig?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/getEncryptionPublicKey](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-getencryptionpublickey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/importedAppleDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importedappledeviceidentity-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/importedAppleDeviceIdentities/{importedAppleDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importedappledeviceidentityresult-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/depOnboardingSettings/getExpiringVppTokenCount](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-getexpiringvpptokencount?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/derivedCredentials](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementderivedcredentialsettings-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/derivedCredentials/{deviceManagementDerivedCredentialSettingsId}](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementderivedcredentialsettings-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceManagement/deviceConfigurations/{deviceConfigurationId}](https://docs.microsoft.com/graph/api/intune-shared-windowsdomainjoinconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceManagement/deviceConfigurations/{deviceConfigurationId}/groupAssignments/{deviceConfigurationGroupAssignmentId}/deviceConfiguration](https://docs.microsoft.com/graph/api/intune-shared-windowsdomainjoinconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta||[GET /deviceManagement/deviceConfigurations/{deviceConfigurationId}/microsoft.graph.windowsDomainJoinConfiguration/networkAccessConfigurations/{deviceConfigurationId}](https://docs.microsoft.com/graph/api/intune-shared-windowsdomainjoinconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceEnrollmentConfigurations](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentwindowshelloforbusinessconfiguration-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentwindowshelloforbusinessconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/assignments](https://docs.microsoft.com/graph/api/intune-onboarding-enrollmentconfigurationassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/assignments/{enrollmentConfigurationAssignmentId}](https://docs.microsoft.com/graph/api/intune-onboarding-enrollmentconfigurationassignment-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceManagementPartners](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementpartner-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceManagementPartners/{deviceManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementpartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/exchangeConnectors](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeconnector-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/exchangeConnectors/{deviceManagementExchangeConnectorId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeconnector-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/exchangeOnPremisesPolicies/{deviceManagementExchangeOnPremisesPolicyId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeonpremisespolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/exchangeOnPremisesPolicy](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeonpremisespolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/exchangeOnPremisesPolicy/conditionalAccessSettings](https://docs.microsoft.com/graph/api/intune-onboarding-onpremisesconditionalaccesssettings-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/getSuggestedEnrollmentLimit](https://docs.microsoft.com/graph/api/intune-enrollment-devicemanagement-getsuggestedenrollmentlimit?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/importedDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentity-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/importedDeviceIdentities/{importedDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentityresult-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/importedWindowsAutopilotDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importedwindowsautopilotdeviceidentity-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/importedWindowsAutopilotDeviceIdentities/{importedWindowsAutopilotDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importedwindowsautopilotdeviceidentity-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/mobileThreatDefenseConnectors](https://docs.microsoft.com/graph/api/intune-onboarding-mobilethreatdefenseconnector-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/mobileThreatDefenseConnectors/{mobileThreatDefenseConnectorId}](https://docs.microsoft.com/graph/api/intune-onboarding-mobilethreatdefenseconnector-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/notificationMessageTemplates](https://docs.microsoft.com/graph/api/intune-notification-notificationmessagetemplate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}](https://docs.microsoft.com/graph/api/intune-notification-notificationmessagetemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}/localizedNotificationMessages](https://docs.microsoft.com/graph/api/intune-notification-localizednotificationmessage-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}/localizedNotificationMessages/{localizedNotificationMessageId}](https://docs.microsoft.com/graph/api/intune-notification-localizednotificationmessage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/remoteAssistancePartners](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/remoteAssistanceSettings](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancesettings-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports](https://docs.microsoft.com/graph/api/intune-remoteassistance-devicemanagementreports-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/resourceAccessProfiles](https://docs.microsoft.com/graph/api/intune-rapolicy-windows10xwificonfiguration-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}](https://docs.microsoft.com/graph/api/intune-rapolicy-windows10xtrustedrootcertificate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}/assignments](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofileassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}/assignments/{deviceManagementResourceAccessProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofileassignment-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/telecomExpenseManagementPartners](https://docs.microsoft.com/graph/api/intune-tem-telecomexpensemanagementpartner-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/telecomExpenseManagementPartners/{telecomExpenseManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-tem-telecomexpensemanagementpartner-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsacceptancestatus-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses/{termsAndConditionsAcceptanceStatusId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsacceptancestatus-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses/{termsAndConditionsAcceptanceStatusId}/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/assignments](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsassignment-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/assignments/{termsAndConditionsAssignmentId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsassignment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsgroupassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments/{termsAndConditionsGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsgroupassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments/{termsAndConditionsGroupAssignmentId}/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/verifyWindowsEnrollmentAutoDiscovery](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagement-verifywindowsenrollmentautodiscovery?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeploymentProfiles](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeploymentProfiles/{windowsAutopilotDeploymentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-azureadwindowsautopilotdeploymentprofile-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-azureadwindowsautopilotdeploymentprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignments](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeploymentprofileassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignments/{windowsAutopilotDeploymentProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeploymentprofileassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/microsoft.graph.activeDirectoryWindowsAutopilotDeploymentProfile/domainJoinConfiguration](https://docs.microsoft.com/graph/api/intune-enrollment-windowsdomainjoinconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/intendedDeploymentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-azureadwindowsautopilotdeploymentprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/windowsAutopilotSettings](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotsettings-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /organization](https://docs.microsoft.com/graph/api/intune-onboarding-organization-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}](https://docs.microsoft.com/graph/api/intune-onboarding-organization-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users](https://docs.microsoft.com/graph/api/intune-onboarding-user-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{usersId}](https://docs.microsoft.com/graph/api/intune-onboarding-user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{usersId}/exportDeviceAndAppManagementData](https://docs.microsoft.com/graph/api/intune-onboarding-user-exportdeviceandappmanagementdata?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/getEffectiveDeviceEnrollmentConfigurations](https://docs.microsoft.com/graph/api/intune-shared-user-geteffectivedeviceenrollmentconfigurations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceAppManagement/sideLoadingKeys/{sideLoadingKeyId}](https://docs.microsoft.com/graph/api/intune-onboarding-sideloadingkey-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /deviceAppManagement/vppTokens/{vppTokenId}](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement](https://docs.microsoft.com/graph/api/intune-companyterms-devicemanagement-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/applePushNotificationCertificate](https://docs.microsoft.com/graph/api/intune-devices-applepushnotificationcertificate-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-appleuserinitiatedenrollmentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}/assignments/{appleEnrollmentProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-enrollment-appleenrollmentprofileassignment-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/complianceManagementPartners/{complianceManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-onboarding-compliancemanagementpartner-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/conditionalAccessSettings](https://docs.microsoft.com/graph/api/intune-onboarding-onpremisesconditionalaccesssettings-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/dataSharingConsents/{dataSharingConsentId}](https://docs.microsoft.com/graph/api/intune-devices-datasharingconsent-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/defaultIosEnrollmentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-depiosenrollmentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/defaultMacOsEnrollmentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-depmacosenrollmentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles/{enrollmentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/importedAppleDeviceIdentities/{importedAppleDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importedappledeviceidentity-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/derivedCredentials/{deviceManagementDerivedCredentialSettingsId}](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementderivedcredentialsettings-update?view=graph-rest-beta&tabs=http)|
|Beta||[PATCH /deviceManagement/deviceConfigurations/{deviceConfigurationId}](https://docs.microsoft.com/graph/api/intune-shared-windowsdomainjoinconfiguration-update?view=graph-rest-beta&tabs=http)|
|Beta||[PATCH /deviceManagement/deviceConfigurations/{deviceConfigurationId}/groupAssignments/{deviceConfigurationGroupAssignmentId}/deviceConfiguration](https://docs.microsoft.com/graph/api/intune-shared-windowsdomainjoinconfiguration-update?view=graph-rest-beta&tabs=http)|
|Beta||[PATCH /deviceManagement/deviceConfigurations/{deviceConfigurationId}/microsoft.graph.windowsDomainJoinConfiguration/networkAccessConfigurations/{deviceConfigurationId}](https://docs.microsoft.com/graph/api/intune-shared-windowsdomainjoinconfiguration-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentplatformrestrictionsconfiguration-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/assignments/{enrollmentConfigurationAssignmentId}](https://docs.microsoft.com/graph/api/intune-onboarding-enrollmentconfigurationassignment-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/deviceManagementPartners/{deviceManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementpartner-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/exchangeConnectors/{deviceManagementExchangeConnectorId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeconnector-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/exchangeOnPremisesPolicies/{deviceManagementExchangeOnPremisesPolicyId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeonpremisespolicy-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/exchangeOnPremisesPolicy](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeonpremisespolicy-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/exchangeOnPremisesPolicy/conditionalAccessSettings](https://docs.microsoft.com/graph/api/intune-onboarding-onpremisesconditionalaccesssettings-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/importedDeviceIdentities/{importedDeviceIdentityId}](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentityresult-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/mobileThreatDefenseConnectors/{mobileThreatDefenseConnectorId}](https://docs.microsoft.com/graph/api/intune-onboarding-mobilethreatdefenseconnector-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}](https://docs.microsoft.com/graph/api/intune-notification-notificationmessagetemplate-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}/localizedNotificationMessages/{localizedNotificationMessageId}](https://docs.microsoft.com/graph/api/intune-notification-localizednotificationmessage-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/remoteAssistanceSettings](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancesettings-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/reports](https://docs.microsoft.com/graph/api/intune-remoteassistance-devicemanagementreports-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}](https://docs.microsoft.com/graph/api/intune-rapolicy-windows10xtrustedrootcertificate-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}/assignments/{deviceManagementResourceAccessProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofileassignment-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/telecomExpenseManagementPartners/{telecomExpenseManagementPartnerId}](https://docs.microsoft.com/graph/api/intune-tem-telecomexpensemanagementpartner-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/termsAndConditions/{termsAndConditionsId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses/{termsAndConditionsAcceptanceStatusId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsacceptancestatus-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses/{termsAndConditionsAcceptanceStatusId}/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/termsAndConditions/{termsAndConditionsId}/assignments/{termsAndConditionsAssignmentId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsassignment-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments/{termsAndConditionsGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsgroupassignment-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments/{termsAndConditionsGroupAssignmentId}/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/windowsAutopilotDeploymentProfiles/{windowsAutopilotDeploymentProfileId}](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignments/{windowsAutopilotDeploymentProfileAssignmentId}](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeploymentprofileassignment-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/microsoft.graph.activeDirectoryWindowsAutopilotDeploymentProfile/domainJoinConfiguration](https://docs.microsoft.com/graph/api/intune-enrollment-windowsdomainjoinconfiguration-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/intendedDeploymentProfile](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/windowsAutopilotSettings](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotsettings-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /organization/{organizationId}](https://docs.microsoft.com/graph/api/intune-onboarding-organization-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{usersId}](https://docs.microsoft.com/graph/api/intune-onboarding-user-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceAppManagement/sideLoadingKeys](https://docs.microsoft.com/graph/api/intune-onboarding-sideloadingkey-create?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceAppManagement/vppTokens](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-create?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceAppManagement/vppTokens/{vppTokenId}/revokeLicenses](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-revokelicenses?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceAppManagement/vppTokens/{vppTokenId}/syncLicenses](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-synclicenses?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceAppManagement/vppTokens/syncLicenseCounts](https://docs.microsoft.com/graph/api/intune-onboarding-vpptoken-synclicensecounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/applePushNotificationCertificate/generateApplePushNotificationCertificateSigningRequest](https://docs.microsoft.com/graph/api/intune-devices-applepushnotificationcertificate-generateapplepushnotificationcertificatesigningrequest?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/appleUserInitiatedEnrollmentProfiles](https://docs.microsoft.com/graph/api/intune-enrollment-appleuserinitiatedenrollmentprofile-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}/assignments](https://docs.microsoft.com/graph/api/intune-enrollment-appleenrollmentprofileassignment-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/appleUserInitiatedEnrollmentProfiles/{appleUserInitiatedEnrollmentProfileId}/setPriority](https://docs.microsoft.com/graph/api/intune-enrollment-appleuserinitiatedenrollmentprofile-setpriority?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/complianceManagementPartners](https://docs.microsoft.com/graph/api/intune-onboarding-compliancemanagementpartner-create?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/dataSharingConsents](https://docs.microsoft.com/graph/api/intune-devices-datasharingconsent-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/dataSharingConsents/{dataSharingConsentId}/consentToDataSharing](https://docs.microsoft.com/graph/api/intune-devices-datasharingconsent-consenttodatasharing?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles/{enrollmentProfileId}/setDefaultProfile](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-setdefaultprofile?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/enrollmentProfiles/{enrollmentProfileId}/updateDeviceProfileAssignment](https://docs.microsoft.com/graph/api/intune-enrollment-enrollmentprofile-updatedeviceprofileassignment?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/generateEncryptionPublicKey](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-generateencryptionpublickey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/importedAppleDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importedappledeviceidentity-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/importedAppleDeviceIdentities/importAppleDeviceIdentityList](https://docs.microsoft.com/graph/api/intune-enrollment-importedappledeviceidentity-importappledeviceidentitylist?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/shareForSchoolDataSyncService](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-shareforschooldatasyncservice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/syncWithAppleDeviceEnrollmentProgram](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-syncwithappledeviceenrollmentprogram?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/unshareForSchoolDataSyncService](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-unshareforschooldatasyncservice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/depOnboardingSettings/{depOnboardingSettingId}/uploadDepToken](https://docs.microsoft.com/graph/api/intune-enrollment-deponboardingsetting-uploaddeptoken?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/derivedCredentials](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementderivedcredentialsettings-create?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/deviceEnrollmentConfigurations](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentplatformrestrictionsconfiguration-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/assign](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentconfiguration-assign?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/assignments](https://docs.microsoft.com/graph/api/intune-onboarding-enrollmentconfigurationassignment-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/deviceEnrollmentConfigurations/{deviceEnrollmentConfigurationId}/setPriority](https://docs.microsoft.com/graph/api/intune-onboarding-deviceenrollmentconfiguration-setpriority?view=graph-rest-1.0&tabs=http)|
|Beta||[POST /deviceManagement/deviceEnrollmentConfigurations/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-deviceenrollmentconfiguration-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/deviceManagementPartners](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementpartner-create?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/enableUnlicensedAdminstrators](https://docs.microsoft.com/graph/api/intune-deviceconfig-devicemanagement-enableunlicensedadminstrators?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/exchangeConnectors](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeconnector-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/exchangeConnectors/{deviceManagementExchangeConnectorId}/sync](https://docs.microsoft.com/graph/api/intune-onboarding-devicemanagementexchangeconnector-sync?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/importedDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentityresult-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/importedDeviceIdentities/importDeviceIdentityList](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentity-importdeviceidentitylist?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/importedDeviceIdentities/searchExistingIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importeddeviceidentity-searchexistingidentities?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/importedWindowsAutopilotDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-importedwindowsautopilotdeviceidentity-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/importedWindowsAutopilotDeviceIdentities/import](https://docs.microsoft.com/graph/api/intune-enrollment-importedwindowsautopilotdeviceidentity-import?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/mobileThreatDefenseConnectors](https://docs.microsoft.com/graph/api/intune-onboarding-mobilethreatdefenseconnector-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/notificationMessageTemplates](https://docs.microsoft.com/graph/api/intune-notification-notificationmessagetemplate-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}/localizedNotificationMessages](https://docs.microsoft.com/graph/api/intune-notification-localizednotificationmessage-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/notificationMessageTemplates/{notificationMessageTemplateId}/sendTestMessage](https://docs.microsoft.com/graph/api/intune-notification-notificationmessagetemplate-sendtestmessage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/remoteAssistancePartners](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}/beginOnboarding](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-beginonboarding?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}/disconnect](https://docs.microsoft.com/graph/api/intune-remoteassistance-remoteassistancepartner-disconnect?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/reports/getRemoteAssistanceSessionsReport](https://docs.microsoft.com/graph/api/intune-remoteassistance-devicemanagementreports-getremoteassistancesessionsreport?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/resourceAccessProfiles](https://docs.microsoft.com/graph/api/intune-rapolicy-windows10xtrustedrootcertificate-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}/assign](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofilebase-assign?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/resourceAccessProfiles/{deviceManagementResourceAccessProfileBaseId}/assignments](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofileassignment-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/resourceAccessProfiles/queryByPlatformType](https://docs.microsoft.com/graph/api/intune-rapolicy-devicemanagementresourceaccessprofilebase-querybyplatformtype?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/telecomExpenseManagementPartners](https://docs.microsoft.com/graph/api/intune-tem-telecomexpensemanagementpartner-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/termsAndConditions](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditions-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/termsAndConditions/{termsAndConditionsId}/acceptanceStatuses](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsacceptancestatus-create?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/termsAndConditions/{termsAndConditionsId}/assignments](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsassignment-create?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/termsAndConditions/{termsAndConditionsId}/groupAssignments](https://docs.microsoft.com/graph/api/intune-companyterms-termsandconditionsgroupassignment-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeploymentProfiles](https://docs.microsoft.com/graph/api/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeploymentProfiles/{windowsAutopilotDeploymentProfileId}/assign](https://docs.microsoft.com/graph/api/intune-shared-windowsautopilotdeploymentprofile-assign?view=graph-rest-beta&tabs=http)|
|Beta||[POST /deviceManagement/windowsAutopilotDeploymentProfiles/hasPayloadLinks](https://docs.microsoft.com/graph/api/intune-shared-windowsautopilotdeploymentprofile-haspayloadlinks?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-create?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/assignResourceAccountToDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-assignresourceaccounttodevice?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/assignUserToDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-assignusertodevice?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assign](https://docs.microsoft.com/graph/api/intune-shared-windowsautopilotdeploymentprofile-assign?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}/assignResourceAccountToDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-assignresourceaccounttodevice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}/assignUserToDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-assignusertodevice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}/unassignResourceAccountFromDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-unassignresourceaccountfromdevice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}/unassignUserFromDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-unassignuserfromdevice?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignedDevices/{windowsAutopilotDeviceIdentityId}/updateDeviceProperties](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-updatedeviceproperties?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/deploymentProfile/assignments](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeploymentprofileassignment-create?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/intendedDeploymentProfile/assign](https://docs.microsoft.com/graph/api/intune-shared-windowsautopilotdeploymentprofile-assign?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/unassignResourceAccountFromDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-unassignresourceaccountfromdevice?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/unassignUserFromDevice](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-unassignuserfromdevice?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/windowsAutopilotDeviceIdentities/{windowsAutopilotDeviceIdentityId}/updateDeviceProperties](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotdeviceidentity-updatedeviceproperties?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/windowsAutopilotSettings/sync](https://docs.microsoft.com/graph/api/intune-enrollment-windowsautopilotsettings-sync?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /organization/{organizationId}/setMobileDeviceManagementAuthority](https://docs.microsoft.com/graph/api/intune-onboarding-organization-setmobiledevicemanagementauthority?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users](https://docs.microsoft.com/graph/api/intune-onboarding-user-create?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|662ed50a-ac44-4eef-ad86-62eed9be2a29|
|**Consent Type**|Admin|
|**Display String**|Read and write Microsoft Intune configuration|
|**Description**|Allows the app to read and write Microsoft Intune service properties including device enrollment and third party service connection configuration.|
## Application Permission
|||
|-|-|
|**Id**|5ac13192-7ace-4fcf-b828-1a26f28068ee|
|**Display String**|Read and write Microsoft Intune configuration|
|**Description**|Allows the app to read and write Microsoft Intune service properties including device enrollment and third party service connection configuration, without a signed-in user.|
## Resources
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-companyterms-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
### [termsAndConditions ](https://docs.microsoft.com/graph/api/resources/intune-companyterms-termsandconditions?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the T&C policy.|
|createdDateTime|DateTimeOffset|DateTime the object was created.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|displayName|String|Administrator-supplied name for the T&C policy. |
|description|String|Administrator-supplied description of the T&C policy.|
|title|String|Administrator-supplied title of the terms and conditions. This is shown to the user on prompts to accept the T&C policy.|
|bodyText|String|Administrator-supplied body text of the terms and conditions, typically the terms themselves. This is shown to the user on prompts to accept the T&C policy.|
|acceptanceStatement|String|Administrator-supplied explanation of the terms and conditions, typically describing what it means to accept the terms and conditions set out in the T&C policy. This is shown to the user on prompts to accept the T&C policy.|
|version|Int32|Integer indicating the current version of the terms. Incremented when an administrator makes a change to the terms and wishes to require users to re-accept the modified T&C policy.|
### [termsAndConditionsAcceptanceStatus ](https://docs.microsoft.com/graph/api/resources/intune-companyterms-termsandconditionsacceptancestatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the entity.|
|userDisplayName|String|Display name of the user whose acceptance the entity represents.|
|acceptedVersion|Int32|Most recent version number of the T&C accepted by the user.|
|acceptedDateTime|DateTimeOffset|DateTime when the terms were last accepted by the user.|
|userPrincipalName|String|The userPrincipalName of the User that accepted the term.|
### [termsAndConditionsAssignment ](https://docs.microsoft.com/graph/api/resources/intune-companyterms-termsandconditionsassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the entity.|
|target|deviceAndAppManagementAssignmentTarget|Assignment target that the T&C policy is assigned to.|
### [termsAndConditionsGroupAssignment ](https://docs.microsoft.com/graph/api/resources/intune-companyterms-termsandconditionsgroupassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the entity.|
|targetGroupId|String|Unique identifier of a group that the T&C policy is assigned to.|
### [applePushNotificationCertificate ](https://docs.microsoft.com/graph/api/resources/intune-devices-applepushnotificationcertificate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the certificate|
|appleIdentifier|String|Apple Id of the account used to create the MDM push certificate.|
|topicIdentifier|String|Topic Id.|
|lastModifiedDateTime|DateTimeOffset|Last modified date and time for Apple push notification certificate.|
|expirationDateTime|DateTimeOffset|The expiration date and time for Apple push notification certificate.|
|certificateUploadStatus|String|The certificate upload status.|
|certificateUploadFailureReason|String|The reason the certificate upload failed.|
|certificateSerialNumber|String|Certificate serial number. This property is read-only.|
|certificate|String|Not yet documented|
### [dataSharingConsent ](https://docs.microsoft.com/graph/api/resources/intune-devices-datasharingconsent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The data sharing consent Id|
|serviceDisplayName|String|The display name of the service work flow|
|termsUrl|String|The TermsUrl for the data sharing consent|
|granted|Boolean|The granted state for the data sharing consent|
|grantDateTime|DateTimeOffset|The time consent was granted for this account|
|grantedByUpn|String|The Upn of the user that granted consent for this account|
|grantedByUserId|String|The UserId of the user that granted consent for this account|
### [activeDirectoryWindowsAutopilotDeploymentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-activedirectorywindowsautopilotdeploymentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile Key Inherited from windowsAutopilotDeploymentProfile|
|displayName|String|The display name of the deployment profile. Max allowed length is 200 chars. Returned by default. Supports: $select, $top, $skip, $orderby. $Search and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|description|String|A description of the deployment profile. Max allowed length is 1500 chars. Supports: $select, $top, $skip, $orderBy. $Search and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|language|String|The language code to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use locale instead. Inherited from windowsAutopilotDeploymentProfile|
|locale|String|The locale (language) to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|createdDateTime|DateTimeOffset|The date and time of when the deployment profile was created. The value cannot be modified and is automatically populated when the profile was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Inherited from windowsAutopilotDeploymentProfile|
|lastModifiedDateTime|DateTimeOffset|The date and time of when the deployment profile was last modified. The value cannot be updated manually and is automatically populated when any changes are made to the profile. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported Read-Only. Inherited from windowsAutopilotDeploymentProfile|
|outOfBoxExperienceSettings|outOfBoxExperienceSettings|The Windows Autopilot Deployment Profile settings used by the Autopilot device for out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use outOfBoxExperienceSetting instead. Inherited from windowsAutopilotDeploymentProfile|
|outOfBoxExperienceSetting|outOfBoxExperienceSetting|The Windows Autopilot Deployment Profile settings used by the device for the out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|enrollmentStatusScreenSettings|windowsEnrollmentStatusScreenSettings|Enrollment status screen setting Inherited from windowsAutopilotDeploymentProfile|
|extractHardwareHash|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use hardwareHashExtractionEnabled instead. Inherited from windowsAutopilotDeploymentProfile|
|hardwareHashExtractionEnabled|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|deviceNameTemplate|String|The template used to name the Autopilot device. This can be a custom text and can also contain either the serial number of the device, or a randomly generated number. The total length of the text generated by the template can be no more than 15 characters. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|deviceType|windowsAutopilotDeviceType|The Windows device type that this profile is applicable to. Possible values include windowsPc, holoLens, and virtualMachine. The default is windowsPc. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile. Possible values are: `windowsPc`, `holoLens`, `surfaceHub2`, `surfaceHub2S`, `virtualMachine`, `unknownFutureValue`.|
|enableWhiteGlove|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode is allowed. When false, Windows Autopilot for pre-provisioned deployment mode is not allowed. The default is FALSE. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use preprovisioningAllowed instead. Inherited from windowsAutopilotDeploymentProfile|
|preprovisioningAllowed|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode for OOBE is allowed to be used. When false, Windows Autopilot for pre-provisioned deployment mode for OOBE is not allowed. The default is FALSE. Inherited from windowsAutopilotDeploymentProfile|
|roleScopeTagIds|String collection|List of role scope tags for the deployment profile.  Inherited from windowsAutopilotDeploymentProfile|
|managementServiceAppId|String|The Entra management service App ID which gets used during client device-based enrollment discovery. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|hybridAzureADJoinSkipConnectivityCheck|Boolean|The Autopilot Hybrid Azure AD join flow will continue even if it does not establish domain controller connectivity during OOBE.|
### [appleEnrollmentProfileAssignment ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-appleenrollmentprofileassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key of the assignment.|
|target|deviceAndAppManagementAssignmentTarget|The assignment target for the Apple user initiated deployment profile.|
### [appleOwnerTypeEnrollmentType ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-appleownertypeenrollmenttype?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|ownerType|managedDeviceOwnerType|The owner type. Possible values are: `unknown`, `company`, `personal`.|
|enrollmentType|appleUserInitiatedEnrollmentType|The enrollment type. Possible values are: `unknown`, `device`, `user`, `accountDrivenUserEnrollment`, `webDeviceEnrollment`, `unknownFutureValue`.|
### [appleUserInitiatedEnrollmentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-appleuserinitiatedenrollmentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|defaultEnrollmentType|appleUserInitiatedEnrollmentType|The default profile enrollment type. Possible values are: `unknown`, `device`, `user`, `accountDrivenUserEnrollment`, `webDeviceEnrollment`, `unknownFutureValue`.|
|availableEnrollmentTypeOptions|appleOwnerTypeEnrollmentType collection|List of available enrollment type options|
|id|String|The GUID for the object|
|displayName|String|Name of the profile|
|description|String|Description of the profile|
|priority|Int32|Priority, 0 is highest|
|platform|devicePlatformType|The platform of the Device. Possible values are: `android`, `androidForWork`, `iOS`, `macOS`, `windowsPhone81`, `windows81AndLater`, `windows10AndLater`, `androidWorkProfile`, `unknown`, `androidAOSP`, `androidMobileApplicationManagement`, `iOSMobileApplicationManagement`, `unknownFutureValue`.|
|createdDateTime|DateTimeOffset|Profile creation time|
|lastModifiedDateTime|DateTimeOffset|Profile last modified time|
### [intune-enrollment-appleuserinitiatedenrollmenttype](https://docs.microsoft.com/graph/api/resources/intune-enrollment-appleuserinitiatedenrollmenttype?view=graph-rest-1.0&tabs=http)

### [azureADWindowsAutopilotDeploymentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-azureadwindowsautopilotdeploymentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile Key Inherited from windowsAutopilotDeploymentProfile|
|displayName|String|The display name of the deployment profile. Max allowed length is 200 chars. Returned by default. Supports: $select, $top, $skip, $orderby. $Search and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|description|String|A description of the deployment profile. Max allowed length is 1500 chars. Supports: $select, $top, $skip, $orderBy. $Search and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|language|String|The language code to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use locale instead. Inherited from windowsAutopilotDeploymentProfile|
|locale|String|The locale (language) to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|createdDateTime|DateTimeOffset|The date and time of when the deployment profile was created. The value cannot be modified and is automatically populated when the profile was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Inherited from windowsAutopilotDeploymentProfile|
|lastModifiedDateTime|DateTimeOffset|The date and time of when the deployment profile was last modified. The value cannot be updated manually and is automatically populated when any changes are made to the profile. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported Read-Only. Inherited from windowsAutopilotDeploymentProfile|
|outOfBoxExperienceSettings|outOfBoxExperienceSettings|The Windows Autopilot Deployment Profile settings used by the Autopilot device for out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use outOfBoxExperienceSetting instead. Inherited from windowsAutopilotDeploymentProfile|
|outOfBoxExperienceSetting|outOfBoxExperienceSetting|The Windows Autopilot Deployment Profile settings used by the device for the out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|enrollmentStatusScreenSettings|windowsEnrollmentStatusScreenSettings|Enrollment status screen setting Inherited from windowsAutopilotDeploymentProfile|
|extractHardwareHash|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use hardwareHashExtractionEnabled instead. Inherited from windowsAutopilotDeploymentProfile|
|hardwareHashExtractionEnabled|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|deviceNameTemplate|String|The template used to name the Autopilot device. This can be a custom text and can also contain either the serial number of the device, or a randomly generated number. The total length of the text generated by the template can be no more than 15 characters. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
|deviceType|windowsAutopilotDeviceType|The Windows device type that this profile is applicable to. Possible values include windowsPc, holoLens, and virtualMachine. The default is windowsPc. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile. Possible values are: `windowsPc`, `holoLens`, `surfaceHub2`, `surfaceHub2S`, `virtualMachine`, `unknownFutureValue`.|
|enableWhiteGlove|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode is allowed. When false, Windows Autopilot for pre-provisioned deployment mode is not allowed. The default is FALSE. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use preprovisioningAllowed instead. Inherited from windowsAutopilotDeploymentProfile|
|preprovisioningAllowed|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode for OOBE is allowed to be used. When false, Windows Autopilot for pre-provisioned deployment mode for OOBE is not allowed. The default is FALSE. Inherited from windowsAutopilotDeploymentProfile|
|roleScopeTagIds|String collection|List of role scope tags for the deployment profile.  Inherited from windowsAutopilotDeploymentProfile|
|managementServiceAppId|String|The Entra management service App ID which gets used during client device-based enrollment discovery. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Inherited from windowsAutopilotDeploymentProfile|
### [depEnrollmentBaseProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-depenrollmentbaseprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object Inherited from enrollmentProfile|
|displayName|String|Name of the profile Inherited from enrollmentProfile|
|description|String|Description of the profile Inherited from enrollmentProfile|
|requiresUserAuthentication|Boolean|Indicates if the profile requires user authentication Inherited from enrollmentProfile|
|configurationEndpointUrl|String|Configuration endpoint url to use for Enrollment Inherited from enrollmentProfile|
|enableAuthenticationViaCompanyPortal|Boolean|Indicates to authenticate with Apple Setup Assistant instead of Company Portal. Inherited from enrollmentProfile|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|Indicates that Company Portal is required on setup assistant enrolled devices Inherited from enrollmentProfile|
|isDefault|Boolean|Indicates if this is the default profile|
|supervisedModeEnabled|Boolean|Supervised mode, True to enable, false otherwise. See https://learn.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune for additional information.|
|supportDepartment|String|Support department information|
|isMandatory|Boolean|Indicates if the profile is mandatory|
|locationDisabled|Boolean|Indicates if Location service setup pane is disabled|
|supportPhoneNumber|String|Support phone number|
|profileRemovalDisabled|Boolean|Indicates if the profile removal option is disabled|
|restoreBlocked|Boolean|Indicates if Restore setup pane is blocked|
|appleIdDisabled|Boolean|Indicates if Apple id setup pane is disabled|
|termsAndConditionsDisabled|Boolean|Indicates if 'Terms and Conditions' setup pane is disabled|
|touchIdDisabled|Boolean|Indicates if touch id setup pane is disabled|
|applePayDisabled|Boolean|Indicates if Apple pay setup pane is disabled|
|siriDisabled|Boolean|Indicates if siri setup pane is disabled|
|diagnosticsDisabled|Boolean|Indicates if diagnostics setup pane is disabled|
|displayToneSetupDisabled|Boolean|Indicates if displaytone setup screen is disabled|
|privacyPaneDisabled|Boolean|Indicates if privacy screen is disabled|
|screenTimeScreenDisabled|Boolean|Indicates if screen timeout setup is disabled|
|deviceNameTemplate|String|Sets a literal or name pattern.|
|configurationWebUrl|Boolean|URL for setup assistant login|
|enabledSkipKeys|String collection|enabledSkipKeys contains all the enabled skip keys as strings|
|enrollmentTimeAzureAdGroupIds|Guid collection|EnrollmentTimeAzureAdGroupIds contains list of enrollment time Azure Group Ids to be associated with profile|
|waitForDeviceConfiguredConfirmation|Boolean|Indicates if the device will need to wait for configured confirmation|
### [depEnrollmentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-depenrollmentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object Inherited from enrollmentProfile|
|displayName|String|Name of the profile Inherited from enrollmentProfile|
|description|String|Description of the profile Inherited from enrollmentProfile|
|requiresUserAuthentication|Boolean|Indicates if the profile requires user authentication Inherited from enrollmentProfile|
|configurationEndpointUrl|String|Configuration endpoint url to use for Enrollment Inherited from enrollmentProfile|
|enableAuthenticationViaCompanyPortal|Boolean|Indicates to authenticate with Apple Setup Assistant instead of Company Portal. Inherited from enrollmentProfile|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|Indicates that Company Portal is required on setup assistant enrolled devices Inherited from enrollmentProfile|
|isDefault|Boolean|Indicates if this is the default profile|
|supervisedModeEnabled|Boolean|Supervised mode, True to enable, false otherwise. See https://learn.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune for additional information.|
|supportDepartment|String|Support department information|
|passCodeDisabled|Boolean|Indicates if Passcode setup pane is disabled|
|isMandatory|Boolean|Indicates if the profile is mandatory|
|locationDisabled|Boolean|Indicates if Location service setup pane is disabled|
|supportPhoneNumber|String|Support phone number|
|iTunesPairingMode|iTunesPairingMode|Indicates the iTunes pairing mode. Possible values are: `disallow`, `allow`, `requiresCertificate`.|
|profileRemovalDisabled|Boolean|Indicates if the profile removal option is disabled|
|managementCertificates|managementCertificateWithThumbprint collection|Management certificates for Apple Configurator|
|restoreBlocked|Boolean|Indicates if Restore setup pane is blocked|
|restoreFromAndroidDisabled|Boolean|Indicates if Restore from Android is disabled|
|appleIdDisabled|Boolean|Indicates if Apple id setup pane is disabled|
|termsAndConditionsDisabled|Boolean|Indicates if 'Terms and Conditions' setup pane is disabled|
|touchIdDisabled|Boolean|Indicates if touch id setup pane is disabled|
|applePayDisabled|Boolean|Indicates if Apple pay setup pane is disabled|
|zoomDisabled|Boolean|Indicates if zoom setup pane is disabled|
|siriDisabled|Boolean|Indicates if siri setup pane is disabled|
|diagnosticsDisabled|Boolean|Indicates if diagnostics setup pane is disabled|
|macOSRegistrationDisabled|Boolean|Indicates if Mac OS registration is disabled|
|macOSFileVaultDisabled|Boolean|Indicates if Mac OS file vault is disabled|
|awaitDeviceConfiguredConfirmation|Boolean|Indicates if the device will need to wait for configured confirmation|
|sharedIPadMaximumUserCount|Int32|This specifies the maximum number of users that can use a shared iPad. Only applicable in shared iPad mode.|
|enableSharedIPad|Boolean|This indicates whether the device is to be enrolled in a mode which enables multi user scenarios. Only applicable in shared iPads.|
### [depIOSEnrollmentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-depiosenrollmentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object Inherited from enrollmentProfile|
|displayName|String|Name of the profile Inherited from enrollmentProfile|
|description|String|Description of the profile Inherited from enrollmentProfile|
|requiresUserAuthentication|Boolean|Indicates if the profile requires user authentication Inherited from enrollmentProfile|
|configurationEndpointUrl|String|Configuration endpoint url to use for Enrollment Inherited from enrollmentProfile|
|enableAuthenticationViaCompanyPortal|Boolean|Indicates to authenticate with Apple Setup Assistant instead of Company Portal. Inherited from enrollmentProfile|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|Indicates that Company Portal is required on setup assistant enrolled devices Inherited from enrollmentProfile|
|isDefault|Boolean|Indicates if this is the default profile Inherited from depEnrollmentBaseProfile|
|supervisedModeEnabled|Boolean|Supervised mode, True to enable, false otherwise. See https://learn.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune for additional information. Inherited from depEnrollmentBaseProfile|
|supportDepartment|String|Support department information Inherited from depEnrollmentBaseProfile|
|isMandatory|Boolean|Indicates if the profile is mandatory Inherited from depEnrollmentBaseProfile|
|locationDisabled|Boolean|Indicates if Location service setup pane is disabled Inherited from depEnrollmentBaseProfile|
|supportPhoneNumber|String|Support phone number Inherited from depEnrollmentBaseProfile|
|profileRemovalDisabled|Boolean|Indicates if the profile removal option is disabled Inherited from depEnrollmentBaseProfile|
|restoreBlocked|Boolean|Indicates if Restore setup pane is blocked Inherited from depEnrollmentBaseProfile|
|appleIdDisabled|Boolean|Indicates if Apple id setup pane is disabled Inherited from depEnrollmentBaseProfile|
|termsAndConditionsDisabled|Boolean|Indicates if 'Terms and Conditions' setup pane is disabled Inherited from depEnrollmentBaseProfile|
|touchIdDisabled|Boolean|Indicates if touch id setup pane is disabled Inherited from depEnrollmentBaseProfile|
|applePayDisabled|Boolean|Indicates if Apple pay setup pane is disabled Inherited from depEnrollmentBaseProfile|
|siriDisabled|Boolean|Indicates if siri setup pane is disabled Inherited from depEnrollmentBaseProfile|
|diagnosticsDisabled|Boolean|Indicates if diagnostics setup pane is disabled Inherited from depEnrollmentBaseProfile|
|displayToneSetupDisabled|Boolean|Indicates if displaytone setup screen is disabled Inherited from depEnrollmentBaseProfile|
|privacyPaneDisabled|Boolean|Indicates if privacy screen is disabled Inherited from depEnrollmentBaseProfile|
|screenTimeScreenDisabled|Boolean|Indicates if screen timeout setup is disabled Inherited from depEnrollmentBaseProfile|
|deviceNameTemplate|String|Sets a literal or name pattern. Inherited from depEnrollmentBaseProfile|
|configurationWebUrl|Boolean|URL for setup assistant login Inherited from depEnrollmentBaseProfile|
|enabledSkipKeys|String collection|enabledSkipKeys contains all the enabled skip keys as strings Inherited from depEnrollmentBaseProfile|
|enrollmentTimeAzureAdGroupIds|Guid collection|EnrollmentTimeAzureAdGroupIds contains list of enrollment time Azure Group Ids to be associated with profile Inherited from depEnrollmentBaseProfile|
|waitForDeviceConfiguredConfirmation|Boolean|Indicates if the device will need to wait for configured confirmation Inherited from depEnrollmentBaseProfile|
|iTunesPairingMode|iTunesPairingMode|Indicates the iTunes pairing mode. Possible values are: `disallow`, `allow`, `requiresCertificate`.|
|managementCertificates|managementCertificateWithThumbprint collection|Management certificates for Apple Configurator|
|restoreFromAndroidDisabled|Boolean|Indicates if Restore from Android is disabled|
|awaitDeviceConfiguredConfirmation|Boolean|Indicates if the device will need to wait for configured confirmation|
|sharedIPadMaximumUserCount|Int32|This specifies the maximum number of users that can use a shared iPad. Only applicable in shared iPad mode.|
|enableSharedIPad|Boolean|This indicates whether the device is to be enrolled in a mode which enables multi user scenarios. Only applicable in shared iPads.|
|companyPortalVppTokenId|String|If set, indicates which Vpp token should be used to deploy the Company Portal w/ device licensing. 'enableAuthenticationViaCompanyPortal' must be set in order for this property to be set.|
|enableSingleAppEnrollmentMode|Boolean|Tells the device to enable single app mode and apply app-lock during enrollment. Default is false. 'enableAuthenticationViaCompanyPortal' and 'companyPortalVppTokenId' must be set for this property to be set.|
|homeButtonScreenDisabled|Boolean|Indicates if home button sensitivity screen is disabled|
|iMessageAndFaceTimeScreenDisabled|Boolean|Indicates if iMessage and FaceTime screen is disabled|
|onBoardingScreenDisabled|Boolean|Indicates if onboarding setup screen is disabled|
|simSetupScreenDisabled|Boolean|Indicates if the SIMSetup screen is disabled|
|softwareUpdateScreenDisabled|Boolean|Indicates if the mandatory sofware update screen is disabled|
|watchMigrationScreenDisabled|Boolean|Indicates if the watch migration screen is disabled|
|appearanceScreenDisabled|Boolean|Indicates if Apperance screen is disabled|
|expressLanguageScreenDisabled|Boolean|Indicates if Express Language screen is disabled|
|preferredLanguageScreenDisabled|Boolean|Indicates if Preferred language screen is disabled|
|deviceToDeviceMigrationDisabled|Boolean|Indicates if Device To Device Migration is disabled|
|welcomeScreenDisabled|Boolean|Indicates if Weclome screen is disabled|
|passCodeDisabled|Boolean|Indicates if Passcode setup pane is disabled|
|zoomDisabled|Boolean|Indicates if zoom setup pane is disabled|
|restoreCompletedScreenDisabled|Boolean|Indicates if Weclome screen is disabled|
|updateCompleteScreenDisabled|Boolean|Indicates if Weclome screen is disabled|
|forceTemporarySession|Boolean|Indicates if temporary sessions is enabled|
|temporarySessionTimeoutInSeconds|Int32|Indicates timeout of temporary session|
|userSessionTimeoutInSeconds|Int32|Indicates timeout of temporary session|
|passcodeLockGracePeriodInSeconds|Int32|Indicates timeout before locked screen requires the user to enter the device passocde to unlock it|
|carrierActivationUrl|String|Carrier URL for activating device eSIM.|
|userlessSharedAadModeEnabled|Boolean|Indicates that this apple device is designated to support 'shared device mode' scenarios. This is distinct from the 'shared iPad' scenario. See https://learn.microsoft.com/mem/intune/enrollment/device-enrollment-shared-ios|

### [depMacOSEnrollmentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-depmacosenrollmentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object Inherited from enrollmentProfile|
|displayName|String|Name of the profile Inherited from enrollmentProfile|
|description|String|Description of the profile Inherited from enrollmentProfile|
|requiresUserAuthentication|Boolean|Indicates if the profile requires user authentication Inherited from enrollmentProfile|
|configurationEndpointUrl|String|Configuration endpoint url to use for Enrollment Inherited from enrollmentProfile|
|enableAuthenticationViaCompanyPortal|Boolean|Indicates to authenticate with Apple Setup Assistant instead of Company Portal. Inherited from enrollmentProfile|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|Indicates that Company Portal is required on setup assistant enrolled devices Inherited from enrollmentProfile|
|isDefault|Boolean|Indicates if this is the default profile Inherited from depEnrollmentBaseProfile|
|supervisedModeEnabled|Boolean|Supervised mode, True to enable, false otherwise. See https://learn.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune for additional information. Inherited from depEnrollmentBaseProfile|
|supportDepartment|String|Support department information Inherited from depEnrollmentBaseProfile|
|isMandatory|Boolean|Indicates if the profile is mandatory Inherited from depEnrollmentBaseProfile|
|locationDisabled|Boolean|Indicates if Location service setup pane is disabled Inherited from depEnrollmentBaseProfile|
|supportPhoneNumber|String|Support phone number Inherited from depEnrollmentBaseProfile|
|profileRemovalDisabled|Boolean|Indicates if the profile removal option is disabled Inherited from depEnrollmentBaseProfile|
|restoreBlocked|Boolean|Indicates if Restore setup pane is blocked Inherited from depEnrollmentBaseProfile|
|appleIdDisabled|Boolean|Indicates if Apple id setup pane is disabled Inherited from depEnrollmentBaseProfile|
|termsAndConditionsDisabled|Boolean|Indicates if 'Terms and Conditions' setup pane is disabled Inherited from depEnrollmentBaseProfile|
|touchIdDisabled|Boolean|Indicates if touch id setup pane is disabled Inherited from depEnrollmentBaseProfile|
|applePayDisabled|Boolean|Indicates if Apple pay setup pane is disabled Inherited from depEnrollmentBaseProfile|
|siriDisabled|Boolean|Indicates if siri setup pane is disabled Inherited from depEnrollmentBaseProfile|
|diagnosticsDisabled|Boolean|Indicates if diagnostics setup pane is disabled Inherited from depEnrollmentBaseProfile|
|displayToneSetupDisabled|Boolean|Indicates if displaytone setup screen is disabled Inherited from depEnrollmentBaseProfile|
|privacyPaneDisabled|Boolean|Indicates if privacy screen is disabled Inherited from depEnrollmentBaseProfile|
|screenTimeScreenDisabled|Boolean|Indicates if screen timeout setup is disabled Inherited from depEnrollmentBaseProfile|
|deviceNameTemplate|String|Sets a literal or name pattern. Inherited from depEnrollmentBaseProfile|
|configurationWebUrl|Boolean|URL for setup assistant login Inherited from depEnrollmentBaseProfile|
|enabledSkipKeys|String collection|enabledSkipKeys contains all the enabled skip keys as strings Inherited from depEnrollmentBaseProfile|
|enrollmentTimeAzureAdGroupIds|Guid collection|EnrollmentTimeAzureAdGroupIds contains list of enrollment time Azure Group Ids to be associated with profile Inherited from depEnrollmentBaseProfile|
|waitForDeviceConfiguredConfirmation|Boolean|Indicates if the device will need to wait for configured confirmation Inherited from depEnrollmentBaseProfile|
|registrationDisabled|Boolean|Indicates if registration is disabled|
|fileVaultDisabled|Boolean|Indicates if file vault is disabled|
|iCloudDiagnosticsDisabled|Boolean|Indicates if iCloud Analytics screen is disabled|
|passCodeDisabled|Boolean|Indicates if Passcode setup pane is disabled|
|zoomDisabled|Boolean|Indicates if zoom setup pane is disabled|
|iCloudStorageDisabled|Boolean|Indicates if iCloud Documents and Desktop screen is disabled|
|chooseYourLockScreenDisabled|Boolean|Indicates if iCloud Documents and Desktop screen is disabled|
|accessibilityScreenDisabled|Boolean|Indicates if Accessibility screen is disabled|
|autoUnlockWithWatchDisabled|Boolean|Indicates if UnlockWithWatch screen is disabled|
|skipPrimarySetupAccountCreation|Boolean|Indicates whether Setup Assistant will skip the user interface for primary account setup|
|setPrimarySetupAccountAsRegularUser|Boolean|Indicates whether Setup Assistant will set the account as a regular user|
|dontAutoPopulatePrimaryAccountInfo|Boolean|Indicates whether Setup Assistant will auto populate the primary account information|
|primaryAccountFullName|String|Indicates what the full name for the primary account is|
|primaryAccountUserName|String|Indicates what the account name for the primary account is|
|enableRestrictEditing|Boolean|Indicates whether the user will enable blockediting|
|adminAccountUserName|String|Indicates what the user name for the admin account is|
|adminAccountFullName|String|Indicates what the full name for the admin account is|
|adminAccountPassword|String|Indicates what the password for the admin account is|
|hideAdminAccount|Boolean|Indicates whether the admin account should be hidded or not|
|requestRequiresNetworkTether|Boolean|Indicates if the device is network-tethered to run the command|
|autoAdvanceSetupEnabled|Boolean|Indicates if Setup Assistant will automatically advance through its screen|
### [depOnboardingSetting ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-deponboardingsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object|
|appleIdentifier|String|The Apple ID used to obtain the current token.|
|tokenExpirationDateTime|DateTimeOffset|When the token will expire.|
|lastModifiedDateTime|DateTimeOffset|When the service was onboarded.|
|lastSuccessfulSyncDateTime|DateTimeOffset|When the service last syned with Intune|
|lastSyncTriggeredDateTime|DateTimeOffset|When Intune last requested a sync.|
|shareTokenWithSchoolDataSyncService|Boolean|Whether or not the Dep token sharing is enabled with the School Data Sync service.|
|lastSyncErrorCode|Int32|Error code reported by Apple during last dep sync.|
|tokenType|depTokenType|Gets or sets the Dep Token Type. Possible values are: `none`, `dep`, `appleSchoolManager`.|
|tokenName|String|Friendly Name for Dep Token|
|syncedDeviceCount|Int32|Gets synced device count|
|dataSharingConsentGranted|Boolean|Consent granted for data sharing with Apple Dep Service|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance.|
### [intune-enrollment-deptokentype](https://docs.microsoft.com/graph/api/resources/intune-enrollment-deptokentype?view=graph-rest-1.0&tabs=http)

### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object.|
### [intune-enrollment-deviceplatformtype](https://docs.microsoft.com/graph/api/resources/intune-enrollment-deviceplatformtype?view=graph-rest-1.0&tabs=http)

### [intune-enrollment-discoverysource](https://docs.microsoft.com/graph/api/resources/intune-enrollment-discoverysource?view=graph-rest-1.0&tabs=http)

### [enrollmentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-enrollmentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object|
|displayName|String|Name of the profile|
|description|String|Description of the profile|
|requiresUserAuthentication|Boolean|Indicates if the profile requires user authentication|
|configurationEndpointUrl|String|Configuration endpoint url to use for Enrollment|
|enableAuthenticationViaCompanyPortal|Boolean|Indicates to authenticate with Apple Setup Assistant instead of Company Portal.|
|requireCompanyPortalOnSetupAssistantEnrolledDevices|Boolean|Indicates that Company Portal is required on setup assistant enrolled devices|
### [intune-enrollment-enrollmentstate](https://docs.microsoft.com/graph/api/resources/intune-enrollment-enrollmentstate?view=graph-rest-1.0&tabs=http)

### [importedAppleDeviceIdentity ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importedappledeviceidentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|serialNumber|String|Device serial number|
|requestedEnrollmentProfileId|String|Enrollment profile Id admin intends to apply to the device during next enrollment|
|requestedEnrollmentProfileAssignmentDateTime|DateTimeOffset|The time enrollment profile was assigned to the device|
|isSupervised|Boolean|Indicates if the Apple device is supervised. |
|discoverySource|discoverySource|Apple device discovery source. Possible values are: `unknown`, `adminImport`, `deviceEnrollmentProgram`.|
|isDeleted|Boolean|Indicates if the device is deleted from Apple Business Manager|
|createdDateTime|DateTimeOffset|Created Date Time of the device|
|lastContactedDateTime|DateTimeOffset|Last Contacted Date Time of the device|
|description|String|The description of the device|
|enrollmentState|enrollmentState|The state of the device in Intune. Possible values are: `unknown`, `enrolled`, `pendingReset`, `failed`, `notContacted`, `blocked`.|
|platform|platform|The platform of the Device. Possible values are: `unknown`, `ios`, `android`, `windows`, `windowsMobile`, `macOS`.|
### [importedAppleDeviceIdentityResult ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importedappledeviceidentityresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from importedAppleDeviceIdentity|
|serialNumber|String|Device serial number Inherited from importedAppleDeviceIdentity|
|requestedEnrollmentProfileId|String|Enrollment profile Id admin intends to apply to the device during next enrollment Inherited from importedAppleDeviceIdentity|
|requestedEnrollmentProfileAssignmentDateTime|DateTimeOffset|The time enrollment profile was assigned to the device Inherited from importedAppleDeviceIdentity|
|isSupervised|Boolean|Indicates if the Apple device is supervised.  Inherited from importedAppleDeviceIdentity|
|discoverySource|discoverySource|Apple device discovery source. Inherited from importedAppleDeviceIdentity. Possible values are: `unknown`, `adminImport`, `deviceEnrollmentProgram`.|
|isDeleted|Boolean|Indicates if the device is deleted from Apple Business Manager Inherited from importedAppleDeviceIdentity|
|createdDateTime|DateTimeOffset|Created Date Time of the device Inherited from importedAppleDeviceIdentity|
|lastContactedDateTime|DateTimeOffset|Last Contacted Date Time of the device Inherited from importedAppleDeviceIdentity|
|description|String|The description of the device Inherited from importedAppleDeviceIdentity|
|enrollmentState|enrollmentState|The state of the device in Intune Inherited from importedAppleDeviceIdentity. Possible values are: `unknown`, `enrolled`, `pendingReset`, `failed`, `notContacted`, `blocked`.|
|platform|platform|The platform of the Device. Inherited from importedAppleDeviceIdentity. Possible values are: `unknown`, `ios`, `android`, `windows`, `windowsMobile`, `macOS`.|
|status|Boolean|Status of imported device identity|
### [importedDeviceIdentity ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importeddeviceidentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Id of the imported device identity|
|importedDeviceIdentifier|String|Imported Device Identifier|
|importedDeviceIdentityType|importedDeviceIdentityType|Type of Imported Device Identity. Possible values are: `unknown`, `imei`, `serialNumber`, `manufacturerModelSerial`.|
|lastModifiedDateTime|DateTimeOffset|Last Modified DateTime of the description|
|createdDateTime|DateTimeOffset|Created Date Time of the device|
|lastContactedDateTime|DateTimeOffset|Last Contacted Date Time of the device|
|description|String|The description of the device|
|enrollmentState|enrollmentState|The state of the device in Intune. Possible values are: `unknown`, `enrolled`, `pendingReset`, `failed`, `notContacted`, `blocked`.|
|platform|platform|The platform of the Device. Possible values are: `unknown`, `ios`, `android`, `windows`, `windowsMobile`, `macOS`.|
### [importedDeviceIdentityResult ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importeddeviceidentityresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Id of the imported device identity Inherited from importedDeviceIdentity|
|importedDeviceIdentifier|String|Imported Device Identifier Inherited from importedDeviceIdentity|
|importedDeviceIdentityType|importedDeviceIdentityType|Type of Imported Device Identity Inherited from importedDeviceIdentity. Possible values are: `unknown`, `imei`, `serialNumber`, `manufacturerModelSerial`.|
|lastModifiedDateTime|DateTimeOffset|Last Modified DateTime of the description Inherited from importedDeviceIdentity|
|createdDateTime|DateTimeOffset|Created Date Time of the device Inherited from importedDeviceIdentity|
|lastContactedDateTime|DateTimeOffset|Last Contacted Date Time of the device Inherited from importedDeviceIdentity|
|description|String|The description of the device Inherited from importedDeviceIdentity|
|enrollmentState|enrollmentState|The state of the device in Intune Inherited from importedDeviceIdentity. Possible values are: `unknown`, `enrolled`, `pendingReset`, `failed`, `notContacted`, `blocked`.|
|platform|platform|The platform of the Device. Inherited from importedDeviceIdentity. Possible values are: `unknown`, `ios`, `android`, `windows`, `windowsMobile`, `macOS`.|
|status|Boolean|Status of imported device identity|
### [intune-enrollment-importeddeviceidentitytype](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importeddeviceidentitytype?view=graph-rest-1.0&tabs=http)

### [importedWindowsAutopilotDeviceIdentity ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importedwindowsautopilotdeviceidentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object|
|groupTag|String|Group Tag of the Windows autopilot device.|
|serialNumber|String|Serial number of the Windows autopilot device.|
|productKey|String|Product Key of the Windows autopilot device.|
|importId|String|The Import Id of the Windows autopilot device.|
|hardwareIdentifier|Binary|Hardware Blob of the Windows autopilot device.|
|state|importedWindowsAutopilotDeviceIdentityState|Current state of the imported device.|
|assignedUserPrincipalName|String|UPN of the user the device will be assigned|
### [importedWindowsAutopilotDeviceIdentityState ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-importedwindowsautopilotdeviceidentitystate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceImportStatus|importedWindowsAutopilotDeviceIdentityImportStatus|Device status reported by Device Directory Service(DDS). Possible values are: `unknown`, `pending`, `partial`, `complete`, `error`.|
|deviceRegistrationId|String|Device Registration ID for successfully added device reported by Device Directory Service(DDS).|
|deviceErrorCode|Int32|Device error code reported by Device Directory Service(DDS).|
|deviceErrorName|String|Device error name reported by Device Directory Service(DDS).|
### [intune-enrollment-itunespairingmode](https://docs.microsoft.com/graph/api/resources/intune-enrollment-itunespairingmode?view=graph-rest-1.0&tabs=http)

### [managementCertificateWithThumbprint ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-managementcertificatewiththumbprint?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|thumbprint|String|The thumbprint of the management certificate|
|certificate|String|The Base 64 encoded management certificate|
### [outOfBoxExperienceSetting ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-outofboxexperiencesetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|privacySettingsHidden|Boolean|When TRUE, privacy settings is hidden to the end user during OOBE. When FALSE, privacy settings is shown to the end user during OOBE. Default value is FALSE.|
|eulaHidden|Boolean|When TRUE, EULA is hidden to the end user during OOBE. When FALSE, EULA is shown to the end user during OOBE. Default value is FALSE.|
|userType|windowsUserType|The type of user. Possible values are administrator and standard. Default value is administrator. Yes No. Possible values are: `administrator`, `standard`, `unknownFutureValue`.|
|deviceUsageType|windowsDeviceUsageType|The Entra join authentication type. Possible values are singleUser and shared. The default is singleUser. Possible values are: `singleUser`, `shared`, `unknownFutureValue`.|
|keyboardSelectionPageSkipped|Boolean|When TRUE, the keyboard selection page is hidden to the end user during OOBE if Language and Region are set. When FALSE, the keyboard selection page is skipped during OOBE.|
|escapeLinkHidden|Boolean|When TRUE, the link that allows user to start over with a different account on company sign-in is hidden. When false, the link that allows user to start over with a different account on company sign-in is available. Default value is FALSE.|
### [outOfBoxExperienceSettings ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-outofboxexperiencesettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|hidePrivacySettings|Boolean|Show or hide privacy settings to user|
|hideEULA|Boolean|Show or hide EULA to user|
|userType|windowsUserType|Type of user. Possible values are: `administrator`, `standard`, `unknownFutureValue`.|
|deviceUsageType|windowsDeviceUsageType|AAD join authentication type. Possible values are: `singleUser`, `shared`, `unknownFutureValue`.|
|skipKeyboardSelectionPage|Boolean|If set, then skip the keyboard selection page if Language and Region are set|
|hideEscapeLink|Boolean|If set to true, then the user can't start over with different account, on company sign-in|
### [intune-enrollment-platform](https://docs.microsoft.com/graph/api/resources/intune-enrollment-platform?view=graph-rest-1.0&tabs=http)

### [suggestedEnrollmentLimit ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-suggestedenrollmentlimit?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|suggestedDailyLimit|Int32|The suggested enrollment limit within a day|
### [windowsAutopilotDeploymentProfile ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotdeploymentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile Key|
|displayName|String|The display name of the deployment profile. Max allowed length is 200 chars. Returned by default. Supports: $select, $top, $skip, $orderby. $Search and $filter are not supported.|
|description|String|A description of the deployment profile. Max allowed length is 1500 chars. Supports: $select, $top, $skip, $orderBy. $Search and $filter are not supported.|
|language|String|The language code to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use locale instead.|
|locale|String|The locale (language) to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|createdDateTime|DateTimeOffset|The date and time of when the deployment profile was created. The value cannot be modified and is automatically populated when the profile was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only.|
|lastModifiedDateTime|DateTimeOffset|The date and time of when the deployment profile was last modified. The value cannot be updated manually and is automatically populated when any changes are made to the profile. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported Read-Only.|
|outOfBoxExperienceSettings|outOfBoxExperienceSettings|The Windows Autopilot Deployment Profile settings used by the Autopilot device for out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use outOfBoxExperienceSetting instead.|
|outOfBoxExperienceSetting|outOfBoxExperienceSetting|The Windows Autopilot Deployment Profile settings used by the device for the out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|enrollmentStatusScreenSettings|windowsEnrollmentStatusScreenSettings|Enrollment status screen setting|
|extractHardwareHash|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use hardwareHashExtractionEnabled instead.|
|hardwareHashExtractionEnabled|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|deviceNameTemplate|String|The template used to name the Autopilot device. This can be a custom text and can also contain either the serial number of the device, or a randomly generated number. The total length of the text generated by the template can be no more than 15 characters. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|deviceType|windowsAutopilotDeviceType|The Windows device type that this profile is applicable to. Possible values include windowsPc, holoLens, and virtualMachine. The default is windowsPc. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Possible values are: `windowsPc`, `holoLens`, `surfaceHub2`, `surfaceHub2S`, `virtualMachine`, `unknownFutureValue`.|
|enableWhiteGlove|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode is allowed. When false, Windows Autopilot for pre-provisioned deployment mode is not allowed. The default is FALSE. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use preprovisioningAllowed instead.|
|preprovisioningAllowed|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode for OOBE is allowed to be used. When false, Windows Autopilot for pre-provisioned deployment mode for OOBE is not allowed. The default is FALSE.|
|roleScopeTagIds|String collection|List of role scope tags for the deployment profile. |
|managementServiceAppId|String|The Entra management service App ID which gets used during client device-based enrollment discovery. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
### [windowsAutopilotDeploymentProfileAssignment ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotdeploymentprofileassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key of the assignment.|
|target|deviceAndAppManagementAssignmentTarget|The assignment target for the Windows Autopilot deployment profile.|
|source|deviceAndAppManagementAssignmentSource|Type of resource used for deployment to a group, direct or parcel/policySet. Possible values are: `direct`, `policySets`.|
|sourceId|String|Identifier for resource used for deployment to a group|
### [windowsAutopilotDeviceIdentity ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotdeviceidentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object|
|groupTag|String|Group Tag of the Windows autopilot device.|
|purchaseOrderIdentifier|String|Purchase Order Identifier of the Windows autopilot device.|
|serialNumber|String|Serial number of the Windows autopilot device.|
|productKey|String|Product Key of the Windows autopilot device.|
|manufacturer|String|Oem manufacturer of the Windows autopilot device.|
|model|String|Model name of the Windows autopilot device.|
|enrollmentState|enrollmentState|Intune enrollment state of the Windows autopilot device. Possible values are: `unknown`, `enrolled`, `pendingReset`, `failed`, `notContacted`.|
|lastContactedDateTime|DateTimeOffset|Intune Last Contacted Date Time of the Windows autopilot device.|
|addressableUserName|String|Addressable user name.|
|userPrincipalName|String|User Principal Name.|
|resourceName|String|Resource Name.|
|skuNumber|String|SKU Number|
|systemFamily|String|System Family|
|azureActiveDirectoryDeviceId|String|AAD Device ID - to be deprecated|
|managedDeviceId|String|Managed Device ID|
|displayName|String|Display Name|
### [intune-enrollment-windowsautopilotdeviceremediationstate](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotdeviceremediationstate?view=graph-rest-1.0&tabs=http)

### [intune-enrollment-windowsautopilotdevicetype](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotdevicetype?view=graph-rest-1.0&tabs=http)

### [intune-enrollment-windowsautopilotprofileassignmentdetailedstatus](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotprofileassignmentdetailedstatus?view=graph-rest-1.0&tabs=http)

### [intune-enrollment-windowsautopilotprofileassignmentstatus](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotprofileassignmentstatus?view=graph-rest-1.0&tabs=http)

### [windowsAutopilotSettings ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object|
|lastSyncDateTime|DateTimeOffset|Last data sync date time with DDS service.|
|lastManualSyncTriggerDateTime|DateTimeOffset|Last data sync date time with DDS service.|
|syncStatus|windowsAutopilotSyncStatus|Indicates the status of sync with Device data sync (DDS) service. Possible values are: `unknown`, `inProgress`, `completed`, `failed`.|
### [intune-enrollment-windowsautopilotsyncstatus](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotsyncstatus?view=graph-rest-1.0&tabs=http)

### [intune-enrollment-windowsautopilotuserlessenrollmentstatus](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsautopilotuserlessenrollmentstatus?view=graph-rest-1.0&tabs=http)

### [windowsDomainJoinConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsdomainjoinconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
### [windowsEnrollmentStatusScreenSettings ](https://docs.microsoft.com/graph/api/resources/intune-enrollment-windowsenrollmentstatusscreensettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|hideInstallationProgress|Boolean|Show or hide installation progress to user|
|allowDeviceUseBeforeProfileAndAppInstallComplete|Boolean|Allow or block user to use device before profile and app installation complete|
|blockDeviceSetupRetryByUser|Boolean|Allow the user to retry the setup on installation failure|
|allowLogCollectionOnInstallFailure|Boolean|Allow or block log collection on installation failure|
|customErrorMessage|String|Set custom error message to show upon installation failure|
|installProgressTimeoutInMinutes|Int32|Set installation progress timeout in minutes|
|allowDeviceUseOnInstallFailure|Boolean|Allow the user to continue using the device on installation failure|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-notification-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
### [localizedNotificationMessage ](https://docs.microsoft.com/graph/api/resources/intune-notification-localizednotificationmessage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|locale|String|The Locale for which this message is destined.|
|subject|String|The Message Template Subject.|
|messageTemplate|String|The Message Template content.|
|isDefault|Boolean|Flag to indicate whether or not this is the default locale for language fallback. This flag can only be set. To unset, set this property to true on another Localized Notification Message.|
### [notificationMessageTemplate ](https://docs.microsoft.com/graph/api/resources/intune-notification-notificationmessagetemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|displayName|String|Display name for the Notification Message Template.|
|defaultLocale|String|The default locale to fallback onto when the requested locale is not available.|
|brandingOptions|notificationTemplateBrandingOptions|The Message Template Branding Options. Branding is defined in the Intune Admin Console. Possible values are: `none`, `includeCompanyLogo`, `includeCompanyName`, `includeContactInformation`, `includeCompanyPortalLink`, `includeDeviceDetails`, `unknownFutureValue`.|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance.|
### [intune-notification-notificationtemplatebrandingoptions](https://docs.microsoft.com/graph/api/resources/intune-notification-notificationtemplatebrandingoptions?view=graph-rest-1.0&tabs=http)

### [certificateConnectorSetting ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-certificateconnectorsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|status|Int32|Certificate connector status|
|certExpiryTime|DateTimeOffset|Certificate expire time|
|enrollmentError|String|Certificate connector enrollment error|
|lastConnectorConnectionTime|DateTimeOffset|Last time certificate connector connected|
|connectorVersion|String|Version of certificate connector|
|lastUploadVersion|Int64|Version of last uploaded certificate connector|
### [complianceManagementPartner ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-compliancemanagementpartner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Id of the entity|
|lastHeartbeatDateTime|DateTimeOffset|Timestamp of last heartbeat after admin onboarded to the compliance management partner|
|partnerState|deviceManagementPartnerTenantState|Partner state of this tenant. Possible values are: `unknown`, `unavailable`, `enabled`, `terminated`, `rejected`, `unresponsive`.|
|displayName|String|Partner display name|
|macOsOnboarded|Boolean|Partner onboarded for Mac devices.|
|androidOnboarded|Boolean|Partner onboarded for Android devices.|
|iosOnboarded|Boolean|Partner onboarded for ios devices.|
|macOsEnrollmentAssignments|complianceManagementPartnerAssignment collection|User groups which enroll Mac devices through partner.|
|androidEnrollmentAssignments|complianceManagementPartnerAssignment collection|User groups which enroll Android devices through partner.|
|iosEnrollmentAssignments|complianceManagementPartnerAssignment collection|User groups which enroll ios devices through partner.|
### [complianceManagementPartnerAssignment ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-compliancemanagementpartnerassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|target|deviceAndAppManagementAssignmentTarget|Group assignment target.|
### [deviceAndAppManagementData ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceandappmanagementdata?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|Stream|Not yet documented|
### [deviceComanagementAuthorityConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicecomanagementauthorityconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|roleScopeTagIds|String collection|Optional role scope tags for the enrollment restrictions. Inherited from deviceEnrollmentConfiguration|
|deviceEnrollmentConfigurationType|deviceEnrollmentConfigurationType|Support for Enrollment Configuration Type Inherited from deviceEnrollmentConfiguration. Possible values are: `unknown`, `limit`, `platformRestrictions`, `windowsHelloForBusiness`, `defaultLimit`, `defaultPlatformRestrictions`, `defaultWindowsHelloForBusiness`, `defaultWindows10EnrollmentCompletionPageConfiguration`, `windows10EnrollmentCompletionPageConfiguration`, `deviceComanagementAuthorityConfiguration`, `singlePlatformRestriction`, `unknownFutureValue`, `enrollmentNotificationsConfiguration`.|
|managedDeviceAuthority|Int32|CoManagement Authority configuration ManagedDeviceAuthority|
|installConfigurationManagerAgent|Boolean|CoManagement Authority configuration InstallConfigurationManagerAgent|
|configurationManagerAgentCommandLineArgument|String|CoManagement Authority configuration ConfigurationManagerAgentCommandLineArgument|
### [deviceEnrollmentConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account|
|displayName|String|The display name of the device enrollment configuration|
|description|String|The description of the device enrollment configuration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value.|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration|
|version|Int32|The version of the device enrollment configuration|
### [intune-onboarding-deviceenrollmentconfigurationtype](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentconfigurationtype?view=graph-rest-1.0&tabs=http)

### [deviceEnrollmentLimitConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentlimitconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|limit|Int32|The maximum number of devices that a user can enroll|
### [deviceEnrollmentNotificationConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentnotificationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|roleScopeTagIds|String collection|Optional role scope tags for the enrollment restrictions. Inherited from deviceEnrollmentConfiguration|
|deviceEnrollmentConfigurationType|deviceEnrollmentConfigurationType|Support for Enrollment Configuration Type Inherited from deviceEnrollmentConfiguration. Possible values are: `unknown`, `limit`, `platformRestrictions`, `windowsHelloForBusiness`, `defaultLimit`, `defaultPlatformRestrictions`, `defaultWindowsHelloForBusiness`, `defaultWindows10EnrollmentCompletionPageConfiguration`, `windows10EnrollmentCompletionPageConfiguration`, `deviceComanagementAuthorityConfiguration`, `singlePlatformRestriction`, `unknownFutureValue`, `enrollmentNotificationsConfiguration`.|
|platformType|enrollmentRestrictionPlatformType|Platform type of the Enrollment Notification. Possible values are: `allPlatforms`, `ios`, `windows`, `windowsPhone`, `android`, `androidForWork`, `mac`, `linux`, `unknownFutureValue`.|
|templateType|enrollmentNotificationTemplateType|Template type of the Enrollment Notification. Possible values are: `email`, `push`, `unknownFutureValue`.|
|notificationMessageTemplateId|Guid|Notification Message Template Id|
|notificationTemplates|String collection|The list of notification data - <TemplateType>_<NotificationMessageTemplateId>|
|brandingOptions|enrollmentNotificationBrandingOptions|Branding Options for the Enrollment Notification. Possible values are: `none`, `includeCompanyLogo`, `includeCompanyName`, `includeContactInformation`, `includeCompanyPortalLink`, `includeDeviceDetails`, `unknownFutureValue`.|
|defaultLocale|String|DefaultLocale for the Enrollment Notification|
### [deviceEnrollmentPlatformRestriction ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentplatformrestriction?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|platformBlocked|Boolean|Block the platform from enrolling|
|personalDeviceEnrollmentBlocked|Boolean|Block personally owned devices from enrolling|
|osMinimumVersion|String|Min OS version supported|
|osMaximumVersion|String|Max OS version supported|
### [deviceEnrollmentPlatformRestrictionConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentplatformrestrictionconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|roleScopeTagIds|String collection|Optional role scope tags for the enrollment restrictions. Inherited from deviceEnrollmentConfiguration|
|deviceEnrollmentConfigurationType|deviceEnrollmentConfigurationType|Support for Enrollment Configuration Type Inherited from deviceEnrollmentConfiguration. Possible values are: `unknown`, `limit`, `platformRestrictions`, `windowsHelloForBusiness`, `defaultLimit`, `defaultPlatformRestrictions`, `defaultWindowsHelloForBusiness`, `defaultWindows10EnrollmentCompletionPageConfiguration`, `windows10EnrollmentCompletionPageConfiguration`, `deviceComanagementAuthorityConfiguration`, `singlePlatformRestriction`, `unknownFutureValue`, `enrollmentNotificationsConfiguration`.|
|platformRestriction|deviceEnrollmentPlatformRestriction|Restrictions based on platform, platform operating system version, and device ownership|
|platformType|enrollmentRestrictionPlatformType|Type of platform for which this restriction applies. Possible values are: `allPlatforms`, `ios`, `windows`, `windowsPhone`, `android`, `androidForWork`, `mac`, `linux`, `unknownFutureValue`.|
### [deviceEnrollmentPlatformRestrictionsConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentplatformrestrictionsconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|iosRestriction|deviceEnrollmentPlatformRestriction|Ios restrictions based on platform, platform operating system version, and device ownership|
|windowsRestriction|deviceEnrollmentPlatformRestriction|Windows restrictions based on platform, platform operating system version, and device ownership|
|windowsMobileRestriction|deviceEnrollmentPlatformRestriction|Windows mobile restrictions based on platform, platform operating system version, and device ownership|
|androidRestriction|deviceEnrollmentPlatformRestriction|Android restrictions based on platform, platform operating system version, and device ownership|
|macOSRestriction|deviceEnrollmentPlatformRestriction|Mac restrictions based on platform, platform operating system version, and device ownership|
### [deviceEnrollmentWindowsHelloForBusinessConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-deviceenrollmentwindowshelloforbusinessconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|pinMinimumLength|Int32|Controls the minimum number of characters required for the Windows Hello for Business PIN.  This value must be between 4 and 127, inclusive, and less than or equal to the value set for the maximum PIN.|
|pinMaximumLength|Int32|Controls the maximum number of characters allowed for the Windows Hello for Business PIN. This value must be between 4 and 127, inclusive. This value must be greater than or equal to the value set for the minimum PIN.|
|pinUppercaseCharactersUsage|windowsHelloForBusinessPinUsage|Controls the ability to use uppercase letters in the Windows Hello for Business PIN.  Allowed permits the use of uppercase letter(s), whereas Required ensures they are present. If set to Not Allowed, uppercase letters will not be permitted. Possible values are: `allowed`, `required`, `disallowed`.|
|pinLowercaseCharactersUsage|windowsHelloForBusinessPinUsage|Controls the ability to use lowercase letters in the Windows Hello for Business PIN.  Allowed permits the use of lowercase letter(s), whereas Required ensures they are present. If set to Not Allowed, lowercase letters will not be permitted. Possible values are: `allowed`, `required`, `disallowed`.|
|pinSpecialCharactersUsage|windowsHelloForBusinessPinUsage|Controls the ability to use special characters in the Windows Hello for Business PIN.  Allowed permits the use of special character(s), whereas Required ensures they are present. If set to Not Allowed, special character(s) will not be permitted. Possible values are: `allowed`, `required`, `disallowed`.|
|state|enablement|Controls whether to allow the device to be configured for Windows Hello for Business. If set to disabled, the user cannot provision Windows Hello for Business except on Azure Active Directory joined mobile phones if otherwise required. If set to Not Configured, Intune will not override client defaults. Possible values are: `notConfigured`, `enabled`, `disabled`.|
|securityDeviceRequired|Boolean|Controls whether to require a Trusted Platform Module (TPM) for provisioning Windows Hello for Business. A TPM provides an additional security benefit in that data stored on it cannot be used on other devices. If set to False, all devices can provision Windows Hello for Business even if there is not a usable TPM.|
|unlockWithBiometricsEnabled|Boolean|Controls the use of biometric gestures, such as face and fingerprint, as an alternative to the Windows Hello for Business PIN.  If set to False, biometric gestures are not allowed. Users must still configure a PIN as a backup in case of failures.|
|remotePassportEnabled|Boolean|Controls the use of Remote Windows Hello for Business. Remote Windows Hello for Business provides the ability for a portable, registered device to be usable as a companion for desktop authentication. The desktop must be Azure AD joined and the companion device must have a Windows Hello for Business PIN.|
|pinPreviousBlockCount|Int32|Controls the ability to prevent users from using past PINs. This must be set between 0 and 50, inclusive, and the current PIN of the user is included in that count. If set to 0, previous PINs are not stored. PIN history is not preserved through a PIN reset.|
|pinExpirationInDays|Int32|Controls the period of time (in days) that a PIN can be used before the system requires the user to change it. This must be set between 0 and 730, inclusive. If set to 0, the user's PIN will never expire|
|enhancedBiometricsState|enablement|Controls the ability to use the anti-spoofing features for facial recognition on devices which support it. If set to disabled, anti-spoofing features are not allowed. If set to Not Configured, the user can choose whether they want to use anti-spoofing. Possible values are: `notConfigured`, `enabled`, `disabled`.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
|intuneBrand|intuneBrand|intuneBrand contains data which is used in customizing the appearance of the Company Portal applications as well as the end user web portal.|
### [intune-onboarding-devicemanagementexchangeaccesslevel](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeaccesslevel?view=graph-rest-1.0&tabs=http)

### [deviceManagementExchangeAccessRule ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeaccessrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceClass|deviceManagementExchangeDeviceClass|Device Class which will be impacted by this rule.|
|accessLevel|deviceManagementExchangeAccessLevel|Access Level for Exchange granted by this rule. Possible values are: `none`, `allow`, `block`, `quarantine`.|
### [deviceManagementExchangeConnector ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
|lastSyncDateTime|DateTimeOffset|Last sync time for the Exchange Connector|
|status|deviceManagementExchangeConnectorStatus|Exchange Connector Status. Possible values are: `none`, `connectionPending`, `connected`, `disconnected`, `unknownFutureValue`.|
|primarySmtpAddress|String|Email address used to configure the Service To Service Exchange Connector.|
|serverName|String|The name of the Exchange server.|
|connectorServerName|String|The name of the server hosting the Exchange Connector.|
|exchangeConnectorType|deviceManagementExchangeConnectorType|The type of Exchange Connector Configured. Possible values are: `onPremises`, `hosted`, `serviceToService`, `dedicated`, `unknownFutureValue`.|
|version|String|The version of the ExchangeConnectorAgent|
|exchangeAlias|String|An alias assigned to the Exchange server|
|exchangeOrganization|String|Exchange Organization to the Exchange server|
### [intune-onboarding-devicemanagementexchangeconnectorstatus](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeconnectorstatus?view=graph-rest-1.0&tabs=http)

### [intune-onboarding-devicemanagementexchangeconnectorsynctype](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeconnectorsynctype?view=graph-rest-1.0&tabs=http)

### [intune-onboarding-devicemanagementexchangeconnectortype](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeconnectortype?view=graph-rest-1.0&tabs=http)

### [deviceManagementExchangeDeviceClass ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangedeviceclass?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|name|String|Name of the device class which will be impacted by this rule.|
|type|deviceManagementExchangeAccessRuleType|Type of device which is impacted by this rule e.g. Model, Family. Possible values are: `family`, `model`.|
### [deviceManagementExchangeOnPremisesPolicy ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementexchangeonpremisespolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String||
|notificationContent|Binary|Notification text that will be sent to users quarantined by this policy. This is UTF8 encoded byte array HTML.|
|defaultAccessLevel|deviceManagementExchangeAccessLevel|Default access state in Exchange. This rule applies globally to the entire Exchange organization. Possible values are: `none`, `allow`, `block`, `quarantine`.|
|accessRules|deviceManagementExchangeAccessRule collection|The list of device access rules in Exchange. The access rules apply globally to the entire Exchange organization|
|knownDeviceClasses|deviceManagementExchangeDeviceClass collection|The list of device classes known to Exchange|
### [deviceManagementPartner ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementpartner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Id of the entity|
|lastHeartbeatDateTime|DateTimeOffset|Timestamp of last heartbeat after admin enabled option Connect to Device management Partner|
|partnerState|deviceManagementPartnerTenantState|Partner state of this tenant. Possible values are: `unknown`, `unavailable`, `enabled`, `terminated`, `rejected`, `unresponsive`.|
|partnerAppType|deviceManagementPartnerAppType|Partner App type. Possible values are: `unknown`, `singleTenantApp`, `multiTenantApp`.|
|singleTenantAppId|String|Partner Single tenant App id|
|displayName|String|Partner display name|
|isConfigured|Boolean|Whether device management partner is configured or not|
|whenPartnerDevicesWillBeRemovedDateTime|DateTimeOffset|DateTime in UTC when PartnerDevices will be removed|
|whenPartnerDevicesWillBeMarkedAsNonCompliantDateTime|DateTimeOffset|DateTime in UTC when PartnerDevices will be marked as NonCompliant|
|groupsRequiringPartnerEnrollment|deviceManagementPartnerAssignment collection|User groups that specifies whether enrollment is through partner.|
### [intune-onboarding-devicemanagementpartnerapptype](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementpartnerapptype?view=graph-rest-1.0&tabs=http)

### [deviceManagementPartnerAssignment ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementpartnerassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|target|deviceAndAppManagementAssignmentTarget|User groups targeting for devices to be enrolled through partner.|
### [intune-onboarding-devicemanagementpartnertenantstate](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicemanagementpartnertenantstate?view=graph-rest-1.0&tabs=http)

### [intune-onboarding-enablement](https://docs.microsoft.com/graph/api/resources/intune-onboarding-enablement?view=graph-rest-1.0&tabs=http)

### [enrollmentConfigurationAssignment ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-enrollmentconfigurationassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the enrollment configuration assignment|
|target|deviceAndAppManagementAssignmentTarget|Represents an assignment to managed devices in the tenant|
### [intune-onboarding-enrollmentnotificationbrandingoptions](https://docs.microsoft.com/graph/api/resources/intune-onboarding-enrollmentnotificationbrandingoptions?view=graph-rest-1.0&tabs=http)

### [intune-onboarding-enrollmentnotificationtemplatetype](https://docs.microsoft.com/graph/api/resources/intune-onboarding-enrollmentnotificationtemplatetype?view=graph-rest-1.0&tabs=http)

### [intune-onboarding-enrollmentrestrictionplatformtype](https://docs.microsoft.com/graph/api/resources/intune-onboarding-enrollmentrestrictionplatformtype?view=graph-rest-1.0&tabs=http)

### [intuneBrand ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-intunebrand?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Company/organization name that is displayed to end users.|
|themeColor|rgbColor|Primary theme color used in the Company Portal applications and web portal.|
|showLogo|Boolean|Boolean that represents whether the administrator-supplied logo images are shown or not shown.|
|lightBackgroundLogo|mimeContent|Logo image displayed in Company Portal apps which have a light background behind the logo.|
|darkBackgroundLogo|mimeContent|Logo image displayed in Company Portal apps which have a dark background behind the logo.|
|showNameNextToLogo|Boolean|Boolean that represents whether the administrator-supplied display name will be shown next to the logo image.|
|showDisplayNameNextToLogo|Boolean|Boolean that represents whether the administrator-supplied display name will be shown next to the logo image.|
|contactITName|String|Name of the person/organization responsible for IT support.|
|contactITPhoneNumber|String|Phone number of the person/organization responsible for IT support.|
|contactITEmailAddress|String|Email address of the person/organization responsible for IT support.|
|contactITNotes|String|Text comments regarding the person/organization responsible for IT support.|
|onlineSupportSiteUrl|String|URL to the company/organization’s IT helpdesk site.|
|onlineSupportSiteName|String|Display name of the company/organization’s IT helpdesk site.|
|privacyUrl|String|URL to the company/organization’s privacy policy.|
### [intune-onboarding-mdmauthority](https://docs.microsoft.com/graph/api/resources/intune-onboarding-mdmauthority?view=graph-rest-1.0&tabs=http)

### [mobileThreatDefenseConnector ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-mobilethreatdefenseconnector?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
|lastHeartbeatDateTime|DateTimeOffset|DateTime of last Heartbeat recieved from the Mobile Threat Defense partner|
|partnerState|mobileThreatPartnerTenantState|Mobile Threat Defense partner state for this account. Possible values are: `unavailable`, `available`, `enabled`, `unresponsive`.|
|androidMobileApplicationManagementEnabled|Boolean|When TRUE, inidicates that data from the Mobile Threat Defense partner can be used during Mobile Application Management (MAM) evaluations for Android devices. When FALSE, inidicates that data from the Mobile Threat Defense partner should not be used during Mobile Application Management (MAM) evaluations for Android devices. Only one partner per platform may be enabled for Mobile Application Management (MAM) evaluation. Default value is FALSE.|
|iosMobileApplicationManagementEnabled|Boolean|When TRUE, inidicates that data from the Mobile Threat Defense partner can be used during Mobile Application Management (MAM) evaluations for IOS devices. When FALSE, inidicates that data from the Mobile Threat Defense partner should not be used during Mobile Application Management (MAM) evaluations for IOS devices. Only one partner per platform may be enabled for Mobile Application Management (MAM) evaluation. Default value is FALSE.|
|androidEnabled|Boolean|For Android, set whether data from the Mobile Threat Defense partner should be used during compliance evaluations|
|iosEnabled|Boolean|For IOS, get or set whether data from the Mobile Threat Defense partner should be used during compliance evaluations|
|windowsEnabled|Boolean|When TRUE, inidicates that data from the Mobile Threat Defense partner can be used during compliance evaluations for Windows. When FALSE, inidicates that data from the Mobile Threat Defense partner should not be used during compliance evaluations for Windows. Default value is FALSE.|
|androidDeviceBlockedOnMissingPartnerData|Boolean|For Android, set whether Intune must receive data from the Mobile Threat Defense partner prior to marking a device compliant|
|iosDeviceBlockedOnMissingPartnerData|Boolean|For IOS, set whether Intune must receive data from the Mobile Threat Defense partner prior to marking a device compliant|
|windowsDeviceBlockedOnMissingPartnerData|Boolean|When TRUE, inidicates that Intune must receive data from the Mobile Threat Defense partner prior to marking a device compliant for Windows. When FALSE, inidicates that Intune may make a device compliant without receiving data from the Mobile Threat Defense partner for Windows. Default value is FALSE.|
|partnerUnsupportedOsVersionBlocked|Boolean|Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Mobile Threat Defense partner|
|partnerUnresponsivenessThresholdInDays|Int32|Get or Set days the per tenant tolerance to unresponsiveness for this partner integration|
|allowPartnerToCollectIOSApplicationMetadata|Boolean|When TRUE, indicates the Mobile Threat Defense partner may collect metadata about installed applications from Intune for IOS devices. When FALSE, indicates the Mobile Threat Defense partner may not collect metadata about installed applications from Intune for IOS devices. Default value is FALSE.|
|allowPartnerToCollectIOSPersonalApplicationMetadata|Boolean|When TRUE, indicates the Mobile Threat Defense partner may collect metadata about personally installed applications from Intune for IOS devices. When FALSE, indicates the Mobile Threat Defense partner may not collect metadata about personally installed applications from Intune for IOS devices. Default value is FALSE.|
|microsoftDefenderForEndpointAttachEnabled|Boolean|When TRUE, inidicates that configuration profile management via Microsoft Defender for Endpoint is enabled. When FALSE, inidicates that configuration profile management via Microsoft Defender for Endpoint is disabled. Default value is FALSE.|
### [intune-onboarding-mobilethreatpartnertenantstate](https://docs.microsoft.com/graph/api/resources/intune-onboarding-mobilethreatpartnertenantstate?view=graph-rest-1.0&tabs=http)

### [onPremisesConditionalAccessSettings ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-onpremisesconditionalaccesssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
|enabled|Boolean|Indicates if on premises conditional access is enabled for this organization|
|includedGroups|Guid collection|User groups that will be targeted by on premises conditional access. All users in these groups will be required to have mobile device managed and compliant for mail access.|
|excludedGroups|Guid collection|User groups that will be exempt by on premises conditional access. All users in these groups will be exempt from the conditional access policy.|
|overrideDefaultRule|Boolean|Override the default access rule when allowing a device to ensure access is granted.|
### [organization ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-organization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object.|
|mobileDeviceManagementAuthority|mdmAuthority|Mobile device management authority. Possible values are: `unknown`, `intune`, `sccm`, `office365`.|
### [sideLoadingKey ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-sideloadingkey?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Side Loading Key Unique Id.|
|value|String|Side Loading Key Value, it is 5x5 value, seperated by hiphens.|
|displayName|String|Side Loading Key Name displayed to the ITPro Admins.|
|description|String|Side Loading Key description displayed to the ITPro Admins..|
|totalActivation|Int32|Side Loading Key Total Activation displayed to the ITPro Admins.|
|lastUpdatedDateTime|String|Side Loading Key Last Updated Date displayed to the ITPro Admins.|
### [user ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the user.|
|deviceEnrollmentLimit|Int32|The limit on the maximum number of devices that the user is permitted to enroll. Allowed values are 5 or 1000.|
### [vppToken ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-vpptoken?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|This is automatically generated when the appleVolumePurchaseProgramToken is created. It is the Key of the entity.|
|organizationName|String|The organization associated with the Apple Volume Purchase Program Token|
|vppTokenAccountType|vppTokenAccountType|The type of volume purchase program which the given Apple Volume Purchase Program Token is associated with. Possible values are: `business`, `education`. Possible values are: `business`, `education`.|
|appleId|String|The apple Id associated with the given Apple Volume Purchase Program Token.|
|expirationDateTime|DateTimeOffset|The expiration date time of the Apple Volume Purchase Program Token.|
|lastSyncDateTime|DateTimeOffset|The last time when an application sync was done with the Apple volume purchase program service using the the Apple Volume Purchase Program Token.|
|token|String|The Apple Volume Purchase Program Token string downloaded from the Apple Volume Purchase Program.|
|lastModifiedDateTime|DateTimeOffset|Last modification date time associated with the Apple Volume Purchase Program Token.|
|state|vppTokenState|Current state of the Apple Volume Purchase Program Token. Possible values are: `unknown`, `valid`, `expired`, `invalid`, `assignedToExternalMDM`. Possible values are: `unknown`, `valid`, `expired`, `invalid`, `assignedToExternalMDM`.|
|lastSyncStatus|vppTokenSyncStatus|Current sync status of the last application sync which was triggered using the Apple Volume Purchase Program Token. Possible values are: `none`, `inProgress`, `completed`, `failed`. Possible values are: `none`, `inProgress`, `completed`, `failed`.|
|automaticallyUpdateApps|Boolean|Whether or not apps for the VPP token will be automatically updated.|
|countryOrRegion|String|Whether or not apps for the VPP token will be automatically updated.|
### [vppTokenActionResult ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-vpptokenactionresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionName|String|Action name|
|actionState|actionState|State of the action. Possible values are: `none`, `pending`, `canceled`, `active`, `done`, `failed`, `notSupported`.|
|startDateTime|DateTimeOffset|Time the action was initiated|
|lastUpdatedDateTime|DateTimeOffset|Time the action state was last updated|
### [intune-onboarding-vpptokenstate](https://docs.microsoft.com/graph/api/resources/intune-onboarding-vpptokenstate?view=graph-rest-1.0&tabs=http)

### [intune-onboarding-vpptokensyncstatus](https://docs.microsoft.com/graph/api/resources/intune-onboarding-vpptokensyncstatus?view=graph-rest-1.0&tabs=http)

### [windows10EnrollmentCompletionPageConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-windows10enrollmentcompletionpageconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account Inherited from deviceEnrollmentConfiguration|
|displayName|String|The display name of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|description|String|The description of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value. Inherited from deviceEnrollmentConfiguration|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|version|Int32|The version of the device enrollment configuration Inherited from deviceEnrollmentConfiguration|
|roleScopeTagIds|String collection|Optional role scope tags for the enrollment restrictions. Inherited from deviceEnrollmentConfiguration|
|deviceEnrollmentConfigurationType|deviceEnrollmentConfigurationType|Support for Enrollment Configuration Type Inherited from deviceEnrollmentConfiguration. Possible values are: `unknown`, `limit`, `platformRestrictions`, `windowsHelloForBusiness`, `defaultLimit`, `defaultPlatformRestrictions`, `defaultWindowsHelloForBusiness`, `defaultWindows10EnrollmentCompletionPageConfiguration`, `windows10EnrollmentCompletionPageConfiguration`, `deviceComanagementAuthorityConfiguration`, `singlePlatformRestriction`, `unknownFutureValue`, `enrollmentNotificationsConfiguration`.|
|showInstallationProgress|Boolean|When TRUE, shows installation progress to user. When false, hides installation progress. The default is false.|
|blockDeviceSetupRetryByUser|Boolean|When TRUE, blocks user from retrying the setup on installation failure. When false, user is allowed to retry. The default is false.|
|allowDeviceResetOnInstallFailure|Boolean|When TRUE, allows device reset on installation failure. When false, reset is blocked. The default is false.|
|allowLogCollectionOnInstallFailure|Boolean|When TRUE, allows log collection on installation failure. When false, log collection is not allowed. The default is false.|
|customErrorMessage|String|The custom error message to show upon installation failure. Max length is 10000. example: "Setup could not be completed. Please try again or contact your support person for help."|
|installProgressTimeoutInMinutes|Int32|The installation progress timeout in minutes. Default is 60 minutes.|
|allowDeviceUseOnInstallFailure|Boolean|When TRUE, allows the user to continue using the device on installation failure. When false, blocks the user on installation failure. The default is false.|
|selectedMobileAppIds|String collection|Selected applications to track the installation status. It is in the form of an array of GUIDs.|
|allowNonBlockingAppInstallation|Boolean|When TRUE, ESP (Enrollment Status Page) installs all required apps targeted during technician phase and ignores any failures for non-blocking apps. When FALSE, ESP fails on any error during app install. The default is false.|
|installQualityUpdates|Boolean|Allows quality updates installation during OOBE|
|trackInstallProgressForAutopilotOnly|Boolean|When TRUE, installation progress is tracked for only Autopilot enrollment scenarios. When false, other scenarios are tracked as well. The default is false.|
|disableUserStatusTrackingAfterFirstUser|Boolean|When TRUE, disables showing installation progress for first user post enrollment. When false, enables showing progress. The default is false.|
### [intune-onboarding-windowshelloforbusinesspinusage](https://docs.microsoft.com/graph/api/resources/intune-onboarding-windowshelloforbusinesspinusage?view=graph-rest-1.0&tabs=http)

### [hasPayloadLinkResultItem ](https://docs.microsoft.com/graph/api/resources/intune-policyset-haspayloadlinkresultitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|payloadId|String|Key of the Payload, In the format of Guid.|
|hasLink|Boolean|Indicate whether a payload has any link or not.|
|error|String|Exception information indicates if check for this item was successful or not.Empty string for no error.|
|sources|deviceAndAppManagementAssignmentSource collection|The reason where the link comes from.|
### [applicabilityRule ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-applicabilityrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|filterType|filterAssociationType|. Possible values are: `unknown`, `include`, `exclude`.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|
### [intune-rapolicy-devicemanagementderivedcredentialissuer](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagementderivedcredentialissuer?view=graph-rest-1.0&tabs=http)

### [intune-rapolicy-devicemanagementderivedcredentialnotificationtype](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagementderivedcredentialnotificationtype?view=graph-rest-1.0&tabs=http)

### [deviceManagementDerivedCredentialSettings ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagementderivedcredentialsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the Derived Credential|
|helpUrl|String|The URL that will be accessible to end users as they retrieve a derived credential using the Company Portal.|
|displayName|String|The display name for the profile.|
|issuer|deviceManagementDerivedCredentialIssuer|The derived credential provider to use. Possible values are: `intercede`, `entrustDatacard`, `purebred`, `xTec`.|
|notificationType|deviceManagementDerivedCredentialNotificationType|The methods used to inform the end user to open Company Portal to deliver Wi-Fi, VPN, or email profiles that use certificates to the device. Possible values are: `none`, `companyPortal`, `email`.|
|renewalThresholdPercentage|Int32|The nominal percentage of time before certificate renewal is initiated by the client.|
### [deviceManagementResourceAccessProfileAssignment ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagementresourceaccessprofileassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the Assignments|
|intent|deviceManagementResourceAccessProfileIntent|The assignment intent for the resource access profile. Possible values are: `apply`, `remove`.|
|target|deviceAndAppManagementAssignmentTarget|The assignment target for the resource access profile.|
|sourceId|String|The identifier of the source of the assignment.|
### [deviceManagementResourceAccessProfileBase ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagementresourceaccessprofilebase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile identifier|
|version|Int32|Version of the profile|
|displayName|String|Profile display name|
|description|String|Profile description|
|creationDateTime|DateTimeOffset|DateTime profile was created|
|lastModifiedDateTime|DateTimeOffset|DateTime profile was last modified|
|roleScopeTagIds|String collection|Scope Tags|
|serverApplicabilityRules|applicabilityRule collection|The list of Applicability Rules for a Device Configuration Profile|
### [intune-rapolicy-devicemanagementresourceaccessprofileintent](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-devicemanagementresourceaccessprofileintent?view=graph-rest-1.0&tabs=http)

### [extendedKeyUsage ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-extendedkeyusage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|name|String|Extended Key Usage Name|
|objectIdentifier|String|Extended Key Usage Object Identifier|
### [intune-rapolicy-policyplatformtype](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-policyplatformtype?view=graph-rest-1.0&tabs=http)

### [windows10XCertificateProfile ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-windows10xcertificateprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile identifier Inherited from deviceManagementResourceAccessProfileBase|
|version|Int32|Version of the profile Inherited from deviceManagementResourceAccessProfileBase|
|displayName|String|Profile display name Inherited from deviceManagementResourceAccessProfileBase|
|description|String|Profile description Inherited from deviceManagementResourceAccessProfileBase|
|creationDateTime|DateTimeOffset|DateTime profile was created Inherited from deviceManagementResourceAccessProfileBase|
|lastModifiedDateTime|DateTimeOffset|DateTime profile was last modified Inherited from deviceManagementResourceAccessProfileBase|
|roleScopeTagIds|String collection|Scope Tags Inherited from deviceManagementResourceAccessProfileBase|
|serverApplicabilityRules|applicabilityRule collection|The list of Applicability Rules for a Device Configuration Profile Inherited from deviceManagementResourceAccessProfileBase|
### [windows10XCustomSubjectAlternativeName ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-windows10xcustomsubjectalternativename?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|sanType|subjectAlternativeNameType|Custom SAN Type. Possible values are: `none`, `emailAddress`, `userPrincipalName`, `customAzureADAttribute`, `domainNameService`, `universalResourceIdentifier`.|
|name|String|Custom SAN Name|
### [windows10XSCEPCertificateProfile ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-windows10xscepcertificateprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile identifier Inherited from deviceManagementResourceAccessProfileBase|
|version|Int32|Version of the profile Inherited from deviceManagementResourceAccessProfileBase|
|displayName|String|Profile display name Inherited from deviceManagementResourceAccessProfileBase|
|description|String|Profile description Inherited from deviceManagementResourceAccessProfileBase|
|creationDateTime|DateTimeOffset|DateTime profile was created Inherited from deviceManagementResourceAccessProfileBase|
|lastModifiedDateTime|DateTimeOffset|DateTime profile was last modified Inherited from deviceManagementResourceAccessProfileBase|
|roleScopeTagIds|String collection|Scope Tags Inherited from deviceManagementResourceAccessProfileBase|
|serverApplicabilityRules|applicabilityRule collection|The list of Applicability Rules for a Device Configuration Profile Inherited from deviceManagementResourceAccessProfileBase|
|certificateStore|certificateStore|Target store certificate. Possible values are: `user`, `machine`.|
|certificateValidityPeriodScale|certificateValidityPeriodScale|Scale for the Certificate Validity Period. Possible values are: `days`, `months`, `years`.|
|certificateValidityPeriodValue|Int32|Value for the Certificate Validity Period|
|extendedKeyUsages|extendedKeyUsage collection|Extended Key Usage (EKU) settings.|
|hashAlgorithm|hashAlgorithms collection|SCEP Hash Algorithm.|
|keySize|keySize|SCEP Key Size. Possible values are: `size1024`, `size2048`, `size4096`.|
|keyStorageProvider|keyStorageProviderOption|Key Storage Provider (KSP). Possible values are: `useTpmKspOtherwiseUseSoftwareKsp`, `useTpmKspOtherwiseFail`, `usePassportForWorkKspOtherwiseFail`, `useSoftwareKsp`.|
|keyUsage|keyUsages|SCEP Key Usage. Possible values are: `keyEncipherment`, `digitalSignature`.|
|renewalThresholdPercentage|Int32|Certificate renewal threshold percentage|
|rootCertificateId|Guid|Trusted Root Certificate ID|
|scepServerUrls|String collection|SCEP Server Url(s).|
|subjectAlternativeNameFormats|windows10XCustomSubjectAlternativeName collection|Custom AAD Attributes.|
|subjectNameFormatString|String|Custom format to use with SubjectNameFormat = Custom. Example: CN={{EmailAddress}},E={{EmailAddress}},OU=Enterprise Users,O=Contoso Corporation,L=Redmond,ST=WA,C=US|
### [windows10XTrustedRootCertificate ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-windows10xtrustedrootcertificate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile identifier Inherited from deviceManagementResourceAccessProfileBase|
|version|Int32|Version of the profile Inherited from deviceManagementResourceAccessProfileBase|
|displayName|String|Profile display name Inherited from deviceManagementResourceAccessProfileBase|
|description|String|Profile description Inherited from deviceManagementResourceAccessProfileBase|
|creationDateTime|DateTimeOffset|DateTime profile was created Inherited from deviceManagementResourceAccessProfileBase|
|lastModifiedDateTime|DateTimeOffset|DateTime profile was last modified Inherited from deviceManagementResourceAccessProfileBase|
|roleScopeTagIds|String collection|Scope Tags Inherited from deviceManagementResourceAccessProfileBase|
|serverApplicabilityRules|applicabilityRule collection|The list of Applicability Rules for a Device Configuration Profile Inherited from deviceManagementResourceAccessProfileBase|
|trustedRootCertificate|Binary|Trusted Root Certificate|
|certFileName|String|File name to display in UI.|
|destinationStore|certificateDestinationStore|Destination store location for the Trusted Root Certificate. Possible values are: `computerCertStoreRoot`, `computerCertStoreIntermediate`, `userCertStoreIntermediate`.|
### [windows10XVpnConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-windows10xvpnconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile identifier Inherited from deviceManagementResourceAccessProfileBase|
|version|Int32|Version of the profile Inherited from deviceManagementResourceAccessProfileBase|
|displayName|String|Profile display name Inherited from deviceManagementResourceAccessProfileBase|
|description|String|Profile description Inherited from deviceManagementResourceAccessProfileBase|
|creationDateTime|DateTimeOffset|DateTime profile was created Inherited from deviceManagementResourceAccessProfileBase|
|lastModifiedDateTime|DateTimeOffset|DateTime profile was last modified Inherited from deviceManagementResourceAccessProfileBase|
|roleScopeTagIds|String collection|Scope Tags Inherited from deviceManagementResourceAccessProfileBase|
|serverApplicabilityRules|applicabilityRule collection|The list of Applicability Rules for a Device Configuration Profile Inherited from deviceManagementResourceAccessProfileBase|
|authenticationCertificateId|Guid|ID to the Authentication Certificate|
|customXmlFileName|String|Custom Xml file name.|
|customXml|Binary|Custom XML commands that configures the VPN connection. (UTF8 byte encoding)|
### [windows10XWifiConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-rapolicy-windows10xwificonfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile identifier Inherited from deviceManagementResourceAccessProfileBase|
|version|Int32|Version of the profile Inherited from deviceManagementResourceAccessProfileBase|
|displayName|String|Profile display name Inherited from deviceManagementResourceAccessProfileBase|
|description|String|Profile description Inherited from deviceManagementResourceAccessProfileBase|
|creationDateTime|DateTimeOffset|DateTime profile was created Inherited from deviceManagementResourceAccessProfileBase|
|lastModifiedDateTime|DateTimeOffset|DateTime profile was last modified Inherited from deviceManagementResourceAccessProfileBase|
|roleScopeTagIds|String collection|Scope Tags Inherited from deviceManagementResourceAccessProfileBase|
|serverApplicabilityRules|applicabilityRule collection|The list of Applicability Rules for a Device Configuration Profile Inherited from deviceManagementResourceAccessProfileBase|
|authenticationCertificateId|Guid|ID to the Authentication Certificate|
|customXmlFileName|String|Custom Xml file name.|
|customXml|Binary|Custom XML commands that configures the VPN connection. (UTF8 byte encoding)|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-remoteassistance-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
### [deviceManagementReports ](https://docs.microsoft.com/graph/api/resources/intune-remoteassistance-devicemanagementreports?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The key of the entity|
### [intune-remoteassistance-remoteassistanceonboardingstatus](https://docs.microsoft.com/graph/api/resources/intune-remoteassistance-remoteassistanceonboardingstatus?view=graph-rest-1.0&tabs=http)

### [remoteAssistancePartner ](https://docs.microsoft.com/graph/api/resources/intune-remoteassistance-remoteassistancepartner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the partner.|
|displayName|String|Display name of the partner.|
|onboardingUrl|String|URL of the partner's onboarding portal, where an administrator can configure their Remote Assistance service.|
|onboardingStatus|remoteAssistanceOnboardingStatus|A friendly description of the current TeamViewer connector status. Possible values are: `notOnboarded`, `onboarding`, `onboarded`.|
|lastConnectionDateTime|DateTimeOffset|Timestamp of the last request sent to Intune by the TEM partner.|
### [remoteAssistanceSettings ](https://docs.microsoft.com/graph/api/resources/intune-remoteassistance-remoteassistancesettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The remote assistance settings identifier|
|remoteAssistanceState|remoteAssistanceState|The current state of remote assistance for the account. Possible values are: disabled, enabled. This setting is configurable by the admin. Remote assistance settings that have not yet been configured by the admin have a disabled state. Returned by default. Possible values are: `disabled`, `enabled`.|
|allowSessionsToUnenrolledDevices|Boolean| Indicates if sessions to unenrolled devices are allowed for the account. This setting is configurable by the admin. Default value is false.|
|blockChat|Boolean| Indicates if sessions to block chat function. This setting is configurable by the admin. Default value is false.|
### [intune-remoteassistance-remoteassistancestate](https://docs.microsoft.com/graph/api/resources/intune-remoteassistance-remoteassistancestate?view=graph-rest-1.0&tabs=http)

### [intune-shared-certificatedestinationstore](https://docs.microsoft.com/graph/api/resources/intune-shared-certificatedestinationstore?view=graph-rest-1.0&tabs=http)

### [intune-shared-certificatestore](https://docs.microsoft.com/graph/api/resources/intune-shared-certificatestore?view=graph-rest-1.0&tabs=http)

### [intune-shared-certificatevalidityperiodscale](https://docs.microsoft.com/graph/api/resources/intune-shared-certificatevalidityperiodscale?view=graph-rest-1.0&tabs=http)

### [intune-shared-deviceandappmanagementassignmentsource](https://docs.microsoft.com/graph/api/resources/intune-shared-deviceandappmanagementassignmentsource?view=graph-rest-1.0&tabs=http)

### [deviceAndAppManagementAssignmentTarget ](https://docs.microsoft.com/graph/api/resources/intune-shared-deviceandappmanagementassignmenttarget?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
### [deviceConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-shared-deviceconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified.|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance.|
|supportsScopeTags|Boolean|Indicates whether or not the underlying Device Configuration supports the assignment of scope tags. Assigning to the ScopeTags property is not allowed when this value is false and entities will not be visible to scoped users. This occurs for Legacy policies created in Silverlight and can be resolved by deleting and recreating the policy in the Azure Portal. This property is read-only.|
|deviceManagementApplicabilityRuleOsEdition|deviceManagementApplicabilityRuleOsEdition|The OS edition applicability for this Policy.|
|deviceManagementApplicabilityRuleOsVersion|deviceManagementApplicabilityRuleOsVersion|The OS version applicability rule for this Policy.|
|deviceManagementApplicabilityRuleDeviceMode|deviceManagementApplicabilityRuleDeviceMode|The device mode applicability rule for this Policy.|
|createdDateTime|DateTimeOffset|DateTime the object was created.|
|description|String|Admin provided description of the Device Configuration.|
|displayName|String|Admin provided name of the device configuration.|
|version|Int32|Version of the device configuration.|
### [deviceEnrollmentConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-shared-deviceenrollmentconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the account|
|displayName|String|The display name of the device enrollment configuration|
|description|String|The description of the device enrollment configuration|
|priority|Int32|Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value.|
|createdDateTime|DateTimeOffset|Created date time in UTC of the device enrollment configuration|
|lastModifiedDateTime|DateTimeOffset|Last modified date time in UTC of the device enrollment configuration|
|version|Int32|The version of the device enrollment configuration|
### [deviceManagementDerivedCredentialSettings ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagementderivedcredentialsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the Derived Credential|
### [intune-shared-enablement](https://docs.microsoft.com/graph/api/resources/intune-shared-enablement?view=graph-rest-1.0&tabs=http)

### [intune-shared-enrollmentstate](https://docs.microsoft.com/graph/api/resources/intune-shared-enrollmentstate?view=graph-rest-1.0&tabs=http)

### [intune-shared-hashalgorithms](https://docs.microsoft.com/graph/api/resources/intune-shared-hashalgorithms?view=graph-rest-1.0&tabs=http)

### [intune-shared-keysize](https://docs.microsoft.com/graph/api/resources/intune-shared-keysize?view=graph-rest-1.0&tabs=http)

### [intune-shared-keystorageprovideroption](https://docs.microsoft.com/graph/api/resources/intune-shared-keystorageprovideroption?view=graph-rest-1.0&tabs=http)

### [intune-shared-keyusages](https://docs.microsoft.com/graph/api/resources/intune-shared-keyusages?view=graph-rest-1.0&tabs=http)

### [user ](https://docs.microsoft.com/graph/api/resources/intune-shared-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the user.|
|**Onboarding**|
|deviceEnrollmentLimit|Int32|The limit on the maximum number of devices that the user is permitted to enroll. Allowed values are 5 or 1000.|
### [intune-shared-vpptokenaccounttype](https://docs.microsoft.com/graph/api/resources/intune-shared-vpptokenaccounttype?view=graph-rest-1.0&tabs=http)

### [windowsAutopilotDeploymentProfile ](https://docs.microsoft.com/graph/api/resources/intune-shared-windowsautopilotdeploymentprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Profile Key|
|displayName|String|The display name of the deployment profile. Max allowed length is 200 chars. Returned by default. Supports: $select, $top, $skip, $orderby. $Search and $filter are not supported.|
|description|String|A description of the deployment profile. Max allowed length is 1500 chars. Supports: $select, $top, $skip, $orderBy. $Search and $filter are not supported.|
|language|String|The language code to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use locale instead.|
|locale|String|The locale (language) to be used when configuring the device. E.g. en-US. The default value is os-default. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|createdDateTime|DateTimeOffset|The date and time of when the deployment profile was created. The value cannot be modified and is automatically populated when the profile was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only.|
|lastModifiedDateTime|DateTimeOffset|The date and time of when the deployment profile was last modified. The value cannot be updated manually and is automatically populated when any changes are made to the profile. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported Read-Only.|
|outOfBoxExperienceSettings|outOfBoxExperienceSettings|The Windows Autopilot Deployment Profile settings used by the Autopilot device for out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use outOfBoxExperienceSetting instead.|
|outOfBoxExperienceSetting|outOfBoxExperienceSetting|The Windows Autopilot Deployment Profile settings used by the device for the out-of-box experience. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|enrollmentStatusScreenSettings|windowsEnrollmentStatusScreenSettings|Enrollment status screen setting|
|extractHardwareHash|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use hardwareHashExtractionEnabled instead.|
|hardwareHashExtractionEnabled|Boolean|Indicates whether the profile supports the extraction of hardware hash values and registration of the device into Windows Autopilot. When TRUE, indicates if hardware extraction and Windows Autopilot registration will happen on the next successful check-in. When FALSE, hardware hash extraction and Windows Autopilot registration will not happen. Default value is FALSE. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|deviceNameTemplate|String|The template used to name the Autopilot device. This can be a custom text and can also contain either the serial number of the device, or a randomly generated number. The total length of the text generated by the template can be no more than 15 characters. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
|deviceType|windowsAutopilotDeviceType|The Windows device type that this profile is applicable to. Possible values include windowsPc, holoLens, and virtualMachine. The default is windowsPc. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported. Possible values are: `windowsPc`, `holoLens`, `surfaceHub2`, `surfaceHub2S`, `virtualMachine`, `unknownFutureValue`.|
|enableWhiteGlove|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode is allowed. When false, Windows Autopilot for pre-provisioned deployment mode is not allowed. The default is FALSE. Read-Only. Starting from May 2024 this property will no longer be supported and will be marked as deprecated. Use preprovisioningAllowed instead.|
|preprovisioningAllowed|Boolean|Indicates whether the user is allowed to use Windows Autopilot for pre-provisioned deployment mode during Out of Box experience (OOBE). When TRUE, indicates that Windows Autopilot for pre-provisioned deployment mode for OOBE is allowed to be used. When false, Windows Autopilot for pre-provisioned deployment mode for OOBE is not allowed. The default is FALSE.|
|roleScopeTagIds|String collection|List of role scope tags for the deployment profile. |
|managementServiceAppId|String|The Entra management service App ID which gets used during client device-based enrollment discovery. Supports: $select, $top, $skip. $Search, $orderBy and $filter are not supported.|
### [windowsDomainJoinConfiguration ](https://docs.microsoft.com/graph/api/resources/intune-shared-windowsdomainjoinconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from deviceConfiguration|
|**Device configuration**|
|activeDirectoryDomainName|String|Active Directory domain name to join.|
|computerNameStaticPrefix|String|Fixed prefix to be used for computer name.|
|computerNameSuffixRandomCharCount|Int32|Dynamically generated characters used as suffix for computer name. Valid values 3 to 14|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from deviceConfiguration|
|description|String|Admin provided description of the Device Configuration. Inherited from deviceConfiguration|
|displayName|String|Admin provided name of the device configuration. Inherited from deviceConfiguration|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from deviceConfiguration|
|organizationalUnit|String|Organizational unit (OU) where the computer account will be created. If this parameter is NULL, the well known computer object container will be used as published in the domain.|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from deviceConfiguration|
|supportsScopeTags|Boolean|Indicates whether or not the underlying Device Configuration supports the assignment of scope tags. Assigning to the ScopeTags property is not allowed when this value is false and entities will not be visible to scoped users. This occurs for Legacy policies created in Silverlight and can be resolved by deleting and recreating the policy in the Azure Portal. This property is read-only. Inherited from deviceConfiguration|
|version|Int32|Version of the device configuration. Inherited from deviceConfiguration|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-tem-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
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
