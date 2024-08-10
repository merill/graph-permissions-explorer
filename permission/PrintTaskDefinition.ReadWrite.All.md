# PrintTaskDefinition.ReadWrite.All

> Allows the application to read and update print task definitions without a signed-in user. 
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[DELETE /print/taskDefinitions/{id}](https://docs.microsoft.com/graph/api/print-delete-taskdefinition?view=graph-rest-beta&tabs=http)|
|V1|A|[DELETE /print/taskDefinitions/{printTaskDefinitionId}](https://docs.microsoft.com/graph/api/print-delete-taskdefinition?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /print/taskDefinitions](https://docs.microsoft.com/graph/api/print-list-taskdefinitions?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /print/taskDefinitions/{id}](https://docs.microsoft.com/graph/api/printtaskdefinition-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /print/taskDefinitions/{id}/tasks](https://docs.microsoft.com/graph/api/printtaskdefinition-list-tasks?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /print/taskDefinitions/{id}/tasks/{id}](https://docs.microsoft.com/graph/api/printtask-get?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /print/taskDefinitions/{printTaskDefinitionId}](https://docs.microsoft.com/graph/api/printtaskdefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /print/taskDefinitions/{taskDefinitionId}/tasks](https://docs.microsoft.com/graph/api/printtaskdefinition-list-tasks?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /print/taskDefinitions/{taskDefinitionId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/printtask-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[PATCH /print/taskDefinitions/{id}](https://docs.microsoft.com/graph/api/print-update-taskdefinition?view=graph-rest-beta&tabs=http)|
|Beta|A|[PATCH /print/taskDefinitions/{id}/tasks/{id}](https://docs.microsoft.com/graph/api/printtaskdefinition-update-task?view=graph-rest-beta&tabs=http)|
|V1|A|[PATCH /print/taskDefinitions/{printTaskDefinitionId}](https://docs.microsoft.com/graph/api/print-update-taskdefinition?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /print/taskDefinitions/{taskDefinitionId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/printtaskdefinition-update-task?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /print/taskDefinitions](https://docs.microsoft.com/graph/api/print-post-taskdefinitions?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|456b71a7-0ee0-4588-9842-c123fcc8f664|
|**Display String**|Read, write and update print task definitions|
|**Description**|Allows the application to read and update print task definitions without a signed-in user. |
## Resources
### [printTask ](https://docs.microsoft.com/graph/api/resources/printtask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The printTask's identifier. Read-only.|
|status|printTaskStatus|The current execution status of this printTask. **The calling application is responsible for updating this status when processing is finished, unless the related printJob has been redirected to another printer.** Failure to report completion will result in the related print job being blocked from printing and eventually deleted. |
|parentUrl|String|The URL for the print entity that triggered this task. For example, `https://graph.microsoft.com/v1.0/print/printers/{printerId}/jobs/{jobId}`. Read-only.|
### [printTaskDefinition ](https://docs.microsoft.com/graph/api/resources/printtaskdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|appIdentity|The application that created the printTaskDefinition. Read-only.|
|displayName|String|The name of the printTaskDefinition.|
|id|String|The printTaskDefinition's identifier. Read-only.|
