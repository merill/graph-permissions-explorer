# MultiTenantOrganization.ReadWrite.All

> Allows the app to read and write multi-tenant organization details and tenants on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /tenantRelationships/multiTenantOrganization/tenants/{tenantId}](https://docs.microsoft.com/graph/api/multitenantorganization-delete-tenants?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/multiTenantOrganization](https://docs.microsoft.com/graph/api/multitenantorganization-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/multiTenantOrganization/joinRequest](https://docs.microsoft.com/graph/api/multitenantorganizationjoinrequestrecord-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/multiTenantOrganization/tenants](https://docs.microsoft.com/graph/api/multitenantorganization-list-tenants?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /tenantRelationships/multiTenantOrganization/tenants/{tenantId}](https://docs.microsoft.com/graph/api/multitenantorganizationmember-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /tenantRelationships/multiTenantOrganization](https://docs.microsoft.com/graph/api/multitenantorganization-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /tenantRelationships/multiTenantOrganization/joinRequest](https://docs.microsoft.com/graph/api/multitenantorganizationjoinrequestrecord-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /tenantRelationships/multiTenantOrganization/tenants/{tenantId}](https://docs.microsoft.com/graph/api/multitenantorganizationmember-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /tenantRelationships/multiTenantOrganization/tenants](https://docs.microsoft.com/graph/api/multitenantorganization-post-tenants?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /tenantRelationships/multiTenantOrganization](https://docs.microsoft.com/graph/api/tenantrelationship-put-multitenantorganization?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|77af1528-84f3-4023-8d90-d219cd433108|
|**Consent Type**|Admin|
|**Display String**|Read and write multi-tenant organization details and tenants|
|**Description**|Allows the app to read and write multi-tenant organization details and tenants on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|920def01-ca61-4d2d-b3df-105b46046a70|
|**Display String**|Read and write all multi-tenant organization details and tenants|
|**Description**|Allows the app to read and write all multi-tenant organization details and tenants, without a signed-in user.|
## Resources
### [multiTenantOrganization ](https://docs.microsoft.com/graph/api/resources/multitenantorganization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|Date when multitenant organization was created. Read-only.|
|description|String|Description of the multitenant organization.|
|displayName|String|Display name of the multitenant organization.|
|id|String|Tenant-specific object ID for the multitenant organization object. It is automatically generated when a multitenant organization object is created and stored in the local tenant. This ID is tenant-specific and doesn't match the object IDs of the same multitenant organization in other tenants. Read-only. Inherited from entity.|
|state|multiTenantOrganizationState|State of the multitenant organization. The possible values are: `active`, `inactive`, `unknownFutureValue`. `active` indicates the multitenant organization is created. `inactive` indicates the multitenant organization isn't created. Read-only.|
### [multiTenantOrganizationJoinRequestRecord ](https://docs.microsoft.com/graph/api/resources/multitenantorganizationjoinrequestrecord?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|addedByTenantId|String|Tenant ID of the Microsoft Entra tenant that added a tenant to the multitenant organization. To reset a failed join request, set `addedByTenantId` to `00000000-0000-0000-0000-000000000000`. Required.|
|memberState|multiTenantOrganizationMemberState|State of the tenant in the multitenant organization. The possible values are: `pending`, `active`, `removed`, `unknownFutureValue`. Tenants in the pending state must join the multitenant organization to participate in the multitenant organization. Tenants in the active state can participate in the multitenant organization. Tenants in the removed state are in the process of being removed from the multitenant organization. Read-only.|
|role|multiTenantOrganizationMemberRole|Role of the tenant in the multitenant organization. The possible values are: `owner`, `member` (default), `unknownFutureValue`. Tenants with the owner role can manage the multitenant organization. There can be multiple tenants with the owner role in a multitenant organization. Tenants with the member role can participate in a multitenant organization.|
|transitionDetails|multiTenantOrganizationJoinRequestTransitionDetails|Details of the processing status for a tenant joining a multitenant organization. Read-only.|
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
