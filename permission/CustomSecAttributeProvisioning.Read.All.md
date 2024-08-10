# CustomSecAttributeProvisioning.Read.All

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /applications/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/jobs/{jobId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /servicePrincipals/{id}/synchronization/templates/{templateId}/schema](https://docs.microsoft.com/graph/api/synchronization-synchronizationschema-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**||
|**Consent Type**||
|**Display String**||
|**Description**||
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [synchronizationSchema ](https://docs.microsoft.com/graph/api/resources/synchronization-synchronizationschema?view=graph-rest-1.0&tabs=http)
| Property      | Type      | Description    |
|:--------------|:----------|:---------------|
|id|String|Unique identifier for the schema.|
|synchronizationRules   |synchronizationRule collection   |A collection of synchronization rules configured for the synchronizationJob or synchronizationTemplate. |
|version                |String                             |The version of the schema, updated automatically with every schema change.|
