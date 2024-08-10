# ThreatSubmissionPolicies.ReadWrite.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[DELETE /security/threatSubmission/emailThreatSubmissionPolicies/{id}](https://docs.microsoft.com/graph/api/security-emailthreatsubmissionpolicy-delete?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Resources
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
