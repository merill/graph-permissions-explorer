# UserAuthenticationMethod.ReadWrite.All

>  Allows the app to read and write authentication methods of all users in your organization that the signed-in user has access to.                       Authentication methods include things like a user’s phone numbers and Authenticator app settings. This                      does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A,D|[DELETE /me/authentication/emailMethods/{emailMethods-id}](https://docs.microsoft.com/graph/api/emailauthenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/authentication/fido2Methods/{id}](https://docs.microsoft.com/graph/api/fido2authenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/authentication/microsoftAuthenticatorMethods/{microsoftAuthenticatorAuthenticationMethodId}](https://docs.microsoft.com/graph/api/microsoftauthenticatorauthenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /me/authentication/passwordlessMicrosoftAuthenticatorMethods/{id}](https://docs.microsoft.com/graph/api/passwordlessmicrosoftauthenticatorauthenticationmethod-delete?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /me/authentication/phoneMethods/{phoneMethodId}](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/authentication/softwareOathMethods/{id}](https://docs.microsoft.com/graph/api/softwareoathauthenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/authentication/temporaryAccessPassMethods/{id}](https://docs.microsoft.com/graph/api/temporaryaccesspassauthenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /me/authentication/windowsHelloForBusinessMethods/{windowsHelloForBusinessAuthenticationMethodId}](https://docs.microsoft.com/graph/api/windowshelloforbusinessauthenticationmethod-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/emailMethods](https://docs.microsoft.com/graph/api/authentication-list-emailmethods?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/emailMethods/{emailMethods-id}](https://docs.microsoft.com/graph/api/emailauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/fido2Methods](https://docs.microsoft.com/graph/api/fido2authenticationmethod-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/fido2Methods/{id}](https://docs.microsoft.com/graph/api/fido2authenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/methods](https://docs.microsoft.com/graph/api/authentication-list-methods?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/methods/{id}](https://docs.microsoft.com/graph/api/authenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/microsoftAuthenticatorMethods](https://docs.microsoft.com/graph/api/microsoftauthenticatorauthenticationmethod-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/microsoftAuthenticatorMethods/{microsoftAuthenticatorAuthenticationMethodId}](https://docs.microsoft.com/graph/api/microsoftauthenticatorauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /me/authentication/passwordlessMicrosoftAuthenticatorMethods](https://docs.microsoft.com/graph/api/passwordlessmicrosoftauthenticatorauthenticationmethod-list?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /me/authentication/passwordlessMicrosoftAuthenticatorMethods/{id}](https://docs.microsoft.com/graph/api/passwordlessmicrosoftauthenticatorauthenticationmethod-get?view=graph-rest-beta&tabs=http)|
|V1|A,D|[GET /me/authentication/passwordMethods](https://docs.microsoft.com/graph/api/authentication-list-passwordmethods?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/passwordMethods/{passwordMethods-id}](https://docs.microsoft.com/graph/api/passwordauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/phoneMethods](https://docs.microsoft.com/graph/api/authentication-list-phonemethods?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/phoneMethods/{phoneMethodId}](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/softwareOathMethods](https://docs.microsoft.com/graph/api/authentication-list-softwareoathmethods?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/softwareOathMethods/{id}](https://docs.microsoft.com/graph/api/softwareoathauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/temporaryAccessPassMethods](https://docs.microsoft.com/graph/api/authentication-list-temporaryaccesspassmethods?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/temporaryAccessPassMethods/{temporaryAccessPassAuthenticationMethodId}](https://docs.microsoft.com/graph/api/temporaryaccesspassauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/windowsHelloForBusinessMethods](https://docs.microsoft.com/graph/api/windowshelloforbusinessauthenticationmethod-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /me/authentication/windowsHelloForBusinessMethods/{windowsHelloForBusinessAuthenticationMethodId}](https://docs.microsoft.com/graph/api/windowshelloforbusinessauthenticationmethod-get?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[GET /users/{id | userPrincipalName}/authentication/methods/{id}](https://docs.microsoft.com/graph/api/authenticationmethod-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /users/{id | userPrincipalName}/authentication/operations/{id}](https://docs.microsoft.com/graph/api/longrunningoperation-get?view=graph-rest-1.0&tabs=http)|
|Beta|A|[GET /users/{usersId}/authentication/fido2Methods/creationOptions](https://docs.microsoft.com/graph/api/fido2authenticationmethod-creationoptions?view=graph-rest-beta&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/authentication/emailMethods/{emailMethods-id}](https://docs.microsoft.com/graph/api/emailauthenticationmethod-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /users/{id | userPrincipalName}/authentication/phoneMethods/{phoneMethodId}](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-update?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[PATCH /users/{id | userPrincipalName}/authentication/signInPreferences](https://docs.microsoft.com/graph/api/authentication-update?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/authentication/phoneMethods/{id}/disableSmsSignIn](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-disablesmssignin?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /me/authentication/phoneMethods/{id}/enableSmsSignIn](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-enablesmssignin?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /me/authentication/phoneMethods/{mobilePhoneMethodId}/disableSmsSignIn](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-disablesmssignin?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /me/authentication/phoneMethods/{mobilePhoneMethodId}/enableSmsSignIn](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-enablesmssignin?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/authentication/emailMethods](https://docs.microsoft.com/graph/api/authentication-post-emailmethods?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /users/{id | userPrincipalName}/authentication/methods/{passwordMethods-id}/resetPassword](https://docs.microsoft.com/graph/api/authenticationmethod-resetpassword?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/authentication/phoneMethods](https://docs.microsoft.com/graph/api/authentication-post-phonemethods?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{id | userPrincipalName}/authentication/phoneMethods/{id}/disableSmsSignIn](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-disablesmssignin?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[POST /users/{id | userPrincipalName}/authentication/phoneMethods/{id}/enableSmsSignIn](https://docs.microsoft.com/graph/api/phoneauthenticationmethod-enablesmssignin?view=graph-rest-beta&tabs=http)|
|V1|A,D|[POST /users/{id | userPrincipalName}/authentication/temporaryAccessPassMethods](https://docs.microsoft.com/graph/api/authentication-post-temporaryaccesspassmethods?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[POST /users/{id}/authentication/fido2methods ](https://docs.microsoft.com/graph/api/authentication-post-fido2methods?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|b7887744-6746-4312-813d-72daeaee7e2d|
|**Consent Type**|Admin|
|**Display String**|Read and write all users' authentication methods.|
|**Description**| Allows the app to read and write authentication methods of all users in your organization that the signed-in user has access to.                       Authentication methods include things like a user’s phone numbers and Authenticator app settings. This                      does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods.|
## Application Permission
|||
|-|-|
|**Id**|50483e42-d915-4231-9639-7fdb7fd190e5|
|**Display String**|Read and write all users' authentication methods |
|**Description**|Allows the application to read and write authentication methods of all users in your organization, without a signed-in user.                       Authentication methods include things like a user’s phone numbers and Authenticator app settings. This                      does not allow the app to see secret information like passwords, or to sign-in or otherwise use the authentication methods|
## Resources
### [authenticationMethod ](https://docs.microsoft.com/graph/api/resources/authenticationmethod?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String| The identifier of this instance of an authentication method registered to this user. Read-only. |
### [authenticationmethods-overview](https://docs.microsoft.com/graph/api/resources/authenticationmethods-overview?view=graph-rest-1.0&tabs=http)

### [authenticationmethods-usage-insights-overview](https://docs.microsoft.com/graph/api/resources/authenticationmethods-usage-insights-overview?view=graph-rest-1.0&tabs=http)

### [emailAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/emailauthenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|emailAddress|String|The email address registered to this user.|
|id|String|The identifier of the email address registered to this user. The ID is always `3ddfcfc8-9383-446f-83cc-3ab9be4be18f`.|
### [fido2AuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/fido2authenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|aaGuid|String|Authenticator Attestation GUID, an identifier that indicates the type (e.g. make and model) of the authenticator.|
|attestationCertificates|String collection|The attestation certificate(s) attached to this security key.|
|attestationLevel|attestationLevel|The attestation level of this FIDO2 security key. Possible values are: `attested`, or `notAttested`.|
|createdDateTime|DateTimeOffset|The timestamp when this key was registered to the user.|
|displayName|String|The display name of the key as given by the user.|
|id|String|The authentication method identifier.|
|model|String|The manufacturer-assigned model of the FIDO2 security key.|
### [longRunningOperation ](https://docs.microsoft.com/graph/api/resources/longrunningoperation?view=graph-rest-1.0&tabs=http)

### [microsoftAuthenticatorAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/microsoftauthenticatorauthenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time that this app was registered. This property is null if the device isn't registered for passwordless Phone Sign-In.|
|deviceTag|String|Tags containing app metadata.|
|displayName|String|The name of the device on which this app is registered.|
|id|String|A unique identifier for this authentication method. Inherited from authenticationMethod|
|phoneAppVersion|String|Numerical version of this instance of the Authenticator app.|
### [passwordAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/passwordauthenticationmethod?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|createdDateTime|DateTimeOffset|The date and time when this password was last updated. This property is currently not populated. Read-only. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|id|String| The identifier of this password registered to this user. This is generally `28c10230-6103-485e-b985-444c60001490`. Read-only.|
|password|String|For security, the password is always returned as `null` from a LIST or GET operation.|
### [passwordlessmicrosoftauthenticatorauthenticationmethod](https://docs.microsoft.com/graph/api/resources/passwordlessmicrosoftauthenticatorauthenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The authentication method identifier.|
|displayName|String|The display name of the mobile device as given by the user.|
|creationDateTime|DateTimeOffset|The timestamp when this method was registered to the user.|
### [passwordResetResponse ](https://docs.microsoft.com/graph/api/resources/passwordresetresponse?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|newPassword|String|The Microsoft Entra ID-generated password.|
### [phoneAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/phoneauthenticationmethod?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String| The identifier of this phone registered to this user. Read-only. <br/><br/>The value of ID is one of the following:<ul><li>`b6332ec1-7057-4abe-9331-3d72feddfe41` - where **phoneType** is `alternateMobile`.</li><li>`e37fc753-ff3b-4958-9484-eaa9425c82bc` - where **phoneType** is `office`.</li><li>`3179e48a-750b-4051-897c-87b9720928f7` - where **phoneType** is `mobile`.</li>|
|phoneNumber|String|The phone number to text or call for authentication. Phone numbers use the format `+{country code} {number}x{extension}`, with extension optional. For example, `+1 5555551234` or `+1 5555551234x123` are valid. Numbers are rejected when creating or updating if they don't match the required format. |
|phoneType|authenticationPhoneType|The type of this phone. Possible values are: `mobile`, `alternateMobile`, or `office`.|
|smsSignInState|authenticationMethodSignInState|Whether a phone is ready to be used for SMS sign-in or not. Possible values are: `notSupported`, `notAllowedByPolicy`, `notEnabled`, `phoneNumberNotUnique`, `ready`, or `notConfigured`, `unknownFutureValue`.|
### [softwareOathAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/softwareoathauthenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The authentication method identifier.|
|secretKey|String|The secret key of the method. Always returns `null`.|
### [strongAuthenticationRequirements ](https://docs.microsoft.com/graph/api/resources/strongauthenticationrequirements?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|perUserMfaState|perUserMfaState|Sets the per-user MFA state for the user. The possible values are: `disabled`, `enforced`, `enabled`, `unknownFutureValue`.|
### [temporaryAccessPassAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/temporaryaccesspassauthenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time when the Temporary Access Pass was created.|
|id|String|The identifier of the Temporary Access Pass registered to this user. Inherited from entity.|
|isUsable|Boolean|The state of the authentication method that indicates whether it's currently usable by the user.|
|isUsableOnce|Boolean|Determines whether the pass is limited to a one-time use. If `true`, the pass can be used once; if `false`, the pass can be used multiple times within the Temporary Access Pass lifetime.|
|lifetimeInMinutes|Int32|The lifetime of the Temporary Access Pass in minutes starting at **startDateTime**. Must be between 10 and 43200 inclusive (equivalent to 30 days).|
|methodUsabilityReason|String|Details about the usability state (**isUsable**). Reasons can include: `EnabledByPolicy`, `DisabledByPolicy`, `Expired`, `NotYetValid`, `OneTimeUsed`.|
|startDateTime|DateTimeOffset|The date and time when the Temporary Access Pass becomes available to use and when **isUsable** is `true` is enforced.|
|temporaryAccessPass|String|The Temporary Access Pass used to authenticate. Returned only on creation of a new **t
### [temporaryAccessPassAuthenticationMethodConfiguration ](https://docs.microsoft.com/graph/api/resources/temporaryaccesspassauthenticationmethodconfiguration?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|defaultLength|Int|Default length in characters of a Temporary Access Pass object. Must be between 8 and 48 characters.|
|defaultLifetimeInMinutes|Int|Default lifetime in minutes for a Temporary Access Pass. Value can be any integer between the **minimumLifetimeInMinutes** and **maximumLifetimeInMinutes**.|
|excludeTargets|excludeTarget collection|Groups of users that are excluded from the policy.|
|id|String|The identifier of the authentication method policy. Inherited from entity.|
|isUsableOnce|Boolean    |If `true`, all the passes in the tenant will be restricted to one-time use. If `false`, passes in the tenant can be created to be either one-time use or reusable.|
|maximumLifetimeInMinutes|Int|Maximum lifetime in minutes for any Temporary Access Pass created in the tenant. Value can be between 10 and 43200 minutes (equivalent to 30 days).|
|minimumLifetimeInMinutes|Int|Minimum lifetime in minutes for any Temporary Access Pass created in the tenant. Value can be between 10 and 43200 minutes (equivalent to 30 days).|
|state|authenticationMethodState|Whether the Temporary Access Pass method is enabled in the tenant. Possible values are: `enabled`, `disabled`. Inherited from authenticationMethodConfiguration. |
### [webauthnCredentialCreationOptions ](https://docs.microsoft.com/graph/api/resources/webauthncredentialcreationoptions?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|challengeTimeoutDateTime|DateTimeOffset| Defines when the challenge in the creation options is no longer valid. Expired challenges are rejected when you attempt to create a new fido2AuthenticationMethod. |  
|publicKey|webauthnCredentialCreationOptions|Defines public key options for the creation of a new WebAuthn public key credential.|
### [webauthnPublicKeyCredential ](https://docs.microsoft.com/graph/api/resources/webauthnpublickeycredential?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|The credential ID created by the WebAuthn Authenticator.|
|response|webauthnAuthenticatorAttestationResponse|Response data returned from a WebAuthn authenticator after it creates a new public key credential.|  
|clientExtensionResults|webauthnAuthenticationExtensionsClientOutputs|The untyped results from the execution of extensions requested by the client when creating a new public key credential.|
### [windowsHelloForBusinessAuthenticationMethod ](https://docs.microsoft.com/graph/api/resources/windowshelloforbusinessauthenticationmethod?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The date and time that this Windows Hello for Business key was registered.|
|displayName|String|The name of the device on which Windows Hello for Business is registered|
|id|String|A unique identifier for this authentication method. Inherited from authenticationMethod|
|keyStrength|authenticationMethodKeyStrength|Key strength of this Windows Hello for Business key. Possible values are: `normal`, `weak`, `unknown`.|
