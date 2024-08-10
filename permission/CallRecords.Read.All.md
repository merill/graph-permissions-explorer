# CallRecords.Read.All

> Allows the app to read call records for all calls and online meetings without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[GET /communications/callRecords](https://docs.microsoft.com/graph/api/callrecords-cloudcommunications-list-callrecords?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/callRecords/{id}](https://docs.microsoft.com/graph/api/callrecords-callrecord-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/callRecords/{id}/participants_v2](https://docs.microsoft.com/graph/api/callrecords-callrecord-list-participants_v2?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/callRecords/{id}/sessions](https://docs.microsoft.com/graph/api/callrecords-callrecord-list-sessions?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /communications/callRecords/getDirectRoutingCalls(fromDateTime={fromDateTime},toDateTime={toDateTime})](https://docs.microsoft.com/graph/api/callrecords-callrecord-getdirectroutingcalls?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /communications/callRecords/getPstnBlockedUsersLog(fromDateTime={fromDateTime},toDateTime={toDateTime})](https://docs.microsoft.com/graph/api/callrecords-callrecord-getpstnblockeduserslog?view=graph-rest-beta&tabs=http)|
|V1|A|[GET /communications/callRecords/getPstnCalls(fromDateTime={fromDateTime},toDateTime={toDateTime})](https://docs.microsoft.com/graph/api/callrecords-callrecord-getpstncalls?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /communications/callRecords/getPstnOnlineMeetingDialoutReport(fromDateTime={fromDateTime},toDateTime={toDateTime})](https://docs.microsoft.com/graph/api/callrecords-callrecord-getpstnonlinemeetingdialoutreport?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /communications/callRecords/getSmsLog(fromDateTime={fromDateTime},toDateTime={toDateTime})](https://docs.microsoft.com/graph/api/callrecords-callrecord-getsmslog?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|45bbb07e-7321-4fd7-a8f6-3ff27e6a81c8|
|**Display String**|Read all call records|
|**Description**|Allows the app to read call records for all calls and online meetings without a signed-in user.|
## Resources
### [call ](https://docs.microsoft.com/graph/api/resources/call?view=graph-rest-1.0&tabs=http)
| Property            | Type                                                                                                   | Description                                                                                                                                                                                         |
| :------------------ | :------------------------------------------------------------------------------------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| callbackUri         | String                                                                                                 | The callback URL on which callbacks are delivered. Must be an HTTPS URL.                                                                                                                             |
| callChainId         | String                                                                                                 | A unique identifier for all the participant calls in a conference or a unique identifier for two participant calls in a P2P call.  This identifier must be copied over from `Microsoft.Graph.Call.CallChainId`. |
| callOptions         | outgoingCallOptions                                                          | Contains the optional features for the call.                                                                                                                                                        |
| callRoutes          | callRoute collection                                                                   | The routing information on how the call was retargeted. Read-only.                                                                                                                                  |
| chatInfo            | chatInfo                                                                                | The chat information. Required information for joining a meeting.                                                                                                                                   |
| direction           | callDirection                                                                                          | The direction of the call. The possible values are `incoming` or `outgoing`. Read-only.                                                                                                              |
| id                  | String                                                                                                 | The unique identifier for the call. Read-only.                                                                                                                                                      |
|incomingContext      | incomingContext                                                                  | Call context associated with an incoming call.                                                                                                                                                      |
| mediaConfig         | appHostedMediaConfig or serviceHostedMediaConfig | The media configuration. Required.                                                                                                                                                              |
| mediaState          | callMediaState                                                                    | Read-only. The call media state.                                                                                                                                                                    |
| meetingInfo         | organizerMeetingInfo, tokenMeetingInfo, or joinMeetingIdMeetingInfo | The meeting information. Required information for meeting scenarios.                                                                                  |
| myParticipantId     | String                                                                                                 | Read-only.                                                                                                                                                                                          |
| requestedModalities | modality collection                                                                                    | The list of requested modalities. Possible values are: `unknown`, `audio`, `video`, `videoBasedScreenSharing`, `data`.                                                                              |
| resultInfo          | resultInfo                                                                            | The result information. For example, the result can hold termination reason. Read-only.                                                                                                                         |
| source              | participantInfo                                                                  | The originator of the call.                                                                                                                                                                         |
| state               | callState                                                                                              | The call state. Possible values are: `incoming`, `establishing`, `ringing`, `established`, `hold`, `transferring`, `transferAccepted`, `redirecting`, `terminating`, `terminated`. Read-only.       |
| subject             | String                                                                                                 | The subject of the conversation.                                                                                                                                                                    |
| targets             | invitationParticipantInfo collection                                             | The targets of the call. Required information for creating peer to peer call.                                                                                                                       |
|toneInfo             | toneInfo                                                                                | Read-only.                                                                                                                                                                                          |
|transcription        | callTranscriptionInfo                                                      | The transcription information for the call. Read-only.                                                                                                                                              |
### [callRecord ](https://docs.microsoft.com/graph/api/resources/callrecords-callrecord?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|endDateTime|DateTimeOffset|UTC time when the last user left the call. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|id|String|Unique identifier for the call record. Read-only.|
|joinWebUrl|String|Meeting URL associated to the call. May not be available for a peerToPeer call record type.|
|lastModifiedDateTime|DateTimeOffset|UTC time when the call record was created. The DatetimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|modalities|modality collection|List of all the modalities used in the call. Possible values are: `unknown`, `audio`, `video`, `videoBasedScreenSharing`, `data`, `screenSharing`, `unknownFutureValue`.|
|startDateTime|DateTimeOffset|UTC time when the first user joined the call. The DatetimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|type|callType|Indicates the type of the call. Possible values are: `unknown`, `groupCall`, `peerToPeer`, `unknownFutureValue`.|
|version|Int64|Monotonically increasing version of the call record. Higher version call records with the same id includes additional data compared to the lower version.|
|organizer (deprecated)|identitySet|The organizing party's identity. The **organizer** property is deprecated and will stop returning data on June 30, 2026. Going forward, use the **organizer_v2** relationship.|
|participants (deprecated)|identitySet collection|List of distinct identities involved in the call. Limited to 130 entries. The **p
### [directRoutingLogRow ](https://docs.microsoft.com/graph/api/resources/callrecords-directroutinglogrow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|callEndSubReason|Int32| In addition to the SIP codes, Microsoft has subcodes that indicate the specific issue.|
|callType|String| Call type and direction.|
|calleeNumber|String| Number of the user or bot who received the call. E.164 format, but might include other data.|
|callerNumber|String| Number of the user or bot who made the call. E.164 format, but might include other data.|
|correlationId|String|Identifier for the call that you can use when calling Microsoft Support. GUID.|
|duration|Int32| Duration of the call in seconds.|
|endDateTime|DateTimeOffset| Only exists for successful (fully established) calls. Time when call ended.|
|failureDateTime|DateTimeOffset| Only exists for failed (not fully established) calls.|
|finalSipCodePhrase|String| Description of the SIP code and Microsoft subcode.|
|finalSipCode|Int32| The final response code with which the call ended. For more information, see RFC 3261.|
|id|String|Unique call identifier. GUID.|
|inviteDateTime|DateTimeOffset| The date and time when the initial invite was sent.|
|mediaBypassEnabled|Boolean| Indicates whether the trunk was enabled for media bypass.|
|mediaPathLocation|String| The datacenter used for media path in a nonbypass call.|
|signalingLocation|String| The datacenter used for signaling for both bypass and nonbypass calls.|
|startDateTime|DateTimeOffset|Call start time.<br/>For failed and unanswered calls, this value can be equal to the invite or failure time.|
|successfulCall|Boolean| Success or attempt.|
|trunkFullyQualifiedDomainName|String| Fully qualified domain name of the session border controller.|
|userDisplayName|String|Display name of the user.|
|userId|String|Calling user's ID in Microsoft Graph. This and other user information is null/empty for bot call types. GUID.|
|userPrincipalName|String|UserPrincipalName (sign-in name) in Microsoft Entra ID. This value is usually the same as the user's SIP Address, and can be the same as the user's email address.|
### [participant ](https://docs.microsoft.com/graph/api/resources/callrecords-participant?view=graph-rest-1.0&tabs=http)
| Property | Type                       | Description                                             |
|:---------|:------------------------------|:--------------------------------------------------------|
| id       | String                        | Unique identifier for the call participant. Inherited from participantBase. |
| identity | microsoft.graph.communicationsIdentitySet | The identity of the call participant. Inherited from participantBase. |
### [pstnBlockedUsersLogRow ](https://docs.microsoft.com/graph/api/resources/callrecords-pstnblockeduserslogrow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|blockDateTime|DateTimeOffset|The date and time when the user was blocked/unblocked from making PSTN calls. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|blockReason|String|The reason why the user is blocked/unblocked from making calls.|
|remediationId|String|Unique identifier (GUID) for the blocking/unblocking action.|
|userBlockMode|microsoft.graph.callRecords.pstnUserBlockMode|Indicates whether the user is blocked or unblocked from making PSTN calls in Microsoft Teams. The possible values are: `blocked`, `unblocked`, `unknownFutureValue`.|
|userDisplayName|String|Display name of the user.|
|userId|String|The unique identifier (GUID) of the user in Microsoft Entra ID.|
|userPrincipalName|String|The user principal name (sign-in name) in Microsoft Entra ID. This is usually the same as the user's SIP address, and can be same as the user's e-mail address.|
|userTelephoneNumber|String|User's blocked number. For details, see E.164.|
### [pstnCallLogRow ](https://docs.microsoft.com/graph/api/resources/callrecords-pstncalllogrow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|callDurationSource|microsoft.graph.callRecords.pstnCallDurationSource|The source of the call duration data. If the call uses a third-party telecommunications operator via the Operator Connect Program, the operator can provide their own call duration data. In this case, the property value is `operator`. Otherwise, the value is `microsoft`.|
|calleeNumber|String|Number dialed in E.164 format.|
|callerNumber|String|Number that received the call for inbound calls or the number dialed for outbound calls. E.164 format.|
|callId|String|Call identifier. Not guaranteed to be unique.|
|callType|String|Indicates whether the call was a PSTN outbound or inbound call and the type of call, such as a call placed by a user or an audio conference.|
|charge|Double|Amount of money or cost of the call that is charged to your account.|
|conferenceId|String|ID of the audio conference.|
|connectionCharge|Double|Connection fee price.|
|currency|String|Type of currency used to calculate the cost of the call. For details, see (ISO 4217.|
|destinationContext|String|Whether the call was domestic (within a country or region) or international (outside a country or region), based on the user's location.|
|destinationName|String|Country or region dialed.|
|duration|Int32|How long the call was connected, in seconds.|
|endDateTime|DateTimeOffset|Call end time.|
|id|String|Unique call identifier. GUID.|
|inventoryType|String|User's phone number type, such as a service of toll-free number.|
|licenseCapability|String|The license used for the call.|
|operator|String|The telecommunications operator which provided PSTN services for this call. This might be Microsoft, or it might be a third-party operator via the Operator Connect Program.|
|startDateTime|DateTimeOffset|Call start time.|
|tenantCountryCode|String|Country code of the tenant. For details, see ISO 3166-1 alpha-2.|
|usageCountryCode|String|Country code of the user. For details, see ISO 3166-1 alpha-2.|
|userDisplayName|String|Display name of the user.|
|userId|String|Calling user's ID in Microsoft Graph. GUID. This and other user info will be null/empty for bot call types (ucap_in, ucap_out).|
|userPrincipalName|String|The user principal name (sign-in name) in Microsoft Entra ID. This is usually the same as the user's SIP address, and can be the same as the user's email address.|
### [pstnOnlineMeetingDialoutReport ](https://docs.microsoft.com/graph/api/resources/callrecords-pstnonlinemeetingdialoutreport?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|currency|String|Currency used to calculate the cost of the call. For details, see ISO 4217.|
|destinationContext|String|Indicates whether the call was `Domestic` (within a country or region) or `International` (outside a country or region) based on the user's location.|
|totalCallCharge|Decimal|Total costs of all the calls within the selected time range, including call charges and connection fees. |
|totalCalls|Int32|Total number of dial-out calls within the selected time range.|
|totalCallSeconds|Int32|Total duration of all the calls within the selected time range, in seconds.|
|usageLocation|String|Country code of the user. For details, see ISO 3166-1 alpha-2.|
|userDisplayName|String|Display name of the user.|
|userId|String|The unique identifier (GUID) of the user in Microsoft Entra ID.|
|userPrincipalName|String|The user principal name (sign-in name) in Microsoft Entra ID. This is usually the same as the user's SIP address, and can be same as the user's e-mail address.|
### [segment ](https://docs.microsoft.com/graph/api/resources/callrecords-segment?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|callee|microsoft.graph.callRecords.endpoint|Endpoint that answered this segment.|
|caller|microsoft.graph.callRecords.endpoint|Endpoint that initiated this segment.|
|endDateTime|DateTimeOffset|UTC time when the segment ended. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|failureInfo|microsoft.graph.callRecords.failureInfo|Failure information associated with the segment if it failed.|
|id|String|Unique identifier for the segment. Read-only.|
|media|microsoft.graph.callRecords.media collection|Media associated with this segment.|
|startDateTime|DateTimeOffset|UTC time when the segment started. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
### [session ](https://docs.microsoft.com/graph/api/resources/callrecords-session?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|callee|microsoft.graph.callRecords.endpoint|Endpoint that answered the session.|
|caller|microsoft.graph.callRecords.endpoint|Endpoint that initiated the session.|
|endDateTime|DateTimeOffset|UTC time when the last user left the session. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|failureInfo|microsoft.graph.callRecords.failureInfo|Failure information associated with the session if the session failed.|
|id|string|Unique identifier for the session. Read-only.|
|isTest|Boolean|Specifies whether the session is a test.|
|modalities|microsoft.graph.callRecords.modality collection|List of modalities present in the session. Possible values are: `unknown`, `audio`, `video`, `videoBasedScreenSharing`, `data`, `screenSharing`, `unknownFutureValue`.|
|startDateTime|DateTimeOffset|UTC time when the first user joined the session. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
### [smsLogRow ](https://docs.microsoft.com/graph/api/resources/callrecords-smslogrow?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|administrativeUnitInfos| microsoft.graph.callRecords.administrativeUnitInfo collection|Collection of administrative units associated to a call.|
|callCharge|Decimal|Amount of money or cost of the SMS that is charged.|
|currency|String|Currency used to calculate the cost of the call. For details, see ISO 4217.|
|destinationContext|String|Indicates whether the SMS was `Domestic` (within a country or region) or `International` (outside a country or region) based on the user's location.|
|destinationName|String|Country or region of a phone number that received the SMS.|
|destinationNumber|String|Partially obfuscated phone number that received the SMS. For details, see E.164.|
|id|String|Unique identifier (GUID) for the SMS.|
|licenseCapability|String|The license used for the SMS.|
|otherPartyCountryCode|String|For an outbound SMS, the country code of the receiver; otherwise (inbound SMS) the country code of the sender. For details, see ISO 3166-1 alpha-2.|
|sentDateTime|DateTimeOffset|The date and time when the SMS was sent.|
|smsId|String|SMS identifier. Not guaranteed to be unique.|
|smsType|String|Type of SMS such as outbound or inbound.|
|smsUnits|Int32|Number of SMS units sent/received.|
|sourceNumber|String|Partially obfuscated phone number that sent the SMS. For details, see E.164.|
|tenantCountryCode|String|Country code of the tenant. For details, see ISO 3166-1 alpha-2.|
|userCountryCode|String|Country code of the user. For details, see ISO 3166-1 alpha-2.|
|userDisplayName|String|Display name of the user.|
|userId|String|The unique identifier (GUID) of the user in Microsoft Entra ID.|
|userPrincipalName|String|The user principal name (sign-in name) in Microsoft Entra ID. It is usually the same as the user's SIP address and can be the same as the user's e-mail address.|
