# ProgramControl.Read.All

> Allows the app to read programs and program controls that the signed-in user has access to in the organization.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /programControls](https://docs.microsoft.com/graph/api/programcontrol-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programControlTypes](https://docs.microsoft.com/graph/api/programcontroltype-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programs](https://docs.microsoft.com/graph/api/program-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /programs/{programId}/controls](https://docs.microsoft.com/graph/api/program-listcontrols?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c492a2e1-2f8f-4caa-b076-99bbf6e40fe4|
|**Consent Type**|Admin|
|**Display String**|Read all programs that user can access|
|**Description**|Allows the app to read programs and program controls that the signed-in user has access to in the organization.|
## Application Permission
|||
|-|-|
|**Id**|eedb7fdd-7539-4345-a38b-4839e4a84cbd|
|**Display String**|Read all programs|
|**Description**|Allows the app to read programs and program controls in the organization, without a signed-in user.|
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
