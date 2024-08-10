# AttackSimulation.ReadWrite.All

> Allows the app to read, create, and update attack simulation and training data for an organization for the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /security/attackSimulation/simulations/{simulationId}](https://docs.microsoft.com/graph/api/simulation-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/attackSimulation/trainingCampaigns/{trainingCampaignId}/$ref](https://docs.microsoft.com/graph/api/attacksimulationroot-delete-trainingcampaigns?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/endUserNotifications](https://docs.microsoft.com/graph/api/endusernotification-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/landingPages/{landingPageId}](https://docs.microsoft.com/graph/api/landingpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/loginPages/{loginPageId}](https://docs.microsoft.com/graph/api/loginpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/payloads/{payloadId}/detail](https://docs.microsoft.com/graph/api/payloaddetail-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}/landingPage](https://docs.microsoft.com/graph/api/landingpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/simulations/{simulationId}/loginPage](https://docs.microsoft.com/graph/api/loginpage-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/trainings/{trainingId}](https://docs.microsoft.com/graph/api/training-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/attackSimulation/trainings/{trainingId}/languageDetails/{trainingLanguageDetailId}?$filter=locale eq 'locale'](https://docs.microsoft.com/graph/api/traininglanguagedetail-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /security/attackSimulation/simulations/{simulationId}](https://docs.microsoft.com/graph/api/simulation-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /security/attackSimulation/trainingCampaigns/{trainingCampaignId}](https://docs.microsoft.com/graph/api/trainingcampaign-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /security/attackSimulation/simulations](https://docs.microsoft.com/graph/api/attacksimulationroot-post-simulation?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /security/attackSimulation/trainingCampaigns](https://docs.microsoft.com/graph/api/attacksimulationroot-post-trainingcampaigns?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|27608d7c-2c66-4cad-a657-951d575f5a60|
|**Consent Type**|User|
|**Display String**|Read, create, and update attack simulation data of an organization|
|**Description**|Allows the app to read, create, and update attack simulation and training data for an organization for the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|e125258e-8c8a-42a8-8f55-ab502afa52f3|
|**Display String**|Read, create, and update all attack simulation data of an organization|
|**Description**|Allows the app to read, create, and update attack simulation and training data for an organization without a signed-in user.|
## Resources
### [accountTargetContent ](https://docs.microsoft.com/graph/api/resources/accounttargetcontent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|type|accountTargetContentType| The type of account target content. Possible values are: `unknown`, `includeAll`, `addressBook`, `unknownFutureValue`.|
### [campaignSchedule ](https://docs.microsoft.com/graph/api/resources/campaignschedule?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|completionDateTime|DateTimeOffset|The date and time at which the campaign completed.|
|launchDateTime|DateTimeOffset|The date and time at which the campaign was launched.|
|status|campaignStatus|The current state of the campaign. The possible values are: `unknown`, `draft`, `inProgress`, `scheduled`, `completed`, `failed`, `cancelled`, `excluded`, `deleted`, `unknownFutureValue`.|
### [emailIdentity ](https://docs.microsoft.com/graph/api/resources/emailidentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name of the user. Inherited from identity.|
|email|String|Email address of the user.|
|id|String|The unique identifier for the user. Inherited from identity.|
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
### [endUserNotificationSetting ](https://docs.microsoft.com/graph/api/resources/endusernotificationsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|notificationPreference|endUserNotificationPreference|Notification preference. Possible values are: `unknown`, `microsoft`, `custom`, `unknownFutureValue`.|
|positiveReinforcement|positiveReinforcementNotification|Positive reinforcement detail.|
|settingType|endUserNotificationSettingType|End user notification type. Possible values are: `unknown`, `noTraining`, `trainingSelected`, `noNotification`, `unknownFutureValue`.|
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
### [oAuthConsentAppDetail ](https://docs.microsoft.com/graph/api/resources/oauthconsentappdetail?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appScope|oAuthAppScope|App scope. Possible values are: `unknown`, `readCalendar`, `readContact`, `readMail`, `readAllChat`, `readAllFile`, `readAndWriteMail`, `sendMail`, `unknownFutureValue`.|
|displayLogo|String|App display logo.|
|displayName|String|App name.|
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
### [trainingSetting ](https://docs.microsoft.com/graph/api/resources/trainingsetting?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|settingType|trainingSettingType|Type of setting. Possible values are: `microsoftCustom`, `microsoftManaged`, `noTraining`, `custom`, `unknownFutureValue`.|
