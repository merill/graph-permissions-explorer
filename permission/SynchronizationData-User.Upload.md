# SynchronizationData-User.Upload

> Allows the app to upload bulk user data to the identity synchronization service, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[POST /servicePrincipals/{servicePrincipalId}/synchronization/jobs/{jobId}/bulkUpload](https://docs.microsoft.com/graph/api/synchronization-synchronizationjob-post-bulkupload?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|1a2e7420-4e92-4d2b-94cb-fb2952e9ddf7|
|**Consent Type**|Admin|
|**Display String**|Upload user data to the identity synchronization service|
|**Description**|Allows the app to upload bulk user data to the identity synchronization service, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|db31e92a-b9ea-4d87-bf6a-75a37a9ca35a|
|**Display String**|Upload user data to the identity synchronization service|
|**Description**|Allows the application to upload bulk user data to the identity synchronization service, without a signed-in user.|
## Resources
### [bulkUpload ](https://docs.microsoft.com/graph/api/resources/synchronization-bulkupload?view=graph-rest-1.0&tabs=http)

