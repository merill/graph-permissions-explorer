# Calendars.Read.Shared

> Allows the app to read events in all calendars that the user can access, including delegate and shared calendars.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[GET /me/calendars](https://docs.microsoft.com/graph/api/calendargroup-list-calendars?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/calendars](https://docs.microsoft.com/graph/api/calendargroup-list-calendars?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /me/findMeetingTimes](https://docs.microsoft.com/graph/api/user-findmeetingtimes?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/findMeetingTimes](https://docs.microsoft.com/graph/api/user-findmeetingtimes?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|2b9c4092-424d-4249-948d-b43879977640|
|**Consent Type**|User|
|**Display String**|Read user and shared calendars|
|**Description**|Allows the app to read events in all calendars that the user can access, including delegate and shared calendars.|
## Resources
### [attendeeBase ](https://docs.microsoft.com/graph/api/resources/attendeebase?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|emailAddress|emailAddress|Includes the name and SMTP address of the attendee.|
|type|attendeeType| The type of attendee. The possible values are: `required`, `optional`, `resource`. Currently if the attendee is a person, findMeetingTimes always considers the person is of the `Required` type.|
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
### [locationConstraint ](https://docs.microsoft.com/graph/api/resources/locationconstraint?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|isRequired|Boolean|The client requests the service to include in the response a meeting location for the meeting. If this is true and all the resources are busy, findMeetingTimes won't return any meeting time suggestions. If this is false and all the resources are busy, **findMeetingTimes** would still look for meeting times without locations. |
|locations|locationConstraintItem collection|Constraint information for one or more locations that the client requests for the meeting.|
|suggestLocation|Boolean|The client requests the service to suggest one or more meeting locations.|
### [meetingTimeSuggestion ](https://docs.microsoft.com/graph/api/resources/meetingtimesuggestion?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|attendeeAvailability|attendeeAvailability collection|An array that shows the availability status of each attendee for this meeting suggestion.|
|confidence|Double|A percentage that represents the likelhood of all the attendees attending.|
|locations|location collection|An array that specifies the name and geographic location of each meeting location for this meeting suggestion.|
|meetingTimeSlot|timeSlot|A time period suggested for the meeting.|
|order|Int32|Order of meeting time suggestions sorted by their computed confidence value from high to low, then by chronology if there are suggestions with the same confidence. |
|organizerAvailability|freeBusyStatus| Availability of the meeting organizer for this meeting suggestion. The possible values are: `free`, `tentative`, `busy`, `oof`, `workingElsewhere`, `unknown`.|
|suggestionReason|String|Reason for suggesting the meeting time.|
### [meetingTimeSuggestionsResult ](https://docs.microsoft.com/graph/api/resources/meetingtimesuggestionsresult?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|emptySuggestionsReason|String|A reason for not returning any meeting suggestions. The possible values are: `attendeesUnavailable`, `attendeesUnavailableOrUnknown`, `locationsUnavailable`, `organizerUnavailable`, or `unknown`. This property is an empty string if the **meetingTimeSuggestions** property does include any meeting suggestions.|
|meetingTimeSuggestions|meetingTimeSuggestion collection|An array of meeting suggestions.|
### [timeConstraint ](https://docs.microsoft.com/graph/api/resources/timeconstraint?view=graph-rest-1.0&tabs=http)
| Property       | Type    |Description|
|:---------------|:--------|:----------|
|activityDomain|activityDomain|The nature of the activity, optional. The possible values are: `work`, `personal`, `unrestricted`, or `unknown`.|
|timeslots|timeSlot collection|An array of time periods.|
