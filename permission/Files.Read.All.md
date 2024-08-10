# Files.Read.All

> Allows the app to read all files the signed-in user can access.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /driveitem/retentionLabel](https://docs.microsoft.com/graph/api/driveitem-removeretentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /drives/{drive-id}/items/{item-id}/retentionLabel](https://docs.microsoft.com/graph/api/driveitem-removeretentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/drive/following/{item-id}](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /users/{user-id}/drive/following/{item-id}](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drive/items/{item-id}/content?format={format}](https://docs.microsoft.com/graph/api/driveitem-get-content-format?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drive/root:/{path and filename}:/content?format={format}](https://docs.microsoft.com/graph/api/driveitem-get-content-format?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /driveitem/retentionLabel](https://docs.microsoft.com/graph/api/driveitem-getretentionlabel?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /drives/{drive-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}?$expand=retentionLabel](https://docs.microsoft.com/graph/api/driveitem-getretentionlabel?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /drives/{drive-id}/items/{item-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /drives/{drive-id}/items/{item-id}/analytics](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/analytics/allTime](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/analytics/lastSevenDays](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /drives/{drive-id}/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/getActivitiesByInterval(startDateTime={startDateTime},endDateTime={endDateTime},interval={interval})](https://docs.microsoft.com/graph/api/itemactivitystat-getactivitybyinterval?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/retentionLabel](https://docs.microsoft.com/graph/api/driveitem-getretentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /drives/{drive-id}/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /groups/{group-id}/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{group-id}/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{groupId}/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{groupId}/drives](https://docs.microsoft.com/graph/api/drive-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive](https://docs.microsoft.com/graph/api/drive-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/following](https://docs.microsoft.com/graph/api/drive-list-following?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /me/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/recent](https://docs.microsoft.com/graph/api/drive-recent?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/root:/{item-path}:/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /me/drive/root:/{item-path}:/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /me/drive/root:/{path}:/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/sharedWithMe](https://docs.microsoft.com/graph/api/drive-sharedwithme?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/special/{name}](https://docs.microsoft.com/graph/api/drive-get-specialfolder?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /shares/{shareIdOrEncodedSharingUrl}/driveItem/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /shares/{shareIdOrEncodedSharingUrl}/driveItem/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/analytics](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/analytics/allTime](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/analytics/lastSevenDays](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/getActivitiesByInterval(startDateTime={startDateTime},endDateTime={endDateTime},interval={interval})](https://docs.microsoft.com/graph/api/itemactivitystat-getactivitybyinterval?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/activities](https://docs.microsoft.com/graph/api/activities-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/analytics](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/analytics/allTime](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/analytics/lastSevenDays](https://docs.microsoft.com/graph/api/itemanalytics-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/driveItem](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{site-id}/lists/{list-id}/items/{item-id}/getActivitiesByInterval(startDateTime={startDateTime},endDateTime={endDateTime},interval={interval})](https://docs.microsoft.com/graph/api/itemactivitystat-getactivitybyinterval?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /sites/{siteId}/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /sites/{siteId}/drive/items/{itemId}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /sites/{siteId}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /sites/{siteId}/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /sites/{siteId}/recycleBin/items](https://docs.microsoft.com/graph/api/recyclebin-list-items?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /teams/{id}/channels/{id}/filesFolder](https://docs.microsoft.com/graph/api/channel-get-filesfolder?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /teams/{teamId}/channels/{channelId}/filesFolder](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}/children](https://docs.microsoft.com/graph/api/driveitem-list-children?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}/thumbnails](https://docs.microsoft.com/graph/api/driveitem-list-thumbnails?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}/versions](https://docs.microsoft.com/graph/api/driveitem-list-versions?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}/versions/{version-id}](https://docs.microsoft.com/graph/api/driveitemversion-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/items/{item-id}/versions/{version-id}/content](https://docs.microsoft.com/graph/api/driveitemversion-get-contents?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{user-id}/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{userId}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-get-content?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{userId}/drive/items/{item-id}/contentStream](https://docs.microsoft.com/graph/api/driveitem-get-contentstream?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{userId}/drive/items/{itemId}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{userId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{userId}/drive/root:/{item-path}](https://docs.microsoft.com/graph/api/driveitem-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{userId}/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /driveitem/retentionLabel](https://docs.microsoft.com/graph/api/driveitem-setretentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /drives/{drive-id}/items/{item-id}/retentionLabel](https://docs.microsoft.com/graph/api/driveitem-setretentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /drives/{drive-id}/items/{item-id}/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /drives/{drive-id}/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /drives/{drive-id}/root:/{item-path}:/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /drives/{driveId}/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{group-id}/drive/items/{item-id}/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{group-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{group-id}/drive/root:/{item-path}:/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /groups/{groupId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/drive/items/{item-id}/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/drive/items/{item-id}/unfollow](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/drive/root:/{item-path}:/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /search/query](https://docs.microsoft.com/graph/api/search-query?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /shares/{shareId}/driveItem/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/drive/items/{item-id}/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{site-id}/drive/root:/{item-path}:/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /sites/{siteId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{user-id}/drive/items/{item-id}/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{user-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{user-id}/drive/items/{item-id}/unfollow](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{user-id}/drive/root:/{item-path}:/extractSensitivityLabels](https://docs.microsoft.com/graph/api/driveitem-extractsensitivitylabels?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{userId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|df85f4d6-205c-4ac5-a5ea-6bf408dba283|
|**Consent Type**|User|
|**Display String**|Read all files that user can access|
|**Description**|Allows the app to read all files the signed-in user can access.|
## Application Permission
|||
|-|-|
|**Id**|01d4889c-1287-42c6-ac1f-5d1e02578ef6|
|**Display String**|Read files in all site collections|
|**Description**|Allows the app to read all files in all site collections without a signed in user.|
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
### [extractSensitivityLabelsResult ](https://docs.microsoft.com/graph/api/resources/extractsensitivitylabelsresult?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|labels|sensitivityLabelAssignment collection|List of sensitivity labels assigned to a file.|
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

### [itemRetentionLabel ](https://docs.microsoft.com/graph/api/resources/itemretentionlabel?view=graph-rest-1.0&tabs=http)
| Property                 | Type                                                             | Description                                                                                                                                                                                                                                            |
|:-------------------------|:-----------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| isLabelAppliedExplicitly | Boolean                                                          | Specifies whether the label is applied explicitly on the item. `True` indicates that the label is applied explicitly; otherwise, the label is inherited from its parent. Read-only.                                                                    |
| labelAppliedBy           | identitySet                       | Identity of the user who applied the label. Read-only.                                                                                                                                                                                                 |
| labelAppliedDateTime     | DateTimeOffset                                                   | The date and time when the label was applied on the item. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| name                     | String                                                           | The retention label on the document. Read-write.                                                                                                                                                                                                       |
| retentionSettings        | retentionLabelSettings | The retention settings enforced on the item. Read-write.                                                                                                                                                                                               |
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

### [search-api-overview](https://docs.microsoft.com/graph/api/resources/search-api-overview?view=graph-rest-1.0&tabs=http)

### [searchRequest ](https://docs.microsoft.com/graph/api/resources/searchrequest?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description| 
|:-------------|:------------|:------------|
|aggregationFilters|String collection|Contains one or more filters to obtain search results aggregated and filtered to a specific value of a field. Optional.<br>Build this filter based on a prior search that aggregates by the same field. From the response of the prior search, identify the searchBucket that filters results to the specific value of the field, use the string in its **aggregationFilterToken** property, and build an aggregation filter string in the format **"{field}:\\"{aggregationFilterToken}\\""**. <br>If multiple values for the same field need to be provided, use the strings in its **aggregationFilterToken** property and build an aggregation filter string in the format **"{field}:or(\\"{aggregationFilterToken1}\\",\\"{aggregationFilterToken2}\\")"**. <br>For example, searching and aggregating drive items by file type returns a **searchBucket** for the file type `docx` in the response. You can conveniently use the **aggregationFilterToken** returned for this **searchBucket** in a subsequent search query and filter matches down to drive items of the `docx` file type. Example 1 and example 2 show the actual requests and responses.|
|aggregations|aggregationOption collection|Specifies aggregations (also known as refiners) to be returned alongside search results. Optional.|
|collapseProperties|collapseProperty collection|Contains the ordered collection of fields and limit to collapse results. Optional.|
|contentSources|String collection|Contains the connection to be targeted.|
|enableTopResults|Boolean|This triggers hybrid sort for messages : the first 3 messages are the most relevant. This property is only applicable to entityType=`message`. Optional.|
|entityTypes|entityType collection| One or more types of resources expected in the response. Possible values are: `event`, `message`, `driveItem`, `externalItem`, `site`, `list`, `listItem`, `drive`, `chatMessage`, `person`, `acronym`, `bookmark`.  Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value(s) in this evolvable enum: `chatMessage`, `person`, `acronym`, `bookmark`. See known limitations for those combinations of two or more entity types that are supported in the same search request. Required.|
|fields|String collection |Contains the fields to be returned for each resource object specified in **entityTypes**, allowing customization of the fields returned by default; otherwise, including additional fields such as custom managed properties from SharePoint and OneDrive, or custom fields in **externalItem** from the content that Microsoft Graph connectors bring in. The **fields** property can use the semantic labels applied to properties. For example, if a property is labeled as title, you can retrieve it using the following syntax: `label_title`. Optional.|
|from|Int32|Specifies the offset for the search results. Offset 0 returns the very first result. Optional.|
|query|searchQuery|Contains the query terms. Required.|
|queryAlterationOptions|searchAlterationOptions|Query alteration options formatted in a JSON blob that contains two optional flags related to spelling correction. Optional. |
|region|String|The geographic location for the search. Required for searches that use application permissions. For details, see Get the region value. |
|resultTemplateOptions|resultTemplateOption collection|Provides the search result template options to render search results from connectors.|
|sharePointOneDriveOptions|sharePointOneDriveOptions|Indicates the kind of contents to be searched when a search is performed using application permissions. Optional.|
|size|Int32|The size of the page to be retrieved. The maximum value is 500. Optional.|
|sortProperties|sortProperty collection|Contains the ordered collection of fields and direction to sort results. There can be at most 5 sort properties in the collection. Optional.|
### [searchResponse ](https://docs.microsoft.com/graph/api/resources/searchresponse?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|hitsContainers|searchHitsContainer collection|A collection of search results.|
|queryAlterationResponse|alterationResponse|Provides information related to spelling corrections in the alteration response.|
|resultTemplates|resultTemplate collection|A dictionary of **resultTemplateIds** and associated values, which include the name and JSON schema of the result templates.|
|searchTerms|String collection|Contains the search terms sent in the initial search query.|
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
