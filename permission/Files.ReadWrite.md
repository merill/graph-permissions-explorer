# Files.ReadWrite

> Allows the app to read, create, update and delete the signed-in user's files.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[](https://docs.microsoft.com/graph/api/workbook-post-tables?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /drives/{drive-id}/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /drives/{drive-id}/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /groups/{group-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/following/{item-id}](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /me/drive/items/{id}/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/tables/{id|name}](https://docs.microsoft.com/graph/api/table-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}](https://docs.microsoft.com/graph/api/worksheet-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}](https://docs.microsoft.com/graph/api/chart-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}](https://docs.microsoft.com/graph/api/table-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /me/drive/root:/{item-path}:/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/tables/{id|name}](https://docs.microsoft.com/graph/api/table-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}](https://docs.microsoft.com/graph/api/worksheet-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}](https://docs.microsoft.com/graph/api/chart-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/names/{name}](https://docs.microsoft.com/graph/api/nameditem-delete?view=graph-rest-beta&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}](https://docs.microsoft.com/graph/api/table-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /sites/{site-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /sites/{siteId}/drive/items/{itemId}](https://docs.microsoft.com/graph/api/driveitem-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{user-id}/drive/following/{item-id}](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{user-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /users/{userId}/drive/items/{itemId}](https://docs.microsoft.com/graph/api/driveitem-delete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /drive/items/{id}/workbook/comments/{id}/replies/{id}](https://docs.microsoft.com/graph/api/workbookcommentreply-get?view=graph-rest-beta&tabs=http)|
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
|V1|D|[GET /me/drive/items/{id}/workbook/application](https://docs.microsoft.com/graph/api/workbookapplication-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/comments](https://docs.microsoft.com/graph/api/workbook-list-comments?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/comments/{id}](https://docs.microsoft.com/graph/api/workbookcomment-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/comments/{id}/replies](https://docs.microsoft.com/graph/api/workbookcomment-list-replies?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/comments/{id}/replies/{id}](https://docs.microsoft.com/graph/api/workbookcommentreply-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/comments/{id}/task](https://docs.microsoft.com/graph/api/workbookdocumenttask-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/comments/{id}/task/changes](https://docs.microsoft.com/graph/api/workbookdocumenttask-list-changes?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/comments/{id}/task/changes/{id}](https://docs.microsoft.com/graph/api/workbookdocumenttaskchange-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names](https://docs.microsoft.com/graph/api/workbook-list-names?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range](https://docs.microsoft.com/graph/api/nameditem-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/boundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/BoundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/Cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/Column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/entireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/EntireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/entireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/EntireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeborder-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/borders/itemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/borders/ItemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/Intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/lastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/LastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/lastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/LastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/lastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/LastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/offsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/OffsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/usedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/names/{name}/range/UsedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/operations/{operation-id}](https://docs.microsoft.com/graph/api/workbookoperation-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tableRowOperationResult(key={operation-id})](https://docs.microsoft.com/graph/api/workbook-tablerowoperationresult?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}](https://docs.microsoft.com/graph/api/table-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/tablecolumn-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range](https://docs.microsoft.com/graph/api/range-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/boundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/BoundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/Cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/Column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/entireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/EntireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/entireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/EntireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeborder-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/itemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/ItemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/Intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/lastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/LastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/lastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/LastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/lastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/LastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/offsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/OffsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/usedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/UsedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/columns/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/range](https://docs.microsoft.com/graph/api/table-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/tablerow-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/rows/{index}/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/rows/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/rows/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/rows/itemAt(index={index})/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/sort](https://docs.microsoft.com/graph/api/tablesort-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/tables/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets](https://docs.microsoft.com/graph/api/workbook-list-worksheets?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/pivotTables](https://docs.microsoft.com/graph/api/workbookworksheet-list-pivottables?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/pivotTables/{id}](https://docs.microsoft.com/graph/api/workbookpivottable-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range(address={address})/visibleView](https://docs.microsoft.com/graph/api/workbookrange-visibleview?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range(address={address})/visibleView/itemAt(index={n})](https://docs.microsoft.com/graph/api/workbookrangeview-itemat?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range(address={address})/visibleView/range](https://docs.microsoft.com/graph/api/workbookrangeview-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range(address={address})/visibleView/rows](https://docs.microsoft.com/graph/api/workbookrangeview-list-rows?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range/columnsAfter(count=n)](https://docs.microsoft.com/graph/api/workbookrange-columnsafter?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range/columnsBefore(count=n)](https://docs.microsoft.com/graph/api/workbookrange-columnsbefore?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range/rowsAbove(count=n)](https://docs.microsoft.com/graph/api/workbookrange-rowsabove?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/range/rowsBelow(count=n)](https://docs.microsoft.com/graph/api/workbookrange-rowsbelow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/tasks](https://docs.microsoft.com/graph/api/workbookworksheet-list-tasks?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/tasks/{id}](https://docs.microsoft.com/graph/api/workbookdocumenttask-get?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/tasks/{id}/changes](https://docs.microsoft.com/graph/api/workbookdocumenttask-list-changes?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id}/tasks/{id}/changes/{id}](https://docs.microsoft.com/graph/api/workbookdocumenttaskchange-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}](https://docs.microsoft.com/graph/api/worksheet-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/cell(row={row},column={column})](https://docs.microsoft.com/graph/api/worksheet-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/Cell(row={row},column={column})](https://docs.microsoft.com/graph/api/worksheet-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts](https://docs.microsoft.com/graph/api/chart-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}](https://docs.microsoft.com/graph/api/chart-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis](https://docs.microsoft.com/graph/api/chartaxis-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis](https://docs.microsoft.com/graph/api/chartaxis-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorgridlines/format/line](https://docs.microsoft.com/graph/api/chartlineformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis](https://docs.microsoft.com/graph/api/chartaxis-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/minorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/dataLabels](https://docs.microsoft.com/graph/api/chartdatalabels-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/image](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/Image(width=0,height=0,fittingMode='fit')](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/image(width=640,height=480,fittingMode='fit')](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/image(width=640,height=480)](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/image(width=640)](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/legend](https://docs.microsoft.com/graph/api/chartlegend-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series](https://docs.microsoft.com/graph/api/chartseries-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}](https://docs.microsoft.com/graph/api/chartseries-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points](https://docs.microsoft.com/graph/api/chartpoint-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points/{point-id}](https://docs.microsoft.com/graph/api/chartpoint-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points/itemAt(index={index})](https://docs.microsoft.com/graph/api/chartpointscollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points/ItemAt(index={index})](https://docs.microsoft.com/graph/api/chartpointscollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/itemAt(index={index})](https://docs.microsoft.com/graph/api/chartseriescollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/ItemAt(index={index})](https://docs.microsoft.com/graph/api/chartseriescollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/title](https://docs.microsoft.com/graph/api/charttitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/itemAt(index={index})](https://docs.microsoft.com/graph/api/chartcollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/ItemAt(index={index})](https://docs.microsoft.com/graph/api/chartcollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/names](https://docs.microsoft.com/graph/api/worksheet-list-names?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/protection](https://docs.microsoft.com/graph/api/worksheetprotection-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range](https://docs.microsoft.com/graph/api/worksheet-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')](https://docs.microsoft.com/graph/api/range-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/boundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/BoundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/Cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/Column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/entireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/EntireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/EntireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format](https://docs.microsoft.com/graph/api/rangeformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders](https://docs.microsoft.com/graph/api/rangeborder-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/itemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/ItemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/fill](https://docs.microsoft.com/graph/api/rangefill-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/font](https://docs.microsoft.com/graph/api/rangefont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/Intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/lastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/LastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/lastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/LastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/lastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/LastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/offsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/OffsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/usedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/UsedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>'/entireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}](https://docs.microsoft.com/graph/api/table-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/tablecolumn-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/range](https://docs.microsoft.com/graph/api/tablecolumn-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/range](https://docs.microsoft.com/graph/api/table-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/tablerow-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/itemAt(index={index})range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/sort](https://docs.microsoft.com/graph/api/tablesort-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/usedRange](https://docs.microsoft.com/graph/api/worksheet-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/items/{id}/workbook/worksheets/{id|name}/UsedRange](https://docs.microsoft.com/graph/api/worksheet-usedrange?view=graph-rest-beta&tabs=http)|
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
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/application](https://docs.microsoft.com/graph/api/workbookapplication-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/comments](https://docs.microsoft.com/graph/api/workbook-list-comments?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/comments/{id}/replies](https://docs.microsoft.com/graph/api/workbookcomment-list-replies?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/comments/{id}/replies/{id}](https://docs.microsoft.com/graph/api/workbookcommentreply-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names](https://docs.microsoft.com/graph/api/workbook-list-names?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range](https://docs.microsoft.com/graph/api/nameditem-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/boundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/BoundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/Cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/Column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/entireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/EntireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/entireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/EntireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeborder-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders/itemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders/ItemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/Intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/lastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/LastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/lastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/LastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/lastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/LastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/offsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/OffsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/usedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/names/{name}/range/UsedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tableRowOperationResult(key={operation-id})](https://docs.microsoft.com/graph/api/workbook-tablerowoperationresult?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}](https://docs.microsoft.com/graph/api/table-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/tablecolumn-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range](https://docs.microsoft.com/graph/api/range-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/boundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/BoundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/Cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/Column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/entireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/EntireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/entireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/EntireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeborder-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/itemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/ItemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/Intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/lastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/LastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/lastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/LastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/lastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/LastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/offsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/OffsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/usedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/UsedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/range](https://docs.microsoft.com/graph/api/table-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/tablerow-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/{index}/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/itemAt(index={index})/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/sort](https://docs.microsoft.com/graph/api/tablesort-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/tables/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets](https://docs.microsoft.com/graph/api/workbook-list-worksheets?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/pivotTables](https://docs.microsoft.com/graph/api/workbookworksheet-list-pivottables?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/pivotTables/{id}](https://docs.microsoft.com/graph/api/workbookpivottable-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range(address={address})/visibleView](https://docs.microsoft.com/graph/api/workbookrange-visibleview?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range(address={address})/visibleView/itemAt(index={n})](https://docs.microsoft.com/graph/api/workbookrangeview-itemat?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range(address={address})/visibleView/range](https://docs.microsoft.com/graph/api/workbookrangeview-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range(address={address})/visibleView/rows](https://docs.microsoft.com/graph/api/workbookrangeview-list-rows?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range/columnsAfter(count=n)](https://docs.microsoft.com/graph/api/workbookrange-columnsafter?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range/columnsBefore(count=n)](https://docs.microsoft.com/graph/api/workbookrange-columnsbefore?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range/rowsAbove(count=n)](https://docs.microsoft.com/graph/api/workbookrange-rowsabove?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range/rowsBelow(count=n)](https://docs.microsoft.com/graph/api/workbookrange-rowsbelow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id}/tasks](https://docs.microsoft.com/graph/api/workbookworksheet-list-tasks?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}](https://docs.microsoft.com/graph/api/worksheet-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/cell(row={row},column={column})](https://docs.microsoft.com/graph/api/worksheet-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/Cell(row={row},column={column})](https://docs.microsoft.com/graph/api/worksheet-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts](https://docs.microsoft.com/graph/api/chart-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}](https://docs.microsoft.com/graph/api/chart-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis](https://docs.microsoft.com/graph/api/chartaxis-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis](https://docs.microsoft.com/graph/api/chartaxis-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorgridlines/format/line](https://docs.microsoft.com/graph/api/chartlineformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis](https://docs.microsoft.com/graph/api/chartaxis-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/minorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/dataLabels](https://docs.microsoft.com/graph/api/chartdatalabels-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/image](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/Image(width=0,height=0,fittingMode='fit')](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/image(width=640,height=480,fittingMode='fit')](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/image(width=640,height=480)](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/image(width=640)](https://docs.microsoft.com/graph/api/chart-image?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/legend](https://docs.microsoft.com/graph/api/chartlegend-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series](https://docs.microsoft.com/graph/api/chartseries-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}](https://docs.microsoft.com/graph/api/chartseries-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points](https://docs.microsoft.com/graph/api/chartpoint-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points/{point-id}](https://docs.microsoft.com/graph/api/chartpoint-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points/itemAt(index={index})](https://docs.microsoft.com/graph/api/chartpointscollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points/ItemAt(index={index})](https://docs.microsoft.com/graph/api/chartpointscollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/itemAt(index={index})](https://docs.microsoft.com/graph/api/chartseriescollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/ItemAt(index={index})](https://docs.microsoft.com/graph/api/chartseriescollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/title](https://docs.microsoft.com/graph/api/charttitle-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/itemAt(index={index})](https://docs.microsoft.com/graph/api/chartcollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/ItemAt(index={index})](https://docs.microsoft.com/graph/api/chartcollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/names](https://docs.microsoft.com/graph/api/worksheet-list-names?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/protection](https://docs.microsoft.com/graph/api/worksheetprotection-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range](https://docs.microsoft.com/graph/api/worksheet-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')](https://docs.microsoft.com/graph/api/range-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/boundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/BoundingRect](https://docs.microsoft.com/graph/api/range-boundingrect?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/Cell](https://docs.microsoft.com/graph/api/range-cell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/Column](https://docs.microsoft.com/graph/api/range-column?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/entireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/EntireColumn](https://docs.microsoft.com/graph/api/range-entirecolumn?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/EntireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format](https://docs.microsoft.com/graph/api/rangeformat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders](https://docs.microsoft.com/graph/api/rangeborder-list?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/itemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/ItemAt(index={index})](https://docs.microsoft.com/graph/api/rangebordercollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/fill](https://docs.microsoft.com/graph/api/rangefill-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/font](https://docs.microsoft.com/graph/api/rangefont-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/Intersection](https://docs.microsoft.com/graph/api/range-intersection?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/lastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/LastCell](https://docs.microsoft.com/graph/api/range-lastcell?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/lastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/LastColumn](https://docs.microsoft.com/graph/api/range-lastcolumn?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/lastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/LastRow](https://docs.microsoft.com/graph/api/range-lastrow?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/offsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/OffsetRange](https://docs.microsoft.com/graph/api/range-offsetrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/usedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/UsedRange](https://docs.microsoft.com/graph/api/range-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>'/entireRow](https://docs.microsoft.com/graph/api/range-entirerow?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables](https://docs.microsoft.com/graph/api/table-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}](https://docs.microsoft.com/graph/api/table-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/tablecolumn-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/tablecolumn-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/tablecolumn-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/range](https://docs.microsoft.com/graph/api/tablecolumn-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/tablecolumn-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablecolumncollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/dataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/DataBodyRange](https://docs.microsoft.com/graph/api/table-databodyrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/headerRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/HeaderRowRange](https://docs.microsoft.com/graph/api/table-headerrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/range](https://docs.microsoft.com/graph/api/table-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/tablerow-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/itemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/ItemAt(index={index})](https://docs.microsoft.com/graph/api/tablerowcollection-itemat?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/itemAt(index={index})/range](https://docs.microsoft.com/graph/api/tablerow-range?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/sort](https://docs.microsoft.com/graph/api/tablesort-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/totalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/TotalRowRange](https://docs.microsoft.com/graph/api/table-totalrowrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/usedRange](https://docs.microsoft.com/graph/api/worksheet-usedrange?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/UsedRange](https://docs.microsoft.com/graph/api/worksheet-usedrange?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /me/drive/root:/{path}:/permissions](https://docs.microsoft.com/graph/api/driveitem-list-permissions?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root/delta](https://docs.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root/search(q='{search-text}')](https://docs.microsoft.com/graph/api/driveitem-search?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/root/subscriptions/socketIo](https://docs.microsoft.com/graph/api/subscriptions-socketio?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/drive/special/{name}](https://docs.microsoft.com/graph/api/drive-get-specialfolder?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /shares/{shareIdOrEncodedSharingUrl}](https://docs.microsoft.com/graph/api/shares-get?view=graph-rest-1.0&tabs=http)|
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
|V1|D|[PATCH /drives/{drive-id}/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-move?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /drives/{drive-id}/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /groups/{group-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-move?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/names/{name}/range](https://docs.microsoft.com/graph/api/range-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/names/{name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/items/{id}/workbook/names/{name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/names/{name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/names/{name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/names/{name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}](https://docs.microsoft.com/graph/api/table-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range](https://docs.microsoft.com/graph/api/range-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}](https://docs.microsoft.com/graph/api/worksheet-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}](https://docs.microsoft.com/graph/api/chart-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis](https://docs.microsoft.com/graph/api/chartaxis-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis](https://docs.microsoft.com/graph/api/chartaxis-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorgridlines/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis](https://docs.microsoft.com/graph/api/chartaxis-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/minorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/dataLabels](https://docs.microsoft.com/graph/api/chartdatalabels-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/legend](https://docs.microsoft.com/graph/api/chartlegend-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}](https://docs.microsoft.com/graph/api/chartseries-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/title](https://docs.microsoft.com/graph/api/charttitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')](https://docs.microsoft.com/graph/api/range-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format](https://docs.microsoft.com/graph/api/rangeformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/fill](https://docs.microsoft.com/graph/api/rangefill-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/font](https://docs.microsoft.com/graph/api/rangefont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}](https://docs.microsoft.com/graph/api/table-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-move?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}](https://docs.microsoft.com/graph/api/nameditem-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}/range](https://docs.microsoft.com/graph/api/range-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}](https://docs.microsoft.com/graph/api/table-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range](https://docs.microsoft.com/graph/api/range-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format](https://docs.microsoft.com/graph/api/rangeformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/fill](https://docs.microsoft.com/graph/api/rangefill-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/font](https://docs.microsoft.com/graph/api/rangefont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}](https://docs.microsoft.com/graph/api/worksheet-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}](https://docs.microsoft.com/graph/api/chart-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis](https://docs.microsoft.com/graph/api/chartaxis-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis](https://docs.microsoft.com/graph/api/chartaxis-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorgridlines/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines/format/line](https://docs.microsoft.com/graph/api/chartlineformat-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis](https://docs.microsoft.com/graph/api/chartaxis-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/format/font](https://docs.microsoft.com/graph/api/chartfont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/majorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/minorGridlines](https://docs.microsoft.com/graph/api/chartgridlines-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/valueAxis/title](https://docs.microsoft.com/graph/api/chartaxistitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/dataLabels](https://docs.microsoft.com/graph/api/chartdatalabels-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/legend](https://docs.microsoft.com/graph/api/chartlegend-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}](https://docs.microsoft.com/graph/api/chartseries-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/title](https://docs.microsoft.com/graph/api/charttitle-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')](https://docs.microsoft.com/graph/api/range-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format](https://docs.microsoft.com/graph/api/rangeformat-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders(<sideIndex>)](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-beta&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders/{sideIndex}](https://docs.microsoft.com/graph/api/rangeborder-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/fill](https://docs.microsoft.com/graph/api/rangefill-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/font](https://docs.microsoft.com/graph/api/rangefont-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}](https://docs.microsoft.com/graph/api/table-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}](https://docs.microsoft.com/graph/api/tablecolumn-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/{index}](https://docs.microsoft.com/graph/api/tablerow-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/sort/fields/icon](https://docs.microsoft.com/graph/api/icon-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /sites/{site-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-move?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /sites/{site-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{user-id}/drive/items/{item-id}](https://docs.microsoft.com/graph/api/driveitem-move?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /users/{user-id}/drive/items/{item-id}/permissions/{perm-id}](https://docs.microsoft.com/graph/api/permission-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /drive/bundles/{driveItemId}/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /drive/following/{driveItemId}/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /drive/items/{driveItemId}/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /drive/root/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /drive/special/{driveItemId}/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /drives/{drive-id}/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{drive-id}/items/{item-id}/invite](https://docs.microsoft.com/graph/api/driveitem-invite?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{drive-id}/items/{item-id}/permanentDelete](https://docs.microsoft.com/graph/api/driveitem-permanentdelete?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /drives/{drive-id}/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /drives/{drive-id}/items/{item-id}/permissions/{perm-id}/revokeGrants](https://docs.microsoft.com/graph/api/permission-revokegrants?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /drives/{drive-id}/items/{parent-item-id}/children](https://docs.microsoft.com/graph/api/driveitem-post-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/checkin](https://docs.microsoft.com/graph/api/driveitem-checkin?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/checkout](https://docs.microsoft.com/graph/api/driveitem-checkout?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/copy](https://docs.microsoft.com/graph/api/driveitem-copy?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/createLink](https://docs.microsoft.com/graph/api/driveitem-createlink?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /drives/{driveId}/items/{itemId}/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /drives/{driveId}/items/{itemId}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/driveitemversion-restore?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /drives/{drivesId}/root/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /groups/{group-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{group-id}/drive/items/{item-id}/invite](https://docs.microsoft.com/graph/api/driveitem-invite?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /groups/{group-id}/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /groups/{group-id}/drive/items/{item-id}/permissions/{perm-id}/revokeGrants](https://docs.microsoft.com/graph/api/permission-revokegrants?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /groups/{group-id}/drive/items/{parent-item-id}/children](https://docs.microsoft.com/graph/api/driveitem-post-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/checkin](https://docs.microsoft.com/graph/api/driveitem-checkin?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/checkout](https://docs.microsoft.com/graph/api/driveitem-checkout?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/copy](https://docs.microsoft.com/graph/api/driveitem-copy?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/createLink](https://docs.microsoft.com/graph/api/driveitem-createlink?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /groups/{groupId}/drive/items/{itemId}/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /groups/{groupId}/drive/items/{itemId}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/driveitemversion-restore?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/application/calculate](https://docs.microsoft.com/graph/api/workbookapplication-calculate?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/closeSession](https://docs.microsoft.com/graph/api/workbook-closesession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/comments/{id}/replies](https://docs.microsoft.com/graph/api/workbookcomment-post-replies?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/createSession](https://docs.microsoft.com/graph/api/workbook-createsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/clear](https://docs.microsoft.com/graph/api/range-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/delete](https://docs.microsoft.com/graph/api/range-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/format/autofitColumns](https://docs.microsoft.com/graph/api/rangeformat-autofitcolumns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/format/autofitRows](https://docs.microsoft.com/graph/api/rangeformat-autofitrows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeformat-post-borders?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/format/fill/clear](https://docs.microsoft.com/graph/api/rangefill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/insert](https://docs.microsoft.com/graph/api/range-insert?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/merge](https://docs.microsoft.com/graph/api/range-merge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/Row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/sort/apply](https://docs.microsoft.com/graph/api/rangesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/{name}/range/unmerge](https://docs.microsoft.com/graph/api/range-unmerge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/names/add](https://docs.microsoft.com/graph/api/nameditem-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/refreshSession](https://docs.microsoft.com/graph/api/workbook-refreshsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/clearFilters](https://docs.microsoft.com/graph/api/table-clearfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/table-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/filter/apply](https://docs.microsoft.com/graph/api/filter-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/filter/clear](https://docs.microsoft.com/graph/api/filter-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/clear](https://docs.microsoft.com/graph/api/range-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/delete](https://docs.microsoft.com/graph/api/range-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/autofitColumns](https://docs.microsoft.com/graph/api/rangeformat-autofitcolumns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/autofitRows](https://docs.microsoft.com/graph/api/rangeformat-autofitrows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeformat-post-borders?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/format/fill/clear](https://docs.microsoft.com/graph/api/rangefill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/insert](https://docs.microsoft.com/graph/api/range-insert?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/merge](https://docs.microsoft.com/graph/api/range-merge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/Row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/sort/apply](https://docs.microsoft.com/graph/api/rangesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/{id|name}/range/unmerge](https://docs.microsoft.com/graph/api/range-unmerge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/columns/add](https://docs.microsoft.com/graph/api/tablecolumncollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/convertToRange](https://docs.microsoft.com/graph/api/table-converttorange?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/reapplyFilters](https://docs.microsoft.com/graph/api/table-reapplyfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/table-post-rows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/rows/add](https://docs.microsoft.com/graph/api/tablerowcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/sort/apply](https://docs.microsoft.com/graph/api/tablesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/sort/clear](https://docs.microsoft.com/graph/api/tablesort-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/{id|name}/sort/reapply](https://docs.microsoft.com/graph/api/tablesort-reapply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/tables/add](https://docs.microsoft.com/graph/api/workbook-post-tables?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id}/pivotTables/{id}/refresh](https://docs.microsoft.com/graph/api/workbookpivottable-refresh?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{id}/workbook/worksheets/{id}/pivotTables/refreshAll](https://docs.microsoft.com/graph/api/workbookpivottable-refreshall?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id}/range/resizedRange(deltaRows={n}, deltaColumns={n})](https://docs.microsoft.com/graph/api/workbookrange-resizedrange?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/](https://docs.microsoft.com/graph/api/worksheet-post-charts?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/line/clear](https://docs.microsoft.com/graph/api/chartlineformat-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/line/clear](https://docs.microsoft.com/graph/api/chartlineformat-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines/format/line/clear](https://docs.microsoft.com/graph/api/chartlineformat-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/format/fill/clear](https://docs.microsoft.com/graph/api/chartfill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/format/fill/setSolidColor](https://docs.microsoft.com/graph/api/chartfill-setsolidcolor?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/legend/format/fill/clear](https://docs.microsoft.com/graph/api/chartfill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/legend/format/fill/setSolidColor](https://docs.microsoft.com/graph/api/chartfill-setsolidcolor?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series](https://docs.microsoft.com/graph/api/chart-post-series?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points](https://docs.microsoft.com/graph/api/chartseries-post-points?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/setData](https://docs.microsoft.com/graph/api/chart-setdata?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/setPosition](https://docs.microsoft.com/graph/api/chart-setposition?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/title/format/fill/clear](https://docs.microsoft.com/graph/api/chartfill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/{name}/title/format/fill/setSolidColor](https://docs.microsoft.com/graph/api/chartfill-setsolidcolor?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/charts/add](https://docs.microsoft.com/graph/api/chartcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/names/add](https://docs.microsoft.com/graph/api/nameditem-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/pivotTables/refreshAll](https://docs.microsoft.com/graph/api/workbookpivottable-refreshall?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/protection/protect](https://docs.microsoft.com/graph/api/worksheetprotection-protect?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/protection/unprotect](https://docs.microsoft.com/graph/api/worksheetprotection-unprotect?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/clear](https://docs.microsoft.com/graph/api/range-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/delete](https://docs.microsoft.com/graph/api/range-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/autofitColumns](https://docs.microsoft.com/graph/api/rangeformat-autofitcolumns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/autofitRows](https://docs.microsoft.com/graph/api/rangeformat-autofitrows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/borders](https://docs.microsoft.com/graph/api/rangeformat-post-borders?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/format/fill/clear](https://docs.microsoft.com/graph/api/rangefill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/insert](https://docs.microsoft.com/graph/api/range-insert?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/merge](https://docs.microsoft.com/graph/api/range-merge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/Row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/sort/apply](https://docs.microsoft.com/graph/api/rangesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/range(address='<address>')/unmerge](https://docs.microsoft.com/graph/api/range-unmerge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/clearFilters](https://docs.microsoft.com/graph/api/table-clearfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/table-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/filter/apply](https://docs.microsoft.com/graph/api/filter-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/filter/clear](https://docs.microsoft.com/graph/api/filter-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/columns/add](https://docs.microsoft.com/graph/api/tablecolumncollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/convertToRange](https://docs.microsoft.com/graph/api/table-converttorange?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/reapplyFilters](https://docs.microsoft.com/graph/api/table-reapplyfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/table-post-rows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/rows/add](https://docs.microsoft.com/graph/api/tablerowcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/sort/apply](https://docs.microsoft.com/graph/api/tablesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/sort/clear](https://docs.microsoft.com/graph/api/tablesort-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/{id|name}/sort/reapply](https://docs.microsoft.com/graph/api/tablesort-reapply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/{id|name}/tables/add](https://docs.microsoft.com/graph/api/tablecollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{id}/workbook/worksheets/add](https://docs.microsoft.com/graph/api/worksheetcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/checkin](https://docs.microsoft.com/graph/api/driveitem-checkin?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/checkout](https://docs.microsoft.com/graph/api/driveitem-checkout?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/copy](https://docs.microsoft.com/graph/api/driveitem-copy?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/invite](https://docs.microsoft.com/graph/api/driveitem-invite?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{item-id}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /me/drive/items/{item-id}/permissions/{perm-id}/revokeGrants](https://docs.microsoft.com/graph/api/permission-revokegrants?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/unfollow](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{item-id}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/driveitemversion-restore?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{itemId}:/{fileName}:/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{itemId}/createLink](https://docs.microsoft.com/graph/api/driveitem-createlink?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/items/{itemId}/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{parent-item-id}/children](https://docs.microsoft.com/graph/api/driveitem-post-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/items/{parentItemId}:/{fileName}:/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/application/calculate](https://docs.microsoft.com/graph/api/workbookapplication-calculate?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/closeSession](https://docs.microsoft.com/graph/api/workbook-closesession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/comments/{id}/replies](https://docs.microsoft.com/graph/api/workbookcomment-post-replies?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/createSession](https://docs.microsoft.com/graph/api/workbook-createsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/clear](https://docs.microsoft.com/graph/api/range-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/delete](https://docs.microsoft.com/graph/api/range-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/autofitColumns](https://docs.microsoft.com/graph/api/rangeformat-autofitcolumns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/autofitRows](https://docs.microsoft.com/graph/api/rangeformat-autofitrows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeformat-post-borders?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/format/fill/clear](https://docs.microsoft.com/graph/api/rangefill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/insert](https://docs.microsoft.com/graph/api/range-insert?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/merge](https://docs.microsoft.com/graph/api/range-merge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/Row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/sort/apply](https://docs.microsoft.com/graph/api/rangesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/{name}/range/unmerge](https://docs.microsoft.com/graph/api/range-unmerge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/names/add](https://docs.microsoft.com/graph/api/nameditem-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/refreshSession](https://docs.microsoft.com/graph/api/workbook-refreshsession?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/clearFilters](https://docs.microsoft.com/graph/api/table-clearfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/table-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/filter/apply](https://docs.microsoft.com/graph/api/filter-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/filter/clear](https://docs.microsoft.com/graph/api/filter-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/clear](https://docs.microsoft.com/graph/api/range-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/delete](https://docs.microsoft.com/graph/api/range-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/autofitColumns](https://docs.microsoft.com/graph/api/rangeformat-autofitcolumns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/autofitRows](https://docs.microsoft.com/graph/api/rangeformat-autofitrows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/borders](https://docs.microsoft.com/graph/api/rangeformat-post-borders?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/format/fill/clear](https://docs.microsoft.com/graph/api/rangefill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/insert](https://docs.microsoft.com/graph/api/range-insert?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/merge](https://docs.microsoft.com/graph/api/range-merge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/Row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/sort/apply](https://docs.microsoft.com/graph/api/rangesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/{id|name}/range/unmerge](https://docs.microsoft.com/graph/api/range-unmerge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/columns/add](https://docs.microsoft.com/graph/api/tablecolumncollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/convertToRange](https://docs.microsoft.com/graph/api/table-converttorange?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/reapplyFilters](https://docs.microsoft.com/graph/api/table-reapplyfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/table-post-rows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/rows/add](https://docs.microsoft.com/graph/api/tablerowcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/sort/apply](https://docs.microsoft.com/graph/api/tablesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/sort/clear](https://docs.microsoft.com/graph/api/tablesort-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/{id|name}/sort/reapply](https://docs.microsoft.com/graph/api/tablesort-reapply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/tables/add](https://docs.microsoft.com/graph/api/workbook-post-tables?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id}/pivotTables/{id}/refresh](https://docs.microsoft.com/graph/api/workbookpivottable-refresh?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id}/pivotTables/refreshAll](https://docs.microsoft.com/graph/api/workbookpivottable-refreshall?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id}/range/resizedRange(deltaRows={n}, deltaColumns={n})](https://docs.microsoft.com/graph/api/workbookrange-resizedrange?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/](https://docs.microsoft.com/graph/api/worksheet-post-charts?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/categoryAxis/format/line/clear](https://docs.microsoft.com/graph/api/chartlineformat-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/format/line/clear](https://docs.microsoft.com/graph/api/chartlineformat-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/axes/seriesAxis/majorGridlines/format/line/clear](https://docs.microsoft.com/graph/api/chartlineformat-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/format/fill/clear](https://docs.microsoft.com/graph/api/chartfill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/format/fill/setSolidColor](https://docs.microsoft.com/graph/api/chartfill-setsolidcolor?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/legend/format/fill/clear](https://docs.microsoft.com/graph/api/chartfill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/legend/format/fill/setSolidColor](https://docs.microsoft.com/graph/api/chartfill-setsolidcolor?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series](https://docs.microsoft.com/graph/api/chart-post-series?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/series/{series-id}/points](https://docs.microsoft.com/graph/api/chartseries-post-points?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/setData](https://docs.microsoft.com/graph/api/chart-setdata?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/setPosition](https://docs.microsoft.com/graph/api/chart-setposition?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/title/format/fill/clear](https://docs.microsoft.com/graph/api/chartfill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/{name}/title/format/fill/setSolidColor](https://docs.microsoft.com/graph/api/chartfill-setsolidcolor?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/charts/add](https://docs.microsoft.com/graph/api/chartcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/names/add](https://docs.microsoft.com/graph/api/nameditem-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/pivotTables/refreshAll](https://docs.microsoft.com/graph/api/workbookpivottable-refreshall?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/protection/protect](https://docs.microsoft.com/graph/api/worksheetprotection-protect?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/protection/unprotect](https://docs.microsoft.com/graph/api/worksheetprotection-unprotect?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/clear](https://docs.microsoft.com/graph/api/range-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/delete](https://docs.microsoft.com/graph/api/range-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/autofitColumns](https://docs.microsoft.com/graph/api/rangeformat-autofitcolumns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/autofitRows](https://docs.microsoft.com/graph/api/rangeformat-autofitrows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/borders](https://docs.microsoft.com/graph/api/rangeformat-post-borders?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/format/fill/clear](https://docs.microsoft.com/graph/api/rangefill-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/insert](https://docs.microsoft.com/graph/api/range-insert?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/merge](https://docs.microsoft.com/graph/api/range-merge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/Row](https://docs.microsoft.com/graph/api/range-row?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/sort/apply](https://docs.microsoft.com/graph/api/rangesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/range(address='<address>')/unmerge](https://docs.microsoft.com/graph/api/range-unmerge?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/clearFilters](https://docs.microsoft.com/graph/api/table-clearfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns](https://docs.microsoft.com/graph/api/table-post-columns?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/filter/apply](https://docs.microsoft.com/graph/api/filter-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/{id|name}/filter/clear](https://docs.microsoft.com/graph/api/filter-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/columns/add](https://docs.microsoft.com/graph/api/tablecolumncollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/convertToRange](https://docs.microsoft.com/graph/api/table-converttorange?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/reapplyFilters](https://docs.microsoft.com/graph/api/table-reapplyfilters?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows](https://docs.microsoft.com/graph/api/table-post-rows?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/rows/add](https://docs.microsoft.com/graph/api/tablerowcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/sort/apply](https://docs.microsoft.com/graph/api/tablesort-apply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/sort/clear](https://docs.microsoft.com/graph/api/tablesort-clear?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/{id|name}/sort/reapply](https://docs.microsoft.com/graph/api/tablesort-reapply?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/{id|name}/tables/add](https://docs.microsoft.com/graph/api/tablecollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/drive/root:/{item-path}:/workbook/worksheets/add](https://docs.microsoft.com/graph/api/worksheetcollection-add?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /shares/{encoded-sharing-url}/permission/grant](https://docs.microsoft.com/graph/api/permission-grant?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /shares/{shareId}/driveItem/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /shares/{sharesId}/driveItem/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|Beta|D|[POST /shares/{sharesId}/root/discardCheckout](https://docs.microsoft.com/graph/api/driveitem-discardcheckout?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /sites/{site-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /sites/{site-id}/drive/items/{item-id}/permissions/{perm-id}/revokeGrants](https://docs.microsoft.com/graph/api/permission-revokegrants?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /sites/{site-id}/drive/items/{parent-item-id}/children](https://docs.microsoft.com/graph/api/driveitem-post-children?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /sites/{site-id}/lists/{list-id}/items/{listItem-id}/driveItem/permissions/{perm-id}/revokeGrants](https://docs.microsoft.com/graph/api/permission-revokegrants?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/checkin](https://docs.microsoft.com/graph/api/driveitem-checkin?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/checkout](https://docs.microsoft.com/graph/api/driveitem-checkout?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/copy](https://docs.microsoft.com/graph/api/driveitem-copy?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/createLink](https://docs.microsoft.com/graph/api/driveitem-createlink?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /sites/{siteId}/drive/items/{itemId}/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/invite](https://docs.microsoft.com/graph/api/driveitem-invite?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /sites/{siteId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /sites/{siteId}/drive/items/{itemId}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/driveitemversion-restore?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /sites/{siteId}/lists/{listId}/items/{itemId}/createLink](https://docs.microsoft.com/graph/api/listitem-createlink?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /sites/{siteId}/pages/{pageId}/microsoft.graph.sitePage/publish](https://docs.microsoft.com/graph/api/sitepage-publish?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{user-id}/drive/items/{item-id}/follow](https://docs.microsoft.com/graph/api/driveitem-follow?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{user-id}/drive/items/{item-id}/permissions/{perm-id}/revokeGrants](https://docs.microsoft.com/graph/api/permission-revokegrants?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{user-id}/drive/items/{item-id}/unfollow](https://docs.microsoft.com/graph/api/driveitem-unfollow?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{user-id}/drive/items/{parent-item-id}/children](https://docs.microsoft.com/graph/api/driveitem-post-children?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/checkin](https://docs.microsoft.com/graph/api/driveitem-checkin?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/checkout](https://docs.microsoft.com/graph/api/driveitem-checkout?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/copy](https://docs.microsoft.com/graph/api/driveitem-copy?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/createLink](https://docs.microsoft.com/graph/api/driveitem-createlink?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{userId}/drive/items/{itemId}/createUploadSession](https://docs.microsoft.com/graph/api/driveitem-createuploadsession?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/invite](https://docs.microsoft.com/graph/api/driveitem-invite?view=graph-rest-1.0&tabs=http)|
|Beta|D|[POST /users/{userId}/drive/items/{itemId}/permissions](https://docs.microsoft.com/graph/api/driveitem-post-permissions?view=graph-rest-beta&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/preview](https://docs.microsoft.com/graph/api/driveitem-preview?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{userId}/drive/items/{itemId}/versions/{version-id}/restoreVersion](https://docs.microsoft.com/graph/api/driveitemversion-restore?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /drives/{drive-id}/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-put-content?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /groups/{group-id}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-put-content?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /me/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-put-content?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /sites/{site-id}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-put-content?view=graph-rest-1.0&tabs=http)|
|V1|D|[PUT /users/{user-id}/drive/items/{item-id}/content](https://docs.microsoft.com/graph/api/driveitem-put-content?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|5c28f0bf-8a70-41f1-8ab2-9032436ddb65|
|**Consent Type**|User|
|**Display String**|Have full access to user files|
|**Description**|Allows the app to read, create, update and delete the signed-in user's files.|
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
### [driveRecipient ](https://docs.microsoft.com/graph/api/resources/driverecipient?view=graph-rest-1.0&tabs=http)

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

### [json ](https://docs.microsoft.com/graph/api/resources/json?view=graph-rest-1.0&tabs=http)

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

### [sharedDriveItem ](https://docs.microsoft.com/graph/api/resources/shareddriveitem?view=graph-rest-1.0&tabs=http)
| Property | Type                          | Description                                                      |
| :------- | :---------------------------- | :--------------------------------------------------------------- |
| id       | String                        | The unique identifier for the share being accessed.              |
| name     | String                        | The display name of the shared item.                             |
| owner    | identitySet | Information about the owner of the shared item being referenced. |
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
### [sitePage ](https://docs.microsoft.com/graph/api/resources/sitepage?view=graph-rest-1.0&tabs=http)
| Property             | Type                                                                   | Description                                                                                                                     |
| :------------------- | :--------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| contentType          | contentTypeInfo                   | The content type of this item. Inherited from baseSitePage.                                                                            |
| createdBy            | identitySet                           |  Identity of the creator of this item. Read-only. Inherited from baseSitePage.                                                                            |
| createdDateTime      | DateTimeOffset                                                       | The date and time the item was created. Read-only. Inherited from baseSitePage.                                                                            |
| description          | String                                                               | The descriptive text for the item. Inherited from baseSitePage.                                                                            |
| eTag                 | String                                                               | ETag for the item. Inherited from baseSitePage.                                                                            |
| id                   | String                                                               | The unique identifier of the item. Inherited from baseSitePage.                                                                                |
| lastModifiedBy       | identitySet                           | TIdentity of the last modifier of this item. Read-only. Inherited from baseSitePage.                                                                            |
| lastModifiedDateTime | DateTimeOffset                                                       | The date and time the item was last modified. Read-only. Inherited from baseSitePage.                                                                            |
| name                 | String                                                               | The name of the item. Inherited from baseSitePage.    |
| pageLayout           | pageLayoutType       | The name of the page layout of the page. The possible values are: `microsoftReserved`, `article`, `home`, `unknownFutureValue`. Inherited from baseSitePage. |
| parentReference      | itemReference                         | Parent information, if the item has a parent. Inherited from baseSitePage.                                                                            |
| promotionKind        | pagePromotionType | Indicates the promotion kind of the sitePage. The possible values are: `microsoftReserved`, `page`, `newsPost`, `unknownFutureValue`.                                                                                    |
| publishingState      | publicationFacet                   | The publishing status and the MM.mm version of the page.  Inherited from baseSitePage.                                                                       |
| reactions            | reactionsFacet                       | Reactions information for the page.                                                                                             |
| showComments         | Boolean                                                                | Determines whether or not to show comments at the bottom of the page.                                                 |
| showRecommendedPages | Boolean                                                                | Determines whether or not to show recommended pages at the bottom of the page.                                        |
| thumbnailWebUrl      | String                                                                 | Url of the sitePage's thumbnail image                                                                                           |
| title                | String                                                                 | Title of the sitePage.  Inherited from baseSitePage. |
| titleArea            | titleArea                                 | Title area on the SharePoint page.                                                                                              |
| webUrl               | String                                                                 | URL that displays the resource in the browser. Read-only. Inherited from baseSitePage.                                                                            |
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
### [uploadSession ](https://docs.microsoft.com/graph/api/resources/uploadsession?view=graph-rest-1.0&tabs=http)
| Property	     | Type              |Description
|:-------------------|:------------------|:------------------------------------
| expirationDateTime | DateTimeOffset    | The date and time in UTC that the upload session will expire. The complete file must be uploaded before this expiration time is reached.|
| nextExpectedRanges | String collection | A collection of byte ranges that the server is missing for the file. These ranges are zero indexed and of the format "start-end" (for example "0-26" to indicate the first 27 bytes of the file). When uploading files as Outlook attachments, instead of a collection of ranges, this property always indicates a single value "{start}", the location in the file where the next upload should begin.|
| uploadUrl          | String            | The URL endpoint that accepts PUT requests for byte ranges of the file.|
### [workbookApplication ](https://docs.microsoft.com/graph/api/resources/workbookapplication?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|calculationMode|string|Returns the calculation mode used in the workbook. Possible values are: `Automatic`, `AutomaticExceptTables`, `Manual`.|
### [workbookChart ](https://docs.microsoft.com/graph/api/resources/workbookchart?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|height|double|Represents the height, in points, of the chart object.|
|id|string|Gets a chart based on its position in the collection. Read-only.|
|left|double|The distance, in points, from the left side of the chart to the worksheet origin.|
|name|string|Represents the name of a chart object.|
|top|double|Represents the distance, in points, from the top edge of the object to the top of row 1 (on a worksheet) or the top of the chart area (on a chart).|
|width|double|Represents the width, in points, of the chart object.|
### [workbookChartAxis ](https://docs.microsoft.com/graph/api/resources/workbookchartaxis?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
| id       |string   | Unique identifier. Read-only.|
|majorUnit|Json|Represents the interval between two major tick marks. Can be set to a numeric value or an empty string.  The returned value is always a number.|
|maximum|Json|Represents the maximum value on the value axis.  Can be set to a numeric value or an empty string (for automatic axis values).  The returned value is always a number.|
|minimum|Json|Represents the minimum value on the value axis. Can be set to a numeric value or an empty string (for automatic axis values).  The returned value is always a number.|
|minorUnit|Json|Represents the interval between two minor tick marks. "Can be set to a numeric value or an empty string (for automatic axis values). The returned value is always a number.|
### [workbookChartAxisTitle ](https://docs.microsoft.com/graph/api/resources/workbookchartaxistitle?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|text|string|Represents the axis title.|
|visible|Boolean|A Boolean that specifies the visibility of an axis title.|
### [workbookChartDataLabels ](https://docs.microsoft.com/graph/api/resources/workbookchartdatalabels?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|position|string|DataLabelPosition value that represents the position of the data label. The possible values are: `None`, `Center`, `InsideEnd`, `InsideBase`, `OutsideEnd`, `Left`, `Right`, `Top`, `Bottom`, `BestFit`, `Callout`.|
|separator|string|String that represents the separator used for the data labels on a chart.|
|showBubbleSize|Boolean|Boolean value that represents whether the data label bubble size is visible.|
|showCategoryName|Boolean|Boolean value that represents whether the data label category name is visible.|
|showLegendKey|Boolean|Boolean value that represents whether the data label legend key is visible.|
|showPercentage|Boolean|Boolean value that represents whether the data label percentage is visible.|
|showSeriesName|Boolean|Boolean value that represents whether the data label series name is visible.|
|showValue|Boolean|Boolean value that represents whether the data label value is visible.|
### [workbookChartFont ](https://docs.microsoft.com/graph/api/resources/workbookchartfont?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|bold|Boolean|Indicates whether the fond is bold.|
|color|string|The HTML color code representation of the text color. For example #FF0000 represents Red.|
|italic|Boolean|Indicates whether the fond is italic.|
|name|string|The font name. For example "Calibri".|
|size|double|The size of the font. For example,  11.|
|underline|string|The type of underlining applied to the font. The possible values are: `None`, `Single`.|
### [workbookChartGridlines ](https://docs.microsoft.com/graph/api/resources/workbookchartgridlines?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|visible|Boolean|Indicates whether the axis gridlines are visible.|
### [workbookChartLegend ](https://docs.microsoft.com/graph/api/resources/workbookchartlegend?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|overlay|Boolean|Indicates whether the chart legend should overlap with the main body of the chart.|
|position|string|Represents the position of the legend on the chart. The possible values are: `Top`, `Bottom`, `Left`, `Right`, `Corner`, `Custom`.|
|visible|Boolean|Indicates whether the chart legend is visible.|
### [workbookChartLineFormat ](https://docs.microsoft.com/graph/api/resources/workbookchartlineformat?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|color|string|The HTML color code that represents the color of lines in the chart.|
### [workbookChartPoint ](https://docs.microsoft.com/graph/api/resources/workbookchartpoint?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|ID|string|unique identifier|
|value|Json|The value of a chart point. Read-only.|
### [workbookChartSeries ](https://docs.microsoft.com/graph/api/resources/workbookchartseries?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|name|string|The name of a series in a chart.|
### [workbookChartTitle ](https://docs.microsoft.com/graph/api/resources/workbookcharttitle?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|overlay|Boolean|Indicates whether the chart title will overlay the chart or not.|
|text|string|The title text of the chart.|
|visible|Boolean|Indicates whether the chart title is visible.|
### [workbookComment ](https://docs.microsoft.com/graph/api/resources/workbookcomment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|content|String|The content of the comment.|
|contentType|String|The content type of the comment.|
|id|String|The unique identifier of the comment. Read-only.|
### [workbookCommentReply ](https://docs.microsoft.com/graph/api/resources/workbookcommentreply?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|content|String|The content of the reply.|
|contentType|String|The content type for the reply.|
|id|String|The unique identifier for the reply. Read-only.|
### [workbookDocumentTask ](https://docs.microsoft.com/graph/api/resources/workbookdocumenttask?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignees|workbookEmailIdentity collection| A collection of user identities the task is assigned to.|
|completedBy|workbookEmailIdentity|The identity of the user who completed the task. Nullable.|
|completedDateTime|DateTimeOffset|Date and time when the task was completed. Nullable. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|createdBy|workbookEmailIdentity|A user identity that creates the task. Nullable.|
|createdDateTime|DateTimeOffset|Date and time when the task was created. Nullable. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String|The unique identifier for the task. Inherited from entity.|
|percentComplete|Int32 | An integer value from `0` to `100` that represents the percentage of the completion of the task. `100` means that the task is completed. Nullable.|
|priority|Int32| An integer value from `0` to `10` that represents the priority of the task. A lower value indicates a higher priority. Nullable.|
|startAndDueDateTime|workbookDocumentTaskSchedule|Start and due date of the task. Nullable.|
|title|String| The title of the task.|
### [workbookDocumentTaskChange ](https://docs.microsoft.com/graph/api/resources/workbookdocumenttaskchange?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|assignee|workbookEmailIdentity|The user identity the task is assigned to. Only present when the **type** property is `assign`. Nullable.|
|changedBy|workbookEmailIdentity|The identity of the user who performs the change.|
|commentId|String|The identifier of the associated comment.|
|createdDateTime|DateTimeOffset|Date and time when the task was changed. Nullable. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|dueDateTime|DateTimeOffset|The due date and time for the task. Only present when the **type** property is `setSchedule`. Nullable. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String|The unique identifier of the change history. Inherited from entity.|
|percentComplete|Int32|An integer value from `0` to `100` that represents the percentage of the completion of the task and associated comment. `100` means that the task and associated comment are completed. If you change the completion from `100` to a lower value, the associated task and comment are reactivated. Only present when the **type** property is `setPercentComplete`. Nullable.|
|priority|Int32|An integer value from `0` to `10` that represents the priority of the task. A lower value indicates a higher priority. `5` indicates the default priority if not set. Only present when the **type** property is `setPriority`. Nullable.|
|startDateTime|DateTimeOffset|The start date and time for the task. Only present when the **type** property is `setSchedule`. Nullable. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|title|String|The title of the task. Only present when the **type** property is `setTitle`. Nullable.|
|type|String|The type of the change history. Possible values are: `create`, `assign`, `unassign`, `unassignAll`, `setPriority`, `setTitle`, `setPercentComplete`, `setSchedule`, `remove`, `restore`, `undo`. |
|undoChangeId|String| The ID of the **w
### [workbookIcon ](https://docs.microsoft.com/graph/api/resources/workbookicon?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|index|int|The index of the icon in the given set.|
|set|string|The set that the icon is part of. The possible values are: `Invalid`, `ThreeArrows`, `ThreeArrowsGray`, `ThreeFlags`, `ThreeTrafficLights1`, `ThreeTrafficLights2`, `ThreeSigns`, `ThreeSymbols`, `ThreeSymbols2`, `FourArrows`, `FourArrowsGray`, `FourRedToBlack`, `FourRating`, `FourTrafficLights`, `FiveArrows`, `FiveArrowsGray`, `FiveRating`, `FiveQuarters`, `ThreeStars`, `ThreeTriangles`, `FiveBoxes`.|
### [workbookNamedItem ](https://docs.microsoft.com/graph/api/resources/workbooknameditem?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|comment|String|The comment associated with this name.|
|name|String|The name of the object. Read-only.|
|scope|String|Indicates whether the name is scoped to the workbook or to a specific worksheet. Read-only.|
|type|String|The type of reference is associated with the name. Possible values are: `String`, `Integer`, `Double`, `Boolean`, `Range`. Read-only.|
|value|String|The formula that the name is defined to refer to. For example, `=Sheet14!$B$2:$H$12` and `=4.75`. Read-only.|
|visible|Boolean|Indicates whether the object is visible.|
### [workbookOperation ](https://docs.microsoft.com/graph/api/resources/workbookoperation?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|error|workbookOperationError| The error returned by the operation.|
|id|String| The identifier for the operation. Read-only.|
|resourceLocation|String| The resource URI for the result.|
|status|String| The current status of the operation. Possible values are: `NotStarted`, `Running`, `Completed`, `Failed`.|
|statusCode| integer| Status code of the operation. |
### [workbookPivotTable ](https://docs.microsoft.com/graph/api/resources/workbookpivottable?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|ID|String| The identifier for the pivot table. Read-only.|
|name|String|The name of the pivot table.	|
### [workbookRange ](https://docs.microsoft.com/graph/api/resources/workbookrange?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|address|string|Represents the range reference in A1-style. Address value contains the Sheet reference (for example, Sheet1!A1:B4). Read-only.|
|addressLocal|string|Represents range reference for the specified range in the language of the user. Read-only.|
|cellCount|int|Number of cells in the range. Read-only.|
|columnCount|int|Represents the total number of columns in the range. Read-only.|
|columnHidden|Boolean|Indicates whether all columns of the current range are hidden.|
|columnIndex|int|Represents the column number of the first cell in the range. Zero-indexed. Read-only.|
|formulas|Json|Represents the formula in A1-style notation.|
|formulasLocal|Json|Represents the formula in A1-style notation, in the user's language and number-formatting locale.  For example, the English "=SUM(A1, 1.5)" formula would become "=SUMME(A1; 1,5)" in German.|
|formulasR1C1|Json|Represents the formula in R1C1-style notation.|
|hidden|Boolean|Represents if all cells of the current range are hidden. Read-only.|
|numberFormat|Json|Represents Excel's number format code for the given cell.|
|rowCount|int|Returns the total number of rows in the range. Read-only.|
|rowHidden|Boolean|Indicates whether all rows of the current range are hidden.|
|rowIndex|int|Returns the row number of the first cell in the range. Zero-indexed. Read-only.|
|text|Json|Text values of the specified range. The Text value doesn't depend on the cell width. The # sign substitution that happens in Excel UI doesn't affect the text value returned by the API. Read-only.|
|valueTypes|Json|Represents the type of data of each cell. The possible values are: `Unknown`, `Empty`, `String`, `Integer`, `Double`, `Boolean`, `Error`. Read-only.|
|values|Json|Represents the raw values of the specified range. The data returned can be of type string, number, or a Boolean. Cell that contains an error returns the error string.|
### [workbookRangeBorder ](https://docs.microsoft.com/graph/api/resources/workbookrangeborder?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|color|string|The HTML color code that represents the color of the border line. Can either be of the form #RRGGBB, for example "FFA500", or a named HTML color, for example "orange".|
|id|string|The border identifier. The possible values are: `EdgeTop`, `EdgeBottom`, `EdgeLeft`, `EdgeRight`, `InsideVertical`, `InsideHorizontal`, `DiagonalDown`, `DiagonalUp`. Read-only.|
|sideIndex|string|Indicates the specific side of the border. The possible values are: `EdgeTop`, `EdgeBottom`, `EdgeLeft`, `EdgeRight`, `InsideVertical`, `InsideHorizontal`, `DiagonalDown`, `DiagonalUp`. Read-only.|
|style|string|Indicates the line style for the border. The possible values are: `None`, `Continuous`, `Dash`, `DashDot`, `DashDotDot`, `Dot`, `Double`, `SlantDashDot`.|
|weight|string|The weight of the border around a range. The possible values are: `Hairline`, `Thin`, `Medium`, `Thick`.|
### [workbookRangeFill ](https://docs.microsoft.com/graph/api/resources/workbookrangefill?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|color|string|HTML color code representing the color of the border line. Can either be of the form #RRGGBB, for example "FFA500", or be a named HTML color, for example "orange".|
### [workbookRangeFont ](https://docs.microsoft.com/graph/api/resources/workbookrangefont?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|bold|Boolean|Inidicates whether the font is bold.|
|color|string|The HTML color code representation of the text color. For example, #FF0000 represents the color red.|
|italic|Boolean|Inidicates whether the font is italic.|
|name|string|The font name. For example, "Calibri".|
|size|double|The font size.|
|underline|string|The type of underlining applied to the font. The possible values are: `None`, `Single`, `Double`, `SingleAccountant`, `DoubleAccountant`.|
### [workbookRangeFormat ](https://docs.microsoft.com/graph/api/resources/workbookrangeformat?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|columnWidth|double|The width of all columns within the range. If the column widths aren't uniform, null will be returned.|
|horizontalAlignment|string|The horizontal alignment for the specified object. Possible values are: `General`, `Left`, `Center`, `Right`, `Fill`, `Justify`, `CenterAcrossSelection`, `Distributed`.|
|rowHeight|double|The height of all rows in the range. If the row heights aren't uniform null will be returned.|
|verticalAlignment|string|The vertical alignment for the specified object. Possible values are: `Top`, `Center`, `Bottom`, `Justify`, `Distributed`.|
|wrapText|Boolean|Indicates whether Excel wraps the text in the object. A null value indicates that the entire range doesn't have a uniform wrap setting.|
### [workbookRangeView ](https://docs.microsoft.com/graph/api/resources/workbookrangeview?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|cellAddresses|Json|The cell addresses.|
|columnCount|Int32|The number of visible columns. Read-only.|
|formulas|Json|The formula in A1-style notation.	|
|formulasLocal|Json|The formula in A1-style notation, in the user's language and number-formatting locale. For example, the English "=SUM(A1, 1.5)" formula would become "=SUMME(A1; 1,5)" in German.	|
|formulasR1C1|Json|Represents the formula in R1C1-style notation.	|
|index|Int32|The index of the range.|
|numberFormat|Json|Excel's number format code for the given cell. Read-only.	|
|rowCount|Int32|The number of visible rows. Read-only.	|
|text|Json|The text values of the specified range. The Text value won't depend on the cell width. The # sign substitution that happens in Excel UI won't affect the text value returned by the API. Read-only.	|
|valueTypes|Json|The type of data of each cell. Read-only. The possible values are: Unknown, Empty, String, Integer, Double, Boolean, Error.	|
|values|Json|The raw values of the specified range view. The data returned could be of type string, number, or a Boolean. Cell that contains an error returns the error string.	|
### [workbookSessionInfo ](https://docs.microsoft.com/graph/api/resources/workbooksessioninfo?view=graph-rest-1.0&tabs=http)
| Property | Type  | Description                               |
|:---------|:------|:------------------------------------------|
| id  | string | ID of the workbook session. |
| persistChanges | Boolean |  `true` for persistent session. `false` for non-persistent session (view mode) |
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
### [workbookTableColumn ](https://docs.microsoft.com/graph/api/resources/workbooktablecolumn?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|The unique identifier for the column within the table. This property should be interpreted as an opaque string value and shouldn't be parsed to any other type. Read-only.|
|index|int|The index of the column within the columns collection of the table. Zero-indexed. Read-only.|
|name|string|The name of the table column.|
|values|Json|TRepresents the raw values of the specified range. The data returned could be of type string, number, or a Boolean. Cell that contain an error will return the error string.|
### [workbookTableRow ](https://docs.microsoft.com/graph/api/resources/workbooktablerow?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|index|Int32|The index of the row within the rows collection of the table. Zero-based. Read-only.|
|values|Json|The raw values of the specified range. The data returned could be of type string, number, or a Boolean. Any cell that contain an error will return the error string.|
### [workbookTableSort ](https://docs.microsoft.com/graph/api/resources/workbooktablesort?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|fields|workbookSortField collection|The list of the current conditions last used to sort the table. Read-only.|
|matchCase|Boolean|Indicates whether the casing impacted the last sort of the table. Read-only.|
|method|string|The Chinese character ordering method last used to sort the table. The possible values are: `PinYin`, `StrokeCount`. Read-only.|
### [workbookWorksheet ](https://docs.microsoft.com/graph/api/resources/workbookworksheet?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|The unique identifier for the worksheet in the workbook. The value of the identifier remains the same even when the worksheet is renamed or moved. Read-only.|
|name|string|The display name of the worksheet.|
|position|int|The zero-based position of the worksheet within the workbook.|
|visibility|string|The visibility of the worksheet. The possible values are: `Visible`, `Hidden`, `VeryHidden`.|
### [workbookWorksheetProtection ](https://docs.microsoft.com/graph/api/resources/workbookworksheetprotection?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|options|workbookWorksheetProtectionOptions|Worksheet protection options. Read-only.|
|protected|Boolean|Indicates whether the worksheet is protected.  Read-only.|
### [workbookWorksheetProtectionOptions ](https://docs.microsoft.com/graph/api/resources/workbookworksheetprotectionoptions?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|allowAutoFilter|Boolean|Indicates whether the worksheet protection option to allow the use of the autofilter feature is enabled.|
|allowDeleteColumns|Boolean|Indicates whether the worksheet protection option to allow deleting columns is enabled.|
|allowDeleteRows|Boolean|Indicates whether the worksheet protection option to allow deleting rows is enabled.|
|allowFormatCells|Boolean|Indicates whether the worksheet protection option to allow formatting cells is enabled.|
|allowFormatColumns|Boolean|Indicates whether the worksheet protection option to allow formatting columns is enabled.|
|allowFormatRows|Boolean|Indicates whether the worksheet protection option to allow formatting rows is enabled.|
|allowInsertColumns|Boolean|Indicates whether the worksheet protection option to allow inserting columns is enabled.|
|allowInsertHyperlinks|Boolean|Indicates whether the worksheet protection option to allow inserting hyperlinks is enabled.|
|allowInsertRows|Boolean|Indicates whether the worksheet protection option to allow inserting rows is enabled.|
|allowPivotTables|Boolean|Indicates whether the worksheet protection option to allow the use of the pivot table feature is enabled.|
|allowSort|Boolean|Indicates whether the worksheet protection option to allow the use of the sort feature is enabled.|
