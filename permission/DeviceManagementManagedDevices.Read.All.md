# DeviceManagementManagedDevices.Read.All

> Allows the app to read the properties of devices managed by Microsoft Intune.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET ** Collection URI for microsoft.management.services.api.deviceInventoryCollectionProperty not found](https://docs.microsoft.com/graph/api/intune-devices-deviceinventorycollectionproperty-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Collection URI for microsoft.management.services.api.deviceInventoryProperty not found](https://docs.microsoft.com/graph/api/intune-devices-deviceinventoryproperty-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Collection URI for microsoft.management.services.api.deviceInventorySimpleProperty not found](https://docs.microsoft.com/graph/api/intune-devices-deviceinventorysimpleproperty-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Entity URI for microsoft.management.services.api.deviceInventoryCollectionProperty not found](https://docs.microsoft.com/graph/api/intune-devices-deviceinventorycollectionproperty-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Entity URI for microsoft.management.services.api.deviceInventoryProperty not found](https://docs.microsoft.com/graph/api/intune-devices-deviceinventoryproperty-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET ** Entity URI for microsoft.management.services.api.deviceInventorySimpleProperty not found](https://docs.microsoft.com/graph/api/intune-devices-deviceinventorysimpleproperty-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement](https://docs.microsoft.com/graph/api/intune-shared-deviceappmanagement-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagementApp](https://docs.microsoft.com/graph/api/intune-devices-windowsmanagementapp-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagementApp/healthStates](https://docs.microsoft.com/graph/api/intune-devices-windowsmanagementapphealthstate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceAppManagement/windowsManagementApp/healthStates/{windowsManagementAppHealthStateId}](https://docs.microsoft.com/graph/api/intune-devices-windowsmanagementapphealthstate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement](https://docs.microsoft.com/graph/api/intune-devices-devicemanagement-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/applePushNotificationCertificate](https://docs.microsoft.com/graph/api/intune-devices-applepushnotificationcertificate-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/autopilotEvents](https://docs.microsoft.com/graph/api/intune-troubleshooting-devicemanagementautopilotevent-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/autopilotEvents/{deviceManagementAutopilotEventId}](https://docs.microsoft.com/graph/api/intune-troubleshooting-devicemanagementautopilotevent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/autopilotEvents/{deviceManagementAutopilotEventId}/policyStatusDetails](https://docs.microsoft.com/graph/api/intune-troubleshooting-devicemanagementautopilotpolicystatusdetail-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/autopilotEvents/{deviceManagementAutopilotEventId}/policyStatusDetails/{deviceManagementAutopilotPolicyStatusDetailId}](https://docs.microsoft.com/graph/api/intune-troubleshooting-devicemanagementautopilotpolicystatusdetail-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/cloudPCConnectivityIssues](https://docs.microsoft.com/graph/api/intune-devices-cloudpcconnectivityissue-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/cloudPCConnectivityIssues/{cloudPCConnectivityIssueId}](https://docs.microsoft.com/graph/api/intune-devices-cloudpcconnectivityissue-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagedDevices](https://docs.microsoft.com/graph/api/intune-devices-windowsmanageddevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagedDevices/{managedDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagedDevices/{managedDeviceId}/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagedDevices/{managedDeviceId}/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagedDevices/appDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-appdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagementEligibleDevices](https://docs.microsoft.com/graph/api/intune-devices-comanagementeligibledevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/comanagementEligibleDevices/{comanagementEligibleDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-comanagementeligibledevice-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps](https://docs.microsoft.com/graph/api/intune-devices-detectedapp-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}](https://docs.microsoft.com/graph/api/intune-devices-detectedapp-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/deviceCategory](https://docs.microsoft.com/graph/api/intune-devices-devicecategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/logCollectionRequests](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/logCollectionRequests/{deviceLogCollectionResponseId}](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/users](https://docs.microsoft.com/graph/api/intune-devices-user-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/users/{userId}](https://docs.microsoft.com/graph/api/intune-devices-user-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/users/{userId}/managedDevices](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/users/{userId}/managedDevices/{managedDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/windowsProtectionState](https://docs.microsoft.com/graph/api/intune-devices-windowsprotectionstate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/windowsProtectionState/detectedMalwareState](https://docs.microsoft.com/graph/api/intune-devices-windowsdevicemalwarestate-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/windowsProtectionState/detectedMalwareState/{windowsDeviceMalwareStateId}](https://docs.microsoft.com/graph/api/intune-devices-windowsdevicemalwarestate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceCategories](https://docs.microsoft.com/graph/api/intune-onboarding-devicecategory-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/deviceCategories/{deviceCategoryId}](https://docs.microsoft.com/graph/api/intune-onboarding-devicecategory-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts](https://docs.microsoft.com/graph/api/intune-devices-devicecompliancescript-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}](https://docs.microsoft.com/graph/api/intune-devices-devicecompliancescript-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicecompliancescriptdevicestate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicecompliancescriptdevicestate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/runSummary](https://docs.microsoft.com/graph/api/intune-devices-devicecompliancescriptrunsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts](https://docs.microsoft.com/graph/api/intune-devices-devicecustomattributeshellscript-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}](https://docs.microsoft.com/graph/api/intune-devices-devicecustomattributeshellscript-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/assignments](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/assignments/{deviceManagementScriptAssignmentId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/deviceRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/groupAssignments](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptgroupassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/groupAssignments/{deviceManagementScriptGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptgroupassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/runSummary](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptrunsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/userRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptuserstate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceCustomAttributeShellScripts/{deviceCustomAttributeShellScriptId}/userRunStates/{deviceManagementScriptUserStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptuserstate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/assignments](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/assignments/{deviceManagementScriptAssignmentId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps](https://docs.microsoft.com/graph/api/intune-devices-detectedapp-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}](https://docs.microsoft.com/graph/api/intune-devices-detectedapp-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices](https://docs.microsoft.com/graph/api/intune-devices-windowsmanageddevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/appDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-appdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/deviceCategory](https://docs.microsoft.com/graph/api/intune-devices-devicecategory-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/deviceInventories](https://docs.microsoft.com/graph/api/intune-devices-deviceinventory-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/deviceInventories/{deviceInventoryId}](https://docs.microsoft.com/graph/api/intune-devices-deviceinventory-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/deviceInventories/{deviceInventoryId}/instances](https://docs.microsoft.com/graph/api/intune-devices-deviceinventorysimpleitem-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/deviceInventories/{deviceInventoryId}/instances/{deviceInventoryItemId}](https://docs.microsoft.com/graph/api/intune-devices-deviceinventorysimpleitem-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/logCollectionRequests](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/logCollectionRequests/{deviceLogCollectionResponseId}](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users](https://docs.microsoft.com/graph/api/intune-devices-user-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}](https://docs.microsoft.com/graph/api/intune-devices-user-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices](https://docs.microsoft.com/graph/api/intune-devices-windowsmanageddevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/appDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-appdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/windowsProtectionState](https://docs.microsoft.com/graph/api/intune-devices-windowsprotectionstate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/windowsProtectionState/detectedMalwareState](https://docs.microsoft.com/graph/api/intune-devices-windowsdevicemalwarestate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/windowsProtectionState/detectedMalwareState/{windowsDeviceMalwareStateId}](https://docs.microsoft.com/graph/api/intune-devices-windowsdevicemalwarestate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/groupAssignments](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptgroupassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/groupAssignments/{deviceManagementScriptGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptgroupassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/runSummary](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptrunsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/userRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptuserstate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/userRunStates/{deviceManagementScriptUserStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptuserstate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/userRunStates/{deviceManagementScriptUserStateId}/deviceRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/userRunStates/{deviceManagementScriptUserStateId}/deviceRunStates/{deviceManagementScriptDeviceStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts](https://docs.microsoft.com/graph/api/intune-devices-deviceshellscript-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}](https://docs.microsoft.com/graph/api/intune-devices-deviceshellscript-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/assignments](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/assignments/{deviceManagementScriptAssignmentId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/deviceRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptdevicestate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/groupAssignments](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptgroupassignment-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/groupAssignments/{deviceManagementScriptGroupAssignmentId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptgroupassignment-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/runSummary](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptrunsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/userRunStates](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptuserstate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/deviceShellScripts/{deviceShellScriptId}/userRunStates/{deviceManagementScriptUserStateId}](https://docs.microsoft.com/graph/api/intune-devices-devicemanagementscriptuserstate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/getComanagedDevicesSummary](https://docs.microsoft.com/graph/api/intune-devices-devicemanagement-getcomanageddevicessummary?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/getComanagementEligibleDevicesSummary](https://docs.microsoft.com/graph/api/intune-devices-devicemanagement-getcomanagementeligibledevicessummary?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDeviceCleanupRules](https://docs.microsoft.com/graph/api/intune-devices-manageddevicecleanuprule-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDeviceCleanupRules/{managedDeviceCleanupRuleId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevicecleanuprule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/managedDeviceOverview](https://docs.microsoft.com/graph/api/intune-devices-manageddeviceoverview-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/managedDevices](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/managedDevices/{managedDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDevices/{managedDeviceId}/getFileVaultKey](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-getfilevaultkey?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDevices/{managedDeviceId}/retrieveDeviceLogsDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-retrievedevicelogsdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDevices/appDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-appdiagnostics?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/mobileAppTroubleshootingEvents](https://docs.microsoft.com/graph/api/intune-devices-mobileapptroubleshootingevent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/mobileAppTroubleshootingEvents/{mobileAppTroubleshootingEventId}](https://docs.microsoft.com/graph/api/intune-devices-mobileapptroubleshootingevent-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/mobileAppTroubleshootingEvents/{mobileAppTroubleshootingEventId}/appLogCollectionRequests](https://docs.microsoft.com/graph/api/intune-devices-applogcollectionrequest-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/mobileAppTroubleshootingEvents/{mobileAppTroubleshootingEventId}/appLogCollectionRequests/{appLogCollectionRequestId}](https://docs.microsoft.com/graph/api/intune-devices-applogcollectionrequest-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/remoteActionAudits](https://docs.microsoft.com/graph/api/intune-devices-remoteactionaudit-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/remoteActionAudits/{remoteActionAuditId}](https://docs.microsoft.com/graph/api/intune-devices-remoteactionaudit-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/reports](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/cachedReportConfigurations](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementcachedreportconfiguration-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/cachedReportConfigurations/{deviceManagementCachedReportConfigurationId}](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementcachedreportconfiguration-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/reports/exportJobs](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementexportjob-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/reports/exportJobs/{deviceManagementExportJobId}](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementexportjob-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/reportSchedules](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreportschedule-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/reports/reportSchedules/{deviceManagementReportScheduleId}](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreportschedule-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/tenantAttachRBAC](https://docs.microsoft.com/graph/api/intune-devices-tenantattachrbac-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/tenantAttachRBAC/getState](https://docs.microsoft.com/graph/api/intune-devices-tenantattachrbac-getstate?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/troubleshootingEvents](https://docs.microsoft.com/graph/api/intune-troubleshooting-devicemanagementtroubleshootingevent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/troubleshootingEvents/{deviceManagementTroubleshootingEventId}](https://docs.microsoft.com/graph/api/intune-troubleshooting-enrollmenttroubleshootingevent-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAnomaly](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsanomaly-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAnomaly/{userExperienceAnalyticsAnomalyId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsanomaly-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAnomalyCorrelationGroupOverview](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsanomalycorrelationgroupoverview-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAnomalyCorrelationGroupOverview/{userExperienceAnalyticsAnomalyCorrelationGroupOverviewId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsanomalycorrelationgroupoverview-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAnomalyDevice](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsanomalydevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAnomalyDevice/{userExperienceAnalyticsAnomalyDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsanomalydevice-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthapplicationperformance-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformance/{userExperienceAnalyticsAppHealthApplicationPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthapplicationperformance-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByAppVersion](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyappversion-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByAppVersion/{userExperienceAnalyticsAppHealthAppPerformanceByAppVersionId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyappversion-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByAppVersionDetails](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyappversiondetails-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByAppVersionDetails/{userExperienceAnalyticsAppHealthAppPerformanceByAppVersionDetailsId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyappversiondetails-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByAppVersionDeviceId](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyappversiondeviceid-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByAppVersionDeviceId/{userExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceIdId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyappversiondeviceid-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByOSVersion](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyosversion-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthApplicationPerformanceByOSVersion/{userExperienceAnalyticsAppHealthAppPerformanceByOSVersionId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthappperformancebyosversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthDeviceModelPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthdevicemodelperformance-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthDeviceModelPerformance/{userExperienceAnalyticsAppHealthDeviceModelPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthdevicemodelperformance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthDevicePerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthdeviceperformance-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthDevicePerformance/{userExperienceAnalyticsAppHealthDevicePerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthdeviceperformance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthDevicePerformanceDetails](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthdeviceperformancedetails-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthDevicePerformanceDetails/{userExperienceAnalyticsAppHealthDevicePerformanceDetailsId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthdeviceperformancedetails-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthOSVersionPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthosversionperformance-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthOSVersionPerformance/{userExperienceAnalyticsAppHealthOSVersionPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsapphealthosversionperformance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsAppHealthOverview](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbaseline-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbaseline-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/appHealthMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/batteryHealthMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/bestPracticesMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/deviceBootPerformanceMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/deviceBootPerformanceMetrics/metricValues](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetric-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/deviceBootPerformanceMetrics/metricValues/{userExperienceAnalyticsMetricId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetric-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/rebootAnalyticsMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/resourcePerformanceMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsBaselines/{userExperienceAnalyticsBaselineId}/workFromAnywhereMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthAppImpact](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthappimpact-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthAppImpact/{userExperienceAnalyticsBatteryHealthAppImpactId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthappimpact-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthCapacityDetails](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthcapacitydetails-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthDeviceAppImpact](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthdeviceappimpact-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthDeviceAppImpact/{userExperienceAnalyticsBatteryHealthDeviceAppImpactId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthdeviceappimpact-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthDevicePerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthdeviceperformance-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthDevicePerformance/{userExperienceAnalyticsBatteryHealthDevicePerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthdeviceperformance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthDeviceRuntimeHistory](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthdeviceruntimehistory-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthDeviceRuntimeHistory/{userExperienceAnalyticsBatteryHealthDeviceRuntimeHistoryId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthdeviceruntimehistory-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthModelPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthmodelperformance-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthModelPerformance/{userExperienceAnalyticsBatteryHealthModelPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthmodelperformance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthOsPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthosperformance-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthOsPerformance/{userExperienceAnalyticsBatteryHealthOsPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthosperformance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsBatteryHealthRuntimeDetails](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsbatteryhealthruntimedetails-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsCategories/{userExperienceAnalyticsCategoryId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticscategory-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceMetricHistory](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetrichistory-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceMetricHistory/{userExperienceAnalyticsMetricHistoryId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetrichistory-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDevicePerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdeviceperformance-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDevicePerformance/{userExperienceAnalyticsDevicePerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdeviceperformance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDevicePerformance/summarizeDevicePerformanceDevices](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdeviceperformance-summarizedeviceperformancedevices?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceScope](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescope-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceScopes](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescope-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceScopes/{userExperienceAnalyticsDeviceScopeId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescope-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceScores](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescores-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceScores/{userExperienceAnalyticsDeviceScoresId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescores-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceStartupHistory](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicestartuphistory-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceStartupHistory/{userExperienceAnalyticsDeviceStartupHistoryId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicestartuphistory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceStartupProcesses](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicestartupprocess-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceStartupProcesses/{userExperienceAnalyticsDeviceStartupProcessId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicestartupprocess-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceStartupProcessPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicestartupprocessperformance-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceStartupProcessPerformance/{userExperienceAnalyticsDeviceStartupProcessPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicestartupprocessperformance-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDevicesWithoutCloudIdentity](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicewithoutcloudidentity-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDevicesWithoutCloudIdentity/{userExperienceAnalyticsDeviceWithoutCloudIdentityId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicewithoutcloudidentity-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceTimelineEvent](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicetimelineevent-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceTimelineEvent/{userExperienceAnalyticsDeviceTimelineEventId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicetimelineevent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsDeviceTimelineEvents/{userExperienceAnalyticsDeviceTimelineEventsId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicetimelineevents-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsImpactingProcess](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsimpactingprocess-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsImpactingProcess/{userExperienceAnalyticsImpactingProcessId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsimpactingprocess-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsMetricHistory](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetrichistory-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsMetricHistory/{userExperienceAnalyticsMetricHistoryId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetrichistory-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsMetricHistory/{userExperienceAnalyticsMetricHistoryId}/userExperienceAnalyticsMetric](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmetric-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsModelScores](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmodelscores-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsModelScores/{userExperienceAnalyticsModelScoresId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsmodelscores-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsNotAutopilotReadyDevice](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsnotautopilotreadydevice-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsNotAutopilotReadyDevice/{userExperienceAnalyticsNotAutopilotReadyDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsnotautopilotreadydevice-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsOverview](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsoverview-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsRegressionSummary](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsregressionsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsRegressionSummary/summarizeDeviceRegressionPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsregressionsummary-summarizedeviceregressionperformance?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsRemoteConnection](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsremoteconnection-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsRemoteConnection/{userExperienceAnalyticsRemoteConnectionId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsremoteconnection-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsResourcePerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsresourceperformance-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsResourcePerformance/{userExperienceAnalyticsResourcePerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsresourceperformance-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsScoreHistory](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsscorehistory-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsScoreHistory/{userExperienceAnalyticsScoreHistoryId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsscorehistory-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/userExperienceAnalyticsSummarizedDeviceScopes](https://docs.microsoft.com/graph/api/intune-devices-devicemanagement-userexperienceanalyticssummarizeddevicescopes?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereHardwareReadinessMetric](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywherehardwarereadinessmetric-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereMetrics](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywheremetric-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereMetrics/{userExperienceAnalyticsWorkFromAnywhereMetricId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywheremetric-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereMetrics/{userExperienceAnalyticsWorkFromAnywhereMetricId}/metricDevices](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywheredevice-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereMetrics/{userExperienceAnalyticsWorkFromAnywhereMetricId}/metricDevices/{userExperienceAnalyticsWorkFromAnywhereDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywheredevice-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereModelPerformance](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywheremodelperformance-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/userExperienceAnalyticsWorkFromAnywhereModelPerformance/{userExperienceAnalyticsWorkFromAnywhereModelPerformanceId}](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsworkfromanywheremodelperformance-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsMalwareInformation](https://docs.microsoft.com/graph/api/intune-devices-windowsmalwareinformation-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsMalwareInformation/{windowsMalwareInformationId}](https://docs.microsoft.com/graph/api/intune-devices-windowsmalwareinformation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsMalwareInformation/{windowsMalwareInformationId}/deviceMalwareStates](https://docs.microsoft.com/graph/api/intune-devices-malwarestateforwindowsdevice-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/windowsMalwareInformation/{windowsMalwareInformationId}/deviceMalwareStates/{malwareStateForWindowsDeviceId}](https://docs.microsoft.com/graph/api/intune-devices-malwarestateforwindowsdevice-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports](https://docs.microsoft.com/graph/api/intune-troubleshooting-reportroot-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/managedDeviceEnrollmentAbandonmentDetails](https://docs.microsoft.com/graph/api/intune-shared-reportroot-manageddeviceenrollmentabandonmentdetails?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/managedDeviceEnrollmentAbandonmentSummary](https://docs.microsoft.com/graph/api/intune-shared-reportroot-manageddeviceenrollmentabandonmentsummary?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/deviceCompliancePolicySettingStateSummaries](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-devicecompliancepolicysettingstatesummary?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managedDeviceCompliances](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-manageddevicecompliances?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managedDeviceCompliances/{managedDeviceComplianceId}](https://docs.microsoft.com/graph/api/managedtenants-manageddevicecompliance-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managedDeviceComplianceTrends](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-manageddevicecompliancetrends?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/managedDeviceComplianceTrends/{managedDeviceComplianceTrendId}](https://docs.microsoft.com/graph/api/managedtenants-manageddevicecompliancetrend-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/windowsDeviceMalwareStates](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-windowsdevicemalwarestates?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/windowsDeviceMalwareStates/{windowsDeviceMalwareStateId}](https://docs.microsoft.com/graph/api/managedtenants-windowsdevicemalwarestate-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/windowsProtectionStates](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-windowsprotectionstates?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/windowsProtectionStates/{windowsProtectionStateId}](https://docs.microsoft.com/graph/api/managedtenants-windowsprotectionstate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users](https://docs.microsoft.com/graph/api/intune-troubleshooting-user-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{usersId}](https://docs.microsoft.com/graph/api/intune-troubleshooting-user-get?view=graph-rest-1.0&tabs=http)|
|Beta||[GET /users/{usersId}/getLoggedOnManagedDevices](https://docs.microsoft.com/graph/api/intune-shared-user-getloggedonmanageddevices?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{usersId}/getManagedDevicesWithAppFailures](https://docs.microsoft.com/graph/api/intune-troubleshooting-user-getmanageddeviceswithappfailures?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/getManagedDevicesWithFailedOrPendingApps](https://docs.microsoft.com/graph/api/intune-troubleshooting-user-getmanageddeviceswithfailedorpendingapps?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/mobileAppIntentAndStates](https://docs.microsoft.com/graph/api/intune-troubleshooting-mobileappintentandstate-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/mobileAppIntentAndStates/{mobileAppIntentAndStateId}](https://docs.microsoft.com/graph/api/intune-troubleshooting-mobileappintentandstate-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/mobileAppTroubleshootingEvents](https://docs.microsoft.com/graph/api/intune-shared-mobileapptroubleshootingevent-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{usersId}/mobileAppTroubleshootingEvents/{mobileAppTroubleshootingEventId}](https://docs.microsoft.com/graph/api/intune-shared-mobileapptroubleshootingevent-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceAppManagement/windowsManagementApp/setAsManagedInstaller](https://docs.microsoft.com/graph/api/intune-devices-windowsmanagementapp-setasmanagedinstaller?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/{managedDeviceId}/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/downloadAppDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-downloadappdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/executeAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-executeaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/comanagedDevices/moveDevicesToOU](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-movedevicestoou?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/logCollectionRequests/{deviceLogCollectionResponseId}/createDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-createdownloadurl?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceComplianceScripts/{deviceComplianceScriptId}/deviceRunStates/{deviceComplianceScriptDeviceStateId}/managedDevice/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceHealthScripts/{deviceHealthScriptId}/deviceRunStates/{deviceHealthScriptDeviceStateId}/managedDevice/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/downloadAppDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-downloadappdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/executeAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-executeaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/detectedApps/{detectedAppId}/managedDevices/moveDevicesToOU](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-movedevicestoou?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/logCollectionRequests/{deviceLogCollectionResponseId}/createDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-createdownloadurl?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/logCollectionRequests/{deviceLogCollectionResponseId}/downloadDeviceLogs](https://docs.microsoft.com/graph/api/intune-devices-devicelogcollectionresponse-downloaddevicelogs?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/{managedDeviceId}/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/downloadAppDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-downloadappdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/executeAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-executeaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/deviceRunStates/{deviceManagementScriptDeviceStateId}/managedDevice/users/{userId}/managedDevices/moveDevicesToOU](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-movedevicestoou?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/activateDeviceEsim](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-activatedeviceesim?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/changeAssignments](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-changeassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/deprovision](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-deprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/disable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-disable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/enrollNowAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-enrollnowaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/initiateDeviceAttestation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatedeviceattestation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/initiateMobileDeviceManagementKeyRecovery](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiatemobiledevicemanagementkeyrecovery?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/initiateOnDemandProactiveRemediation](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-initiateondemandproactiveremediation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/pauseConfigurationRefresh](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-pauseconfigurationrefresh?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/reenable](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-reenable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/removeDeviceFirmwareConfigurationInterfaceManagement](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-removedevicefirmwareconfigurationinterfacemanagement?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/rotateLocalAdminPassword](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-rotatelocaladminpassword?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/downloadAppDiagnostics](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-downloadappdiagnostics?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/executeAction](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-executeaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/moveDevicesToOU](https://docs.microsoft.com/graph/api/intune-devices-manageddevice-movedevicestoou?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/mobileAppTroubleshootingEvents/{mobileAppTroubleshootingEventId}/appLogCollectionRequests/{appLogCollectionRequestId}/createDownloadUrl](https://docs.microsoft.com/graph/api/intune-devices-applogcollectionrequest-createdownloadurl?view=graph-rest-1.0&tabs=http)|
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
|V1|A,D|[POST /deviceManagement/reports/getNoncompliantDevicesAndSettingsReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getnoncompliantdevicesandsettingsreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getPolicyNonComplianceMetadata](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getpolicynoncompliancemetadata?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getPolicyNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getpolicynoncompliancereport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getPolicyNonComplianceSummaryReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getpolicynoncompliancesummaryreport?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getReportFilters](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getreportfilters?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/reports/getSettingComplianceAggReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getsettingcomplianceaggreport?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/reports/getSettingNonComplianceReport](https://docs.microsoft.com/graph/api/intune-reporting-devicemanagementreports-getsettingnoncompliancereport?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/tenantAttachRBAC/enable](https://docs.microsoft.com/graph/api/intune-devices-tenantattachrbac-enable?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/userExperienceAnalyticsDeviceScope/triggerDeviceScopeAction](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescope-triggerdevicescopeaction?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/userExperienceAnalyticsDeviceScopes/{userExperienceAnalyticsDeviceScopeId}/triggerDeviceScopeAction](https://docs.microsoft.com/graph/api/intune-devices-userexperienceanalyticsdevicescope-triggerdevicescopeaction?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|314874da-47d6-4978-88dc-cf0d37f0bb82|
|**Consent Type**|Admin|
|**Display String**|Read Microsoft Intune devices|
|**Description**|Allows the app to read the properties of devices managed by Microsoft Intune.|
## Application Permission
|||
|-|-|
|**Id**|2f51be20-0bb4-4fed-bf7b-db946066c75e|
|**Display String**|Read Microsoft Intune devices|
|**Description**|Allows the app to read the properties of devices managed by Microsoft Intune, without a signed-in user.|
## Resources
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
### [appLogCollectionDownloadDetails ](https://docs.microsoft.com/graph/api/resources/intune-devices-applogcollectiondownloaddetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|downloadUrl|String|Download SAS (Shared Access Signature) Url for completed app log request.|
|decryptionKey|String|Decryption key that used to decrypt the log.|
|appLogDecryptionAlgorithm|appLogDecryptionAlgorithm|Decryption algorithm for Content. Default is ASE256. Possible values are: `aes256`, `unknownFutureValue`.|
### [appLogCollectionRequest ](https://docs.microsoft.com/graph/api/resources/intune-devices-applogcollectionrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique Identifier. This is userId_DeviceId_AppId id.|
|status|appLogUploadState|Indicates the status for the app log collection request if it is pending, completed or failed, Default is pending. Possible values are: `pending`, `completed`, `failed`, `unknownFutureValue`.|
|errorMessage|String|Indicates error message if any during the upload process.|
|customLogFolders|String collection|List of log folders.|
|completedDateTime|DateTimeOffset|Time at which the upload log request reached a completed state if not completed yet NULL will be returned.|
### [bulkManagedDeviceActionResult ](https://docs.microsoft.com/graph/api/resources/intune-devices-bulkmanageddeviceactionresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|successfulDeviceIds|String collection|Successful devices|
|failedDeviceIds|String collection|Failed devices|
|notFoundDeviceIds|String collection|Not found devices|
|notSupportedDeviceIds|String collection|Not supported devices|
### [cloudPCConnectivityIssue ](https://docs.microsoft.com/graph/api/resources/intune-devices-cloudpcconnectivityissue?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics connectivity issue event entity.|
|deviceId|String|The Intune DeviceId of the device the connection is associated with.|
|errorCode|String|The error code of the connectivity issue.|
|errorDateTime|DateTimeOffset|The time that the connection initiated. The time is shown in ISO 8601 format and Coordinated Universal Time (UTC) time.|
|userId|String|The unique id of user who initialize the connection.|
|errorDescription|String|The detailed description of what went wrong.|
|recommendedAction|String|The recommended action to fix the corresponding error.|
### [comanagedDevicesSummary ](https://docs.microsoft.com/graph/api/resources/intune-devices-comanageddevicessummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|inventoryCount|Int32|Number of devices with Inventory swung-over. This property is read-only.|
|compliancePolicyCount|Int32|Number of devices with CompliancePolicy swung-over. This property is read-only.|
|resourceAccessCount|Int32|Number of devices with ResourceAccess swung-over. This property is read-only.|
|configurationSettingsCount|Int32|Number of devices with ConfigurationSettings swung-over. This property is read-only.|
|windowsUpdateForBusinessCount|Int32|Number of devices with WindowsUpdateForBusiness swung-over. This property is read-only.|
|endpointProtectionCount|Int32|Number of devices with EndpointProtection swung-over. This property is read-only.|
|modernAppsCount|Int32|Number of devices with ModernApps swung-over. This property is read-only.|
|officeAppsCount|Int32|Number of devices with OfficeApps swung-over. This property is read-only.|
|totalComanagedCount|Int32|Number of Co-Managed Devices. This property is read-only.|
### [comanagementEligibleDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-comanagementeligibledevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Id for the device|
|deviceName|String|DeviceName|
|deviceType|deviceType|DeviceType. Possible values are: `desktop`, `windowsRT`, `winMO6`, `nokia`, `windowsPhone`, `mac`, `winCE`, `winEmbedded`, `iPhone`, `iPad`, `iPod`, `android`, `iSocConsumer`, `unix`, `macMDM`, `holoLens`, `surfaceHub`, `androidForWork`, `androidEnterprise`, `windows10x`, `androidnGMS`, `chromeOS`, `linux`, `blackberry`, `palm`, `unknown`, `cloudPC`.|
|clientRegistrationStatus|deviceRegistrationState|ClientRegistrationStatus. Possible values are: `notRegistered`, `registered`, `revoked`, `keyConflict`, `approvalPending`, `certificateReset`, `notRegisteredPendingEnrollment`, `unknown`.|
|ownerType|ownerType|OwnerType. Possible values are: `unknown`, `company`, `personal`.|
|managementAgents|managementAgentType|ManagementAgents. Possible values are: `eas`, `mdm`, `easMdm`, `intuneClient`, `easIntuneClient`, `configurationManagerClient`, `configurationManagerClientMdm`, `configurationManagerClientMdmEas`, `unknown`, `jamf`, `googleCloudDevicePolicyController`, `microsoft365ManagedMdm`, `msSense`, `intuneAosp`, `google`, `unknownFutureValue`.|
|managementState|managementState|ManagementState. Possible values are: `managed`, `retirePending`, `retireFailed`, `wipePending`, `wipeFailed`, `unhealthy`, `deletePending`, `retireIssued`, `wipeIssued`, `wipeCanceled`, `retireCanceled`, `discovered`.|
|referenceId|String|ReferenceId|
|mdmStatus|String|MDMStatus|
|osVersion|String|OSVersion|
|serialNumber|String|SerialNumber|
|manufacturer|String|Manufacturer|
|model|String|Model|
|osDescription|String|OSDescription|
|entitySource|Int32|EntitySource|
|userId|String|UserId|
|upn|String|UPN|
|userEmail|String|UserEmail|
|userName|String|UserName|
|status|comanagementEligibleType|ComanagementEligibleStatus. Possible values are: `comanaged`, `eligible`, `eligibleButNotAzureAdJoined`, `needsOsUpdate`, `ineligible`, `scheduledForEnrollment`, `unknownFutureValue`.|
### [comanagementEligibleDevicesSummary ](https://docs.microsoft.com/graph/api/resources/intune-devices-comanagementeligibledevicessummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|comanagedCount|Int32|Count of devices already Co-Managed|
|eligibleCount|Int32|Count of devices fully eligible for Co-Management|
|scheduledForEnrollmentCount|Int32|Count of devices scheduled for Co-Management enrollment. Valid values 0 to 9999999|
|eligibleButNotAzureAdJoinedCount|Int32|Count of devices eligible for Co-Management but not yet joined to Azure Active Directory|
|needsOsUpdateCount|Int32|Count of devices that will be eligible for Co-Management after an OS update|
|ineligibleCount|Int32|Count of devices ineligible for Co-Management|
### [detectedApp ](https://docs.microsoft.com/graph/api/resources/intune-devices-detectedapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique Identifier for the detected application. This is automatically generated by Intune at the time the application is created. Read-only.|
|displayName|String|Name of the discovered application. Read-only|
|version|String|Version of the discovered application. Read-only|
|sizeInByte|Int64|Discovered application size in bytes. Read-only|
|deviceCount|Int32|The number of devices that have installed this application|
|publisher|String|Indicates the publisher of the discovered application. For example: 'Microsoft'.  The default value is an empty string.|
|platform|detectedAppPlatformType|Indicates the operating system / platform of the discovered application.  Some possible values are Windows, iOS, macOS. The default value is unknown (0). Possible values are: `unknown`, `windows`, `windowsMobile`, `windowsHolographic`, `ios`, `macOS`, `chromeOS`, `androidOSP`, `androidDeviceAdministrator`, `androidWorkProfile`, `androidDedicatedAndFullyManaged`, `unknownFutureValue`.|
### [deviceAppManagement ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceappmanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
### [deviceAssignmentItem ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceassignmentitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|itemId|String|The unique identifier for the application or configuration. ItemId is required property which needs to be set in the action POST request parameter for the DeviceAssignmentItem intended to remove. Max length is 40|
|itemType|deviceAssignmentItemType|Indicates the application or configuration type. ItemType is required property which needs to be set in the action POST request parameter for the DeviceAssignmentItem intended to remove. Possible values are: application, deviceConfiguration, deviceManagementConfigurationPolicy, mobileAppConfiguration. application itemType is default value. Possible values are: `application`, `deviceConfiguration`, `deviceManagementConfigurationPolicy`, `mobileAppConfiguration`, `unknownFutureValue`.|
|itemSubTypeDisplayName|String|Indicates the specific type for the application or configuration. For example, unknown, application, appConfiguration, exploitProtection, bitLocker, deviceControl, microsoftEdgeBaseline, attackSurfaceReductionRulesConfigMgr, endpointDetectionandResponse, windowsUpdateforBusiness, microsoftDefenderFirewallRules, applicationControl, microsoftDefenderAntivirusexclusions, microsoftDefenderAntivirus, wiredNetwork, derivedPersonalIdentityVerificationCredential, windowsHealthMonitoring, extensions, mxProfileZebraOnly, deviceFirmwareConfigurationInterface, deliveryOptimization, identityProtection, kiosk, overrideGroupPolicy, domainJoinPreview, pkcsImportedCertificate, networkBoundary, endpointProtection, microsoftDefenderAtpWindows10Desktop, sharedMultiUserDevice, deviceFeatures, secureAssessmentEducation, wiFiImport, editionUpgradeAndModeSwitch, vpn, custom, softwareUpdates, deviceRestrictionsWindows10Team, email, trustedCertificate, scepCertificate, emailSamsungKnoxOnly, pkcsCertificate, deviceRestrictions, wiFi, settingsCatalog. Read-Only. Returned in the action result. Default value is null. The property value cannot be modified and is automatically populated with the action result. Max length is 200. This property is read-only.|
|itemDisplayName|String|The item displayName name for the application or configuration. Read-Only. Returned in the action result. Default value is null. The property value cannot be modified and is automatically populated with the action result. Max length is 200. This property is read-only.|
|assignmentItemActionIntent|deviceAssignmentItemIntent|Indicates the IT Admin's intent on the application or configuration when executing this action on the managed device. Intent needs to be set as default value remove in the action POST request parameter. For the application or configuration intended to remove through previous actions but not included in current action, its intent will be reported as restore in the action result. Possible values are: remove, restore. remove intent is default value. This property is read-only. Possible values are: `remove`, `restore`, `unknownFutureValue`.|
|assignmentItemActionStatus|deviceAssignmentItemStatus|Indicates the live status for the application or configuration regarding the executed action on the managed device. Read-Only. Returned in the action result. Possible values are: initiated, inProgress, removed, error, succeeded. initiated status is default value. This property is read-only. Possible values are: `initiated`, `inProgress`, `removed`, `error`, `succeeded`, `unknownFutureValue`.|
|intentActionMessage|String|The intent action message for the application or configuration regarding the executed action on the managed device. When the action is on error, this property provides message on the reason of failure. When the action is in progress, this property provides message on what's being processed on the device. Read-Only. Returned in the action result. Can be null. Max length is 1500. This property is read-only.|
|errorCode|Int64|The error code for the application or configuration regarding the failed executed action on the managed device. Read-Only. Returned in the action result. 0 is default value and indicates no failure. Valid values -9.22337203685478E+18 to 9.22337203685478E+18. This property is read-only.|
|lastActionDateTime|DateTimeOffset|The date and time when the application or configuration was initiated an action execution. Read-Only. Returned in the action result. The property value cannot be modified and is automatically populated when the action is initiated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2025 would look like this: '2025-01-01T00:00:00Z'. This property is read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the application or configuration was last modified because of either action execution or status change. Read-Only. Returned in the action result. The property value cannot be modified and is automatically populated when the action is initiated or the device has a status change. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2025 would look like this: '2025-01-01T00:00:00Z'. This property is read-only.|
### [deviceCategory ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicecategory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the device category. Read-only.|
### [deviceComplianceScript ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicecompliancescript?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the device compliance script|
|publisher|String|Name of the device compliance script publisher|
|version|String|Version of the device compliance script|
|displayName|String|Name of the device compliance script|
|description|String|Description of the device compliance script|
|detectionScriptContent|Binary|The entire content of the detection powershell script|
|createdDateTime|DateTimeOffset|The timestamp of when the device compliance script was created. This property is read-only.|
|lastModifiedDateTime|DateTimeOffset|The timestamp of when the device compliance script was modified. This property is read-only.|
|runAsAccount|runAsAccountType|Indicates the type of execution context. Possible values are: `system`, `user`.|
|enforceSignatureCheck|Boolean|Indicate whether the script signature needs be checked|
|runAs32Bit|Boolean|Indicate whether PowerShell script(s) should run as 32-bit|
|roleScopeTagIds|String collection|List of Scope Tag IDs for the device compliance script|
### [deviceComplianceScriptDeviceState ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicecompliancescriptdevicestate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device compliance script device state entity. This property is read-only.|
|detectionState|runState|Detection state from the lastest device compliance script execution. Possible values are: `unknown`, `success`, `fail`, `scriptError`, `pending`, `notApplicable`.|
|lastStateUpdateDateTime|DateTimeOffset|The last timestamp of when the device compliance script executed|
|expectedStateUpdateDateTime|DateTimeOffset|The next timestamp of when the device compliance script is expected to execute|
|lastSyncDateTime|DateTimeOffset|The last time that Intune Managment Extension synced with Intune|
|scriptOutput|String|Output of the detection script|
|scriptError|String|Error from the detection script|
### [deviceComplianceScriptRunSummary ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicecompliancescriptrunsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device compliance script run summary entity. This property is read-only.|
|noIssueDetectedDeviceCount|Int32|Number of devices for which the detection script did not find an issue and the device is healthy. Valid values -2147483648 to 2147483647|
|issueDetectedDeviceCount|Int32|Number of devices for which the detection script found an issue. Valid values -2147483648 to 2147483647|
|detectionScriptErrorDeviceCount|Int32|Number of devices on which the detection script execution encountered an error and did not complete. Valid values -2147483648 to 2147483647|
|detectionScriptPendingDeviceCount|Int32|Number of devices which have not yet run the latest version of the device compliance script. Valid values -2147483648 to 2147483647|
|lastScriptRunDateTime|DateTimeOffset|Last run time for the script across all devices|
### [deviceCustomAttributeShellScript ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicecustomattributeshellscript?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the custom attribute entity.|
|customAttributeName|String|The name of the custom attribute.|
|customAttributeType|deviceCustomAttributeValueType|The expected type of the custom attribute's value. Possible values are: `integer`, `string`, `dateTime`.|
|displayName|String|Name of the device management script.|
|description|String|Optional description for the device management script.|
|scriptContent|Binary|The script content.|
|createdDateTime|DateTimeOffset|The date and time the device management script was created. This property is read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time the device management script was last modified. This property is read-only.|
|runAsAccount|runAsAccountType|Indicates the type of execution context. Possible values are: `system`, `user`.|
|fileName|String|Script file name.|
|roleScopeTagIds|String collection|List of Scope Tag IDs for this PowerShellScript instance.|
### [deviceInventory ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceinventory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique catalog id for this inventory entity type|
|displayName|String|The localized display name of the entity. Example: "Disk Drives". This property is read-only.|
|lastSyncDateTime|DateTimeOffset|The date and time that the inventory data was last synced with Intune. The value cannot be modified and is automatically populated when the device performs a sync. The Timestamp type represents date and time information and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Read-only. This property is read-only.|
### [deviceInventoryCollectionProperty ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceinventorycollectionproperty?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The catalog id for this inventory property type Inherited from deviceInventoryProperty|
|displayName|String|The localized display name of the property. Example: "Size (MB)". This property is read-only. Inherited from deviceInventoryProperty|
|values|deviceInventoryValue collection|Collection value of the property. This property is read-only.|
### [deviceInventoryItem ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceinventoryitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|A unique identifier for the inventory data|
### [deviceInventoryProperty ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceinventoryproperty?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The catalog id for this inventory property type|
|displayName|String|The localized display name of the property. Example: "Size (MB)". This property is read-only.|
### [deviceInventorySimpleItem ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceinventorysimpleitem?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|A unique identifier for the inventory data Inherited from deviceInventoryItem|
### [deviceInventorySimpleProperty ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceinventorysimpleproperty?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The catalog id for this inventory property type Inherited from deviceInventoryProperty|
|displayName|String|The localized display name of the property. Example: "Size (MB)". This property is read-only. Inherited from deviceInventoryProperty|
|value|deviceInventoryValue|Value of the property. This property is read-only.|
### [deviceLogCollectionResponse ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicelogcollectionresponse?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier in the form of tenantId_deviceId_requestId.|
|status|appLogUploadState|Indicates the status for the app log collection request if it is pending, completed or failed, Default is pending. Possible values are: `pending`, `completed`, `failed`, `unknownFutureValue`.|
|managedDeviceId|Guid|Indicates Intune device unique identifier.|
|requestedDateTimeUTC|DateTimeOffset|The DateTime of the request.|
|receivedDateTimeUTC|DateTimeOffset|The DateTime the request was received.|
|initiatedByUserPrincipalName|String|The UPN for who initiated the request.|
|expirationDateTimeUTC|DateTimeOffset|The DateTime of the expiration of the logs.|
|sizeInKB|Double|The size of the logs in KB. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|enrolledByUser|String|The User Principal Name (UPN) of the user that enrolled the device.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the device|
|subscriptionState|deviceManagementSubscriptionState|Tenant mobile device management subscription state. Possible values are: `pending`, `active`, `warning`, `disabled`, `deleted`, `blocked`, `lockedOut`.|
|deviceProtectionOverview|deviceProtectionOverview|Device protection overview.|
|windowsMalwareOverview|windowsMalwareOverview|Malware overview for windows devices.|
|userExperienceAnalyticsSettings|userExperienceAnalyticsSettings|User experience analytics device settings|
### [deviceManagementScriptAssignment ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicemanagementscriptassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device management script group assignment entity. This property is read-only.|
|target|deviceAndAppManagementAssignmentTarget|The Id of the Azure Active Directory group we are targeting the script to.|
### [deviceManagementScriptDeviceState ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicemanagementscriptdevicestate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device management script device state entity. This property is read-only.|
|runState|runState|State of latest run of the device management script. Possible values are: `unknown`, `success`, `fail`, `scriptError`, `pending`, `notApplicable`.|
|resultMessage|String|Details of execution output.|
|lastStateUpdateDateTime|DateTimeOffset|Latest time the device management script executes.|
|errorCode|Int32|Error code corresponding to erroneous execution of the device management script.|
|errorDescription|String|Error description corresponding to erroneous execution of the device management script.|
### [deviceManagementScriptGroupAssignment ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicemanagementscriptgroupassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device management script group assignment entity. This property is read-only.|
|targetGroupId|String|The Id of the Azure Active Directory group we are targeting the script to.|
### [deviceManagementScriptRunSummary ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicemanagementscriptrunsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device management script run summary entity. This property is read-only.|
|successDeviceCount|Int32|Success device count.|
|errorDeviceCount|Int32|Error device count.|
|successUserCount|Int32|Success user count.|
|errorUserCount|Int32|Error user count.|
### [deviceManagementScriptUserState ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicemanagementscriptuserstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the device management script user state entity. This property is read-only.|
|successDeviceCount|Int32|Success device count for specific user.|
|errorDeviceCount|Int32|Error device count for specific user.|
|userPrincipalName|String|User principle name of specific user.|
### [deviceScopeActionResult ](https://docs.microsoft.com/graph/api/resources/intune-devices-devicescopeactionresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceScopeAction|deviceScopeAction|The triggered action name. Possible values are: .|
|deviceScopeId|String|The unique identifier of the device scope the action was triggered on.|
|status|deviceScopeActionStatus|Indicates the status of the attempt device scope action. When succeeded, the action was succeessfully triggered, When failed, the action was failed to trigger. Possible values are: `failed`, `succeeded`, `unknownFutureValue`.|
|failedMessage|String|The message indicates the reason the device scope action failed to trigger.|
### [deviceShellScript ](https://docs.microsoft.com/graph/api/resources/intune-devices-deviceshellscript?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|executionFrequency|Duration|The interval for script to run. If not defined the script will run once|
|retryCount|Int32|Number of times for the script to be retried if it fails|
|blockExecutionNotifications|Boolean|Does not notify the user a script is being executed|
|id|String|Unique Identifier for the device management script.|
|displayName|String|Name of the device management script.|
|description|String|Optional description for the device management script.|
|scriptContent|Binary|The script content.|
|createdDateTime|DateTimeOffset|The date and time the device management script was created. This property is read-only.|
|lastModifiedDateTime|DateTimeOffset|The date and time the device management script was last modified. This property is read-only.|
|runAsAccount|runAsAccountType|Indicates the type of execution context. Possible values are: `system`, `user`.|
|fileName|String|Script file name.|
|roleScopeTagIds|String collection|List of Scope Tag IDs for this PowerShellScript instance.|
### [malwareStateForWindowsDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-malwarestateforwindowsdevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique Identifier. This is device id.|
|deviceName|String|Indicates the name of the device being evaluated for malware state|
|executionState|windowsMalwareExecutionState|Indicates execution status of the malware. Possible values are: unknown, blocked, allowed, running, notRunning. Defaults to unknown. Possible values are: `unknown`, `blocked`, `allowed`, `running`, `notRunning`.|
|threatState|windowsMalwareThreatState|Indicates threat status of the malware. Possible values are: active, actionFailed, manualStepsRequired, fullScanRequired, rebootRequired, remediatedWithNonCriticalFailures, quarantined, removed, cleaned, allowed, noStatusCleared. defaults to noStatusCleared. Possible values are: `active`, `actionFailed`, `manualStepsRequired`, `fullScanRequired`, `rebootRequired`, `remediatedWithNonCriticalFailures`, `quarantined`, `removed`, `cleaned`, `allowed`, `noStatusCleared`.|
|initialDetectionDateTime|DateTimeOffset|Initial detection datetime of the malware|
|lastStateChangeDateTime|DateTimeOffset|The last time this particular threat was changed|
|detectionCount|Int32|Indicates the number of times the malware is detected|
### [managedDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-manageddevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the device. This property is read-only.|
|userId|String|Unique Identifier for the user associated with the device. This property is read-only.|
|deviceName|String|Name of the device. This property is read-only.|
|managedDeviceOwnerType|managedDeviceOwnerType|Ownership of the device. Can be 'company' or 'personal'. Possible values are: `unknown`, `company`, `personal`.|
|deviceActionResults|deviceActionResult collection|List of ComplexType deviceActionResult objects. This property is read-only.|
|enrolledDateTime|DateTimeOffset|Enrollment time of the device. Supports $filter operator 'lt' and 'gt'. This property is read-only.|
|lastSyncDateTime|DateTimeOffset|The date and time that the device last completed a successful sync with Intune. Supports $filter operator 'lt' and 'gt'. This property is read-only.|
|operatingSystem|String|Operating system of the device. Windows, iOS, etc. This property is read-only.|
|complianceState|complianceState|Compliance state of the device. Examples: Compliant, Conflict, Error, etc. Default is unknown. Supports $filter operator 'eq' and 'or'. This property is read-only. Possible values are: `unknown`, `compliant`, `noncompliant`, `conflict`, `error`, `inGracePeriod`, `configManager`.|
|jailBroken|String|Whether the device is jail broken or rooted. Default is an empty string. Supports $filter operator 'eq' and 'or'. This property is read-only.|
|managementAgent|managementAgentType|Management channel of the device. Examples: Intune, EAS, etc. Default is unknown. Supports $filter operator 'eq' and 'or'. This property is read-only. Possible values are: `eas`, `mdm`, `easMdm`, `intuneClient`, `easIntuneClient`, `configurationManagerClient`, `configurationManagerClientMdm`, `configurationManagerClientMdmEas`, `unknown`, `jamf`, `googleCloudDevicePolicyController`.|
|osVersion|String|Operating system version of the device. This property is read-only.|
|easActivated|Boolean|Whether the device is Exchange ActiveSync activated. This property is read-only.|
|easDeviceId|String|Exchange ActiveSync Id of the device. This property is read-only.|
|easActivationDateTime|DateTimeOffset|Exchange ActivationSync activation time of the device. This property is read-only.|
|azureADRegistered|Boolean|Whether the device is Azure Active Directory registered. This property is read-only.|
|deviceEnrollmentType|deviceEnrollmentType|Enrollment type of the device. This property is read-only. Possible values are: `unknown`, `userEnrollment`, `deviceEnrollmentManager`, `appleBulkWithUser`, `appleBulkWithoutUser`, `windowsAzureADJoin`, `windowsBulkUserless`, `windowsAutoEnrollment`, `windowsBulkAzureDomainJoin`, `windowsCoManagement`, `windowsAzureADJoinUsingDeviceAuth`, `appleUserEnrollment`, `appleUserEnrollmentWithServiceAccount`.|
|activationLockBypassCode|String|The code that allows the Activation Lock on managed device to be bypassed. Default, is Null (Non-Default property) for this property when returned as part of managedDevice entity in LIST call. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only.|
|emailAddress|String|Email(s) for the user associated with the device. This property is read-only.|
|azureADDeviceId|String|The unique identifier for the Azure Active Directory device. Read only. This property is read-only.|
|deviceRegistrationState|deviceRegistrationState|Device registration state. This property is read-only. Possible values are: `notRegistered`, `registered`, `revoked`, `keyConflict`, `approvalPending`, `certificateReset`, `notRegisteredPendingEnrollment`, `unknown`.|
|deviceCategoryDisplayName|String|Device category display name. Default is an empty string. Supports $filter operator 'eq' and 'or'. This property is read-only.|
|isSupervised|Boolean|Device supervised status. This property is read-only.|
|exchangeLastSuccessfulSyncDateTime|DateTimeOffset|Last time the device contacted Exchange. This property is read-only.|
|exchangeAccessState|deviceManagementExchangeAccessState|The Access State of the device in Exchange. This property is read-only. Possible values are: `none`, `unknown`, `allowed`, `blocked`, `quarantined`.|
|exchangeAccessStateReason|deviceManagementExchangeAccessStateReason|The reason for the device's access state in Exchange. This property is read-only. Possible values are: `none`, `unknown`, `exchangeGlobalRule`, `exchangeIndividualRule`, `exchangeDeviceRule`, `exchangeUpgrade`, `exchangeMailboxPolicy`, `other`, `compliant`, `notCompliant`, `notEnrolled`, `unknownLocation`, `mfaRequired`, `azureADBlockDueToAccessPolicy`, `compromisedPassword`, `deviceNotKnownWithManagedApp`.|
|remoteAssistanceSessionUrl|String|Url that allows a Remote Assistance session to be established with the device. Default is an empty string. To retrieve actual values GET call needs to be made, with device id and included in select parameter. This property is read-only.|
|remoteAssistanceSessionErrorDetails|String|An error string that identifies issues when creating Remote Assistance session objects. This property is read-only.|
|isEncrypted|Boolean|Device encryption status. This property is read-only.|
|userPrincipalName|String|Device user principal name. This property is read-only.|
|model|String|Model of the device. This property is read-only.|
|manufacturer|String|Manufacturer of the device. This property is read-only.|
|imei|String|IMEI. This property is read-only.|
|complianceGracePeriodExpirationDateTime|DateTimeOffset|The DateTime when device compliance grace period expires. This property is read-only.|
|serialNumber|String|SerialNumber. This property is read-only.|
|phoneNumber|String|Phone number of the device. This property is read-only.|
|androidSecurityPatchLevel|String|Android security patch level. This property is read-only.|
|userDisplayName|String|User display name. This property is read-only.|
|configurationManagerClientEnabledFeatures|configurationManagerClientEnabledFeatures|ConfigrMgr client enabled features. This property is read-only.|
|wiFiMacAddress|String|Wi-Fi MAC. This property is read-only.|
|deviceHealthAttestationState|deviceHealthAttestationState|The device health attestation state. This property is read-only.|
|subscriberCarrier|String|Subscriber Carrier. This property is read-only.|
|meid|String|MEID. This property is read-only.|
|totalStorageSpaceInBytes|Int64|Total Storage in Bytes. This property is read-only.|
|freeStorageSpaceInBytes|Int64|Free Storage in Bytes. Default value is 0. Read-only. This property is read-only.|
|managedDeviceName|String|Automatically generated name to identify a device. Can be overwritten to a user friendly name.|
|partnerReportedThreatState|managedDevicePartnerReportedHealthState|Indicates the threat state of a device when a Mobile Threat Defense partner is in use by the account and device. Read Only. This property is read-only. Possible values are: `unknown`, `activated`, `deactivated`, `secured`, `lowSeverity`, `mediumSeverity`, `highSeverity`, `unresponsive`, `compromised`, `misconfigured`.|
|requireUserEnrollmentApproval|Boolean|Reports if the managed iOS device is user approval enrollment. This property is read-only.|
|managementCertificateExpirationDate|DateTimeOffset|Reports device management certificate expiration date. This property is read-only.|
|iccid|String|Integrated Circuit Card Identifier, it is A SIM card's unique identification number. Default is an empty string. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only.|
|udid|String|Unique Device Identifier for iOS and macOS devices. Default is an empty string. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only.|
|notes|String|Notes on the device created by IT Admin. Default is null. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported.|
|ethernetMacAddress|String|Indicates Ethernet MAC Address of the device. Default, is Null (Non-Default property) for this property when returned as part of managedDevice entity. Individual get call with select query options is needed to retrieve actual values. Example: deviceManagement/managedDevices({managedDeviceId})?$select=ethernetMacAddress Supports: $select. $Search is not supported. Read-only. This property is read-only.|
|physicalMemoryInBytes|Int64|Total Memory in Bytes. Default is 0. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. Read-only. This property is read-only.|
|enrollmentProfileName|String|Name of the enrollment profile assigned to the device. Default value is empty string, indicating no enrollment profile was assgined. This property is read-only.|
### [managedDeviceCleanupRule ](https://docs.microsoft.com/graph/api/resources/intune-devices-manageddevicecleanuprule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Indicates the identifier of the device cleanup rule. This id is assigned at the time when the device cleanup rule is created. Read-only.|
|displayName|String|Indicates the display name of the device cleanup rule.|
|description|String|Indicates the description for the device clean up rule.|
|deviceCleanupRulePlatformType|deviceCleanupRulePlatformType|Indicates the managed device platform for which the admin wants to create the device clean up rule. Possible values are: `all`, `androidAOSP`, `androidDeviceAdministrator`, `androidDedicatedAndFullyManagedCorporateOwnedWorkProfile`, `chromeOS`, `androidPersonallyOwnedWorkProfile`, `ios`, `macOS`, `windows`, `windowsHolographic`, `unknownFutureValue`.|
|lastModifiedDateTime|DateTimeOffset|Indicates the date and time when the device cleanup rule was last modified. This property is read-only.|
|deviceInactivityBeforeRetirementInDays|Int32|Indicates the number of days when the device has not contacted Intune. Valid values 0 to 2147483647|
### [managedDeviceOverview ](https://docs.microsoft.com/graph/api/resources/intune-devices-manageddeviceoverview?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the summary|
|enrolledDeviceCount|Int32|Total enrolled device count. Does not include PC devices managed via Intune PC Agent|
|mdmEnrolledCount|Int32|The number of devices enrolled in MDM|
|dualEnrolledDeviceCount|Int32|The number of devices enrolled in both MDM and EAS|
|deviceOperatingSystemSummary|deviceOperatingSystemSummary|Device operating system summary.|
|deviceExchangeAccessStateSummary|deviceExchangeAccessStateSummary|Distribution of Exchange Access State in Intune|
### [intune-devices-manageddeviceremoteaction](https://docs.microsoft.com/graph/api/resources/intune-devices-manageddeviceremoteaction?view=graph-rest-1.0&tabs=http)

### [mobileAppTroubleshootingEvent ](https://docs.microsoft.com/graph/api/resources/intune-devices-mobileapptroubleshootingevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The GUID for the object|
### [powerliftDownloadRequest ](https://docs.microsoft.com/graph/api/resources/intune-devices-powerliftdownloadrequest?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|powerliftId|Guid|The unique id for the request|
|files|String collection|The list of files to download|
### [powerliftIncidentMetadata ](https://docs.microsoft.com/graph/api/resources/intune-devices-powerliftincidentmetadata?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|powerliftId|Guid|The unique identifier of the app diagnostic. Example: 8520467a-49a9-44a4-8447-8dfb8bec6726|
|easyId|String|The unique app diagnostic identifier as a user friendly 8 character hexadecimal string. Example: 8520467A|
|createdAtDateTime|DateTimeOffset|The time the app diagnostic was created. Example: 2022-04-19T17:24:45.313Z|
|platform|String|The device's OS the diagnostic is from. Example: iOS|
|application|String|The name of the application the diagnostic is from. Example: com.microsoft.CompanyPortal|
|clientVersion|String|The version of the application. Example: 5.2203.1|
|locale|String|The locale information of the application. Example: en-US|
|fileNames|String collection|A list of files that are associated with the diagnostic.|
### [remoteActionAudit ](https://docs.microsoft.com/graph/api/resources/intune-devices-remoteactionaudit?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Report Id.|
|deviceDisplayName|String|Intune device name.|
|userName|String|\[deprecated\] Please use InitiatedByUserPrincipalName instead.|
|initiatedByUserPrincipalName|String|User who initiated the device action, format is UPN.|
|action|remoteAction|The action name. Possible values are: `unknown`, `factoryReset`, `removeCompanyData`, `resetPasscode`, `remoteLock`, `enableLostMode`, `disableLostMode`, `locateDevice`, `rebootNow`, `recoverPasscode`, `cleanWindowsDevice`, `logoutSharedAppleDeviceActiveUser`, `quickScan`, `fullScan`, `windowsDefenderUpdateSignatures`, `factoryResetKeepEnrollmentData`, `updateDeviceAccount`, `automaticRedeployment`, `shutDown`, `rotateBitLockerKeys`, `rotateFileVaultKey`, `getFileVaultKey`, `setDeviceName`, `activateDeviceEsim`, `deprovision`, `disable`, `reenable`, `moveDeviceToOrganizationalUnit`, `initiateMobileDeviceManagementKeyRecovery`, `initiateOnDemandProactiveRemediation`, `rotateLocalAdminPassword`, `unknownFutureValue`, `launchRemoteHelp`, `revokeAppleVppLicenses`, `removeDeviceFirmwareConfigurationInterfaceManagement`, `pauseConfigurationRefresh`, `initiateDeviceAttestation`, `changeAssignments`, `delete`.|
|requestDateTime|DateTimeOffset|Time when the action was issued, given in UTC.|
|deviceOwnerUserPrincipalName|String|Upn of the device owner.|
|deviceIMEI|String|IMEI of the device.|
|actionState|actionState|Action state. Possible values are: `none`, `pending`, `canceled`, `active`, `done`, `failed`, `notSupported`.|
|managedDeviceId|String|Action target.|
|deviceActionDetails|keyValuePair_2OfString_String collection|DeviceAction details|
|deviceActionCategory|actionCategory|DeviceAction category. Possible values are: `single`, `bulk`.|
|bulkDeviceActionId|String|BulkAction ID|
### [tenantAttachRBAC ](https://docs.microsoft.com/graph/api/resources/intune-devices-tenantattachrbac?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for this entity|
### [tenantAttachRBACState ](https://docs.microsoft.com/graph/api/resources/intune-devices-tenantattachrbacstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|enabled|Boolean|Indicates whether the tenant is enabled for Tenant Attach with role management.  TRUE if enabled, FALSE if the Tenant Attach with rolemanagement is disabled.|
### [user ](https://docs.microsoft.com/graph/api/resources/intune-devices-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the user.|
### [userExperienceAnalyticsAnomaly ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsanomaly?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the user experience analytics anomaly device object.|
|anomalyId|String|The unique identifier of the anomaly.|
|anomalyName|String|The name of the anomaly.|
|deviceImpactedCount|Int32|The number of devices impacted by the anomaly. Valid values -2147483648 to 2147483647|
|severity|userExperienceAnalyticsAnomalySeverity|The severity of the anomaly. Possible values are: high, medium, low, informational or other. Possible values are: `high`, `medium`, `low`, `informational`, `other`, `unknownFutureValue`.|
|state|userExperienceAnalyticsAnomalyState|The state of the anomaly. Possible values are: new, active, disabled, removed or other. Possible values are: `new`, `active`, `disabled`, `removed`, `other`, `unknownFutureValue`.|
|anomalyType|userExperienceAnalyticsAnomalyType|The category of the anomaly. Possible values are: device, application, stopError, driver or other. Possible values are: `device`, `application`, `stopError`, `driver`, `other`, `unknownFutureValue`.|
|anomalyFirstOccurrenceDateTime|DateTimeOffset|Indicates the first occurrence date and time for the anomaly.|
|anomalyLatestOccurrenceDateTime|DateTimeOffset|Indicates the latest occurrence date and time for the anomaly.|
|detectionModelId|String|The unique identifier of the anomaly detection model.|
|issueId|String|The unique identifier of the anomaly detection model.|
|assetName|String|The name of the application or module that caused the anomaly.|
|assetVersion|String|The version of the application or module that caused the anomaly.|
|assetPublisher|String|The publisher of the application or module that caused the anomaly.|
### [userExperienceAnalyticsAnomalyCorrelationGroupOverview ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsanomalycorrelationgroupoverview?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the user experience analytics anomaly correlation group overview object.|
|anomalyId|String|The unique identifier of the anomaly. Anomaly details such as name and type can be found in the UserExperienceAnalyticsAnomalySeverityOverview entity.|
|correlationGroupId|String|The unique identifier for the correlation group which will uniquely identify one of the correlation group within an anomaly. The correlation Id can be mapped to the correlation group name by concatinating the correlation group features. Example of correlation group name which is the indicative of concatenated features names are  for names, Contoso manufacture 4.4.1 and Windows 11.22621.1485.|
|correlationGroupFeatures|userExperienceAnalyticsAnomalyCorrelationGroupFeature collection|Describes the features of a device that are shared between all devices in a correlation group.|
|correlationGroupPrevalence|userExperienceAnalyticsAnomalyCorrelationGroupPrevalence|The prevalence of the correlation group. Possible values are: high, medium or low. Possible values are: `high`, `medium`, `low`, `unknownFutureValue`.|
|correlationGroupPrevalencePercentage|Double|The percentage of the devices in the correlation group that are anomalous. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|totalDeviceCount|Int32|Indicates the total number of devices in the tenant. Valid values -2147483648 to 2147483647|
|anomalyCorrelationGroupCount|Int32|Indicates the number of correlation groups in the anomaly. Valid values -2147483648 to 2147483647|
|correlationGroupDeviceCount|Int32|Indicates the total number of devices in a correlation group. Valid values -2147483648 to 2147483647|
|correlationGroupAnomalousDeviceCount|Int32|Indicates the total number of devices affected by the anomaly in the correlation group. Valid values -2147483648 to 2147483647|
|correlationGroupAtRiskDeviceCount|Int32|Indicates the total number of devices at risk in the correlation group. Valid values -2147483648 to 2147483647|
### [userExperienceAnalyticsAnomalyDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsanomalydevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the user experience analytics anomaly device object.|
|deviceId|String|The unique identifier of the device.|
|deviceName|String|The name of the device.|
|deviceModel|String|The model name of the device.|
|deviceManufacturer|String|The manufacturer name of the device.|
|osName|String|The name of the OS installed on the device.|
|osVersion|String|The OS version installed on the device.|
|anomalyId|String|The unique identifier of the anomaly.|
|anomalyOnDeviceFirstOccurrenceDateTime|DateTimeOffset|Indicates the first occurance date and time for the anomaly on the device.|
|anomalyOnDeviceLatestOccurrenceDateTime|DateTimeOffset|Indicates the latest occurance date and time for the anomaly on the device.|
|correlationGroupId|String|The unique identifier of the correlation group.|
|deviceStatus|userExperienceAnalyticsDeviceStatus|Indicates the device status with respect to the correlation group. At risk devices are devices that share correlation group features but may not yet be affected by an anomaly, such as when a device is experiencing crashes on an application but that application has not been used on the device but is currently installed. This could lead to the device becoming anomalous if the application in question were to be used. Possible values are: anomolous, affected or atRisk. Possible values are: `anomalous`, `affected`, `atRisk`, `unknownFutureValue`.|
### [userExperienceAnalyticsAppHealthApplicationPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthapplicationperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics application performance object. Supports: $select, $OrderBy. Read-only.|
|appHangCount|Int32|The number of hangs for the application. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appHealthScore|Double|The health score of the application. Valid values 0 to 100. Supports: $filter, $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|appHealthStatus|String|The overall health status of the application. Read-only.|
|allOrgsHealthScore|Double|The median health score of the application across all organizations. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|activeDeviceCount|Int32|The health score of the application. Valid values 0 to 100. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appName|String|The name of the application. Possible values are: outlook.exe, excel.exe. Supports: $select, $OrderBy. Read-only.|
|appDisplayName|String|The friendly name of the application. Possible values are: Outlook, Excel. Supports: $select, $OrderBy. Read-only.|
|appPublisher|String|The publisher of the application. Supports: $select, $OrderBy. Read-only.|
|appUsageDuration|Int32|The total usage time of the application in minutes. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appCrashCount|Int32|The number of crashes for the application. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|meanTimeToFailureInMinutes|Int32|The mean time to failure for the application in minutes. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
### [userExperienceAnalyticsAppHealthAppPerformanceByAppVersion ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthappperformancebyappversion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics app performance object.|
|appVersion|String|The version of the application.|
|appName|String|The name of the application. Possible values are: outlook.exe, excel.exe. Supports: $select, $OrderBy. Read-only.|
|appDisplayName|String|The friendly name of the application. Possible values are: Outlook, Excel. Supports: $select, $OrderBy. Read-only.|
|appPublisher|String|The publisher of the application. Supports: $select, $OrderBy. Read-only.|
|appUsageDuration|Int32|The total usage time of the application in minutes. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appCrashCount|Int32|The number of crashes for the application. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|meanTimeToFailureInMinutes|Int32|The mean time to failure for the application in minutes. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
### [userExperienceAnalyticsAppHealthAppPerformanceByAppVersionDetails ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthappperformancebyappversiondetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics application performance by application version details object. Supports: $select, $OrderBy. Read-only.|
|deviceCountWithCrashes|Int32|The total number of devices that have reported one or more application crashes for this application and version. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|isMostUsedVersion|Boolean|When TRUE, indicates the version of application is the most used version for that application. When FALSE, indicates the version is not the most used version. FALSE by default. Supports: $select, $OrderBy. Read-only.|
|isLatestUsedVersion|Boolean|When TRUE, indicates the version of application is the latest version for that application that is in use. When FALSE, indicates the version is not the latest version. FALSE by default. Supports: $select, $OrderBy.|
|appName|String|The name of the application.|
|appDisplayName|String|The friendly name of the application.|
|appPublisher|String|The publisher of the application.|
|appVersion|String|The version of the application.|
|appCrashCount|Int32|The number of crashes for the app. Valid values -2147483648 to 2147483647|
### [userExperienceAnalyticsAppHealthAppPerformanceByAppVersionDeviceId ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthappperformancebyappversiondeviceid?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics application performance by application version device id object. Supports: $select, $OrderBy. Read-only.|
|deviceId|String|The Intune device id of the device. Supports: $select, $OrderBy. Read-only.|
|deviceDisplayName|String|The name of the device. Supports: $select, $OrderBy. Read-only.|
|processedDateTime|DateTimeOffset|The date and time when the statistics were last computed. The value cannot be modified and is automatically populated when the statistics are computed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2022 would look like this: '2022-01-01T00:00:00Z'. Returned by default. Read-only.|
|appName|String|The name of the application.|
|appDisplayName|String|The friendly name of the application.|
|appPublisher|String|The publisher of the application.|
|appVersion|String|The version of the application.|
|appCrashCount|Int32|The number of crashes for the app. Valid values -2147483648 to 2147483647|
### [userExperienceAnalyticsAppHealthAppPerformanceByOSVersion ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthappperformancebyosversion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics application performance by OS version object. Supports: $select, $OrderBy. Read-only.|
|osVersion|String|The OS version of the application. Supports: $select, $OrderBy. Read-only.|
|osBuildNumber|String|The OS build number of the application. Supports: $select, $OrderBy. Read-only.|
|activeDeviceCount|Int32|The number of devices where the application has been active. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appName|String|The name of the application. Possible values are: outlook.exe, excel.exe. Supports: $select, $OrderBy. Read-only.|
|appDisplayName|String|The friendly name of the application. Possible values are: Outlook, Excel. Supports: $select, $OrderBy. Read-only.|
|appPublisher|String|The publisher of the application. Supports: $select, $OrderBy. Read-only.|
|appUsageDuration|Int32|The total usage time of the application in minutes. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appCrashCount|Int32|The number of crashes for the application. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|meanTimeToFailureInMinutes|Int32|The mean time to failure for the application in minutes. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
### [userExperienceAnalyticsAppHealthDeviceModelPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthdevicemodelperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device model performance object. Supports: $select, $OrderBy. Read-only.|
|deviceModel|String|The model name of the device. Supports: $select, $OrderBy. Read-only.|
|deviceManufacturer|String|The manufacturer name of the device. Supports: $select, $OrderBy. Read-only.|
|activeDeviceCount|Int32|The number of active devices for the model. Valid values 0 to 2147483647. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|meanTimeToFailureInMinutes|Int32|The mean time to failure for the application in minutes. Valid values 0 to 2147483647. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|modelAppHealthScore|Double|The application health score of the device model. Valid values 0 to 100. Supports: $filter, $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|modelAppHealthStatus|String|The overall app health status of the device model.|
|healthStatus|userExperienceAnalyticsHealthState|The health state of the user experience analytics model. Possible values are: unknown, insufficientData, needsAttention, meetingGoals. Unknown by default. Supports: $filter, $select, $OrderBy. Read-only. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsAppHealthDevicePerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthdeviceperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device performance object. Supports: $select, $OrderBy. Read-only.|
|deviceModel|String|The model name of the device. Supports: $select, $OrderBy. Read-only.|
|deviceManufacturer|String|The manufacturer name of the device. Supports: $select, $OrderBy. Read-only.|
|appCrashCount|Int32|The number of application crashes for the device. Valid values 0 to 2147483647. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|crashedAppCount|Int32|The number of distinct application crashes for the device. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|appHangCount|Int32|The number of application hangs for the device. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|processedDateTime|DateTimeOffset|The date and time when the statistics were last computed. The value cannot be modified and is automatically populated when the statistics are computed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2022 would look like this: '2022-01-01T00:00:00Z'. Returned by default. Read-only.|
|meanTimeToFailureInMinutes|Int32|The mean time to failure for the application in minutes. Valid values 0 to 2147483647. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|deviceAppHealthScore|Double|The application health score of the device. Valid values 0 to 100. Supports: $filter, $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|deviceAppHealthStatus|String|The overall app health status of the device.|
|healthStatus|userExperienceAnalyticsHealthState|The health state of the user experience analytics device. Possible values are: unknown, insufficientData, needsAttention, meetingGoals. Unknown by default. Supports: $filter, $select, $OrderBy. Read-only. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|deviceId|String|The Intune device id of the device. Supports: $select, $OrderBy. Read-only.|
|deviceDisplayName|String|The name of the device. Supports: $select, $OrderBy. Read-only.|
### [userExperienceAnalyticsAppHealthDevicePerformanceDetails ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthdeviceperformancedetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device performance details object. Supports: $select, $OrderBy. Read-only.|
|eventDateTime|DateTimeOffset|The time the event occurred. The value cannot be modified and is automatically populated when the statistics are computed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2022 would look like this: '2022-01-01T00:00:00Z'. Returned by default. Read-only.|
|eventType|String|The type of the event. Supports: $select, $OrderBy. Read-only.|
|appDisplayName|String|The friendly name of the application for which the event occurred. Possible values are: outlook.exe, excel.exe. Supports: $select, $OrderBy. Read-only.|
|appPublisher|String|The publisher of the application. Supports: $select, $OrderBy. Read-only.|
|appVersion|String|The version of the application. Possible values are: 1.0.0.1, 75.65.23.9. Supports: $select, $OrderBy. Read-only.|
|deviceId|String|The Intune device id of the device. Supports: $select, $OrderBy. Read-only.|
|deviceDisplayName|String|The name of the device. Supports: $select, $OrderBy. Read-only.|
### [userExperienceAnalyticsAppHealthOSVersionPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsapphealthosversionperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics OS version performance object. Supports: $select, $OrderBy. Read-only.|
|osVersion|String|The OS version installed on the device. Supports: $select, $OrderBy. Read-only.|
|osBuildNumber|String|The OS build number installed on the device. Supports: $select, $OrderBy. Read-only.|
|activeDeviceCount|Int32|The number of active devices for the OS version. Valid values 0 to 2147483647. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|meanTimeToFailureInMinutes|Int32|The mean time to failure for the application in minutes. Valid values 0 to 2147483647. Supports: $filter, $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|osVersionAppHealthScore|Double|The application health score of the OS version. Valid values 0 to 100. Supports: $filter, $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|osVersionAppHealthStatus|String|The overall app health status of the OS version.|
### [userExperienceAnalyticsBaseline ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbaseline?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics baseline.|
|displayName|String|The name of the baseline.|
|overallScore|Int32|The overall score of the user experience analytics baseline.|
|isBuiltIn|Boolean|When TRUE, indicates the current baseline is the commercial median baseline. When FALSE, indicates it is a custom baseline. FALSE by default.|
|createdDateTime|DateTimeOffset|The date the custom baseline was created. The value cannot be modified and is automatically populated when the baseline is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default.|
### [userExperienceAnalyticsBatteryHealthAppImpact ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthappimpact?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery app impact object.|
|activeDevices|Int32|Number of active devices for using that app over a 14-day period. Valid values 0 to 2147483647|
|appName|String|App name. Eg: oltk.exe|
|appDisplayName|String|User friendly display name for the app. Eg: Outlook|
|appPublisher|String|App publisher. Eg: Microsoft Corporation|
|isForegroundApp|Boolean|true if the user had active interaction with the app.|
|batteryUsagePercentage|Double|The percent of total battery power used by this application when the device was not plugged into AC power, over 14 days computed across all devices in the tenant. Unit in percentage. Valid values 0 to 1.79769313486232E+308|
### [userExperienceAnalyticsBatteryHealthCapacityDetails ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthcapacitydetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery health capacity object.|
|activeDevices|Int32|Number of active devices within the tenant. Valid values 0 to 2147483647|
|batteryCapacityGood|Int32|Number of devices whose battery maximum capacity is greater than 80%. Valid values 0 to 2147483647|
|batteryCapacityFair|Int32|Number of devices whose battery maximum capacity is greater than 50% but lesser than 80%. Valid values 0 to 2147483647|
|batteryCapacityPoor|Int32|Number of devices whose battery maximum capacity is lesser than 50%. Valid values 0 to 2147483647|
|lastRefreshedDateTime|DateTimeOffset|Recorded date time of this capacity details instance.|
### [userExperienceAnalyticsBatteryHealthDeviceAppImpact ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthdeviceappimpact?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery device app impact object.|
|deviceId|String|The unique identifier of the device, Intune DeviceID or SCCM device id.|
|appName|String|App name. Eg: oltk.exe|
|appDisplayName|String|User friendly display name for the app. Eg: Outlook|
|appPublisher|String|App publisher. Eg: Microsoft Corporation|
|isForegroundApp|Boolean|true if the user had active interaction with the app.|
|batteryUsagePercentage|Double|The percent of total battery power used by this application when the device was not plugged into AC power, over 14 days. Unit in percentage. Valid values 0 to 1.79769313486232E+308|
### [userExperienceAnalyticsBatteryHealthDevicePerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthdeviceperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery health device performance object.|
|deviceId|String|The unique identifier of the device, Intune DeviceID.|
|deviceName|String|Device friendly name.|
|model|String|The model name of the device. Deprecated in favor of DeviceModelName.|
|manufacturer|String|The manufacturer name of the device. Deprecated in favor of DeviceManufacturerName.|
|deviceModelName|String|The model name of the device.|
|deviceManufacturerName|String|The manufacturer name of the device.|
|maxCapacityPercentage|Int32|Ratio of current capacity and design capacity of the battery with the lowest capacity. Unit in percentage and values range from 0-100. Valid values 0 to 2147483647|
|estimatedRuntimeInMinutes|Int32|The estimated runtime of the device when the battery is fully charged. Unit in minutes. Valid values 0 to 2147483647|
|batteryAgeInDays|Int32|Estimated battery age. Unit in days. Valid values 0 to 2147483647|
|fullBatteryDrainCount|Int32|Number of times the battery has been discharged an amount that equals 100% of its capacity, but not necessarily by discharging it from 100% to 0%. Valid values 0 to 2147483647|
|deviceBatteryCount|Int32|Number of batteries in a user device. Valid values 0 to 2147483647|
|deviceBatteriesDetails|userExperienceAnalyticsDeviceBatteryDetail collection|Properties (maxCapacity and cycleCount) related to all batteries of the device.|
|deviceBatteryTags|String collection|Tags for computed information on how battery on the device is behaving. E.g. newbattery, batterycapacityred, designcapacityzero, etc.|
|deviceBatteryHealthScore|Int32|A weighted average of a device’s maximum capacity score and runtime estimate score. Values range from 0-100. Valid values 0 to 2147483647|
|healthStatus|userExperienceAnalyticsHealthState|The overall battery health status of the device. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsBatteryHealthDeviceRuntimeHistory ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthdeviceruntimehistory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery health runtime object.|
|deviceId|String|The unique identifier of the device, Intune DeviceID or SCCM device id.|
|runtimeDateTime|String|The datetime for the instance of runtime history.|
|estimatedRuntimeInMinutes|Int32|The estimated runtime of the device when the battery is fully charged. Unit in minutes. Valid values 0 to 2147483647|
### [userExperienceAnalyticsBatteryHealthModelPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthmodelperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery health model performance object.|
|activeDevices|Int32|Number of active devices for that model. Valid values 0 to 2147483647|
|model|String|The model name of the device. Deprecated in favor of DeviceModelName.|
|manufacturer|String|Name of the device manufacturer. Deprecated in favor of DeviceManufacturerName.|
|deviceModelName|String|The model name of the device.|
|deviceManufacturerName|String|The manufacturer name of the device.|
|averageMaxCapacityPercentage|Int32|The mean of the maximum capacity for all devices of a given model. Maximum capacity measures the full charge vs. design capacity for a device’s batteries.. Valid values 0 to 2147483647|
|averageEstimatedRuntimeInMinutes|Int32|The mean of the estimated runtimes on full charge for all devices of a given model. Unit in minutes. Valid values 0 to 2147483647|
|averageBatteryAgeInDays|Int32|The mean of the battery age for all devices of a given model in a tenant. Unit in days. Valid values 0 to 2147483647|
|meanFullBatteryDrainCount|Int32|The mean of number of times the battery has been discharged an amount that equals 100% of its capacity for all devices of a given model in a tenant. Valid values 0 to 2147483647|
|medianMaxCapacityPercentage|Int32|The median of the maximum capacity for all devices of a given model. Maximum capacity measures the full charge vs. design capacity for a device’s batteries.. Valid values 0 to 2147483647|
|medianEstimatedRuntimeInMinutes|Int32|The median of the estimated runtimes on full charge for all devices of a given model. Unit in minutes. Valid values 0 to 2147483647|
|medianFullBatteryDrainCount|Int32|The median of number of times the battery has been discharged an amount that equals 100% of its capacity for all devices of a given model in a tenant. Valid values 0 to 2147483647|
|modelBatteryHealthScore|Int32|A weighted average of a model’s maximum capacity score and runtime estimate score. Values range from 0-100. Valid values 0 to 2147483647|
|modelHealthStatus|userExperienceAnalyticsHealthState|The overall battery health status of a given model in a tenant. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsBatteryHealthOsPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthosperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery health os performance object.|
|activeDevices|Int32|Number of active devices for that os version. Valid values 0 to 2147483647|
|osVersion|String|Version of the operating system.|
|osBuildNumber|String|Build number of the operating system.|
|averageMaxCapacityPercentage|Int32|The mean of the maximum capacity for all devices running a particular operating system version. Maximum capacity measures the full charge vs. design capacity for a device’s batteries.. Valid values 0 to 2147483647|
|averageEstimatedRuntimeInMinutes|Int32|The mean of the estimated runtimes on full charge for all devices running a particular operating system version. Unit in minutes. Valid values 0 to 2147483647|
|averageBatteryAgeInDays|Int32|The mean of the battery age for all devices running a particular operating system version in a tenant. Unit in days. Valid values 0 to 2147483647|
|meanFullBatteryDrainCount|Int32|The mean of number of times the battery has been discharged an amount that equals 100% of its capacity for all devices running a particular operating system version in a tenant. Valid values 0 to 2147483647|
|medianMaxCapacityPercentage|Int32|The median of the maximum capacity for all devices running a particular operating system version. Maximum capacity measures the full charge vs. design capacity for a device’s batteries.. Valid values 0 to 2147483647|
|medianEstimatedRuntimeInMinutes|Int32|The median of the estimated runtimes on full charge for all devices running a particular operating system version. Unit in minutes. Valid values 0 to 2147483647|
|medianFullBatteryDrainCount|Int32|The median of number of times the battery has been discharged an amount that equals 100% of its capacity for all devices running a particular operating system version in a tenant. Valid values 0 to 2147483647|
|osBatteryHealthScore|Int32|A weighted average of battery health score across all devices running a particular operating system version. Values range from 0-100. Valid values 0 to 2147483647|
|osHealthStatus|userExperienceAnalyticsHealthState|The overall battery health status of a given os version in a tenant. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsBatteryHealthRuntimeDetails ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsbatteryhealthruntimedetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics battery health runtime object.|
|activeDevices|Int32|Number of active devices within the tenant. Valid values 0 to 2147483647|
|batteryRuntimeGood|Int32|Number of devices  whose active runtime is greater than 5 hours. Valid values 0 to 2147483647|
|batteryRuntimeFair|Int32|Number of devices whose active runtime is greater than 3 hours but lesser than 5 hours. Valid values 0 to 2147483647|
|batteryRuntimePoor|Int32|Number of devices whose active runtime is lesser than 3 hours. Valid values 0 to 2147483647|
|lastRefreshedDateTime|DateTimeOffset|Recorded date time of this runtime details instance.|
### [userExperienceAnalyticsCategory ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticscategory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics category. Read-only.|
|overallScore|Int32|The overall score of the user experience analytics category.|
|totalDevices|Int32|The total device count of the user experience analytics category.|
|insights|userExperienceAnalyticsInsight collection|The insights for the category. Read-only.|
|state|userExperienceAnalyticsHealthState|The current health state of the user experience analytics category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsDevicePerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdeviceperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device boot performance device.|
|deviceName|String|The user experience analytics device name.|
|model|String|The user experience analytics device model.|
|manufacturer|String|The user experience analytics device manufacturer.|
|diskType|diskType|The user experience analytics device disk type. Possible values are: `unknown`, `hdd`, `ssd`, `unknownFutureValue`.|
|operatingSystemVersion|String|The user experience analytics device Operating System version.|
|bootScore|Int32|The user experience analytics device boot score.|
|coreBootTimeInMs|Int32|The user experience analytics device core boot time in milliseconds.|
|groupPolicyBootTimeInMs|Int32|The user experience analytics device group policy boot time in milliseconds.|
|healthStatus|userExperienceAnalyticsHealthState|The health state of the user experience analytics device. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|loginScore|Int32|The user experience analytics device login score.|
|coreLoginTimeInMs|Int32|The user experience analytics device core login time in milliseconds.|
|groupPolicyLoginTimeInMs|Int32|The user experience analytics device group policy login time in milliseconds.|
|deviceCount|Int64|User experience analytics summarized device count.|
|responsiveDesktopTimeInMs|Int32|The user experience analytics responsive desktop time in milliseconds.|
|blueScreenCount|Int32|Number of Blue Screens in the last 30 days. Valid values 0 to 9999999|
|restartCount|Int32|Number of Restarts in the last 30 days. Valid values 0 to 9999999|
|averageBlueScreens|Double|Average (mean) number of Blue Screens per device in the last 30 days. Valid values 0 to 9999999|
|averageRestarts|Double|Average (mean) number of Restarts per device in the last 30 days. Valid values 0 to 9999999|
|startupPerformanceScore|Double|The user experience analytics device startup performance score. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|modelStartupPerformanceScore|Double|The user experience analytics model level startup performance score. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
### [userExperienceAnalyticsDeviceScope ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicescope?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the device scope configuration.|
|deviceScopeName|String|The name of the user experience analytics device Scope configuration.|
|ownerId|String|The unique identifier of the person (admin) who created the device scope configuration.|
|isBuiltIn|Boolean|Indicates whether the device scope configuration is built-in or custom. When TRUE, the device scope configuration is built-in. When FALSE, the device scope configuration is custom. Default value is FALSE.|
|enabled|Boolean|Indicates whether a device scope is enabled or disabled. When TRUE, the device scope is enabled. When FALSE, the device scope is disabled. Default value is FALSE.|
|status|deviceScopeStatus|Indicates the device scope status after the device scope has been enabled. Possible values are: none, computing, insufficientData or completed. Default value is none. Possible values are: `none`, `computing`, `insufficientData`, `completed`, `unknownFutureValue`.|
|parameter|deviceScopeParameter|Device scope configuration parameter. It will be extended in future to add more parameter. Eg: device scope parameter can be OS version, Disk Type, Device manufacturer, device model or Scope tag. Default value: scopeTag. Possible values are: `none`, `scopeTag`, `unknownFutureValue`.|
|operator|deviceScopeOperator|Device scope configuration query operator. Possible values are: equals, notEquals, contains, notContains, greaterThan, lessThan. Default value: equals. Possible values are: `none`, `equals`, `unknownFutureValue`.|
|valueObjectId|String|The unique identifier for a user device scope tag Id used for the creation of device scope configuration.|
|value|String|The device scope configuration query clause value.|
|createdDateTime|DateTimeOffset|Indicates the creation date and time for the custom device scope.|
|lastModifiedDateTime|DateTimeOffset|Indicates the last updated date and time for the custom device scope.|
### [userExperienceAnalyticsDeviceScopeSummary ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicescopesummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|totalDeviceScopes|Int32|The total number of user experience analytics device scopes. Valid values -2147483648 to 2147483647|
|totalDeviceScopesEnabled|Int32|The total number of user experience analytics device scopes that are enabled. Valid values -2147483648 to 2147483647|
|completedDeviceScopeIds|String collection|A collection of the user experience analytics device scope Unique Identifiers that are enabled and finished recalculating the report metric.|
|insufficientDataDeviceScopeIds|String collection|A collection of user experience analytics device scope Unique Identitfiers that are enabled but there is insufficient data to calculate results.|
### [userExperienceAnalyticsDeviceScores ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicescores?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device score entry. Supports: $select, $OrderBy. Read-only.|
|deviceName|String|The name of the device. Supports: $select, $OrderBy. Read-only.|
|model|String|The model name of the device. Supports: $select, $OrderBy. Read-only.|
|manufacturer|String|The manufacturer name of the device. Examples: Microsoft Corporation, HP, Lenovo. Supports: $select, $OrderBy. Read-only.|
|endpointAnalyticsScore|Double|Indicates a weighted average of the various scores. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|startupPerformanceScore|Double|Indicates a weighted average of boot score and logon score used for measuring startup performance. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|appReliabilityScore|Double|Indicates a score calculated from application health data to indicate when a device is having problems running one or more applications. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|workFromAnywhereScore|Double|Indicates a weighted score of the work from anywhere on a device level. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|batteryHealthScore|Double|Indicates a calulated score indicating the health of the device's battery. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|healthStatus|userExperienceAnalyticsHealthState|The health status of the device. Possible values are: unknown, insufficientData, needsAttention, meetingGoals. Unknown by default. Supports: $filter, $select, $OrderBy. Read-only. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsDeviceStartupHistory ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicestartuphistory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device startup history. Supports: $select, $OrderBy. Read-only.|
|deviceId|String|The Intune device id of the device. Supports: $select, $OrderBy. Read-only.|
|startTime|DateTimeOffset|The device boot start time. The value cannot be modified and is automatically populated when the device performs a reboot. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2022 would look like this: '2022-01-01T00:00:00Z'. Returned by default. Read-only.|
|coreBootTimeInMs|Int32|The device core boot time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|groupPolicyBootTimeInMs|Int32|The impact of device group policy client on boot time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|featureUpdateBootTimeInMs|Int32|The impact of device feature updates on boot time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|totalBootTimeInMs|Int32|The device total boot time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|groupPolicyLoginTimeInMs|Int32|The impact of device group policy client on login time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|coreLoginTimeInMs|Int32|The device core login time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|responsiveDesktopTimeInMs|Int32|The time for desktop to become responsive during login process in milliseconds. Supports: $select, $OrderBy. Read-only.|
|totalLoginTimeInMs|Int32|The device total login time in milliseconds. Supports: $select, $OrderBy. Read-only.|
|isFirstLogin|Boolean|When TRUE, indicates the device login is the first login after a reboot. When FALSE, indicates the device login is not the first login after a reboot. Supports: $select, $OrderBy. Read-only.|
|isFeatureUpdate|Boolean|When TRUE, indicates the device boot record is associated with feature updates. When FALSE, indicates the device boot record is not associated with feature updates. Supports: $select, $OrderBy. Read-only.|
|operatingSystemVersion|String|The user experience analytics device boot record's operating system version. Supports: $select, $OrderBy. Read-only.|
|restartCategory|userExperienceAnalyticsOperatingSystemRestartCategory|OS restart category. Possible values are: unknown, restartWithUpdate, restartWithoutUpdate, blueScreen, shutdownWithUpdate, shutdownWithoutUpdate, longPowerButtonPress, bootError, update. Unknown by default. Supports: $select, $OrderBy. Read-only. Possible values are: `unknown`, `restartWithUpdate`, `restartWithoutUpdate`, `blueScreen`, `shutdownWithUpdate`, `shutdownWithoutUpdate`, `longPowerButtonPress`, `bootError`, `update`, `unknownFutureValue`.|
|restartStopCode|String|OS restart stop code. This shows the bug check code which can be used to look up the blue screen reason. Supports: $select, $OrderBy. Read-only.|
|restartFaultBucket|String|OS restart fault bucket. The fault bucket is used to find additional information about a system crash. Supports: $select, $OrderBy. Read-only.|
### [userExperienceAnalyticsDeviceStartupProcess ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicestartupprocess?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device startup process. Supports: $select, $OrderBy. Read-only.|
|managedDeviceId|String|The Intune device id of the device. Supports: $select, $OrderBy. Read-only.|
|processName|String|The name of the process. Examples: outlook, excel. Supports: $select, $OrderBy. Read-only.|
|productName|String|The product name of the process. Examples: Microsoft Outlook, Microsoft Excel. Supports: $select, $OrderBy. Read-only.|
|publisher|String|The publisher of the process. Examples: Microsoft Corporation, Contoso Corp. Supports: $select, $OrderBy. Read-only.|
|startupImpactInMs|Int32|The impact of startup process on device boot time in milliseconds. Supports: $select, $OrderBy. Read-only.|
### [userExperienceAnalyticsDeviceStartupProcessPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicestartupprocessperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device startup process performance. Supports: $select, $OrderBy. Read-only.|
|processName|String|The name of the startup process. Examples: outlook, excel. Supports: $select, $OrderBy. Read-only.|
|productName|String|The product name of the startup process. Examples: Microsoft Outlook, Microsoft Excel. Supports: $select, $OrderBy. Read-only.|
|publisher|String|The publisher of the startup process. Examples: Microsoft Corporation, Contoso Corp. Supports: $select, $OrderBy. Read-only.|
|deviceCount|Int64|The count of devices which initiated this process on startup. Supports: $filter, $select, $OrderBy. Read-only.|
|medianImpactInMs|Int64|The median impact of startup process on device boot time in milliseconds. Supports: $filter, $select, $OrderBy. Read-only.|
|totalImpactInMs|Int64|The total impact of startup process on device boot time in milliseconds. Supports: $filter, $select, $OrderBy. Read-only.|
### [userExperienceAnalyticsDeviceTimelineEvent ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicetimelineevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics NRT device timeline event object.|
|deviceId|String|The id of the device where the event occurred.|
|eventDateTime|DateTimeOffset|The time the event occured.|
|eventLevel|deviceEventLevel|The severity level of the event enum. Possible values are: none, verbose, information, warning, error ,critical. Default value: none. Possible values are: `none`, `verbose`, `information`, `warning`, `error`, `critical`, `unknownFutureValue`.|
|eventSource|String|The source of the event. Examples include: Intune, Sccm.|
|eventName|String|The name of the event. Examples include: BootEvent, LogonEvent, AppCrashEvent, AppHangEvent.|
|eventDetails|String|The details provided by the event, format depends on event type.|
### [userExperienceAnalyticsDeviceTimelineEvents ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicetimelineevents?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics NRT device timeline events object.|
|deviceId|String|The id of the device where the event occurred.|
|eventDateTime|DateTimeOffset|The time the event occured.|
|eventLevel|deviceEventLevel|The severity level of the event enum. Possible values are: `none`, `verbose`, `information`, `warning`, `error` ,`critical`. Default value: `none`. Possible values are: `none`, `verbose`, `information`, `warning`, `error`, `critical`, `unknownFutureValue`.|
|eventSource|String|The source of the event. Examples include: Intune, Sccm.|
|eventName|String|The name of the event. Examples include: BootEvent, LogonEvent, AppCrashEvent, AppHangEvent.|
|eventDetails|String|The details provided by the event, format depends on event type.|
|eventAdditionalInformation|String|Placeholder value for future expansion.|
### [userExperienceAnalyticsDeviceWithoutCloudIdentity ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsdevicewithoutcloudidentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics tenant attach device.|
|deviceName|String|The tenant attach device's name.|
|azureAdDeviceId|String|Azure Active Directory Device Id|
### [userExperienceAnalyticsImpactingProcess ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsimpactingprocess?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics top impacting process entity.|
|deviceId|String|The unique identifier of the impacted device.|
|category|String|The category of impacting process.|
|processName|String|The process name.|
|description|String|The description of process.|
|publisher|String|The publisher of the process.|
|impactValue|Double|The impact value of the process. Valid values 0 to 1.79769313486232E+308|
### [userExperienceAnalyticsMetric ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics metric.|
|value|Double|The value of the user experience analytics metric.|
|unit|String|The unit of the user experience analytics metric. Examples: none, percentage, count, seconds, score.|
### [userExperienceAnalyticsMetricHistory ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsmetrichistory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics metric history.|
|deviceId|String|The Intune device id of the device.|
|metricDateTime|DateTimeOffset|The metric date time. The value cannot be modified and is automatically populated when the metric is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default.|
|metricType|String|The user experience analytics metric type.|
### [userExperienceAnalyticsModelScores ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsmodelscores?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics model score entry. Supports: $select, $OrderBy. Read-only.|
|model|String|The model name of the device. Supports: $select, $OrderBy. Read-only.|
|manufacturer|String|The manufacturer name of the device. Examples: Microsoft Corporation, HP, Lenovo. Supports: $select, $OrderBy. Read-only.|
|modelDeviceCount|Int64|Indicates unique devices count of given model in a consolidated report. Supports: $select, $OrderBy. Read-only. Valid values -9.22337203685478E+18 to 9.22337203685478E+18|
|endpointAnalyticsScore|Double|Indicates a weighted average of the various scores. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|startupPerformanceScore|Double|Indicates a weighted average of boot score and logon score used for measuring startup performance. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|appReliabilityScore|Double|Indicates a score calculated from application health data to indicate when a device is having problems running one or more applications. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|workFromAnywhereScore|Double|Indicates a weighted score of the work from anywhere on a device level. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|batteryHealthScore|Double|Indicates a calulated score indicating the health of the device's battery. Valid values range from 0-100. Value -1 means associated score is unavailable. A higher score indicates a healthier device. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|healthStatus|userExperienceAnalyticsHealthState|The health status of the device. Possible values are: unknown, insufficientData, needsAttention, meetingGoals. Unknown by default. Supports: $filter, $select, $OrderBy. Read-only. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsNotAutopilotReadyDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsnotautopilotreadydevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics intune device.|
|deviceName|String|The intune device's name.|
|serialNumber|String|The intune device's serial number.|
|manufacturer|String|The intune device's manufacturer.|
|model|String|The intune device's model.|
|managedBy|String|The intune device's managed by.|
|autoPilotRegistered|Boolean|The intune device's autopilotRegistered.|
|autoPilotProfileAssigned|Boolean|The intune device's autopilotProfileAssigned.|
|azureAdRegistered|Boolean|The intune device's azureAdRegistered.|
|azureAdJoinType|String|The intune device's azure Ad joinType.|
### [userExperienceAnalyticsOverview ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsoverview?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics overview. Supports: $select, $OrderBy. Read-only.|
|overallScore|Int32|The user experience analytics overall score.|
|deviceBootPerformanceOverallScore|Int32|The user experience analytics device boot performance overall score.|
|bestPracticesOverallScore|Int32|The user experience analytics best practices overall score.|
|workFromAnywhereOverallScore|Int32|The user experience analytics Work From Anywhere overall score.|
|appHealthOverallScore|Int32|The user experience analytics app health overall score.|
|resourcePerformanceOverallScore|Int32|The user experience analytics resource performance overall score.|
|batteryHealthOverallScore|Int32|The user experience analytics battery health overall score.|
|insights|userExperienceAnalyticsInsight collection|The user experience analytics insights. Read-only.|
|state|userExperienceAnalyticsHealthState|The current health state of the user experience analytics overview. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|deviceBootPerformanceHealthState|userExperienceAnalyticsHealthState|The current health state of the user experience analytics 'BootPerformance' category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|bestPracticesHealthState|userExperienceAnalyticsHealthState|The current health state of the user experience analytics 'BestPractices' category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|workFromAnywhereHealthState|userExperienceAnalyticsHealthState|The current health state of the user experience analytics 'WorkFromAnywhere' category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|appHealthState|userExperienceAnalyticsHealthState|The current health state of the user experience analytics 'BestPractices' category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|resourcePerformanceHealthState|userExperienceAnalyticsHealthState|The current health state of the user experience analytics 'ResourcePerformance' category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
|batteryHealthState|userExperienceAnalyticsHealthState|The current health state of the user experience analytics 'BatteryHealth' category. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsRegressionSummary ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsregressionsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics regression summary.|
### [userExperienceAnalyticsRemoteConnection ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsremoteconnection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics remote connection entity.|
|deviceId|String|The id of the device.|
|deviceName|String|The name of the device.|
|model|String|The user experience analytics device model.|
|virtualNetwork|String|The user experience analytics virtual network.|
|manufacturer|String|The user experience analytics manufacturer.|
|deviceCount|Int32|The count of remote connection. Valid values 0 to 2147483647|
|cloudPcRoundTripTime|Double|The round tip time of Cloud PC Device. Valid values 0 to 1.79769313486232E+308|
|cloudPcSignInTime|Double|The sign in time of Cloud PC Device. Valid values 0 to 1.79769313486232E+308|
|remoteSignInTime|Double|The remote sign in time of Cloud PC Device. Valid values 0 to 1.79769313486232E+308|
|coreBootTime|Double|The core boot time of Cloud PC Device. Valid values 0 to 1.79769313486232E+308|
|coreSignInTime|Double|The core sign in time of Cloud PC Device. Valid values 0 to 1.79769313486232E+308|
|cloudPcFailurePercentage|Double|The sign in failure percentage of Cloud PC Device. Valid values 0 to 100|
|userPrincipalName|String|The user experience analytics userPrincipalName.|
### [userExperienceAnalyticsResourcePerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsresourceperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics resource performance entity.|
|deviceId|String|The id of the device.|
|deviceName|String|The name of the device.|
|model|String|The user experience analytics device model.|
|deviceCount|Int64|User experience analytics summarized device count.|
|manufacturer|String|The user experience analytics device manufacturer.|
|cpuSpikeTimePercentage|Double|CPU spike time in percentage. Valid values 0 to 100|
|ramSpikeTimePercentage|Double|RAM spike time in percentage. Valid values 0 to 100|
|cpuSpikeTimeScore|Int32|The user experience analytics device CPU spike time score. Valid values 0 to 100|
|cpuSpikeTimePercentageThreshold|Double|Threshold of cpuSpikeTimeScore. Valid values 0 to 100|
|ramSpikeTimeScore|Int32|The user experience analytics device RAM spike time score. Valid values 0 to 100|
|ramSpikeTimePercentageThreshold|Double|Threshold of ramSpikeTimeScore. Valid values 0 to 100|
|deviceResourcePerformanceScore|Int32|Resource performance score of a specific device. Valid values 0 to 100|
|averageSpikeTimeScore|Int32|AverageSpikeTimeScore of a device or a model type. Valid values 0 to 100|
|machineType|userExperienceAnalyticsMachineType|Helps to identify if device is a physical device or virtual. Possible values are: `unknown`, `physical`, `virtual`, `unknownFutureValue`.|
|cpuDisplayName|String|The name of the processor on the device, For example, 11th Gen Intel(R) Core(TM) i7.|
|totalProcessorCoreCount|Int32|The count of cores of the processor of device. Valid values 0 to 512|
|cpuClockSpeedInMHz|Double|The clock speed of the processor, in MHz. Valid values 0 to 1000000|
|totalRamInMB|Double|The total RAM of the device, in MB. Valid values 0 to 1000000|
|diskType|diskType|The type of disk storage used on the device. Possible values are: `unknown`, `hdd`, `ssd`, `unknownFutureValue`.|
|healthStatus|userExperienceAnalyticsHealthState|The health state of the user experience analytics model. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsScoreHistory ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsscorehistory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics device startup process. Supports: $select, $OrderBy. Read-only.|
|startupDateTime|DateTimeOffset|The device startup date time. The value cannot be modified and is automatically populated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Returned by default.|
|overallScore|Int32|User experience analytics overall score. Score will be in the range 0-100, 100 is the ideal score. Valid values 0 to 100|
|startupScore|Int32|User experience analytics device startup score. Score will be in the range 0-100, 100 is the ideal score.|
|coreBootScore|Int32|The user experience analytics device core boot score. Score will be in the range 0-100, 100 is the ideal score.|
|coreSigninScore|Int32|The User experience analytics device core sign-in score. Score will be in the range 0-100, 100 is the ideal score.|
|recommendedSoftwareScore|Int32|The User experience analytics device core sign-in score. Score will be in the range 0-100, 100 is the ideal score.|
|appHealthOverallScore|Int32|The User experience analytics app health overall score.|
|workFromAnywhereScore|Int32|The User experience analytics work from anywhere score.|
|batteryHealthScore|Int32|The User experience analytics battery health score.|
|startupTotalDevices|Int32|The total device count of the user experience analytics category startup performance.|
|recommendedSoftwareTotalDevices|Int32|The total device count of the user experience analytics category recommended software.|
|appHealthTotalDevices|Int32|The total device count of the user experience analytics category app health.|
|workFromAnywhereTotalDevices|Int32|The total device count of the user experience analytics category work from anywhere.|
|batteryHealthTotalDevices|Int32|The total device count of the user experience analytics category battery health.|
|restartScore|Int32|Restart score. Score will be in the range 0-100, 100 is the ideal score, 0 indicates excessive restarts. Valid values 0 to 9999999|
### [intune-devices-userexperienceanalyticssummarizedby](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticssummarizedby?view=graph-rest-1.0&tabs=http)

### [userExperienceAnalyticsWorkFromAnywhereDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsworkfromanywheredevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics work from anywhere device. Supports: $select, $OrderBy. Read-only.|
|deviceId|String|The Intune device id of the device. Supports: $select, $OrderBy. Read-only.|
|deviceName|String|The name of the device. Supports: $select, $OrderBy. Read-only.|
|serialNumber|String|The serial number of the device. Supports: $select, $OrderBy. Read-only.|
|manufacturer|String|The manufacturer name of the device. Supports: $select, $OrderBy. Read-only.|
|model|String|The model name of the device. Supports: $select, $OrderBy. Read-only.|
|ownership|String|Ownership of the device. Supports: $select, $OrderBy. Read-only.|
|managedBy|String|The management agent of the device. Supports: $select, $OrderBy. Read-only.|
|autoPilotRegistered|Boolean|When TRUE, indicates the intune device's autopilot is registered. When FALSE, indicates it's not registered. Supports: $select, $OrderBy. Read-only.|
|autoPilotProfileAssigned|Boolean|When TRUE, indicates the intune device's autopilot profile is assigned. When FALSE, indicates it's not Assigned. Supports: $select, $OrderBy. Read-only.|
|azureAdRegistered|Boolean|When TRUE, indicates the device's Azure Active Directory (Azure AD) is registered. When False, indicates it's not registered. Supports: $select, $OrderBy. Read-only.|
|azureAdDeviceId|String|The Azure Active Directory (Azure AD) device Id. Supports: $select, $OrderBy. Read-only.|
|azureAdJoinType|String|The work from anywhere device's Azure Active Directory (Azure AD) join type. Supports: $select, $OrderBy. Read-only.|
|osDescription|String|The OS description of the device. Supports: $select, $OrderBy. Read-only.|
|osVersion|String|The OS version of the device. Supports: $select, $OrderBy. Read-only.|
|tenantAttached|Boolean|When TRUE, indicates the device is Tenant Attached. When FALSE, indicates it's not Tenant Attached. Supports: $select, $OrderBy. Read-only.|
|compliancePolicySetToIntune|Boolean|When TRUE, indicates the device's compliance policy is set to intune. When FALSE, indicates it's not set to intune. Supports: $select, $OrderBy. Read-only.|
|otherWorkloadsSetToIntune|Boolean|When TRUE, indicates the device's other workloads is set to intune. When FALSE, indicates it's not set to intune. Supports: $select, $OrderBy. Read-only.|
|isCloudManagedGatewayEnabled|Boolean|When TRUE, indicates the device's Cloud Management Gateway for Configuration Manager is enabled. When FALSE, indicates it's not enabled. Supports: $select, $OrderBy. Read-only.|
|upgradeEligibility|operatingSystemUpgradeEligibility|The windows upgrade eligibility status of device. Possible values are: upgraded, unknown, notCapable, capable. Unknown by default. Supports: $select, $OrderBy. Read-only. Possible values are: `upgraded`, `unknown`, `notCapable`, `capable`, `unknownFutureValue`.|
|ramCheckFailed|Boolean|When TRUE, indicates RAM hardware check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|storageCheckFailed|Boolean|When TRUE, indicates storage hardware check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|processorCoreCountCheckFailed|Boolean|When TRUE, indicates processor hardware core count check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|processorSpeedCheckFailed|Boolean|When TRUE, indicates processor hardware speed check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|tpmCheckFailed|Boolean|When TRUE, indicates Trusted Platform Module (TPM) hardware check failed for device to the latest version of upgrade to windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|secureBootCheckFailed|Boolean|When TRUE, indicates secure boot hardware check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|processorFamilyCheckFailed|Boolean|When TRUE, indicates processor hardware family check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|processor64BitCheckFailed|Boolean|When TRUE, indicates processor hardware 64-bit architecture check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|osCheckFailed|Boolean|When TRUE, indicates OS check failed for device to upgrade to the latest version of windows. When FALSE, indicates the check succeeded. Supports: $select, $OrderBy. Read-only.|
|workFromAnywhereScore|Double|Indicates work from anywhere per device overall score. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|windowsScore|Double|Indicates per device windows score. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|cloudManagementScore|Double|Indicates per device cloud management score. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|cloudIdentityScore|Double|Indicates per device cloud identity score. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|cloudProvisioningScore|Double|Indicates per device cloud provisioning score. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|healthStatus|userExperienceAnalyticsHealthState|The health state of the user experience analytics work from anywhere device. Possible values are: unknown, insufficientData, needsAttention, meetingGoals. Unknown by default. Supports: $select, $OrderBy. Read-only. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [userExperienceAnalyticsWorkFromAnywhereHardwareReadinessMetric ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsworkfromanywherehardwarereadinessmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics hardware readiness metric object. Supports: $select, $OrderBy. Read-only.|
|totalDeviceCount|Int32|The count of total devices in an organization. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|upgradeEligibleDeviceCount|Int32|The count of devices in an organization eligible for windows upgrade. Valid values 0 to 2147483647. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|ramCheckFailedPercentage|Double|The percentage of devices for which RAM hardware check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|storageCheckFailedPercentage|Double|The percentage of devices for which storage hardware check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|processorCoreCountCheckFailedPercentage|Double|The percentage of devices for which processor hardware core count check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|processorSpeedCheckFailedPercentage|Double|The percentage of devices for which processor hardware speed check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|tpmCheckFailedPercentage|Double|The percentage of devices for which Trusted Platform Module (TPM) hardware check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|secureBootCheckFailedPercentage|Double|The percentage of devices for which secure boot hardware check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|processorFamilyCheckFailedPercentage|Double|The percentage of devices for which processor hardware family check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|processor64BitCheckFailedPercentage|Double|The percentage of devices for which processor hardware 64-bit architecture check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|osCheckFailedPercentage|Double|The percentage of devices for which OS check has failed. Valid values 0 to 100. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
### [userExperienceAnalyticsWorkFromAnywhereMetric ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsworkfromanywheremetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the user experience analytics work from anywhere metric. Read-only.|
### [userExperienceAnalyticsWorkFromAnywhereModelPerformance ](https://docs.microsoft.com/graph/api/resources/intune-devices-userexperienceanalyticsworkfromanywheremodelperformance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier of the work from anywhere model performance object. Supports: $select, $OrderBy. Read-only.|
|model|String|The model name of the device. Supports: $select, $OrderBy. Read-only.|
|manufacturer|String|The manufacturer name of the device. Supports: $select, $OrderBy. Read-only.|
|modelDeviceCount|Int32|The devices count for the model. Supports: $select, $OrderBy. Read-only. Valid values -2147483648 to 2147483647|
|workFromAnywhereScore|Double|The work from anywhere score of the device model. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|windowsScore|Double|The window score of the device model. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|cloudManagementScore|Double|The cloud management score of the device model. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|cloudIdentityScore|Double|The cloud identity score of the device model. Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|cloudProvisioningScore|Double|The cloud provisioning score of the device model.  Valid values 0 to 100. Value -1 means associated score is unavailable. Supports: $select, $OrderBy. Read-only. Valid values -1.79769313486232E+308 to 1.79769313486232E+308|
|healthStatus|userExperienceAnalyticsHealthState|The health state of the user experience analytics work from anywhere device model. Possible values are: unknown, insufficientData, needsAttention, meetingGoals. Unknown by default. Supports: $select, $OrderBy. Read-only. Possible values are: `unknown`, `insufficientData`, `needsAttention`, `meetingGoals`, `unknownFutureValue`.|
### [windowsDeviceMalwareState ](https://docs.microsoft.com/graph/api/resources/intune-devices-windowsdevicemalwarestate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique Identifier. This is malware id.|
|displayName|String|Malware name|
|additionalInformationUrl|String|Information URL to learn more about the malware|
|severity|windowsMalwareSeverity|Severity of the malware. Possible values are: `unknown`, `low`, `moderate`, `high`, `severe`.|
|executionState|windowsMalwareExecutionState|Execution status of the malware like blocked/executing etc. Possible values are: `unknown`, `blocked`, `allowed`, `running`, `notRunning`.|
|state|windowsMalwareState|Current status of the malware like cleaned/quarantined/allowed etc. Possible values are: `unknown`, `detected`, `cleaned`, `quarantined`, `removed`, `allowed`, `blocked`, `cleanFailed`, `quarantineFailed`, `removeFailed`, `allowFailed`, `abandoned`, `blockFailed`.|
|threatState|windowsMalwareThreatState|Current status of the malware like cleaned/quarantined/allowed etc. Possible values are: `active`, `actionFailed`, `manualStepsRequired`, `fullScanRequired`, `rebootRequired`, `remediatedWithNonCriticalFailures`, `quarantined`, `removed`, `cleaned`, `allowed`, `noStatusCleared`.|
|initialDetectionDateTime|DateTimeOffset|Initial detection datetime of the malware|
|lastStateChangeDateTime|DateTimeOffset|The last time this particular threat was changed|
|detectionCount|Int32|Number of times the malware is detected|
|category|windowsMalwareCategory|Category of the malware. Possible values are: `invalid`, `adware`, `spyware`, `passwordStealer`, `trojanDownloader`, `worm`, `backdoor`, `remoteAccessTrojan`, `trojan`, `emailFlooder`, `keylogger`, `dialer`, `monitoringSoftware`, `browserModifier`, `cookie`, `browserPlugin`, `aolExploit`, `nuker`, `securityDisabler`, `jokeProgram`, `hostileActiveXControl`, `softwareBundler`, `stealthNotifier`, `settingsModifier`, `toolBar`, `remoteControlSoftware`, `trojanFtp`, `potentialUnwantedSoftware`, `icqExploit`, `trojanTelnet`, `exploit`, `filesharingProgram`, `malwareCreationTool`, `remote_Control_Software`, `tool`, `trojanDenialOfService`, `trojanDropper`, `trojanMassMailer`, `trojanMonitoringSoftware`, `trojanProxyServer`, `virus`, `known`, `unknown`, `spp`, `behavior`, `vulnerability`, `policy`, `enterpriseUnwantedSoftware`, `ransom`, `hipsRule`.|
### [windowsMalwareInformation ](https://docs.microsoft.com/graph/api/resources/intune-devices-windowsmalwareinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique Identifier. This is malware id.|
|displayName|String|Indicates the name of the malware|
|additionalInformationUrl|String|Indicates an informational URL to learn more about the malware|
|severity|windowsMalwareSeverity|Severity of the malware. Possible values are: unknown, low, moderate, high, severe. default is unknown. Possible values are: `unknown`, `low`, `moderate`, `high`, `severe`.|
|category|windowsMalwareCategory|Category of the malware. Possible values are: invalid, adware, spyware, passwordStealer, trojanDownloader, worm, backdoor, remoteAccessTrojan, trojan, emailFlooder, keylogger, dialer, monitoringSoftware, browserModifier, cookie, browserPlugin, aolExploit, nuker, securityDisabler, jokeProgram, hostileActiveXControl, softwareBundler, stealthNotifier, settingsModifier, toolBar, remoteControlSoftware, trojanFtp, potentialUnwantedSoftware, icqExploit, trojanTelnet, exploit, filesharingProgram, malwareCreationTool, remote_Control_Software, tool, trojanDenialOfService, trojanDropper, trojanMassMailer, trojanMonitoringSoftware, trojanProxyServer, virus, known, unknown, spp, behavior, vulnerability, policy, enterpriseUnwantedSoftware, ransom, hipsRule. default value is invalid. Possible values are: `invalid`, `adware`, `spyware`, `passwordStealer`, `trojanDownloader`, `worm`, `backdoor`, `remoteAccessTrojan`, `trojan`, `emailFlooder`, `keylogger`, `dialer`, `monitoringSoftware`, `browserModifier`, `cookie`, `browserPlugin`, `aolExploit`, `nuker`, `securityDisabler`, `jokeProgram`, `hostileActiveXControl`, `softwareBundler`, `stealthNotifier`, `settingsModifier`, `toolBar`, `remoteControlSoftware`, `trojanFtp`, `potentialUnwantedSoftware`, `icqExploit`, `trojanTelnet`, `exploit`, `filesharingProgram`, `malwareCreationTool`, `remote_Control_Software`, `tool`, `trojanDenialOfService`, `trojanDropper`, `trojanMassMailer`, `trojanMonitoringSoftware`, `trojanProxyServer`, `virus`, `known`, `unknown`, `spp`, `behavior`, `vulnerability`, `policy`, `enterpriseUnwantedSoftware`, `ransom`, `hipsRule`.|
|lastDetectionDateTime|DateTimeOffset|Indicates the last time the malware was detected in UTC|
### [windowsManagedDevice ](https://docs.microsoft.com/graph/api/resources/intune-devices-windowsmanageddevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the device. This property is read-only. Inherited from managedDevice|
|userId|String|Unique Identifier for the user associated with the device. This property is read-only. Inherited from managedDevice|
|deviceName|String|Name of the device. This property is read-only. Inherited from managedDevice|
|hardwareInformation|hardwareInformation|The hardward details for the device. Includes information such as storage space, manufacturer, serial number, etc. By default most property of this type are set to null/0/false and enum defaults for associated types. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only. Inherited from managedDevice|
|ownerType|ownerType|Ownership of the device. Possible values are, 'company' or 'personal'. Default is unknown. Supports $filter operator 'eq' and 'or'. Inherited from managedDevice. Possible values are: `unknown`, `company`, `personal`.|
|managedDeviceOwnerType|managedDeviceOwnerType|Ownership of the device. Can be 'company' or 'personal' Inherited from managedDevice. Possible values are: `unknown`, `company`, `personal`.|
|deviceActionResults|deviceActionResult collection|List of ComplexType deviceActionResult objects. This property is read-only. Inherited from managedDevice|
|managementState|managementState|Management state of the device. Examples: Managed, RetirePending, etc. Default is managed. Supports $filter operator 'eq' and 'or'. This property is read-only. Inherited from managedDevice. Possible values are: `managed`, `retirePending`, `retireFailed`, `wipePending`, `wipeFailed`, `unhealthy`, `deletePending`, `retireIssued`, `wipeIssued`, `wipeCanceled`, `retireCanceled`, `discovered`.|
|enrolledDateTime|DateTimeOffset|Enrollment time of the device. Supports $filter operator 'lt' and 'gt'. This property is read-only. Inherited from managedDevice|
|lastSyncDateTime|DateTimeOffset|The date and time that the device last completed a successful sync with Intune. Supports $filter operator 'lt' and 'gt'. This property is read-only. Inherited from managedDevice|
|chassisType|chassisType|Chassis type of the device. This property is read-only. Inherited from managedDevice. Possible values are: `unknown`, `desktop`, `laptop`, `worksWorkstation`, `enterpriseServer`, `phone`, `tablet`, `mobileOther`, `mobileUnknown`.|
|operatingSystem|String|Operating system of the device. Windows, iOS, etc. This property is read-only. Inherited from managedDevice|
|deviceType|deviceType|Platform of the device. Examples: Desktop, WindowsRT, etc. Default is unknown. Supports $filter operator 'eq' and 'or'. This property is read-only. Inherited from managedDevice. Possible values are: `desktop`, `windowsRT`, `winMO6`, `nokia`, `windowsPhone`, `mac`, `winCE`, `winEmbedded`, `iPhone`, `iPad`, `iPod`, `android`, `iSocConsumer`, `unix`, `macMDM`, `holoLens`, `surfaceHub`, `androidForWork`, `androidEnterprise`, `windows10x`, `androidnGMS`, `chromeOS`, `linux`, `blackberry`, `palm`, `unknown`, `cloudPC`.|
|complianceState|complianceState|Compliance state of the device. Examples: Compliant, Conflict, Error, etc. Default is unknown. Supports $filter operator 'eq' and 'or'. This property is read-only. Inherited from managedDevice. Possible values are: `unknown`, `compliant`, `noncompliant`, `conflict`, `error`, `inGracePeriod`, `configManager`.|
|jailBroken|String|Whether the device is jail broken or rooted. Default is an empty string. Supports $filter operator 'eq' and 'or'. This property is read-only. Inherited from managedDevice|
|managementAgent|managementAgentType|Management channel of the device. Examples: Intune, EAS, etc. Default is unknown. Supports $filter operator 'eq' and 'or'. This property is read-only. Inherited from managedDevice. Possible values are: `eas`, `mdm`, `easMdm`, `intuneClient`, `easIntuneClient`, `configurationManagerClient`, `configurationManagerClientMdm`, `configurationManagerClientMdmEas`, `unknown`, `jamf`, `googleCloudDevicePolicyController`, `microsoft365ManagedMdm`, `msSense`, `intuneAosp`, `google`, `unknownFutureValue`.|
|osVersion|String|Operating system version of the device. This property is read-only. Inherited from managedDevice|
|easActivated|Boolean|Whether the device is Exchange ActiveSync activated. This property is read-only. Inherited from managedDevice|
|easDeviceId|String|Exchange ActiveSync Id of the device. This property is read-only. Inherited from managedDevice|
|easActivationDateTime|DateTimeOffset|Exchange ActivationSync activation time of the device. This property is read-only. Inherited from managedDevice|
|aadRegistered|Boolean|Whether the device is Azure Active Directory registered. This property is read-only. Inherited from managedDevice|
|azureADRegistered|Boolean|Whether the device is Azure Active Directory registered. This property is read-only. Inherited from managedDevice|
|deviceEnrollmentType|deviceEnrollmentType|Enrollment type of the device. This property is read-only. Inherited from managedDevice. Possible values are: `unknown`, `userEnrollment`, `deviceEnrollmentManager`, `appleBulkWithUser`, `appleBulkWithoutUser`, `windowsAzureADJoin`, `windowsBulkUserless`, `windowsAutoEnrollment`, `windowsBulkAzureDomainJoin`, `windowsCoManagement`, `windowsAzureADJoinUsingDeviceAuth`, `appleUserEnrollment`, `appleUserEnrollmentWithServiceAccount`, `azureAdJoinUsingAzureVmExtension`, `androidEnterpriseDedicatedDevice`, `androidEnterpriseFullyManaged`, `androidEnterpriseCorporateWorkProfile`, `appleACMEBasicBYOD`, `appleACMEDEPUserless`, `appleACMEDEPUDACompanyPortal`, `appleACMEDEPUDASetupAsstLegacy`, `appleACMEDEPUDAModernAuth`.|
|lostModeState|lostModeState|Indicates if Lost mode is enabled or disabled. This property is read-only. Inherited from managedDevice. Possible values are: `disabled`, `enabled`.|
|activationLockBypassCode|String|The code that allows the Activation Lock on managed device to be bypassed. Default, is Null (Non-Default property) for this property when returned as part of managedDevice entity in LIST call. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only. Inherited from managedDevice|
|emailAddress|String|Email(s) for the user associated with the device. This property is read-only. Inherited from managedDevice|
|azureActiveDirectoryDeviceId|String|The unique identifier for the Azure Active Directory device. Read only. This property is read-only. Inherited from managedDevice|
|azureADDeviceId|String|The unique identifier for the Azure Active Directory device. Read only. This property is read-only. Inherited from managedDevice|
|deviceRegistrationState|deviceRegistrationState|Device registration state. This property is read-only. Inherited from managedDevice. Possible values are: `notRegistered`, `registered`, `revoked`, `keyConflict`, `approvalPending`, `certificateReset`, `notRegisteredPendingEnrollment`, `unknown`.|
|deviceCategoryDisplayName|String|Device category display name. Default is an empty string. Supports $filter operator 'eq' and 'or'. This property is read-only. Inherited from managedDevice|
|isSupervised|Boolean|Device supervised status. This property is read-only. Inherited from managedDevice|
|exchangeLastSuccessfulSyncDateTime|DateTimeOffset|Last time the device contacted Exchange. This property is read-only. Inherited from managedDevice|
|exchangeAccessState|deviceManagementExchangeAccessState|The Access State of the device in Exchange. This property is read-only. Inherited from managedDevice. Possible values are: `none`, `unknown`, `allowed`, `blocked`, `quarantined`.|
|exchangeAccessStateReason|deviceManagementExchangeAccessStateReason|The reason for the device's access state in Exchange. This property is read-only. Inherited from managedDevice. Possible values are: `none`, `unknown`, `exchangeGlobalRule`, `exchangeIndividualRule`, `exchangeDeviceRule`, `exchangeUpgrade`, `exchangeMailboxPolicy`, `other`, `compliant`, `notCompliant`, `notEnrolled`, `unknownLocation`, `mfaRequired`, `azureADBlockDueToAccessPolicy`, `compromisedPassword`, `deviceNotKnownWithManagedApp`.|
|remoteAssistanceSessionUrl|String|Url that allows a Remote Assistance session to be established with the device. Default is an empty string. To retrieve actual values GET call needs to be made, with device id and included in select parameter. This property is read-only. Inherited from managedDevice|
|remoteAssistanceSessionErrorDetails|String|An error string that identifies issues when creating Remote Assistance session objects. This property is read-only. Inherited from managedDevice|
|isEncrypted|Boolean|Device encryption status. This property is read-only. Inherited from managedDevice|
|userPrincipalName|String|Device user principal name. This property is read-only. Inherited from managedDevice|
|model|String|Model of the device. This property is read-only. Inherited from managedDevice|
|manufacturer|String|Manufacturer of the device. This property is read-only. Inherited from managedDevice|
|imei|String|IMEI. This property is read-only. Inherited from managedDevice|
|complianceGracePeriodExpirationDateTime|DateTimeOffset|The DateTime when device compliance grace period expires. This property is read-only. Inherited from managedDevice|
|serialNumber|String|SerialNumber. This property is read-only. Inherited from managedDevice|
|phoneNumber|String|Phone number of the device. This property is read-only. Inherited from managedDevice|
|androidSecurityPatchLevel|String|Android security patch level. This property is read-only. Inherited from managedDevice|
|userDisplayName|String|User display name. This property is read-only. Inherited from managedDevice|
|configurationManagerClientEnabledFeatures|configurationManagerClientEnabledFeatures|ConfigrMgr client enabled features. This property is read-only. Inherited from managedDevice|
|wiFiMacAddress|String|Wi-Fi MAC. This property is read-only. Inherited from managedDevice|
|deviceHealthAttestationState|deviceHealthAttestationState|The device health attestation state. This property is read-only. Inherited from managedDevice|
|subscriberCarrier|String|Subscriber Carrier. This property is read-only. Inherited from managedDevice|
|meid|String|MEID. This property is read-only. Inherited from managedDevice|
|totalStorageSpaceInBytes|Int64|Total Storage in Bytes. This property is read-only. Inherited from managedDevice|
|freeStorageSpaceInBytes|Int64|Free Storage in Bytes. Default value is 0. Read-only. This property is read-only. Inherited from managedDevice|
|managedDeviceName|String|Automatically generated name to identify a device. Can be overwritten to a user friendly name. Inherited from managedDevice|
|partnerReportedThreatState|managedDevicePartnerReportedHealthState|Indicates the threat state of a device when a Mobile Threat Defense partner is in use by the account and device. Read Only. This property is read-only. Inherited from managedDevice. Possible values are: `unknown`, `activated`, `deactivated`, `secured`, `lowSeverity`, `mediumSeverity`, `highSeverity`, `unresponsive`, `compromised`, `misconfigured`.|
|retireAfterDateTime|DateTimeOffset|Indicates the time after when a device will be auto retired because of scheduled action. This property is read-only. Inherited from managedDevice|
|usersLoggedOn|loggedOnUser collection|Indicates the last logged on users of a device. This property is read-only. Inherited from managedDevice|
|preferMdmOverGroupPolicyAppliedDateTime|DateTimeOffset|Reports the DateTime the preferMdmOverGroupPolicy setting was set.  When set, the Intune MDM settings will override Group Policy settings if there is a conflict. Read Only. This property is read-only. Inherited from managedDevice|
|autopilotEnrolled|Boolean|Reports if the managed device is enrolled via auto-pilot. This property is read-only. Inherited from managedDevice|
|requireUserEnrollmentApproval|Boolean|Reports if the managed iOS device is user approval enrollment. This property is read-only. Inherited from managedDevice|
|managementCertificateExpirationDate|DateTimeOffset|Reports device management certificate expiration date. This property is read-only. Inherited from managedDevice|
|iccid|String|Integrated Circuit Card Identifier, it is A SIM card's unique identification number. Default is an empty string. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only. Inherited from managedDevice|
|udid|String|Unique Device Identifier for iOS and macOS devices. Default is an empty string. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Read-only. This property is read-only. Inherited from managedDevice|
|roleScopeTagIds|String collection|List of Scope Tag IDs for this Device instance. Inherited from managedDevice|
|windowsActiveMalwareCount|Int32|Count of active malware for this windows device. Default is 0. To retrieve actual values GET call needs to be made, with device id and included in select parameter. This property is read-only. Inherited from managedDevice|
|windowsRemediatedMalwareCount|Int32|Count of remediated malware for this windows device. Default is 0. To retrieve actual values GET call needs to be made, with device id and included in select parameter. This property is read-only. Inherited from managedDevice|
|notes|String|Notes on the device created by IT Admin. Default is null. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. $Search is not supported. Inherited from managedDevice|
|configurationManagerClientHealthState|configurationManagerClientHealthState|Configuration manager client health state, valid only for devices managed by MDM/ConfigMgr Agent Inherited from managedDevice|
|configurationManagerClientInformation|configurationManagerClientInformation|Configuration manager client information, valid only for devices managed, duel-managed or tri-managed by ConfigMgr Agent Inherited from managedDevice|
|ethernetMacAddress|String|Indicates Ethernet MAC Address of the device. Default, is Null (Non-Default property) for this property when returned as part of managedDevice entity. Individual get call with select query options is needed to retrieve actual values. Example: deviceManagement/managedDevices({managedDeviceId})?$select=ethernetMacAddress Supports: $select. $Search is not supported. Read-only. This property is read-only. Inherited from managedDevice|
|physicalMemoryInBytes|Int64|Total Memory in Bytes. Default is 0. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Supports: $select. Read-only. This property is read-only. Inherited from managedDevice|
|processorArchitecture|managedDeviceArchitecture|Processor architecture. This property is read-only. Inherited from managedDevice. Possible values are: `unknown`, `x86`, `x64`, `arm`, `arM64`.|
|specificationVersion|String|Specification version. This property is read-only. Inherited from managedDevice|
|joinType|joinType|Device join type Inherited from managedDevice. Possible values are: `unknown`, `azureADJoined`, `azureADRegistered`, `hybridAzureADJoined`.|
|skuFamily|String|Device sku family Inherited from managedDevice|
|securityPatchLevel|String|This indicates the security patch level of the operating system. These special updates contain important security fixes. For iOS/MacOS they are in (a) format. For android its in 2017-08-07 format. This property is read-only. Inherited from managedDevice|
|skuNumber|Int32|Device sku number, see also: https://learn.microsoft.com/windows/win32/api/sysinfoapi/nf-sysinfoapi-getproductinfo. Valid values 0 to 2147483647. This property is read-only. Inherited from managedDevice|
|managementFeatures|managedDeviceManagementFeatures|Device management features Inherited from managedDevice. Possible values are: `none`, `microsoftManagedDesktop`.|
|chromeOSDeviceInfo|chromeOSDeviceProperty collection|List of properties of the ChromeOS Device. Default is an empty list. To retrieve actual values GET call needs to be made, with device id and included in select parameter. Inherited from managedDevice|
|enrollmentProfileName|String|Name of the enrollment profile assigned to the device. Default value is empty string, indicating no enrollment profile was assgined. This property is read-only. Inherited from managedDevice|
|bootstrapTokenEscrowed|Boolean|Reports if the managed device has an escrowed Bootstrap Token. This is only for macOS devices. To get, include BootstrapTokenEscrowed in the select clause and query with a device id. If FALSE, no bootstrap token is escrowed. If TRUE, the device has escrowed a bootstrap token with Intune. This property is read-only. Inherited from managedDevice|
|deviceFirmwareConfigurationInterfaceManaged|Boolean|Indicates whether the device is DFCI managed. When TRUE the device is DFCI managed. When FALSE, the device is not DFCI managed. The default value is FALSE. Inherited from managedDevice|
|deviceIdentityAttestationDetail|deviceIdentityAttestationDetail|Indicates the attestation status of the managed device. And in which way. Default: Unknown. Inherited from managedDevice|
### [windowsManagementApp ](https://docs.microsoft.com/graph/api/resources/intune-devices-windowsmanagementapp?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the Windows management app|
|availableVersion|String|Windows management app available version.|
|managedInstaller|managedInstallerStatus|Managed Installer Status. Possible values are: `disabled`, `enabled`.|
|managedInstallerConfiguredDateTime|String|Managed Installer Configured Date Time|
### [windowsManagementAppHealthState ](https://docs.microsoft.com/graph/api/resources/intune-devices-windowsmanagementapphealthstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the Windows management app health state. This property is read-only.|
|healthState|healthState|Windows management app health state. Possible values are: `unknown`, `healthy`, `unhealthy`.|
|installedVersion|String|Windows management app installed version.|
|lastCheckInDateTime|DateTimeOffset|Windows management app last check-in time.|
|deviceName|String|Name of the device on which Windows management app is installed.|
|deviceOSVersion|String|Windows 10 OS version of the device on which Windows management app is installed.|
### [windowsProtectionState ](https://docs.microsoft.com/graph/api/resources/intune-devices-windowsprotectionstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique Identifier for the device protection status object. This is device id of the device|
|malwareProtectionEnabled|Boolean|When TRUE indicates anti malware is enabled when FALSE indicates anti malware is not enabled.|
|deviceState|windowsDeviceHealthState|Indicates device's health state. Possible values are: clean, fullScanPending, rebootPending, manualStepsPending, offlineScanPending, critical. Possible values are: `clean`, `fullScanPending`, `rebootPending`, `manualStepsPending`, `offlineScanPending`, `critical`.|
|realTimeProtectionEnabled|Boolean|When TRUE indicates real time protection is enabled, when FALSE indicates real time protection is not enabled. Defaults to setting on client device.|
|networkInspectionSystemEnabled|Boolean|When TRUE indicates network inspection system enabled, when FALSE indicates network inspection system is not enabled. Defaults to setting on client device.|
|quickScanOverdue|Boolean|When TRUE indicates quick scan is overdue, when FALSE indicates quick scan is not overdue. Defaults to setting on client device.|
|fullScanOverdue|Boolean|When TRUE indicates full scan is overdue, when FALSE indicates full scan is not overdue. Defaults to setting on client device.|
|signatureUpdateOverdue|Boolean|When TRUE indicates signature is out of date, when FALSE indicates signature is not out of date. Defaults to setting on client device.|
|rebootRequired|Boolean|When TRUE indicates reboot is required, when FALSE indicates when TRUE indicates reboot is not required. Defaults to setting on client device.|
|fullScanRequired|Boolean|When TRUE indicates full scan is required, when FALSE indicates full scan is not required. Defaults to setting on client device.|
|engineVersion|String|Current endpoint protection engine's version|
|signatureVersion|String|Current malware definitions version|
|antiMalwareVersion|String|Current anti malware version|
|lastQuickScanDateTime|DateTimeOffset|Last quick scan datetime|
|lastFullScanDateTime|DateTimeOffset|Last quick scan datetime|
|lastQuickScanSignatureVersion|String|Last quick scan signature version|
|lastFullScanSignatureVersion|String|Last full scan signature version|
|lastReportedDateTime|DateTimeOffset|Last device health status reported time|
|productStatus|windowsDefenderProductStatus|Product Status of Windows Defender Antivirus. Possible values are: noStatus, serviceNotRunning, serviceStartedWithoutMalwareProtection, pendingFullScanDueToThreatAction, pendingRebootDueToThreatAction, pendingManualStepsDueToThreatAction, avSignaturesOutOfDate, asSignaturesOutOfDate, noQuickScanHappenedForSpecifiedPeriod, noFullScanHappenedForSpecifiedPeriod, systemInitiatedScanInProgress, systemInitiatedCleanInProgress, samplesPendingSubmission, productRunningInEvaluationMode, productRunningInNonGenuineMode, productExpired, offlineScanRequired, serviceShutdownAsPartOfSystemShutdown, threatRemediationFailedCritically, threatRemediationFailedNonCritically, noStatusFlagsSet, platformOutOfDate, platformUpdateInProgress, platformAboutToBeOutdated, signatureOrPlatformEndOfLifeIsPastOrIsImpending, windowsSModeSignaturesInUseOnNonWin10SInstall. Possible values are: `noStatus`, `serviceNotRunning`, `serviceStartedWithoutMalwareProtection`, `pendingFullScanDueToThreatAction`, `pendingRebootDueToThreatAction`, `pendingManualStepsDueToThreatAction`, `avSignaturesOutOfDate`, `asSignaturesOutOfDate`, `noQuickScanHappenedForSpecifiedPeriod`, `noFullScanHappenedForSpecifiedPeriod`, `systemInitiatedScanInProgress`, `systemInitiatedCleanInProgress`, `samplesPendingSubmission`, `productRunningInEvaluationMode`, `productRunningInNonGenuineMode`, `productExpired`, `offlineScanRequired`, `serviceShutdownAsPartOfSystemShutdown`, `threatRemediationFailedCritically`, `threatRemediationFailedNonCritically`, `noStatusFlagsSet`, `platformOutOfDate`, `platformUpdateInProgress`, `platformAboutToBeOutdated`, `signatureOrPlatformEndOfLifeIsPastOrIsImpending`, `windowsSModeSignaturesInUseOnNonWin10SInstall`.|
|isVirtualMachine|Boolean|When TRUE indicates the device is a virtual machine, when FALSE indicates the device is not a virtual machine. Defaults to setting on client device.|
|tamperProtectionEnabled|Boolean|When TRUE indicates the Windows Defender tamper protection feature is enabled, when FALSE indicates the Windows Defender tamper protection feature is not enabled. Defaults to setting on client device.|
### [deviceCategory ](https://docs.microsoft.com/graph/api/resources/intune-onboarding-devicecategory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the device category. Read-only.|
|displayName|String|Display name for the device category.|
|description|String|Optional description for the device category.|
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
### [deviceCategory ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicecategory?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the device category. Read-only.|
|**Onboarding**|
|displayName|String|Display name for the device category.|
|description|String|Optional description for the device category.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-shared-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier associated with the device.|
|**Device configuration**|
|intuneAccountId|Guid|Intune Account ID for given tenant|
|legacyPcManangementEnabled|Boolean|The property to enable Non-MDM managed legacy PC management for this account. This property is read-only.|
|maximumDepTokens|Int32|Maximum number of DEP tokens allowed per-tenant.|
|settings|deviceManagementSettings|Account level settings.|
|**Device management**|
|accountMoveCompletionDateTime|DateTimeOffset|The date & time when tenant data moved between scaleunits.|
|adminConsent|adminConsent|Admin consent information.|
|deviceProtectionOverview|deviceProtectionOverview|Device protection overview.|
|managedDeviceCleanupSettings|managedDeviceCleanupSettings|Device cleanup rule|
|subscriptionState|deviceManagementSubscriptionState|Tenant mobile device management subscription state. Possible values are: `pending`, `active`, `warning`, `disabled`, `deleted`, `blocked`, `lockedOut`.|
|subscriptions|deviceManagementSubscriptions|Tenant's Subscription. Possible values are: `none`, `intune`, `office365`, `intunePremium`, `intune_EDU`, `intune_SMB`.|
|windowsMalwareOverview|windowsMalwareOverview|Malware overview for windows devices.|
|**Group Policy Analytics**|
|groupPolicyObjectFiles|groupPolicyObjectFile collection|A list of Group Policy Object files uploaded.|
|**Onboarding**|
|intuneBrand|intuneBrand|intuneBrand contains data which is used in customizing the appearance of the Company Portal applications as well as the end user web portal.|
|**Odj**|
|domainJoinConnectors|deviceManagementDomainJoinConnector collection|A list of connector objects.|
### [mobileAppTroubleshootingEvent ](https://docs.microsoft.com/graph/api/resources/intune-shared-mobileapptroubleshootingevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object.|
|**Troubleshooting**|
|additionalInformation|keyValuePair collection|A set of string key and string value pairs which provides additional information on the Troubleshooting event Inherited from deviceManagementTroubleshootingEvent|
|applicationId|String|Intune application identifier.|
|correlationId|String|ID used for tracing the failure in the service. |
|eventDateTime|DateTimeOffset|Time when the event occurred . |
|eventName|String|Event Name corresponding to the Troubleshooting Event. Optional|
|history|mobileAppTroubleshootingHistoryItem collection|Intune Mobile Application Troubleshooting History Item|
|managedDeviceIdentifier|String|Device identifier created or collected by Intune.|
|troubleshootingErrorDetails|deviceManagementTroubleshootingErrorDetails|Object containing detailed information about the error and its remediation. Inherited from deviceManagementTroubleshootingEvent|
|userId|String|Identifier for the user that tried to enroll the device.|
### [report ](https://docs.microsoft.com/graph/api/resources/intune-shared-report?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|Stream|Report content; details vary by report type.|
### [reportRoot ](https://docs.microsoft.com/graph/api/resources/intune-shared-reportroot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for this entity.|
### [user ](https://docs.microsoft.com/graph/api/resources/intune-shared-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the user.|
|**Onboarding**|
|deviceEnrollmentLimit|Int32|The limit on the maximum number of devices that the user is permitted to enroll. Allowed values are 5 or 1000.|
### [appleVppTokenTroubleshootingEvent ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-applevpptokentroubleshootingevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object Inherited from deviceManagementTroubleshootingEvent|
|eventDateTime|DateTimeOffset|Time when the event occurred . Inherited from deviceManagementTroubleshootingEvent|
|correlationId|String|Id used for tracing the failure in the service. Inherited from deviceManagementTroubleshootingEvent|
|troubleshootingErrorDetails|deviceManagementTroubleshootingErrorDetails|Object containing detailed information about the error and its remediation. Inherited from deviceManagementTroubleshootingEvent|
|eventName|String|Event Name corresponding to the Troubleshooting Event. It is an Optional field Inherited from deviceManagementTroubleshootingEvent|
|additionalInformation|keyValuePair collection|A set of string key and string value pairs which provides additional information on the Troubleshooting event Inherited from deviceManagementTroubleshootingEvent|
|tokenId|String|Apple Volume Purchase Program Token Identifier.|
### [deviceManagement ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-devicemanagement?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|
### [deviceManagementAutopilotEvent ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-devicemanagementautopilotevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object|
|deviceId|String|Device id associated with the object|
|eventDateTime|DateTimeOffset|Time when the event occurred .|
|deviceRegisteredDateTime|DateTimeOffset|Device registration date.|
|enrollmentStartDateTime|DateTimeOffset|Device enrollment start date.|
|enrollmentType|windowsAutopilotEnrollmentType|Enrollment type. Possible values are: `unknown`, `azureADJoinedWithAutopilotProfile`, `offlineDomainJoined`, `azureADJoinedUsingDeviceAuthWithAutopilotProfile`, `azureADJoinedUsingDeviceAuthWithoutAutopilotProfile`, `azureADJoinedWithOfflineAutopilotProfile`, `azureADJoinedWithWhiteGlove`, `offlineDomainJoinedWithWhiteGlove`, `offlineDomainJoinedWithOfflineAutopilotProfile`.|
|deviceSerialNumber|String|Device serial number.|
|managedDeviceName|String|Managed device name.|
|userPrincipalName|String|User principal name used to enroll the device.|
|windowsAutopilotDeploymentProfileDisplayName|String|Autopilot profile name.|
|enrollmentState|enrollmentState|Enrollment state like Enrolled, Failed. Possible values are: `unknown`, `enrolled`, `pendingReset`, `failed`, `notContacted`, `blocked`.|
|windows10EnrollmentCompletionPageConfigurationDisplayName|String|Enrollment Status Page profile name|
|windows10EnrollmentCompletionPageConfigurationId|String|Enrollment Status Page profile ID|
|deploymentState|windowsAutopilotDeploymentState|Deployment state like Success, Failure, InProgress, SuccessWithTimeout. Possible values are: `unknown`, `success`, `inProgress`, `failure`, `successWithTimeout`, `notAttempted`, `disabled`, `successOnRetry`.|
|deviceSetupStatus|windowsAutopilotDeploymentState|Deployment status for the enrollment status page’s device setup phase. Possible values are: `unknown`, `success`, `inProgress`, `failure`, `successWithTimeout`, `notAttempted`, `disabled`, `successOnRetry`.|
|accountSetupStatus|windowsAutopilotDeploymentState|Deployment status for the enrollment status page’s account setup phase. Possible values are: `unknown`, `success`, `inProgress`, `failure`, `successWithTimeout`, `notAttempted`, `disabled`, `successOnRetry`.|
|osVersion|String|Device operating system version.|
|deploymentDuration|Duration|Autopilot deployment duration including enrollment.|
|deploymentTotalDuration|Duration|Total deployment duration from enrollment to Desktop screen.|
|devicePreparationDuration|Duration|Time spent in device enrollment.|
|deviceSetupDuration|Duration|Time spent in device ESP.|
|accountSetupDuration|Duration|Time spent in user ESP.|
|deploymentStartDateTime|DateTimeOffset|Deployment start time.|
|deploymentEndDateTime|DateTimeOffset|Deployment end time.|
|targetedAppCount|Int32|Count of applications targeted.|
|targetedPolicyCount|Int32|Count of policies targeted.|
|enrollmentFailureDetails|String|Enrollment failure details.|
### [deviceManagementAutopilotPolicyStatusDetail ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-devicemanagementautopilotpolicystatusdetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object|
|displayName|String|The friendly name of the policy.|
|policyType|deviceManagementAutopilotPolicyType|The type of policy. Possible values are: `unknown`, `application`, `appModel`, `configurationPolicy`.|
|complianceStatus|deviceManagementAutopilotPolicyComplianceStatus|The policy compliance or enforcement status. Enforcement status takes precedence if it exists. Possible values are: `unknown`, `compliant`, `installed`, `notCompliant`, `notInstalled`, `error`.|
|trackedOnEnrollmentStatus|Boolean|Indicates if this policy was tracked as part of the autopilot bootstrap enrollment sync session|
|lastReportedDateTime|DateTimeOffset|Timestamp of the reported policy status|
|errorCode|Int32|The errorode associated with the compliance or enforcement status of the policy. Error code for enforcement status takes precedence if it exists.|
### [deviceManagementTroubleshootingEvent ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-devicemanagementtroubleshootingevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object|
|eventDateTime|DateTimeOffset|Time when the event occurred .|
|correlationId|String|Id used for tracing the failure in the service.|
### [enrollmentTroubleshootingEvent ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-enrollmenttroubleshootingevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object Inherited from deviceManagementTroubleshootingEvent|
|eventDateTime|DateTimeOffset|Time when the event occurred . Inherited from deviceManagementTroubleshootingEvent|
|correlationId|String|Id used for tracing the failure in the service. Inherited from deviceManagementTroubleshootingEvent|
|managedDeviceIdentifier|String|Device identifier created or collected by Intune.|
|operatingSystem|String|Operating System.|
|osVersion|String|OS Version.|
|userId|String|Identifier for the user that tried to enroll the device.|
|deviceId|String|Azure AD device identifier.|
|enrollmentType|deviceEnrollmentType|Type of the enrollment. Possible values are: `unknown`, `userEnrollment`, `deviceEnrollmentManager`, `appleBulkWithUser`, `appleBulkWithoutUser`, `windowsAzureADJoin`, `windowsBulkUserless`, `windowsAutoEnrollment`, `windowsBulkAzureDomainJoin`, `windowsCoManagement`, `windowsAzureADJoinUsingDeviceAuth`, `appleUserEnrollment`, `appleUserEnrollmentWithServiceAccount`.|
|failureCategory|deviceEnrollmentFailureReason|Highlevel failure category. Possible values are: `unknown`, `authentication`, `authorization`, `accountValidation`, `userValidation`, `deviceNotSupported`, `inMaintenance`, `badRequest`, `featureNotSupported`, `enrollmentRestrictionsEnforced`, `clientDisconnected`, `userAbandonment`.|
|failureReason|String|Detailed failure reason.|
### [managedDeviceSummarizedAppState ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-manageddevicesummarizedappstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|summarizedAppState|runState|runState for the object. Possible values are: `unknown`, `success`, `fail`, `scriptError`, `pending`, `notApplicable`.|
|deviceId|String|DeviceId of device represented by this object|
### [mobileAppIntentAndState ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-mobileappintentandstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|UUID for the object|
|managedDeviceIdentifier|String|Device identifier created or collected by Intune.|
|userId|String|Identifier for the user that tried to enroll the device.|
|mobileAppList|mobileAppIntentAndStateDetail collection|The list of payload intents and states for the tenant.|
### [reportRoot ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-reportroot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for this entity.|
### [user ](https://docs.microsoft.com/graph/api/resources/intune-troubleshooting-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique Identifier for the user|
### [deviceCompliancePolicySettingStateSummary ](https://docs.microsoft.com/graph/api/resources/managedtenants-devicecompliancepolicysettingstatesummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for this entity. Required. Read-only.|
|conflictDeviceCount|Int32|The number of devices in a conflict state. Optional. Read-only.|
|errorDeviceCount|Int32|The number of devices in an error state. Optional. Read-only.|
|failedDeviceCount|Int32|The number of devices in a failed state. Optional. Read-only.|
|intuneAccountId|String|The identifer for the Microsoft Intune account. Required. Read-only.|
|intuneSettingId|String|The identifier for the Intune setting. Optional. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Optional. Read-only.|
|notApplicableDeviceCount|Int32|The number of devices in a not applicable state. Optional. Read-only.|
|pendingDeviceCount|Int32|The number of devices in a pending state. Optional. Read-only.|
|policyType|String|The type for the device compliance policy. Optional. Read-only.|
|settingName|String|The name for the setting within the device compliance policy. Optional. Read-only.|
|succeededDeviceCount|Int32|The number of devices in a succeeded state. Optional. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Required. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Required. Read-only.|
### [managedDeviceCompliance ](https://docs.microsoft.com/graph/api/resources/managedtenants-manageddevicecompliance?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|complianceStatus|String|Compliance state of the device. This property is read-only. Possible values are: `unknown`, `compliant`, `noncompliant`, `conflict`, `error`, `inGracePeriod`, `configManager`. Optional. Read-only.|
|deviceType|String|Platform of the device. This property is read-only. Possible values are: `desktop`, `windowsRT`, `winMO6`, `nokia`, `windowsPhone`, `mac`, `winCE`, `winEmbedded`, `iPhone`, `iPad`, `iPod`, `android`, `iSocConsumer`, `unix`, `macMDM`, `holoLens`, `surfaceHub`, `androidForWork`, `androidEnterprise`, `windows10x`, `androidnGMS`, `chromeOS`, `linux`, `blackberry`, `palm`, `unknown`, `cloudPC`.  Optional. Read-only.|
|id|String|The unique identity for this entity. Required. Read-only.|
|inGracePeriodUntilDateTime|DateTimeOffset|The date and time when the grace period will expire. Optional. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Optional. Read-only.|
|lastSyncDateTime|DateTimeOffset|The date and time that the device last completed a successful sync with Microsoft Endpoint Manager. Optional. Read-only.|
|managedDeviceId|String|The identifier for the managed device in Microsoft Endpoint Manager. Optional. Read-only.|
|managedDeviceName|String|The display name for the managed device. Optional. Read-only.|
|manufacturer|String|The manufacture for the device. Optional. Read-only.|
|model|String|The model for the device. Optional. Read-only.|
|osDescription|String|The description of the operating system for the managed device. Optional. Read-only.|
|osVersion|String|The version of the operating system for the managed device. Optional. Read-only.|
|ownerType|String|The type of owner for the managed device. Optional. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Optional. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.|
### [managedDeviceComplianceTrend ](https://docs.microsoft.com/graph/api/resources/managedtenants-manageddevicecompliancetrend?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|compliantDeviceCount|Int32|The number of devices with a compliant status. Required. Read-only.|
|configManagerDeviceCount|Int32|The number of devices manged by Configuration Manager. Required. Read-only.|
|countDateTime|String|The date and time compliance snapshot was performed. Required. Read-only.|
|errorDeviceCount|Int32|The number of devices with an error status. Required. Read-only.|
|id|String|The unique identifier for this entity. Required. Read-only.|
|inGracePeriodDeviceCount|Int32|The number of devices that are in a grace period status. Required. Read-only.|
|noncompliantDeviceCount|Int32|The number of devices that are in a non-compliant status. Required. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Optional. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.|
|unknownDeviceCount|Int32|The number of devices in an unknown status. Required. Read-only.|
### [windowsDeviceMalwareState ](https://docs.microsoft.com/graph/api/resources/managedtenants-windowsdevicemalwarestate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|additionalInformationUrl|String|The additional information URL for the discovered malware. Optional. Read-only.|
|detectionCount|Int32|The number of times the piece of malware has been detected. Optional. Read-only.|
|deviceDeleted|Boolean|A flag indicating whether the device has been deleted. Optional. Read-only.|
|id|String|The unique identifier for the device malware state. Required. Read-only.|
|initialDetectionDateTime|DateTimeOffset|The date and time the piece of malware was initially detected. Optional. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Optional. Read-only.|
|lastStateChangeDateTime|DateTimeOffset|The date and time the malware state was last changed. Optional. Read-only.|
|malwareCategory|String|The category for the detected malware. Optional. Read-only.|
|malwareDisplayName|String|The display name for the detected malware. Optional. Read-only.|
|malwareExecutionState|String|The execution state for the detected malware. Optional. Read-only.|
|malwareId|String|The unique identifier for the detected malware. Optional. Read-only.|
|malwareSeverity|String|The severity for the detected malware. Optional. Read-only.|
|malwareThreatState|String|The threat state for the detected malware. Optional. Read-only.|
|managedDeviceId|String|The identifier for the managed device where the malware was detected. Optional. Read-only.|
|managedDeviceName|String|The display name for the managed device where the malware was detected. Optional. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Optional. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.|
### [windowsProtectionState ](https://docs.microsoft.com/graph/api/resources/managedtenants-windowsprotectionstate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|antiMalwareVersion|String|The anti-malware version for the managed device. Optional. Read-only.|
|attentionRequired|Boolean|A flag indicating whether attention is required for the managed device. Optional. Read-only.|
|deviceDeleted|Boolean|A flag indicating whether the managed device has been deleted. Optional. Read-only.|
|devicePropertyRefreshDateTime|DateTimeOffset|The date and time the device property has been refreshed. Optional. Read-only.|
|engineVersion|String|The anti-virus engine version for the managed device. Optional. Read-only.|
|fullScanOverdue|Boolean|A flag indicating whether quick scan is overdue for the managed device. Optional. Read-only.|
|fullScanRequired|Boolean|A flag indicating whether full scan is overdue for the managed device. Optional. Read-only.|
|id|String|The unique identifier for the Windows protection state. Required. Read-only.|
|lastFullScanDateTime|DateTimeOffset|The date and time a full scan was completed. Optional. Read-only.|
|lastFullScanSignatureVersion|String|The version anti-malware version used to perform the last full scan. Optional. Read-only.|
|lastQuickScanDateTime|DateTimeOffset|The date and time a quick scan was completed. Optional. Read-only.|
|lastQuickScanSignatureVersion|String|The version anti-malware version used to perform the last full scan. Optional. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Optional. Read-only.|
|lastReportedDateTime|DateTimeOffset|The date and time the protection state was last reported for the managed device. Optional. Read-only.|
|malwareProtectionEnabled|Boolean|A flag indicating whether malware protection is enabled for the managed device. Optional. Read-only.|
|managedDeviceHealthState|String|The health state for the managed device. Optional. Read-only.|
|managedDeviceId|String|The unique identifier for the managed device. Optional. Read-only.|
|managedDeviceName|String|The display name for the managed device. Optional. Read-only.|
|networkInspectionSystemEnabled|Boolean|A flag indicating whether the network inspection system is enabled. Optional. Read-only.|
|quickScanOverdue|Boolean|A flag indicating weather a quick scan is overdue. Optional. Read-only.|
|realTimeProtectionEnabled|Boolean|A flag indicating whether real time protection is enabled. Optional. Read-only.|
|rebootRequired|Boolean|A flag indicating whether a reboot is required. Optional. Read-only.|
|signatureUpdateOverdue|Boolean|A flag indicating whether an signature update is overdue. Optional. Read-only.|
|signatureVersion|String|The signature version for the managed device. Optional. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Optional. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Optional. Read-only.|
