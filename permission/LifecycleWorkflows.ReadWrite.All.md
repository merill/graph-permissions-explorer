# LifecycleWorkflows.ReadWrite.All

> Allows the app to create, update, list, read and delete all workflows, tasks and related lifecycle workflows resources on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/identitygovernance-workflow-createnewversion?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/lifecycleWorkflows/customTaskExtensions/{customTaskExtensionId}/](https://docs.microsoft.com/graph/api/identitygovernance-customtaskextension-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/lifecycleWorkflows/deletedItems/workflows/{workflowId}/](https://docs.microsoft.com/graph/api/identitygovernance-deleteditemcontainer-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/](https://docs.microsoft.com/graph/api/identitygovernance-workflow-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/customTaskExtensions](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-list-customtaskextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/customTaskExtensions/{customTaskExtensionId}](https://docs.microsoft.com/graph/api/identitygovernance-customtaskextension-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/deletedItems/workflows/](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-list-deleteditems?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/deletedItems/workflows/{workflowId}/](https://docs.microsoft.com/graph/api/identitygovernance-deleteditemcontainer-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/settings](https://docs.microsoft.com/graph/api/identitygovernance-lifecyclemanagementsettings-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/taskDefinitions](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-list-taskdefinitions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/taskDefinitions/{taskDefinitionId}](https://docs.microsoft.com/graph/api/identitygovernance-taskdefinition-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-list-workflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflow_id}/runs/{runId}/userProcessingResults/{userProcessingResultId}](https://docs.microsoft.com/graph/api/identitygovernance-userprocessingresult-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflow-id}/userProcessingResults](https://docs.microsoft.com/graph/api/identitygovernance-workflow-list-userprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}](https://docs.microsoft.com/graph/api/identitygovernance-workflow-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identitygovernance/lifecycleWorkflows/workflows/{workflowId}/executionScope](https://docs.microsoft.com/graph/api/workflow-list-executionscope?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/runs/](https://docs.microsoft.com/graph/api/identitygovernance-workflow-list-runs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/runs/{runId}](https://docs.microsoft.com/graph/api/identitygovernance-run-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/runs/{runId}/taskProcessingResults](https://docs.microsoft.com/graph/api/identitygovernance-run-list-taskprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/runs/{runId}/userProcessingResults/](https://docs.microsoft.com/graph/api/identitygovernance-run-list-userprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/runs/{runId}/userProcessingResults/{userProcessingResultId}/taskProcessingResults](https://docs.microsoft.com/graph/api/identitygovernance-userprocessingresult-list-taskprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/runs/summary(startDateTime={timestamp},endDateTime={timestamp})](https://docs.microsoft.com/graph/api/identitygovernance-run-summary?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/taskReports](https://docs.microsoft.com/graph/api/identitygovernance-workflow-list-taskreports?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/taskReports/{taskReportId}/taskProcessingResults](https://docs.microsoft.com/graph/api/identitygovernance-taskreport-list-taskprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/taskReports/summary(startDateTime={timestamp},endDateTime={timestamp})](https://docs.microsoft.com/graph/api/identitygovernance-taskreport-summary?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/tasks](https://docs.microsoft.com/graph/api/identitygovernance-workflow-list-task?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/userProcessingResults/{userProcessingResultId}/taskProcessingResults](https://docs.microsoft.com/graph/api/identitygovernance-userprocessingresult-list-taskprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/userProcessingResults/summary(startDateTime={TimeStamp},endDateTime={TimeStamp})](https://docs.microsoft.com/graph/api/identitygovernance-userprocessingresult-summary?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions](https://docs.microsoft.com/graph/api/identitygovernance-workflow-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions/{workflowVersion-versionNumber}](https://docs.microsoft.com/graph/api/identitygovernance-workflowversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions/{workflowVersion-versionNumber}/tasks](https://docs.microsoft.com/graph/api/identitygovernance-workflowversion-list-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions/{workFlowVersion-versionNumber}/tasks](https://docs.microsoft.com/graph/api/identitygovernance-workflowversion-list-tasks?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflowTemplates](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-list-workflowtemplates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflowTemplates/{workflowTemplateId}](https://docs.microsoft.com/graph/api/identitygovernance-workflowtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/lifecycleWorkflows/customTaskExtensions/{customTaskExtensionId}](https://docs.microsoft.com/graph/api/identitygovernance-customtaskextension-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/lifecycleWorkflows/settings](https://docs.microsoft.com/graph/api/identitygovernance-lifecyclemanagementsettings-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/lifecycleWorkflows/workflows/{workflowId}](https://docs.microsoft.com/graph/api/identitygovernance-workflow-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/identitygovernance-task-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/lifecycleWorkflows/customTaskExtensions](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-post-customtaskextensions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/lifecycleWorkflows/deletedItems/workflows/{workflowId}/restore](https://docs.microsoft.com/graph/api/identitygovernance-workflow-restore?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/lifecycleWorkflows/workflows](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-post-workflows?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/activate](https://docs.microsoft.com/graph/api/identitygovernance-workflow-activate?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/createNewVersion](https://docs.microsoft.com/graph/api/identitygovernance-workflow-createnewversion?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/tasks/{taskId}/taskProcessingResults/{taskProcessingResultsId}/resume](https://docs.microsoft.com/graph/api/identitygovernance-taskprocessingresult-resume?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|84b9d731-7db8-4454-8c90-fd9e95350179|
|**Consent Type**|Admin|
|**Display String**|Read and write all lifecycle workflows resources|
|**Description**|Allows the app to create, update, list, read and delete all workflows, tasks and related lifecycle workflows resources on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|5c505cf4-8424-4b8e-aa14-ee06e3bb23e3|
|**Display String**|Read and write all lifecycle workflows resources|
|**Description**|Allows the app to create, update, list, read and delete all workflows, tasks and related lifecycle workflows resources without a signed-in user.|
## Resources
### [customExtensionAuthenticationConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionauthenticationconfiguration?view=graph-rest-1.0&tabs=http)

### [customExtensionCalloutResponse ](https://docs.microsoft.com/graph/api/resources/customextensioncalloutresponse?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|data|customExtensionData|Contains the data the external system provides to the custom extension endpoint.|
|source|String|Identifies the external system or event context related to the response.|
|type|String|Describes the type of event related to the response.|
### [customExtensionClientConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionclientconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|timeoutInMilliseconds|Int32|The max duration in milliseconds that Microsoft Entra ID waits for a response from the external app before it shuts down the connection. The valid range is between `200` and `2000` milliseconds. Default duration is `1000`.|
|maximumRetries|Int32|The max number of retries that Microsoft Entra ID makes to the external API. Values of 0 or 1 are supported. If `null`, the default for the service applies.|
### [customExtensionEndpointConfiguration ](https://docs.microsoft.com/graph/api/resources/customextensionendpointconfiguration?view=graph-rest-1.0&tabs=http)

### [emailSettings ](https://docs.microsoft.com/graph/api/resources/emailsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|senderDomain|String|Specifies the domain that should be used when sending email notifications. This domain must be verified in order to be used. We recommend that you use a domain that has the appropriate DNS records to facilitate email validation, like SPF, DKIM, DMARC, and MX, because this then complies with the RFC compliance for sending and receiving email. For details, see Learn more about Exchange Online Email Routing.|
|useCompanyBranding|Boolean|Specifies if the organization’s banner logo should be included in email notifications. The banner logo will replace the Microsoft logo at the top of the email notification. If `true` the banner logo will be taken from the tenant’s branding settings. This value can only be set to `true` if the organizationalBranding **b
### [customTaskExtension ](https://docs.microsoft.com/graph/api/resources/identitygovernance-customtaskextension?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authenticationConfiguration|microsoft.graph.customExtensionAuthenticationConfiguration|Configuration for securing the API call to the logic app. Inherited from customCalloutExtension. Required.|
|callbackConfiguration|microsoft.graph.identityGovernance.customTaskExtensionCallbackConfiguration|The callback configuration for a custom task extension.|
|clientConfiguration|microsoft.graph.customExtensionClientConfiguration|HTTP connection settings that define how long Microsoft Entra ID can wait for a connection to a logic app, how many times you can retry a timed-out connection and the exception scenarios when retries are allowed. Inherited from customCalloutExtension.|
|createdDateTime|DateTimeOffset|When the custom task extension was created.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|description|String|Describes the purpose of the custom task extension for administrative use. Inherited from customCalloutExtension. Optional.|
|displayName|String|A unique string that identifies the custom task extension. Inherited from customCalloutExtension. Required.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|endpointConfiguration|microsoft.graph.customExtensionEndpointConfiguration|Details for allowing the custom task extension to call the logic app. Inherited from customCalloutExtension.|
|id|String| Inherited from entity.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|lastModifiedDateTime|DateTimeOffset|When the custom extension was last modified.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
### [customTaskExtensionCallbackConfiguration ](https://docs.microsoft.com/graph/api/resources/identitygovernance-customtaskextensioncallbackconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|timeoutDuration|Duration| Callback time out in ISO 8601 time duration. Accepted time durations are between five minutes to three hours. For example, PT5M for five minutes and PT3H for three hours. Inherited from customExtensionCallbackConfiguration.|
|authorizedApps|microsoft.graph.application collection| A collection of unique identifiers or **a
### [customTaskExtensionCallbackData ](https://docs.microsoft.com/graph/api/resources/identitygovernance-customtaskextensioncallbackdata?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|operationStatus|microsoft.graph.identityGovernance.customTaskExtensionOperationStatus|Operation status that's provided by the Azure Logic App indicating whenever the Azure Logic App has run successfully or not. Supported values: `completed`, `failed`, `unknownFutureValue`.|
### [lifecycleManagementSettings ](https://docs.microsoft.com/graph/api/resources/identitygovernance-lifecyclemanagementsettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|workflowScheduleIntervalInHours|Int32|The interval in hours at which all workflows running in the tenant should be scheduled for execution. This interval has a minimum value of 1 and a maximum value of 24. The default value is 3 hours. |
|emailSettings|microsoft.graph.emailSettings|Defines the settings for emails sent out from email-specific tasks within workflows. Accepts 2 parameters<br><br>senderDomain- Defines the domain of who is sending the email. <br>useCompanyBranding- A Boolean value that defines if company branding is to be used with the email.|
### [run ](https://docs.microsoft.com/graph/api/resources/identitygovernance-run?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|completedDateTime|DateTimeOffset|The date time that the run completed. Value is `null` if the workflow hasn't completed.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|failedTasksCount|Int32|The number of tasks that failed in the run execution.|
|failedUsersCount|Int32|The number of users that failed in the run execution.|
|id|String|A unique identifier for the workflow run.|
|lastUpdatedDateTime|DateTimeOffset|The datetime that the run was last updated.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|processingStatus|microsoft.graph.identityGovernance.lifecycleWorkflowProcessingStatus|The run execution status. The possible values are: `queued`, `inProgress`, `completed`, `completedWithErrors`, `canceled`, `failed`, `unknownFutureValue`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|scheduledDateTime|DateTimeOffset|The date time that the run is scheduled to be executed for a workflow.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|startedDateTime|DateTimeOffset|The date time that the run execution started.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|successfulUsersCount|Int32|The number of successfully completed users in the run.|
|totalUsersCount|Int32|The total number of users in the workflow execution.|
|totalTasksCounts|Int32|The total number of tasks in the run execution.|
|totalUnprocessedTasksCount|Int32|The total number of unprocessed tasks in the run execution.|
|workflowExecutionType|microsoft.graph.identityGovernance.workflowExecutionType|The execution type of the workflows associated with the run. The possible values are: `scheduled`, `onDemand`, `unknownFutureValue`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
### [runSummary ](https://docs.microsoft.com/graph/api/resources/identitygovernance-runsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|failedRuns|Int32|The number of failed workflow runs.|
|failedTasks|Int32|The number of failed tasks of a workflow.|
|successfulRuns|Int32|The number of successful workflow runs.|
|totalRuns|Int32|The total number of runs for a workflow.|
|totalTasks|Int32|The total number of tasks processed by a workflow.|
|totalUsers|Int32|The total number of users processed by a workflow.|
### [identitygovernance-task](https://docs.microsoft.com/graph/api/resources/identitygovernance-task?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|arguments|microsoft.graph.keyValuePair collection|Arguments included within the task. <br/> For guidance to configure this property, see Configure the arguments for built-in Lifecycle Workflow tasks. Required.|
|category|microsoft.graph.identityGovernance.lifecycleTaskCategory|The category of the task. The possible values are: `joiner`, `leaver`, `unknownFutureValue`. This property is multi-valued and the same task can apply to both `joiner` and `leaver` categories.<br><br>Supports `$filter`(`eq`, `ne`).|
|continueOnError|Boolean|A Boolean value that specifies whether, if this task fails, the workflow stops, and subsequent tasks aren't run. Optional.|
|description|String|A string that describes the purpose of the task for administrative use. Optional.|
|displayName|String|A unique string that identifies the task. Required.<br><br>Supports `$filter`(`eq`, `ne`) and `orderBy`.|
|executionSequence|Int32|An integer that states in what order the task runs in a workflow.<br><br>Supports `$orderby`.|
|id|String|Identifier used for individually addressing a specific task. Inherited from entity.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|isEnabled|Boolean|A Boolean value that denotes whether the task is set to run or not. Optional.<br><br>Supports `$filter`(`eq`, `ne`) and `orderBy`.|
|taskDefinitionId|String|A unique template identifier for the task. For more information about the tasks that Lifecycle Workflows currently supports and their unique identifiers, see Configure the arguments for built-in Lifecycle Workflow tasks. Required.<br><br>Supports `$filter`(`eq`, `ne`).|
### [taskDefinition ](https://docs.microsoft.com/graph/api/resources/identitygovernance-taskdefinition?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|category|microsoft.graph.identityGovernance.lifecycleTaskCategory|The category of the HR function that the tasks created using this definition can be used with. The possible values are: `joiner`, `mover`, `leaver`, `unknownFutureValue`. This is a multi-valued enumeration whose allowed combinations are `joiner`, `joiner,leaver`, or `leaver`.<br><br>Supports `$filter`(`eq`, `ne`, `has`) and `$orderby`. |
|continueOnError|Boolean|Defines if the workflow will continue if the task has an error.|
|description|String|The description of the taskDefinition.|
|displayName|String|The display name of the taskDefinition.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|id|String|The unique identifier for the taskDefinition. Inherited from entity.|
|parameters|microsoft.graph.identityGovernance.parameter collection|The parameters that must be supplied when creating a workflow task object.<br><br>Supports `$filter`(`any`).|
|version|Int32|The version number of the taskDefinition. New records are pushed when we add support for new parameters.<br><br>Supports `$filter`(`ge`, `gt`, `le`, `lt`, `eq`, `ne`) and `$orderby`.|
### [taskProcessingResult ](https://docs.microsoft.com/graph/api/resources/identitygovernance-taskprocessingresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|completedDateTime|DateTimeOffset|The date time when taskProcessingResult execution ended. Value is `null` if task execution is still in progress.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|createdDateTime|DateTimeOffset|The date time when the taskProcessingResult was created.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|failureReason|String|Describes why the taskProcessingResult has failed.|
|id|String|Identifier used for individually addressing a specific task processing result. Inherited from entity.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|processingStatus|microsoft.graph.identityGovernance.lifecycleWorkflowProcessingStatus|Describes the execution status of the `taskProcessingResult`. The possible values are: `queued`, `inProgress`, `completed`, `completedWithErrors`, `canceled`, `failed`, `unknownFutureValue`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|startedDateTime|DateTimeOffset|The date time when taskProcessingResult execution started. Value is `null` if task execution has not yet started.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
### [taskReport ](https://docs.microsoft.com/graph/api/resources/identitygovernance-taskreport?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|completedDateTime|DateTimeOffset|The date time that the associated run completed. Value is `null` if the run has not completed.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|failedUsersCount|Int32|The number of users in the run execution for which the associated task failed.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|id|String|The unique identifier of the task report. Inherited from entity.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|lastUpdatedDateTime|DateTimeOffset|The date and time that the task report was last updated.|
|processingStatus|microsoft.graph.identityGovernance.lifecycleWorkflowProcessingStatus|The processing status of the associated task based on the taskProcessingResults. The possible values are based on the number of `queued`, `inProgress`, `completed`, `completedWithErrors`, `canceled`, `failed`, and `unknownFutureValue`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|runId|String|The unique identifier of the associated run.|
|startedDateTime|DateTimeOffset|The date time that the associated run started. Value is `null` if the run has not started.|
|successfulUsersCount|Int32|The number of users in the run execution for which the associated task succeeded.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|totalUsersCount|Int32|The total number of users in the run execution for which the associated task was scheduled to execute.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|unprocessedUsersCount|Int32|The number of users in the run execution for which the associated task is `queued`, `in progress`, or `canceled`.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
### [taskReportSummary ](https://docs.microsoft.com/graph/api/resources/identitygovernance-taskreportsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|failedTasks|Int32|The number of failed tasks in a report.|
|successfulTasks|Int32|The total number of successful tasks in a report.|
|totalTasks|Int32|The total number of tasks in a report.|
|unprocessedTasks|Int32|The number of unprocessed tasks in a report.|
### [timeBasedAttributeTrigger ](https://docs.microsoft.com/graph/api/resources/identitygovernance-timebasedattributetrigger?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|offsetInDays|Int32|How many days before or after the time-based attribute specified the workflow should trigger. For example, if the attribute is `employeeHireDate` and offsetInDays is -1, then the workflow should trigger one day before the employee hire date. The value can range between -180 and 180 days.|
|timeBasedAttribute|microsoft.graph.identityGovernance.workflowTriggerTimeBasedAttribute|Determines which time-based identity property to reference. The possible values are: `employeeHireDate`, `employeeLeaveDateTime`, `createdDateTime`, `unknownFutureValue`.|
### [triggerAndScopeBasedConditions ](https://docs.microsoft.com/graph/api/resources/identitygovernance-triggerandscopebasedconditions?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|scope|microsoft.graph.subjectSet|Defines who the workflow runs for.|
|trigger|microsoft.graph.identityGovernance.workflowExecutionTrigger|What triggers a workflow to run.|
### [userProcessingResult ](https://docs.microsoft.com/graph/api/resources/identitygovernance-userprocessingresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|completedDateTime|DateTimeOffset|The date time that the workflow execution for a user completed. Value is null if the workflow hasn't completed.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|failedTasksCount|Int32|The number of tasks that failed in the workflow execution.|
|id|String|Identifier used for individually addressing a specific user processing result.Inherited from entity.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|processingStatus|microsoft.graph.identityGovernance.lifecycleWorkflowProcessingStatus|The workflow execution status. The possible values are: `queued`, `inProgress`, `completed`, `completedWithErrors`, `canceled`, `failed`, `unknownFutureValue`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|scheduledDateTime|DateTimeOffset|The date time that the workflow is scheduled to be executed for a user.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|startedDateTime|DateTimeOffset|The date time that the workflow execution started. Value is `null` if the workflow execution has not started.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|totalTasksCount|Int32|The total number of tasks that in the workflow execution.|
|totalUnprocessedTasksCount|Int32|The total number of unprocessed tasks for the workflow.|
|workflowExecutionType|microsoft.graph.identityGovernance.workflowExecutionType|Describes the execution type of the workflow. The possible values are: `scheduled`, `onDemand`, `unknownFutureValue`.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|workflowVersion|Int32|The version of the workflow that was executed.|
### [userSummary ](https://docs.microsoft.com/graph/api/resources/identitygovernance-usersummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|failedTasks|Int32|The number of failed tasks for users in a user summary.|
|failedUsers|Int32|The number of failed users in a user summary.|
|successfulUsers|Int32|The number of successful users in a user summary.|
|totalTasks|Int32|The total tasks of users in a user summary.|
|totalUsers|Int32|The total number of users in a user summary|
### [workflow ](https://docs.microsoft.com/graph/api/resources/identitygovernance-workflow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|category|microsoft.graph.identityGovernance.lifecycleWorkflowCategory|The category of the HR function supported by the workflows created using this template. A workflow can only belong to one category. The possible values are: `joiner`, `leaver`, `mover`, `unknownFutureValue`. Inherited from workflowBase. Required.<br><br>Supports `$filter`(`eq`,`ne`) and `$orderby`|
|createdDateTime|DateTimeOffset|When the `workflow` was created. Inherited from workflowBase.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|deletedDateTime|DateTimeOffset|When the workflow was deleted.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|description|String|The description of the `workflow`. Inherited from workflowBase. Optional.|
|displayName|String|The display name of the `workflow`. Inherited from workflowBase. Required.<br><br>Supports `$filter`(`eq`, `ne`) and `orderby`.|
|executionConditions|microsoft.graph.identityGovernance.workflowExecutionConditions|Conditions describing when to execute the workflow and the criteria to identify in-scope subject set. Inherited from workflowBase. Required.|
|id|String|Identifier used for individually addressing a specific workflow.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|isEnabled|Boolean|Whether the workflow is enabled or disabled. If this setting is `true`, the workflow can be run on demand or on schedule when **isSchedulingEnabled** is `true`. Inherited from workflowBase. Optional. Defaults to `true`.<br><br>Supports `$filter`(`eq`, `ne`) and `orderBy`.|
|isSchedulingEnabled|Boolean|If `true`, the Lifecycle Workflow engine executes the workflow based on the schedule defined by tenant settings. Cannot be `true` for a disabled workflow (where **isEnabled** is `false`). Inherited from workflowBase. Optional. Defaults to `false`.<br><br>Supports `$filter`(`eq`, `ne`) and `orderBy`.|
|lastModifiedDateTime|DateTimeOffset|The date time when the `workflow` was last modified. Inherited from workflowBase.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|nextScheduleRunDateTime|DateTimeOffset|The date time when the `workflow` is expected to run next based on the schedule interval, if there are any users matching the execution conditions. <br><br>Supports `$filter`(`lt`,`gt`) and `$orderby`.|
|version|Int32|The current version number of the workflow. Value is 1 when the workflow is first created.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
### [workflowExecutionConditions ](https://docs.microsoft.com/graph/api/resources/identitygovernance-workflowexecutionconditions?view=graph-rest-1.0&tabs=http)

### [workflowTemplate ](https://docs.microsoft.com/graph/api/resources/identitygovernance-workflowtemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|category|microsoft.graph.identityGovernance.lifecycleWorkflowCategory|The category of the workflow template. The possible values are: `joiner`, `mover`, `leaver`,`unknownFutureValue`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|description|String|The description of the `workflowTemplate`.|
|displayName|String|The display name of the `workflowTemplate`.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
|executionConditions|microsoft.graph.identityGovernance.workflowExecutionConditions|Conditions describing when to execute the workflow and the criteria to identify in-scope subject set.|
|id|String|The unique identifier for the `workflowTemplate`.Inherited from entity.<br><br>Supports `$filter`(`eq`, `ne`) and `$orderby`.|
### [workflowVersion ](https://docs.microsoft.com/graph/api/resources/identitygovernance-workflowversion?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|category|microsoft.graph.identityGovernance.lifecycleWorkflowCategory|The category of the HR function supported by the workflows created using this template. A workflow can only belong to one category. The possible values are: `joiner`, `leaver`, `mover`,`unknownFutureValue`. Inherited from workflowBase.<br><br>Supports `$filter`(`eq`,`ne`) and `$orderby`|
|createdDateTime|DateTimeOffset|The date time when the `workflow` was versioned. Inherited from workflowBase.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|description|String|The description of the `workflowversion`. Inherited from workflowBase.|
|displayName|String|The display name of the `workflowversion`. Inherited from workflowBase.<br><br>Supports `$filter`(`eq`, `ne`) and `orderby`.|
|executionConditions|microsoft.graph.identityGovernance.workflowExecutionConditions|Conditions describing when to execute the workflow and the criteria to identify in-scope subject set. Inherited from workflowBase.|
|isEnabled|Boolean|Whether the workflow is enabled or disabled. If this setting is `true`, the workflow can be run on demand or on schedule when **isSchedulingEnabled** is `true`. Inherited from workflowBase.<br><br>Supports `$filter`(`eq`, `ne`) and `orderBy`.|
|isSchedulingEnabled|Boolean|If `true`, the Lifecycle Workflow engine executes the workflow based on the schedule defined by tenant settings. Cannot be `true` for a disabled workflow (where **isEnabled** is `false`). Inherited from workflowBase.<br><br>Supports `$filter`(`eq`, `ne`) and `orderBy`.|
|lastModifiedDateTime|DateTimeOffset|The date time when the `workflow` was last modified. Inherited from workflowBase.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
|versionNumber|Int32|The version of the workflow.<br><br>Supports `$filter`(`lt`, `le`, `gt`, `ge`, `eq`, `ne`) and `$orderby`.|
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
