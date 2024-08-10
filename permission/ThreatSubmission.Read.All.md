# ThreatSubmission.Read.All

> Allows the app to read your organization's threat submissions and threat submission policies on behalf of the signed-in user.
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
## Delegate Permission
|||
|-|-|
|**Id**|7083913a-4966-44b6-9886-c5822a5fd910|
|**Consent Type**|Admin|
|**Display String**|Read all threat submissions|
|**Description**|Allows the app to read your organization's threat submissions and threat submission policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|86632667-cd15-4845-ad89-48a88e8412e1|
|**Display String**|Read all of the organization's threat submissions|
|**Description**|Allows the app to read your organization's threat submissions and to view threat submission policies without a signed-in user.|
## Resources
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
### [fileThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-filethreatsubmission?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                    |
|:---------|:-------|:-------------------------------|
| fileName | String | It specifies the file name to be submitted. |
### [urlThreatSubmission ](https://docs.microsoft.com/graph/api/resources/security-urlthreatsubmission?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                 |
|:---------|:-------|:----------------------------|
| webUrl   | String | Denotes the webUrl that needs to be submitted. |
