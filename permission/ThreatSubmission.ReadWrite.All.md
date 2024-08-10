# ThreatSubmission.ReadWrite.All

> Allows the app to read your organization's threat submissions and threat submission policies on behalf of the signed-in user. Also allows the app to create new threat submissions on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /security/threatSubmission/emailThreats](https://docs.microsoft.com/graph/api/security-emailthreatsubmission-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/threatSubmission/emailThreats/{emailThreatsId}](https://docs.microsoft.com/graph/api/security-emailthreatsubmission-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/threatSubmission/emailThreatSubmissionPolicies/{emailThreatSubmissionPoliciesId}](https://docs.microsoft.com/graph/api/security-emailthreatsubmissionpolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/threatSubmission/fileThreats](https://docs.microsoft.com/graph/api/security-filethreatsubmission-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/threatSubmission/fileThreats/{fileThreatsId}](https://docs.microsoft.com/graph/api/security-filethreatsubmission-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/threatSubmission/urlThreats](https://docs.microsoft.com/graph/api/security-urlthreatsubmission-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /security/threatSubmission/urlThreats/{urlThreatsId}](https://docs.microsoft.com/graph/api/security-urlthreatsubmission-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET security/threatSubmission/emailThreatSubmissionPolicies](https://docs.microsoft.com/graph/api/security-emailthreatsubmissionpolicy-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/threatSubmission/emailThreats](https://docs.microsoft.com/graph/api/security-emailthreatsubmission-post-emailthreats?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/threatSubmission/emailThreats/{emailThreatsId}/review](https://docs.microsoft.com/graph/api/security-emailthreatsubmission-review?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/threatSubmission/fileThreats](https://docs.microsoft.com/graph/api/security-filethreatsubmission-post-filethreats?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /security/threatSubmission/urlThreats](https://docs.microsoft.com/graph/api/security-urlthreatsubmission-post-urlthreats?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8458e264-4eb9-4922-abe9-768d58f13c7f|
|**Consent Type**|Admin|
|**Display String**|Read and write all threat submissions|
|**Description**|Allows the app to read your organization's threat submissions and threat submission policies on behalf of the signed-in user. Also allows the app to create new threat submissions on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|d72bdbf4-a59b-405c-8b04-5995895819ac|
|**Display String**|Read and write all of the organization's threat submissions|
|**Description**|Allows the app to read your organization's threat submissions and threat submission policies without a signed-in user. Also allows the app to create new threat submissions without a signed-in user.|
## Resources
### [emailContentThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-emailcontentthreatsubmission?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|fileContent|String|Base64 encoded file content.|
### [emailThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-emailthreatsubmission?view=graph-rest-1.0&tabs=http)
| Property     | Type    | Description    |
|:-----------------------------|:-----------------------------|:-------------------------------------------------------------------------------------------------------|
| attackSimulationInfo         | security.attackSimulationInfo | If the email is phishing simulation, this field won't be null.|
| internetMessageId            | String                       | Specifies the internet message ID of the email being submitted. This information is present in the email header. |
| originalCategory             | submissionCategory           | The original category of the submission. The possible values are: `notJunk`, `spam`, `phishing`, `malware` and `unkownFutureValue`. |
| receivedDateTime             | DateTimeOffset               | Specifies the date and time stamp when the email was received.  | 
| recipientEmailAddress        | String                       | Specifies the email address (in smtp format) of the recipient who received the email. |
| sender                       | String                       | Specifies the email address of the sender. | 
| senderIP                     | String                       | Specifies the IP address of the sender. |
| subject                      | String                       | Specifies the subject of the email. |
| tenantAllowOrBlockListAction | security.tenantAllowOrBlockListAction | It's used to automatically add allows for the components such as URL, file, sender; which are deemed bad by Microsoft so that similar messages in the future can be allowed. |
### [emailThreatSubmissionPolicy ](https://docs.microsoft.com/graph/api/resources/security-emailthreatsubmissionpolicy?view=graph-rest-1.0&tabs=http)
| Property                                 | Type    | Description                                                                                |
|:-----------------------------------------|:--------|:-------------------------------------------------------------------------------------------|
| customizedNotificationSenderEmailAddress | String  | Specifies the email address of the sender from which email notifications will be sent to end users to inform them whether an email is spam, phish or clean. The default value is `null`. Optional for creation.                   |
| customizedReportRecipientEmailAddress    | String  | Specifies the destination where the reported messages from end users land whenever they report something as phish, junk or not junk. The default value is `null`. Optional for creation. |
| id                                       | String  | Only one id is supported. The default value is `DefaultReportSubmissionPolicy`. |
| isAlwaysReportEnabledForUsers            | Boolean | Indicates whether end users can report a message as spam, phish or junk directly without a confirmation(popup). The default value is `true`.  Optional for creation.          |
| isAskMeEnabledForUsers                   | Boolean | Indicates whether end users can confirm using a popup before reporting messages as spam, phish or not junk. The default value is `true`.  Optional for creation.   |
| isCustomizedMessageEnabled               | Boolean | Indicates whether the email notifications sent to end users to inform them if an email is a phish mail, spam or junk is customized or not. The default value is `false`. Optional for creation.    |
| isCustomizedMessageEnabledForPhishing    | Boolean | If enabled, customized message only shows when email is reported as phishing. The default value is `false`. Optional for creation. |
| isCustomizedNotificationSenderEnabled    | Boolean | Indicates whether to use the sender email address set using customizedNotificationSenderEmailAddress for sending email notifications to end users. The default value is `false`. Optional for creation.  |
| isNeverReportEnabledForUsers             | Boolean | Indicates whether end users can move the message from one folder to another based on the action of spam, phish or not junk without actually reporting it. The default value is `true`. Optional for creation.         |
| isOrganizationBrandingEnabled            | Boolean | Indicates whether the branding logo should be used in the email notifications sent to end users. The default value is `false`. Optional for creation.        |
| isReportFromQuarantineEnabled            | Boolean | Indicates whether end users can submit from the quarantine page. The default value is `true`. Optional for creation.  |
| isReportToCustomizedEmailAddressEnabled  | Boolean | Indicates whether emails reported by end users should be sent to the custom mailbox configured using customizedReportRecipientEmailAddress.  The default value is `false`. Optional for creation.              |
| isReportToMicrosoftEnabled               | Boolean | If enabled, the email is sent to Microsoft for analysis. The default value is `false`. Required for creation.  |
| isReviewEmailNotificationEnabled         | Boolean | Indicates whether an email notification is sent to the end user who reported the email when it has been reviewed by the admin. The default value is `false`. Optional for creation.  |
### [emailUrlThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-emailurlthreatsubmission?view=graph-rest-1.0&tabs=http)
| Property   | Type   | Description                            |
|:-----------|:-------|:---------------------------------------|
| messageUrl | String | Specifies the url of the message to be submitted. |
### [fileContentThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-filecontentthreatsubmission?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                  |
|:------------|:-------|:-----------------------------|
| fileContent | String | It specifies the file content in base 64 format. |
### [fileThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-filethreatsubmission?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                    |
|:---------|:-------|:-------------------------------|
| fileName | String | It specifies the file name to be submitted. |
### [fileUrlThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-fileurlthreatsubmission?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                   |
|:---------|:-------|:------------------------------|
| fileUrl  | String | It specifies the URL of the file that needs to be submitted. |
### [threatSubmission ](https://docs.microsoft.com/graph/api/resources/security-threatsubmission?view=graph-rest-1.0&tabs=http)
| Property        | Type                       | Description                                                                      |
|:----------------|:---------------------------|:---------------------------------------------------------------------------------|
| adminReview     | security.submissionAdminReview| Specifies the admin review property that constitutes of who reviewed the user submission, when and what was it identified as. |
| category        | submissionCategory         | Specifies the category of the submission. Supports `$filter = category eq 'value'`. The possible values are: `notJunk`, `spam`, `phishing`, `malware`, and `unkownFutureValue`.|
| clientSource    | submissionClientSource     | Specifies the source of the submission. The possible values are: `microsoft`, `other`, and `unkownFutureValue`. |
| contentType     | submissionContentType      | Specifies the type of content being submitted. The possible values are: `email`, `url`, `file`, `app`, and `unkownFutureValue`.  |
| createdBy       | security.submissionUserIdentity     | Specifies who submitted the email as a threat. Supports `$filter = createdBy/email eq 'value'`. |
| createdDateTime | DateTimeOffset  | Specifies when the threat submission was created. Supports `$filter = createdDateTime ge 2022-01-01T00:00:00Z and createdDateTime lt 2022-01-02T00:00:00Z`.             |
| id              | String                     | Specifies the ID of threat submission. |
| result          | security.submissionResult          | Specifies the result of the analysis performed by Microsoft.  |
| source          | submissionSource           | Specifies the role of the submitter. Supports `$filter = source eq 'value'`. The possible values are: `administrator`,  `user`, and `unkownFutureValue`.  |
| status          | longRunningOperationStatus | Indicates whether the threat submission has been analyzed by Microsoft. Supports `$filter = status eq 'value'`. The possible values are: `notStarted`, `running`, `succeeded`, `failed`, `skipped`, and `unkownFutureValue`. |
| tenantId        | String                     | Indicates the tenant id of the submitter. Not required when created using a `POST` operation. It's extracted from the token of the post API call. |
### [urlThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-urlthreatsubmission?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                 |
|:---------|:-------|:----------------------------|
| webUrl   | String | Denotes the webUrl that needs to be submitted. |
