# AttackSimulation.Read.All

> Allows the app to read attack simulation and training data for an organization for the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /reports/getAttackSimulationRepeatOffenders](https://docs.microsoft.com/graph/api/securityreportsroot-getattacksimulationrepeatoffenders?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getAttackSimulationSimulationUserCoverage](https://docs.microsoft.com/graph/api/reportroot-getattacksimulationsimulationusercoverage?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/getAttackSimulationTrainingUserCoverage](https://docs.microsoft.com/graph/api/reportroot-getattacksimulationtrainingusercoverage?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /reports/security/getAttackSimulationRepeatOffenders](https://docs.microsoft.com/graph/api/securityreportsroot-getattacksimulationrepeatoffenders?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/security/getAttackSimulationSimulationUserCoverage](https://docs.microsoft.com/graph/api/securityreportsroot-getattacksimulationsimulationusercoverage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /reports/security/getAttackSimulationTrainingUserCoverage](https://docs.microsoft.com/graph/api/securityreportsroot-getattacksimulationtrainingusercoverage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/endUserNotifications](https://docs.microsoft.com/graph/api/endusernotification-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/endUserNotifications?$filter=source eq 'tenant'](https://docs.microsoft.com/graph/api/attacksimulationroot-list-endusernotifications?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/landingPages?$filter=source eq 'tenant'](https://docs.microsoft.com/graph/api/attacksimulationroot-list-landingpage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/landingPages/{landingPageId}](https://docs.microsoft.com/graph/api/landingpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/loginPages?$filter=source eq 'tenant'](https://docs.microsoft.com/graph/api/attacksimulationroot-list-loginpage?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/loginPages/{loginPageId}](https://docs.microsoft.com/graph/api/loginpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/operations/{operationsId}](https://docs.microsoft.com/graph/api/attacksimulationoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/payloads?$filter=source eq 'tenant'](https://docs.microsoft.com/graph/api/attacksimulationroot-list-payloads?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/payloads/{payloadId}](https://docs.microsoft.com/graph/api/payload-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/payloads/{payloadId}/detail](https://docs.microsoft.com/graph/api/payloaddetail-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulationAutomations](https://docs.microsoft.com/graph/api/attacksimulationroot-list-simulationautomations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulationAutomations/{simulationAutomationId}](https://docs.microsoft.com/graph/api/simulationautomation-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulationAutomations/{simulationAutomationId}/runs](https://docs.microsoft.com/graph/api/simulationautomation-list-runs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations](https://docs.microsoft.com/graph/api/attacksimulationroot-list-simulations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}](https://docs.microsoft.com/graph/api/simulation-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /security/attackSimulation/simulations/{simulationId}/excludedAccountTarget](https://docs.microsoft.com/graph/api/attacksimulationroot-get-excludedaccounttarget?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/attackSimulation/simulations/{simulationId}/includedAccountTarget](https://docs.microsoft.com/graph/api/attacksimulationroot-get-includedaccounttarget?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}/landingPage](https://docs.microsoft.com/graph/api/landingpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}/loginPage](https://docs.microsoft.com/graph/api/loginpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}/report/overview](https://docs.microsoft.com/graph/api/simulationreportoverview-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}/report/simulationUsers](https://docs.microsoft.com/graph/api/usersimulationdetails-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /security/attackSimulation/trainingCampaigns](https://docs.microsoft.com/graph/api/attacksimulationroot-list-trainingcampaigns?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/attackSimulation/trainingCampaigns/{trainingCampaignId}](https://docs.microsoft.com/graph/api/trainingcampaign-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/attackSimulation/trainingCampaigns/{trainingCampaignId}/report/campaignUsers](https://docs.microsoft.com/graph/api/usertrainingcampaigndetails-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/attackSimulation/trainingCampaigns/{trainingCampaignId}/report/overview](https://docs.microsoft.com/graph/api/trainingcampaignreportoverview-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/trainings](https://docs.microsoft.com/graph/api/attacksimulationroot-list-trainings?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/trainings/{trainingId}](https://docs.microsoft.com/graph/api/training-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/trainings/{trainingId}/languageDetails/{trainingLanguageDetailId}?$filter=locale eq 'locale'](https://docs.microsoft.com/graph/api/traininglanguagedetail-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|104a7a4b-ca76-4677-b7e7-2f4bc482f381|
|**Consent Type**|Admin|
|**Display String**|Read attack simulation data of an organization|
|**Description**|Allows the app to read attack simulation and training data for an organization for the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|93283d0a-6322-4fa8-966b-8c121624760d|
|**Display String**|Read attack simulation data of an organization|
|**Description**|Allows the app to read attack simulation and training data for an organization without a signed-in user.|
## Resources
### [accountTargetContent ](https://docs.microsoft.com/graph/api/resources/accounttargetcontent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|type|accountTargetContentType| The type of account target content. Possible values are: `unknown`, `includeAll`, `addressBook`, `unknownFutureValue`.|
### [attackSimulationOperation ](https://docs.microsoft.com/graph/api/resources/attacksimulationoperation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Operation created date time. The timestamp represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from longRunningOperation.|
|id|String|The unique identifier for the operation. Inherited from entity.|
|lastActionDateTime|DateTimeOffset|The time of the last action in the operation. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Inherited from longRunningOperation.|
|percentageCompleted|Int32| Percentage of completion of the respective operation.|
|resourceLocation|String|URI of the resource location. Inherited from longRunningOperation.|
|status|longRunningOperationStatus|Operation status. The possible values are: `notStarted`, `running`, `succeeded`, `failed`, `unknownFutureValue`. Inherited from longRunningOperation.|
|statusDetail|String|Status detail of the operation. Inherited from longRunningOperation.|
|tenantId|String|Tenant identifier.|
|type|attackSimulationOperationType|The attack simulation operation type. Possible values are: `createSimulation`, `updateSimulation`, `unknownFutureValue`.|
### [attackSimulationRepeatOffender ](https://docs.microsoft.com/graph/api/resources/attacksimulationrepeatoffender?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attackSimulationUser|attackSimulationUser|The user in an attack simulation and training campaign.|
|repeatOffenceCount|Int32|Number of repeat offences of the user in attack simulation and training campaigns.|
### [attackSimulationSimulationUserCoverage ](https://docs.microsoft.com/graph/api/resources/attacksimulationsimulationusercoverage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attackSimulationUser|attackSimulationUser|User in an attack simulation and training campaign.|
|clickCount|Int32|Number of link clicks in the received payloads by the user in attack simulation and training campaigns.|
|compromisedCount|Int32|Number of compromising actions by the user in attack simulation and training campaigns.|
|latestSimulationDateTime|DateTimeOffset|Date and time of the latest attack simulation and training campaign that the user was included in.|
|simulationCount|Int32|Number of attack simulation and training campaigns that the user was included in.|
### [attackSimulationTrainingUserCoverage ](https://docs.microsoft.com/graph/api/resources/attacksimulationtrainingusercoverage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attackSimulationUser|attackSimulationUser|User in an attack simulation and training campaign.|
|userTrainings|userTrainingStatusInfo collection|List of assigned trainings and their statuses for the user.|
### [endUserNotification ](https://docs.microsoft.com/graph/api/resources/endusernotification?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|emailIdentity|Identity of the user who created the notification.|
|createdDateTime|DateTimeOffset|Date and time when the notification was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|Description of the notification as defined by the user.|
|displayName|String|Name of the notification as defined by the user.|
|id|String|Unique identifier for the **endUserNotification** object. Inherited from entity.|
|lastModifiedBy|emailIdentity|Identity of the user who last modified the notification.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the notification was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|notificationType|endUserNotificationType|Type of notification. Possible values are: `unknown`, `positiveReinforcement`, `noTraining`, `trainingAssignment`, `trainingReminder`, `unknownFutureValue`.|
|source|simulationContentSource|The source of the content. Possible values are: `unknown`, `global`, `tenant`, `unknownFutureValue`.|
|status|simulationContentStatus|The status of the notification. Possible values are: `unknown`, `draft`, `ready`, `archive`, `delete`, `unknownFutureValue`.|
|supportedLocales|String collection|Supported locales for **e
### [landingPage ](https://docs.microsoft.com/graph/api/resources/landingpage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|emailIdentity|Identity of the user who created the landing page.|
|createdDateTime|DateTimeOffset|Date and time when the landing page was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|Description of the landing page as defined by the user.|
|displayName|String|The display name of the landing page.|
|id|String|Unique identifier for the **landingPage** object. Inherited from entity.|
|lastModifiedBy|emailIdentity|Email identity of the user who last modified the landing page.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the landing page was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|locale|String|Content locale.|
|source|simulationContentSource|The source of the content. Possible values are: `unknown`, `global`, `tenant`, `unknownFutureValue`.|
|status|simulationContentStatus|The status of the simulation. Possible values are: `unknown`, `draft`, `ready`, `archive`, `delete`, `unknownFutureValue`.|
|supportedLocales|String collection|Supported locales.|
### [loginPage ](https://docs.microsoft.com/graph/api/resources/loginpage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|String|The HTML content of the login page.|
|createdBy|emailIdentity|Identity of the user who created the login page.|
|createdDateTime|DateTimeOffset|Date and time when the login page was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|Description about the login page.|
|displayName|String|Display name of the login page.|
|id|String|Unique identifier for the **loginPage** object. Inherited from entity.|
|language|String|The content language of the login page.|
|lastModifiedBy|emailIdentity|Identity of the user who last modified the login page.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the login page was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|source|simulationContentStatus|The source of the content. Possible values are: `unknown`, `global`, `tenant`, `unknownFutureValue`.|
|status|simulationContentStatus|The login page status. Possible values are: `unknown`, `draft`, `ready`, `archive`, `delete`, `unknownFutureValue`.|
### [payload ](https://docs.microsoft.com/graph/api/resources/payload?view=graph-rest-1.0&tabs=http)
| Property | Type        | Description |
|:-------------|:------------|:------------|
|brand|payloadBrand|The branch of a payload. Possible values are: `unknown`, `other`, `americanExpress`, `capitalOne`, `dhl`, `docuSign`, `dropbox`, `facebook`, `firstAmerican`, `microsoft`, `netflix`, `scotiabank`, `sendGrid`, `stewartTitle`, `tesco`, `wellsFargo`, `syrinxCloud`, `adobe`, `teams`, `zoom`, `unknownFutureValue`. |
|complexity|payloadComplexity|The complexity of a payload. Possible values are: `unknown`, `low`, `medium`, `high`, `unknownFutureValue`.|
|createdBy|emailIdentity|Identity of the user who created the attack simulation and training campaign payload.|
|createdDateTime|DateTimeOffset|Date and time when the attack simulation and training campaign payload. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|Description of the attack simulation and training campaign payload.|
|detail|payloadDetail|Additional details about the payload.|
|displayName|String|Display name of the attack simulation and training campaign payload. Supports `$filter` and `$orderby`.|
|id|String|Unique identifier for the attack simulation and training campaign payload. Inherited from entity.|
|industry|payloadIndustry|Industry of a payload. Possible values are: `unknown`, `other`, `banking`, `businessServices`, `consumerServices`, `education`, `energy`, `construction`, `consulting`, `financialServices`, `government`, `hospitality`, `insurance`, `legal`, `courierServices`, `IT`, `healthcare`, `manufacturing`, `retail`, `telecom`, `realEstate`, `unknownFutureValue`.|
|isAutomated|Boolean|Indicates whether the attack simulation and training campaign payload was created from an automation flow. Supports `$filter` and `$orderby`. |
|isControversial|Boolean|Indicates whether the payload is controversial. |
|isCurrentEvent|Boolean|Indicates whether the payload is from any recent event. |
|language|String|Payload language.|
|lastModifiedBy|emailIdentity|Identity of the user who most recently modified the attack simulation and training campaign payload.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the attack simulation and training campaign payload was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|payloadTags|String collection|Free text tags for a payload.|
|platform|payloadDeliveryPlatform|The payload delivery platform for a simulation. Possible values are: `unknown`, `sms`, `email`, `teams`, `unknownFutureValue`.|
|predictedCompromiseRate|Double|Predicted probability for a payload to phish a targeted user.|
|simulationAttackType|simulationAttackType|Attack type of the attack simulation and training campaign. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `social`, `cloud`, `endpoint`, `unknownFutureValue`.|
|source|simulationContentSource|Simulation content source. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `global`, `tenant`, `unknownFutureValue`.|
|status|simulationContentStatus|Simulation content status. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `draft`, `ready`, `archive`, `delete`, `unknownFutureValue`.|
|technique|simulationAttackTechnique|The social engineering technique used in the attack simulation and training campaign. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `credentialHarvesting`, `attachmentMalware`, `driveByUrl`, `linkInAttachment`, `linkToMalwareFile`, `unknownFutureValue`, `oAuthConsentGrant`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `oAuthConsentGrant`. For more information on the types of social engineering attack techniques, see simulations.|
|theme|payloadTheme|The theme of a payload. Possible values are: `unknown`, `other`, `accountActivation`, `accountVerification`, `billing`, `cleanUpMail`, `controversial`, `documentReceived`, `expense`, `fax`, `financeReport`, `incomingMessages`, `invoice`, `itemReceived`, `loginAlert`, `mailReceived`, `password`, `payment`, `payroll`, `personalizedOffer`, `quarantine`, `remoteWork`, `reviewMessage`, `securityUpdate`, `serviceSuspended`, `signatureRequired`, `upgradeMailboxStorage`, `verifyMailbox`, `voicemail`, `advertisement`, `employeeEngagement`, `unknownFutureValue`.|
### [payloadDetail ](https://docs.microsoft.com/graph/api/resources/payloaddetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|coachMarks|payloadCoachmark collection|Payload coachmark details.|
|content|String|Payload content details.|
|phishingUrl|String|The phishing URL used to target a user.|
### [simulation ](https://docs.microsoft.com/graph/api/resources/simulation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attackTechnique|simulationAttackTechnique|The social engineering technique used in the attack simulation and training campaign. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `credentialHarvesting`, `attachmentMalware`, `driveByUrl`, `linkInAttachment`, `linkToMalwareFile`, `unknownFutureValue`, `oAuthConsentGrant`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `oAuthConsentGrant`. For more information on the types of social engineering attack techniques, see simulations.|
|attackType|simulationAttackType|Attack type of the attack simulation and training campaign. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `social`, `cloud`, `endpoint`, `unknownFutureValue`.|
|automationId|String|Unique identifier for the attack simulation automation.|
|completionDateTime|DateTimeOffset|Date and time of completion of the attack simulation and training campaign. Supports `$filter` and `$orderby`.|
|createdBy|emailIdentity|Identity of the user who created the attack simulation and training campaign.|
|createdDateTime|DateTimeOffset|Date and time of creation of the attack simulation and training campaign.|
|description|String|Description of the attack simulation and training campaign.|
|displayName|String|Display name of the attack simulation and training campaign. Supports `$filter` and `$orderby`.|
|durationInDays|Int32|Simulation duration in days.|
|endUserNotificationSetting|endUserNotificationSetting|Details about the end user notification setting.|
|excludedAccountTarget|accountTargetContent|Users excluded from the simulation.|
|id|String|Unique identifier for the attack simulation and training campaign. Inherited from entity.|
|includedAccountTarget|accountTargetContent|Users targeted in the simulation.|
|isAutomated|Boolean|Flag that represents if the attack simulation and training campaign was created from a simulation automation flow. Supports `$filter` and `$orderby`. |
|lastModifiedBy|emailIdentity|Identity of the user who most recently modified the attack simulation and training campaign.|
|lastModifiedDateTime|DateTimeOffset|Date and time of the most recent modification of the attack simulation and training campaign.|
|launchDateTime|DateTimeOffset|Date and time of the launch/start of the attack simulation and training campaign. Supports `$filter` and `$orderby`.|
|oAuthConsentAppDetail|oAuthConsentAppDetail|OAuth app details for the OAuth technique.|
|payloadDeliveryPlatform|payloadDeliveryPlatform|Method of delivery of the phishing payload used in the attack simulation and training campaign. Possible values are: `unknown`, `sms`, `email`, `teams`, `unknownFutureValue`.|
|report|simulationReport|Report of the attack simulation and training campaign.|
|status|simulationStatus|Status of the attack simulation and training campaign. Supports `$filter` and `$orderby`. Possible values are: `unknown`, `draft`, `running`, `scheduled`, `succeeded`, `failed`, `cancelled`, `excluded`, `unknownFutureValue`.|
|trainingSetting|trainingSetting|Details about the training settings for a simulation.|
### [simulationAutomation ](https://docs.microsoft.com/graph/api/resources/simulationautomation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|emailIdentity|Identity of the user who created the attack simulation automation.|
|createdDateTime|DateTimeOffset|Date and time when the attack simulation automation was created.|
|description|String|Description of the attack simulation automation.|
|displayName|String|Display name of the attack simulation automation. Supports `$filter` and `$orderby`.|
|id|String|Unique identifier for the attack simulation automation. Inherited from entity.|
|lastModifiedBy|emailIdentity|Identity of the user who most recently modified the attack simulation automation.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the attack simulation automation was most recently modified.|
|lastRunDateTime|DateTimeOffset|Date and time of the latest run of the attack simulation automation.|
|nextRunDateTime|DateTimeOffset|Date and time of the upcoming run of the attack simulation automation.|
|status|simulationAutomationStatus|Status of the attack simulation automation. Supports `$filter` and `$orderby`. The possible values are: `unknown`, `draft`, `notRunning`, `running`, `completed`, `unknownFutureValue`.|
### [simulationAutomationRun ](https://docs.microsoft.com/graph/api/resources/simulationautomationrun?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|endDateTime|DateTimeOffset|Date and time when the run ends in an attack simulation automation.|
|id|String|Unique identifier for the run of an attack simulation automation. Inherited from entity.|
|simulationId|String|Unique identifier for the attack simulation campaign initiated in the attack simulation automation run.|
|startDateTime|DateTimeOffset|Date and time when the run starts in an attack simulation automation.|
|status|simulationAutomationRunStatus|Status of the attack simulation automation run. The possible values are: `unknown`, `running`, `succeeded`, `failed`, `skipped`, `unknownFutureValue`.|
### [simulationReportOverview ](https://docs.microsoft.com/graph/api/resources/simulationreportoverview?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|recommendedActions|recommendedAction collection|List of recommended actions for a tenant to improve its security posture based on the attack simulation and training campaign attack type.|
|resolvedTargetsCount|Int32|Number of valid users in the attack simulation and training campaign.|
|simulationEventsContent|simulationEventsContent|Summary of simulation events in the attack simulation and training campaign.|
|trainingEventsContent|trainingEventsContent|Summary of assigned trainings in the attack simulation and training campaign.|
### [training ](https://docs.microsoft.com/graph/api/resources/training?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|availabilityStatus|trainingAvailabilityStatus|Training availability status. Possible values are: `unknown`, `notAvailable`, `available`, `archive`, `delete`, `unknownFutureValue`.|
|createdBy|emailIdentity|Identity of the user who created the training.|
|createdDateTime|DateTimeOffset|Date and time when the training was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|The description for the training.|
|displayName|String|The display name for the training.|
|durationInMinutes|Int32|Training duration.|
|hasEvaluation|Boolean|Indicates whether the training has any evaluation.|
|id|String|Unique identifier for the **training** object. Inherited from entity.|
|lastModifiedBy|emailIdentity|Identity of the user who last modified the training.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the training was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|source|simulationContentSource|Training content source. Possible values are: `unknown`, `global`, `tenant`, `unknownFutureValue`.|
|supportedLocales|String collection|Supported locales for content for the associated training.|
|tags|String collection|Training tags.|
|type|trainingType|The type of training. Possible values are: `unknown`, `phishing`, `unknownFutureValue`.|
### [trainingCampaign ](https://docs.microsoft.com/graph/api/resources/trainingcampaign?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|campaignSchedule|campaignSchedule|Details about the schedule and current status for a training campaign|
|createdBy|emailIdentity|Identity of the user who created the training campaign|
|createdDateTime|DateTimeOffset|Date and time of creation of the training campaign.|
|description|String|Description of the training campaign.|
|displayName|String|Display name of the training campaign. Supports `$filter` and `$orderby`.|
|endUserNotificationSetting|endUserNotificationSetting|Details about the end user notification setting.|
|excludedAccountTarget|accountTargetContent|Users excluded from the training campaign.|
|id|String|Unique identifier for the training campaign. Inherited from entity.|
|includedAccountTarget|accountTargetContent|Users targeted in the training campaign.|
|lastModifiedBy|emailIdentity|Identity of the user who most recently modified the training campaign.|
|lastModifiedDateTime|DateTimeOffset|Date and time of the most recent modification of the training campaign.|
|report|trainingCampaignReport|Report of the training campaign.|
|trainingSetting|trainingSetting|Details about the training settings for a training campaign.|
### [trainingCampaignReportOverview ](https://docs.microsoft.com/graph/api/resources/trainingcampaignreportoverview?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|trainingModuleCompletion|trainingEventsContent|Aggregate data of training completion.|
|trainingNotificationDeliveryStatus|trainingNotificationDelivery|Aggregate data of training mail delivery over the course of the training campaign.|
|userCompletionStatus|userTrainingCompletionSummary|Aggregate data of users training progress.|
### [trainingLanguageDetail ](https://docs.microsoft.com/graph/api/resources/traininglanguagedetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|content|String|Language specific content for the training.|
|createdBy|emailIdentity|Identity of the user who created the language details.|
|createdDateTime|DateTimeOffset|Date and time when the language details were created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|description|String|Description as defined by the user.|
|displayName|String|Display name as defined by the user.|
|id|String|Unique identifier of the **trainingLanguageDetail** object. Inherited from entity.|
|isDefaultLangauge|Boolean|Indicates whether the training has a default language.|
|lastModifiedBy|emailIdentity|Identity of the user who last modified the details.|
|lastModifiedDateTime|DateTimeOffset|Date and time when the **trainingLanguageDetail** was last modified. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|locale|String|Content locale for the training detail.|
### [userSimulationDetails ](https://docs.microsoft.com/graph/api/resources/usersimulationdetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignedTrainingsCount|Int32|Number of trainings assigned to a user in an attack simulation and training campaign.|
|completedTrainingsCount|Int32|Number of trainings completed by a user in an attack simulation and training campaign.|
|compromisedDateTime|DateTimeOffset|Date and time of the compromising online action by a user in an attack simulation and training campaign.|
|inProgressTrainingsCount|Int32|Number of trainings in progress by a user in an attack simulation and training campaign.|
|isCompromised|Boolean|Indicates whether a user was compromised in an attack simulation and training campaign.|
|reportedPhishDateTime|DateTimeOffset|Date and time when a user reported the delivered payload as phishing in the attack simulation and training campaign.|
|simulationEvents|userSimulationEventInfo collection|List of simulation events of a user in the attack simulation and training campaign.|
|simulationUser|attackSimulationUser|User in an attack simulation and training campaign.|
|trainingEvents|userTrainingEventInfo collection|List of training events of a user in the attack simulation and training campaign.|
