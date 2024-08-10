# VirtualEvent.ReadWrite

> Allows the app to read and write virtual events for you
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /solutions/virtualEvents/townhalls/{townhallId}/presenters/{presenterId}](https://docs.microsoft.com/graph/api/virtualeventpresenter-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /solutions/virtualEvents/webinars/{webinarId}/presenters/{presenterId}](https://docs.microsoft.com/graph/api/virtualeventpresenter-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /solutions/virtualEvents/webinars/{webinarId}/registrationConfiguration/questions/{questionId}](https://docs.microsoft.com/graph/api/virtualeventregistrationquestionbase-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/townhalls/{townhallId}/presenters](https://docs.microsoft.com/graph/api/virtualevent-list-presenters?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/townhalls/{townhallId}/presenters/{presenterId}](https://docs.microsoft.com/graph/api/virtualeventpresenter-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/{webinarId}](https://docs.microsoft.com/graph/api/virtualeventwebinar-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/{webinarId}/presenters](https://docs.microsoft.com/graph/api/virtualevent-list-presenters?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/{webinarId}/presenters/{presenterId}](https://docs.microsoft.com/graph/api/virtualeventpresenter-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/{webinarId}/registrationConfiguration](https://docs.microsoft.com/graph/api/virtualeventwebinarregistrationconfiguration-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /solutions/virtualEvents/webinars/{webinarId}/registrations](https://docs.microsoft.com/graph/api/virtualeventregistration-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/virtualEvents/webinars/{webinarId}/registrations?$filter=email eq '{email}'](https://docs.microsoft.com/graph/api/virtualeventregistration-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /solutions/virtualEvents/webinars/{webinarId}/registrations?$filter=userId eq '{userId}'](https://docs.microsoft.com/graph/api/virtualeventregistration-list?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/{webinarId}/registrations/{registrationId}](https://docs.microsoft.com/graph/api/virtualeventregistration-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/{webinarId}/sessions/{sessionId}](https://docs.microsoft.com/graph/api/virtualeventsession-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/virtualEvents/webinars/getByUserRole(role='{role}')](https://docs.microsoft.com/graph/api/virtualeventwebinar-getbyuserrole?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /solutions/virtualEvents/webinars/{webinarId}/presenters/{presenterId}](https://docs.microsoft.com/graph/api/virtualeventpresenter-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /solutions/virtualEvents/townhalls/{townhallId}/presenters](https://docs.microsoft.com/graph/api/virtualevent-post-presenters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /solutions/virtualEvents/webinars/{webinarId}/presenters](https://docs.microsoft.com/graph/api/virtualevent-post-presenters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /solutions/virtualEvents/webinars/{webinarId}/registrationConfiguration/questions](https://docs.microsoft.com/graph/api/virtualeventregistrationconfiguration-post-questions?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /solutions/virtualEvents/webinars/{webinarId}/registrations/{registrationId}/cancel](https://docs.microsoft.com/graph/api/virtualeventregistration-cancel?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|d38d189c-e29b-4344-8b3b-829bfa81380b|
|**Consent Type**|Admin|
|**Display String**|Read and write your virtual events|
|**Description**|Allows the app to read and write virtual events for you|
## Resources
### [communicationsGuestIdentity ](https://docs.microsoft.com/graph/api/resources/communicationsguestidentity?view=graph-rest-1.0&tabs=http)
| Property                       | Type                        | Description           |
| :----------------------------- | :---------------------------| :---------------------|
| displayName | String | The display name associated with the guest user. Inherited from **identity**. |
| id | String | The unique identifier for the guest user. Inherited from **i
### [communicationsUserIdentity ](https://docs.microsoft.com/graph/api/resources/communicationsuseridentity?view=graph-rest-1.0&tabs=http)
| Property                       | Type                        | Description                     |
| :----------------------------- | :---------------------------| :-------------------------------|
| displayName | String | The display name associated with the user. Inherited from **identity**. |
| id | String | The user's object ID. Inherited from **identity**. |
| tenantId | String | The user's tenant ID. |
### [identity ](https://docs.microsoft.com/graph/api/resources/identity?view=graph-rest-1.0&tabs=http)
| Property    | Type   | Description                                                                                                                                                                                                                                                                                                           |
|:------------|:-------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| displayName         | String | The display name of the identity.<br/><br/>For drive items, the display name might not always be available or up to date. For example, if a user changes their display name the API might show the new value in a future response, but the items associated with the user don't show up as changed when using delta.       |
| id                  | String | Unique identifier for the identity or actor. For example, in the access reviews decisions API, this property might record the **id** of the principal, that is, the group, user, or application that's subject to review. |
| tenantId            | String | Unique identity of the tenant. Optional.                                    |
| thumbnails          | thumbnailSet | Keyed collection of thumbnail resources. Optional. Applies to drive items, for example. |
### [virtualEventPresenter ](https://docs.microsoft.com/graph/api/resources/virtualeventpresenter?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|email|String|Email address of the presenter.|
|id|String|Unique identifier of the presenter. Inherited from entity.|
|identity|identity|Identity information of the presenter. The supported identities are: communicationsGuestIdentity and communicationsUserIdentity. |
|presenterDetails|virtualEventPresenterDetails|Other details about the presenter. This property returns `null` when the virtual event type is virtualEventTownhall. |
### [virtualEventPresenterDetails ](https://docs.microsoft.com/graph/api/resources/virtualeventpresenterdetails?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|bio|itemBody|Bio of the presenter.|
|company|String|The presenter's company name.|
|jobTitle|String|The presenter's job title.|
|linkedInProfileWebUrl|String|The presenter's LinkedIn profile URL.|
|personalSiteWebUrl|String|The presenter's personal website URL.|
|photo|Stream|The content stream of the presenter's photo.|
|twitterProfileWebUrl|String|The presenter's Twitter profile URL.|
### [virtualEventRegistration ](https://docs.microsoft.com/graph/api/resources/virtualeventregistration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|  
|cancelationDateTime|DateTimeOffset|Date and time when the registrant cancels their registration for the virtual event. Only appears when applicable. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|email|String|Email address of the registrant.|
|firstName|String|First name of the registrant.|
|id|String|Unique identifier of the registrant. Read-only. Inherited from entity.|
|lastName|String|Last name of the registrant.|
|registrationDateTime|DateTimeOffset|Date and time when the registrant registers for the virtual event. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|registrationQuestionAnswers|virtualEventRegistrationQuestionAnswer collection|The registrant's answer to the registration questions.|
|status|virtualEventAttendeeRegistrationStatus|Registration status of the registrant. Read-only. Possible values are `registered`, `canceled`, `waitlisted`, `pendingApproval`, `rejectedByOrganizer`, and `unknownFutureValue`. |
|userId|String|The registrant's ID in Microsoft Entra ID. Only appears when the registrant is registered in Microsoft Entra ID.|
|preferredTimezone|String|The registrant's time zone details.|
|preferredLanguage|String|The registrant's preferred language.|
### [virtualEventRegistrationCustomQuestion ](https://docs.microsoft.com/graph/api/resources/virtualeventregistrationcustomquestion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|answerChoices|String collection|Answer choices when **answerInputType** is `singleChoice` or `multiChoice`. |
|answerInputType|virtualEventRegistrationQuestionAnswerInputType|Input type of the registration question answer. Possible values are `text`, `multilineText`, `singleChoice`, `multiChoice`, `boolean`, and `unknownFutureValue`.|
|displayName|String|Display name of the registration question. Inherited from virtualEventRegistrationQuestionBase.|
|id|String|Unique identifier of the registration question. Inherited from virtualEventRegistrationQuestionBase.|
|isRequired|Boolean| Indicates whether an answer to the question is required. The default value is `false`. Inherited from virtualEventRegistrationQuestionBase.|
### [virtualEventRegistrationPredefinedQuestion ](https://docs.microsoft.com/graph/api/resources/virtualeventregistrationpredefinedquestion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|label|virtualEventRegistrationPredefinedQuestionLabel|Label of the predefined registration question. It accepts a single line of text: `street`, `city`, `state`, `postalCode`, `countryOrRegion`, `industry`, `jobTitle`, `organization`, and `unknownFutureValue`. |
### [virtualEventRegistrationQuestionBase ](https://docs.microsoft.com/graph/api/resources/virtualeventregistrationquestionbase?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Display name of the registration question.|
|id|String|Unique identifier of the registration question. Inherited from entity.|
|isRequired|Boolean| Indicates whether an answer to the question is required. The default value is `false`.|
### [virtualEventSession ](https://docs.microsoft.com/graph/api/resources/virtualeventsession?view=graph-rest-1.0&tabs=http)
| Property              | Type                                          | Description    |
| :-------------------- | :-------------------------------------------- | :------------------------------------ |
| allowAttendeeToEnableCamera | Boolean | Indicates whether attendees can turn on their camera. Inherited from onlineMeetingBase. |
| allowAttendeeToEnableMic | Boolean | Indicates whether attendees can turn on their microphone. Inherited from onlineMeetingBase. |
| allowMeetingChat      | meetingChatMode | Specifies the mode of meeting chat. Inherited from onlineMeetingBase. |
| allowParticipantsToChangeName | Boolean | Specifies whether participants are allowed to rename themselves in an instance of the meeting. Inherited from onlineMeetingBase. |
| allowTeamworkReactions | Boolean | Indicates whether Teams reactions are enabled for the virtual event session. Inherited from onlineMeetingBase. |
| allowTranscription | Boolean | Indicates whether transcription is enabled for the virtual event session. Inherited from onlineMeetingBase. |
| allowRecording | Boolean | Indicates whether recording is enabled for the virtual event session. Inherited from onlineMeetingBase. |
| allowedPresenters     | onlineMeetingPresenters| Specifies who can be a presenter in a virtual event session. Inherited from onlineMeetingBase. |
| anonymizeIdentityForRoles    | onlineMeetingRole collection | Specifies whose identity is anonymized in the virtual event session. Possible values are: `attendee`. The `attendee` value can't be removed through a PATCH operation once added. Inherited from onlineMeetingBase.|
| audioConferencing     | audioConferencing     | The phone access (dial-in) information for the virtual event session. Read-only. Inherited from onlineMeetingBase. |
| chatInfo              | chatInfo | The chat information associated with the virtual event session. Inherited from onlineMeetingBase. |
| endDateTime           | DateTimeTimeZone | The virtual event session end time.   |
| id | String | The unique identifier of the virtual event session. Read-only. Inherited from onlineMeetingBase. |
| isEntryExitAnnounced  | Boolean | Indicates whether to announce when callers join or leave. Inherited from onlineMeetingBase. |
| joinInformation | itemBody | The join information of the virtual event session. Read-only. Inherited from onlineMeetingBase. |
| joinMeetingIdSettings | joinMeetingIdSettings | Specifies the **joinMeetingId**, the meeting passcode, and the requirement for the passcode. Inherited from onlineMeetingBase. |
| joinWebUrl | String | The join URL of the virtual event session. Read-only. Inherited from onlineMeetingBase. |
| lobbyBypassSettings | lobbyBypassSettings | Specifies which participants can bypass the meeting lobby. Inherited from onlineMeetingBase. |
| recordAutomatically | Boolean | Indicates whether to record the virtual event session automatically. Inherited from onlineMeetingBase. |
| startDateTime | DateTimeTimeZone | The virtual event session start time. |
| subject | String | The subject of the virtual event session. Inherited from onlineMeetingBase. |
| videoTeleconferenceId | String | The video teleconferencing ID. Read-only. Inherited from onlineMeetingBase. |
| watermarkProtection | watermarkProtectionValues     | Specifies whether the client application should apply a watermark to a content type. Inherited from onlineMeetingBase. |
### [virtualEventTownhall ](https://docs.microsoft.com/graph/api/resources/virtualeventtownhall?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| audience | meetingAudience | The audience to whom the town hall is visible. Possible values are: `everyone`, `organization`, and `unknownFutureValue`.  |
| coOrganizers  | communicationsUserIdentity collection | Identity information of the coorganizers of the town hall. |
| createdBy | communicationsIdentitySet | Identity information of the creator of the town hall. Inherited from virtualEvent. Read-only. |
| description | itemBody | Description of the town hall. Inherited from virtualEvent. |
| displayName | String | Display name of the town hall. Inherited from virtualEvent. |
| endDateTime | dateTimeTimeZone | Date and time when the town hall ends. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone. Inherited from virtualEvent. |
| id | String | Unique identifier of the town hall. Inherited from entity. Read-only. |
| invitedAttendees | identity collection | The attendees invited to the town hall. The supported identities are: communicationsUserIdentity and communicationsGuestIdentity. |
| isInviteOnly | Boolean | Indicates whether the town hall is only open to invited people and groups within your organization. The **isInviteOnly** property can only be `true` if the value of the **audience** property is set to `organization`. |
| settings | virtualEventSettings | The virtual event settings. |
| startDateTime | dateTimeTimeZone | Date and time when the town hall starts. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone. Inherited from virtualEvent. |
| status | virtualEventStatus | Status of the town hall. Possible values are: `draft`, `published`, `canceled`, and `unknownFutureValue`. Inherited from virtualEvent. |
### [virtualEventWebinar ](https://docs.microsoft.com/graph/api/resources/virtualeventwebinar?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
| -------- | ---- | ----------- |
| audience | meetingAudience | To whom the webinar is visible. Possible values are: `everyone`, `organization`, and `unknownFutureValue`. |
| coOrganizers  | communicationsUserIdentity collection | Identity information of coorganizers of the webinar. |
| createdBy | communicationsIdentitySet | Identity information for the creator of the webinar. Inherited from virtualEvent. |
| description | itemBody | Description of the webinar. Inherited from virtualEvent. |
| displayName | String | Display name of the webinar. Inherited from virtualEvent. |
| endDateTime | dateTimeTimeZone | End time of the webinar. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone. |
| startDateTime | dateTimeTimeZone | Start time of the webinar. The **timeZone** property _can_ be set to any of the time zones currently supported by Windows. For details on how to get all available time zones using PowerShell, see Get-TimeZone. |
| id | String | Unique identifier of the webinar. Inherited from entity.|
| settings | virtualEventSettings | The webinar settings. Inherited from virtualEvent. |
| status | virtualEventStatus | Status of the webinar. Possible values are: `draft`, `published`, `canceled`, and `unknownFutureValue`. Inherited from virtualEvent. |
### [virtualEventWebinarRegistrationConfiguration ](https://docs.microsoft.com/graph/api/resources/virtualeventwebinarregistrationconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| registrationWebUrl | String | Registration portal URL of the webinar. Inherited from virtualEventRegistrationConfiguration. |
