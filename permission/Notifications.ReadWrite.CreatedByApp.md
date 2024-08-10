# Notifications.ReadWrite.CreatedByApp

> Allows the app to deliver its notifications on behalf of signed-in users. Also allows the app to read, update, and delete the user's notification items for this app.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|D|[POST /me/notifications/](https://docs.microsoft.com/graph/api/user-post-notifications?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|89497502-6e42-46a2-8cb2-427fd3df970a|
|**Consent Type**|User|
|**Display String**|Deliver and manage user notifications for this app|
|**Description**|Allows the app to deliver its notifications on behalf of signed-in users. Also allows the app to read, update, and delete the user's notification items for this app.|
## Resources
### [projectrome-notification](https://docs.microsoft.com/graph/api/resources/projectrome-notification?view=graph-rest-1.0&tabs=http)
| Property           | Type                                              | Description                                                                                                                                                                                                                                                                                                                                               |
| :----------------- | :------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| targetHostName     | String                                            | Represents the host name of the app to which the calling service wants to post the notification, for the given user. If targeting web endpoints (see **targetPolicy.platformTypes**), ensure that **targetHostName** is the same as the name used when creating a subscription on the client side within the application JSON property.                   |
| appNotificationId  | String                                            | The unique ID set by the app server of a notification that is used to identify and target an individual notification.                                                                                                                                                                                                                                     |
| groupName          | String                                            | The name of the group that this notification belongs to. It is set by the developer for grouping notifications together.                                                                                                                                                                                                                   |
| targetPolicy       | targetPolicyEndpoints | Target policy object handles notification delivery policy for endpoint types that should be targeted (Windows, iOS, Android and WebPush) for the given user.                                                                                                                                                                                              |
| payload            | payloadTypes                   | This is the data content of a raw or visual user notification that will be delivered to and consumed by the app client receiving this notification.                                                                                                                                                                                                       |
| displayTimeToLive  | Int32                                             | Sets how long (in seconds) this notification content stays in each platform's notification viewer. For example, when the notification is delivered to a Windows device, the value of this property is passed on to ToastNotification.ExpirationTime, which determines how long the toast notification stays in the user's Windows Action Center.  |
| expirationDateTime | DateTimeOffset                                    | Sets a UTC expiration date and time on a user notification using ISO 8601 format (for example, midnight UTC on Jan 1, 2019 would look like this: `'2019-01-01T00:00:00Z'`). When time is up, the notification is removed from the Microsoft Graph notification feed store completely and is no longer part of notification history. Max value is 30 days. |
| priority           | string                                            | Indicates the priority of a raw user notification. Visual notifications are sent with high priority by default. Valid values are `None`, `High` and `Low`.                                                                                                                                                                                                |
| fallbackPolicy     | fallbackpolicy               | Optional fallback policy object handles notification fallback policy for iOS endpoints only and is designed to be used for high-priority raw notifications that might not be delivered to devices due to platform specific restrictions (for example battery saver mode).                                                                                        |
