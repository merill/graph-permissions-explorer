# Files.Read

> Allows the app to read the signed-in user's files.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /me/drive/following/{item-id}](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{user-id}/drive/following/{item-id}](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drive/items/{item-id}/content?format={format}](https://docs.microsoft.com/graph/api/driveitem-get-content-format?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drive/root:/{path and filename}:/content?format={format}](https://docs.microsoft.com/graph/api/driveitem-get-content-format?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /drives/{drive-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /drives/{drive-id}/items/{item-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /drives/{drive-id}/items/{item-id}/analytics](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/analytics/allTime](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/analytics/lastSevenDays](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /drives/{drive-id}/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/getActivitiesByInterval(startDateTime={startDateTime},endDateTime={endDateTime},interval={interval})](https://docs.microsoft.com/graph/api/itemactivitystat-getactivitybyinterval?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{drive-id}/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{driveId}/list/subscriptions/socketIo](https://docs.microsoft.com/graph/api/subscriptions-socketio?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /drives/{driveId}/root/subscriptions/socketIo](https://docs.microsoft.com/graph/api/subscriptions-socketio?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /groups/{group-id}/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{group-id}/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{groupId}/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{groupId}/drive/root/subscriptions/socketIo](https://docs.microsoft.com/graph/api/subscriptions-socketio?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /groups/{groupId}/drives](https://docs.microsoft.com/graph/api/drive-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive](https://docs.microsoft.com/graph/api/drive-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/following](https://docs.microsoft.com/graph/api/drive-list-following?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/names](https://docs.microsoft.com/graph/api/worksheet-list-names?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/recent](https://docs.microsoft.com/graph/api/drive-recent?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/names](https://docs.microsoft.com/graph/api/worksheet-list-names?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{path}:/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root/subscriptions/socketIo](https://docs.microsoft.com/graph/api/subscriptions-socketio?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/special/{name}](https://docs.microsoft.com/graph/api/drive-get-specialfolder?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /shares/{shareIdOrEncodedSharingUrl}/driveItem/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /shares/{shareIdOrEncodedSharingUrl}/driveItem/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /sites/{site-id}/analytics](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /sites/{site-id}/analytics/allTime](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/analytics/lastSevenDays](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/getActivitiesByInterval(startDateTime={startDateTime},endDateTime={endDateTime},interval={interval})](https://docs.microsoft.com/graph/api/itemactivitystat-getactivitybyinterval?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /sites/{site-id}/lists/{list-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/analytics](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/analytics/allTime](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/analytics/lastSevenDays](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/driveItem](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/getActivitiesByInterval(startDateTime={startDateTime},endDateTime={endDateTime},interval={interval})](https://docs.microsoft.com/graph/api/itemactivitystat-getactivitybyinterval?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{siteId}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /sites/{siteId}/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /sites/{siteId}/drive/items/{itemId}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /sites/{siteId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /sites/{siteId}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /sites/{siteId}/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /sites/{siteId}/lists/{listId}/drive/root/subscriptions/socketIo](https://docs.microsoft.com/graph/api/subscriptions-socketio?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /sites/{siteId}/recycleBin/items](https://docs.microsoft.com/graph/api/recyclebin-list-items?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /teams/{id}/channels/{id}/filesFolder](https://docs.microsoft.com/graph/api/channel-get-filesfolder?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /teams/{teamId}/channels/{channelId}/filesFolder](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id}/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{userId}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId}/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /users/{userId}/drive/items/{itemId}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{userId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /users/{userId}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{userId}/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{drive-id}/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{group-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/unfollow](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /shares/{shareId}/driveItem/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{site-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{user-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{user-id}/drive/items/{item-id}/unfollow](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|10465720-29dd-4523-a11a-6a75c743c9d9|
|**Consent Type**|User|
|**Display String**|Read user files|
|**Description**|Allows the app to read the signed-in user's files.|
## Resources
### [channel ](https://docs.microsoft.com/graph/api/resources/channel?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|createdDateTime|dateTimeOffset|Read only. Timestamp at which the channel was created.|
|description|String|Optional textual description for the channel.|
|displayName|String|Channel name as it will appear to the user in Microsoft Teams. The maximum length is 50 characters.|
|email|String| The email address for sending messages to the channel. Read-only.|
|id|String|The channel's unique identifier. Read-only.|
|isArchived| Boolean | Indicates whether the channel is archived. Read-only. |
|isFavoriteByDefault|Boolean|Indicates whether the channel should be marked as recommended for all members of the team to show in their channel list. **Note:** All recommended channels automatically show in the channels list for education and frontline worker users. The property can only be set programmatically via the Create team method. The default value is `false`.|
|membershipType|channelMembershipType|The type of the channel. Can be set during creation and can't be changed. The possible values are: `standard`, `private`, `unknownFutureValue`, `shared`. The default value is `standard`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `shared`.|
|tenantId |string | The ID of the Microsoft Entra tenant. |
|webUrl|String|A hyperlink that will go to the channel in Microsoft Teams. This is the URL that you get when you right-click a channel in Microsoft Teams and select Get link to channel. This URL should be treated as an opaque blob, and not parsed. Read-only.|
|summary|channelSummary|Contains summary information about the channel, including number of owners, members, guests, and an indicator for members from other tenants. The **s
### [deleted](https://docs.microsoft.com/graph/api/resources/deleted?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                               |
|:---------|:-------|:------------------------------------------|
| state    | String | Represents the state of the deleted item. |
### [drive ](https://docs.microsoft.com/graph/api/resources/drive?view=graph-rest-1.0&tabs=http)
| Property             | Type                          | Description                                                                                                                                                                                                                      |
| :------------------- | :---------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| createdBy            | [identitySet][]               | Identity of the user, device, or application which created the item. Read-only.                                                                                                                                                  |
| createdDateTime      | dateTimeOffset                | Date and time of item creation. Read-only.                                                                                                                                                                                       |
| description          | String                        | Provide a user-visible description of the drive. Read-write.
| driveType            | String                        | Describes the type of drive represented by this resource. OneDrive personal drives will return `personal`. OneDrive for Business will return `business`. SharePoint document libraries will return `documentLibrary`. Read-only. |
| id                   | String                        | The unique identifier of the drive. Read-only.                                                                                                                                                                                   |
| lastModifiedBy       | [identitySet][]               | Identity of the user, device, and application which last modified the item. Read-only.                                                                                                                                           |
| lastModifiedDateTime | dateTimeOffset                | Date and time the item was last modified. Read-only.                                                                                                                                                                             |
| name                 | string                        | The name of the item. Read-write.                                                                                                                                                                                                |
| owner                | identitySet | Optional. The user account that owns the drive. Read-only.                                                                                                                                                                       |
| quota                | quota             | Optional. Information about the drive's storage space quota. Read-only.                                                                                                                                                          |
| sharepointIds        | [sharepointIds][]             | Returns identifiers useful for SharePoint REST compatibility. Read-only. This property is not returned by default and must be selected using the `$select` query parameter.  |
| system               | [systemFacet][]               | If present, indicates that this is a system-managed drive. Read-only.
| webUrl               | string (url)                  | URL that displays the resource in the browser. Read-only.                                                                                                                                                                        |
### [driveItem ](https://docs.microsoft.com/graph/api/resources/driveitem?view=graph-rest-1.0&tabs=http)
| Property             | Type               | Description
|:---------------------|:-------------------|:---------------------------------
| audio                | [audio][]          | Audio metadata, if the item is an audio file. Read-only. Read-only. Only on OneDrive Personal.
| bundle               | [bundle][]         | Bundle metadata, if the item is a bundle. Read-only.
| content              | Stream             | The content stream, if the item represents a file.
| createdBy            | [identitySet][]    | Identity of the user, device, and application that created the item. Read-only.
| createdDateTime      | DateTimeOffset     | Date and time of item creation. Read-only.
| cTag                 | String             | An eTag for the content of the item. This eTag isn't changed if only the metadata is changed. **Note** This property isn't returned if the item is a folder. Read-only.
| deleted              | [deleted][]        | Information about the deleted state of the item. Read-only.
| description          | String             | Provides a user-visible description of the item. Read-write. Only on OneDrive Personal.
| eTag                 | String             | eTag for the entire item (metadata + content). Read-only.
| file                 | [file][]           | File metadata, if the item is a file. Read-only.
| fileSystemInfo       | [fileSystemInfo][] | File system information on client. Read-write.
| folder               | [folder][]         | Folder metadata, if the item is a folder. Read-only.
| id                   | String             | The unique identifier of the item within the Drive. Read-only.
| image                | [image][]          | Image metadata, if the item is an image. Read-only.
| lastModifiedBy       | [identitySet][]    | Identity of the user, device, and application that last modified the item. Read-only.
| lastModifiedDateTime | DateTimeOffset     | Date and time the item was last modified. Read-only.
| location             | [geoCoordinates][] | Location metadata, if the item has location data. Read-only.
| malware              | [malware][]        | Malware metadata, if the item was detected to contain malware. Read-only.
| name                 | String             | The name of the item (filename and extension). Read-write.
| package              | [package][]        | If present, indicates that this item is a package instead of a folder or file. Packages are treated like files in some contexts and folders in others. Read-only.
| parentReference      | [itemReference][]  | Parent information, if the item has a parent. Read-write.
| pendingOperations    | [pendingOperations][] | If present, indicates that one or more operations that might affect the state of the driveItem are pending completion. Read-only.
| photo                | [photo][]          | Photo metadata, if the item is a photo. Read-only.
| publication          | [publicationFacet][] | Provides information about the published or checked-out state of an item, in locations that support such actions. This property isn't returned by default. Read-only. |
| remoteItem           | [remoteItem][]     | Remote item data, if the item is shared from a drive other than the one being accessed. Read-only.
| root                 | [root][]           | If this property is non-null, it indicates that the driveItem is the top-most driveItem in the drive.
| searchResult         | [searchResult][]   | Search metadata, if the item is from a search result. Read-only.
| shared               | [shared][]         | Indicates that the item was shared with others and provides information about the shared state of the item. Read-only.
| sharepointIds        | [sharepointIds][]  | Returns identifiers useful for SharePoint REST compatibility. Read-only.
| size                 | Int64              | Size of the item in bytes. Read-only.
| specialFolder        | [specialFolder][]  | If the current item is also available as a special folder, this facet is returned. Read-only.
| video                | [video][]          | Video metadata, if the item is a video. Read-only.
| webDavUrl            | String             | WebDAV compatible URL for the item.
| webUrl               | String             | URL that displays the resource in the browser. Read-only.

