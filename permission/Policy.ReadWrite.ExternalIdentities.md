# Policy.ReadWrite.ExternalIdentities

> Allows the application to read and update the organization's external identities policy on behalf of the signed-in user.  For example, external identities policy controls if users invited to access resources in your organization via B2B collaboration or B2B direct connect are allowed to self-service leave.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /policies/externalIdentitiesPolicy](https://docs.microsoft.com/graph/api/externalidentitiespolicy-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[PATCH /policies/externalIdentitiesPolicy](https://docs.microsoft.com/graph/api/externalidentitiespolicy-update?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b5219784-1215-45b5-b3f1-88fe1081f9c0|
|**Consent Type**|Admin|
|**Display String**|Read and write your organization's external identities policy|
|**Description**|Allows the application to read and update the organization's external identities policy on behalf of the signed-in user.  For example, external identities policy controls if users invited to access resources in your organization via B2B collaboration or B2B direct connect are allowed to self-service leave.|
## Application Permission
|||
|-|-|
|**Id**|03cc4f92-788e-4ede-b93f-199424d144a5|
|**Display String**|Read and write your organization's external identities policy|
|**Description**|Allows the application to read and update the organization's external identities policy without a signed-in user.  For example, external identities policy controls if users invited to access resources in your organization via B2B collaboration or B2B direct connect are allowed to self-service leave.|
## Resources
### [externalIdentitiesPolicy ](https://docs.microsoft.com/graph/api/resources/externalidentitiespolicy?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|allowDeletedIdentitiesDataRemoval|Boolean|<!--Notifies Azure AD whether to clean up the user information about the external identity, from the guest tenant, when the user is deleted in their home tenant.--> **Reserved for future use.**| 
|allowExternalIdentitiesToLeave|Boolean|Defines whether external users can leave the guest tenant. If set to `false`, self-service controls are disabled, and the admin of the guest tenant must manually remove the external user from the guest tenant. When the external user leaves the tenant, their data in the guest tenant is first soft-deleted then permanently deleted in 30 days.|
|displayName|String|The policy name. Inherited from policyBase.|
