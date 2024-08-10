# Bookings.Read.All

> Allows an app to read bookings appointments, businesses, customers, services, and staff on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[](https://docs.microsoft.com/graph/api/bookingbusiness-post-appointments?view=graph-rest-1.0&tabs=http)|
|V1|A|[DELETE /solutions/bookingBusinesses/{id}/appointments/{id}](https://docs.microsoft.com/graph/api/bookingappointment-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A|[DELETE /solutions/bookingbusinesses/{id}/customers/{id}](https://docs.microsoft.com/graph/api/bookingcustomer-delete?view=graph-rest-beta&tabs=http)|
|V1|A|[DELETE /solutions/bookingBusinesses/{id}/customers/{id}](https://docs.microsoft.com/graph/api/bookingcustomer-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses](https://docs.microsoft.com/graph/api/bookingbusiness-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses](https://docs.microsoft.com/graph/api/bookingbusiness-list?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{bookingBusinessesId}/customQuestions](https://docs.microsoft.com/graph/api/bookingbusiness-list-customquestions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{bookingBusinessesId}/customQuestions](https://docs.microsoft.com/graph/api/bookingbusiness-list-customquestions?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{bookingBusinessesId}/customQuestions/{bookingCustomQuestionId}](https://docs.microsoft.com/graph/api/bookingcustomquestion-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{bookingBusinessesId}/customQuestions/{bookingCustomQuestionId}](https://docs.microsoft.com/graph/api/bookingcustomquestion-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}](https://docs.microsoft.com/graph/api/bookingbusiness-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}](https://docs.microsoft.com/graph/api/bookingbusiness-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/appointments](https://docs.microsoft.com/graph/api/bookingbusiness-list-appointments?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/appointments](https://docs.microsoft.com/graph/api/bookingbusiness-list-appointments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/appointments/{id}](https://docs.microsoft.com/graph/api/bookingappointment-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/calendarView?start={start-value}&end={end-value}](https://docs.microsoft.com/graph/api/bookingbusiness-list-calendarview?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/calendarView?start={start-value}&end={end-value}](https://docs.microsoft.com/graph/api/bookingbusiness-list-calendarview?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/customers](https://docs.microsoft.com/graph/api/bookingbusiness-list-customers?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/customers](https://docs.microsoft.com/graph/api/bookingbusiness-list-customers?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/customers/{id}](https://docs.microsoft.com/graph/api/bookingcustomer-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/customers/{id}](https://docs.microsoft.com/graph/api/bookingcustomer-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/services](https://docs.microsoft.com/graph/api/bookingbusiness-list-services?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/services](https://docs.microsoft.com/graph/api/bookingbusiness-list-services?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/services/{id}](https://docs.microsoft.com/graph/api/bookingservice-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/services/{id}](https://docs.microsoft.com/graph/api/bookingservice-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/staffMembers](https://docs.microsoft.com/graph/api/bookingbusiness-list-staffmembers?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/staffMembers](https://docs.microsoft.com/graph/api/bookingbusiness-list-staffmembers?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /solutions/bookingbusinesses/{id}/staffMembers/{id}](https://docs.microsoft.com/graph/api/bookingstaffmember-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /solutions/bookingBusinesses/{id}/staffMembers/{id}](https://docs.microsoft.com/graph/api/bookingstaffmember-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/bookingCurrencies](https://docs.microsoft.com/graph/api/bookingcurrency-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /solutions/bookingCurrencies/{id}](https://docs.microsoft.com/graph/api/bookingcurrency-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /solutions/bookingBusinesses/{id}/appointments/{id}](https://docs.microsoft.com/graph/api/bookingappointment-update?view=graph-rest-1.0&tabs=http)|
|Beta|A|[PATCH /solutions/bookingbusinesses/{id}/customers/{id}](https://docs.microsoft.com/graph/api/bookingcustomer-update?view=graph-rest-beta&tabs=http)|
|V1|A|[PATCH /solutions/bookingBusinesses/{id}/customers/{id}](https://docs.microsoft.com/graph/api/bookingcustomer-update?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /solutions/bookingbusinesses/{id}/appointments](https://docs.microsoft.com/graph/api/bookingbusiness-post-appointments?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /solutions/bookingBusinesses/{id}/appointments](https://docs.microsoft.com/graph/api/bookingbusiness-post-appointments?view=graph-rest-1.0&tabs=http)|
|Beta|A|[POST /solutions/bookingbusinesses/{id}/getStaffAvailability](https://docs.microsoft.com/graph/api/bookingbusiness-getstaffavailability?view=graph-rest-beta&tabs=http)|
|V1|A|[POST /solutions/bookingBusinesses/{id}/getStaffAvailability](https://docs.microsoft.com/graph/api/bookingbusiness-getstaffavailability?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|33b1df99-4b29-4548-9339-7a7b83eaeebc|
|**Consent Type**|User|
|**Display String**|Read bookings information|
|**Description**|Allows an app to read bookings appointments, businesses, customers, services, and staff on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|6e98f277-b046-4193-a4f2-6bf6a78cd491|
|**Display String**|Read all Bookings related resources.|
|**Description**|Allows an app to read Bookings appointments, businesses, customers, services, and staff without a signed-in user.  |
## Resources
### [bookingAppointment ](https://docs.microsoft.com/graph/api/resources/bookingappointment?view=graph-rest-1.0&tabs=http)
| Property     | Type |Description|
|:---------------|:--------|:----------|
|additionalInformation|String|Additional information that is sent to the customer when an appointment is confirmed.|
|anonymousJoinWebUrl|String|The URL of the meeting to join anonymously.|
|appointmentLabel|String|The custom label that can be stamped on this appointment by users.|
|createdDateTime|DateTimeOffset|The date, time, and time zone when the appointment was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.	|
|customerEmailAddress|String|The SMTP address of the bookingCustomer who books the appointment.|
|customerName|String|The customer's name.|
|customerNotes|String|Notes from the customer associated with this appointment. You can get the value only when you read this **bookingAppointment** by its ID. You can set this property only when you initially create an appointment with a new customer.|
|customerPhone|String|The customer's phone number.|
|customers|bookingCustomerInformation collection|A collection of customer properties for an appointment. An appointment contains a list of customer information and each unit will indicate the properties of a customer who is part of that appointment. Optional.|
|customerTimeZone|String|The time zone of the customer. For a list of possible values, see dateTimeTimeZone.|
|duration|Duration|The length of the appointment, denoted in ISO8601 format. |
|end|dateTimeTimeZone|The date, time, and time zone when the appointment ends.|
|filledAttendeesCount|Int32|The current number of customers in the appointment.|
|id|String| The ID of the **bookingAppointment**. Read-only.|
|isCustomerAllowedToManageBooking|Boolean|Indicates that the customer can manage bookings created by the staff. The default value is `false`.|
|isLocationOnline|Boolean|Indicates that the appointment is held online. The default value is `false`.|
|joinWebUrl|String|The URL of the online meeting for the appointment.|
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the booking business was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|maximumAttendeesCount|Int32|The maximum number of customers allowed in an appointment. If **maximumAttendeesCount** of the service is greater than 1, pass valid customer IDs while creating or updating an appointment. To create a customer, use the Create bookingCustomer operation.|
|optOutOfCustomerEmail|Boolean|If `true` indicates that the bookingCustomer for this appointment doesn't wish to receive a confirmation for this appointment.|
|postBuffer|Duration|The amount of time to reserve after the appointment ends, for cleaning up, as an example. The value is expressed in ISO8601 format. |
|preBuffer|Duration|The amount of time to reserve before the appointment begins, for preparation, as an example. The value is expressed in ISO8601 format.|
|price|Double|The regular price for an appointment for the specified bookingService.|
|priceType|bookingPriceType| A setting to provide flexibility for the pricing structure of services. Possible values are: `undefined`, `fixedPrice`, `startingAt`, `hourly`, `free`, `priceVaries`, `callUs`, `notSet`, `unknownFutureValue`.|
|reminders|bookingReminder collection|The collection of customer reminders sent for this appointment. The value of this property is available only when reading this **bookingAppointment** by its ID.|
|selfServiceAppointmentId|String|Another tracking ID for the appointment, if the appointment was created directly by the customer on the scheduling page, as opposed to by a staff member on behalf of the customer.|
|serviceId|String|The ID of the bookingService associated with this appointment.|
|serviceLocation|location|The location where the service is delivered.|
|serviceName|String|The name of the **bookingService** associated with this appointment.<br>This property is optional when creating a new appointment. If not specified, it's computed from the service associated with the appointment by the **serviceId** property.|
|serviceNotes|String|Notes from a bookingStaffMember. The value of this property is available only when reading this **bookingAppointment** by its ID.|
|smsNotificationsEnabled|Boolean|If `true`, indicates SMS notifications will be sent to the customers for the appointment. Default value is `false`.|
|staffMemberIds|String collection|The ID of each bookingStaffMember who is scheduled in this appointment.|
|start|dateTimeTimeZone|The date, time, and time zone when the appointment begins.|
### [bookingBusiness ](https://docs.microsoft.com/graph/api/resources/bookingbusiness?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|address|physicalAddress|The street address of the business. The **address** property, together with **phone** and **webSiteUrl**, appear in the footer of a business scheduling page. The attribute **type** of physicalAddress is not supported in v1.0. Internally we map the addresses to the type `others`.|
|bookingPageSettings|bookingPageSettings|Settings for the published booking page.|
|businessHours|bookingWorkHours collection|The hours of operation for the business.|
|businessType|String|The type of business.|
|createdDateTime|DateTimeOffset|The date, time, and time zone when the booking business was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|defaultCurrencyIso|String|The code for the currency that the business operates in on Microsoft Bookings.|
|displayName|String|The name of the business, which interfaces with customers. This name appears at the top of the business scheduling page.|
|email|String|The email address for the business.|
|id|String|A unique programmatic identifier for the business. Read-only.|
|isPublished|Boolean|The scheduling page has been made available to external customers. Use the **publish** and **unpublish** actions to set this property. Read-only.|
|languageTag|String|The language of the self-service booking page.|
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the booking business was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|phone|String|The telephone number for the business. The **phone** property, together with **address** and **webSiteUrl**, appear in the footer of a business scheduling page.|
|publicUrl|String|The URL for the scheduling page, which is set after you publish or unpublish the page. Read-only.|
|schedulingPolicy|bookingSchedulingPolicy|Specifies how bookings can be created for this business.|
|webSiteUrl|String|The URL of the business web site. The **w
### [bookingCurrency ](https://docs.microsoft.com/graph/api/resources/bookingcurrency?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| A 3-character currency code, based on ISO 4217. For example, the currency code for the US dollar is USD, and for the Australian dollar is AUD. Read-only.|
|symbol|String| The currency symbol. For example, the currency symbol for the US dollar and for the Australian dollar is $.  |
### [bookingCustomer ](https://docs.microsoft.com/graph/api/resources/bookingcustomer?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|addresses|physicalAddress collection|Addresses associated with the customer. The attribute **type** of **physicalAddress** isn't supported in v1.0. Internally we map the addresses to the type `others`.|
|createdDateTime|DateTimeOffset|The date, time, and time zone when the customer was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|The name of the customer.|
|emailAddress|String|The SMTP address of the customer.|
|id|String| The ID of the customer. Read-only. Inherited from bookingCustomerBase.|
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the customer was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|phones|phone collection|Phone numbers associated with the customer, including home, business, and mobile numbers.|
### [bookingCustomerInformation ](https://docs.microsoft.com/graph/api/resources/bookingcustomerinformation?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|customerId|String|The ID of the **bookingCustomer** for this appointment. If no ID is specified when an appointment is created, then a new **bookingCustomer** object is created. Once set, you should consider the **customerId** immutable. |
|customQuestionAnswers|bookingQuestionAnswer collection|It consists of the list of custom questions and answers given by the customer as part of the appointment |
|emailAddress|String| The SMTP address of the bookingCustomer who is booking the appointment |
|location|location| Represents location information for the bookingCustomer who is booking the appointment. |
|name|String|The customer's name. |
|notes|String|Notes from the customer associated with this appointment. You can get the value only when reading this **bookingAppointment** by its ID. You can set this property only when initially creating an appointment with a new customer. After that point, the value is computed from the customer represented by the **customerId**. |
|phone|String|The customer's phone number. |
|timeZone|String|The time zone of the customer. For a list of possible values, see dateTimeTimeZone.|
### [bookingCustomQuestion ](https://docs.microsoft.com/graph/api/resources/bookingcustomquestion?view=graph-rest-1.0&tabs=http)
| Property        | Type              | Description                                                                                               |
| :-------------- | :---------------- | :-------------------------------------------------------------------------------------------------------- |
| answerInputType | answerInputType   | The expected answer type. The possible values are: `text`, `radioButton`, `unknownFutureValue`.     |
| answerOptions   | String collection | List of possible answer values.                                                                    |
| createdDateTime|DateTimeOffset|The date, time, and time zone when the custom question was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
| displayName     | String            | The question. |
| id              | String            | The ID of the custom question. Inherited from entity.                           |
| lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the custom question was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
### [bookingReminder ](https://docs.microsoft.com/graph/api/resources/bookingreminder?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|message|String|The message in the reminder.|
|offset|Duration|The amount of time before the start of an appointment that the reminder should be sent. It's denoted in ISO 8601 format.|
|recipients|bookingReminderRecipients|The persons who should receive the reminder. Possible values are: `allAttendees`, `staff`, `customer`, `unknownFutureValue`.|
### [bookingService ](https://docs.microsoft.com/graph/api/resources/bookingservice?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|additionalInformation|String|Additional information that is sent to the customer when an appointment is confirmed.|
|createdDateTime|DateTimeOffset|The date, time, and time zone when the service was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|customQuestions|bookingQuestionAssignment collection| Contains the set of custom questions associated with a particular service. |
|defaultDuration|Duration|The default length of the service, represented in numbers of days, hours, minutes, and seconds. For example, P11D23H59M59.999999999999S. |
|defaultLocation|location|The default physical location for the service.|
|defaultPrice|Double|The default monetary price for the service.|
|defaultPriceType|bookingPriceType|The default way the service is charged. Possible values are: `undefined`, `fixedPrice`, `startingAt`, `hourly`, `free`, `priceVaries`, `callUs`, `notSet`, `unknownFutureValue`.|
|defaultReminders|bookingReminder collection|The default set of reminders for an appointment of this service. The value of this property is available only when reading this **bookingService** by its ID.|
|description|String|A text description for the service.|
|displayName|String|A service name.|
|id|String|The ID of that service, in a GUID format. Read-only.|
|isAnonymousJoinEnabled|Boolean|Indicates if an anonymousJoinWebUrl(webrtcUrl) is generated for the appointment booked for this service. The default value is `false`. |
|isCustomerAllowedToManageBooking|Boolean|Indicates that the customer can manage bookings created by the staff. The default value is `false`.|
|isHiddenFromCustomers|Boolean|`True` indicates that this service isn't available to customers for booking.|
|isLocationOnline|Boolean|Indicates that the appointments for the service are held online. The default value is `false`.|
|languageTag|String|The language of the self-service booking page.|
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the service was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|maximumAttendeesCount|Int32|The maximum number of customers allowed in a service. If **maximumAttendeesCount** of the service is greater than 1, pass valid customer IDs while creating or updating an appointment. To create a customer, use the Create bookingCustomer operation. |
|notes|String|Additional information about this service.|
|postBuffer|Duration|The time to buffer after an appointment for this service ends, and before the next customer appointment can be booked.|
|preBuffer|Duration|The time to buffer before an appointment for this service can start.|
|schedulingPolicy|bookingSchedulingPolicy|The set of policies that determine how appointments for this type of service should be created and managed.|
|smsNotificationsEnabled|Boolean|True indicates SMS notifications can be sent to the customers for the appointment of the service. Default value is false.|
|staffMemberIds|String collection|Represents those staff members who provide this service. |
|webUrl|String|The URL a customer uses to access the service.|
### [bookingStaffMember ](https://docs.microsoft.com/graph/api/resources/bookingstaffmember?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|availabilityIsAffectedByPersonalCalendar|Boolean|True means that if the staff member is a Microsoft 365 user, the Bookings API would verify the staff member's availability in their personal calendar in Microsoft 365, before making a booking. |
|createdDateTime|DateTimeOffset|The date, time, and time zone when the staff member was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|displayName|String|The name of the staff member, as displayed to customers. Required.|
|emailAddress|String|The email address of the staff member. This email address can be in the same Microsoft 365 tenant as the business, or in a different email domain. This email address can be used if the **sendConfirmationsToOwner** property is set to true in the scheduling policy of the business. Required.|
|id|String| The ID of the staff member, in a GUID format. Read-only.|
|isEmailNotificationEnabled|Boolean|Indicates that a staff member is notified via email when a booking assigned to them is created or changed. The default value is `true`.|
|membershipStatus|bookingStaffMembershipStatus| The membership status of the staff member in the business. Possible values are: `active`, `pendingAcceptance`, `rejectedByStaff`, `unknownFutureValue`. |
|lastUpdatedDateTime|DateTimeOffset|The date, time, and time zone when the staff member was last updated. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|role|bookingStaffRole| The role of the staff member in the business. Possible values are: `guest`, `administrator`, `viewer`, `externalGuest`, `unknownFutureValue`, `scheduler`, `teamMember`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values from this evolvable enum: `scheduler`, `teamMember`. Required. |
|timeZone|String|The time zone of the staff member. For a list of possible values, see dateTimeTimeZone.|
|useBusinessHours|Boolean|True means the staff member's availability is as specified in the **businessHours** property of the business. False means the availability is determined by the staff member's **workingHours** property setting.|
|workingHours|bookingWorkHours collection|The range of hours each day of the week that the staff member is available for booking. By default, they're initialized to be the same as the **b
### [dateTimeTimeZone ](https://docs.microsoft.com/graph/api/resources/datetimetimezone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|dateTime|String|A single point of time in a combined date and time representation (`{date}T{time}`; for example, `2017-08-29T04:00:00.0000000`).|
|timeZone|String|Represents a time zone, for example, "Pacific Standard Time". See below for more possible values.|
### [Location ](https://docs.microsoft.com/graph/api/resources/location?view=graph-rest-1.0&tabs=http)
| Property  | Type   | Description                                                     |
|:----------|:-------|:----------------------------------------------------------------|
| address | physicalAddress |The street address of the location. |
| coordinates | outlookGeoCoordinates | The geographic coordinates and elevation of the location. |
| displayName  | String | The name associated with the location.                       |
| locationEmailAddress | String | Optional email address of the location.              |
| locationUri | String | Optional URI representing the location. |
| locationType | locationType | The type of location. The possible values are: `default`, `conferenceRoom`, `homeAddress`, `businessAddress`,`geoCoordinates`, `streetAddress`, `hotel`, `restaurant`, `localBusiness`, `postalAddress`. Read-only.|
| uniqueId | String | For internal use only.|
| uniqueIdType | locationUniqueIdType | For internal use only. |
### [phone ](https://docs.microsoft.com/graph/api/resources/phone?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|number|string|The phone number.|
|type|phoneType|The type of phone number. The possible values are: `home`, `business`, `mobile`, `other`, `assistant`, `homeFax`, `businessFax`, `otherFax`, `pager`, `radio`.|
### [physicalAddress ](https://docs.microsoft.com/graph/api/resources/physicaladdress?view=graph-rest-1.0&tabs=http)
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|city|String|The city.|
|countryOrRegion|String|The country or region. It's a free-format string value, for example, "United States".|
|postalCode|String|The postal code.|
|state|String|The state.|
|street|String|The street.|
### [staffAvailabilityItem ](https://docs.microsoft.com/graph/api/resources/staffavailabilityitem?view=graph-rest-1.0&tabs=http)
| Property  | Type |Description|
|:---------------|:--------|:----------|
|availabilityItems |availabilityItem collection |Each item in this collection indicates a slot and the status of the staff member.|
|staffId |String |The ID of the staff member.|