### [driveItemVersion ](https://docs.microsoft.com/graph/api/resources/driveitemversion?view=graph-rest-1.0&tabs=http)
|      Property        |                         Type                         |                               Description                               |
| :------------------- | :--------------------------------------------------- | :---------------------------------------------------------------------- |
| content              | Stream                                               | The content stream for this version of the item.                        |
| id                   | String                                               | The ID of the version. Read-only.                                       |
| lastModifiedBy       | identitySet           | Identity of the user who last modified the version. Read-only.          |
| lastModifiedDateTime | DateTimeOffset          | Date and time when the version was last modified. Read-only.            |
| publication          | publicationFacet | Indicates the publication status of this particular version. Read-only. |
| size                 | Int64                                                | Indicates the size of the content stream for this version of the item.  |
### [itemActivity ](https://docs.microsoft.com/graph/api/resources/itemactivity?view=graph-rest-1.0&tabs=http)
| Property | Type                    | Description
|:---------|:------------------------|:----------------------------------------
| access   | [accessAction][]        | An item was accessed.
| activityDateTime    | DateTimeOffset | Details about when the activity took place. Read-only.
| actor    | [identitySet][]         | Identity of who performed the action. Read-only.
| id       | string                  | The unique identifier of the activity. Read-only.

### [itemActivityStat ](https://docs.microsoft.com/graph/api/resources/itemactivitystat?view=graph-rest-1.0&tabs=http)
| Property         | Type                    | Description
|:-----------------|:------------------------|:----------------------------------------
| access           | [itemActionStat][]      | Statistics about the **access** actions in this interval. Read-only.
| create           | [itemActionStat][]      | Statistics about the **create** actions in this interval. Read-only.
| delete           | [itemActionStat][]      | Statistics about the **delete** actions in this interval. Read-only.
| edit             | [itemActionStat][]      | Statistics about the **edit** actions in this interval. Read-only.
| endDateTime      | DateTimeOffset          | When the interval ends. Read-only.
| incompleteData   | [incompleteData][]      | Indicates that the statistics in this interval are based on incomplete data. Read-only.
| isTrending       | Boolean                 | Indicates whether the item is "trending." Read-only.
| move             | [itemActionStat][]      | Statistics about the **move** actions in this interval. Read-only.
| startDateTime    | DateTimeOffset          | When the interval starts. Read-only.

