# IndustryData-OutboundFlow.ReadWrite.All

> Allows the app to read and write outbound data flows on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /external/industryData/outboundProvisioningFlowSets/{id}](https://docs.microsoft.com/graph/api/industrydata-industrydataroot-delete-outboundprovisioningflowsets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[DELETE /external/industryData/OutboundProvisioningFlowSets/{id}/provisioningFlows/{id}](https://docs.microsoft.com/graph/api/industrydata-classgroupprovisioningflow-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/outboundProvisioningFlowSets](https://docs.microsoft.com/graph/api/industrydata-industrydataroot-list-outboundprovisioningflowsets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/outboundProvisioningFlowSets/{id}](https://docs.microsoft.com/graph/api/industrydata-outboundprovisioningflowset-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/outboundProvisioningFlowSets/{id}/provisioningFlows](https://docs.microsoft.com/graph/api/industrydata-outboundprovisioningflowset-list-provisioningflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /external/industryData/OutboundProvisioningFlowSets/{id}/provisioningFlows/{id}](https://docs.microsoft.com/graph/api/industrydata-classgroupprovisioningflow-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/outboundProvisioningFlowSets/{id}](https://docs.microsoft.com/graph/api/industrydata-outboundprovisioningflowset-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /external/industryData/OutboundProvisioningFlowSets/{id}/provisioningFlows/{id}](https://docs.microsoft.com/graph/api/industrydata-classgroupprovisioningflow-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/OutboundProvisioningFlowSets](https://docs.microsoft.com/graph/api/industrydata-industrydataroot-post-outboundprovisioningflowsets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/outboundProvisioningFlowSets/{id}/provisioningFlows](https://docs.microsoft.com/graph/api/industrydata-outboundprovisioningflowset-post-provisioningflows?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /external/industryData/outboundProvisioningFlowSets/{outboundProvisioningFlowSetId}/provisioningFlows/{provisioningFlowId}/reset](https://docs.microsoft.com/graph/api/industrydata-provisioningflow-reset?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|aeb68e0b-e562-4a1f-b6dd-3484ad0cbb4b|
|**Consent Type**|Admin|
|**Display String**|Manage outbound flow definitions|
|**Description**|Allows the app to read and write outbound data flows on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|24a65b4a-e501-47e2-8849-d679517887f0|
|**Display String**|Manage outbound flow definitions|
|**Description**|Allows the app to read and write outbound data flows without a signed-in user.|
## Resources
### [administrativeUnitProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-administrativeunitprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                           | Description                                                                                                                                                                                                         |
| :------------------- | :------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| createdDateTime      | DateTimeOffset                                                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| creationOptions      | microsoft.graph.industryData.adminUnitCreationOptions | The different attribute choices for the administrative units to be provisioned.                                                                                                                                      |
| id                   | String                                                                                                         | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                                   | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [adminUnitCreationOptions ](https://docs.microsoft.com/graph/api/resources/industrydata-adminunitcreationoptions?view=graph-rest-1.0&tabs=http)
| Property                      | Type    | Description                                                                                 |
| :---------------------------- | :------ | :------------------------------------------------------------------------------------------ |
| createBasedOnOrg              | Boolean | Indicates whether the administrative unit should be created based on the org.                |
| createBasedOnOrgPlusRoleGroup | Boolean | Indicates whether the administrative unit should be created based on the org and role group. |
### [classGroupConfiguration ](https://docs.microsoft.com/graph/api/resources/industrydata-classgroupconfiguration?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                                 | Description                                                                  |
| :------------------- | :------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------- |
| additionalAttributes | microsoft.graph.industryData.additionalClassGroupAttributes collection                                               | The different attributes to sync for the class groups. The possible values are: `courseTitle`, `courseCode`, `courseSubject`, `courseGradeLevel`, `courseExternalId`, `academicSessionTitle`, `academicSessionExternalId`, `classCode`, `unknownFutureValue`. |
| additionalOptions    | microsoft.graph.industryData.additionalClassGroupOptions | The different options for the class groups to be provisioned with.            |
| enrollmentMappings   | microsoft.graph.industryData.enrollmentMappings                   | The different enrollmentMappings for the class groups to be provisioned with. |
### [classGroupProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-classgroupprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                         | Description                                                                                                                                                                                                         |
| :------------------- | :----------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| configuration        | microsoft.graph.industryData.classGroupConfiguration | The different attribute choices for the class groups to be provisioned.                                                                                                                                              |
| createdDateTime      | DateTimeOffset                                                                                               | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| id                   | String                                                                                                       | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                               | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [filter ](https://docs.microsoft.com/graph/api/resources/industrydata-filter?view=graph-rest-1.0&tabs=http)

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
### [securityGroupCreationOptions ](https://docs.microsoft.com/graph/api/resources/industrydata-securitygroupcreationoptions?view=graph-rest-1.0&tabs=http)
| Property                      | Type    | Description                                                                                               |
| :---------------------------- | :------ | :-------------------------------------------------------------------------------------------------------- |
| createBasedOnOrgPlusRoleGroup | Boolean | Indicates whether the security group should be created based on the org and role group. |
| createBasedOnRoleGroup        | Boolean | A Boolean choice indicating whether the security group should be created based on the role group          |
### [securityGroupProvisioningFlow ](https://docs.microsoft.com/graph/api/resources/industrydata-securitygroupprovisioningflow?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                                   | Description                                                                                                                                                                                                         |
| :------------------- | :--------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| createdDateTime      | DateTimeOffset                                                                                                         | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| creationOptions      | microsoft.graph.industryData.securityGroupCreationOptions | The different attribute choices for the class groups to be provisioned.                                                                                                                                              |
| id                   | String                                                                                                                 | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| lastModifiedDateTime | DateTimeOffset                                                                                                         | Inherited from microsoft.graph.industryData.provisioningFlow.                                                                                                      |
| readinessStatus      | microsoft.graph.industryData.readinessStatus                                                                           | Inherited from microsoft.graph.industryData.provisioningFlow. The possible values are: `notReady`, `ready`, `failed`, `disabled`, `expired`, `unknownFutureValue`. |
### [userCreationOptions ](https://docs.microsoft.com/graph/api/resources/industrydata-usercreationoptions?view=graph-rest-1.0&tabs=http)
| Property       | Type                                                                                                        | Description                                                      |
| :------------- | :---------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------- |
| configurations | microsoft.graph.industryData.userConfiguration collection | The different management choices for the users to be provisioned. |
### [userManagementOptions ](https://docs.microsoft.com/graph/api/resources/industrydata-usermanagementoptions?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                                                     | Description                                                      |
| :------------------- | :------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------- |
| additionalAttributes | microsoft.graph.industryData.additionalUserAttributes collection                                         | The different attribute choices for the users to be provisioned. The possible values are: `userGradeLevel`, `userNumber`, `unknownFutureValue`. |
| additionalOptions    | microsoft.graph.industryData.additionalUserOptions | The different management choices for the users to be provisioned. |
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
