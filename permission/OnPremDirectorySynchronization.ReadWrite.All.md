# OnPremDirectorySynchronization.ReadWrite.All

> Allows the app to read and write all on-premises directory synchronization information for the organization, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /directory/onPremisesSynchronization](https://docs.microsoft.com/graph/api/onpremisesdirectorysynchronization-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /directory/onPremisesSynchronization/{id}](https://docs.microsoft.com/graph/api/onpremisesdirectorysynchronization-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|c2d95988-7604-4ba1-aaed-38a5f82a51c7|
|**Consent Type**|Admin|
|**Display String**|Read and write all on-premises directory synchronization information|
|**Description**|Allows the app to read and write all on-premises directory synchronization information for the organization, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|c22a92cc-79bf-4bb1-8b6c-e0a05d3d80ce|
|**Display String**|Read and write all on-premises directory synchronization information|
|**Description**|Allows the app to read and write all on-premises directory synchronization information for the organization, without a signed-in user.|
## Resources
### [onPremisesDirectorySynchronization ](https://docs.microsoft.com/graph/api/resources/onpremisesdirectorysynchronization?view=graph-rest-1.0&tabs=http)
| Property      | Type                                                                                                               | Description                                                                                                                  |
| :------------ | :----------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| configuration | onPremisesDirectorySynchronizationConfiguration | Consists of configurations that can be fine-tuned and impact the on-premises directory synchronization process for a tenant. Nullable.|
| features      | onPremisesDirectorySynchronizationFeature             | Consists of directory synchronization features that can be enabled or disabled. Not nullable.                                             |
| id            | String                                                                                                             | The unique Microsoft Entra tenant ID.                                                                                               |
### [onPremisesDirectorySynchronizationConfiguration ](https://docs.microsoft.com/graph/api/resources/onpremisesdirectorysynchronizationconfiguration?view=graph-rest-1.0&tabs=http)
| Property                     | Type                                                                                             | Description                                                             |
| :--------------------------- | :----------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------- |
| accidentalDeletionPrevention | onPremisesAccidentalDeletionPrevention | Contains the accidental deletion prevention configuration for a tenant. |
### [onPremisesDirectorySynchronizationFeature ](https://docs.microsoft.com/graph/api/resources/onpremisesdirectorysynchronizationfeature?view=graph-rest-1.0&tabs=http)
| Property                                         | Type    | Description                                                                                                                                                                                                                                                                                            |
| :----------------------------------------------- | :------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| blockCloudObjectTakeoverThroughHardMatchEnabled  | Boolean | Used to block cloud object takeover via source anchor hard match if enabled.                                                                                                                                                                                                                           |
| blockSoftMatchEnabled                            | Boolean | Use to block soft match for all objects if enabled for the  tenant. Customers are encouraged to enable this feature and keep it enabled until soft matching is required again for their tenancy. This flag should be enabled again after any soft matching has been completed and is no longer needed. |
| bypassDirSyncOverridesEnabled                    | Boolean | When `true`, persists the values of _Mobile_ and _OtherMobile_ in on-premises AD during sync cycles instead of values of _MobilePhone_ or _AlternateMobilePhones_ in Microsoft Entra ID.                                                                                                                         |
| cloudPasswordPolicyForPasswordSyncedUsersEnabled | Boolean | Used to indicate that cloud password policy applies to users whose passwords are synchronized from on-premises.                                                                                                                                                                                        |
| concurrentCredentialUpdateEnabled                | Boolean | Used to enable concurrent user credentials update in OrgId.                                                                                                                                                                                                                                            |
| concurrentOrgIdProvisioningEnabled               | Boolean | Used to enable concurrent user creation in OrgId.                                                                                                                                                                                                                                                      |
| deviceWritebackEnabled                           | Boolean | Used to indicate that device write-back is enabled.                                                                                                                                                                                                                                                    |
| directoryExtensionsEnabled                       | Boolean | Used to indicate that directory extensions are being synced from on-premises AD to Microsoft Entra ID.                                                                                                                                                                 |
| fopeConflictResolutionEnabled                    | Boolean | Used to indicate that for a Microsoft Forefront Online Protection for Exchange (FOPE) migrated tenant, the conflicting proxy address should be migrated over.                                                                                                                                          |
| groupWriteBackEnabled                            | Boolean | Used to enable object-level group writeback feature for additional group types.                                                                                                                                                                                                                        |
| passwordSyncEnabled                              | Boolean | Used to indicate on-premise password synchronization is enabled.                                                                                                                                                                                                                                       |
| passwordWritebackEnabled                         | Boolean | Used to indicate that writeback of password resets from Microsoft Entra ID to on-premises AD is enabled.                                                                                                                                                                                                         |
| quarantineUponProxyAddressesConflictEnabled      | Boolean | Used to indicate that we should quarantine objects with conflicting proxy address.                                                                                                                                                                                                                     |
| quarantineUponUpnConflictEnabled                 | Boolean | Used to indicate that we should quarantine objects conflicting with duplicate userPrincipalName.                                                                                                                                                                                                       |
| softMatchOnUpnEnabled                            | Boolean | Used to indicate that we should soft match objects based on userPrincipalName.                                                                                                                                                                                                                         |
| synchronizeUpnForManagedUsersEnabled             | Boolean | Used to indicate that we should synchronize userPrincipalName objects for managed users with licenses.                                                                                                                                                                                                 |
| unifiedGroupWritebackEnabled                     | Boolean | Used to indicate that Microsoft 365 Group write-back is enabled.                                                                                                                                                                                                                                       |
| userForcePasswordChangeOnLogonEnabled            | Boolean | Used to indicate that feature to force password change for a user on logon is enabled while synchronizing on-premise credentials.                                                                                                                                                                      |
| userWritebackEnabled                             | Boolean | Used to indicate that user writeback is enabled.                                                                                                                                                                                                                                                       |
