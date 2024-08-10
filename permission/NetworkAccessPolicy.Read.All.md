# NetworkAccessPolicy.Read.All

> Allows the app to read your organization's security and routing network access policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /filteringProfiles/{filteringProfileId}/policies](https://docs.microsoft.com/graph/api/networkaccess-filteringpolicylink-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/connectivity/branches/{branchSiteId}/connectivityConfiguration](https://docs.microsoft.com/graph/api/networkaccess-branchconnectivityconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/connectivity/branches/{branchSiteId}/forwardingProfiles](https://docs.microsoft.com/graph/api/networkaccess-branchsite-list-forwardingprofiles?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/filteringPolicies](https://docs.microsoft.com/graph/api/networkaccess-networkaccessroot-list-filteringpolicies?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkaccess/filteringPolicies/{filteringPoliciesId}](https://docs.microsoft.com/graph/api/networkaccess-filteringpolicylink-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkaccess/filteringPolicies/{filteringPoliciesId}/policyRules/{policyRulesId}](https://docs.microsoft.com/graph/api/networkaccess-filteringrule-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/filteringPolicies/{filteringPolicyId}](https://docs.microsoft.com/graph/api/networkaccess-filteringpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkaccess/filteringPolicies/{filteringPolicyId}?$expand=policyRules](https://docs.microsoft.com/graph/api/networkaccess-filteringrule-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/filteringProfiles](https://docs.microsoft.com/graph/api/networkaccess-filteringprofile-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/filteringProfiles/{filteringProfileId}](https://docs.microsoft.com/graph/api/networkaccess-filteringprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/filteringProfiles/{filteringProfileId}/policies/{policyLinkId}/policy](https://docs.microsoft.com/graph/api/networkaccess-policylink-list-policy?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/forwardingProfiles/{forwardingProfileId}/policies/ ](https://docs.microsoft.com/graph/api/networkaccess-forwardingprofile-list-policies?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/reports/entitiesSummaries(startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-entitiessummaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/reports/getCrossTenantSummary(startDateTime={startDateTime},endDateTime={endDateTime},discoveryPivotDateTime={discoveryPivotDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-getcrosstenantsummary?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/reports/getDestinationSummaries(startDateTime={startDateTime},endDateTime={endDateTime},aggregatedBy={aggregatedBy})](https://docs.microsoft.com/graph/api/networkaccess-reports-getdestinationsummaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/reports/getDeviceUsageSummary(startDateTime={startDateTime},endDateTime={endDateTime},activityPivotDateTime={activityPivotDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-getdeviceusagesummary?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/reports/transactionSummaries(startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-transactionsummaries?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/settings/forwardingOptions](https://docs.microsoft.com/graph/api/networkaccess-forwardingoptions-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccess/tenantStatus](https://docs.microsoft.com/graph/api/networkaccess-tenantstatus-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccessRoot/reports/crossTenantAccessReport(startDateTime={startDateTime}, endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-crosstenantaccessreport?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccessRoot/reports/destinationReport(startDateTime={startDateTime}, endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-destinationreport?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccessRoot/reports/deviceReport(startDateTime={startDateTime}, endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-devicereport?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccessRoot/reports/userReport(startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-userreport?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /networkAccessRoot/reports/webCategoryReport(startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/networkaccess-reports-webcategoryreport?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|ba22922b-752c-446f-89d7-a2d92398fceb|
|**Consent Type**|User|
|**Display String**|Read security and routing policies for network access|
|**Description**|Allows the app to read your organization's security and routing network access policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|8a3d36bf-cb46-4bcc-bec9-8d92829dab84|
|**Display String**|Read all security and routing policies for network access|
|**Description**|Allows the app to read your organization's network access policies, without a signed-in user.|
## Resources
### [networkaccess-branchconnectivityconfiguration](https://docs.microsoft.com/graph/api/resources/networkaccess-branchconnectivityconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|branchId|String|Unique identifier or a specific reference assigned to a branchSite. Key.|
|branchName|String|Display name assigned to a branchSite.|
|links|microsoft.graph.networkaccess.connectivityConfigurationLink collection|List of connectivity configurations for deviceLink objects.|
### [conditionalAccessSettings ](https://docs.microsoft.com/graph/api/resources/networkaccess-conditionalaccesssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|signalingStatus|microsoft.graph.networkaccess.status|When SignalingStatus is enabled, the Conditional Access policy includes zero trust network access information. The possible values are: `enabled`, `disabled`.|
### [crossTenantAccess ](https://docs.microsoft.com/graph/api/resources/networkaccess-crosstenantaccess?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceCount|Int64|The number of devices that accessed the external tenant.|
|lastAccessDateTime|DateTimeOffset|The timestamp of the most recent access to the external tenant.|
|resourceTenantId|String|The tenant ID of the external tenant.|
|resourceTenantName|String| The name of the external tenant.|
|resourceTenantPrimaryDomain|String|The domain of the external tenant.|
|usageStatus|microsoft.graph.networkaccess.usageStatus|The usage status of cross-tenant access. The possible values are `frequentlyUsed`, `rarelyUsed`, and `unknownFutureValue`.|
|userCount|Int64|The number of users that accessed the external tenant.|
### [crossTenantSummary ](https://docs.microsoft.com/graph/api/resources/networkaccess-crosstenantsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authTransactionCount|Int32|The total number of authentication sessions between startDateTime and endDateTime.	|
|deviceCount|Int32|The number of unique devices that performed cross-tenant access.	|
|newTenantCount|Int32|The number of unique tenants that were accessed between endDateTime and discoveryPivotDateTime, but weren't accessed between discoveryPivotDateTime and startDateTime.|
|rarelyUsedTenantCount|Int32|The number of tenants that are rarely used.|
|tenantCount|Int32|The number of unique tenants that were accessed, not including the device's tenant.|
|userCount|Int32|The number of unique users that performed cross-tenant access.|
### [destination ](https://docs.microsoft.com/graph/api/resources/networkaccess-destination?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceCount|Int32|The number of unique devices that were seen.|
|fqdn|String|The fully qualified domain name (FQDN) of the destination.|
|ip|String|The internet protocol (IP) used to access the destination.|
|lastAccessDateTime|DateTimeOffset|The most recent access DateTime.|
|networkingProtocol|microsoft.graph.networkaccess.networkingProtocol|The set of communication rules and conventions that govern data transmission between devices in a network. The possible values are: `ip`, `icmp`, `igmp`, `ggp`, `ipv4`, `tcp`, `pup`, `udp`, `idp`, `ipv6`, `ipv6RoutingHeader`, `ipv6FragmentHeader`, `ipSecEncapsulatingSecurityPayload`, `ipSecAuthenticationHeader`, `icmpV6`, `ipv6NoNextHeader`, `ipv6DestinationOptions`, `nd`, `raw`, `ipx`, `spx`, and `spxII`.|
|port|Int32|The numeric identifier that is associated with a specific endpoint in a network.|
|trafficType|microsoft.graph.networkaccess.trafficType|The traffic classification. The possible values are `internet`, `private`, `microsoft365`, and `all`.|
|transactionCount|Int32|The number of transactions.|
|userCount|Int32|The number of unique Microsoft Entra ID users that were seen.|
### [destinationSummary ](https://docs.microsoft.com/graph/api/resources/networkaccess-destinationsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|count|Int32|The number of the destinationSummary objects, aggregated by Global Secure Access service.|
|destination|String|The IP address or FQDN of the destination.|
|trafficType|microsoft.graph.networkaccess.trafficType|The traffic classification. The allowed values are `internet`, `private`, `microsoft365`, `all`, and `unknownFutureValue`.|
### [device ](https://docs.microsoft.com/graph/api/resources/networkaccess-device?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceId|String|A unique device ID.|
|displayName|String|The display name for the device.|
|isCompliant|Boolean|A value that indicates whether or not the device is compliant.|
|lastAccessDateTime|DateTimeOffset|The most recent access time for the device.|
|operatingSystem|String|The operating system on the device.|
|trafficType|microsoft.graph.networkaccess.trafficType|The traffic classification. The possible values are: `internet`, `private`, `microsoft365`, or `all`.|
### [deviceLink ](https://docs.microsoft.com/graph/api/resources/networkaccess-devicelink?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|bgpConfiguration|microsoft.graph.networkaccess.bgpConfiguration|The border gateway protocol specifies the Border Gateway Protocol (BGP) IP address and ASN for directing traffic from a link to the edge.|
|bandwidthCapacityInMbps|Int64|Determines the maximum allowed Mbps (megabits per second) bandwidth from a device link. The possible values are:`250`,`500`,`750`,`1000`.|
|deviceVendor|microsoft.graph.networkaccess.deviceVendor|Specifies the manufacturer of the deviceLink. The possible values are: `barracudaNetworks`, `checkPoint`, `ciscoMeraki`, `citrix`, `fortinet`, `hpeAruba`, `netFoundry`, `nuage`, `openSystems`, `paloAltoNetworks`, `riverbedTechnology`, `silverPeak`, `vmWareSdWan`, `versa`, `other`.|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|ipAddress|String|The public IP address of your CPE (customer premise equipment) device. |
|lastModifiedDateTime|DateTimeOffset|last modified time.|
|name|String|Name.|
|tunnelConfiguration|microsoft.graph.networkaccess.tunnelConfiguration|The connectivity settings, including the protocol, IPSec policy, and preshared key, are specified for establishing connectivity.|
|version|String|Version.|
### [deviceUsageSummary ](https://docs.microsoft.com/graph/api/resources/networkaccess-deviceusagesummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activeDeviceCount|Int32|The number of distinct device IDs between the discovery pivot time and the end of the reporting period.|
|inactiveDeviceCount|Int32|The discovery pivot time and the end of the reporting period, but were seen between the start of the reporting period and the discovery pivot time.|
|totalDeviceCount|Int32|The total number of distinct device IDs that were seen during the reporting period.|
### [entitiesSummary ](https://docs.microsoft.com/graph/api/resources/networkaccess-entitiessummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceCount|Int64|The number of unique devices that were seen.|
|trafficType|microsoft.graph.networkaccess.trafficType|The traffic classification. The possible values are: `internet`, `private`, `microsoft365`, `all`.|
|userCount|Int64|The number of unique Microsoft Entra ID users that were seen.|
|workloadCount|Int64|The number of unique target workloads/hosts that were seen.|
### [filteringPolicy ](https://docs.microsoft.com/graph/api/resources/networkaccess-filteringpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when the filtering Policy was originally created.|
|description|String|A description of the filtering policy. Inherited from microsoft.graph.networkaccess.policy.|
|id|String|The identifier for the filtering policy. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when a particular profile was last modified or updated.|
|name|String|The display name for the filtering policy. Inherited from microsoft.graph.networkaccess.policy.|
### [filteringPolicyLink ](https://docs.microsoft.com/graph/api/resources/networkaccess-filteringpolicylink?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.networkaccess.filteringPolicyAction|The actions for filtering policies, offering "block" and "allow" options to specify whether to block or allow access based on the policy. The possible values are: `block`, `allow`.|
|createdDateTime|DateTimeOffset|The date and time when the filtering Policy link was created.|
|id|String|Unique identifier. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the policy was most recently modified.|
|loggingState|microsoft.graph.networkaccess.status|A value that tells whether the link is enabled or disabled. Inherited from microsoft.graph.networkaccess.policyLink. The allowed values are `enabled` and `disabled`.|
|priority|Int64|Provides an integer priority level for each instance of a URL filtering policy linked to a profile. Required.|
### [filteringProfile ](https://docs.microsoft.com/graph/api/resources/networkaccess-filteringprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when the filteringProfile was created.|
|description|String|A description of the filtering profile. Inherited from microsoft.graph.networkaccess.profile.|
|id|String|The distinct identifier that is assigned to a specific profile. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when a particular profile was last modified or updated. Inherited from microsoft.graph.networkaccess.profile.|
|name|String|The name of the profile. Inherited from microsoft.graph.networkaccess.profile.|
|priority|Int64|The priority used to order the profile for processing within a list.|
|state|microsoft.graph.networkaccess.status|The profile state. Inherited from microsoft.graph.networkaccess.profile. The possible values are: `enabled`, `disabled`.|
### [filteringRule ](https://docs.microsoft.com/graph/api/resources/networkaccess-filteringrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|destinations|microsoft.graph.networkaccess.ruleDestination collection|Possible destinations and types of destinations accessed by the user in accordance with the network filtering policy, such as IP addresses and FQDNs/URLs.|
|id|String|A unique ID for the rule. Inherited from microsoft.graph.entity.|
|name|String|The display name of the rule. Inherited from microsoft.graph.networkaccess.policyRule.|
|ruleType|microsoft.graph.networkaccess.networkDestinationType|The rule types that specify the basis for filtering. The possible values are `url`, `fqdn`, `ipAddress`, `ipRange`, `ipSubnet`, and `webCategory`.|
### [forwardingPolicyLink ](https://docs.microsoft.com/graph/api/resources/networkaccess-forwardingpolicylink?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier. Inherited from microsoft.graph.entity.|
|state|microsoft.graph.networkaccess.status|Link Status. Inherited from microsoft.graph.networkaccess.policyLink. The possible values are: `enabled`, `disabled`.|
|version|String|Version number. Inherited from microsoft.graph.networkaccess.policyLink.|
### [forwardingProfile ](https://docs.microsoft.com/graph/api/resources/networkaccess-forwardingprofile?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|associations|microsoft.graph.networkaccess.association collection|Specifies the users, groups, devices, and remote networks whose traffic is associated with the given traffic forwarding profile.|
|description|String|Profile description. Inherited from microsoft.graph.networkaccess.profile.|
|id|String|Identifier for the profile. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|Profile last modified time. Inherited from microsoft.graph.networkaccess.profile.|
|name|String|Profile name. Inherited from microsoft.graph.networkaccess.profile.|
|priority|Int32|Profile priority.|
|state|microsoft.graph.networkaccess.status|Determines whether the profile is active or inactive. Inherited from microsoft.graph.networkaccess.profile. The possible values are: `enabled`, `disabled`.|
|trafficForwardingType|microsoft.graph.networkaccess.trafficForwardingType|Profile traffic type. The possible values are: `m365`, `internet`, `private`.|
|version|String|Version.|
### [remoteNetwork ](https://docs.microsoft.com/graph/api/resources/networkaccess-remotenetwork?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the remote network. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|last modified time.|
|name|String|Name.|
|region|microsoft.graph.networkaccess.region|Specify the region closest to your remote network. The possible value are: `eastUS`, `eastUS2`, `westUS`, `westUS2`, `westUS3`, `centralUS`, `northCentralUS`, `southCentralUS`, `northEurope`, `westEurope`, `franceCentral`, `germanyWestCentral`, `switzerlandNorth`, `ukSouth`, `canadaEast`, `canadaCentral`, `southAfricaWest`, `southAfricaNorth`, `uaeNorth`, `australiaEast`, `westCentralUS`, `centralIndia`, `southEastAsia`, `swedenCentral`, `southIndia`, `australiaSouthEast`, `koreaCentral`, `koreaSouth`, `polandCentral`, `brazilSouth`, `japanEast`, `japanWest`, `koreaSouth`, `italyNorth`, `franceSouth`, `israelCentral`, `unknownFutureValue`.|
|version|String|Remote network version.|
### [remoteNetworkConnectivityConfiguration ](https://docs.microsoft.com/graph/api/resources/networkaccess-remotenetworkconnectivityconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|remoteNetworkId|String|Unique identifier or a specific reference assigned to a branchSite. Key.|
|remoteNetworkName|String|Display name assigned to a branchSite.|
### [tenantStatus ](https://docs.microsoft.com/graph/api/resources/networkaccess-tenantstatus?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|onboardingErrorMessage|String|Reflects a message to the user if there's an error.|
|onboardingStatus|microsoft.graph.networkaccess.onboardingStatus|Reflects the tenant onboarding status. The possible values are: `offboarded`, `offboardingInProgress`, `onboardingInProgress`, `onboarded`, `onboardingErrorOccurred`, `offboardingErrorOccurred`.|
### [transactionSummary ](https://docs.microsoft.com/graph/api/resources/networkaccess-transactionsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|blockedCount|Int32|The number of transactions that were blocked.|
|totalCount|Int32|The total number of transactions.|
|trafficType|microsoft.graph.networkaccess.trafficType|The trraffic classification. The possible values are `internet`, `private`, `microsoft365`, and `all`.|
### [networkaccess-user](https://docs.microsoft.com/graph/api/resources/networkaccess-user?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|User display Name.|
|lastAccessDateTime|DateTimeOffset|The date and time of the most recent access.|
|trafficType|microsoft.graph.networkaccess.trafficType|The traffic classification. The possible values are `internet`, `private`, `microsoft365`, and `all`.|
|userId|String|The ID for the user.|
|userPrincipalName|String|A unique identifier that is associated with a user in a system or directory. Typically, this value is an email address that is used for user authentication and identification.|
|userType|microsoft.graph.networkaccess.userType|The user type. The possible values are `member`, `guest`, and `unknownFutureValue`.|
### [webCategoriesSummary ](https://docs.microsoft.com/graph/api/resources/networkaccess-webcategoriessummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|deviceCount|Int32|The number of unique devices that were seen.|
|transactionCount|Int32|The number of transactions that were seen.|
|userCount|Int32|The number of unique Microsoft Entra ID users that were seen.|
|webCategory|microsoft.graph.networkaccess.webCategory|The website category.|
