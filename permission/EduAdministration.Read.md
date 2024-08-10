# EduAdministration.Read

> Read the state and settings of all Microsoft education apps on behalf of the user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[GET /education/synchronizationProfiles](https://docs.microsoft.com/graph/api/educationsynchronizationprofile-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /education/synchronizationProfiles/{id}](https://docs.microsoft.com/graph/api/educationsynchronizationprofile-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /education/synchronizationProfiles/{id}/errors](https://docs.microsoft.com/graph/api/educationsynchronizationerrors-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /education/synchronizationProfiles/{id}/profileStatus](https://docs.microsoft.com/graph/api/educationsynchronizationprofilestatus-get?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|8523895c-6081-45bf-8a5d-f062a2f12c9f|
|**Consent Type**|Admin|
|**Display String**|Read education app settings|
|**Description**|Read the state and settings of all Microsoft education apps on behalf of the user.|
## Resources
### [educationsynchronizationerror](https://docs.microsoft.com/graph/api/resources/educationsynchronizationerror?view=graph-rest-1.0&tabs=http)
| Property             | Type           | Description                                                     |
| :------------------- | :------------- | :-------------------------------------------------------------- |
| id                   | String         | The unique identifier for the resource. (read-only)             |
| entryType            | String         | Represents the sync entity (school, section, student, teacher). |
| errorCode            | String         | Represents the error code for this error.                       |
| errorMessage         | String         | Contains a description of the error.                            |
| joiningValue         | String         | The unique identifier for the entry.                            |
| recordedDateTime     | DateTimeOffset | The time of occurrence of this error.                           |
| reportableIdentifier | String         | The identifier of this error entry.                             |
### [educationsynchronizationprofile](https://docs.microsoft.com/graph/api/resources/educationsynchronizationprofile?view=graph-rest-1.0&tabs=http)
| Property                             | Type                                                   | Description                                                                                                                       |
| :----------------------------------- | :----------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| id                                   | String                                                 | The unique identifier for the resource. (read-only)                                                                               |
| displayName                          | String                                                 | Name of the configuration profile for syncing identities.                                                                         |
| dataProvider                         | [educationSynchronizationDataProvider]                 | The data provider used for the profile.                                                                                           |
| expirationDate                       | Date                                                   | The date the profile should be considered expired and cease syncing. Provide the date in `YYYY-MM-DD` format, following ISO 8601. Maximum value is 18 months from profile creation.  (optional)       |
| handleSpecialCharacterConstraint     | Bool                                                   | Determines if School Data Sync should automatically replace unsupported special characters while syncing from source.             |
| identitySynchronizationConfiguration | [educationIdentitySynchronizationConfiguration]        | Determines how the Profile should [create new][fullsync] or [match existing][dirsync] Microsoft Entra users.                                  |
| licensesToAssign                     | [educationSynchronizationLicenseAssignment] collection | License setup configuration.                                                                                                      |
| state                                | educationSynchronizationProfileState                   | The state of the profile. Possible values are: `provisioning`, `provisioned`, `provisioningFailed`, `deleting`, `deletionFailed`. |
### [educationsynchronizationprofilestatus](https://docs.microsoft.com/graph/api/resources/educationsynchronizationprofilestatus?view=graph-rest-1.0&tabs=http)
| Property                    | Type                           | Description                                                                                                              |
| :-------------------------- | :----------------------------- | :----------------------------------------------------------------------------------------------------------------------- |
| errorCount | Int64                 | Number of errors during synchronization.                                        |
| id                          | String                         | The unique identifier for the resource. Read-only.                                                                      |
| lastActivityDateTime | DateTimeOffset                 | Date and time when most recent changes were observed in the profile.                                        |
| lastSynchronizationDateTime | DateTimeOffset                 | Date and time of the most recent successful synchronization.                                        |
| status                      | educationSynchronizationStatus | The status of a sync. The possible values are: `paused`, `inProgress`, `success`, `error`, `validationError`, `quarantined`, `unknownFutureValue`, `extracting`, `validating`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following values in this evolvable enum: `extracting`, `validating`.|
| statusMessage | String                 | Status message for the synchronization stage of the current profile.                                        |
