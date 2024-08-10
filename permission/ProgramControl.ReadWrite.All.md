# ProgramControl.ReadWrite.All

> Allows the app to read, update, delete and perform actions on programs and program controls that the signed-in user has access to in the organization.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[DELETE /programControls/{id}](https://docs.microsoft.com/graph/api/programcontrol-delete?view=graph-rest-beta&tabs=http)|
|Beta|D|[DELETE /programs/{id}](https://docs.microsoft.com/graph/api/program-delete?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programControls](https://docs.microsoft.com/graph/api/programcontrol-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programControlTypes](https://docs.microsoft.com/graph/api/programcontroltype-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programs](https://docs.microsoft.com/graph/api/program-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programs/{programId}/controls](https://docs.microsoft.com/graph/api/program-listcontrols?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /programs/{programId}](https://docs.microsoft.com/graph/api/program-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /programControls](https://docs.microsoft.com/graph/api/programcontrol-create?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /programs](https://docs.microsoft.com/graph/api/program-create?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|50fd364f-9d93-4ae1-b170-300e87cccf84|
|**Consent Type**|Admin|
|**Display String**|Manage all programs that user can access|
|**Description**|Allows the app to read, update, delete and perform actions on programs and program controls that the signed-in user has access to in the organization.|
## Application Permission
|||
|-|-|
|**Id**|60a901ed-09f7-4aa5-a16e-7dd3d6f9de36|
|**Display String**|Manage all programs|
|**Description**|Allows the app to read, update, delete and perform actions on programs and program controls in the organization, without a signed-in user.|
## Resources
### [accessreviews-root](https://docs.microsoft.com/graph/api/resources/accessreviews-root?view=graph-rest-1.0&tabs=http)

### [program](https://docs.microsoft.com/graph/api/resources/program?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
| id                        |String                              |  The feature-assigned identifier of the program.                    |
| displayName               |String                              |  The name of the program.  Required on create.                  |
| description               |String                              |  The description of the program.           |
### [programcontrol](https://docs.microsoft.com/graph/api/resources/programcontrol?view=graph-rest-1.0&tabs=http)
| Property | Type    | Description |
|:-------- |:---- |:----------- |
| id | String | The feature-assigned identifier of the link between program and control. |
| programId | String | The programId of the program this control is a part of. Required on create. |
| controlId | String | The controlId of the control, in particular the identifier of an access review. Required on create. |
| controlTypeId | String | The programControlType identifies the type of program control - for example, a control linking to guest access reviews. Required on create. |
| displayName | String | The name of the control. |
| status | String | The life cycle status of the control. |
| createdDateTime | DateTimeOffset | The creation date and time of the program control. |
| owner | userIdentity | The user who created the program control. |
| resource | programResource | The resource, a group or an app, targeted by this program control's access review. |
### [programcontroltype](https://docs.microsoft.com/graph/api/resources/programcontroltype?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
| id                     |String                | The feature-assigned identifier of the program control type                                      |
| displayName            |String                | The name of the program control type                                                             |
