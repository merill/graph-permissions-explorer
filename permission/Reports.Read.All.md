# Reports.Read.All

> Allows an app to read all service usage reports on behalf of the signed-in user.  Services that provide usage reports include Office 365 and Azure Active Directory.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /print/reports/dailyPrintUsageByPrinter](https://docs.microsoft.com/graph/api/reportroot-list-dailyprintusagebyprinter?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/dailyPrintUsageByPrinter/{id}](https://docs.microsoft.com/graph/api/printusagebyprinter-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/dailyPrintUsageByUser](https://docs.microsoft.com/graph/api/reportroot-list-dailyprintusagebyuser?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/dailyPrintUsageByUser/{id}](https://docs.microsoft.com/graph/api/printusagebyuser-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/getGroupArchivedPrintJobs(groupId='{groupId}',startDateTime='{startDateTime}',endDateTime='{endDateTime}')](https://docs.microsoft.com/graph/api/reports-getgrouparchivedprintjobs?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/getPrinterArchivedPrintJobs(printerId='{printerId}',startDateTime='{startDateTime}',endDateTime='{endDateTime}')](https://docs.microsoft.com/graph/api/reports-getprinterarchivedprintjobs?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/getUserArchivedPrintJobs(userId='{userId}',startDateTime='{startDateTime}',endDateTime='{endDateTime}')](https://docs.microsoft.com/graph/api/reports-getuserarchivedprintjobs?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/monthlyPrintUsageByPrinter](https://docs.microsoft.com/graph/api/reportroot-list-monthlyprintusagebyprinter?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/monthlyPrintUsageByPrinter/{id}](https://docs.microsoft.com/graph/api/printusagebyprinter-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/monthlyPrintUsageByUser](https://docs.microsoft.com/graph/api/reportroot-list-monthlyprintusagebyuser?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /print/reports/monthlyPrintUsageByUser/{id}](https://docs.microsoft.com/graph/api/printusagebyuser-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /reports/applicationSignInDetailedSummary](https://docs.microsoft.com/graph/api/reportroot-list-applicationsignindetailedsummary?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /reports/applicationSignInDetailedSummary/{id}](https://docs.microsoft.com/graph/api/applicationsignindetailedsummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/credentialUserRegistrationDetails](https://docs.microsoft.com/graph/api/reportroot-list-credentialuserregistrationdetails?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /reports/dailyPrintUsageByPrinter](https://docs.microsoft.com/graph/api/reportroot-list-dailyprintusagebyprinter?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/dailyPrintUsageByPrinter/{id}](https://docs.microsoft.com/graph/api/printusagebyprinter-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/dailyPrintUsageByUser](https://docs.microsoft.com/graph/api/reportroot-list-dailyprintusagebyuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/dailyPrintUsageByUser/{id}](https://docs.microsoft.com/graph/api/printusagebyuser-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getBrowserDistributionUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getbrowserdistributionusercounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getBrowserUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getbrowserusercounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getBrowserUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getbrowseruserdetail?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getCredentialUsageSummary(period='{periodValue}')](https://docs.microsoft.com/graph/api/reportroot-getcredentialusagesummary?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getCredentialUserRegistrationCount](https://docs.microsoft.com/graph/api/reportroot-getcredentialuserregistrationcount?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/getEmailActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailactivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailactivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailActivityUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getemailactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailAppUsageAppsUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailappusageappsusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailAppUsageUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailappusageusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailAppUsageUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getemailappusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailAppUsageUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailappusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getEmailAppUsageVersionsUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getemailappusageversionsusercounts?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getFormsUserActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getformsuseractivitycounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getFormsUserActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getformsuseractivityuserdetail?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /reports/getGroupArchivedPrintJobs(groupId='{groupId}',startDateTime='{startDateTime}',endDateTime='{endDateTime}')](https://docs.microsoft.com/graph/api/reports-getgrouparchivedprintjobs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getM365AppPlatformUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getm365appplatformusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getM365AppUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getm365appusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getM365AppUserDetail(date='{date_value}')](https://docs.microsoft.com/graph/api/reportroot-getm365appuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getM365AppUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getm365appuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getMailboxUsageDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getmailboxusagedetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getMailboxUsageMailboxCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getmailboxusagemailboxcounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getMailboxUsageQuotaStatusMailboxCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getmailboxusagequotastatusmailboxcounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getMailboxUsageStorage(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getmailboxusagestorage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ActivationCounts](https://docs.microsoft.com/graph/api/reportroot-getoffice365activationcounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ActivationsUserCounts](https://docs.microsoft.com/graph/api/reportroot-getoffice365activationsusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ActivationsUserDetail](https://docs.microsoft.com/graph/api/reportroot-getoffice365activationsuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ActiveUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365activeusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ActiveUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getoffice365activeuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ActiveUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365activeuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365GroupsActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365groupsactivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365GroupsActivityDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getoffice365groupsactivitydetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365GroupsActivityDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365groupsactivitydetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365GroupsActivityFileCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365groupsactivityfilecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365GroupsActivityGroupCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365groupsactivitygroupcounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365GroupsActivityStorage(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365groupsactivitystorage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOffice365ServicesUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getoffice365servicesusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveActivityFileCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveactivityfilecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveactivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveActivityUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getonedriveactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveUsageAccountCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveusageaccountcounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveUsageAccountDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getonedriveusageaccountdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveUsageAccountDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveusageaccountdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveUsageFileCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveusagefilecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getOneDriveUsageStorage(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getonedriveusagestorage?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/getPrinterArchivedPrintJobs(printerId='{printerId}',startDateTime='{startDateTime}',endDateTime='{endDateTime}')](https://docs.microsoft.com/graph/api/reports-getprinterarchivedprintjobs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getRelyingPartyDetailedSummary(period='parameterValue')](https://docs.microsoft.com/graph/api/reportroot-getrelyingpartydetailedsummary?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointActivityFileCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointactivityfilecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointActivityPages(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointactivitypages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointactivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointActivityUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getsharepointactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointSiteUsageDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getsharepointsiteusagedetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointSiteUsageDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointsiteusagedetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointSiteUsageFileCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointsiteusagefilecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointSiteUsagePages(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointsiteusagepages?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointSiteUsageSiteCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointsiteusagesitecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSharePointSiteUsageStorage(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getsharepointsiteusagestorage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessactivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessactivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessActivityUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessactivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessDeviceUsageDistributionUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessdeviceusagedistributionusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessDeviceUsageUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessdeviceusageusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessDeviceUsageUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessdeviceusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessDeviceUsageUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessdeviceusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessOrganizerActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessorganizeractivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessOrganizerActivityMinuteCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessorganizeractivityminutecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessOrganizerActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessorganizeractivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessParticipantActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessparticipantactivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessParticipantActivityMinuteCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessparticipantactivityminutecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessParticipantActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinessparticipantactivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessPeerToPeerActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinesspeertopeeractivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessPeerToPeerActivityMinuteCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinesspeertopeeractivityminutecounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getSkypeForBusinessPeerToPeerActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getskypeforbusinesspeertopeeractivityusercounts?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsDeviceUsageDistributionTotalUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusagedistributiontotalusercounts?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/getTeamsDeviceUsageDistributionUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusagedistributionusercounts?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsDeviceUsageDistributionUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusagedistributionusercounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsDeviceUsageTotalUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusagetotalusercounts?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/getTeamsDeviceUsageUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusageusercounts?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsDeviceUsageUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusageusercounts?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/getTeamsDeviceUsageUserDetail(date='{date_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsDeviceUsageUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsdeviceusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsTeamActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsteamactivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsTeamActivityDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsteamactivitydetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsTeamActivityDistributionCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsteamactivitydistributioncounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsTeamCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsteamcounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsUserActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitycounts?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitycounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityDistributionTotalUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitydistributiontotalusercounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityDistributionUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitydistributionusercounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityTotalCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitytotalcounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityTotalDistributionCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitytotaldistributioncounts?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityTotalUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivitytotalusercounts?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/getTeamsUserActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivityusercounts?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/getTeamsUserActivityUserCounts(period='D7')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivityusercounts?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/getTeamsUserActivityUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getTeamsUserActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getteamsuseractivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/getUserArchivedPrintJobs(userId='{userId}',startDateTime='{startDateTime}',endDateTime='{endDateTime}')](https://docs.microsoft.com/graph/api/reports-getuserarchivedprintjobs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammeractivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerActivityUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammeractivityusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerActivityUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getyammeractivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerActivityUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammeractivityuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerDeviceUsageDistributionUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammerdeviceusagedistributionusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerDeviceUsageUserCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammerdeviceusageusercounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerDeviceUsageUserDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getyammerdeviceusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerDeviceUsageUserDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammerdeviceusageuserdetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerGroupsActivityCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammergroupsactivitycounts?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerGroupsActivityDetail(date={date_value})](https://docs.microsoft.com/graph/api/reportroot-getyammergroupsactivitydetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerGroupsActivityDetail(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammergroupsactivitydetail?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/getYammerGroupsActivityGroupCounts(period='{period_value}')](https://docs.microsoft.com/graph/api/reportroot-getyammergroupsactivitygroupcounts?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/monthlyPrintUsageByPrinter](https://docs.microsoft.com/graph/api/reportroot-list-monthlyprintusagebyprinter?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/monthlyPrintUsageByPrinter/{id}](https://docs.microsoft.com/graph/api/printusagebyprinter-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/monthlyPrintUsageByUser](https://docs.microsoft.com/graph/api/reportroot-list-monthlyprintusagebyuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /reports/monthlyPrintUsageByUser/{id}](https://docs.microsoft.com/graph/api/printusagebyuser-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /reports/serviceActivity/getMetricsForConditionalAccessCompliantDevicesSignInSuccess](https://docs.microsoft.com/graph/api/serviceactivity-getmetricsforconditionalaccesscompliantdevicessigninsuccess?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/serviceActivity/getMetricsForConditionalAccessManagedDevicesSignInSuccess](https://docs.microsoft.com/graph/api/serviceactivity-getmetricsforconditionalaccessmanageddevicessigninsuccess?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/serviceActivity/getMetricsForMfaSignInFailure](https://docs.microsoft.com/graph/api/serviceactivity-getmetricsformfasigninfailure?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/serviceActivity/getMetricsForMfaSignInSuccess](https://docs.microsoft.com/graph/api/serviceactivity-getmetricsformfasigninsuccess?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/serviceActivity/getMetricsForSamlSignInSuccess](https://docs.microsoft.com/graph/api/serviceactivity-getmetricsforsamlsigninsuccess?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/sla/azureADAuthentication](https://docs.microsoft.com/graph/api/azureadauthentication-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userCredentialUsageDetails](https://docs.microsoft.com/graph/api/reportroot-list-usercredentialusagedetails?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/credentialUserRegistrationsSummaries](https://docs.microsoft.com/graph/api/managedtenants-managedtenant-list-credentialuserregistrationssummaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /tenantRelationships/managedTenants/credentialUserRegistrationsSummaries/{credentialUserRegistrationsSummaryId}](https://docs.microsoft.com/graph/api/managedtenants-credentialuserregistrationssummary-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET reports/getAzureADApplicationSignInSummary(period='{period}')](https://docs.microsoft.com/graph/api/reportroot-getazureadapplicationsigninsummary?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|02e97553-ed7b-43d0-ab3c-f8bace0d040c|
|**Consent Type**|Admin|
|**Display String**|Read all usage reports|
|**Description**|Allows an app to read all service usage reports on behalf of the signed-in user.  Services that provide usage reports include Office 365 and Azure Active Directory.|
## Application Permission
|||
|-|-|
|**Id**|230c1aed-a721-4c5d-9cb4-a90514e508ef|
|**Display String**|Read all usage reports|
|**Description**|Allows an app to read all service usage reports without a signed-in user.  Services that provide usage reports include Office 365 and Azure Active Directory.|
## Resources
### [applicationSignInDetailedSummary ](https://docs.microsoft.com/graph/api/resources/applicationsignindetailedsummary?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|aggregatedEventDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|appDisplayName|String|Name of the application that the user signed in to.|
|appId|String|ID of the application that the user signed in to.|
|id|String| A unique ID representing the sign-in activity. Inherited from entity.|
|signInCount|Int64|Count of sign-ins made by the application.|
|status|signInStatus|Details of the sign-in status.|
### [applicationSignInSummary ](https://docs.microsoft.com/graph/api/resources/applicationsigninsummary?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|appDisplayName|String|Name of the application that the user signed into.|
|failedSignInCount|Int64|Count of failed sign-ins made by the application.|
|successPercentage|Int32|Percentage of successful sign-ins made by the application.|
|successfulSignInCount|Int64|Count of successful sign-ins made by the application.|
### [archivedPrintJob ](https://docs.microsoft.com/graph/api/resources/archivedprintjob?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String|The archived print job's GUID. Read-only.|
|printerId|String|The printer ID that the job was queued for. Read-only.|
|printerName|String|The printer name that the job was queued for. Read-only.|
|processingState|printJobProcessingState|The print job's final processing state. Read-only.|
|createdDateTime|DateTimeOffset|The dateTimeOffset when the job was created. Read-only.|
|acquiredDateTime|DateTimeOffset|The dateTimeOffset when the job was acquired by the printer, if any. Read-only.|
|completionDateTime|DateTimeOffset|The dateTimeOffset when the job was completed, canceled, or aborted. Read-only.|
|acquiredByPrinter|Boolean|True if the job was acquired by a printer; false otherwise. Read-only.|
|copiesPrinted|Int32|The number of copies that were printed. Read-only.|
|createdBy|userIdentity|The user who created the print job. Read-only.|
### [azureADAuthentication ](https://docs.microsoft.com/graph/api/resources/azureadauthentication?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attainments|serviceLevelAgreementAttainment collection|SLA data for a Microsoft Entra tenant for a calendar month.|
### [credentialUsageSummary ](https://docs.microsoft.com/graph/api/resources/credentialusagesummary?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| authMethod | usageAuthMethod | Represents the authentication method that the user used. Possible values are:`email`, `mobileSMS`, `mobileCall`, `officePhone`, `securityQuestion` (only used for self-service password reset), `appNotification`, `appCode`, `alternateMobileCall` (supported only in registration), `fido`, `appPassword`, `unknownFutureValue`. |
| failureActivityCount | Int64 | Provides the count of failed resets or registration data. |
| feature | featureType | Defines the feature to report. Possible values are: `registration`, `reset`, `unknownFutureValue`. |
| id | String | The unique identifier for the activity. Read-only. |
| successfulActivityCount | Int64 | Provides the count of successful registrations or resets. |
### [credentialUserRegistrationCount ](https://docs.microsoft.com/graph/api/resources/credentialuserregistrationcount?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| id | String | The unique identifier for the activity. Read-only. |
| totalUserCount | Int64 | Provides the count of users with **accountEnabled** set to `true` in the tenant. |
| userRegistrationCounts | userRegistrationCount collection | A collection of registration count and status information for users in your tenant. |
### [credentialUserRegistrationDetails ](https://docs.microsoft.com/graph/api/resources/credentialuserregistrationdetails?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| authMethods | registrationAuthMethod collection | Represents the authentication method that the user has registered. Possible values are: `email`, `mobilePhone`, `officePhone`,  `securityQuestion` (only used for self-service password reset), `appNotification`,  `appCode`, `alternateMobilePhone` (supported only in registration),  `fido`,  `appPassword`,  `unknownFutureValue`. |
| id | String | The unique identifier for the activity. Read-only.|
| isCapable | Boolean | Indicates whether the user is ready to perform self-service password reset or MFA. |
| isEnabled | Boolean | Indicates whether the user enabled to perform self-service password reset. |
| isMfaRegistered | Boolean | Indicates whether the user is registered for MFA. |
| isRegistered | Boolean | Indicates whether the user has registered any authentication methods for self-service password reset. |
| userDisplayName | String | Provides the user name of the corresponding user. |
| userPrincipalName | String | Provides the user principal name of the corresponding user. |
### [credentialUserRegistrationsSummary ](https://docs.microsoft.com/graph/api/resources/managedtenants-credentialuserregistrationssummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for this entity. Required. Read-only.|
|lastRefreshedDateTime|DateTimeOffset|Date and time the entity was last updated in the multi-tenant management platform. Optional. Read-only.|
|mfaAndSsprCapableUserCount|Int32|The number of users that are capable of performing multi-factor authentication or self service password reset. Optional. Read-only.|
|mfaConditionalAccessPolicyState|String|The state of a conditional access policy that enforces multi-factor authentication. Optional. Read-only.|
|mfaExcludedUserCount|Int32|The number of users in the multi-factor authentication exclusion security group (Microsoft 365 Lighthouse - MFA exclusions). Optional. Read-only.|
|mfaRegisteredUserCount|Int32|The number of users registered for multi-factor authentication. Optional. Read-only.|
|securityDefaultsEnabled|Boolean|A flag indicating whether Identity Security Defaults is enabled. Optional. Read-only.|
|ssprEnabledUserCount|Int32|The number of users enabled for self service password reset. Optional. Read-only.|
|ssprRegisteredUserCount|Int32|The number of users registered for self service password reset. Optional. Read-only.|
|tenantDisplayName|String|The display name for the managed tenant. Required. Read-only.|
|tenantId|String|The Microsoft Entra tenant identifier for the managed tenant. Required. Read-only.|
|tenantLicenseType|String|The license type associated with the tenant; for example, `AADFree`, `AADPremium1`, `AADPremium2`.|
|totalUserCount|Int32|The total number of users in the given managed tenant. Optional. Read-only.|
### [office365ActiveUserCounts ](https://docs.microsoft.com/graph/api/resources/office365activeusercounts?view=graph-rest-1.0&tabs=http)
| Property          | Type   | Description                              |
| :---------------- | :----- | ---------------------------------------- |
| reportRefreshDate | Date   | The latest date of the content.          |
| office365         | Int64  | The number of active users in Microsoft 365. This number includes all the active users in Exchange, OneDrive, SharePoint, Skype For Business, Yammer, and Microsoft Teams. You can find the definition of active user for each product in the respective property description. |
| exchange          | Int64  | The number of active users in Exchange. Any user who can read and send email is considered an active user. |
| oneDrive          | Int64  | The number of active users in OneDrive. Any user who viewed or edited files, shared files internally or externally, or synced files is considered an active user. |
| sharePoint        | Int64  | The number of active users in SharePoint. Any user who viewed or edited files, shared files internally or externally, synced files, or viewed SharePoint pages is considered an active user. |
| skypeForBusiness  | Int64  | The number of active users in Skype For Business. Any user who organized or participated in conferences, or joined peer-to-peer sessions is considered an active user. |
| yammer            | Int64  | The number of active users in Yammer. Any user who can post, read, or like messages is considered an active user. |
| teams             | Int64  | The number of active users in Microsoft Teams. Any user who posted messages in team channels, sent messages in private chat sessions, or participated in meetings or calls is considered an active user. |
| reportDate        | Date   | The date on which a number of users were active. |
| reportPeriod      | String | The number of days the report covers.    |
### [office365ActiveUserDetail ](https://docs.microsoft.com/graph/api/resources/office365activeuserdetail?view=graph-rest-1.0&tabs=http)
| Property                          | Type              | Description                              |
| :-------------------------------- | :---------------- | ---------------------------------------- |
| reportRefreshDate                 | Date              | The latest date of the content.          |
| userPrincipalName                 | String            | The user principal name (UPN) of the user. The UPN is an Internet-style login name for the user based on the Internet standard RFC 822. By convention, this should map to the user's email name. The general format is alias@domain, where domain must be present in the tenant’s collection of verified domains. This property is required when a user is created. |
| displayName                       | String            | The name displayed in the address book for the user. This is usually the combination of the user's first name, middle initial, and last name. This property is required when a user is created and it can't be cleared during updates. |
| isDeleted                         | Boolean           | Whether this user has been deleted or soft deleted. |
| deletedDate                       | Date              | The date when the delete operation happened. Default value is "null" when the user hasn't been deleted. |
| hasExchangeLicense                | Boolean           | Whether the user has been assigned an Exchange license. |
| hasOneDriveLicense                | Boolean           | Whether the user has been assigned a OneDrive license. |
| hasSharePointLicense              | Boolean           | Whether the user has been assigned a SharePoint license. |
| hasSkypeForBusinessLicense        | Boolean           | Whether the user has been assigned a Skype For Business license. |
| hasYammerLicense                  | Boolean           | Whether the user has been assigned a Yammer license. |
| hasTeamsLicense                   | Boolean           | Whether the user has been assigned a Teams license. |
| exchangeLastActivityDate          | Date              | The date when user last read or sent email. |
| oneDriveLastActivityDate          | Date              | The date when user last viewed or edited files, shared files internally or externally, or synced files. |
| sharePointLastActivityDate        | Date              | The date when user last viewed or edited files, shared files internally or externally, synced files, or viewed SharePoint pages. |
| skypeForBusinessLastActivityDate  | Date              | The date when user last organized or participated in conferences, or joined peer-to-peer sessions. |
| yammerLastActivityDate            | Date              | The date when user last posted, read, or liked message. |
| teamsLastActivityDate             | Date              | The date when user last posted messages in team channels, sent messages in private chat sessions, or participated in meetings or calls. |
| exchangeLicenseAssignDate         | Date              | The last date when the user was assigned an Exchange license. |
| oneDriveLicenseAssignDate         | Date              | The last date when the user was assigned a OneDrive license. |
| sharePointLicenseAssignDate       | Date              | The last date when the user was assigned a SharePoint license. |
| skypeForBusinessLicenseAssignDate | Date              | The last date when the user was assigned a Skype For Business license. |
| yammerLicenseAssignDate           | Date              | The last date when the user was assigned a Yammer license. |
| teamsLicenseAssignDate            | Date              | The last date when the user was assigned a Teams license. |
| assignedProducts                  | String collection | All the products assigned for the user.  |
### [office365GroupsActivityCounts ](https://docs.microsoft.com/graph/api/resources/office365groupsactivitycounts?view=graph-rest-1.0&tabs=http)
| Property               | Type   | Description                              |
| :--------------------- | :----- | ---------------------------------------- |
| reportRefreshDate      | Date   | The latest date of the content.          |
| exchangeEmailsReceived | Int64  | The number of emails received by Group mailboxes. |
| yammerMessagesPosted   | Int64  | The number of messages posted to Yammer groups. |
| yammerMessagesRead     | Int64  | The number of messages read in Yammer groups. |
| yammerMessagesLiked    | Int64  | The number of messages liked in Yammer groups. |
| teamsChannelMessages   | Int64  | The number of channel messages in Teams team. |
| teamsMeetingsOrganized | Int64  | The number of meetings organized in Teams team. |
| reportDate             | Date   | The date on which a number of emails were sent to a group mailbox or a number of messages were posted, read, or liked in a Yammer group |
| reportPeriod           | String | The number of days the report covers.    |
### [office365GroupsActivityDetail ](https://docs.microsoft.com/graph/api/resources/office365groupsactivitydetail?view=graph-rest-1.0&tabs=http)
| Property                          | Type    | Description                              |
| :-------------------------------- | :------ | ---------------------------------------- |
| groupId                           | String  | The group id.          |
| reportRefreshDate                 | Date    | The latest date of the content.          |
| groupDisplayName                  | String  | The display name of the group.           |
| isDeleted                         | Boolean | Whether this user has been deleted or soft deleted. |
| ownerPrincipalName                | String  | The group owner principal name.          |
| lastActivityDate                  | Date    | The last activity date for the following scenarios:  group mailbox received email; user viewed, edited, shared, or synced files in SharePoint document library; user viewed SharePoint pages; user posted, read, or liked messages in Yammer groups. |
| groupType                         | String  | The group type. Possible values are: **Public** or **Private**. |
| memberCount                       | Int64   | The group member count.                  |
| externalMemberCount               | Int64   | The group external member count.         |
| exchangeReceivedEmailCount        | Int64   | The number of emails that the group mailbox received. |
| sharePointActiveFileCount         | Int64   | The number of active files in SharePoint Group site. |
| yammerPostedMessageCount          | Int64   | The number of messages posted to Yammer groups. |
| yammerReadMessageCount            | Int64   | The number of messages read in Yammer groups. |
| yammerLikedMessageCount           | Int64   | The number of messages liked in Yammer groups. |
| teamsChannelMessagesCount         | Int64   | The number of channel messages in Teams team. |
| teamsMeetingsOrganizedCount       | Int64   | The number of meetings organized in Teams team. |
| exchangeMailboxTotalItemCount     | Int64   | The number of items in the group mailbox. |
| exchangeMailboxStorageUsedInBytes | Int64   | The storage used of the group mailbox.   |
| sharePointTotalFileCount          | Int64   | The total number of files in SharePoint Group site. |
| sharePointSiteStorageUsedInBytes  | Int64   | The storage used by SharePoint Group site. |
| reportPeriod                      | String  | The number of days the report covers.    |
### [office365GroupsActivityFileCounts ](https://docs.microsoft.com/graph/api/resources/office365groupsactivityfilecounts?view=graph-rest-1.0&tabs=http)
| Property          | Type   | Description                              |
| :---------------- | :----- | ---------------------------------------- |
| reportRefreshDate | Date   | The latest date of the content.          |
| total             | Int64  | The total number of files in the group's SharePoint document library. |
| active            | Int64  | The number of files that were viewed, edited, shared, or synced in the group's SharePoint document library. |
| reportDate        | Date   | The date on which a number of files were active in the group's SharePoint site. |
| reportPeriod      | String | The number of days the report covers.    |
### [office365GroupsActivityGroupCounts ](https://docs.microsoft.com/graph/api/resources/office365groupsactivitygroupcounts?view=graph-rest-1.0&tabs=http)
| Property          | Type   | Description                              |
| :---------------- | :----- | ---------------------------------------- |
| reportRefreshDate | Date   | The latest date of the content.          |
| total             | Int64  | The total number of groups.              |
| active            | Int64  | The number of active groups. A group is considered active if any of the following occurred: group mailbox received email, or  a user viewed, edited, shared, or synced files in SharePoint document library, or a user viewed SharePoint pages, or a user posted, read, or liked messages in Yammer groups. |
| reportDate        | Date   | The date on which groups were active. |
| reportPeriod      | String | The number of days the report covers.    |
### [office365GroupsActivityStorage ](https://docs.microsoft.com/graph/api/resources/office365groupsactivitystorage?view=graph-rest-1.0&tabs=http)
| Property                  | Type   | Description                              |
| :------------------------ | :----- | ---------------------------------------- |
| reportRefreshDate         | Date   | The latest date of the content.          |
| mailboxStorageUsedInBytes | Int64  | The storage used in group mailbox.       |
| siteStorageUsedInBytes    | Int64  | The storage used in SharePoint document library. |
| reportDate                | Date   | The snapshot date for Exchange and SharePoint used storage. |
| reportPeriod              | String | The number of days the report covers.    |
### [office365ServicesUserCounts ](https://docs.microsoft.com/graph/api/resources/office365servicesusercounts?view=graph-rest-1.0&tabs=http)
| Property                 | Type   | Description                              |
| :----------------------- | :----- | ---------------------------------------- |
| reportRefreshDate        | Date   | The latest date of the content.          |
| exchangeActive           | Int64  | The number of active users on Exchange. Any user who can read and send email is considered an active user. |
| exchangeInactive         | Int64  | The number of inactive users on Exchange. |
| oneDriveActive           | Int64  | The number of active users on OneDrive. Any user who viewed or edited files, shared files internally or externally, or synced files is considered an active user. |
| oneDriveInactive         | Int64  | The number of inactive users on OneDrive. |
| sharePointActive         | Int64  | The number of active users on SharePoint. Any user who viewed or edited files, shared files internally or externally, synced files, or viewed SharePoint pages is considered an active user. |
| sharePointInactive       | Int64  | The number of inactive users on SharePoint. |
| skypeForBusinessActive   | Int64  | The number of active users on Skype For Business. Any user who organized or participated in conferences, or joined peer-to-peer sessions is considered an active user. |
| skypeForBusinessInactive | Int64  | The number of inactive users on Skype For Business. |
| yammerActive             | Int64  | The number of active users on Yammer. Any user who can post, read, or like messages is considered an active user. |
| yammerInactive           | Int64  | The number of inactive users on Yammer.  |
| teamsActive              | Int64  | The number of active users on Microsoft Teams. Any user who posted messages in team channels, sent messages in private chat sessions, or participated in meetings or calls is considered an active user. |
| teamsInactive            | Int64  | The number of inactive users on Microsoft Teams.     |
| office365Active          | Int64  | The number of active users on Microsoft 365.   |
| office365Inactive        | Int64  | The number of inactive users on Microsoft 365.     |
| reportPeriod             | String | The number of days the report covers.    |
### [printer ](https://docs.microsoft.com/graph/api/resources/printer?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|capabilities|printerCapabilities|The capabilities of the printer associated with this printer share. Inherited from printerBase.|
|defaults|printerDefaults|The printer's default print settings. Inherited from printerBase.|
|displayName|String|The name of the printer. Inherited from printerBase.|
|hasPhysicalDevice|Boolean|True if the printer has a physical device for printing. Read-only.|
|id|String|The document's identifier. Inherited from printerBase. Read-only.|
|isAcceptingJobs|Boolean|True if the printer is currently accepting new print jobs. Inherited from printerBase.|
|isShared|Boolean|True if the printer is shared; false otherwise. Read-only.|
|lastSeenDateTime|DateTimeOffset|The most recent dateTimeOffset when a printer interacted with Universal Print. Read-only.|
|location|printerLocation|The physical and/or organizational location of the printer. Inherited from printerBase.|
|manufacturer|String|The manufacturer reported by the printer. Inherited from printerBase.|
|model|String|The model name reported by the printer. Inherited from printerBase.|
|registeredDateTime|DateTimeOffset|The DateTimeOffset when the printer was registered. Read-only.|
|status|printerStatus|The processing status of the printer, including any errors. Inherited from printerBase.|
### [printUsageByPrinter ](https://docs.microsoft.com/graph/api/resources/printusagebyprinter?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|blackAndWhitePageCount|Int64|The estimated number of black and white pages printed based on reporting by the printer.|
|colorPageCount|Int64|The estimated number of color pages printed based on reporting by the printer.|
|completedBlackAndWhiteJobCount|Int64|The number of black and white print jobs completed by the printer.|
|completedColorJobCount|Int64|The number of color print jobs completed by the printer.|
|completedJobCount|Int64|The number of print jobs that were completed by the printer.|
|doubleSidedSheetCount|Int64|The estimated number of double-sided media sheets printed based on reporting by the printer.|
|id|String|The ID of this usage summary.|
|incompleteJobCount|Int64|The number of print jobs that were queued for the printer, but not completed.|
|mediaSheetCount|Int64|The estimated number of media sheets printed based on reporting by the printer.|
|pageCount|Int64|The estimated number of pages printed based on reporting by the printer.|
|printerId|String|The ID of the printer represented by these statistics.|
|printerName|String|The name of the printer represented by these statistics.|
|singleSidedSheetCount|Int64|The estimated number of single-sided media sheets printed based on reporting by the printer.|
|usageDate|Date|The date associated with these statistics.|
### [printUsageByUser ](https://docs.microsoft.com/graph/api/resources/printusagebyuser?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:-------------|:------------|:------------|
|blackAndWhitePageCount|Int64|The estimated number of black and white pages printed on behalf of the user based on reporting by the printer.|
|colorPageCount|Int64|The estimated number of color pages printed on behalf of the user based on reporting by the printer.|
|completedBlackAndWhiteJobCount|Int64|The number of black and white print jobs completed on behalf of the user.|
|completedColorJobCount|Int64|The number of color print jobs completed on behalf of the user.|
|completedJobCount|Int64|The number of print jobs that were completed on behalf of the user.|
|doubleSidedSheetCount|Int64|The estimated number of double-sided media sheets printed on behalf of the user based on reporting by the printer.|
|id|String|The ID of this usage summary.|
|incompleteJobCount|Int64|The number of print jobs that were queued on behalf of the user, but not completed.|
|mediaSheetCount|Int64|The estimated number of media sheets printed on behalf of the user based on reporting by the printer.|
|pageCount|Int64|The estimated number of pages printed on behalf of the user based on reporting by the printer.|
|singleSidedSheetCount|Int64|The estimated number of single-sided media sheets printed on behalf of the user based on reporting by the printer.|
|usageDate|Date|The date associated with these statistics.|
|userPrincipalName|String|The UPN of the user represented by these statistics.|
### [relyingPartyDetailedSummary ](https://docs.microsoft.com/graph/api/resources/relyingpartydetailedsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|failedSignInCount|Int64|Number of failed sign ins on AD FS in the period specified.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|id|String|Unique identifier for the report. Inherited from entity.|
|migrationStatus|migrationStatus|Indicates whether the app can be easily moved to Entra ID. The possible values are: `ready`, `needsReview`, `additionalStepsRequired`, `unknownFutureValue`.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|migrationValidationDetails|keyValuePair collection|Specifies all the validations checks done on applications config details.|
|relyingPartyId|String|Identifies the relying party to this federation service. It's used when issuing claims to the relying party.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|relyingPartyName|String|Name of the relying party's website or other entity on the Internet that uses an identity provider to authenticate a user who wants to log in.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|replyUrls|String collection|Specifies where the relying party expects to receive the token.|
|serviceId|String|Uniquely identifies the Active Directory forest.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|signInSuccessRate|Double|Calculated as `Number of successful / (Number of successful + Number of failed sign ins)` or `successfulSignInCount / totalSignInCount` on AD FS in the period specified.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|successfulSignInCount|Int64|Number of successful sign ins on AD FS.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|totalSignInCount|Int64|Number of successful + failed sign ins on AD FS in the period specified.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
|uniqueUserCount|Int64|Number of unique users that signed into the application.<br/><br/> Supports `$orderby`, `$filter` (`eq`).|
### [serviceActivityValueMetric ](https://docs.microsoft.com/graph/api/resources/serviceactivityvaluemetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|intervalStartDateTime|DateTimeOffset|The starting date and time (UTC) of the interval.|
|value|Int64|The aggregated value over the given aggregation interval starting from the `intervalStartDateTime`. The value is caculated at the minute level. The value at the starting minute of the `intervalStartDateTime` is included. The value at the last minute of the given interval is excluded. For example, if `intervalStartDateTime` is `2023-09-20T18:00:00Z` and aggregation interval is `5` minutes, then the value is aggregated from `2023-09-20T18:00:00Z`(inclusive) to `2023-09-20T18:05:00Z`(exclusive).|
### [userCredentialUsageDetails ](https://docs.microsoft.com/graph/api/resources/usercredentialusagedetails?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| authMethod | usageAuthMethod | Represents the authentication method that the user used. Possible values are:`email`, `mobileSMS`, `mobileCall`, `officePhone`, `securityQuestion` (only used for self-service password reset), `appNotification`, `appCode`, `alternateMobileCall` (supported only in registration), `fido`, `appPassword`,`unknownFutureValue` |
| eventDateTime | DateTimeOffset | The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| failureReason | String | Provides the failure reason for the corresponding reset or registration workflow. |
| feature | featureType | Possible values are: `registration`, `reset`, `unknownFutureValue`. |
| id | String | Read-only. The unique identifier for the activity. Read-only.|
| isSuccess | Boolean | Indicates success or failure of the workflow. |
| userDisplayName | String | User name of the user performing the reset or registration workflow. |
| userPrincipalName | String | User principal name of the user performing the reset or registration workflow. |
### [userRegistrationDetails ](https://docs.microsoft.com/graph/api/resources/userregistrationdetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|User object identifier in Microsoft Entra ID. Inherited from entity.|
|isAdmin|Boolean|Indicates whether the user has an admin role in the tenant. This value can be used to check the authentication methods that privileged accounts are registered for and capable of.|
|isMfaCapable|Boolean|Indicates whether the user has registered a strong authentication method for multifactor authentication. The method must be allowed by the authentication methods policy. Supports `$filter` (`eq`).|
|isMfaRegistered|Boolean|Indicates whether the user has registered a strong authentication method for multifactor authentication. The method may not necessarily be allowed by the authentication methods policy. Supports `$filter` (`eq`).|
|isPasswordlessCapable|Boolean|Indicates whether the user has registered a passwordless strong authentication method (including FIDO2, Windows Hello for Business, and Microsoft Authenticator (Passwordless)) that is allowed by the authentication methods policy. Supports `$filter` (`eq`).|
|isSsprCapable|Boolean|Indicates whether the user has registered the required number of authentication methods for self-service password reset and the user is allowed to perform self-service password reset by policy. Supports `$filter` (`eq`).|
|isSsprEnabled|Boolean|Indicates whether the user is allowed to perform self-service password reset by policy. The user may not necessarily have registered the required number of authentication methods for self-service password reset. Supports `$filter` (`eq`).|
|isSsprRegistered|Boolean|Indicates whether the user has registered the required number of authentication methods for self-service password reset. The user may not necessarily be allowed to perform self-service password reset by policy. Supports `$filter` (`eq`).|
|isSystemPreferredAuthenticationMethodEnabled|Boolean|Indicates whether system preferred authentication method is enabled. If enabled, the system dynamically determines the most secure authentication method among the methods registered by the user. Supports `$filter` (`eq`).|
|lastUpdatedDateTime|DateTimeOffset|The date and time (UTC) when the report was last updated. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|methodsRegistered|String collection|Collection of authentication methods registered, such as `mobilePhone`, `email`, `passKeyDeviceBound`. Supports `$filter` (`any` with `eq`).|
|systemPreferredAuthenticationMethods|String collection| Collection of authentication methods that the system determined to be the most secure authentication methods among the registered methods for second factor authentication. Possible values are: `push`, `oath`, `voiceMobile`, `voiceAlternateMobile`, `voiceOffice`, `sms`, `none`, `unknownFutureValue`. Supports `$filter` (`any` with `eq`).|
|userDisplayName|String| The user display name, such as `Adele Vance`. Supports `$filter` (`eq`, `startsWith`) and `$orderby`.|
|userPreferredMethodForSecondaryAuthentication|userDefaultAuthenticationMethod|The method the user selected as the default second-factor for performing multifactor authentication. Possible values are: `push`, `oath`, `voiceMobile`, `voiceAlternateMobile`, `voiceOffice`, `sms`, `none`, `unknownFutureValue`. This property is used as preferred MFA method when **isSystemPreferredAuthenticationMethodEnabled** is `false`. Supports `$filter` (`any` with `eq`).|
|userPrincipalName|String|The user principal name, such as `AdeleV@contoso.com`. Supports `$filter` (`eq`, `startsWith`) and `$orderby`.|
|userType|signInUserType|Identifies whether the user is a member or guest in the tenant. The possible values are: `member`, `guest`, `unknownFutureValue`.|
