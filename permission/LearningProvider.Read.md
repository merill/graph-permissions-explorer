# LearningProvider.Read

> Allows the app to read data for the learning provider in the organization's directory, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /employeeExperience/learningProviders](https://docs.microsoft.com/graph/api/employeeexperience-list-learningproviders?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /employeeExperience/learningProviders/{learningProviderId}](https://docs.microsoft.com/graph/api/learningprovider-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|dd8ce36f-9245-45ea-a99e-8ac398c22861|
|**Consent Type**|Admin|
|**Display String**|Read learning provider|
|**Description**|Allows the app to read data for the learning provider in the organization's directory, on behalf of the signed-in user.|
## Resources
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
