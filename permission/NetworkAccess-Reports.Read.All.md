# NetworkAccess-Reports.Read.All

> Allows the app to read all network access reports on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /networkAccess/logs/traffic](https://docs.microsoft.com/graph/api/networkaccess-logs-list-traffic?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b0c61509-cfc3-42bd-9bd4-66d81785fee4|
|**Consent Type**|Admin|
|**Display String**|Read all network access reports|
|**Description**|Allows the app to read all network access reports on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|40049381-3cc1-42af-94ec-5ce755db4b0d|
|**Display String**|Read all network access reports|
|**Description**|Allows the app to read all network access reports without a signed-in user.|
## Resources
### [networkAccessTraffic ](https://docs.microsoft.com/graph/api/resources/networkaccess-networkaccesstraffic?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|action|microsoft.graph.networkaccess.filteringPolicyAction|Indicates what action to take based on filtering policies. The possible values are: `block`, `allow`.|
|agentVersion|String|Represents the version of the Global Secure Access client agent software. Supports $filter (`eq`) and `$orderby`.|
|connectionId|String|Represents a unique identifier assigned to a connection. Supports $filter (`eq`) and `$orderby`.|
|createdDateTime|DateTimeOffset|Represents the date and time when a network access traffic log entry was created. Supports $filter (`eq`) and `$orderby`.|
|destinationFQDN|String|Represents the Fully Qualified Domain Name (FQDN) of the destination host or server in a network communication. Supports $filter (`eq`) and `$orderby`.|
|destinationIp|String|Represents the IP address of the destination host or server in a network communication. Supports $filter (`eq`) and `$orderby`.|
|destinationPort|Int32|Represents the network port number on the destination host or server in a network communication. Supports $filter (`eq`) and `$orderby`.|
|deviceCategory|microsoft.graph.networkaccess.deviceCategory|Represents the category classification of a device within a network infrastructure. The possible values are: `client`, `branch`, `unknownFutureValue`. Supports $filter (`eq`) and `$orderby`.|
|deviceId|String|Represents a unique identifier assigned to a device within a network infrastructure. Supports $filter (`eq`) and `$orderby`.|
|deviceOperatingSystem|String|Represents the operating system installed on a device within a network infrastructure. Supports $filter (`eq`) and `$orderby`.|
|deviceOperatingSystemVersion|String|Represents the version or release number of the operating system installed on a device within a network infrastructure. Supports $filter (`eq`) and `$orderby`.|
|headers|microsoft.graph.networkaccess.headers|Represents the headers included in a network request or response. Supports $filter (`eq`) and `$orderby`.|
|networkProtocol|microsoft.graph.networkaccess.networkingProtocol|Represents the networking protocol used for communication.The possible values are: `ip`, `icmp`, `igmp`, `ggp`, `ipv4`, `tcp`, `pup`, `udp`, `idp`, `ipv6`, `ipv6RoutingHeader`, `ipv6FragmentHeader`, `ipSecEncapsulatingSecurityPayload`, `ipSecAuthenticationHeader`, `icmpV6`, `ipv6NoNextHeader`, `ipv6DestinationOptions`, `nd`, `raw`, `ipx`, `spx`, `spxII`, `unknownFutureValue`. Supports $filter (`eq`) and `$orderby`.|
|policyId|String|Represents a unique identifier assigned to a policy. Supports $filter (`eq`) and `$orderby`.|
|policyRuleId|String|Represents a unique identifier assigned to a policy rule. Supports $filter (`eq`) and `$orderby`.|
|receivedBytes|Int64|Represents the total number of bytes received in a network communication or data transfer. Supports $filter (`eq`) and `$orderby`.|
|sentBytes|Int64| Represents the total number of bytes sent in a network communication or data transfer. Supports $filter (`eq`) and `$orderby`.|
|sessionId|String|Represents a unique identifier assigned to a session or connection within a network infrastructure. Supports $filter (`eq`) and `$orderby`.|
|sourceIp|String|Represents the source IP address in a network communication. Supports $filter (`eq`) and `$orderby`.|
|sourcePort|Int32|Represents the network port number on the source host or device in a network communication. Supports $filter (`eq`) and `$orderby`.|
|tenantId|String|Represents a unique identifier assigned to a tenant within a network infrastructure. Supports $filter (`eq`) and `$orderby`.|
|trafficType|microsoft.graph.networkaccess.trafficType|Represents the type or category of network traffic.The possible values are: `internet`, `private`, `microsoft365`, `all`, `unknownFutureValue`. Supports $filter (`eq`) and `$orderby`.|
|transactionId|String|Represents a unique identifier assigned to a specific transaction or operation. Key. Supports $filter (`eq`) and `$orderby`.|
|transportProtocol|microsoft.graph.networkaccess.networkingProtocol|Represents the transport protocol used for communication.The possible values are: `ip`, `icmp`, `igmp`, `ggp`, `ipv4`, `tcp`, `pup`, `udp`, `idp`, `ipv6`, `ipv6RoutingHeader`, `ipv6FragmentHeader`, `ipSecEncapsulatingSecurityPayload`, `ipSecAuthenticationHeader`, `icmpV6`, `ipv6NoNextHeader`, `ipv6DestinationOptions`, `nd`, `raw`, `ipx`, `spx`, `spxII`, `unknownFutureValue`. Supports $filter (`eq`) and `$orderby`.|
|userId|String|Represents a unique identifier assigned to a user. Supports $filter (`eq`) and `$orderby`.|
|userPrincipalName|String|Represents the user principal name (UPN) associated with a user. Supports $filter (`eq`) and `$orderby`.|
