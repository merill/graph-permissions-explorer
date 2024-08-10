# CloudPC.ReadWrite.All

> Allows the app to read and write the properties of Cloud PCs on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /deviceManagement/virtualEndpoint/deviceImages/{id}](https://docs.microsoft.com/graph/api/cloudpcdeviceimage-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /deviceManagement/virtualEndpoint/onPremisesConnections/{id}](https://docs.microsoft.com/graph/api/cloudpconpremisesconnection-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/virtualEndpoint/provisioningPolicies/{id}](https://docs.microsoft.com/graph/api/cloudpcprovisioningpolicy-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /deviceManagement/virtualEndpoint/userSettings/{id}](https://docs.microsoft.com/graph/api/cloudpcusersetting-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /roleManagement/cloudPC/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignmentmultiple-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /roleManagement/deviceManagement/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /cloudPCs/{cloudPCId}/retrieveReviewStatus](https://docs.microsoft.com/graph/api/cloudpc-retrievereviewstatus?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDevices/{managedDeviceId}/getCloudPcRemoteActionResults](https://docs.microsoft.com/graph/api/manageddevice-getcloudpcremoteactionresults?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/managedDevices/{managedDeviceId}/getCloudPcReviewStatus](https://docs.microsoft.com/graph/api/manageddevice-getcloudpcreviewstatus?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/monitoring/alertRecords](https://docs.microsoft.com/graph/api/devicemanagement-alertrecord-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/monitoring/alertRecords/{alertRecordId}](https://docs.microsoft.com/graph/api/devicemanagement-alertrecord-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/monitoring/alertRecords/getPortalNotifications](https://docs.microsoft.com/graph/api/devicemanagement-alertrecord-getportalnotifications?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/monitoring/alertRules](https://docs.microsoft.com/graph/api/devicemanagement-alertrule-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/monitoring/alertRules/{alertRuleId}](https://docs.microsoft.com/graph/api/devicemanagement-alertrule-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/auditEvents](https://docs.microsoft.com/graph/api/virtualendpoint-list-auditevents?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/auditEvents/{id}](https://docs.microsoft.com/graph/api/cloudpcauditevent-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/auditEvents/getAuditActivityTypes](https://docs.microsoft.com/graph/api/cloudpcauditevent-getauditactivitytypes?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/bulkActions](https://docs.microsoft.com/graph/api/virtualendpoint-list-bulkactions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/bulkActions/{cloudPcBulkActionId}](https://docs.microsoft.com/graph/api/cloudpcbulkaction-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/cloudPCs](https://docs.microsoft.com/graph/api/virtualendpoint-list-cloudpcs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/cloudPCs/{id}](https://docs.microsoft.com/graph/api/cloudpc-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/cloudPCs/{id}/getCloudPcConnectivityHistory](https://docs.microsoft.com/graph/api/cloudpc-getcloudpcconnectivityhistory?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /deviceManagement/virtualEndpoint/cloudPCs/{id}/getSupportedCloudPcRemoteActions](https://docs.microsoft.com/graph/api/cloudpc-getsupportedcloudpcremoteactions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/cloudPCs/{id}/retrieveCloudPcRemoteActionResults](https://docs.microsoft.com/graph/api/cloudpc-retrievecloudpcremoteactionresults?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/cloudPCs/getProvisionedCloudPCs(groupId='{groupId}',servicePlanId='{servicePlanId}')](https://docs.microsoft.com/graph/api/cloudpc-getprovisionedcloudpcs?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /deviceManagement/virtualEndpoint/crossCloudGovernmentOrganizationMapping](https://docs.microsoft.com/graph/api/cloudpccrosscloudgovernmentorganizationmapping-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/deviceImages](https://docs.microsoft.com/graph/api/virtualendpoint-list-deviceimages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/deviceImages/{id}](https://docs.microsoft.com/graph/api/cloudpcdeviceimage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/deviceImages/getSourceImages](https://docs.microsoft.com/graph/api/cloudpcdeviceimage-getsourceimages?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/externalPartnerSettings](https://docs.microsoft.com/graph/api/virtualendpoint-list-externalpartnersettings?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/externalPartnerSettings/{cloudPcExternalPartnerSettingId}](https://docs.microsoft.com/graph/api/cloudpcexternalpartnersetting-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/frontLineServicePlans](https://docs.microsoft.com/graph/api/virtualendpoint-list-frontlineserviceplans?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/frontLineServicePlans/{cloudPcFrontLineServicePlanId}](https://docs.microsoft.com/graph/api/cloudpcfrontlineserviceplan-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/galleryImages](https://docs.microsoft.com/graph/api/virtualendpoint-list-galleryimages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/galleryImages/{id}](https://docs.microsoft.com/graph/api/cloudpcgalleryimage-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /deviceManagement/virtualEndpoint/getEffectivePermissions](https://docs.microsoft.com/graph/api/virtualendpoint-geteffectivepermissions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/onPremisesConnections](https://docs.microsoft.com/graph/api/virtualendpoint-list-onpremisesconnections?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/onPremisesConnections/{id}](https://docs.microsoft.com/graph/api/cloudpconpremisesconnection-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/organizationSettings](https://docs.microsoft.com/graph/api/cloudpcorganizationsettings-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/provisioningPolicies](https://docs.microsoft.com/graph/api/virtualendpoint-list-provisioningpolicies?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/provisioningPolicies/{id}](https://docs.microsoft.com/graph/api/cloudpcprovisioningpolicy-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/reports/exportJobs/{cloudPcExportJobId}](https://docs.microsoft.com/graph/api/cloudpcexportjob-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/reports/getRealTimeRemoteConnectionLatency(cloudPcId='id')](https://docs.microsoft.com/graph/api/cloudpcreports-getrealtimeremoteconnectionlatency?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/reports/getRealTimeRemoteConnectionStatus(cloudPcId='id')](https://docs.microsoft.com/graph/api/cloudpcreports-getrealtimeremoteconnectionstatus?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /deviceManagement/virtualEndpoint/retrieveScopedPermissions](https://docs.microsoft.com/graph/api/virtualendpoint-retrievescopedpermissions?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /deviceManagement/virtualEndpoint/retrieveTenantEncryptionSetting](https://docs.microsoft.com/graph/api/virtualendpoint-retrievetenantencryptionsetting?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/servicePlans](https://docs.microsoft.com/graph/api/virtualendpoint-list-serviceplans?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/sharedUseServicePlans](https://docs.microsoft.com/graph/api/virtualendpoint-list-shareduseserviceplans?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/sharedUseServicePlans/{cloudPcSharedUseServicePlanId}](https://docs.microsoft.com/graph/api/cloudpcshareduseserviceplan-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/snapshots](https://docs.microsoft.com/graph/api/virtualendpoint-list-snapshots?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/snapshots/{cloudPcSnapshotId}](https://docs.microsoft.com/graph/api/cloudpcsnapshot-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/snapshots/getStorageAccounts(subscriptionId='{subscriptionId}')](https://docs.microsoft.com/graph/api/cloudpcsnapshot-getstorageaccounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/snapshots/getSubscriptions](https://docs.microsoft.com/graph/api/cloudpcsnapshot-getsubscriptions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /deviceManagement/virtualEndpoint/supportedRegions](https://docs.microsoft.com/graph/api/virtualendpoint-list-supportedregions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/userSettings](https://docs.microsoft.com/graph/api/virtualendpoint-list-usersettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /deviceManagement/virtualEndpoint/userSettings/{id}](https://docs.microsoft.com/graph/api/cloudpcusersetting-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/cloudPCs](https://docs.microsoft.com/graph/api/user-list-cloudpcs?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/cloudPCs/{cloudPCId}/getCloudPcLaunchInfo](https://docs.microsoft.com/graph/api/cloudpc-getcloudpclaunchinfo?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/cloudPCs/{cloudPCId}/getFrontlineCloudPcAccessState](https://docs.microsoft.com/graph/api/cloudpc-getfrontlinecloudpcaccessstate?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/cloudPCs/{cloudPCId}/getShiftWorkCloudPcAccessState](https://docs.microsoft.com/graph/api/cloudpc-getshiftworkcloudpcaccessstate?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/cloudPCs/{id}](https://docs.microsoft.com/graph/api/cloudpc-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPc/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplicationmultiple-list-roleassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignmentmultiple-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /roleManagement/cloudPC/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-list-roledefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /roleManagement/directory/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/cloudPcConnections](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-cloudpcconnections?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/cloudPcConnections/{cloudPcConnectionId}](https://docs.microsoft.com/graph/api/managedtenants-cloudpcconnection-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/cloudPcDevices](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-cloudpcdevices?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/cloudPcDevices/{cloudPcDeviceId}](https://docs.microsoft.com/graph/api/managedtenants-cloudpcdevice-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/cloudPcsOverview](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-cloudpcsoverview?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/cloudPcsOverview/{cloudPcOverviewId}](https://docs.microsoft.com/graph/api/managedtenants-cloudpcoverview-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{userId}/cloudPCs/{id}](https://docs.microsoft.com/graph/api/cloudpc-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/monitoring/alertRules/{alertRuleId}](https://docs.microsoft.com/graph/api/devicemanagement-alertrule-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/virtualEndpoint/externalPartnerSettings/{cloudPcExternalPartnerSettingId}](https://docs.microsoft.com/graph/api/cloudpcexternalpartnersetting-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /deviceManagement/virtualEndpoint/onPremisesConnections/{id}](https://docs.microsoft.com/graph/api/cloudpconpremisesconnection-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /deviceManagement/virtualEndpoint/organizationSettings](https://docs.microsoft.com/graph/api/cloudpcorganizationsettings-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/virtualEndpoint/provisioningPolicies/{id}](https://docs.microsoft.com/graph/api/cloudpcprovisioningpolicy-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /deviceManagement/virtualEndpoint/userSettings/{id}](https://docs.microsoft.com/graph/api/cloudpcusersetting-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /roleManagement/cloudPC/roleAssignments/{id}](https://docs.microsoft.com/graph/api/unifiedroleassignmentmultiple-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /roleManagement/deviceManagement/roleDefinitions/{id}](https://docs.microsoft.com/graph/api/unifiedroledefinition-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /cloudPCs/{cloudPCId}/setReviewStatus](https://docs.microsoft.com/graph/api/cloudpc-setreviewstatus?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/reprovisionCloudPc](https://docs.microsoft.com/graph/api/manageddevice-reprovisioncloudpc?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/resizeCloudPc](https://docs.microsoft.com/graph/api/manageddevice-resizecloudpc?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/restoreCloudPc](https://docs.microsoft.com/graph/api/manageddevice-restorecloudpc?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/{managedDeviceId}/setCloudPcReviewStatus](https://docs.microsoft.com/graph/api/manageddevice-setcloudpcreviewstatus?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/bulkReprovisionCloudPc](https://docs.microsoft.com/graph/api/manageddevice-bulkreprovisioncloudpc?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/bulkRestoreCloudPc](https://docs.microsoft.com/graph/api/manageddevice-bulkrestorecloudpc?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/managedDevices/bulkSetCloudPcReviewStatus](https://docs.microsoft.com/graph/api/manageddevice-bulksetcloudpcreviewstatus?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/monitoring/alertRecords/{alertRecordId}/setPortalNotificationAsSent](https://docs.microsoft.com/graph/api/devicemanagement-alertrecord-setportalnotificationassent?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/monitoring/alertRecords/changeAlertRecordsPortalNotificationAsSent](https://docs.microsoft.com/graph/api/devicemanagement-alertrecord-changealertrecordsportalnotificationassent?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/monitoring/alertRules](https://docs.microsoft.com/graph/api/devicemanagement-alertrule-post?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/bulkActions](https://docs.microsoft.com/graph/api/virtualendpoint-post-bulkactions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/changeUserAccountType](https://docs.microsoft.com/graph/api/cloudpc-changeuseraccounttype?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/endGracePeriod](https://docs.microsoft.com/graph/api/cloudpc-endgraceperiod?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/poweroff](https://docs.microsoft.com/graph/api/cloudpc-poweroff?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/poweron](https://docs.microsoft.com/graph/api/cloudpc-poweron?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/reboot](https://docs.microsoft.com/graph/api/cloudpc-reboot?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/rename](https://docs.microsoft.com/graph/api/cloudpc-rename?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{cloudPCId}/troubleshoot](https://docs.microsoft.com/graph/api/cloudpc-troubleshoot?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{id}/createSnapshot](https://docs.microsoft.com/graph/api/cloudpc-createsnapshot?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{id}/resize](https://docs.microsoft.com/graph/api/cloudpc-resize?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{id}/restore](https://docs.microsoft.com/graph/api/cloudpc-restore?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/{id}/retryPartnerAgentInstallation](https://docs.microsoft.com/graph/api/cloudpc-retrypartneragentinstallation?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/4b18de4b-ab05-4059-8c61-0323a7df4ced/endGracePeriod](https://docs.microsoft.com/graph/api/cloudpc-endgraceperiod?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/bulkResize](https://docs.microsoft.com/graph/api/cloudpc-bulkresize?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/cloudPCs/validateBulkResize](https://docs.microsoft.com/graph/api/cloudpc-validatebulkresize?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /deviceManagement/virtualEndpoint/crossCloudGovernmentOrganizationMapping](https://docs.microsoft.com/graph/api/virtualendpoint-post-crosscloudgovernmentorganizationmapping?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/deviceImages](https://docs.microsoft.com/graph/api/virtualendpoint-post-deviceimages?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/deviceImages/{cloudPcDeviceImageId}/reupload](https://docs.microsoft.com/graph/api/cloudpcdeviceimage-reupload?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/externalPartnerSettings](https://docs.microsoft.com/graph/api/virtualendpoint-post-externalpartnersettings?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /deviceManagement/virtualEndpoint/onPremisesConnections](https://docs.microsoft.com/graph/api/virtualendpoint-post-onpremisesconnections?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /deviceManagement/virtualEndpoint/onPremisesConnections/{id}/runHealthChecks](https://docs.microsoft.com/graph/api/cloudpconpremisesconnection-runhealthcheck?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/onPremisesConnections/{Id}/UpdateAdDomainPassword](https://docs.microsoft.com/graph/api/cloudpconpremisesconnection-updateaddomainpassword?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/provisioningPolicies](https://docs.microsoft.com/graph/api/virtualendpoint-post-provisioningpolicies?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/provisioningPolicies/{id}/apply](https://docs.microsoft.com/graph/api/cloudpcprovisioningpolicy-apply?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/provisioningPolicies/{id}/assign](https://docs.microsoft.com/graph/api/cloudpcprovisioningpolicy-assign?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/provisioningPolicies/applyConfig](https://docs.microsoft.com/graph/api/cloudpcprovisioningpolicy-applyconfig?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/exportJobs](https://docs.microsoft.com/graph/api/cloudpcreports-post-exportjobs?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getActionStatusReports](https://docs.microsoft.com/graph/api/cloudpcreports-getactionstatusreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getCloudPcRecommendationReports](https://docs.microsoft.com/graph/api/cloudpcreports-getcloudpcrecommendationreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getConnectionQualityReports](https://docs.microsoft.com/graph/api/cloudpcreports-getconnectionqualityreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getDailyAggregatedRemoteConnectionReports](https://docs.microsoft.com/graph/api/cloudpcreports-getdailyaggregatedremoteconnectionreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getFrontlineReport](https://docs.microsoft.com/graph/api/cloudpcreports-getfrontlinereport?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getInaccessibleCloudPcReports](https://docs.microsoft.com/graph/api/cloudpcreports-getinaccessiblecloudpcreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getRawRemoteConnectionReports](https://docs.microsoft.com/graph/api/cloudpcreports-getrawremoteconnectionreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getRemoteConnectionHistoricalReports](https://docs.microsoft.com/graph/api/cloudpcreports-getremoteconnectionhistoricalreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getSharedUseLicenseUsageReport](https://docs.microsoft.com/graph/api/cloudpcreports-getshareduselicenseusagereport?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/getTotalAggregatedRemoteConnectionReports](https://docs.microsoft.com/graph/api/cloudpcreports-gettotalaggregatedremoteconnectionreports?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /deviceManagement/virtualEndpoint/reports/retrieveCrossRegionDisasterRecoveryReport](https://docs.microsoft.com/graph/api/cloudpcreports-retrievecrossregiondisasterrecoveryreport?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/userSettings](https://docs.microsoft.com/graph/api/virtualendpoint-post-usersettings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /deviceManagement/virtualEndpoint/userSettings/{id}/assign](https://docs.microsoft.com/graph/api/cloudpcusersetting-assign?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /me/cloudPCs/{cloudPCId}/reboot](https://docs.microsoft.com/graph/api/cloudpc-reboot?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/cloudPCs/{cloudPCId}/rename](https://docs.microsoft.com/graph/api/cloudpc-rename?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/cloudPCs/{cloudPCId}/start](https://docs.microsoft.com/graph/api/cloudpc-start?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/cloudPCs/{cloudPCId}/stop](https://docs.microsoft.com/graph/api/cloudpc-stop?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/cloudPCs/{cloudPCId}/troubleshoot](https://docs.microsoft.com/graph/api/cloudpc-troubleshoot?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/cloudPCs/{id}/reprovision](https://docs.microsoft.com/graph/api/cloudpc-reprovision?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /roleManagement/cloudPC/roleAssignments](https://docs.microsoft.com/graph/api/rbacapplicationmultiple-post-roleassignments?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /roleManagement/deviceManagement/roleDefinitions](https://docs.microsoft.com/graph/api/rbacapplication-post-roledefinitions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{userId}/cloudPCs/{cloudPCId}/reboot](https://docs.microsoft.com/graph/api/cloudpc-reboot?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{userId}/cloudPCs/{cloudPCId}/rename](https://docs.microsoft.com/graph/api/cloudpc-rename?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{userId}/cloudPCs/{cloudPCId}/troubleshoot](https://docs.microsoft.com/graph/api/cloudpc-troubleshoot?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{userId}/cloudPCs/{id}/reprovision](https://docs.microsoft.com/graph/api/cloudpc-reprovision?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9d77138f-f0e2-47ba-ab33-cd246c8b79d1|
|**Consent Type**|Admin|
|**Display String**|Read and write Cloud PCs|
|**Description**|Allows the app to read and write the properties of Cloud PCs on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|3b4349e1-8cf5-45a3-95b7-69d1751d3e6a|
|**Display String**|Read and write Cloud PCs|
|**Description**|Allows the app to read and write the properties of Cloud PCs, without a signed-in user.|
## Resources
### [cloudPC ](https://docs.microsoft.com/graph/api/resources/cloudpc?view=graph-rest-1.0&tabs=http)
|Property|Type| Description                                                                                                                                                                                                                                                                                                         |
|:---|:---|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|aadDeviceId|String| The Microsoft Entra device ID for the Cloud PC, also known as the Azure Active Directory (Azure AD) device ID, that consists of 32 characters in a GUID format. Generated on a VM joined to Microsoft Entra ID. Read-only.                                                                                                                                                                      |
|displayName|String| The display name for the Cloud PC. Maximum length is 64 characters. Read-only. You can use the cloudPC: rename API to modify the Cloud PC name.                                                                                                                                                                                   |
|gracePeriodEndDateTime|DateTimeOffset| The date and time when the grace period ends and reprovisioning or deprovisioning happen. Required only if the status is `inGracePeriod`. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                       |
|id|String| The unique identifier of the customer-facing Cloud PC entity that consists of 32 characters in a GUID format. Read-only. Inherited from entity.                                                                                                                                                                                                                  |
|imageDisplayName|String| The name of the operating system image used for the Cloud PC. Maximum length is 50 characters. Only letters (A-Z, a-z), numbers (0-9), and special characters (-,_,.) are allowed for this property. The property value can't begin or end with an underscore. Read-only.|
|lastModifiedDateTime|DateTimeOffset| The last modified date and time of the Cloud PC. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                                                                                       |
|managedDeviceId|String| The Intune enrolled device ID for the Cloud PC that consists of 32 characters in a GUID format. The **managedDeviceId** property of Windows 365 Business Cloud PCs is always null as Windows 365 Business Cloud PCs aren't Intune-enrolled automatically by Windows 365. Read-only.                                                                         |
|managedDeviceName|String| The Intune enrolled device name for the Cloud PC. The **managedDeviceName** property of Windows 365 Business Cloud PCs is always null as Windows 365 Business Cloud PCs aren't Intune-enrolled automatically by Windows 365. Read-only.                                                                                                   |
|onPremisesConnectionName|String| The on-premises connection that applied during the provisioning of Cloud PCs. Read-only.                                                                                                                                                                                                                                |
|provisioningPolicyId|String| The provisioning policy ID for the Cloud PC that consists of 32 characters in a GUID format. A policy defines the type of Cloud PC the user wants to create. Read-only.                                                                                                                                                                                                                                                                        |
|provisioningPolicyName|String| The provisioning policy that applied during the provisioning of Cloud PCs. Maximum length is 120 characters. Read-only.                                                                                                                                                                                                      |
|provisioningType|cloudPcProvisioningType| The type of licenses to be used when provisioning Cloud PCs using this policy. Possible values are: `dedicated`, `shared`, `unknownFutureValue`. The default value is `dedicated`.                                                                                                                                      |
|servicePlanId|String| The service plan ID for the Cloud PC that consists of 32 characters in a GUID format. For more information about service plans, see Product names and service plan identifiers for licensing. Read-only.                                                                                               
|servicePlanName|String| The service plan name for the customer-facing Cloud PC entity. Read-only.                                                                                                                                                                                                                                     |
|userPrincipalName|String| The user principal name (UPN) of the user assigned to the Cloud PC. Maximum length is 113 characters. For more information on username policies, see Password policies and account restrictions in Microsoft Entra ID. Read-only.                       |
### [cloudPcAuditEvent ](https://docs.microsoft.com/graph/api/resources/cloudpcauditevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activity|String|The friendly name of the audit activity.|
|activityDateTime|DateTimeOffset|The date time in UTC when the activity was performed. Read-only.|
|activityOperationType|cloudPcAuditActivityOperationType|The HTTP operation type of the activity. Possible values include `create`, `delete`, `patch` and `unknownFutureValue`. Read-only.|
|activityResult|cloudPcAuditActivityResult|The result of the activity. Possible values include `success`, `clientError`, `failure`, `timeout` and `unknownFutureValue`. Read-only.|
|activityType|String|The type of activity that was performed. Read-only.|
|actor|cloudPcAuditActor|Microsoft Entra ID user and application associated with the audit event. Read-only.|
|category|cloudPcAuditCategory|The category of the audit event. Possible values include `cloudPC` and `unknownFutureValue`. Read-only.|
|componentName|String|The component name for the audit event. Read-only.|
|correlationId|String|The client request ID that is used to correlate activity within the system. Read-only.|
|displayName|String|The display name for the audit event. Read-only.|
|id|String|The unique identifier for the audit event. Read-only.|
|resources|cloudPcAuditResource collection|The list of cloudPcAuditResource objects. Read-only.|
### [cloudPcBulkAction ](https://docs.microsoft.com/graph/api/resources/cloudpcbulkaction?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionSummary|cloudPcBulkActionSummary|Run summary of this bulk action.|
|cloudPcIDs|String collection|IDs of the Cloud PCs the bulk action applies to. |
|createdDateTime|DateTimeOffset|The date and time when the bulk action was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|Name of the bulk action.|
|id|String|ID of the bulk action. Inherited from entity.|
|initiatedByUserPrincipalName|String|Indicates the user principal name (UPN) of the user who initiated this bulk action. Read-only.|
|scheduledDuringMaintenanceWindow|Boolean|Indicates whether the bulk action is scheduled according to the maintenance window. When `true`, the bulk action uses the maintenance window to schedule the action; `false` means that the bulk action doesn't use the maintenance window. The default value is `false`.|
|status|cloudPcBulkActionStatus|Indicates the status of bulk actions. Possible values are `pending`, `succeeded`, `failed`, `unknownFutureValue`. The default value is `pending`. Read-only.|
### [cloudPcBulkRemoteActionResult ](https://docs.microsoft.com/graph/api/resources/cloudpcbulkremoteactionresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|failedDeviceIds|String collection|A list of all the Intune managed device IDs that completed the bulk action with a failure.|
|notFoundDeviceIds|String collection|A list of all the Intune managed device IDs that were not found when the bulk action was attempted.|
|notSupportedDeviceIds|String collection|A list of all the Intune managed device IDs that were identified as unsupported for the bulk action.|
|successfulDeviceIds|String collection|A list of all the Intune managed device IDs that completed the bulk action successfully.|
### [cloudPcBulkReprovision ](https://docs.microsoft.com/graph/api/resources/cloudpcbulkreprovision?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionSummary|cloudPcBulkActionSummary|Run summary of this bulk action. Inherited from cloudPcBulkAction. |
|cloudPcIds|String collection|IDs of the Cloud PCs the bulk action applies to. Inherited from cloudPcBulkAction. |
|createdDateTime|DateTimeOffset|The date and time when the bulk action was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from cloudPcBulkAction. |
|displayName|String|Name of the bulk action. Inherited from cloudPcBulkAction. |
|id|String|ID of the bulk action. Inherited from cloudPcBulkAction. |
|initiatedByUserPrincipalName|String|Indicates the user principal name (UPN) of the user who initiated this bulk action. Read-only. Inherited from cloudPcBulkAction.|
|scheduledDuringMaintenanceWindow|Boolean|Indicates whether the bulk action is scheduled according to the maintenance window. When `true`, the bulk action uses the maintenance window to schedule the action; `false` means that the bulk action doesn't use the maintenance window. The default value is `false`. Inherited from cloudPcBulkAction.|
|status|cloudPcBulkActionStatus|Indicates the status of bulk actions. Possible values are `pending`, `succeeded`, `failed`, `unknownFutureValue`. The default value is `pending`. Read-only. Inherited from cloudPcBulkAction.|
### [cloudPcBulkRestore ](https://docs.microsoft.com/graph/api/resources/cloudpcbulkrestore?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionSummary|cloudPcBulkActionSummary|Run summary of this bulk action. Inherited from cloudPcBulkAction. |
|cloudPcIds|String collection|IDs of the Cloud PCs the bulk action applies to. Inherited from cloudPcBulkAction. |
|createdDateTime|DateTimeOffset|The date and time when the bulk action was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from cloudPcBulkAction. |
|displayName|String|Name of the bulk action. Inherited from cloudPcBulkAction. |
|id|String|ID of the bulk action. Inherited from cloudPcBulkAction. |
|initiatedByUserPrincipalName|String|Indicates the user principal name (UPN) of the user who initiated this bulk action. Read-only. Inherited from cloudPcBulkAction.|
|restorePointDateTime|DateTimeOffset|The date and time point for the selected Cloud PCs to restore. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|scheduledDuringMaintenanceWindow|Boolean|Indicates whether the bulk action is scheduled according to the maintenance window. When `true`, the bulk action uses the maintenance window to schedule the action; `false` means that the bulk action doesn't use the maintenance window. The default value is `false`. Inherited from cloudPcBulkAction.|
|status|cloudPcBulkActionStatus|Indicates the status of bulk actions. Possible values are `pending`, `succeeded`, `failed`, `unknownFutureValue`. The default value is `pending`. Read-only. Inherited from cloudPcBulkAction.|
|timeRange|restoreTimeRange|The time range of the restore point. The possible values are: `before`, `after`, `beforeOrAfter`, `unknownFutureValue`. The default value is `before`.|
### [cloudPcConnectivityEvent ](https://docs.microsoft.com/graph/api/resources/cloudpcconnectivityevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|eventDateTime|DateTimeOffset|Indicates the date and time when this event was created. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appears as `2014-01-01T00:00:00Z`.|
|eventName|string|Name of the event.|
|eventResult|cloudPcConnectivityEventResult|Result of this event. Possible values are: `unknown`, `success`, `failure`, and `unknownFutureValue`.|
|eventType|cloudPcConnectivityEventType|Type of this event. Possible values are: `unknown`, `userConnection`, `userTroubleshooting`, `deviceHealthCheck`, and `unknownFutureValue`.|
|message|string|Additional message for this event.|
### [cloudPcCrossCloudGovernmentOrganizationMapping ](https://docs.microsoft.com/graph/api/resources/cloudpccrosscloudgovernmentorganizationmapping?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The tenant ID of the GCC tenant in public cloud.|
|organizationIdsInUSGovCloud|String collection|The tenant ID in the Azure Government cloud corresponding to the GCC tenant in the public cloud. Currently, 1:1 mappings are supported, so this collection can only contain one tenant ID.|
### [cloudPcDeviceImage ](https://docs.microsoft.com/graph/api/resources/cloudpcdeviceimage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the associated device image. The device image display name and the version are used to uniquely identify the Cloud PC device image. Read-only.|
|errorCode|cloudPcDeviceImageErrorCode|The error code of the status of the image that indicates why the upload failed, if applicable. Possible values are: `internalServerError`, `sourceImageNotFound`, `osVersionNotSupported`, `sourceImageInvalid`, `sourceImageNotGeneralized`, `unknownFutureValue`, `vmAlreadyAzureAdJoined`, `paidSourceImageNotSupport`, `sourceImageNotSupportCustomizeVMName`, `sourceImageSizeExceedsLimitation`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `vmAlreadyAzureAdJoined`, `paidSourceImageNotSupport`, `sourceImageNotSupportCustomizeVMName`, `sourceImageSizeExceedsLimitation`. Read-only.|
|expirationDate|Date|The date when the image became unavailable. Read-only.|
|id|String|The unique identifier (ID) of the image resource on the Cloud PC. Read-only. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The data and time when the image was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
|operatingSystem|String|The operating system (OS) of the image. For example, `Windows 10 Enterprise`. Read-only.|
|osBuildNumber|String|The OS build version of the image. For example, `1909`. Read-only.|
|osStatus|cloudPcDeviceImageOsStatus|The OS status of this image. Possible values are: `supported`, `supportedWithWarning`, `unknown`, `unknownFutureValue`. The default value is `unknown`. Read-only.|
|sourceImageResourceId|String|The unique identifier (ID) of the source image resource on Azure. The required ID format is: "/subscriptions/{subscription-id}/resourceGroups/{resourceGroupName}/providers/Microsoft.Compute/images/{imageName}". Read-only.|
|status|cloudPcDeviceImageStatus|The status of the image on the Cloud PC. Possible values are: `pending`, `ready`, `failed`, `unknownFutureValue`. Read-only.|
|version|String|The image version. For example, `0.0.1` and `1.5.13`. Read-only.|
### [cloudPcDomainJoinConfiguration ](https://docs.microsoft.com/graph/api/resources/cloudpcdomainjoinconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|domainJoinType|cloudPcDomainJoinType|Specifies the method by which the provisioned Cloud PC joins Microsoft Entra ID. If you choose the `hybridAzureADJoin` type, only provide a value for the **onPremisesConnectionId** property and leave the **regionName** property empty. If you choose the `azureADJoin` type, provide a value for either the **onPremisesConnectionId** or the **regionName** property. Possible values are: `azureADJoin`, `hybridAzureADJoin`, `unknownFutureValue`.|
|onPremisesConnectionId|String|The Azure network connection ID that matches the virtual network IT admins want the provisioning policy to use when they create Cloud PCs. You can use this property in both domain join types: _Azure AD joined_ or _Hybrid Microsoft Entra joined_. If you enter an **onPremisesConnectionId**, leave the **regionName** property empty.|
|regionGroup|cloudPcRegionGroup|The logical geographic group this region belongs to. Multiple regions can belong to one region group. A customer can select a **regionGroup** when they provision a Cloud PC, and the Cloud PC is put in one of the regions in the group based on resource status. For example, the Europe region group contains the Northern Europe and Western Europe regions. Possible values are: `default`, `australia`, `canada`, `usCentral`, `usEast`, `usWest`, `france`, `germany`, `europeUnion`, `unitedKingdom`, `japan`, `asia`, `india`, `southAmerica`, `euap`, `usGovernment`, `usGovernmentDOD`, `unknownFutureValue`, `norway`, `switzerland`, `southKorea`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values in this evolvable enum: `norway`, `switzerland`, `southKorea`. Read-only.|
|regionName|String|The supported Azure region where the IT admin wants the provisioning policy to create Cloud PCs. Within this region, the Windows 365 service creates and manages the underlying virtual network. This option is available only when the IT admin selects _M
### [cloudPcExportJob ](https://docs.microsoft.com/graph/api/resources/cloudpcexportjob?view=graph-rest-1.0&tabs=http)
| Property           | Type                                                     | Description                                                                                                                                                                             |
| :----------------- | :------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| expirationDateTime | DateTimeOffset                                           | The date and time when the export job expires.                                                                                                                                              |
| exportJobStatus    | cloudPcExportJobStatus | The status of the export job. The possible values are: `notStarted`, `inProgress`, `completed`, `unknownFutureValue`. Read-only.                                                         |
| exportUrl          | String                                                   | The storage account URL of the exported report. It can be used to download the file.                                                                                                    |
| filter             | String                                                   | The filter applied on the report.                                                                                                                                                       |
| format             | String                                                   | The format of the exported report.                                                                                                                                                      |
| id                 | String                                                   | The unique identifier for the report. Read-only.                                                                                                                                        |
| reportName         | cloudPcReportName           | The report name. The possible values are: `remoteConnectionHistoricalReports`, `dailyAggregatedRemoteConnectionReports`, `totalAggregatedRemoteConnectionReports`, `sharedUseLicenseUsageReport`, `sharedUseLicenseUsageRealTimeReport`, `unknownFutureValue`,  `noLicenseAvailableConnectivityFailureReport`, `frontlineLicenseUsageReport`, `frontlineLicenseUsageRealTimeReport`,  `remoteConnectionQualityReports`, `inaccessibleCloudPcReports`, `rawRemoteConnectionReports`, `cloudPcUsageCategoryReports`, `crossRegionDisasterRecoveryReport`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values in this evolvable enum: `noLicenseAvailableConnectivityFailureReport`, `frontlineLicenseUsageReport`, `frontlineLicenseUsageRealTimeReport`, `remoteConnectionQualityReports`, `inaccessibleCloudPcReports`, `rawRemoteConnectionReports`, `cloudPcUsageCategoryReports`, `crossRegionDisasterRecoveryReport`.|
| requestDateTime    | DateTimeOffset                                           | The date and time when the export job was requested.  |
| select             | String collection                                        | The selected columns of the report.   |
### [cloudPcExternalPartnerSetting ](https://docs.microsoft.com/graph/api/resources/cloudpcexternalpartnersetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|enableConnection|Boolean|Enable or disable the connection to an external partner. If `true`, an external partner API will accept incoming calls from external partners. Required. Supports `$filter` (`eq`).|
|id|String|The unique identifier for the Cloud PC external partner setting. Read-only. |
|lastSyncDateTime|DateTimeOffset|Last data sync time for this external partner. The Timestamp type represents the date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 looks like this: '2014-01-01T00:00:00Z'.|
|partnerId|String|The external partner ID.|
|status|cloudPcExternalPartnerStatus|The status of the connection to the external partner. The possible values are: `notAvailable`, `available`, `healthy`, `unhealthy`, `unknownFutureValue`.|
|statusDetails|String|Status details message.|
### [cloudPcForensicStorageAccount ](https://docs.microsoft.com/graph/api/resources/cloudpcforensicstorageaccount?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|storageAccountId|String|The ID of the storage account.|
|storageAccountName|String|The name of the storage account.|
### [cloudPcFrontLineServicePlan ](https://docs.microsoft.com/graph/api/resources/cloudpcfrontlineserviceplan?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the front-line service plan. For example, `2vCPU/8GB/128GB Front-line` or `4vCPU/16GB/256GB Front-line`.|
|id|String|The unique identifier (ID) of the front-line service plan.|
|totalCount|Int32|The total number of front-line service plans purchased by the customer.|
|usedCount|Int32|The number of service plans that have been used for the account.|
### [cloudPcGalleryImage ](https://docs.microsoft.com/graph/api/resources/cloudpcgalleryimage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of this gallery image. For example, `Windows 11 Enterprise + Microsoft 365 Apps 22H2`. Read-only.|
|endDate|Date|The date when the status of the image becomes `supportedWithWarning`. Users can still provision new Cloud PCs if the current time is later than **endDate** and earlier than **expirationDate**. For example, assume the **endDate** of a gallery image is `2023-9-14` and **expirationDate** is `2024-3-14`, users are able to provision new Cloud PCs if today is 2023-10-01. Read-only.|
|expirationDate|Date|The date when the image is no longer available. Users are unable to provision new Cloud PCs if the current time is later than **expirationDate**. The value is usually **endDate** plus six months. For example, if the **startDate** is `2025-10-14`, the **expirationDate** is usually `2026-04-14`. Read-only.|
|id|String|The unique identifier (ID) of the gallery image resource on Cloud PC. The ID format is {publisherName_offerName_skuName}. For example, `MicrosoftWindowsDesktop_windows-ent-cpc_win11-22h2-ent-cpc-m365`. You can find the **publisherName**, **offerName**, and **skuName** in the Azure Marketplace. Inherited from entity. Read-only.|
|offerName|String|The offer name of this gallery image that is passed to Azure Resource Manager (ARM) to retrieve the image resource. Read-only.|
|publisherName|String|The publisher name of this gallery image that is passed to Azure Resource Manager (ARM) to retrieve the image resource. Read-only.|
|sizeInGB|Int32|Indicates the size of this image in gigabytes. For example, `64`. Read-only.|
|skuName|String|The SKU name of this image that is passed to Azure Resource Manager (ARM) to retrieve the image resource. Read-only.|
|startDate|Date| The date when the Cloud PC image is available for provisioning new Cloud PCs. For example, `2022-09-20`. Read-only.|
|status|cloudPcGalleryImageStatus|The status of the gallery image on the Cloud PC. Possible values are: `supported`, `supportedWithWarning`, `notSupported`, `unknownFutureValue`. The default value is `supported`. Read-only.|
### [cloudPcLaunchInfo ](https://docs.microsoft.com/graph/api/resources/cloudpclaunchinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|cloudPcId|String|The unique identifier of the Cloud PC.|
|cloudPcLaunchUrl|String|The connect URL of the Cloud PC.|
|windows365SwitchCompatible|Boolean|Indicates whether the Cloud PC supports switch functionality. If the value is `true`, it supports switch functionality; otherwise,  `false`.|
|windows365SwitchNotCompatibleReason|String|Indicates the reason the Cloud PC doesn't support switch. `CPCOsVersionNotMeetRequirement` indicates that the user needs to update their Cloud PC operation system version. `CPCHardwareNotMeetRequirement` indicates that the Cloud PC needs more CPU or RAM to support the functionality.|
### [cloudPcOnPremisesConnection ](https://docs.microsoft.com/graph/api/resources/cloudpconpremisesconnection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|adDomainName|String|The fully qualified domain name (FQDN) of the Active Directory domain you want to join. Maximum length is 255. Optional.|
|adDomainPassword|String| The password associated with the username of an Active Directory account (**adDomainUsername**).|
|adDomainUsername|String|The username of an Active Directory account (user or service account) that has permission to create computer objects in Active Directory. Required format: `admin@contoso.com`. Optional.|
|alternateResourceUrl|String|The interface URL of the partner service's resource that links to this Azure network connection. Returned only on `$select`.|
|connectionType|cloudPcOnPremisesConnectionType|Specifies how the provisioned Cloud PC joins to Microsoft Entra. It includes different types, one is Microsoft Entra ID join, which means there's no on-premises Active Directory (AD) in the current tenant, and the Cloud PC device is joined by Microsoft Entra. Another one is hybridAzureADJoin, which means there's also an on-premises Active Directory (AD) in the current tenant and the Cloud PC device joins to on-premises Active Directory (AD) and Microsoft Entra. The type also determines which types of users can be assigned and can sign into a Cloud PC. The azureADJoin type indicates that cloud-only and hybrid users can be assigned and signed into the Cloud PC. hybridAzureADJoin indicates only hybrid users can be assigned and signed into the Cloud PC. The default value is `hybridAzureADJoin`.|
|displayName|String|The display name for the Azure network connection.|
|healthCheckStatus|cloudPcOnPremisesConnectionStatus|  The status of the most recent health check done on the on-premises connection. For example, if the status is `passed`, the on-premises connection passed all checks run by the service. Possible values: `pending`, `running`, `passed`, `failed`, `warning`, `informational`. Default is `pending`. Read-only. |
|healthCheckStatusDetail|cloudPcOnPremisesConnectionStatusDetail| Indicates the results of health checks performed on the on-premises connection. Read-only. Returned only on `$select`. For an example that shows how to get the **inUse** property, see Example 2: Get the selected properties of an Azure network connection, including healthCheckStatusDetail. Read-only.|
|id|String|Unique identifier for the Azure network connection. Read-only.|
|inUse|Boolean|When `true`, the Azure network connection is in use. When `false`, the connection isn't in use. You can't delete a connection that’s in use. Returned only on `$select`. For an example that shows how to get the **inUse** property, see Example 2: Get the selected properties of an Azure network connection, including healthCheckStatusDetail. Read-only.|
|organizationalUnit|String|The organizational unit (OU) in which the computer account is created. If left null, the OU configured as the default (a well-known computer object container) in the tenant's Active Directory domain (OU) is used. Optional.|
|resourceGroupId|String|The unique identifier of the target resource group used associated with the on-premises network connectivity for Cloud PCs. Required format: “/subscriptions/{subscription-id}/resourceGroups/{resourceGroupName}” |
|subnetId|String|The unique identifier of the target subnet used associated with the on-premises network connectivity for Cloud PCs. Required format: “/subscriptions/{subscription-id}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkId}/subnets/{subnetName}” |
|subscriptionId|String|The unique identifier of the Azure subscription associated with the tenant.|
|subscriptionName|String|The name of the Azure subscription is used to create an Azure network connection. Read-only.|
|virtualNetworkId|String|The unique identifier of the target virtual network used associated with the on-premises network connectivity for Cloud PCs. Required format: “/subscriptions/{subscription-id}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks/{virtualNetworkName}” |
|virtualNetworkLocation|String|Indicates the resource location of the target virtual network. For example, the location can be eastus2, westeurope, etc. Read-only (computed value). |
### [cloudPcOnPremisesConnectionStatusDetail ](https://docs.microsoft.com/graph/api/resources/cloudpconpremisesconnectionstatusdetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|endDateTime|DateTimeOffset|The end time of the connection health check. The Timestamp  is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appears as `2014-01-01T00:00:00Z`. Read-Only.|
|healthChecks|cloudPcOnPremisesConnectionHealthCheck collection|A list of all checks that have been run on the connection. Read-Only.|
|startDateTime|DateTimeOffset|The start time of the health check. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appear as `2014-01-01T00:00:00Z`. Read-Only. |
### [cloudpconpremisesconnectionstatusdetails](https://docs.microsoft.com/graph/api/resources/cloudpconpremisesconnectionstatusdetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|endDateTime|DateTimeOffset|The end time of the connection health check. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|healthChecks|cloudPcOnPremisesConnectionHealthCheck collection|All checks that are done on the connection.|
|startDateTime|DateTimeOffset|The start time of the connection health check. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [cloudPcOrganizationSettings ](https://docs.microsoft.com/graph/api/resources/cloudpcorganizationsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|enableMEMAutoEnroll|Boolean|Specifies whether new Cloud PCs will be automatically enrolled in Microsoft Endpoint Manager (MEM). The default value is `false`.|
|enableSingleSignOn|Boolean|`True` if the provisioned Cloud PC can be accessed by single sign-on. `False` indicates that the provisioned Cloud PC doesn't support this feature. Default value is `false`. Windows 365 users can use single sign-on to authenticate to Microsoft Entra ID with passwordless options (for example, FIDO keys) to access their Cloud PC. Optional.|
|id|String|The ID of the organization settings.|
|osVersion|cloudPcOperatingSystem|The version of the operating system (OS) to provision on Cloud PCs. The possible values are: `windows10`, `windows11`, `unknownFutureValue`.|
|userAccountType|cloudPcUserAccountType|The account type of the user on provisioned Cloud PCs. The possible values are: `standardUser`, `administrator`, `unknownFutureValue`.|
|windowsSettings|cloudPcWindowsSettings|Represents the Cloud PC organization settings for a tenant. A tenant has only one **c
### [cloudPcProvisioningPolicy ](https://docs.microsoft.com/graph/api/resources/cloudpcprovisioningpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alternateResourceUrl|String|The URL of the alternate resource that links to this provisioning policy. Read-only.|
|cloudPcGroupDisplayName|String|The display name of the Cloud PC group that the Cloud PCs reside in. Read-only.|
|cloudPcNamingTemplate|String|The template used to name Cloud PCs provisioned using this policy. The template can contain custom text and replacement tokens, including `%USERNAME:x%` and `%RAND:x%`, which represent the user's name and a randomly generated number, respectively. For example, `CPC-%USERNAME:4%-%RAND:5%` means that the name of the Cloud PC starts with `CPC-`, followed by a four-character username, a `-` character, and then five random characters. The total length of the text generated by the template can't exceed 15 characters. Supports `$filter`, `$select`, and `$orderby`.|
|description|String|The provisioning policy description. Supports `$filter`, `$select`, and `$orderBy`. |
|displayName|String|The display name for the provisioning policy.|
|domainJoinConfigurations|cloudPcDomainJoinConfiguration collection|Specifies a list ordered by priority on how Cloud PCs join Microsoft Entra ID (Azure AD). Supports `$select`.|
|enableSingleSignOn|Boolean|`True` if the provisioned Cloud PC can be accessed by single sign-on. `False` indicates that the provisioned Cloud PC doesn't support this feature. The default value is `false`. Windows 365 users can use single sign-on to authenticate to Microsoft Entra ID with passwordless options (for example, FIDO keys) to access their Cloud PC. Optional.|
|gracePeriodInHours|Int32|The number of hours to wait before reprovisioning/deprovisioning happens. Read-only.|
|id|String|The unique identifier associated with the provisioning policy. This ID is auto populated during the creation of a new provisioning policy. Supports `$filter`, `$select`, and `$orderBy`. Read-only. Inherited from entity. |
|imageDisplayName|String|The display name of the operating system image that is used for provisioning. For example, `Windows 11 Preview + Microsoft 365 Apps 23H2 23H2`. Supports `$filter`, `$select`, and `$orderBy`. |
|imageId|String|The unique identifier that represents an operating system image that is used for provisioning new Cloud PCs. The format for a gallery type image is: {publisherName_offerName_skuName}. Supported values for each of the parameters are:<ul><li>publisher: `Microsoftwindowsdesktop`</li> <li>offer: `windows-ent-cpc`</li> <li>sku: `21h1-ent-cpc-m365`, `21h1-ent-cpc-os`, `20h2-ent-cpc-m365`, `20h2-ent-cpc-os`, `20h1-ent-cpc-m365`, `20h1-ent-cpc-os`, `19h2-ent-cpc-m365`, and `19h2-ent-cpc-os`</li></ul> Supports `$filter`, `$select`, and `$orderBy`.|
|imageType|cloudPcProvisioningPolicyImageType|The type of operating system image (custom or gallery) that is used for provisioning on Cloud PCs. Possible values are: `gallery`, `custom`. The default value is `gallery`. Supports $filter, $select, and $orderBy.|
|localAdminEnabled|Boolean|When `true`, the local admin is enabled for Cloud PCs; `false` indicates that the local admin isn't enabled for Cloud PCs. The default value is `false`. Supports `$filter`, `$select`, and `$orderBy`.|
|microsoftManagedDesktop|microsoftManagedDesktop|The specific settings to **microsoftManagedDesktop** that enables Microsoft Managed Desktop customers to get device managed experience for Cloud PC. To enable **microsoftManagedDesktop** to provide more value, an admin needs to specify certain settings in it. Supports `$filter`, `$select`, and `$orderBy`.|
|provisioningType|cloudPcProvisioningType|Specifies the type of license used when provisioning Cloud PCs using this policy. By default, the license type is `dedicated` if the **provisioningType** isn't specified when you create the **cloudPcProvisioningPolicy**. You can't change this property after the **cloudPcProvisioningPolicy** was created. Possible values are: `dedicated`, `shared`, `unknownFutureValue`.|
|windowsSetting|cloudPcWindowsSetting|Indicates a specific Windows setting to configure during the creation of Cloud PCs for this provisioning policy. Supports `$select`. |
### [cloudPcProvisioningPolicyAssignment ](https://docs.microsoft.com/graph/api/resources/cloudpcprovisioningpolicyassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier for the provisioning policy assignment. If **target** is a user group, then the ID is shown as `{policyId_groupId}`. Read-only. Inherited from entity.|
|target|cloudPcManagementAssignmentTarget|The assignment target for the provisioning policy. Currently, the only target supported for this policy is a user group. For details, see cloudPcManagementGroupAssignmentTarget. |
### [cloudPcProvisioningPolicyAutopatch ](https://docs.microsoft.com/graph/api/resources/cloudpcprovisioningpolicyautopatch?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|autopatchGroupId|String|The unique identifier (ID) of a Windows Autopatch group. An Autopatch group is a logical container or unit that groups several Microsoft Entra groups and software update policies. Devices with the same Autopatch group ID share unified software update management. The default value is `null` that indicates that no Autopatch group is associated with the provisioning policy.|
### [cloudPcRemoteActionCapability ](https://docs.microsoft.com/graph/api/resources/cloudpcremoteactioncapability?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionCapability|actionCapability|Indicates the state of the supported action capability to perform a Cloud PC remote action. Possible values are: `enabled`, `disabled`. Default value is `enabled`.|
|actionName|cloudPcRemoteActionName|The name of the supported Cloud PC remote action. Possible values are: `unknown`, `restart`, `rename`, `restore`, `resize`, `reprovision`, `troubleShoot`, `changeUserAccountType`, `placeUnderReview`. Default value is `unknown`.|
### [cloudPcRemoteActionResult ](https://docs.microsoft.com/graph/api/resources/cloudpcremoteactionresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionName|String|The specified action. Supported values in the Microsoft Endpoint Manager portal are: `Reprovision`, `Resize`, `Restore`. Supported values in enterprise Cloud PC devices are: `Reboot`, `Rename`, `Reprovision`, `Troubleshoot`.|
|actionState|actionState|State of the action. Possible values are: `None`, `pending`, `canceled`, `active`, `done`, `failed`, `notSupported`. Read-only.|
|cloudPcId|String|The ID of the Cloud PC device on which the remote action is performed. Read-only.|
|managedDeviceId|String|The ID of the Intune managed device on which the remote action is performed. Read-only.|
|startDateTime|DateTimeOffset|Time the action was initiated. The Timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appears as '2014-01-01T00:00:00Z'.|
|lastUpdatedDateTime|DateTimeOffset|Last update time for action. The Timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appears as '2014-01-01T00:00:00Z'.|
|statusDetail|cloudPcStatusDetail|The extended details of the action status, including error code, error message, and additional information. For example, `"statusDetail": {"code": "internalServerError","message": "There was an internal server error. Please contact support xxx.","additionalInformation": [ { "@odata.type":"microsoft.graph.keyValuePair","name": "correlationId","value": "52367774-cfb7-4e9c-ab51-1b864c31f2d1"} ]}` |
|statusDetails (deprecated)|cloudPcStatusDetails|The details of the Cloud PC status. This property is deprecated and will no longer be supported effective August 31, 2024. Use statusDetail instead. |
### [cloudPcResizeValidationResult ](https://docs.microsoft.com/graph/api/resources/cloudpcresizevalidationresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|cloudPcId|String|The cloudPC ID that corresponds to its unique identifier.|
|validationResult|cloudPcResizeValidationCode|Describes a list of the validation result for the Cloud PC resize action. The possible values are: `success`, `cloudPcNotFound`, `operationCnflict`, `operationNotSupported`, `targetLicenseHasAssigned`, `internalServerError`, and `unknownFutureValue`.|
### [cloudPcRestorePointSetting ](https://docs.microsoft.com/graph/api/resources/cloudpcrestorepointsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|frequencyType|cloudPcRestorePointFrequencyType|The time interval in hours to take snapshots (restore points) of a Cloud PC automatically. Possible values are: `default`, `fourHours`, `sixHours`, `twelveHours`, `sixteenHours`, `twentyFourHours`, `unknownFutureValue`. The default value is `default` that indicates that the time interval for automatic capturing of restore point snapshots is set to 12 hours.|
|userRestoreEnabled|Boolean|If `true`, the user has the ability to use snapshots to restore Cloud PCs. If `false`, non-admin users can't use snapshots to restore the Cloud PC.|
### [cloudPcReviewStatus ](https://docs.microsoft.com/graph/api/resources/cloudpcreviewstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|azureStorageAccountId|String|The resource ID of the Azure Storage account in which the Cloud PC snapshot is being saved.|
|azureStorageAccountName|String|The name of the Azure Storage account in which the Cloud PC snapshot is being saved.|
|azureStorageContainerName|String|The name of the container in an Azure Storage account in which the Cloud PC snapshot is being saved.|
|inReview|Boolean| `True` if the Cloud PC is set to in review by the administrator.|
|restorePointDateTime|DateTimeOffset|The specific date and time of the Cloud PC snapshot that was taken and saved automatically, when the Cloud PC is set to in review. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appears as `2014-01-01T00:00:00Z`.|
|reviewStartDateTime|DateTimeOffset|The specific date and time when the Cloud PC was set to in review. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 appears as `2014-01-01T00:00:00Z`.|
|subscriptionId|String|The ID of the Azure subscription in which the Cloud PC snapshot is being saved, in GUID format.|
|subscriptionName|String|The name of the Azure subscription in which the Cloud PC snapshot is being saved.|
|userAccessLevel|cloudPcUserAccessLevel|The access level of the end user on the Cloud PC. Possible values are: `unrestricted`, `restricted`.|
### [cloudPcScopedPermission ](https://docs.microsoft.com/graph/api/resources/cloudpcscopedpermission?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|permission|String|	The operations allowed on scoped resources for the authenticated user. Example permission is `Microsoft.CloudPC/ProvisioningPolicies/Create`. |
|scopeIds|Collection(String)|The scope IDs of corresponding permission. Currently, it's Intune scope tag ID.|
### [cloudPcServicePlan ](https://docs.microsoft.com/graph/api/resources/cloudpcserviceplan?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The name for the service plan. Read-only.|
|id|String|Unique identifier for the service plan. Read-only.|
|provisioningType|cloudPcProvisioningType|Specifies the type of license used when provisioning Cloud PCs. By default, the license type is `dedicated`. Possible values are: `dedicated`, `shared`, `unknownFutureValue`, `sharedByUser`, `sharedByEntraGroup`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `sharedByUser`, `sharedByEntraGroup`. The `shared` member is deprecated and will stop returning on April 30, 2027; going forward, use the `sharedByUser` member.|
|ramInGB|Int32|The size of the RAM in GB. Read-only.|
|supportedSolution|cloudPcManagementService|The supported service or solution for the region. The possible values are: `windows365`, `devBox`, `rpaBox`, `unknownFutureValue`. Read-only.|
|storageInGB|Int32|The size of the OS Disk in GB. Read-only.|
|type|cloudPcServicePlanType|The type of the service plan. Possible values are: `enterprise`, `business`, `unknownFutureValue`. Read-only.|
|userProfileInGB|Int32|The size of the user profile disk in GB. Read-only.|
|vCpuCount|Int32|The number of vCPUs. Read-only.|
### [cloudpcshareduseserviceplan](https://docs.microsoft.com/graph/api/resources/cloudpcshareduseserviceplan?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                         |
|:------------|:-------|:--------------------------------------------------------------------|
| displayName | String | The display name of the shared-use service plan.                    |
| id          | String | The unique identifier for the shared-use service plan.              |
| totalCount  | Int32  | Total number of shared-use service plans purchased by the customer. |
| usedCount   | Int32  | The number of service plans that the account uses.                  |
### [cloudPcSnapshot ](https://docs.microsoft.com/graph/api/resources/cloudpcsnapshot?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|cloudPcId|String|The unique identifier for the Cloud PC.|
|createdDateTime|DateTimeOffset|The date and time at which the snapshot was taken. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String|The unique identifier for the snapshot of the Cloud PC device at a specific point in time. Inherited from entity.|
|lastRestoredDateTime|DateTimeOffset|The date and time at which the snapshot was last used to restore the Cloud PC device. The timestamp is shown in ISO 8601 format and Coordinated Universal Time (UTC). For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|snapshotType| cloudPcSnapshotType   | The type of snapshot that indicates how to create the snapshot. Possible values are `automatic`, `manual`. Default value is `automatic`.|
|status|cloudPcSnapshotStatus|The status of the Cloud PC snapshot. The possible values are: `ready`, `unknownFutureValue`.|
|expirationDateTime|DateTimeOffset| The date and time when the snapshot expires. The time is shown in ISO 8601 format and Coordinated Universal Time (UTC) time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [cloudPcSourceDeviceImage ](https://docs.microsoft.com/graph/api/resources/cloudpcsourcedeviceimage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name for the source image. Read-only.|
|resourceId|String| The fully qualified unique identifier (ID) of the source image resource in Azure. The ID format is: "/subscriptions/{subscription-id}/resourceGroups/{resourceGroupName}/providers/Microsoft.Compute/images/{imageName}". Read-only.|
|subscriptionDisplayName|String|The display name of the subscription that hosts the source image. Read-only.|
|subscriptionId|String|The unique identifier (ID) of the subscription that hosts the source image. Read-only.|
### [cloudPcSubscription ](https://docs.microsoft.com/graph/api/resources/cloudpcsubscription?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|subscriptionId|String|The ID of the subscription.|
|subscriptionName|String|The name of the subscription.|
### [cloudPcSupportedRegion ](https://docs.microsoft.com/graph/api/resources/cloudpcsupportedregion?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---      |:---  |:---         |
|displayName|String|The name for the supported region. Read-only.|
|id|String|The unique identifier for the supported region. Read-only.|
|regionGroup|cloudPcRegionGroup|The geographic group this region belongs to. Multiple regions can belong to one region group. For example, the `europeUnion` region group contains the Northern Europe and Western Europe regions. A customer can select a region group when provisioning a Cloud PC; however, the Cloud PC is put under one of the regions under the group based on resource capacity. The region with more quota is chosen. Possible values are: `default`, `australia`, `canada`, `usCentral`, `usEast`, `usWest`, `france`, `germany`, `europeUnion`, `unitedKingdom`, `japan`, `asia`, `india`, `southAmerica`, `euap`, `usGovernment`, `usGovernmentDOD`, `unknownFutureValue`, `norway`, `switzerland`，`southKorea`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `norway`, `switzerland`，`southKorea`. Read-only.|
|regionStatus|cloudPcSupportedRegionStatus|The status of the supported region. Possible values are: `available`, `restricted`, `unavailable`, `unknownFutureValue`. Read-only.|
|supportedSolution|cloudPcManagementService|The supported service or solution for the region. The possible values are: `windows365`, `devBox`, `unknownFutureValue`, `rpaBox`. You must use the `Prefer: include-unknown-enum-members` request header to get the following value or values in this evolvable enum: `rpaBox`. Read-only.|
### [cloudPcTenantEncryptionSetting ](https://docs.microsoft.com/graph/api/resources/cloudpctenantencryptionsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|tenantDiskEncryptionType|cloudPcDiskEncryptionType|Indicates the Cloud PC disk encryption type for a tenant. It is a tenant-level setting that applies globally to all Cloud PCs in the tenant. Possible values are: `platformManagedKey`, `customerManagedKey`, `unknownFutureValue`. Read-only.|
|lastSyncDateTime|DateTimeOffset|Indicates the date and time when last sync tenant encryption setting.|
### [cloudPcUserSetting ](https://docs.microsoft.com/graph/api/resources/cloudpcusersetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when the setting was created. The timestamp type represents the date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|displayName|String|The setting name displayed in the user interface. |
|id|String|Unique identifier for the Cloud PC user setting. Read-only. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the setting was last modified. The timestamp type represents the date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|localAdminEnabled|Boolean|Indicates whether the local admin option is enabled. The default value is `false`. To enable the local admin option, change the setting to `true`. If the local admin option is enabled, the end user can be an admin of the Cloud PC device. |
|resetEnabled|Boolean|Indicates whether an end user is allowed to reset their Cloud PC. When `true`, the user is allowed to reset their Cloud PC. When `false`, end-user initiated reset is not allowed. The default value is `false`. |
|restorePointSetting|cloudPcRestorePointSetting|Defines how frequently a restore point is created that is, a snapshot is taken) for users' provisioned Cloud PCs (default is 12 hours), and whether the user is allowed to restore their own Cloud PCs to a backup made at a specific point in time.|
### [cloudPcUserSettingAssignment ](https://docs.microsoft.com/graph/api/resources/cloudpcusersettingassignment?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when this assignment was created. The timestamp type represents the date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|id|String|Unique Identifier for the user setting assignment. If **target** is a user group, the ID has the following structure: `{policyID}\_{groupID}`. Read-only. Inherited from entity.|
|target|cloudPcManagementAssignmentTarget|The assignment target for the user setting. Currently, the only target supported for this user setting is a user group. For details, see cloudPcManagementGroupAssignmentTarget.|
### [cloudPcWindowsSetting ](https://docs.microsoft.com/graph/api/resources/cloudpcwindowssetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|locale|String|The Windows language or region tag to use for language pack configuration and localization of the Cloud PC. The default value is `en-US`, which corresponds to English (United States).|
### [cloudPcWindowsSettings ](https://docs.microsoft.com/graph/api/resources/cloudpcwindowssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|language|String|The Windows language/region tag to use for language pack configuration and localization of the Cloud PC. The default value is `en-US`, which corresponds to English (United States).|
### [alertRecord ](https://docs.microsoft.com/graph/api/resources/devicemanagement-alertrecord?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertImpact|microsoft.graph.deviceManagement.alertImpact|The impact of the alert event. Consists of a list of key-value pair and a number followed by the aggregation type. For example, `6 affectedCloudPcCount` means that 6 Cloud PCs are affected. `12 affectedCloudPcPercentage` means 12% of Cloud PCs are affected. The list of key-value pair indicates the details of the alert impact.|
|alertRuleId|String|The corresponding ID of the alert rule.|
|alertRuleTemplate|microsoft.graph.deviceManagement.alertRuleTemplate|The rule template of the alert event. The possible values are: `cloudPcProvisionScenario`, `cloudPcImageUploadScenario`, `cloudPcOnPremiseNetworkConnectionCheckScenario`, `unknownFutureValue`, `cloudPcInGracePeriodScenario`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `cloudPcInGracePeriodScenario`.|
|detectedDateTime|DateTimeOffset|The date and time when the alert event was detected. The Timestamp type represents date and time information using ISO 8601 format. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|The display name of the alert record.|
|id|String|The unique identifier for the alert record. Inherited from entity.|
|lastUpdatedDateTime|DateTimeOffset|The date and time when the alert record was last updated. The Timestamp type represents date and time information using ISO 8601 format. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|resolvedDateTime|DateTimeOffset|The date and time when the alert event was resolved. The Timestamp type represents date and time information using ISO 8601 format. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|severity|microsoft.graph.deviceManagement.ruleSeverityType|The severity of the alert event. The possible values are: `unknown`, `informational`, `warning`, `critical`, `unknownFutureValue`.|
|status|microsoft.graph.deviceManagement.alertStatusType|The status of the alert record. The possible values are: `active`, `resolved`, `unknownFutureValue`.|
### [alertRule ](https://docs.microsoft.com/graph/api/resources/devicemanagement-alertrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertRuleTemplate|microsoft.graph.deviceManagement.alertRuleTemplate|The rule template of the alert event. The possible values are: `cloudPcProvisionScenario`, `cloudPcImageUploadScenario`, `cloudPcOnPremiseNetworkConnectionCheckScenario`, `cloudPcInGracePeriodScenario`, `cloudPcFrontlineInsufficientLicensesScenario`, `cloudPcInaccessibleScenario`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `cloudPcInGracePeriodScenario`.|
|description|String|The rule description.|
|displayName|String|The display name of the rule.|
|enabled|Boolean|The status of the rule that indicates whether the rule is enabled or disabled. If `true`, the rule is enabled; otherwise, the rule is disabled.|
|id|String|The unique identifier for the alert rule. Inherited from entity.|
|isSystemRule|Boolean|Indicates whether the rule is a system rule. If `true`, the rule is a system rule; otherwise, the rule is a custom-defined rule and can be edited. System rules are built in and only a few properties can be edited.|
|notificationChannels|microsoft.graph.deviceManagement.notificationChannel collection|The notification channels of the rule selected by the user.|
|severity|microsoft.graph.deviceManagement.ruleSeverityType|The severity of the rule. The possible values are: `unknown`, `informational`, `warning`, `critical`, `unknownFutureValue`.|
|threshold|microsoft.graph.deviceManagement.ruleThreshold|The conditions that determine when to send alerts. For example, you can configure a condition to send an alert when provisioning fails for six or more Cloud PCs. This property is deprecated. Use conditions instead.|
|conditions|microsoft.graph.deviceManagement.ruleCondition collection|The conditions that determine when to send alerts. For example, you can configure a condition to send an alert when provisioning fails for six or more Cloud PCs.|
### [notificationChannel ](https://docs.microsoft.com/graph/api/resources/devicemanagement-notificationchannel?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|notificationChannelType|microsoft.graph.deviceManagement.notificationChannelType|The type of the notification channel. The possible values are: `portal`, `email`, `phoneCall`, `sms`, `unknownFutureValue`.|
|notificationReceivers|microsoft.graph.deviceManagement.notificationReceiver collection|Information about the notification receivers, such as locale and contact information. For example, `en-us` for locale and `serena.davis@contoso.com` for contact information.|
### [portalNotification ](https://docs.microsoft.com/graph/api/resources/devicemanagement-portalnotification?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|alertImpact|microsoft.graph.deviceManagement.alertImpact|The associated alert impact.|
|alertRecordId|String|The associated alert record ID.|
|alertRuleId|String|The associated alert rule ID.|
|alertRuleName|String|The associated alert rule name.|
|alertRuleTemplate|microsoft.graph.deviceManagement.alertRuleTemplate|The associated alert rule template. The possible values are: `cloudPcProvisionScenario`, `cloudPcImageUploadScenario`, `cloudPcOnPremiseNetworkConnectionCheckScenario`, `unknownFutureValue`, `cloudPcInGracePeriodScenario`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `cloudPcInGracePeriodScenario`.|
|id|String|The unique identifier for the portal notification.|
|isPortalNotificationSent|Boolean|`true` if the portal notification has already been sent to the user; `false` otherwise.|
|severity|microsoft.graph.deviceManagement.ruleSeverityType|The associated alert rule severity. The possible values are: `unknown`, `informational`, `warning`, `critical`, `unknownFutureValue`.|
### [ruleCondition ](https://docs.microsoft.com/graph/api/resources/devicemanagement-rulecondition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|relationshipType|microsoft.graph.deviceManagement.relationshipType| The relationship type.  Possible values are: `and`, `or`.|
|conditionCategory|microsoft.graph.deviceManagement.conditionCategory|The property that the rule condition monitors. Possible values are:  `provisionFailures`, `imageUploadFailures`, `azureNetworkConnectionCheckFailures`, `cloudPcInGracePeriod`, `frontlineInsufficientLicenses`, `cloudPcConnectionErrors`, `cloudPcHostHealthCheckFailures`, `cloudPcZoneOutage`, `unknownFutureValue`.|
|aggregation|microsoft.graph.deviceManagement.aggregationType|The built-in aggregation method for the rule condition. The possible values are: `count`, `percentage`, `affectedCloudPcCount`, `affectedCloudPcPercentage`, `unknownFutureValue`.|
|operator|microsoft.graph.deviceManagement.operatorType|The built-in operator for the rule condition. The possible values are: `greaterOrEqual`, `equal`, `greater`, `less`, `lessOrEqual`, `notEqual`, `unknownFutureValue`.|
|thresholdValue|String|The threshold value of the alert condition. The threshold value can be a number in string form or string like "WestUS".|
### [ruleThreshold ](https://docs.microsoft.com/graph/api/resources/devicemanagement-rulethreshold?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|aggregation|microsoft.graph.deviceManagement.aggregationType|Indicates the built-in aggregation methods. The possible values are: `count`, `percentage`, `affectedCloudPcCount`, `affectedCloudPcPercentage`, `unknownFutureValue`.|
|operator|microsoft.graph.deviceManagement.operatorType|Indicates the built-in operator. The possible values are: `greaterOrEqual`, `equal`, `greater`, `less`, `lessOrEqual`, `notEqual`, `unknownFutureValue`.|
|target|Int32|The target threshold value.|
### [cloudPcConnection ](https://docs.microsoft.com/graph/api/resources/managedtenants-cloudpcconnection?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name of the cloud PC connection. Required. Read-only.|
|healthCheckStatus|String|The health status of the cloud PC connection. Possible values are: `pending`, `running`, `passed`, `failed`, `unknownFutureValue`.  Required. Read-only.|
|id|String|The unique identifier for the cloud PC connection. Required. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Required. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Required. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Required. Read-only.|
### [cloudPcDevice ](https://docs.microsoft.com/graph/api/resources/managedtenants-cloudpcdevice?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|cloudPcStatus|String|The status of the cloud PC. Possible values are: `notProvisioned`, `provisioning`, `provisioned`, `upgrading`, `inGracePeriod`, `deprovisioning`, `failed`. Required. Read-only.|
|deviceSpecification|String|The specification of the cloud PC device. Required. Read-only.|
|displayName|String|The display name  of the cloud PC device. Required. Read-only.|
|id|String|The unique identifier of the cloud PC device. Required. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Required. Read-only.|
|managedDeviceId|String|The managed device identifier of the cloud PC device. Optional. Read-only.|
|managedDeviceName|String|The managed device display name of the cloud PC device. Optional. Read-only.|
|provisioningPolicyId|String|The provisioning policy identifier for the cloud PC device. Required. Read-only.|
|servicePlanName|String|The service plan name of the cloud PC device. Required. Read-only.|
|servicePlanType|String|The service plan type of the cloud PC device. Required. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Required. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Required. Read-only.|
|userPrincipalName|String|The user principal name (UPN) of the user assigned to the cloud PC device. Required. Read-only.|
### [cloudPcOverview ](https://docs.microsoft.com/graph/api/resources/managedtenants-cloudpcoverview?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|frontlineLicensesCount|Int32|The total number of cloud PC devices that have the `Frontline` SKU. Optional. Read-only.|
|id|String|The unique identifier for the cloud PC overview. Required. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Optional. Read-only.|
|numberOfCloudPcConnectionStatusFailed|Int32|The number of cloud PC connections that have a status of `failed`. Optional. Read-only.|
|numberOfCloudPcConnectionStatusPassed|Int32|The number of cloud PC connections that have a status of `passed`. Optional. Read-only.|
|numberOfCloudPcConnectionStatusPending|Int32|The number of cloud PC connections that have a status of `pending`. Optional. Read-only.|
|numberOfCloudPcConnectionStatusRunning|Int32|The number of cloud PC connections that have a status of `running`. Optional. Read-only.|
|numberOfCloudPcConnectionStatusUnkownFutureValue|Int32|The number of cloud PC connections that have a status of `unknownFutureValue`. Optional. Read-only.|
|numberOfCloudPcStatusDeprovisioning|Int32|The number of cloud PCs that have a status of `deprovisioning`. Optional. Read-only.|
|numberOfCloudPcStatusFailed|Int32|The number of cloud PCs that have a status of `failed`. Optional. Read-only.|
|numberOfCloudPcStatusInGracePeriod|Int32|The number of cloud PCs that have a status of `inGracePeriod`. Optional. Read-only.|
|numberOfCloudPcStatusNotProvisioned|Int32|The number of cloud PCs that have a status of `notProvisioned`. Optional. Read-only.|
|numberOfCloudPcStatusProvisioned|Int32|The number of cloud PCs that have a status of `provisioned`. Optional. Read-only.|
|numberOfCloudPcStatusProvisioning|Int32|The number of cloud PCs that have a status of `provisioning`. Optional. Read-only.|
|numberOfCloudPcStatusUnknown|Int32|The number of cloud PCs that have a status of `unknown`. Optional. Read-only.|
|numberOfCloudPcStatusUpgrading|Int32|The number of cloud PCs that have a status of `upgrading`. Optional. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Optional. Read-only.|
|totalBusinessLicenses|Int32|The total number of cloud PC devices that have the `Business` SKU. Optional. Read-only.|
|totalCloudPcConnectionStatus|Int32|The total number of cloud PC connection statuses for the given managed tenant. Optional. Read-only.|
|totalCloudPcStatus|Int32|The total number of cloud PC statues for the given managed tenant. Optional. Read-only.|
|totalEnterpriseLicenses|Int32|The total number of cloud PC devices that have the `Enterprise` SKU. Optional. Read-only.|
### [microsoftManagedDesktop ](https://docs.microsoft.com/graph/api/resources/microsoftmanageddesktop?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|managedType|microsoftManagedDesktopType|Indicates the provisioning policy associated with Microsoft Managed Desktop settings. Possible values are: `notManaged`, `premiumManaged`, `standardManaged`, `starterManaged`, `unknownFutureValue`. The default is `notManaged`.|
|profile|String|The name of the Microsoft Managed Desktop profile that the Windows 365 Cloud PC is associated with.|
### [unifiedRoleAssignment ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appScopeId|String|Identifier of the app specific scope when the assignment scope is app specific. The scope of an assignment determines the set of resources for which the principal has been granted access. App scopes are scopes that are defined and understood by a resource application only. For the entitlement management provider, use this property to specify a catalog. For example, `/AccessPackageCatalog/beedadfe-01d5-4025-910b-84abb9369997`. Supports `$filter` (`eq`, `in`). For example, `/roleManagement/entitlementManagement/roleAssignments?$filter=appScopeId eq '/AccessPackageCatalog/{catalog id}'`.|
|directoryScopeId|String|Identifier of the directory object representing the scope of the assignment. The scope of an assignment determines the set of resources for which the principal has been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications, unlike app scopes that are defined and understood by a resource application only. Supports `$filter` (`eq`, `in`).|
|id|String| The unique identifier for the unifiedRoleAssignment. Key, not nullable, Read-only. |
|principalId|String| Identifier of the principal to which the assignment is granted. Supported principals are users, role-assignable groups, and service principals. Supports `$filter` (`eq`, `in`). |
|roleDefinitionId|String| Identifier of the unifiedRoleDefinition the assignment is for. Read-only. Supports `$filter` (`eq`, `in`). |
### [unifiedRoleAssignmentMultiple ](https://docs.microsoft.com/graph/api/resources/unifiedroleassignmentmultiple?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| appScopeIds | String collection | Ids of the app specific scopes when the assignment scopes are app specific. The scopes of an assignment determine the set of resources for which the principal has access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. Use `/` for tenant-wide scope. App scopes are scopes that are defined and understood by this application only. |
| description | String | Description of the role assignment. |
| directoryScopeIds | String collection | Ids of the directory objects that represent the scopes of the assignment. The scopes of an assignment determine the set of resources for which the principals have been granted access. Directory scopes are shared scopes stored in the directory that are understood by multiple applications. App scopes are scopes that are defined and understood by this application only. |
| displayName | String | Name of the role assignment. Required. |
| id | String | The unique identifier for the **unifiedRoleAssignmentMultiple** object. Key, not nullable, Read-only. |
| principalIds | String collection | Identifiers of the principals to which the assignment is granted. Supports `$filter` (`any` operator only). |
| roleDefinitionId | String | Identifier of the unifiedRoleDefinition the assignment is for. |
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
