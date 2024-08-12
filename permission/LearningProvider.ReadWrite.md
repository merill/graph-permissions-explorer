# LearningProvider.ReadWrite

> Allows the app to create, update, read, and delete data for the learning provider in the organization's directory, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /employeeExperience/learningProviders/{learningProviderId}/$ref](https://docs.microsoft.com/graph/api/employeeexperience-delete-learningproviders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /employeeExperience/learningProviders](https://docs.microsoft.com/graph/api/employeeexperience-list-learningproviders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /employeeExperience/learningProviders/{learningProviderId}](https://docs.microsoft.com/graph/api/learningprovider-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /employeeExperience/learningProviders/{learningProviderId}](https://docs.microsoft.com/graph/api/learningprovider-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /employeeExperience/learningProviders](https://docs.microsoft.com/graph/api/employeeexperience-post-learningproviders?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|40c2eb57-abaf-49f5-9331-e90fd01f7130|
|**Consent Type**|Admin|
|**Display String**|Manage learning provider|
|**Description**|Allows the app to create, update, read, and delete data for the learning provider in the organization's directory, on behalf of the signed-in user.|
## Resources
### [learningCourseActivity ](https://docs.microsoft.com/graph/api/resources/learningcourseactivity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignedDateTime|DateTimeOffset|Date and time when the assignment was completed. Optional.|
|assignerUserId|String|The user ID of the assigner. Optional.|
|assignmentType|assignmentType|Assignment type for the course activity. Possible values are: `required`, `recommended`, `unknownFutureValue`, `peerRecommended`.You must use the `Prefer: include-unknown-enum-members` request header to get the following value or values in this evolvable enum: `peerRecommended`. Required.|
|completedDateTime|DateTimeOffset|Date and time when the assignment was completed. Optional.|
|completionPercentage|Int32|The percentage completion value of the course activity. Optional.|
|dueDateTime|DateTimeTimeZone|Due date for the course activity. Optional.|
|externalCourseActivityId|String|A course activity ID generated by the provider. Optional.|
|id|String|A generated ID that can be used with other course activity APIs.|
|learnerUserId|String|The user ID of the learner to whom the activity is assigned. Required.|
|learningContentId|String|The ID of the learning content created in Viva Learning. Required.|
|learningProviderId|String|The registration ID of the provider. Required.|
|startedDateTime|DateTimeOffset|Date and time when the self-initiated course was started by the learner. Optional.|
|status|courseStatus|The status of the course activity. Possible values are: `notStarted`, `inProgress`, `completed`. Required.|
### [learningProvider ](https://docs.microsoft.com/graph/api/resources/learningprovider?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|The display name that appears in Viva Learning. Required.|
|id|String|The unique identifier for the learning provider. Required. Inherited from entity.|
|isCourseActivitySyncEnabled|Boolean|Indicates whether a provider can ingest learning course activity records. The default value is `false`. Set to `true` to make learningCourseActivities available for this provider.|
|loginWebUrl|String|Authentication URL to access the courses for the provider. Optional.|
|longLogoWebUrlForDarkTheme|String|The long logo URL for the dark mode that needs to be a publicly accessible image. This image would be saved to the blob storage of Viva Learning for rendering within the Viva Learning app. Required.|
|longLogoWebUrlForLightTheme|String|The long logo URL for the light mode that needs to be a publicly accessible image. This image would be saved to the blob storage of Viva Learning for rendering within the Viva Learning app. Required.|
|squareLogoWebUrlForDarkTheme|String|The square logo URL for the dark mode that needs to be a publicly accessible image. This image would be saved to the blob storage of Viva Learning for rendering within the Viva Learning app. Required.|
|squareLogoWebUrlForLightTheme|String|The square logo URL for the light mode that needs to be a publicly accessible image. This image would be saved to the blob storage of Viva Learning for rendering within the Viva Learning app. Required.|