### [itemAnalytics ](https://docs.microsoft.com/graph/api/resources/itemanalytics?view=graph-rest-1.0&tabs=http)
| Property      | Type                 | Description
|:--------------|:---------------------|:--------------------------------------
| allTime       | [itemActivityStat][] | Analytics over the item's lifespan.
| lastSevenDays | [itemActivityStat][] | Analytics for the last seven days.

### [itemReference ](https://docs.microsoft.com/graph/api/resources/itemreference?view=graph-rest-1.0&tabs=http)
| Property      | Type              | Description
|:--------------|:------------------|:-----------------------------------------
| driveId       | String            | Unique identifier of the drive instance that contains the driveItem. Only returned if the item is located in a [drive][]. Read-only.
| driveType     | String            | Identifies the type of drive. Only returned if the item is located in a [drive][]. See [drive][] resource for values.
| id            | String            | Unique identifier of the driveItem in the drive or a listItem in a list. Read-only.
| name          | String            | The name of the item being referenced. Read-only.
| path          | String            | Percent-encoded path that can be used to navigate to the item. Read-only.
| shareId       | String            | A unique identifier for a shared resource that can be accessed via the [Shares][] API.
| sharepointIds | [sharepointIds][] | Returns identifiers useful for SharePoint REST compatibility. Read-only.
| siteId        | String            | For OneDrive for Business and SharePoint, this property represents the ID of the site that contains the parent document library of the driveItem resource or the parent list of the listItem resource. The value is the same as the id property of that site][] resource. It is an [opaque string that consists of three identifiers of the site. <br>For OneDrive, this property is not populated.

### [List ](https://docs.microsoft.com/graph/api/resources/list?view=graph-rest-1.0&tabs=http)
| Property             | Type                              | Description                                                                                           |
|:---------------------|:----------------------------------|:------------------------------------------------------------------------------------------------------|
| createdBy            | identitySet     | Identity of the creator of this item. Read-only. Inherited from baseItem.              |
| createdDateTime      | DateTimeOffset                    | The date and time when the item was created. Read-only. Inherited from baseItem.       |
| description          | String                            | The descriptive text for the item. Inherited from baseItem.                            |
| displayName          | String                            | The displayable title of the list.                                                                    |
| eTag                 | String                            | ETag for the item. Inherited from baseItem.                                            |
| id                   | String                            | The unique identifier of the item. Read-only. Inherited from baseItem.                 |
| lastModifiedBy       | identitySet     | Identity of the last modifier of this item. Read-only. Inherited from baseItem.        |
| lastModifiedDateTime | DateTimeOffset                    | The date and time when the item was last modified. Read-only. Inherited from baseItem. |
| list                 | listInfo           | Contains more details about the list.                                                                 |
| name                 | String                            | The name of the item. Read-only. Inherited from baseItem.                              |
| parentReference      | itemReference | Parent information if the item has a parent. Read-write. Inherited from baseItem.      |
| sharepointIds        | sharepointIds | Returns identifiers useful for SharePoint REST compatibility. Read-only.                              |
| system               | systemFacet     | If present, indicates that the list is system-managed. Read-only.                                     |
| webUrl               | String                            | URL that displays the item in the browser. Read-only. Inherited from baseItem.         |
### [listItem ](https://docs.microsoft.com/graph/api/resources/listitem?view=graph-rest-1.0&tabs=http)
| Property    | Type                | Description                        |
|:------------|:--------------------|:-----------------------------------|
| contentType | [contentTypeInfo][] | The content type of this list item |
### [Permission ](https://docs.microsoft.com/graph/api/resources/permission?view=graph-rest-1.0&tabs=http)
| Property                         | Type                                      | Description |
|:---------------------------------|:------------------------------------------|:-----------------
| expirationDateTime               | DateTimeOffset                            | A format of yyyy-MM-ddTHH:mm:ssZ of DateTimeOffset indicates the expiration time of the permission. DateTime.MinValue indicates there's no expiration set for this permission. Optional. |
| id                               | String                                    | The unique identifier of the permission among all permissions on the item. Read-only. |
| hasPassword                      | Boolean                                   | Indicates whether the password is set for this permission. This property only appears in the response. Optional. Read-only. For OneDrive Personal only.. |
| grantedTo (deprecated)           | IdentitySet             | For user type permissions, the details of the users and applications for this permission. Read-only. |
| grantedToIdentities (deprecated) | Collection(IdentitySet) | For type permissions, the details of the users to whom permission was granted. Read-only. |
| grantedToIdentitiesV2            | Collection([SharePointIdentitySet][]) | For link type permissions, the details of the users to whom permission was granted. Read-only. |
| grantedToV2                      | [SharePointIdentitySet][]                 | For user type permissions, the details of the users and applications for this permission. Read-only. |
| inheritedFrom                    | ItemReference         | Provides a reference to the ancestor of the current permission, if it's inherited from an ancestor. Read-only. |
| invitation                       | [SharingInvitation][]                     | Details of any associated sharing invitation for this permission. Read-only. |
| link                             | [SharingLink][]                           | Provides the link details of the current permission, if it's a link type permission. Read-only. |
| roles                            | Collection of String                      | The type of permission, for example, `read`. See below for the full list of roles. Read-only. |
| shareId                          | String                                    | A unique token that can be used to access this shared item via the **shares** API. Read-only. |
### [recycleBin ](https://docs.microsoft.com/graph/api/resources/recyclebin?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                                                                                                              |
|:---------|:-------|:-------------------------------------------------------------------------------------------------------------------------|
|id| String | The unique identifier for the **r
### [recycleBinItem ](https://docs.microsoft.com/graph/api/resources/recyclebinitem?view=graph-rest-1.0&tabs=http)
| Property            | Type           | Description                                                                                                                                                                                                      |
|:--------------------|:---------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| deletedDateTime     | DateTimeOffset | Date and time when the item was deleted. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| deletedFromLocation | String         | Relative URL of the list or folder that originally contained the item.                                                                                                                                           |
| id                  | String         | Unique identifier of the delete transaction. Inherited from baseItem.                                                                                                                             |
| name                | String         | Name of the item. Inherited from baseItem.                                                                                                                                                        |
| size                | Int64          | Size of the item in bytes.                                                                                                                                                                                       |
### [remoteItem ](https://docs.microsoft.com/graph/api/resources/remoteitem?view=graph-rest-1.0&tabs=http)

### [sharingInvitation ](https://docs.microsoft.com/graph/api/resources/sharinginvitation?view=graph-rest-1.0&tabs=http)

### [sharingLink ](https://docs.microsoft.com/graph/api/resources/sharinglink?view=graph-rest-1.0&tabs=http)
| Property    | Type          | Description
|:------------|:--------------|:-------------------------------------
| application | [identity][]  | The app the link is associated with.
| preventsDownload | Boolean       | If true then the user can only use this link to view the item on the web, and cannot use it to download the contents of the item. Only for OneDrive for Business and SharePoint.
| scope       | String        | The scope of the link represented by this permission. Value `anonymous` indicates the link is usable by anyone, `organization` indicates the link is only usable for users signed into the same tenant.
| type        | String        | The type of the link created.
| webHtml     | String        | For `embed` links, this property contains the HTML code for an `<iframe>` element that will embed the item in a webpage.
| webUrl      | String        | A URL that opens the item in the browser on the OneDrive website.

### [site ](https://docs.microsoft.com/graph/api/resources/site?view=graph-rest-1.0&tabs=http)
| Property            | Type                                | Description                                                                                    |
| :----------------------- | :---------------------------------- | :--------------------------------------------------------------------------------------------- |
| **createdDateTime**      | DateTimeOffset                      | The date and time the item was created. Read-only.                                             |
| **description**          | string                              | The descriptive text for the site.                                                             |
| **displayName**          | string                              | The full title for the site. Read-only.                                                        |
| **eTag**                 | string                              | ETag for the item. Read-only.                                                                  |
| **id**                   | string                              | The unique identifier of the item. Read-only.                                                  |
| **isPersonalSite**       | bool                                | Identifies whether the site is personal or not. Read-only.                                                  |
| **lastModifiedDateTime** | DateTimeOffset                      | The date and time the item was last modified. Read-only.                                       |
| **name**                 | string                              | The name/title of the item.                                                                  |
| **root**                 | root                     | If present, provides the root site in the site collection. Read-only.            |
| **sharepointIds**        | sharepointIds   | Returns identifiers useful for SharePoint REST compatibility. Read-only.                       |
| **siteCollection**       | siteCollection | Provides details about the site's site collection. Available only on the root site. Read-only. |
| **webUrl**               | string (url)                        | URL that displays the item in the browser. Read-only.                                          |
### [subscription ](https://docs.microsoft.com/graph/api/resources/subscription?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|---|---|---|
| applicationId | String | Optional. Identifier of the application used to create the subscription. Read-only. |
| changeType | String | Required. Indicates the type of change in the subscribed resource that raises a change notification. The supported values are: `created`, `updated`, `deleted`. Multiple values can be combined using a comma-separated list. <br><br>**Note:** <li> Drive root item and list change notifications support only the `updated` changeType. <li>User and group change notifications support `updated` and `deleted` changeType. Use `updated` to receive notifications when user or group is created, updated, or soft deleted. Use `deleted` to receive notifications when user or group is permanently deleted. |
| clientState | String | Optional. Specifies the value of the `clientState` property sent by the service in each change notification. The maximum length is 128 characters. The client can check that the change notification came from the service by comparing the value of the `clientState` property sent with the subscription with the value of the `clientState` property received with each change notification. |
| creatorId | String | Optional. Identifier of the user or service principal that created the subscription. If the app used delegated permissions to create the subscription, this field contains the ID of the signed-in user the app called on behalf of. If the app used application permissions, this field contains the ID of the service principal corresponding to the app. Read-only. |
| encryptionCertificate | String | Optional. A base64-encoded representation of a certificate with a public key used to encrypt resource data in change notifications. Optional but required when **includeResourceData** is `true`. |
| encryptionCertificateId | String | Optional. A custom app-provided identifier to help identify the certificate needed to decrypt resource data. |
| expirationDateTime | DateTimeOffset | Required. Specifies the date and time when the webhook subscription expires. The time is in UTC, and can be an amount of time from subscription creation that varies for the resource subscribed to. For the maximum supported subscription length of time, see Subscription lifetime. |
| id | String | Optional. Unique identifier for the subscription. Read-only. |
| includeResourceData | Boolean | Optional. When set to `true`, change notifications include resource data (such as content of a chat message). |
| latestSupportedTlsVersion | String | Optional. Specifies the latest version of Transport Layer Security (TLS) that the notification endpoint, specified by **notificationUrl**, supports. The possible values are: `v1_0`, `v1_1`, `v1_2`, `v1_3`. </br></br>For subscribers whose notification endpoint supports a version lower than the currently recommended version (TLS 1.2), specifying this property by a set timeline allows them to temporarily use their deprecated version of TLS before completing their upgrade to TLS 1.2. For these subscribers, not setting this property per the timeline would result in subscription operations failing. </br></br>For subscribers whose notification endpoint already supports TLS 1.2, setting this property is optional. In such cases, Microsoft Graph defaults the property to `v1_2`. |
| lifecycleNotificationUrl | String | Required for Teams resources if  the `expirationDateTime` value is more than 1 hour from now; optional otherwise. The URL of the endpoint that receives lifecycle notifications, including `subscriptionRemoved`, `reauthorizationRequired`, and `missed` notifications. This URL must make use of the HTTPS protocol. For more information, see Reduce missing subscriptions and change notifications. |
| notificationQueryOptions | String | Optional. OData query options for specifying value for the targeting resource. Clients receive notifications when resource reaches the state matching the query options provided here. With this new property in the subscription creation payload along with all existing properties, Webhooks deliver notifications whenever a resource reaches the desired state mentioned in the notificationQueryOptions property. For example, when the print job is completed or when a print job resource `isFetchable` property value becomes `true` etc. <br/><br/> Supported only for Universal Print Service. For more information, see Subscribe to change notifications from cloud printing APIs using Microsoft Graph.  |
| notificationUrl | String | Required. The URL of the endpoint that receives the change notifications. This URL must make use of the HTTPS protocol. Any query string parameter included in the notificationUrl property is included in the HTTP POST request when Microsoft Graph sends the change notifications.|
| notificationUrlAppId | String | Optional. The app ID that the subscription service can use to generate the validation token. The value allows the client to validate the authenticity of the notification received. |
| resource | String | Required. Specifies the resource that is monitored for changes. Don't include the base URL (`https://graph.microsoft.com/v1.0/`). See the possible resource path values for each supported resource. |
### [systemfacet](https://docs.microsoft.com/graph/api/resources/systemfacet?view=graph-rest-1.0&tabs=http)

### [Thumbnail ](https://docs.microsoft.com/graph/api/resources/thumbnail?view=graph-rest-1.0&tabs=http)
| Property     | Type   | Description|
| :----------- | :----- | :----------------------------------------------------|
| content      | Stream | The content stream for the thumbnail.|
| height       | Int32  | The height of the thumbnail, in pixels.|
| sourceItemId | String | The unique identifier of the item that provided the thumbnail. This is only available when a folder thumbnail is requested.|
| url          | String | The URL used to fetch the thumbnail content.|
| width        | Int32  | The width of the thumbnail, in pixels.|
### [ThumbnailSet ](https://docs.microsoft.com/graph/api/resources/thumbnailset?view=graph-rest-1.0&tabs=http)
| Property | Type                      | Description                                                                       |
|:---------|:--------------------------|:----------------------------------------------------------------------------------|
| id       | String                    | The ID within the item. Read-only.                                                |
| large    | Thumbnail | A 1920x1920 scaled thumbnail.                                                     |
| medium   | Thumbnail | A 176x176 scaled thumbnail.                                                       |
| small    | Thumbnail | A 48x48 cropped thumbnail.                                                        |
| source   | Thumbnail | A custom thumbnail image or the original image used to generate other thumbnails. |
### [workbookNamedItem ](https://docs.microsoft.com/graph/api/resources/workbooknameditem?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|comment|String|The comment associated with this name.|
|name|String|The name of the object. Read-only.|
|scope|String|Indicates whether the name is scoped to the workbook or to a specific worksheet. Read-only.|
|type|String|The type of reference is associated with the name. Possible values are: `String`, `Integer`, `Double`, `Boolean`, `Range`. Read-only.|
|value|String|The formula that the name is defined to refer to. For example, `=Sheet14!$B$2:$H$12` and `=4.75`. Read-only.|
|visible|Boolean|Indicates whether the object is visible.|
### [workbookTable ](https://docs.microsoft.com/graph/api/resources/workbooktable?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|The unique identifier for the table in the workbook. The value of the identifier remains the same even when the table is renamed. This property should be interpreted as an opaque string value and shouldn't be parsed to any other type. Read-only.|
|name|string|The name of the table.|
|showHeaders|Boolean|Indicates whether the header row is visible or not. This value can be set to show or remove the header row.|
|showTotals|Boolean|Indicates whether the total row is visible or not. This value can be set to show or remove the total row.|
|style|string|A constant value that represents the Table style. Possible values are: `TableStyleLight1` through `TableStyleLight21`, `TableStyleMedium1` through `TableStyleMedium28`, `TableStyleStyleDark1` through `TableStyleStyleDark11`. A custom user-defined style present in the workbook can also be specified.|
|highlightFirstColumn|Boolean|Indicates whether the first column contains special formatting.	|
|highlightLastColumn|Boolean|Indicates whether the last column contains special formatting.	|
|showBandedColumns|Boolean|Indicates whether the columns show banded formatting in which odd columns are highlighted differently from even ones to make reading the table easier.	|
|showBandedRows|Boolean|Indicates whether the rows show banded formatting in which odd rows are highlighted differently from even ones to make reading the table easier.	|
|showFilterButton|Boolean|Indicates whether the filter buttons are visible at the top of each column header. Setting this is only allowed if the table contains a header row.	|
|legacyId|String|A legacy identifier used in older Excel clients. The value of the identifier remains the same even when the table is renamed. This property should be interpreted as an opaque string value and shouldn't be parsed to any other type. Read-only.	|
