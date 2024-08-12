# Organization.ReadWrite.All

> Allows the app to read and write the organization and related resources, on behalf of the signed-in user. Related resources include things like subscribed skus and tenant branding information.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /organization/{id}/certificateBasedAuthConfiguration/{id}](https://docs.microsoft.com/graph/api/certificatebasedauthconfiguration-delete?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /organization/{organizationId}/branding](https://docs.microsoft.com/graph/api/organizationalbranding-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-delete?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /directory/subscriptions](https://docs.microsoft.com/graph/api/directory-list-subscriptions?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /directory/subscriptions(commerceSubscriptionId='{commerceSubscriptionId}')](https://docs.microsoft.com/graph/api/companysubscription-get?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /directory/subscriptions/{id}](https://docs.microsoft.com/graph/api/companysubscription-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /organization](https://docs.microsoft.com/graph/api/organization-list?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /organization/{id}/certificateBasedAuthConfiguration](https://docs.microsoft.com/graph/api/certificatebasedauthconfiguration-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{id}/certificateBasedAuthConfiguration/{id}](https://docs.microsoft.com/graph/api/certificatebasedauthconfiguration-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}](https://docs.microsoft.com/graph/api/organization-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}/branding](https://docs.microsoft.com/graph/api/organizationalbranding-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}/branding/localizations](https://docs.microsoft.com/graph/api/organizationalbranding-list-localizations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-get?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /organization/{organizationId}/settings/contactInsights](https://docs.microsoft.com/graph/api/organizationsettings-list-contactinsights?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /organization/{organizationId}/settings/microsoftApplicationDataAccess](https://docs.microsoft.com/graph/api/organizationsettings-list-microsoftapplicationdataaccess?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /subscribedSkus](https://docs.microsoft.com/graph/api/subscribedsku-list?view=graph-rest-1.0&tabs=http)|
|V1|A|[GET /subscribedSkus/{id}](https://docs.microsoft.com/graph/api/subscribedsku-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /organization/{id}](https://docs.microsoft.com/graph/api/organization-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /organization/{organizationId}/branding](https://docs.microsoft.com/graph/api/organizationalbranding-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-update?view=graph-rest-1.0&tabs=http)|
|Beta|D|[PATCH /organization/{organizationId}/settings/contactInsights](https://docs.microsoft.com/graph/api/insightssettings-update?view=graph-rest-beta&tabs=http)|
|Beta|D|[PATCH /organization/{organizationId}/settings/microsoftApplicationDataAccess](https://docs.microsoft.com/graph/api/microsoftapplicationdataaccesssettings-update?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /organization/{id}/certificateBasedAuthConfiguration](https://docs.microsoft.com/graph/api/certificatebasedauthconfiguration-post-certificatebasedauthconfiguration?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /organization/{organizationId}/branding/localizations](https://docs.microsoft.com/graph/api/organizationalbranding-post-localizations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}/{Stream object type such as backgroundImage}](https://docs.microsoft.com/graph/api/organizationalbranding-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|46ca0847-7e6b-426e-9775-ea810a948356|
|**Consent Type**|Admin|
|**Display String**|Read and write organization information|
|**Description**|Allows the app to read and write the organization and related resources, on behalf of the signed-in user. Related resources include things like subscribed skus and tenant branding information.|
## Application Permission
|||
|-|-|
|**Id**|292d869f-3427-49a8-9dab-8c70152b74e9|
|**Display String**|Read and write organization information|
|**Description**|Allows the app to read and write the organization and related resources, without a signed-in user. Related resources include things like subscribed skus and tenant branding information.|
## Resources
### [certificateAuthority ](https://docs.microsoft.com/graph/api/resources/certificateauthority?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|certificate|Binary|Required. The base64 encoded string representing the public certificate.|
|certificateRevocationListUrl|String|The URL of the certificate revocation list.|
|deltaCertificateRevocationListUrl|String|The URL contains the list of all revoked certificates since the last time a full certificate revocaton list was created.|
|isRootAuthority|Boolean|Required. **true** if the trusted certificate is a root authority, **false** if the trusted certificate is an intermediate authority.|
|issuer|String|The issuer of the certificate, calculated from the **certificate** value. Read-only. |
|issuerSki|String|The subject key identifier of the certificate, calculated from the **c
### [certificateBasedAuthConfiguration ](https://docs.microsoft.com/graph/api/resources/certificatebasedauthconfiguration?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|certificateAuthorities|certificateAuthority collection|Collection of certificate authorities which creates a trusted certificate chain.|
|id|String|The unique identifier of the certificate based auth configuration. Read-only.|
### [companySubscription ](https://docs.microsoft.com/graph/api/resources/companysubscription?view=graph-rest-1.0&tabs=http)
| Property               | Type                                             | Description                                                                                                                                                                                                                                                                                                                 |
| ---------------------- | ------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| commerceSubscriptionId | String                                           | The ID of this subscription in the commerce system. Alternate key.                                                                                                                                                                                                                                                          |
| createdDateTime        | DateTimeOffset                                   | The date and time when this subscription was created. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.                                                                                     |
| id                     | String                                           | The unique ID for this subscription. Inherited from entity.                                                                                                                                                                                                                                                    |
| isTrial                | Boolean                                          | Whether the subscription is a free trial or purchased.                                                                                                                                                                                                                                                                      |
| nextLifecycleDateTime  | DateTimeOffset                                   | The date and time when the subscription will move to the next state (as defined by the **status** property) if not renewed by the tenant. The DateTimeOffset type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. |
| ownerId                | String                                           | The object ID of the account admin.                                                                                                                                                                                                                                                                                         |
| ownerTenantId          | String                                           | The unique identifier for the Microsoft partner tenant that created the subscription on a customer tenant.                                                                                                                                                                                                                  |
| ownerType              | String                                           | Indicates the entity that **ownerId** belongs to, for example, "User".                                                                                                                                                                                                                                                      |
| serviceStatus          | servicePlanInfo collection | The provisioning status of each service included in this subscription.                                                                                                                                                                                                                                               |
| skuId                  | String                                           | The object ID of the SKU associated with this subscription.                                                                                                                                                                                                                                                                 |
| skuPartNumber          | String                                           | The SKU associated with this subscription.                                                                                                                                                                                                                                                                                  |
| status                 | String                                           | The status of this subscription. Possible values are: `Enabled`, `Deleted`, `Suspended`, `Warning`, `LockedOut`.                                                                                                                                                                                                            |
| totalLicenses          | Int32                                            | The number of licenses included in this subscription.                                                                                                                                                                                                                                                                          |
### [contentCustomization ](https://docs.microsoft.com/graph/api/resources/contentcustomization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attributeCollection|keyValue collection| Represents the content options of External Identities to be customized throughout the authentication flow for a tenant.|
|attributeCollectionRelativeUrl|String| A relative URL for the content options of External Identities to be customized throughout the authentication flow for a tenant.|
|registrationCampaign|keyValue collection| Represents content options to customize during MFA proofup interruptions. |
|registrationCampaignRelativeUrl|String| The relative URL of the content options to customize during MFA proofup interruptions. |
### [insightsSettings ](https://docs.microsoft.com/graph/api/resources/insightssettings?view=graph-rest-1.0&tabs=http)
| Property   | Type|Description|
|:---------------|:--------|:----------|
|disabledForGroup|String| The ID of a Microsoft Entra group, of which the specified type of insights are disabled for its members. The default value is `null`. Optional.|
|isEnabledInOrganization|Boolean| `true` if insights of the specified type are enabled for the organization; `false` if insights of the specified type are disabled for all users without exceptions. The default value is `true`. Optional.|
### [loginPageLayoutConfiguration ](https://docs.microsoft.com/graph/api/resources/loginPageLayoutConfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| layoutTemplateType | layoutTemplateType | Represents the layout template to be displayed on the login page for a tenant. The possible values are <ul><li> `default` - Represents the default Microsoft layout with a centered lightbox. <li> `verticalSplit` - Represents a layout with a background on the left side and a full-height lightbox to the right. <li> `unknownFutureValue` - Evolvable enumeration sentinel value. Don't use. </ul>  |
| isHeaderShown | Boolean | Option to show the header on the sign-in page. |
| isFooterShown | Boolean | Option to show the footer on the sign-in page. |
### [microsoftApplicationDataAccessSettings ](https://docs.microsoft.com/graph/api/resources/microsoftapplicationdataaccesssettings?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|isEnabledForAllMicrosoftApplications|Boolean|When set to `true`, all users in the organization can access in a Microsoft app any Microsoft 365 data that the user has been authorized to access. The Microsoft app can be a Microsoft 365 app (for example, Excel, Outlook) or non-Microsoft 365 app (for example, Edge). The default is `true`. <br> It is possible to disable this access for a subset of users in a Microsoft Entra security group, by specifying the group in the **disabledForGroup** property. <br> When set to `false`, all users can access authorized Microsoft 365 data only in a Microsoft 365 app.|
|disabledForGroup|String|The ID of a Microsoft Entra security group for which the members are allowed to access Microsoft 365 data using only Microsoft 365 apps, but not other Microsoft apps such as Edge. <br> This is only applicable if **i
### [organization ](https://docs.microsoft.com/graph/api/resources/organization?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:-------- |:---- |:----------- |
| assignedPlans | assignedPlan collection | The collection of service plans associated with the tenant. Not nullable. |
| businessPhones | String collection | Telephone number for the organization. Although this property is a string collection, only one number can be set. |
| city | String | City name of the address for the organization. |
| country | String | Country or region name of the address for the organization. |
| countryLetterCode | String | Country or region abbreviation for the organization in ISO 3166-2 format. |
| createdDateTime | DateTimeOffset | Timestamp of when the organization was created. The value can't be modified and is automatically populated when the organization is created. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| defaultUsageLocation | String | Two-letter ISO 3166 country code indicating the default service usage location of an organization. |
| deletedDateTime | DateTimeOffset | Represents date and time of when the Microsoft Entra tenant was deleted using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only. |
| displayName | String | The display name for the tenant. |
| id | String | The tenant ID, a unique identifier representing the organization (or tenant). Inherited from directoryObject. Key. Not nullable. Read-only. |
| isMultipleDataLocationsForServicesEnabled | Boolean | `true` if organization is Multi-Geo enabled; **false** if the organization isn't Multi-Geo enabled; **null** (default). Read-only. For more information, see OneDrive Online Multi-Geo. |
| marketingNotificationEmails | String collection | Not nullable. |
| onPremisesLastSyncDateTime | DateTimeOffset | The time and date at which the tenant was last synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`. Read-only.|
| onPremisesSyncEnabled | Boolean | `true` if this object is synced from an on-premises directory; `false` if this object was originally synced from an on-premises directory but is no longer synced. Nullable. `null` if this object isn't synced from on-premises active directory (default). |
| partnerTenantType | partnerTenantType | The type of partnership this tenant has with Microsoft. The possible values are: `microsoftSupport`, `syndicatePartner`, `breadthPartner`, `breadthPartnerDelegatedAdmin`, `resellerPartnerDelegatedAdmin`, `valueAddedResellerPartnerDelegatedAdmin`, `unknownFutureValue`. Nullable. For more information about the possible types, see partnerTenantType values.|
| postalCode | String | Postal code of the address for the organization. |
| preferredLanguage | String | The preferred language for the organization. Should follow ISO 639-1 Code; for example, `en`. |
| privacyProfile | privacyProfile | The privacy profile of an organization. |
| provisionedPlans | ProvisionedPlan collection | Not nullable. |
| securityComplianceNotificationMails | String collection | Not nullable.|
| securityComplianceNotificationPhones | String collection| Not nullable.|
| state | String | State name of the address for the organization. |
| street | String | Street name of the address for organization. |
| technicalNotificationMails | String collection | Not nullable. |
| tenantType | String | Not nullable. Can be one of the following types: <li> `AAD` - An enterprise identity access management (IAM) service that serves business-to-employee and business-to-business (B2B) scenarios. <li> `AAD B2C` An identity access management (IAM) service that serves business-to-consumer (B2C) scenarios.  <li> `CIAM` - A customer identity & access management (CIAM) solution that provides an integrated platform to serve consumers, partners, and citizen scenarios. |
| verifiedDomains | VerifiedDomain collection | The collection of domains associated with this tenant. Not nullable. |
### [organizationalBranding ](https://docs.microsoft.com/graph/api/resources/organizationalbranding?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| backgroundColor | String | Color that will appear in place of the background image in low-bandwidth connections. We recommend that you use the primary color of your banner logo or your organization color. Specify this in hexadecimal format, for example, white is `#FFFFFF`. Inherited from organizationalBrandingProperties. |
| backgroundImage | Stream | Image that appears as the background of the sign-in page. The allowed types are PNG or JPEG not smaller than 300 KB and not larger than 1920 × 1080 pixels. A smaller image will reduce bandwidth requirements and make the page load faster. Inherited from organizationalBrandingProperties. Returned only on `$select`. |
| backgroundImageRelativeUrl | String | A relative URL for the **backgroundImage** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| bannerLogo | Stream | A banner version of your company logo that appears on the sign-in page. The allowed types are PNG or JPEG no larger than 245 x 36 pixels. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties. Returned only on `$select`. |
| bannerLogoRelativeUrl | String | A relative url for the **bannerLogo** property that is combined with a CDN base URL from the **cdnList** to provide the read-only version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| cdnList | String collection | A list of base URLs for all available CDN providers that are serving the assets of the current resource. Several CDN providers are used at the same time for high availability of read requests. Read-only. Inherited from organizationalBrandingProperties. |
| contentCustomization | contentCustomization | Represents the content options to be customized throughout the authentication flow for a tenant. <br/><br/>**NOTE:** Supported by Microsoft Entra External ID in external tenants only. |
| customAccountResetCredentialsUrl | String | A custom URL for resetting account credentials. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128 characters. Inherited from organizationalBrandingProperties. |
| customCannotAccessYourAccountText | String | A string to replace the default "Can't access your account?" self-service password reset (SSPR) hyperlink text on the sign-in page. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customCannotAccessYourAccountUrl | String | A custom URL to replace the default URL of the self-service password reset (SSPR) "Can't access your account?" hyperlink on the sign-in page. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128 characters. <br/><br/>**DO NOT USE.** Use **customAccountResetCredentialsUrl** instead. Inherited from organizationalBrandingProperties. |
| customCSS | Stream | CSS styling that appears on the sign-in page. The allowed format is .css format only and not larger than 25KB. Inherited from organizationalBrandingProperties. |
| customCSSRelativeUrl | String| A relative URL for the **customCSS** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| customForgotMyPasswordText | String | A string to replace the default "Forgot my password" hyperlink text on the sign-in form. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customPrivacyAndCookiesText | String | A string to replace the default "Privacy and Cookies" hyperlink text in the footer. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customPrivacyAndCookiesUrl | String | A custom URL to replace the default URL of the "Privacy and Cookies" hyperlink in the footer. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128 characters. Inherited from organizationalBrandingProperties. |
| customResetItNowText | String | A string to replace the default "reset it now" hyperlink text on the sign-in form. This text must be in Unicode format and not exceed 256 characters. <br/><br/>**DO NOT USE:** Customization of the "reset it now" hyperlink text is currently not supported. Inherited from organizationalBrandingProperties. |
| customTermsOfUseText | String | A string to replace the the default "Terms of Use" hyperlink text in the footer. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customTermsOfUseUrl | String | A custom URL to replace the default URL of the "Terms of Use" hyperlink in the footer. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128characters. Inherited from organizationalBrandingProperties. |
| favicon | Stream | A custom icon (favicon) to replace a default Microsoft product favicon on a Microsoft Entra tenant. Inherited from organizationalBrandingProperties. |
| faviconRelativeUrl | String | A relative url for the favicon above that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| headerBackgroundColor | String | The RGB color to apply to customize the color of the header. Inherited from organizationalBrandingProperties. |
| headerLogo | Stream | A company logo that appears in the header of the sign-in page. The allowed types are PNG or JPEG not larger than 245 x 36 pixels. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties. |
| headerLogoRelativeUrl | String | A relative URL for the **headerLogo** property that is combined with a CDN base URL from the **cdnList** to provide the read-only version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| id | String | An identifier that represents the locale specified using culture names. Culture names follow the RFC 1766 standard in the format "languagecode2-country/regioncode2", where "languagecode2" is a lowercase two-letter code derived from ISO 639-1 and "country/regioncode2" is an uppercase two-letter code derived from ISO 3166. For example, U.S. English is `en-US`. The **id** for the default /branding is always the String types `0` or `default`. Read-only. <br/><br/>**NOTE:** Multiple branding for a single locale are currently not supported. Inherited from organizationalBrandingProperties. |
| loginPageLayoutConfiguration | loginPageLayoutConfiguration | Represents the layout configuration to be displayed on the login page for a tenant. Inherited from organizationalBrandingProperties. |
| loginPageTextVisibilitySettings | loginPageTextVisibilitySettings | Represents the various texts that can be hidden on the login page for a tenant. Inherited from organizationalBrandingProperties. |
| signInPageText | String | Text that appears at the bottom of the sign-in box. You can use this to communicate additional information, such as the phone number to your help desk or a legal statement. This text must be Unicode and not exceed 1024 characters. Inherited from organizationalBrandingProperties. |
| squareLogo | Stream | A square version of your company logo that appears in Windows 10 out-of-box experiences (OOBE) and when Windows Autopilot is enabled for deployment. Allowed types are PNG or JPEG no larger than 240 x 240 pixels and no more than 10 KB in size. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties. Returned only on `$select`.|
| squareLogoRelativeUrl | String | A relative url for the **squareLogo** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| squareLogoDark | Stream | A square dark version of your company logo that appears in Windows 10 out-of-box experiences (OOBE) and when Windows Autopilot is enabled for deployment. Allowed types are PNG or JPEG not larger than 240 x 240 pixels and not more than 10 KB in size. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties.|
| squareLogoDarkRelativeUrl | String | A relative URL for the **squareLogoDark** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| usernameHintText | String | String that shows as the hint in the username textbox on the sign-in screen. This text must be a Unicode, without links or code, and can't exceed 64 characters. Inherited from organizationalBrandingProperties. |
### [organizationalBrandingLocalization ](https://docs.microsoft.com/graph/api/resources/organizationalbrandinglocalization?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
| backgroundColor | String | Color that appears in place of the background image in low-bandwidth connections. We recommend that you use the primary color of your banner logo or your organization color. Specify this in hexadecimal format, for example, white is `#FFFFFF`. Inherited from organizationalBrandingProperties. |
| backgroundImage | Stream | Image that appears as the background of the sign-in page. The allowed types are PNG or JPEG not smaller than 300 KB and not larger than 1920 × 1080 pixels. A smaller image will reduce bandwidth requirements and make the page load faster. Inherited from organizationalBrandingProperties. |
| backgroundImageRelativeUrl | String | A relative URL for the **backgroundImage** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| bannerLogo | Stream | A banner version of your company logo that appears on the sign-in page. The allowed types are PNG or JPEG not larger than 36 × 245 pixels. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties. |
| bannerLogoRelativeUrl | String | A relative URL for the **bannerLogo** property that is combined with a CDN base URL from the **cdnList** to provide the read-only version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| cdnList | String collection | A list of base URLs for all available CDN providers that are serving the assets of the current resource. Several CDN providers are used at the same time for high availability of read requests. Read-only. Inherited from organizationalBrandingProperties. |
| contentCustomization | contentCustomization | Represents the content options to be customized throughout the authentication flow for a tenant. <br/><br/>**NOTE:** Supported by Microsoft Entra External ID in external tenants only. |
| customAccountResetCredentialsUrl | String | A custom URL for resetting account credentials. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128 characters. Inherited from organizationalBrandingProperties. |
| customCannotAccessYourAccountText | String | A string to replace the default "Can't access your account?" self-service password reset (SSPR) hyperlink text on the sign-in page. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customCannotAccessYourAccountUrl | String | A custom URL to replace the default URL of the self-service password reset (SSPR) "Can't access your account?" hyperlink on the sign-in page. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128 characters. <br/><br/>**DO NOT USE.** Use **customAccountResetCredentialsUrl** instead. Inherited from organizationalBrandingProperties. |
| customCSS | Stream | CSS styling that appears on the sign-in page. The allowed format is .css format only and not larger than 25KB. Inherited from organizationalBrandingProperties. |
| customCSSRelativeUrl | String| A relative URL for the **customCSS** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| customForgotMyPasswordText | String | A string to replace the default "Forgot my password" hyperlink text on the sign-in form. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customPrivacyAndCookiesText | String | A string to replace the default "Privacy and Cookies" hyperlink text in the footer. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customPrivacyAndCookiesUrl | String | A custom URL to replace the default URL of the "Privacy and Cookies" hyperlink in the footer. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128 characters. Inherited from organizationalBrandingProperties. |
| customResetItNowText | String | A string to replace the default "reset it now" hyperlink text on the sign-in form. This text must be in Unicode format and not exceed 256 characters. <br/><br/>**DO NOT USE:** Customization of the "reset it now" hyperlink text is currently not supported. Inherited from organizationalBrandingProperties. |
| customTermsOfUseText | String | A string to replace the the default "Terms of Use" hyperlink text in the footer. This text must be in Unicode format and not exceed 256 characters. Inherited from organizationalBrandingProperties. |
| customTermsOfUseUrl | String | A custom URL to replace the default URL of the "Terms of Use" hyperlink in the footer. This URL must be in ASCII format or non-ASCII characters must be URL encoded, and not exceed 128characters. Inherited from organizationalBrandingProperties. |
| favicon | Stream | A custom icon (favicon) to replace a default Microsoft product favicon on a Microsoft Entra tenant. Inherited from organizationalBrandingProperties. |
| faviconRelativeUrl | String | A relative url for the favicon above that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| headerBackgroundColor | String | The RGB color to apply to customize the color of the header. Inherited from organizationalBrandingProperties. |
| headerLogo | Stream | A company logo that appears in the header of the sign-in page. The allowed types are PNG or JPEG not larger than 36 × 245 pixels. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties. |
| headerLogoRelativeUrl | String | A relative URL for the **headerLogo** property that is combined with a CDN base URL from the **cdnList** to provide the read-only version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| id | String | An identifier that represents the locale specified using culture names. Culture names follow the RFC 1766 standard in the format "languagecode2-country/regioncode2", where "languagecode2" is a lowercase two-letter code derived from ISO 639-1 and "country/regioncode2" is an uppercase two-letter code derived from ISO 3166. For example, U.S. English is `en-US`. The **id** for the default /branding is always the String types `0` or `default`. Read-only. <br/><br/>**NOTE:** Multiple branding for a single locale are currently not supported. |
| loginPageLayoutConfiguration | loginPageLayoutConfiguration | Represents the layout configuration to be displayed on the login page for a tenant. Inherited from organizationalBrandingProperties. |
| loginPageTextVisibilitySettings | loginPageTextVisibilitySettings | Represents the various texts that can be hidden on the login page for a tenant. Inherited from organizationalBrandingProperties. |
| signInPageText | String | Text that appears at the bottom of the sign-in box. Use this to communicate additional information, such as the phone number to your help desk or a legal statement. This text must be in Unicode format and not exceed 1024 characters. Inherited from organizationalBrandingProperties.|
| squareLogo | Stream | A square version of your company logo that appears in Windows 10 out-of-box experiences (OOBE) and when Windows Autopilot is enabled for deployment. Allowed types are PNG or JPEG not larger than 240 x 240 pixels and not more than 10 KB in size. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties.|
| squareLogoRelativeUrl | String | A relative URL for the **squareLogo** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| squareLogoDark | Stream | A square dark version of your company logo that appears in Windows 10 out-of-box experiences (OOBE) and when Windows Autopilot is enabled for deployment. Allowed types are PNG or JPEG not larger than 240 x 240 pixels and not more than 10 KB in size. We recommend using a transparent image with no padding around the logo. Inherited from organizationalBrandingProperties.|
| squareLogoDarkRelativeUrl | String | A relative URL for the **squareLogoDark** property that is combined with a CDN base URL from the **cdnList** to provide the version served by a CDN. Read-only. Inherited from organizationalBrandingProperties. |
| usernameHintText | String | A string that shows as the hint in the username textbox on the sign-in screen. This text must be a Unicode, without links or code, and can't exceed 64 characters. Inherited from organizationalBrandingProperties. |
### [privacyProfile ](https://docs.microsoft.com/graph/api/resources/privacyprofile?view=graph-rest-1.0&tabs=http)
| Property   | Type|Description|
|:---------------|:--------|:----------|
|contactEmail|String| A valid smtp email address for the privacy statement contact. Not required.|
|statementUrl|String| A valid URL format that begins with http:// or https://. Maximum length is 255 characters. The URL that directs to the company's privacy statement. Not required.|
### [subscribedSku ](https://docs.microsoft.com/graph/api/resources/subscribedsku?view=graph-rest-1.0&tabs=http)
| Property         | Type                                             | Description                                                                                                                                                                                                                                               |
| :--------------- | :----------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| accountId        | String                                           | The unique ID of the account this SKU belongs to.                                                                                                                                                                                                         |
| accountName      | String                                           | The name of the account this SKU belongs to.                                                                                                                                                                                                              |
| appliesTo        | String                                           | The target class for this SKU. Only SKUs with target class `User` are assignable. Possible values are: `User`, `Company`.                                                                                                                                          |
| capabilityStatus | String                                           | `Enabled` indicates that the **prepaidUnits** property has at least one unit that is enabled. `LockedOut` indicates that the customer canceled their subscription. Possible values are: `Enabled`, `Warning`, `Suspended`, `Deleted`, `LockedOut`. |
| consumedUnits    | Int32                                            | The number of licenses that have been assigned.                                                                                                                                                                                                           |
| id               | String                                           | The unique identifier for the subscribed sku object. Key, not nullable.                                                                                                                                                                                   |
| prepaidUnits     | licenseUnitsDetail      | Information about the number and status of prepaid licenses.                                                                                                                                                                                              |
| servicePlans     | servicePlanInfo collection | Information about the service plans that are available with the SKU. Not nullable.                                                                                                                                                                         |
| skuId            | Guid                                             | The unique identifier (GUID) for the service SKU.                                                                                                                                                                                                         |
| skuPartNumber    | String                                           | The SKU part number; for example: `AAD_PREMIUM` or `RMSBASIC`. To get a list of commercial subscriptions that an organization has acquired, see List subscribedSkus.                                                      |
| subscriptionIds | String collection                                    | A list of all subscription IDs associated with this SKU.                                                                                                                                                                                                  |