# ThreatHunting.Read.All

> Allows the app to run hunting queries, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[POST /security/runHuntingQuery](https://docs.microsoft.com/graph/api/security-security-runhuntingquery?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b152eca8-ea73-4a48-8c98-1a6742673d99|
|**Consent Type**|Admin|
|**Display String**|Run hunting queries|
|**Description**|Allows the app to run hunting queries, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|dd98c7f5-2d42-42d3-a0e4-633161547251|
|**Display String**|Run hunting queries|
|**Description**|Allows the app to run hunting queries, without a signed-in user.|
## Resources
### [huntingQueryResults ](https://docs.microsoft.com/graph/api/resources/security-huntingqueryresults?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|schema|microsoft.graph.security.singlePropertySchema collection|The schema for the response.|
|results|microsoft.graph.security.huntingRowResult collection|The results of the hunting query.|
