# OrgContact.Read.All

> Allows the app to read all organizational contacts on behalf of the signed-in user.  These contacts are managed by the organization and are different from a user's personal contacts.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[GET /contacts](https://docs.microsoft.com/graph/api/orgcontact-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}](https://docs.microsoft.com/graph/api/orgcontact-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/directReports](https://docs.microsoft.com/graph/api/orgcontact-list-directreports?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/manager](https://docs.microsoft.com/graph/api/orgcontact-get-manager?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/memberOf](https://docs.microsoft.com/graph/api/orgcontact-list-memberof?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /contacts/{id}/transitiveMemberOf](https://docs.microsoft.com/graph/api/orgcontact-list-transitivememberof?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /contacts/{id}/transitiveReports/$count](https://docs.microsoft.com/graph/api/orgcontact-get-transitivereports?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /contacts/delta](https://docs.microsoft.com/graph/api/orgcontact-delta?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /contacts/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/orgcontact-retryserviceprovisioning?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /orgContacts/{id}/retryServiceProvisioning](https://docs.microsoft.com/graph/api/orgcontact-retryserviceprovisioning?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|08432d1b-5911-483c-86df-7980af5cdee0|
|**Consent Type**|Admin|
|**Display String**|Read organizational contacts|
|**Description**|Allows the app to read all organizational contacts on behalf of the signed-in user.  These contacts are managed by the organization and are different from a user's personal contacts.|
## Application Permission
|||
|-|-|
|**Id**|e1a88a34-94c4-4418-be12-c87b00e26bea|
|**Display String**|Read organizational contacts|
|**Description**|Allows the app to read all organizational contacts without a signed-in user.  These contacts are managed by the organization and are different from a user's personal contacts.|
## Resources
### [directoryObject ](https://docs.microsoft.com/graph/api/resources/directoryobject?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|deletedDateTime|DateTimeOffset|Date and time when this object was deleted. Always `null` when the object hasn't been deleted. |
|id|String|The unique identifier for the object. For example, `12345678-9abc-def0-1234-56789abcde`. The value of the **i
### [orgContact ](https://docs.microsoft.com/graph/api/resources/orgcontact?view=graph-rest-1.0&tabs=http)
| Property                     | Type                                                                     | Description                                                                                                                                                                                                                                                                                                                        |
|:-----------------------------|:-------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| addresses                    | physicalOfficeAddress collection             | Postal addresses for this organizational contact. For now a contact can only have one physical address.                                                                                                                                                                                                                            |
| companyName                  | String                                                                   | Name of the company that this organizational contact belongs to.  Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                          |
| department                   | String                                                                   | The name for the department in which the contact works.  Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                   |
| displayName                  | String                                                                   | Display name for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values), `$search`, and `$orderby`.                                                                                                                                                                                   |
| givenName                    | String                                                                   | First name for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                                |
| id                           | String                                                                   | Unique identifier for this organizational contact.  Supports `$filter` (`eq`, `ne`, `not`, `in`).                                                                                                                                                                                                                                  |
| jobTitle                     | String                                                                   | Job title for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                                 |
| mail                         | String                                                                   | The SMTP address for the contact, for example, "jeff@contoso.com". Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                             |
| mailNickname                 | String                                                                   | Email alias (portion of email address pre-pending the @ symbol) for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                           |
| serviceProvisioningErrors    | serviceProvisioningError collection       | Errors published by a federated service describing a non-transient, service-specific error regarding the properties or link from an organizational contact object . <br><br> Supports `$filter` (`eq`, `not`, for isResolved and serviceInstance).  |
| onPremisesLastSyncDateTime   | DateTimeOffset                                                           | Date and time when this organizational contact was last synchronized from on-premises AD. This date and time information uses ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`).                             |
| onPremisesProvisioningErrors | onPremisesProvisioningError collection | List of any synchronization provisioning errors for this organizational contact. Supports `$filter` (`eq`, `not` for **category** and **propertyCausingError**), `/$count eq 0`, `/$count ne 0`.                                                                                                                                                                                                                 |
| onPremisesSyncEnabled        | Boolean                                                                  | `true` if this object is synced from an on-premises directory; `false` if this object was originally synced from an on-premises directory but is no longer synced and now mastered in Exchange; `null` if this object has never been synced from an on-premises directory (default). <br/> <br/> Supports `$filter` (`eq`, `ne`, `not`, `in`, and `eq` for `null` values). |
| phones                       | phone collection                                             | List of phones for this organizational contact. Phone types can be mobile, business, and businessFax. Only one of each type can ever be present in the collection.                                                                                                                                                                 |
| proxyAddresses               | String collection                                                        | For example: "SMTP: bob@contoso.com", "smtp: bob@sales.contoso.com". The **any** operator is required for filter expressions on multi-valued properties. Supports `$filter` (`eq`, `not`, `ge`, `le`, `startsWith`, `/$count eq 0`, `/$count ne 0`).                                                                                                              |
| surname                      | String                                                                   | Last name for this organizational contact. Supports `$filter` (`eq`, `ne`, `not`, `ge`, `le`, `in`, `startsWith`, and `eq` for `null` values).                                                                                                                                                                                                                 |
