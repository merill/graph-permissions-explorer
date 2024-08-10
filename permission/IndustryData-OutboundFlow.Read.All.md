# IndustryData-OutboundFlow.Read.All

> Allows the app to read outbound data flows on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /external/industryData/outboundProvisioningFlowSets](https://docs.microsoft.com/graph/api/industrydata-industrydataroot-list-outboundprovisioningflowsets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/outboundProvisioningFlowSets/{id}](https://docs.microsoft.com/graph/api/industrydata-outboundprovisioningflowset-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/outboundProvisioningFlowSets/{id}/provisioningFlows](https://docs.microsoft.com/graph/api/industrydata-outboundprovisioningflowset-list-provisioningflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/OutboundProvisioningFlowSets/{id}/provisioningFlows/{id}](https://docs.microsoft.com/graph/api/industrydata-classgroupprovisioningflow-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|4741a003-8952-4be4-9217-33a0ac327122|
|**Consent Type**|Admin|
|**Display String**|View outbound flow definitions|
|**Description**|Allows the app to read outbound data flows on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|61d0354c-5d88-483c-b974-a37ec3395a2c|
|**Display String**|View outbound flow definitions|
|**Description**|Allows the app to read outbound data flows without a signed-in user.|
## Resources
### [administrativeUnitProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-administrativeunitprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                           | Description                                                                                                                                                                                                         |
| :------------------- | :------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| createdDateTime      | DateTimeOffset                                                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| creationOptions      | microsoft.graph.industryData.adminUnitCreationOptions | The different attribute choices for the administrative units to be provisioned.                                                                                                                                      |
| id                   | String                                                                                                         | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                                   | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [classGroupProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-classgroupprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                         | Description                                                                                                                                                                                                         |
| :------------------- | :----------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| configuration        | microsoft.graph.industryData.classGroupConfiguration | The different attribute choices for the class groups to be provisioned.                                                                                                                                              |
| createdDateTime      | DateTimeOffset                                                                                               | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| id                   | String                                                                                                       | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                               | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [outboundProvisioningFlowSet ](https://docs.microsoft.com/graph/api/resources/industrydata-outboundprovisioningflowset?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                       | Description                                                                                                                                                                                                                                |
| :------------------- | :------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| createdDateTime      | DateTimeOffset                                                             | The date and time when the flowSet was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.               |
| displayName          | String                                                                     | The display name of the flowSet provided by the caller.                                                                                                                                                                                     |
| filter               | microsoft.graph.industryData.filter | The collection of provisioning filters applicable to all the flows under the given flowSet.                                                                                                                                                 |
| id                   | String                                                                     | The unique identifier for the flowSet. Inherited from entity.                                                                                                                                                    |
| lastModifiedDateTime | DateTimeOffset                                                             | The date and time when the flowSet was most recently changed. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
### [provisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-provisioningflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:-------|:---|:----------|
|createdDateTime|DateTimeOffset|The date and time when the provisioning flow was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String|The unique identifier for the provisioning flow. Inherited from entity.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the provisioning flow was most recently changed. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|readinessStatus|microsoft.graph.industryData.readinessStatus|The state of the activity from creation through to ready to do work. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`.|
### [securityGroupProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-securitygroupprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                                   | Description                                                                                                                                                                                                         |
| :------------------- | :--------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| createdDateTime      | DateTimeOffset                                                                                                         | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| creationOptions      | microsoft.graph.industryData.securityGroupCreationOptions | The different attribute choices for the class groups to be provisioned.                                                                                                                                              |
| id                   | String                                                                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                                         | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                                           | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [userProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-userprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                     | Description                                                                                                                                                                                                         |
| :------------------- | :------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| createdDateTime      | DateTimeOffset                                                                                           | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| createUnmatchedUsers | Boolean                                                                                                  | A Boolean choice indicating whether unmatched users should be created or ignored.                                                                                                                                    |
| creationOptions      | microsoft.graph.industryData.userCreationOptions     | The different management choices for the new users to be provisioned.                                                                                                                                                |
| id                   | String                                                                                                   | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                           | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| managementOptions    | microsoft.graph.industryData.userManagementOptions | The different attribute choices for all the users to be considered.                                                                                                                                                  |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                             | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
