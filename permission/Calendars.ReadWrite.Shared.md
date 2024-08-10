# Calendars.ReadWrite.Shared

> Allows the app to create, read, update and delete events in all calendars in the organization user has permissions to access. This includes delegate and shared calendars.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[POST /me/findMeetingTimes](https://docs.microsoft.com/graph/api/user-findmeetingtimes?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id|userPrincipalName}/findMeetingTimes](https://docs.microsoft.com/graph/api/user-findmeetingtimes?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|12466101-c9b8-439a-8589-dd09ee67e8e9|
|**Consent Type**|User|
|**Display String**|Read and write user and shared calendars|
|**Description**|Allows the app to create, read, update and delete events in all calendars in the organization user has permissions to access. This includes delegate and shared calendars.|
## Resources
### [attendeeBase ](https://docs.microsoft.com/graph/api/resources/attendeebase?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|emailAddress|emailAddress|Includes the name and SMTP address of the attendee.|
|type|attendeeType| The type of attendee. The possible values are: `required`, `optional`, `resource`. Currently if the attendee is a person, findMeetingTimes always considers the person is of the `Required` type.|
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
