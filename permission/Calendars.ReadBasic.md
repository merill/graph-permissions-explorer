# Calendars.ReadBasic

> Allows the app to read events in user calendars, except for properties such as body, attachments, and extensions.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/calendar/events/{id}](https://docs.microsoft.com/graph/api/group-get-event?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/calendar/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/group-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/events/{id}](https://docs.microsoft.com/graph/api/group-get-event?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /groups/{id}/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendar/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/user-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendar/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendarGroups](https://docs.microsoft.com/graph/api/user-list-calendargroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendarGroups/{id}](https://docs.microsoft.com/graph/api/calendargroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendarGroups/{id}/calendars/{id}/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendars](https://docs.microsoft.com/graph/api/calendargroup-list-calendars?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendars/{id}/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/calendarView/delta?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /me/events/delta](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/events/delta?startDateTime={start_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendar/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/calendar-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendar/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendarGroups](https://docs.microsoft.com/graph/api/user-list-calendargroups?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendarGroups/{id}](https://docs.microsoft.com/graph/api/calendargroup-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendarGroups/{id}/calendars/{id}/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendars](https://docs.microsoft.com/graph/api/calendargroup-list-calendars?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendars/{id}/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/calendarView?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/user-list-calendarview?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/events/{id}/instances?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-list-instances?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/events/delta](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/events/delta?startDateTime={start_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id | userPrincipalName}/reminderView(startDateTime={startDateTime-value},endDateTime={endDateTime-value})](https://docs.microsoft.com/graph/api/user-reminderview?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/reminderView(startDateTime={startDateTime},endDateTime={endDateTime})](https://docs.microsoft.com/graph/api/user-reminderview?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /users/{id}/calendarView/delta?startDateTime={start_datetime}&endDateTime={end_datetime}](https://docs.microsoft.com/graph/api/event-delta?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/calendar/getSchedule](https://docs.microsoft.com/graph/api/calendar-getschedule?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id|userPrincipalName}/calendar/getSchedule](https://docs.microsoft.com/graph/api/calendar-getschedule?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[Prefer: outlook.timezone="Eastern Standard Time"](https://docs.microsoft.com/graph/api/event-get?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|662d75ba-a364-42ad-adee-f5f880ea4878|
|**Consent Type**|User|
|**Display String**|Read basic details of user calendars|
|**Description**|Allows the app to read events in user calendars, except for properties such as body, attachments, and extensions.|
## Application Permission
|||
|-|-|
|**Id**||
|**Display String**||
|**Description**||
## Resources
### [calendar ](https://docs.microsoft.com/graph/api/resources/calendar?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|allowedOnlineMeetingProviders|onlineMeetingProviderType collection| Represent the online meeting service providers that can be used to create online meetings in this calendar. Possible values are: `unknown`, `skypeForBusiness`, `skypeForConsumer`, `teamsForBusiness`.|
|canEdit |Boolean |`true` if the user can write to the calendar, `false` otherwise. This property is `true` for the user who created the calendar. This property is also `true` for a user who has been shared a calendar and granted write access. |
|canShare |Boolean |`true` if the user has the permission to share the calendar, `false` otherwise. Only the user who created the calendar can share it. |
|canViewPrivateItems |Boolean |`true` if the user can read calendar items that have been marked private, `false` otherwise. |
|changeKey|String|Identifies the version of the calendar object. Every time the calendar is changed, changeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only.|
|color|calendarColor|Specifies the color theme to distinguish the calendar from other calendars in a UI. The property values are: `auto`, `lightBlue`, `lightGreen`, `lightOrange`, `lightGray`, `lightYellow`, `lightTeal`, `lightPink`, `lightBrown`, `lightRed`, `maxColor`.|
|defaultOnlineMeetingProvider|onlineMeetingProviderType|The default online meeting provider for meetings sent from this calendar. Possible values are: `unknown`, `skypeForBusiness`, `skypeForConsumer`, `teamsForBusiness`.|
|hexColor |String |The calendar color, expressed in a hex color code of three hexadecimal values, each ranging from 00 to FF and representing the red, green, or blue components of the color in the RGB color space. If the user has never explicitly set a color for the calendar, this property is empty. Read-only.|
|id|String|The calendar's unique identifier. Read-only.|
|isDefaultCalendar|Boolean|`true` if this is the default calendar where new events are created by default, `false` otherwise.|
|isRemovable|Boolean| Indicates whether this user calendar can be deleted from the user mailbox.|
|isTallyingResponses|Boolean|Indicates whether this user calendar supports tracking of meeting responses. Only meeting invites sent from users' primary calendars support tracking of meeting responses.|
|name|String|The calendar name.|
|owner |emailAddress | If set, this represents the user who created or added the calendar. For a calendar that the user created or added, the **o
### [calendarGroup ](https://docs.microsoft.com/graph/api/resources/calendargroup?view=graph-rest-1.0&tabs=http)
| Property  | Type   | Description                                                                                                                                                                                               |
| :-------- | :----- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| name      | String | The group name.                                                                                                                                                                                           |
| changeKey | String | Identifies the version of the calendar group. Every time the calendar group is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only. |
| classId   | Guid   | The class identifier. Read-only.                                                                                                                                                                          |
| id        | String | The group's unique identifier. Read-only.                                                                                                                                                                 |
### [dateTimeTimeZone ](https://docs.microsoft.com/graph/api/resources/datetimetimezone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|dateTime|String|A single point of time in a combined date and time representation (`{date}T{time}`; for example, `2017-08-29T04:00:00.0000000`).|
|timeZone|String|Represents a time zone, for example, "Pacific Standard Time". See below for more possible values.|
### [event ](https://docs.microsoft.com/graph/api/resources/event?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
|allowNewTimeProposals| Boolean | `true` if the meeting organizer allows invitees to propose a new time when responding; otherwise, `false`. Optional. Default is `true`. |
|attendees|Attendee collection|The collection of attendees for the event.|
|body|ItemBody|The body of the message associated with the event. It can be in HTML or text format.|
|bodyPreview|String|The preview of the message associated with the event. It is in text format.|
|categories|String collection|The categories associated with the event. Each category corresponds to the **displayName** property of an outlookCategory defined for the user.|
|changeKey|String|Identifies the version of the event object. Every time the event is changed, ChangeKey changes as well. This allows Exchange to apply changes to the correct version of the object.|
|createdDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|end|DateTimeTimeZone|The date, time, and time zone that the event ends. By default, the end time is in UTC.|
|hasAttachments|Boolean|Set to true if the event has attachments.|
|hideAttendees|Boolean|When set to `true`, each attendee only sees themselves in the meeting request and meeting **Tracking** list. Default is false.|
|iCalUId|String|A unique identifier for an event across calendars. This ID is different for each occurrence in a recurring series. Read-only.|
|id|String| Unique identifier for the event. !INCLUDE [outlook-beta-id] Case-sensitive and read-only.|
|importance|String|The importance of the event. The possible values are: `low`, `normal`, `high`.|
|isAllDay|Boolean|Set to true if the event lasts all day. If true, regardless of whether it's a single-day or multi-day event, start and end time must be set to midnight and be in the same time zone.|
|isCancelled|Boolean|Set to true if the event has been canceled.|
|isDraft|Boolean|Set to true if the user has updated the meeting in Outlook but has not sent the updates to attendees. Set to false if all changes have been sent, or if the event is an appointment without any attendees.|
|isOnlineMeeting|Boolean| `True` if this event has online meeting information (that is, **onlineMeeting** points to an onlineMeetingInfo resource), `false` otherwise. Default is `false` (**onlineMeeting** is `null`). Optional. <br> After you set **isOnlineMeeting** to `true`, Microsoft Graph initializes **onlineMeeting**. Subsequently Outlook ignores any further changes to **isOnlineMeeting**, and the meeting remains available online. |
|isOrganizer|Boolean|Set to true if the calendar owner (specified by the **owner** property of the calendar) is the organizer of the event (specified by the **organizer** property of the **event**). This also applies if a delegate organized the event on behalf of the owner.|
|isReminderOn|Boolean|Set to true if an alert is set to remind the user of the event.|
|lastModifiedDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|location|Location|The location of the event.|
|locations|Location collection|The locations where the event is held or attended from. The **location** and **locations** properties always correspond with each other. If you update the **location** property, any prior locations in the **locations** collection would be removed and replaced by the new **location** value. |
|onlineMeeting|OnlineMeetingInfo| Details for an attendee to join the meeting online. Default is null. Read-only. <br>After you set the **isOnlineMeeting** and **onlineMeetingProvider** properties to enable a meeting online, Microsoft Graph initializes **onlineMeeting**. When set, the meeting remains available online, and you cannot change the **isOnlineMeeting**, **onlineMeetingProvider**, and **onlneMeeting** properties again.|
|onlineMeetingProvider|onlineMeetingProviderType| Represents the online meeting service provider. By default, **onlineMeetingProvider** is `unknown`. The possible values are `unknown`, `teamsForBusiness`, `skypeForBusiness`, and `skypeForConsumer`. Optional. <br> After you set **onlineMeetingProvider**, Microsoft Graph initializes **onlineMeeting**. Subsequently you cannot change **onlineMeetingProvider** again, and the meeting remains available online. |
|onlineMeetingUrl|String|A URL for an online meeting. The property is set only when an organizer specifies in Outlook that an event is an online meeting such as Skype. Read-only.<br>To access the URL to join an online meeting, use **joinUrl** which is exposed via the **onlineMeeting** property of the **event**. The **onlineMeetingUrl** property will be deprecated in the future. |
|organizer|Recipient|The organizer of the event.|
|originalEndTimeZone|String|The end time zone that was set when the event was created. A value of `tzone://Microsoft/Custom` indicates that a legacy custom time zone was set in desktop Outlook.|
|originalStart|DateTimeOffset|Represents the start time of an event when it is initially created as an occurrence or exception in a recurring series. This property is not returned for events that are single instances. Its date and time information is expressed in ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|originalStartTimeZone|String|The start time zone that was set when the event was created. A value of `tzone://Microsoft/Custom` indicates that a legacy custom time zone was set in desktop Outlook.|
|recurrence|PatternedRecurrence|The recurrence pattern for the event.|
|reminderMinutesBeforeStart|Int32|The number of minutes before the event start time that the reminder alert occurs.|
|responseRequested|Boolean|Default is true, which represents the organizer would like an invitee to send a response to the event.|
|responseStatus|ResponseStatus|Indicates the type of response sent in response to an event message.|
|sensitivity|String| Possible values are: `normal`, `personal`, `private`, `confidential`.|
|seriesMasterId|String|The ID for the recurring series master item, if this event is part of a recurring series.|
|showAs|String|The status to show. Possible values are: `free`, `tentative`, `busy`, `oof`, `workingElsewhere`, `unknown`.|
|start|DateTimeTimeZone|The start date, time, and time zone of the event. By default, the start time is in UTC.|
|subject|String|The text of the event's subject line.|
|transactionId|String|A custom identifier specified by a client app for the server to avoid redundant POST operations in case of client retries to create the same event. This is useful when low network connectivity causes the client to time out before receiving a response from the server for the client's prior create-event request. After you set **transactionId** when creating an event, you cannot change **transactionId** in a subsequent update. This property is only returned in a response payload if an app has set it. Optional.|
|type|String|The event type. Possible values are: `singleInstance`, `occurrence`, `exception`, `seriesMaster`. Read-only|
|webLink|String|The URL to open the event in Outlook on the web.<br/><br/>Outlook on the web opens the event in the browser if you are signed in to your mailbox. Otherwise, Outlook on the web prompts you to sign in.<br/><br/>This URL cannot be accessed from within an iFrame.|
### [reminder ](https://docs.microsoft.com/graph/api/resources/reminder?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|changeKey|String|Identifies the version of the reminder. Every time the reminder is changed, **changeKey** changes as well. This allows Exchange to apply changes to the correct version of the object.|
|eventEndTime|DateTimeTimeZone|The date, time and time zone that the event ends.|
|eventId|String|The unique ID of the event. Read only.|
|eventLocation|Location|The location of the event.|
|eventStartTime|DateTimeTimeZone|The date, time, and time zone that the event starts.|
|eventSubject|String|The text of the event's subject line.|
|eventWebLink|String|The URL to open the event in Outlook on the web.<br/><br/>The event opens in the browser if you're logged in to your mailbox via Outlook on the web. You're prompted to log in if you aren't already logged in with the browser.<br/><br/>This URL can't be accessed from within an iFrame.|
|reminderFireTime|DateTimeTimeZone|The date, time, and time zone that the reminder is set to occur.|
### [scheduleInformation ](https://docs.microsoft.com/graph/api/resources/scheduleinformation?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|availabilityView |String |Represents a merged view of availability of all the items in `scheduleItems`. The view consists of time slots. Availability during each time slot is indicated with: `0`= free or working elswhere, `1`= tentative, `2`= busy, `3`= out of office.<br><br>**Note:** Working elsewhere is set to `0` instead of `4` for backward compatibility. For details, see the Q&A.|
|error |freeBusyError |Error information from attempting to get the availability of the user, distribution list, or resource. |
|scheduleId |String |An SMTP address of the user, distribution list, or resource, identifying an instance of **scheduleInformation**. |
|scheduleItems |scheduleItem collection |Contains the items that describe the availability of the user or resource. |
|workingHours |workingHours |The days of the week and hours in a specific time zone that the user works. These are set as part of the user's mailboxSettings.|
