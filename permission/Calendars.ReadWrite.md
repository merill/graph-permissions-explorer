# Calendars.ReadWrite

> Allows the app to create, read, update, and delete events in user calendars. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groups/{id}/calendar/events/{id}](https://docs.microsoft.com/graph/api/group-delete-event?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groups/{id}/calendar/events/{id}/](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /groups/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/calendar/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/calendarGroups/{id}](https://docs.microsoft.com/graph/api/calendargroup-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/calendarGroups/{id}/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/calendars/{id}](https://docs.microsoft.com/graph/api/calendar-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/calendar/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/calendarGroups/{id}](https://docs.microsoft.com/graph/api/calendargroup-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/calendars/{id}](https://docs.microsoft.com/graph/api/calendar-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id | userPrincipalName}/events/{id}](https://docs.microsoft.com/graph/api/event-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{id}/calendar/calendarPermissions/{id}](https://docs.microsoft.com/graph/api/calendarpermission-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/group-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendar/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/user-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendarGroups](https://docs.microsoft.com/graph/api/user-list-calendargroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendars](https://docs.microsoft.com/graph/api/calendargroup-list-calendars?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendarView/delta?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /me/events/delta](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/events/delta?startDateTime={start_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendar/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/calendar-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendarGroups](https://docs.microsoft.com/graph/api/user-list-calendargroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendars](https://docs.microsoft.com/graph/api/calendargroup-list-calendars?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/user-list-calendarview?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/events/delta](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/events/delta?startDateTime={start_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/reminderView(startDateTime={startDateTime-value},endDateTime={endDateTime-value})](https://docs.microsoft.com/graph/api/user-reminderview?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/reminderView(startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/user-reminderview?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id}/calendarView/delta?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/{id}/calendar/events/{id}](https://docs.microsoft.com/graph/api/group-update-event?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /groups/{id}/events/{id}](https://docs.microsoft.com/graph/api/group-update-event?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/calendar/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/calendarGroups/{id}](https://docs.microsoft.com/graph/api/calendargroup-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/calendarGroups/{id}/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /me/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/calendar/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/calendarGroups/{id}](https://docs.microsoft.com/graph/api/calendargroup-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/calendars/{id}/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/events/{id}](https://docs.microsoft.com/graph/api/event-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/calendar/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{id}/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events](https://docs.microsoft.com/graph/api/user-post-events?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/attachments](https://docs.microsoft.com/graph/api/event-post-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/getSchedule](https://docs.microsoft.com/graph/api/calendar-getschedule?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups](https://docs.microsoft.com/graph/api/user-post-calendargroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups/{id}/calendars/{id}/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups/{id}/calendars/{id}/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups/{id}/calendars/{id}/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups/{id}/calendars/{id}/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups/{id}/calendars/{id}/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendarGroups/{id}/calendars/{id}/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars](https://docs.microsoft.com/graph/api/calendargroup-post-calendars?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events](https://docs.microsoft.com/graph/api/user-post-events?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendars/{id}/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events](https://docs.microsoft.com/graph/api/user-post-events?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/attachments](https://docs.microsoft.com/graph/api/event-post-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/attachments/createUploadSession](https://docs.microsoft.com/graph/api/attachment-createuploadsession?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /solutions/bookingbusinesses/{id}/getStaffAvailability](https://docs.microsoft.com/graph/api/bookingbusiness-getstaffavailability?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /solutions/bookingBusinesses/{id}/getStaffAvailability](https://docs.microsoft.com/graph/api/bookingbusiness-getstaffavailability?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events](https://docs.microsoft.com/graph/api/user-post-events?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/attachments](https://docs.microsoft.com/graph/api/event-post-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendar/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups](https://docs.microsoft.com/graph/api/user-post-calendargroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars](https://docs.microsoft.com/graph/api/calendargroup-post-calendars?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events](https://docs.microsoft.com/graph/api/user-post-events?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/calendars/{id}/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events](https://docs.microsoft.com/graph/api/user-post-events?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/accept](https://docs.microsoft.com/graph/api/event-accept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/attachments](https://docs.microsoft.com/graph/api/event-post-attachments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/attachments/createUploadSession](https://docs.microsoft.com/graph/api/attachment-createuploadsession?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/cancel](https://docs.microsoft.com/graph/api/event-cancel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/decline](https://docs.microsoft.com/graph/api/event-decline?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/dismissReminder](https://docs.microsoft.com/graph/api/event-dismissreminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/snoozeReminder](https://docs.microsoft.com/graph/api/event-snoozereminder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/events/{id}/tentativelyAccept](https://docs.microsoft.com/graph/api/event-tentativelyaccept?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id|userPrincipalName}/calendar/getSchedule](https://docs.microsoft.com/graph/api/calendar-getschedule?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[Prefer: outlook.timezone="Eastern Standard Time"](https://docs.microsoft.com/graph/api/user-list-events?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1ec239c2-d7c9-4623-a91a-a9775856bb36|
|**Consent Type**|User|
|**Display String**|Have full access to user calendars |
|**Description**|Allows the app to create, read, update, and delete events in user calendars. |
## Application Permission
|||
|-|-|
|**Id**|ef54d2bf-783f-4e0f-bca1-3210c0444d99|
|**Display String**|Read and write calendars in all mailboxes|
|**Description**|Allows the app to create, read, update, and delete events of all calendars without a signed-in user.|
## Resources
### [attachment ](https://docs.microsoft.com/graph/api/resources/attachment?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|contentType|String|The MIME type.|
|id|String| Read-only.|
|isInline|Boolean|`true` if the attachment is an inline attachment; otherwise, `false`.|
|lastModifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|name|String|The attachment's file name.|
|size|Int32|The length of the attachment in bytes.|
### [attachmentItem ](https://docs.microsoft.com/graph/api/resources/attachmentitem?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|attachmentType|String| The type of attachment. Possible values are: `file`, `item`, `reference`. Required.|
|contentId|String| The CID or Content-Id of the attachment for referencing for the in-line attachments using the `<img src="cid:contentId">` tag in HTML messages. Optional.|
|contentType|String|The nature of the data in the attachment. Optional.|
|isInline|Boolean|`true` if the attachment is an inline attachment; otherwise, `false`. Optional.|
|name|String|The display name of the attachment. This can be a descriptive string and doesn't have to be the actual file name. Required.|
|size|Int64|The length of the attachment in bytes. Required.|
### [attendee ](https://docs.microsoft.com/graph/api/resources/attendee?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|emailAddress|emailAddress|Includes the name and SMTP address of the attendee.|
|proposedNewTime|timeSlot|An alternate date/time proposed by the attendee for a meeting request to start and end. If the attendee hasn't proposed another time, then this property isn't included in a response of a GET event.|
|status|ResponseStatus|The attendee's response (none, accepted, declined, etc.) for the event and date-time that the response was sent.|
|type|String|The attendee type: `required`, `optional`, `resource`.|
### [bookingAppointment ](https://docs.microsoft.com/graph/api/resources/bookingappointment?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
|additionalInformation|String|Additional information that is sent to the customer when an appointment is confirmed.|
|anonymousJoinWebUrl|String|The URL of the meeting to join anonymously.|
|appointmentLabel|String|The custom label that can be stamped on this appointment by users.|
|createdDateTime|DateTimeOffset|The date, time, and time zone when the appointment was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.	|
|customerEmailAddress|String|The SMTP address of the bookingCustomer who books the appointment.|
|customerName|String|The customer's name.|
|customerNotes|String|Notes from the customer associated with this appointment. You can get the value only when you read this **bookingAppointment** by its ID. You can set this property only when you initially create an appointment with a new customer.|
|customerPhone|String|The customer's phone number.|
|customers|bookingCustomerInformation collection|A collection of customer properties for an appointment. An appointment contains a list of customer information and each unit will indicate the properties of a customer who is part of that appointment. Optional.|
|customerTimeZone|String|The time zone of the customer. For a list of possible values, see dateTimeTimeZone.|
|duration|Duration|The length of the appointment, denoted in ISO8601 format. |
|end|dateTimeTimeZone|The date, time, and time zone when the appointment ends.|
|filledAttendeesCount|Int32|The current number of customers in the appointment.|
|id|String| The ID of the **bookingAppointment**. Read-only.|
|isCustomerAllowedToManageBooking|Boolean|Indicates that the customer can manage bookings created by the staff. The default value is `false`.|
|isLocationOnline|Boolean|Indicates that the appointment is held online. The default value is `false`.|
|joinWebUrl|String|The URL of the online meeting for the appointment.|
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the booking business was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|maximumAttendeesCount|Int32|The maximum number of customers allowed in an appointment. If **maximumAttendeesCount** of the service is greater than 1, pass valid customer IDs while creating or updating an appointment. To create a customer, use the Create bookingCustomer operation.|
|optOutOfCustomerEmail|Boolean|If `true` indicates that the bookingCustomer for this appointment doesn't wish to receive a confirmation for this appointment.|
|postBuffer|Duration|The amount of time to reserve after the appointment ends, for cleaning up, as an example. The value is expressed in ISO8601 format. |
|preBuffer|Duration|The amount of time to reserve before the appointment begins, for preparation, as an example. The value is expressed in ISO8601 format.|
|price|Double|The regular price for an appointment for the specified bookingService.|
|priceType|bookingPriceType| A setting to provide flexibility for the pricing structure of services. Possible values are: `undefined`, `fixedPrice`, `startingAt`, `hourly`, `free`, `priceVaries`, `callUs`, `notSet`, `unknownFutureValue`.|
|reminders|bookingReminder collection|The collection of customer reminders sent for this appointment. The value of this property is available only when reading this **bookingAppointment** by its ID.|
|selfServiceAppointmentId|String|Another tracking ID for the appointment, if the appointment was created directly by the customer on the scheduling page, as opposed to by a staff member on behalf of the customer.|
|serviceId|String|The ID of the bookingService associated with this appointment.|
|serviceLocation|location|The location where the service is delivered.|
|serviceName|String|The name of the **bookingService** associated with this appointment.<br>This property is optional when creating a new appointment. If not specified, it's computed from the service associated with the appointment by the **serviceId** property.|
|serviceNotes|String|Notes from a bookingStaffMember. The value of this property is available only when reading this **bookingAppointment** by its ID.|
|smsNotificationsEnabled|Boolean|If `true`, indicates SMS notifications will be sent to the customers for the appointment. Default value is `false`.|
|staffMemberIds|String collection|The ID of each bookingStaffMember who is scheduled in this appointment.|
|start|dateTimeTimeZone|The date, time, and time zone when the appointment begins.|
### [bookingStaffMember ](https://docs.microsoft.com/graph/api/resources/bookingstaffmember?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|availabilityIsAffectedByPersonalCalendar|Boolean|True means that if the staff member is a Microsoft 365 user, the Bookings API would verify the staff member's availability in their personal calendar in Microsoft 365, before making a booking. |
|createdDateTime|DateTimeOffset|The date, time, and time zone when the staff member was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|The name of the staff member, as displayed to customers. Required.|
|emailAddress|String|The email address of the staff member. This email address can be in the same Microsoft 365 tenant as the business, or in a different email domain. This email address can be used if the **sendConfirmationsToOwner** property is set to true in the scheduling policy of the business. Required.|
|id|String| The ID of the staff member, in a GUID format. Read-only.|
|isEmailNotificationEnabled|Boolean|Indicates that a staff member is notified via email when a booking assigned to them is created or changed. The default value is `true`.|
|membershipStatus|bookingStaffMembershipStatus| The membership status of the staff member in the business. Possible values are: `active`, `pendingAcceptance`, `rejectedByStaff`, `unknownFutureValue`. |
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the staff member was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|role|bookingStaffRole| The role of the staff member in the business. Possible values are: `guest`, `administrator`, `viewer`, `externalGuest`, `unknownFutureValue`, `scheduler`, `teamMember`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `scheduler`, `teamMember`. Required. |
|timeZone|String|The time zone of the staff member. For a list of possible values, see dateTimeTimeZone.|
|useBusinessHours|Boolean|True means the staff member's availability is as specified in the **businessHours** property of the business. False means the availability is determined by the staff member's **workingHours** property setting.|
|workingHours|bookingWorkHours collection|The range of hours each day of the week that the staff member is available for booking. By default, they're initialized to be the same as the **b
### [calendar ](https://docs.microsoft.com/graph/api/resources/calendar?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|allowedOnlineMeetingProviders|onlineMeetingProviderType collection| Represent the online meeting service providers that can be used to create online meetings in this calendar. Possible values are: `unknown`, `skypeForBusiness`, `skypeForConsumer`, `teamsForBusiness`.|
|canEdit |Boolean |`true` if the user can write to the calendar, `false` otherwise. This property is `true` for the user who created the calendar. This property is also `true` for a user who has been shared a calendar and granted write access. |
|canShare |Boolean |`true` if the user has the permission to share the calendar, `false` otherwise. Only the user who created the calendar can share it. |
|canViewPrivateItems |Boolean |`true` if the user can read calendar items that have been marked private, `false` otherwise. |
|changeKey|String|Identifies the version of the calendar object. Every time the calendar is changed, changeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only.|
|color|calendarColor|Specifies the color theme to distinguish the calendar from other calendars in a UI. The property values are: `auto`, `lightBlue`, `lightGreen`, `lightOrange`, `lightGray`, `lightYellow`, `lightTeal`, `lightPink`, `lightBrown`, `lightRed`, `maxColor`.|
|defaultOnlineMeetingProvider|onlineMeetingProviderType|The default online meeting provider for meetings sent from this calendar. Possible values are: `unknown`, `skypeForBusiness`, `skypeForConsumer`, `teamsForBusiness`.|
|hexColor |String |The calendar color, expressed in a hex color code of three hexadecimal values, each ranging from 00 to FF and representing the red, green, or blue components of the color in the RGB color space. If the user has never explicitly set a color for the calendar, this property is empty. Read-only.|
|id|String|The calendar's unique identifier. Read-only.|
|isDefaultCalendar|Boolean|`true` if this is the default calendar where new events are created by default, `false` otherwise.|
|isRemovable|Boolean| Indicates whether this user calendar can be deleted from the user mailbox.|
|isTallyingResponses|Boolean|Indicates whether this user calendar supports tracking of meeting responses. Only meeting invites sent from users' primary calendars support tracking of meeting responses.|
|name|String|The calendar name.|
|owner |emailAddress | If set, this represents the user who created or added the calendar. For a calendar that the user created or added, the **o
### [calendarGroup ](https://docs.microsoft.com/graph/api/resources/calendargroup?view=graph-rest-1.0&tabs=http)
| Property  | Type   | Description                                                                                                                                                                                               |
| :-------- | :----- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| name      | String | The group name.                                                                                                                                                                                           |
| changeKey | String | Identifies the version of the calendar group. Every time the calendar group is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only. |
| classId   | Guid   | The class identifier. Read-only.                                                                                                                                                                          |
| id        | String | The group's unique identifier. Read-only.                                                                                                                                                                 |
### [dateTimeTimeZone ](https://docs.microsoft.com/graph/api/resources/datetimetimezone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|dateTime|String|A single point of time in a combined date and time representation (`{date}T{time}`; for example, `2017-08-29T04:00:00.0000000`).|
|timeZone|String|Represents a time zone, for example, "Pacific Standard Time". See below for more possible values.|
### [event ](https://docs.microsoft.com/graph/api/resources/event?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
|allowNewTimeProposals| Boolean | `true` if the meeting organizer allows invitees to propose a new time when responding; otherwise, `false`. Optional. Default is `true`. |
|attendees|Attendee collection|The collection of attendees for the event.|
|body|ItemBody|The body of the message associated with the event. It can be in HTML or text format.|
|bodyPreview|String|The preview of the message associated with the event. It is in text format.|
|categories|String collection|The categories associated with the event. Each category corresponds to the **displayName** property of an outlookCategory defined for the user.|
|changeKey|String|Identifies the version of the event object. Every time the event is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|end|DateTimeTimeZone|The date, time, and time zone that the event ends. By default, the end time is in UTC.|
|hasAttachments|Boolean|Set to true if the event has attachments.|
|hideAttendees|Boolean|When set to `true`, each attendee only sees themselves in the meeting request and meeting **Tracking** list. Default is false.|
|iCalUId|String|A unique identifier for an event across calendars. This ID is different for each occurrence in a recurring series. Read-only.|
|id|String| Unique identifier for the event. !INCLUDE [outlook-beta-id] Case-sensitive and read-only.|
|importance|String|The importance of the event. The possible values are: `low`, `normal`, `high`.|
|isAllDay|Boolean|Set to true if the event lasts all day. If true, regardless of whether it's a single-day or multi-day event, start and end time must be set to midnight and be in the same time zone.|
|isCancelled|Boolean|Set to true if the event has been canceled.|
|isDraft|Boolean|Set to true if the user has updated the meeting in Outlook but has not sent the updates to attendees. Set to false if all changes have been sent, or if the event is an appointment without any attendees.|
|isOnlineMeeting|Boolean| `True` if this event has online meeting information (that is, **onlineMeeting** points to an onlineMeetingInfo resource), `false` otherwise. Default is `false` (**onlineMeeting** is `null`). Optional. <br> After you set **isOnlineMeeting** to `true`, Microsoft Graph initializes **onlineMeeting**. Subsequently Outlook ignores any further changes to **isOnlineMeeting**, and the meeting remains available online. |
|isOrganizer|Boolean|Set to true if the calendar owner (specified by the **owner** property of the calendar) is the organizer of the event (specified by the **organizer** property of the **event**). This also applies if a delegate organized the event on behalf of the owner.|
|isReminderOn|Boolean|Set to true if an alert is set to remind the user of the event.|
|lastModifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|location|Location|The location of the event.|
|locations|Location collection|The locations where the event is held or attended from. The **location** and **locations** properties always correspond with each other. If you update the **location** property, any prior locations in the **locations** collection would be removed and replaced by the new **location** value. |
|onlineMeeting|OnlineMeetingInfo| Details for an attendee to join the meeting online. Default is null. Read-only. <br>After you set the **isOnlineMeeting** and **onlineMeetingProvider** properties to enable a meeting online, Microsoft Graph initializes **onlineMeeting**. When set, the meeting remains available online, and you cannot change the **isOnlineMeeting**, **onlineMeetingProvider**, and **onlneMeeting** properties again.|
|onlineMeetingProvider|onlineMeetingProviderType| Represents the online meeting service provider. By default, **onlineMeetingProvider** is `unknown`. The possible values are `unknown`, `teamsForBusiness`, `skypeForBusiness`, and `skypeForConsumer`. Optional. <br> After you set **onlineMeetingProvider**, Microsoft Graph initializes **onlineMeeting**. Subsequently you cannot change **onlineMeetingProvider** again, and the meeting remains available online. |
|onlineMeetingUrl|String|A URL for an online meeting. The property is set only when an organizer specifies in Outlook that an event is an online meeting such as Skype. Read-only.<br>To access the URL to join an online meeting, use **joinUrl** which is exposed via the **onlineMeeting** property of the **event**. The **onlineMeetingUrl** property will be deprecated in the future. |
|organizer|Recipient|The organizer of the event.|
|originalEndTimeZone|String|The end time zone that was set when the event was created. A value of `tzone://Microsoft/Custom` indicates that a legacy custom time zone was set in desktop Outlook.|
|originalStart|DateTimeOffset|Represents the start time of an event when it is initially created as an occurrence or exception in a recurring series. This property is not returned for events that are single instances. Its date and time information is expressed in ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|originalStartTimeZone|String|The start time zone that was set when the event was created. A value of `tzone://Microsoft/Custom` indicates that a legacy custom time zone was set in desktop Outlook.|
|recurrence|PatternedRecurrence|The recurrence pattern for the event.|
|reminderMinutesBeforeStart|Int32|The number of minutes before the event start time that the reminder alert occurs.|
|responseRequested|Boolean|Default is true, which represents the organizer would like an invitee to send a response to the event.|
|responseStatus|ResponseStatus|Indicates the type of response sent in response to an event message.|
|sensitivity|String| Possible values are: `normal`, `personal`, `private`, `confidential`.|
|seriesMasterId|String|The ID for the recurring series master item, if this event is part of a recurring series.|
|showAs|String|The status to show. Possible values are: `free`, `tentative`, `busy`, `oof`, `workingElsewhere`, `unknown`.|
|start|DateTimeTimeZone|The start date, time, and time zone of the event. By default, the start time is in UTC.|
|subject|String|The text of the event's subject line.|
|transactionId|String|A custom identifier specified by a client app for the server to avoid redundant POST operations in case of client retries to create the same event. This is useful when low network connectivity causes the client to time out before receiving a response from the server for the client's prior create-event request. After you set **transactionId** when creating an event, you cannot change **transactionId** in a subsequent update. This property is only returned in a response payload if an app has set it. Optional.|
|type|String|The event type. Possible values are: `singleInstance`, `occurrence`, `exception`, `seriesMaster`. Read-only|
|webLink|String|The URL to open the event in Outlook on the web.<br/><br/>Outlook on the web opens the event in the browser if you are signed in to your mailbox. Otherwise, Outlook on the web prompts you to sign in.<br/><br/>This URL cannot be accessed from within an iFrame.|
### [itemBody ](https://docs.microsoft.com/graph/api/resources/itembody?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|content|String|The content of the item.|
|contentType|bodyType|The type of the content. Possible values are `text` and `html`.|
### [Location ](https://docs.microsoft.com/graph/api/resources/location?view=graph-rest-1.0&tabs=http)
| Property  | Type   | Description                                                     |
|:----------|:-------|:----------------------------------------------------------------|
| address | physicalAddress |The street address of the location. |
| coordinates | outlookGeoCoordinates | The geographic coordinates and elevation of the location. |
| displayName  | String | The name associated with the location.                       |
| locationEmailAddress | String | Optional email address of the location.              |
| locationUri | String | Optional URI representing the location. |
| locationType | locationType | The type of location. The possible values are: `default`, `conferenceRoom`, `homeAddress`, `businessAddress`,`geoCoordinates`, `streetAddress`, `hotel`, `restaurant`, `localBusiness`, `postalAddress`. Read-only.|
| uniqueId | String | For internal use only.|
| uniqueIdType | locationUniqueIdType | For internal use only. |
### [message ](https://docs.microsoft.com/graph/api/resources/message?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|bccRecipients|recipient collection|The Bcc: recipients for the message.|
|body|itemBody|The body of the message. It can be in HTML or text format. Find out about safe HTML in a message body.|
|bodyPreview|String|The first 255 characters of the message body. It is in text format.|
|ccRecipients|recipient collection|The Cc: recipients for the message.|
|changeKey|String|The version of the message.|
|conversationId|String|The ID of the conversation the email belongs to.|
|conversationIndex|Edm.Binary|Indicates the position of the message within the conversation.|
|createdDateTime|DateTimeOffset|The date and time the message was created. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|flag|followupFlag|The flag value that indicates the status, start date, due date, or completion date for the message.|
|from|recipient|The owner of the mailbox from which the message is sent. In most cases, this value is the same as the **sender** property, except for sharing or delegation scenarios. The value must correspond to the actual mailbox used. Find out more about setting the from and sender properties of a message.|
|hasAttachments|Boolean|Indicates whether the message has attachments. This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false. To verify the existence of inline attachments, parse the **body** property to look for a `src` attribute, such as `<IMG src="cid:image001.jpg@01D26CD8.6C05F070">`.|
|id|String|Unique identifier for the message. !INCLUDE [outlook-beta-id] Read-only. |
|importance|importance| The importance of the message. The possible values are: `low`, `normal`, and `high`.|
|inferenceClassification | inferenceClassificationType | The classification of the message for the user, based on inferred relevance or importance, or on an explicit override. The possible values are: `focused` or `other`. |
|internetMessageHeaders | internetMessageHeader collection | A collection of message headers defined by RFC5322. The set includes message headers indicating the network path taken by a message from the sender to the recipient. It can also contain custom message headers that hold app data for the message. <br><br> Returned only on applying a `$select` query option. Read-only. |
|internetMessageId |String |The message ID in the format specified by RFC2822. |
|isDeliveryReceiptRequested|Boolean|Indicates whether a read receipt is requested for the message.|
|isDraft|Boolean|Indicates whether the message is a draft. A message is a draft if it hasn't been sent yet.|
|isRead|Boolean|Indicates whether the message has been read.|
|isReadReceiptRequested|Boolean|Indicates whether a read receipt is requested for the message.|
|lastModifiedDateTime|DateTimeOffset|The date and time the message was last changed. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|parentFolderId|String|The unique identifier for the message's parent mailFolder.|
|receivedDateTime|DateTimeOffset|The date and time the message was received. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|replyTo|recipient collection|The email addresses to use when replying.|
|sender|recipient|The account that is actually used to generate the message. In most cases, this value is the same as the **from** property. You can set this property to a different value when sending a message from a shared mailbox, for a shared calendar, or as a delegate. In any case, the value must correspond to the actual mailbox used. Find out more about setting the from and sender properties of a message.|
|sentDateTime|DateTimeOffset|The date and time the message was sent. <br><br> The date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|subject|String|The subject of the message.|
|toRecipients|recipient collection|The To: recipients for the message.|
|uniqueBody|itemBody|The part of the body of the message that is unique to the current message. **uniqueBody** is not returned by default but can be retrieved for a given message by use of the `?$select=uniqueBody` query. It can be in HTML or text format.|
|webLink|String|The URL to open the message in Outlook on the web.<br><br>You can append an ispopout argument to the end of the URL to change how the message is displayed. If ispopout is not present or if it is set to 1, then the message is shown in a popout window. If ispopout is set to 0, the browser shows the message in the Outlook on the web review pane.<br><br>The message opens in the browser if you are signed in to your mailbox via Outlook on the web. You are prompted to sign in if you are not already signed in with the browser.<br><br>This URL cannot be accessed from within an iFrame.|
### [patternedRecurrence ](https://docs.microsoft.com/graph/api/resources/patternedrecurrence?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|pattern|recurrencePattern|The frequency of an event. <br/><br/> For access reviews: <li>Do not specify this property for a one-time access review. <li> Only **interval**, **dayOfMonth**, and **type** (`weekly`, `absoluteMonthly`) properties of recurrencePattern are supported.|
|range|recurrenceRange|The duration of an event.|
### [reminder ](https://docs.microsoft.com/graph/api/resources/reminder?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|changeKey|String|Identifies the version of the reminder. Every time the reminder is changed, **changeKey** changes as well. This allows Exchange to apply changes to the correct version of the object.|
|eventEndTime|DateTimeTimeZone|The date, time and time zone that the event ends.|
|eventId|String|The unique ID of the event. Read only.|
|eventLocation|Location|The location of the event.|
|eventStartTime|DateTimeTimeZone|The date, time, and time zone that the event starts.|
|eventSubject|String|The text of the event's subject line.|
|eventWebLink|String|The URL to open the event in Outlook on the web.<br/><br/>The event opens in the browser if you're logged in to your mailbox via Outlook on the web. You're prompted to log in if you aren't already logged in with the browser.<br/><br/>This URL can't be accessed from within an iFrame.|
|reminderFireTime|DateTimeTimeZone|The date, time, and time zone that the reminder is set to occur.|
### [scheduleInformation ](https://docs.microsoft.com/graph/api/resources/scheduleinformation?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|availabilityView |String |Represents a merged view of availability of all the items in `scheduleItems`. The view consists of time slots. Availability during each time slot is indicated with: `0`= free or working elswhere, `1`= tentative, `2`= busy, `3`= out of office.<br><br>**Note:** Working elsewhere is set to `0` instead of `4` for backward compatibility. For details, see the Q&A.|
|error |freeBusyError |Error information from attempting to get the availability of the user, distribution list, or resource. |
|scheduleId |String |An SMTP address of the user, distribution list, or resource, identifying an instance of **scheduleInformation**. |
|scheduleItems |scheduleItem collection |Contains the items that describe the availability of the user or resource. |
|workingHours |workingHours |The days of the week and hours in a specific time zone that the user works. These are set as part of the user's mailboxSettings.|
### [staffAvailabilityItem ](https://docs.microsoft.com/graph/api/resources/staffavailabilityitem?view=graph-rest-1.0&tabs=http)
| Property  | Type |Description|
|:---------------|:--------|:----------|
|availabilityItems |availabilityItem collection |Each item in this collection indicates a slot and the status of the staff member.|
|staffId |String |The ID of the staff member.|
### [timeSlot ](https://docs.microsoft.com/graph/api/resources/timeslot?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|end|dateTimeTimeZone|The date, time, and time zone that a period ends. |
|start|dateTimeTimeZone|The date, time, and time zone that a period begins.|
### [uploadSession ](https://docs.microsoft.com/graph/api/resources/uploadsession?view=graph-rest-1.0&tabs=http)
| Property	     | Type              |Description
|:-------------------|:------------------|:------------------------------------
| expirationDateTime | DateTimeOffset    | The date and time in UTC that the upload session will expire. The complete file must be uploaded before this expiration time is reached.|
| nextExpectedRanges | String collection | A collection of byte ranges that the server is missing for the file. These ranges are zero indexed and of the format "start-end" (for example "0-26" to indicate the first 27 bytes of the file). When uploading files as Outlook attachments, instead of a collection of ranges, this property always indicates a single value "{start}", the location in the file where the next upload should begin.|
| uploadUrl          | String            | The URL endpoint that accepts PUT requests for byte ranges of the file.|
### [user ](https://docs.microsoft.com/graph/api/resources/user?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|aboutMe|String|A freeform text entry field for the user to describe themselves. Returned only on `$select`.|
|accountEnabled|Boolean| `true` if the account is enabled; otherwise, `false`. This property is required when a user is created. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).    |
|ageGroup|ageGroup|Sets the age group of the user. Allowed values: `null`, `Minor`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|assignedLicenses|assignedLicense collection|The licenses that are assigned to the user, including inherited (group-based) licenses. This property doesn't differentiate between directly assigned and inherited licenses. Use the **licenseAssignmentStates** property to identify the directly assigned and inherited licenses. Not nullable. Returned only on `$select`. Supports `$filter` (`eq`, `not`, `/$count eq 0`, `/$count ne 0`).           |
|assignedPlans|assignedPlan collection|The plans that are assigned to the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq` and `not`). |
|birthday|DateTimeOffset|The birthday of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|businessPhones|String collection|The telephone numbers for the user. NOTE: Although it's a string collection, only one number can be set for this property. Read-only for users synced from the on-premises directory. <br><br>Returned by default. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|city|String|The city where the user is located. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|companyName | String | The name of the company that the user is associated with. This property can be useful for describing the company that a guest comes from. The maximum length is 64 characters.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|consentProvidedForMinor|consentProvidedForMinor|Sets whether consent was obtained for minors. Allowed values: `null`, `Granted`, `Denied`, and `NotRequired`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, and `in`).|
|country|String|The country/region where the user is located; for example, `US` or `UK`. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|createdDateTime | DateTimeOffset |The date and time the user was created, in ISO 8601 format and UTC. The value can't be modified and is automatically populated when the entity is created. Nullable. For on-premises users, the value represents when they were first created in Microsoft Entra ID. Property is `null` for some users created before June 2018 and on-premises users that were synced to Microsoft Entra ID before June 2018. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| creationType | String | Indicates whether the user account was created through one of the following methods: <br/> <ul><li>As a regular school or work account (`null`). <li>As an external account (`Invitation`). <li>As a local account for an Azure Active Directory B2C tenant (`LocalAccount`). <li>Through self-service sign-up by an internal user using email verification (`EmailVerified`). <li>Through self-service sign-up by a guest signing up through a link that is part of a user flow (`SelfServiceSignUp`).</ul> <br>Read-only.<br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|customSecurityAttributes|customSecurityAttributeValue|An open complex type that holds the value of a custom security attribute that is assigned to a directory object. Nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `startsWith`). The filter value is case-sensitive.|
|deletedDateTime| DateTimeOffset | The date and time the user was deleted. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`). |
|department|String|The name of the department in which the user works. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, and `eq` on `null` values).|
|displayName|String|The name displayed in the address book for the user. This value is usually the combination of the user's first name, middle initial, and family name. This property is required when a user is created and it can't be cleared during updates. Maximum length is 256 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values), `$orderby`, and `$search`.|
| employeeHireDate | DateTimeOffset |The date and time when the user was hired or will start work in a future hire. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeLeaveDateTime | DateTimeOffset | The date and time when the user left or will leave the organization. <br><br>To read this property, the calling app must be assigned the *User-LifeCycleInfo.Read.All* permission. To write this property, the calling app must be assigned the *User.Read.All* and *User-LifeCycleInfo.ReadWrite.All* permissions. To read this property in delegated scenarios, the admin needs at least one of the following Microsoft Entra roles: *Lifecycle Workflows Administrator*, *Global Reader*. To write this property in delegated scenarios, the admin needs the *Global Administrator* role. <br><br>Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`). <br><br>For more information, see Configure the employeeLeaveDateTime property for a user.|
| employeeId | String | The employee identifier assigned to the user by the organization. The maximum length is 16 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|employeeOrgData|employeeOrgData |Represents organization data (for example, division and costCenter) associated with a user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`).|
| employeeType | String | Captures enterprise worker type. For example, `Employee`, `Contractor`, `Consultant`, or `Vendor`. Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`).|
|externalUserState|String|For a guest invited to the tenant using the invitation API, this property represents the invited user's invitation status. For invited users, the state can be `PendingAcceptance` or `Accepted`, or `null` for all other users. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|externalUserStateChangeDateTime|DateTimeOffset|Shows the timestamp for the latest change to the **externalUserState** property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `in`).|
|faxNumber|String|The fax number of the user. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|givenName|String|The given name (first name) of the user. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| hireDate | DateTimeOffset | The hire date of the user. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014, is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`. <br> **Note:** This property is specific to SharePoint in Microsoft 365. We recommend using the native **employeeHireDate** property to set and update hire date values using Microsoft Graph APIs. |
|id|String|The unique identifier for the user. Should be treated as an opaque identifier. Inherited from directoryObject. Key. Not nullable. Read-only. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `in`).|
|identities|objectIdentity collection| Represents the identities that can be used to sign in to this user account. Microsoft (also known as a local account), organizations, or social identity providers such as Facebook, Google, and Microsoft can provide identity and tie it to a user account. It might contain multiple items with the same **signInType** value. <br><br>Returned only on `$select`. <br><br> Supports `$filter` (`eq`) with limitations. <!--Supports `$filter` (`eq`) including on `null` values, only where the **signInType** is not `userPrincipalName`.-->|
|imAddresses|String collection|The instant message voice-over IP (VOIP) session initiation protocol (SIP) addresses for the user. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`).|
|interests|String collection|A list for the user to describe their interests. <br><br>Returned only on `$select`.|
|isResourceAccount|Boolean| Don't use – reserved for future use.|
|jobTitle|String|The user's job title. Maximum length is 128 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not` , `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|lastPasswordChangeDateTime| DateTimeOffset | The time when this Microsoft Entra user last changed their password or when their password was created, whichever date the latest action was performed. The date and time information uses ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. <br><br>Returned only on `$select`.|
|legalAgeGroupClassification|legalAgeGroupClassification| Used by enterprise applications to determine the legal age group of the user. This property is read-only and calculated based on **ageGroup** and **consentProvidedForMinor** properties. Allowed values: `null`, `MinorWithOutParentalConsent`, `MinorWithParentalConsent`, `MinorNoParentalConsentRequired`, `NotAdult`, and `Adult`. For more information, see legal age group property definitions. <br><br>Returned only on `$select`.|
|licenseAssignmentStates|licenseAssignmentState collection|State of license assignments for this user. Also indicates licenses that are directly assigned or the user inherited through group memberships. Read-only. <br><br>Returned only on `$select`.|
|mail|String|The SMTP address for the user, for example, `jeff@contoso.com`. Changes to this property update the user's **proxyAddresses** collection to include the value as an SMTP address. This property can't contain accent characters. <br/> **NOTE:** We don't recommend updating this property for Azure AD B2C user profiles. Use the **otherMails** property instead. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, and `eq` on `null` values).|
|mailboxSettings|mailboxSettings|Settings for the primary mailbox of the signed-in user. You can get or update settings for sending automatic replies to incoming messages, locale, and time zone. <br><br>Returned only on `$select`.|
|mailNickname|String|The mail alias for the user. This property must be specified when a user is created. Maximum length is 64 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|mobilePhone|String|The primary cellular telephone number for the user. Read-only for users synced from the on-premises directory. Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values) and `$search`. |
|mySite|String|The URL for the user's site. <br><br>Returned only on `$select`.|
|officeLocation|String|The office location in the user's place of business. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|onPremisesDistinguishedName|String| Contains the on-premises Active Directory `distinguished name` or `DN`. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. |
|onPremisesDomainName|String| Contains the on-premises `domainFQDN`, also called dnsDomainName synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`.|
|onPremisesExtensionAttributes|onPremisesExtensionAttributes|Contains extensionAttributes1-15 for the user. These extension attributes are also known as Exchange custom attributes 1-15. <br><li>For an **onPremisesSyncEnabled** user, the source of authority for this set of properties is the on-premises and is read-only. </li><li>For a cloud-only user (where **onPremisesSyncEnabled** is `false`), these properties can be set during the creation or update of a user object.  </li><li>For a cloud-only user previously synced from on-premises Active Directory, these properties are read-only in Microsoft Graph but can be fully managed through the Exchange Admin Center or the Exchange Online V2 module in PowerShell.</li><br> Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`). |
|onPremisesImmutableId|String|This property is used to associate an on-premises Active Directory user account to their Microsoft Entra user object. This property must be specified when creating a new user account in the Graph if you're using a federated domain for the user's **userPrincipalName** (UPN) property. **NOTE:** The **$** and **\_** characters can't be used when specifying this property. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).                            |
|onPremisesLastSyncDateTime|DateTimeOffset|Indicates the last time at which the object was synced with the on-premises directory; for example: `2013-02-16T03:04:54Z`. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).|
|onPremisesProvisioningErrors|onPremisesProvisioningError collection| Errors when using Microsoft synchronization product during provisioning. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|onPremisesSamAccountName|String| Contains the on-premises `samAccountName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|onPremisesSecurityIdentifier|String|Contains the on-premises security identifier (SID) for the user that was synchronized from on-premises to the cloud. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq` including on `null` values). |
|onPremisesSyncEnabled|Boolean| `true` if this user object is currently being synced from an on-premises Active Directory (AD); otherwise the user isn't being synced and can be managed in Microsoft Entra ID. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|onPremisesUserPrincipalName|String| Contains the on-premises `userPrincipalName` synchronized from the on-premises directory. The property is only populated for customers who are synchronizing their on-premises directory to Microsoft Entra ID via Microsoft Entra Connect. Read-only. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`).|
|otherMails|String collection| A list of other email addresses for the user; for example: `["bob@contoso.com", "Robert@fabrikam.com"]`. <br>NOTE: This property can't contain accent characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|passwordPolicies|String|Specifies password policies for the user. This value is an enumeration with one possible value being `DisableStrongPassword`, which allows weaker passwords than the default policy to be specified. `DisablePasswordExpiration` can also be specified. The two might be specified together; for example: `DisablePasswordExpiration, DisableStrongPassword`. <br><br>Returned only on `$select`. For more information on the default password policies, see Microsoft Entra password policies. Supports `$filter` (`ne`, `not`, and `eq` on `null` values).|
|passwordProfile|passwordProfile|Specifies the password profile for the user. The profile contains the user's password. This property is required when a user is created. The password in the profile must satisfy minimum requirements as specified by the **passwordPolicies** property. By default, a strong password is required. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values).|
|pastProjects|String collection|A list for the user to enumerate their past projects. <br><br>Returned only on `$select`.|
|postalCode|String|The postal code for the user's postal address. The postal code is specific to the user's country/region. In the United States of America, this attribute contains the ZIP code. Maximum length is 40 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
| preferredDataLocation | String | The preferred data location for the user. For more information, see OneDrive Online Multi-Geo.|
|preferredLanguage|String|The preferred language for the user. The preferred language format is based on RFC 4646. The name is a combination of an ISO 639 two-letter lowercase culture code associated with the language, and an ISO 3166 two-letter uppercase subculture code associated with the country or region. Example: "en-US", or "es-ES". <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values)|
|preferredName|String|The preferred name for the user. **Not Supported. This attribute returns an empty string.**<br><br>Returned only on `$select`.|
|provisionedPlans|provisionedPlan collection|The plans that are provisioned for the user. Read-only. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`).|
|proxyAddresses|String collection|For example: `"SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com"]`. Changes to the **mail** property update this collection to include the value as an SMTP address. For more information, see [mail and proxyAddresses properties. The proxy address prefixed with `SMTP` (capitalized) is the primary proxy address, while those addresses prefixed with `smtp` are the secondary proxy addresses. For Azure AD B2C accounts, this property has a limit of 10 unique addresses. Read-only in Microsoft Graph; you can update this property only through the Microsoft 365 admin center. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `endsWith`, `/$count eq 0`, `/$count ne 0`).|
|refreshTokensValidFromDateTime|DateTimeOffset|Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. <br><br>Returned only on `$select`. Read-only. |
|responsibilities|String collection|A list for the user to enumerate their responsibilities. <br><br>Returned only on `$select`.|
| serviceProvisioningErrors    | serviceProvisioningError collection       | Errors published by a federated service describing a nontransient, service-specific error regarding the properties or link from a user object. <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance).  |
|schools|String collection|A list for the user to enumerate the schools they attended. <br><br>Returned only on `$select`.|
|securityIdentifier| String | Security identifier (SID) of the user, used in Windows scenarios. <br><br>Read-only. Returned by default. <br>Supports `$select` and `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`). |
|showInAddressList|Boolean|**Do not use in Microsoft Graph. Manage this property through the Microsoft 365 admin center instead.** Represents whether the user should be included in the Outlook global address list. See Known issue.|
|signInActivity | signInActivity | Get the last signed-in date and request ID of the sign-in for a given user. Read-only.<br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`) *but not with any other filterable properties*. <br><br>**Note:** <br/><li>Details for this property require a Microsoft Entra ID P1 or P2 license and the **AuditLog.Read.All** permission.<li>This property isn't returned for a user who never signed in or last signed in before April 2020.|
|signInSessionsValidFromDateTime|DateTimeOffset| Any refresh tokens or session tokens (session cookies) issued before this time are invalid. Applications get an error when using an invalid refresh or session token to acquire a delegated access token (to access APIs such as Microsoft Graph). If this happens, the application needs to acquire a new refresh token by requesting the authorized endpoint. Read-only. Use revokeSignInSessions to reset. <br><br>Returned only on `$select`.|
|skills|String collection|A list for the user to enumerate their skills. <br><br>Returned only on `$select`.|
|state|String|The state or province in the user's address. Maximum length is 128 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|streetAddress|String|The street address of the user's place of business. Maximum length is 1,024 characters. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|surname|String|The user's surname (family name or last name). Maximum length is 64 characters. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|usageLocation|String|A two-letter country code (ISO standard 3166). Required for users that are assigned licenses due to legal requirements to check for availability of services in countries. Examples include: `US`, `JP`, and `GB`. Not nullable. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` on `null` values).|
|userPrincipalName|String|The user principal name (UPN) of the user. The UPN is an Internet-style sign-in name for the user based on the Internet standard RFC 822. By convention, this value should map to the user's email name. The general format is alias@domain, where the domain must be present in the tenant's collection of verified domains. This property is required when a user is created. The verified domains for the tenant can be accessed from the **verifiedDomains** property of organization.<br>NOTE: This property can't contain accent characters. Only the following characters are allowed `A - Z`, `a - z`, `0 - 9`, ` ' . - _ ! # ^ ~`. For the complete list of allowed characters, see username policies. <br><br>Returned by default. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, `endsWith`) and `$orderby`.
|userType|String|A string value that can be used to classify user types in your directory. The possible values are `Member` and `Guest`. <br><br>Returned only on `$select`. Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` on `null` values). **N
