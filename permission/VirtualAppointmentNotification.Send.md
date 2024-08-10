# VirtualAppointmentNotification.Send

> Allows an application to send notifications for virtual appointments for the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[POST /me/onlineMeetings/{onlineMeetingId}/sendVirtualAppointmentReminderSms](https://docs.microsoft.com/graph/api/virtualappointment-sendvirtualappointmentremindersms?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/onlineMeetings/{onlineMeetingId}/sendVirtualAppointmentSms](https://docs.microsoft.com/graph/api/virtualappointment-sendvirtualappointmentsms?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/onlineMeetings/{onlineMeetingId}/sendVirtualAppointmentReminderSms](https://docs.microsoft.com/graph/api/virtualappointment-sendvirtualappointmentremindersms?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/onlineMeetings/{onlineMeetingId}/sendVirtualAppointmentSms](https://docs.microsoft.com/graph/api/virtualappointment-sendvirtualappointmentsms?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|20d02fff-a0ef-49e7-a46e-019d4a6523b7|
|**Consent Type**|Admin|
|**Display String**|Send notification regarding virtual appointments for the signed-in user|
|**Description**|Allows an application to send notifications for virtual appointments for the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|97e45b36-1250-48e4-bd70-2df6dab7e94a|
|**Display String**|Send notification regarding virtual appointments as any user|
|**Description**|Allows the application to send notification regarding virtual appointments as any user, without a signed-in user. The app must also be authorized to access an individual user's data by the online meetings application access policy.|
## Resources
### [attendeeNotificationInfo ](https://docs.microsoft.com/graph/api/resources/attendeenotificationinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|phoneNumber|String|The phone number of the external attendee. Required.|
|timeZone|String|The time zone of the external attendee. The timeZone property can be set to any of the time zones currently supported by Windows. Required.|
### [remindbeforetimeinminutestype](https://docs.microsoft.com/graph/api/resources/remindbeforetimeinminutestype?view=graph-rest-1.0&tabs=http)

### [virtualappointmentmessagetype](https://docs.microsoft.com/graph/api/resources/virtualappointmentmessagetype?view=graph-rest-1.0&tabs=http)

