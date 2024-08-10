# Synchronization.Read.All

> Allows the app to read Azure AD synchronization information, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /applications/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /applications/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /applications/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-jobs?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /servicePrincipals/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET applications/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET applications/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET servicePrincipals/{id}/synchronization/templates](https://docs.microsoft.com/graph/api/synchronization-synchronization-list-templates?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET servicePrincipals/{id}/synchronization/templates/{templateId}](https://docs.microsoft.com/graph/api/synchronization-synchronizationtemplate-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7aa02aeb-824f-4fbe-a3f7-611f751f5b55|
|**Consent Type**|Admin|
|**Display String**|Read all Azure AD synchronization data|
|**Description**|Allows the app to read Azure AD synchronization information, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|5ba43d2f-fa88-4db2-bd1c-a67c5f0fb1ce|
|**Display String**|Read all Azure AD synchronization data. |
|**Description**|Allows the application to read Azure AD synchronization information, without a signed-in user.|
## Resources
### [synchronizationJob ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationjob?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|id             |String                     |Unique synchronization job identifier. Read-only.|
|schedule       |synchronizationSchedule|Schedule used to run the job. Read-only.|
|status         |synchronizationStatus     |Status of the job, which includes when the job was last run, current job state, and errors.|
|synchronizationJobSettings   |keyValuePair    |Settings associated with the job. Some settings are inherited from the template.|
|templateId     |String    |Identifier of the synchronization template this job is based on.|
### [synchronizationSchema ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationschema?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|id|String|Unique identifier for the schema.|
|synchronizationRules   |synchronizationRule collection   |A collection of synchronization rules configured for the synchronizationJob or synchronizationTemplate. |
|version                |String                             |The version of the schema, updated automatically with every schema change.|
### [synchronizationTemplate ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationtemplate?view=graph-rest-1.0&tabs=http)
| Property      | Type                      | Description                  |
|:--------------|:--------------------------|:-----------------------------|
|id             |String                     |Unique template identifier.|
|applicationId  |String                     |Identifier of the application this template belongs to.|
|default        |Boolean                    |`true` if this template is recommended to be the default for the application.|
|description    |String                     |Description of the template.|
|discoverable   |String                     |`true` if this template should appear in the collection of templates available for the application instance (service principal).|
|factoryTag     |String                     |One of the well-known factory tags supported by the synchronization engine. The **factoryTag** tells the synchronization engine which implementation to use when processing jobs based on this template.|
|metadata       |synchronizationMetadataEntry collection  |Additional extension properties. Unless mentioned explicitly, metadata values should not be changed.|
