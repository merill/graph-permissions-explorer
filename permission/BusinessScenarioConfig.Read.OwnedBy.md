# BusinessScenarioConfig.Read.OwnedBy

> Allows the app to read the configurations of business scenarios it owns, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /solutions/businessScenarios](https://docs.microsoft.com/graph/api/solutionsroot-list-businessscenarios?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}](https://docs.microsoft.com/graph/api/businessscenario-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}/planner](https://docs.microsoft.com/graph/api/businessscenarioplanner-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}/planner/planConfiguration](https://docs.microsoft.com/graph/api/plannerplanconfiguration-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}/planner/planConfiguration/localizations](https://docs.microsoft.com/graph/api/plannerplanconfiguration-list-localizations?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /solutions/businessScenarios/{businessScenarioId}/planner/taskConfiguration](https://docs.microsoft.com/graph/api/plannertaskconfiguration-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c47e7b6e-d6f1-4be9-9ffd-1e00f3e32892|
|**Consent Type**|Admin|
|**Display String**|Read business scenario configurations this app creates or owns|
|**Description**|Allows the app to read the configurations of business scenarios it owns, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|acc0fc4d-2cd6-4194-8700-1768d8423d86|
|**Display String**|Read all business scenario configurations this app creates or owns|
|**Description**|Allows the app to read the configurations of business scenarios it owns, without a signed-in user.|
## Resources
### [businessScenario ](https://docs.microsoft.com/graph/api/resources/businessscenario?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|identitySet|The identity of the user who created the scenario.|
|createdDateTime|DateTimeOffset|The date and time when the scenario was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|Display name of the scenario.|
|id|String|The unique identifier for the scenario. Inherited from entity.|
|lastModifiedBy|identitySet|The identity of the user who last modified the scenario.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the scenario was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|ownerAppIds|String collection|Identifiers of applications that are authorized to work with this scenario.|
|uniqueName|String|Unique name of the scenario. To avoid conflicts, the recommended value for the unique name is a reverse domain name format, owned by the author of the scenario. For example, a scenario authored by *C
### [businessScenarioPlanner ](https://docs.microsoft.com/graph/api/resources/businessscenarioplanner?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the **b
### [plannerPlanConfiguration ](https://docs.microsoft.com/graph/api/resources/plannerplanconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|buckets|plannerPlanConfigurationBucketDefinition collection|List the buckets that should be created in the plan.|
|createdBy|identitySet|The identity of the creator of the plan configuration.|
|createdDateTime|DateTimeOffset|The date and time when the plan configuration was created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
|defaultLanguage|String|The language code for the default language to be used for the names of the objects created for the plan.|
|id|String|The unique identifier for the plan configuration. Inherited from entity. |
|lastModifiedBy|identitySet|The identity of the user who last modified the plan configuration. |
|lastModifiedDateTime|DateTimeOffset|The date and time when the plan configuration was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
### [plannerPlanConfigurationLocalization ](https://docs.microsoft.com/graph/api/resources/plannerplanconfigurationlocalization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|buckets|plannerPlanConfigurationBucketLocalization collection|Localized names for configured buckets in the plan configuration.|
|id|String|The unique identifier for the plan configuration location. Inherited from entity.|
|languageTag|String|The language code associated with the localized names in this object.|
|planTitle|String|Localized title of the plan.|
### [plannerTaskConfiguration ](https://docs.microsoft.com/graph/api/resources/plannertaskconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|editPolicy|plannerTaskPolicy|Policy configuration for tasks created for the businessScenario when they're being changed outside of the scenario.|
|id|String|The unique identifier for the task configuration. Inherited from entity.|
