# LifecycleWorkflows.Read.All

> Allows the app to list and read all workflows, tasks and related lifecycle workflows resources on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
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
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/tasks/{taskId}](https://docs.microsoft.com/graph/api/identitygovernance-task-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/userProcessingResults/{userProcessingResultId}/taskProcessingResults](https://docs.microsoft.com/graph/api/identitygovernance-userprocessingresult-list-taskprocessingresults?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions](https://docs.microsoft.com/graph/api/identitygovernance-workflow-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions/{workflowVersion-versionNumber}](https://docs.microsoft.com/graph/api/identitygovernance-workflowversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions/{workflowVersion-versionNumber}/tasks](https://docs.microsoft.com/graph/api/identitygovernance-workflowversion-list-tasks?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /identityGovernance/lifecycleWorkflows/workflows/{workflowId}/versions/{workFlowVersion-versionNumber}/tasks](https://docs.microsoft.com/graph/api/identitygovernance-workflowversion-list-tasks?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflowTemplates](https://docs.microsoft.com/graph/api/identitygovernance-lifecycleworkflowscontainer-list-workflowtemplates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /identityGovernance/lifecycleWorkflows/workflowTemplates/{workflowTemplateId}](https://docs.microsoft.com/graph/api/identitygovernance-workflowtemplate-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9bcb9916-765a-42af-bf77-02282e26b01a|
|**Consent Type**|Admin|
|**Display String**|Read all lifecycle workflows resources|
|**Description**|Allows the app to list and read all workflows, tasks and related lifecycle workflows resources on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|7c67316a-232a-4b84-be22-cea2c0906404|
|**Display String**|Read all lifecycle workflows resources|
|**Description**|Allows the app to list and read all workflows, tasks and related lifecycle workflows resources without a signed-in user.|
## Resources
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
