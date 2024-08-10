# TeamsActivity.Send.User

## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[POST /teamwork/sendActivityNotificationToRecipients](https://docs.microsoft.com/graph/api/teamwork-sendactivitynotificationtorecipients?view=graph-rest-1.0&tabs=http)|
|V1|A|[POST /users/{userId | user-principal-name}/teamwork/sendActivityNotification](https://docs.microsoft.com/graph/api/userteamwork-sendactivitynotification?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [aadUserNotificationRecipient ](https://docs.microsoft.com/graph/api/resources/aadusernotificationrecipient?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|userId|String|Microsoft Entra user identifier. Use the List users method to get this ID.|
### [itemBody ](https://docs.microsoft.com/graph/api/resources/itembody?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|content|String|The content of the item.|
|contentType|bodyType|The type of the content. Possible values are `text` and `html`.|
### [keyValuePair ](https://docs.microsoft.com/graph/api/resources/keyvaluepair?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|name|String|Name for this key-value pair|
|value|String|Value for this key-value pair|
### [teamsAppInstallation ](https://docs.microsoft.com/graph/api/resources/teamsappinstallation?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
|consentedPermissionSet|teamsAppPermissionSet|The set of resource-specific permissions consented to while installing or upgrading the teamsApp.|
| id                  | string   | A unique ID (not the Teams app ID). |
### [teamsCatalogApp ](https://docs.microsoft.com/graph/api/resources/teamscatalogapp?view=graph-rest-1.0&tabs=http)

### [teamworkActivityTopic ](https://docs.microsoft.com/graph/api/resources/teamworkactivitytopic?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|source|teamworkActivityTopicSource|Type of source. Possible values are: `entityUrl`, `text`. For supported Microsoft Graph URLs, use `entityUrl`. For custom text, use `text`.|
|value|String|The topic value. If the value of the **source** property is `entityUrl`, this must be a Microsoft Graph URL. If the value is `text`, this must be a plain text value.|
|webUrl|String|The link the user clicks when they select the notification. Optional when **s
### [teamworkNotificationRecipient ](https://docs.microsoft.com/graph/api/resources/teamworknotificationrecipient?view=graph-rest-1.0&tabs=http)

