# NetworkAccess.Read.All

> Allows the app to read all network access information on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /networkAccess/connectivity/branches](https://docs.microsoft.com/graph/api/networkaccess-connectivity-list-branches?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/connectivity/branches/{branchSiteId}](https://docs.microsoft.com/graph/api/networkaccess-branchsite-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/connectivity/branches/{branchSiteId}/deviceLinks](https://docs.microsoft.com/graph/api/networkaccess-branchsite-list-devicelinks?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/connectivity/branches/{branchSiteId}/deviceLinks/{deviceLinkId}](https://docs.microsoft.com/graph/api/networkaccess-devicelink-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/connectivity/remoteNetworks/{remoteNetworkId}/deviceLinks/{deviceLinkId}](https://docs.microsoft.com/graph/api/networkaccess-devicelink-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/forwardingPolicies](https://docs.microsoft.com/graph/api/networkaccess-networkaccessroot-list-forwardingpolicies?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/forwardingPolicies/{forwardingPolicyId}](https://docs.microsoft.com/graph/api/networkaccess-forwardingpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkaccess/forwardingPolicies/{forwardingPolicyId}/policyRules/](https://docs.microsoft.com/graph/api/networkaccess-policy-list-policyrules?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkaccess/forwardingPolicies/{forwardingPolicyId}/policyRules/{ruleId}](https://docs.microsoft.com/graph/api/networkaccess-policyrule-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/forwardingProfiles/](https://docs.microsoft.com/graph/api/networkaccess-networkaccessroot-list-forwardingprofiles?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/forwardingProfiles/{forwardingProfileId}](https://docs.microsoft.com/graph/api/networkaccess-forwardingprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/forwardingProfiles/{forwardingProfileId}/policies/{forwardingPolicyId}](https://docs.microsoft.com/graph/api/networkaccess-forwardingpolicylink-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/settings/conditionalAccess](https://docs.microsoft.com/graph/api/networkaccess-conditionalaccesssettings-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkAccess/settings/crossTenantAccess](https://docs.microsoft.com/graph/api/networkaccess-crosstenantaccesssettings-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /networkaccess/settings/enrichedAuditLogs](https://docs.microsoft.com/graph/api/networkaccess-settings-list-enrichedauditlogs?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|2f7013e0-ab4e-447f-a5e1-5d419950692d|
|**Consent Type**|Admin|
|**Display String**|Read all network access information|
|**Description**|Allows the app to read all network access information on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|e30060de-caa5-4331-99d3-6ac6c966a9a4|
|**Display String**|Read all network access information|
|**Description**|Allows the app to read all network access information and configuration settings without a signed-in user.|
## Resources
### [networkaccess-branchsite](https://docs.microsoft.com/graph/api/resources/networkaccess-branchsite?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|bandwidthCapacity|Int64|Determines the maximum allowed Mbps (megabits per second) bandwidth from a branch site. The possible values are:`250`,`500`,`750`,`1000`.|
|connectivityState|microsoft.graph.networkaccess.connectivityState|Determines the branch site status. The possible values are: `pending`, `connected`, `inactive`, `error`.|
|id|String|Identifier for the branch. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|last modified time.|
|name|String|Name.|
|region|microsoft.graph.networkaccess.region|Specify the region closest to your remote network. The possible value are: `eastUS`, `eastUS2`, `westUS`, `westUS2`, `westUS3`, `centralUS`, `northCentralUS`, `southCentralUS`, `northEurope`, `westEurope`, `franceCentral`, `germanyWestCentral`, `switzerlandNorth`, `ukSouth`, `canadaEast`, `canadaCentral`, `southAfricaWest`, `southAfricaNorth`, `uaeNorth`, `australiaEast`, `westCentralUS`, `centralIndia`, `southEastAsia`, `swedenCentral`, `southIndia`, `australiaSouthEast`, `koreaCentral`, `koreaSouth`, `polandCentral`, `brazilSouth`, `japanEast`, `japanWest`, `koreaSouth`, `italyNorth`, `franceSouth`, `israelCentral`, `unknownFutureValue`.|
|version|String|The branch version.|
|country (deprecated)|String|The branch site is created in the specified country. **D
### [conditionalAccessSettings ](https://docs.microsoft.com/graph/api/resources/networkaccess-conditionalaccesssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|signalingStatus|microsoft.graph.networkaccess.status|When SignalingStatus is enabled, the Conditional Access policy includes zero trust network access information. The possible values are: `enabled`, `disabled`.|
### [crossTenantAccessSettings ](https://docs.microsoft.com/graph/api/resources/networkaccess-crosstenantaccesssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|networkPacketTaggingStatus|microsoft.graph.networkaccess.status|Determines if a header with the user tenant ID is inserted into the network traffic.    .The possible values are: `enabled`, `disabled`.|
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
### [enrichedAuditLogs ](https://docs.microsoft.com/graph/api/resources/networkaccess-enrichedauditlogs?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|exchange|microsoft.graph.networkaccess.enrichedAuditLogsSettings|Exchange Online enriched audit logs settings.|
|id|String|Id Inherited from microsoft.graph.entity.|
|sharepoint|microsoft.graph.networkaccess.enrichedAuditLogsSettings|SharePoint Online enriched audit logs settings.|
|teams|microsoft.graph.networkaccess.enrichedAuditLogsSettings|Teams enriched audit logs settings.|
### [forwardingPolicy ](https://docs.microsoft.com/graph/api/resources/networkaccess-forwardingpolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|description|String|Forwarding policy description. Inherited from microsoft.graph.networkaccess.policy.|
|id|String|Identifier for the forwarding policy. Inherited from microsoft.graph.entity.|
|name|String|Forwarding policy name. Inherited from microsoft.graph.networkaccess.policy.|
|trafficForwardingType|microsoft.graph.networkaccess.trafficForwardingType|Traffic type for forwarding policy. The possible values are: `m365`, `internet`, `private`.|
|version|String|Forwarding policy version. Inherited from microsoft.graph.networkaccess.policy.|
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
### [forwardingRule ](https://docs.microsoft.com/graph/api/resources/networkaccess-forwardingrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.networkaccess.forwardingRuleAction|The action to apply to traffic. The possible values are: `bypass`, `forward`, `unknownFutureValue`.|
|destinations|microsoft.graph.networkaccess.ruleDestination collection|Destinations maintain a list of potential destinations and destination types that the user may access within the context of a network filtering policy. This includes IP addresses and fully qualified domain names (FQDNs)/URLs.|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|name|String|Name. Inherited from microsoft.graph.networkaccess.policyRule.|
|ruleType|microsoft.graph.networkaccess.networkDestinationType|The network destination type used by a URL filtering policy is defined, which can include types such as IP (Internet Protocol) or FQDN (Fully Qualified Domain Name). The possible values are: `url`, `fqdn`, `ipAddress`, `ipRange`, `ipSubnet`.|
### [m365ForwardingRule ](https://docs.microsoft.com/graph/api/resources/networkaccess-m365forwardingrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.networkaccess.forwardingRuleAction|The action applies to traffic. The possible values are: `bypass`, `forward`.|
|category|microsoft.graph.networkaccess.forwardingCategory|Defines the category of Office 365 traffic used by a forwarding rule for Microsoft 365 traffic (for example, optimized traffic). The possible values are: `default`, `optimized`, `allow`.|
|destinations|microsoft.graph.networkaccess.ruleDestination collection|destinations à Maintains the list of potential destinations and destination types that the user could be accessing in the context of a forwarding policy, including IPs and FQDNs/URLs     Inherited from microsoft.graph.networkaccess.forwardingRule.|
|ID|String|Identifier. Inherited from microsoft.graph.entity.|
|name|String|Name. Inherited from microsoft.graph.networkaccess.policyRule.|
|ports|String collection|The port(s) used by a forwarding rule for Microsoft 365 traffic are specified to determine the specific network port(s) through which the Microsoft 365 traffic is directed and forwarded.|
|protocol|microsoft.graph.networkaccess.networkingProtocol|Defines the networking protocol type used by a forwarding rule for Microsoft 365 traffic. The possible values are: `ip`, `icmp`, `igmp`, `ggp`, `ipv4`, `tcp`, `pup`, `udp`, `idp`, `ipv6`, `ipv6RoutingHeader`, `ipv6FragmentHeader`, `ipSecEncapsulatingSecurityPayload`, `ipSecAuthenticationHeader`, `icmpV6`, `ipv6NoNextHeader`, `ipv6DestinationOptions`, `nd`, `raw`, `ipx`, `spx`, `spxII`|
|ruleType|microsoft.graph.networkaccess.networkDestinationType|Destination Type. Inherited from microsoft.graph.networkaccess.forwardingRule. The possible values are: `url`, `fqdn`, `ipAddress`, `ipRange`, `ipSubnet`, `webCategory`.|
### [policyRule ](https://docs.microsoft.com/graph/api/resources/networkaccess-policyrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the rule. Inherited from microsoft.graph.entity.|
|name|String|Name.|
### [privateAccessForwardingRule ](https://docs.microsoft.com/graph/api/resources/networkaccess-privateaccessforwardingrule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.networkaccess.forwardingRuleAction|The action applies to traffic. The possible values are: `bypass`, `forward`.|
|destinations|microsoft.graph.networkaccess.ruleDestination collection|maintains the list of potential destinations and destination types that the user could be accessing in the context of a forwarding policy, including IPs and FQDNs/URLs Inherited from microsoft.graph.networkaccess.forwardingRule.|
|id|String|Identifier. Inherited from microsoft.graph.entity.|
|name|String|Name. Inherited from microsoft.graph.networkaccess.policyRule.|
|ruleType|microsoft.graph.networkaccess.networkDestinationType|Destination Type. Inherited from microsoft.graph.networkaccess.forwardingRule. The possible values are: `url`, `fqdn`, `ipAddress`, `ipRange`, `ipSubnet`|
### [remoteNetwork ](https://docs.microsoft.com/graph/api/resources/networkaccess-remotenetwork?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Identifier for the remote network. Inherited from microsoft.graph.entity.|
|lastModifiedDateTime|DateTimeOffset|last modified time.|
|name|String|Name.|
|region|microsoft.graph.networkaccess.region|Specify the region closest to your remote network. The possible value are: `eastUS`, `eastUS2`, `westUS`, `westUS2`, `westUS3`, `centralUS`, `northCentralUS`, `southCentralUS`, `northEurope`, `westEurope`, `franceCentral`, `germanyWestCentral`, `switzerlandNorth`, `ukSouth`, `canadaEast`, `canadaCentral`, `southAfricaWest`, `southAfricaNorth`, `uaeNorth`, `australiaEast`, `westCentralUS`, `centralIndia`, `southEastAsia`, `swedenCentral`, `southIndia`, `australiaSouthEast`, `koreaCentral`, `koreaSouth`, `polandCentral`, `brazilSouth`, `japanEast`, `japanWest`, `koreaSouth`, `italyNorth`, `franceSouth`, `israelCentral`, `unknownFutureValue`.|
|version|String|Remote network version.|
