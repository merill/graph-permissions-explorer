# VirtualEvent.ReadWrite.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[POST /solutions/virtualEvents/webinars/{webinarId}/registrations/{registrationId}/cancel](https://docs.microsoft.com/graph/api/virtualeventregistration-cancel?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
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
