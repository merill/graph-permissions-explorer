# VirtualAppointment.Read

> Allows an application to read virtual appointments for the signed-in user. Only an organizer or participant user can read their virtual appointments.  
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/onlineMeetings/{onlineMeetingId}/getVirtualAppointmentJoinWebUrl](https://docs.microsoft.com/graph/api/virtualappointment-getvirtualappointmentjoinweburl?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{userId}/onlineMeetings/{onlineMeetingId}/getVirtualAppointmentJoinWebUrl](https://docs.microsoft.com/graph/api/virtualappointment-getvirtualappointmentjoinweburl?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|27470298-d3b8-4b9c-aad4-6334312a3eac|
|**Consent Type**|Admin|
|**Display String**|Read a user's virtual appointments|
|**Description**|Allows an application to read virtual appointments for the signed-in user. Only an organizer or participant user can read their virtual appointments.  |
