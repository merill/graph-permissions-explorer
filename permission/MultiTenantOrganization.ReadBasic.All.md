# MultiTenantOrganization.ReadBasic.All

> Allows the app to read multi-tenant organization basic details and active tenants on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /tenantRelationships/multiTenantOrganization](https://docs.microsoft.com/graph/api/multitenantorganization-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /tenantRelationships/multiTenantOrganization/tenants](https://docs.microsoft.com/graph/api/multitenantorganization-list-tenants?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|225db56b-15b2-4daa-acb3-0eec2bbe4849|
|**Consent Type**|User|
|**Display String**|Read multi-tenant organization basic details and active tenants|
|**Description**|Allows the app to read multi-tenant organization basic details and active tenants on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|f9c2b2a7-3895-4b2e-80f6-c924b456e50b|
|**Display String**|Read multi-tenant organization basic details and active tenants|
|**Description**|Allows the app to read multi-tenant organization basic details and active tenants, without a signed-in user.|
## Resources
### [multiTenantOrganization ](https://docs.microsoft.com/graph/api/resources/multitenantorganization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date when multitenant organization was created. Read-only.|
|description|String|Description of the multitenant organization.|
|displayName|String|Display name of the multitenant organization.|
|id|String|Tenant-specific object ID for the multitenant organization object. It is automatically generated when a multitenant organization object is created and stored in the local tenant. This ID is tenant-specific and doesn't match the object IDs of the same multitenant organization in other tenants. Read-only. Inherited from entity.|
|state|multiTenantOrganizationState|State of the multitenant organization. The possible values are: `active`, `inactive`, `unknownFutureValue`. `active` indicates the multitenant organization is created. `inactive` indicates the multitenant organization isn't created. Read-only.|
### [multiTenantOrganizationMember ](https://docs.microsoft.com/graph/api/resources/multitenantorganizationmember?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|addedByTenantId|String|Tenant ID of the tenant that added the tenant to the multitenant organization. Read-only.|
|addedDateTime|DateTimeOffset|Date and time when the tenant was added to the multitenant organization. Read-only.|
|displayName|String|Display name of the tenant added to the multitenant organization.|
|joinedDateTime|DateTimeOffset|Date and time when the tenant joined the multitenant organization. Read-only.|
|role|multiTenantOrganizationMemberRole|Role of the tenant in the multitenant organization. The possible values are: `owner`, `member` (default), `unknownFutureValue`. Tenants with the owner role can manage the multitenant organization but tenants with the member role can only participate in a multitenant organization. There can be multiple tenants with the owner role in a multitenant organization. |
|state|multiTenantOrganizationMemberState|State of the tenant in the multitenant organization. The possible values are: `pending`, `active`, `removed`, `unknownFutureValue`. Tenants in the pending state must join the multitenant organization to participate in the multitenant organization. Tenants in the active state can participate in the multitenant organization. Tenants in the removed state are in the process of being removed from the multitenant organization. Read-only.|
|tenantId|String|Tenant ID of the Microsoft Entra tenant added to the multitenant organization. Set at the time tenant is added.<br><br>Supports `$filter`. Key.|
|transitionDetails|multiTenantOrganizationMemberTransitionDetails|Details of the processing status for a tenant in a multitenant organization. Read-only. Nullable.|
