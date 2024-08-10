# OrganizationalBranding.ReadWrite.All

> Allows the app to read and write the organizational branding information, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /organization/{organizationId}/branding](https://docs.microsoft.com/graph/api/organizationalbranding-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}/branding](https://docs.microsoft.com/graph/api/organizationalbranding-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}/branding/localizations](https://docs.microsoft.com/graph/api/organizationalbranding-list-localizations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /organization/{organizationId}/branding](https://docs.microsoft.com/graph/api/organizationalbranding-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}](https://docs.microsoft.com/graph/api/organizationalbrandinglocalization-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /organization/{organizationId}/branding/localizations](https://docs.microsoft.com/graph/api/organizationalbranding-post-localizations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PUT /organization/{organizationId}/branding/localizations/{organizationalBrandingLocalizationId}/{Stream object type such as backgroundImage}](https://docs.microsoft.com/graph/api/organizationalbranding-update?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|15ce63de-b141-4c9a-a9a5-241bf27c6aaf|
|**Consent Type**|Admin|
|**Display String**|Read and write organizational branding information|
|**Description**|Allows the app to read and write the organizational branding information, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|d2ebfbc1-a5f8-424b-83a6-56ab5927a73c|
|**Display String**|Read and write organizational branding information|
|**Description**|Allows the app to read and write the organizational branding information, without a signed-in user.|
## Resources
### [contentCustomization ](https://docs.microsoft.com/graph/api/resources/contentcustomization?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|attributeCollection|keyValue collection| Represents the content options of External Identities to be customized throughout the authentication flow for a tenant.|
|attributeCollectionRelativeUrl|String| A relative URL for the content options of External Identities to be customized throughout the authentication flow for a tenant.|
|registrationCampaign|keyValue collection| Represents content options to customize during MFA proofup interruptions. |
|registrationCampaignRelativeUrl|String| The relative URL of the content options to customize during MFA proofup interruptions. |
### [loginPageLayoutConfiguration ](https://docs.microsoft.com/graph/api/resources/loginPageLayoutConfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| layoutTemplateType | layoutTemplateType | Represents the layout template to be displayed on the login page for a tenant. The possible values are <ul><li> `default` - Represents the default Microsoft layout with a centered lightbox. <li> `verticalSplit` - Represents a layout with a background on the left side and a full-height lightbox to the right. <li> `unknownFutureValue` - Evolvable enumeration sentinel value. Don't use. </ul>  |
| isHeaderShown | Boolean | Option to show the header on the sign-in page. |
| isFooterShown | Boolean | Option to show the footer on the sign-in page. |
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
