# VirtualAppointment.ReadWrite

> Allows an application to read and write virtual appointments for the signed-in user. Only an organizer or participant user can read and write their virtual appointments. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/onlineMeetings/{onlineMeetingId}/getVirtualAppointmentJoinWebUrl](https://docs.microsoft.com/graph/api/virtualappointment-getvirtualappointmentjoinweburl?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{userId}/onlineMeetings/{onlineMeetingId}/getVirtualAppointmentJoinWebUrl](https://docs.microsoft.com/graph/api/virtualappointment-getvirtualappointmentjoinweburl?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|2ccc2926-a528-4b17-b8bb-860eed29d64c|
|**Consent Type**|Admin|
|**Display String**|Read and write a user's virtual appointments  |
|**Description**|Allows an application to read and write virtual appointments for the signed-in user. Only an organizer or participant user can read and write their virtual appointments. |
