# OnPremDirectorySynchronization.Read.All

> Allows the app to read all on-premises directory synchronization information for the organization, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /directory/onPremisesSynchronization](https://docs.microsoft.com/graph/api/onpremisesdirectorysynchronization-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f6609722-4100-44eb-b747-e6ca0536989d|
|**Consent Type**|Admin|
|**Display String**|Read all on-premises directory synchronization information|
|**Description**|Allows the app to read all on-premises directory synchronization information for the organization, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|bb70e231-92dc-4729-aff5-697b3f04be95|
|**Display String**|Read all on-premises directory synchronization information|
|**Description**|Allows the app to read all on-premises directory synchronization information for the organization, without a signed-in user.|
## Resources
### [onPremisesDirectorySynchronization ](https://docs.microsoft.com/graph/api/resources/onpremisesdirectorysynchronization?view=graph-rest-1.0&tabs=http)
| Property      | Type                                                                                                               | Description                                                                                                                  |
| :------------ | :----------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| configuration | onPremisesDirectorySynchronizationConfiguration | Consists of configurations that can be fine-tuned and impact the on-premises directory synchronization process for a tenant. Nullable.|
| features      | onPremisesDirectorySynchronizationFeature             | Consists of directory synchronization features that can be enabled or disabled. Not nullable.                                             |
| id            | String                                                                                                             | The unique Microsoft Entra tenant ID.                                                                                               |
