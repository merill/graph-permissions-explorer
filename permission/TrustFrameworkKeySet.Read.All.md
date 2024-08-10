# TrustFrameworkKeySet.Read.All

> Allows the app to read trust framework key set properties on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[GET /trustFramework/keySets](https://docs.microsoft.com/graph/api/trustframework-list-keysets?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /trustFramework/keySets/{id}](https://docs.microsoft.com/graph/api/trustframeworkkeyset-get?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /trustFramework/keySets/{id}/getActiveKey](https://docs.microsoft.com/graph/api/trustframeworkkeyset-getactivekey?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7ad34336-f5b1-44ce-8682-31d7dfcd9ab9|
|**Consent Type**|Admin|
|**Display String**|Read trust framework key sets|
|**Description**|Allows the app to read trust framework key set properties on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|fff194f1-7dce-4428-8301-1badb5518201|
|**Display String**|Read trust framework key sets|
|**Description**|Allows the app to read trust framework key set properties without a signed-in user.|
## Resources
### [trustFrameworkKey ](https://docs.microsoft.com/graph/api/resources/trustframeworkkey?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|d|String|RSA Key - private exponent. The field isn't readable.|
|dp|String|RSA Key - first exponent. The field isn't readable.|
|dq|String|RSA Key - second exponent. The field isn't readable.|
|e|String|RSA Key - public exponent. |
|exp|Int64|This value is a NumericDate as defined in RFC 7519. That is, a JSON numeric value representing the number of seconds from 1970-01-01T00:00:00Z UTC until the specified UTC date/time, ignoring leap seconds.|
|k|String|Symmetric Key for oct key type. The field isn't readable.|
|kid|String|The unique identifier for the key.|
|kty|String|The **kty** (key type) parameter identifies the cryptographic algorithm family used with the key. The valid values are `rsa`, `oct`.|
|n|String|RSA Key - modulus.|
|nbf|Int64|This value is a NumericDate as defined in RFC 7519. That is, a JSON numeric value representing the number of seconds from 1970-01-01T00:00:00Z UTC until the specified UTC date/time, ignoring leap seconds.|
|p|String|RSA Key - first prime. The field isn't readable.|
|q|String|RSA Key - second prime. The field isn't readable.|
|qi|String|RSA Key - Coefficient. The field isn't readable.|
|status|trustFrameworkKeyStatus|Status of the key. The possible values are: `enabled`, `disabled`, `unknownFutureValue`.|
|use|String|The **use** (public key use) parameter identifies the intended use of the public key. The **use** parameter is employed to indicate whether a public key is used for encrypting data or verifying the signature on data. Possible values are: `sig` (signature), `enc` (encryption).|
|x5c|String collection|The **x5c** (X.509 certificate chain) parameter contains a chain of one or more PKIX certificates. For more information, see RFC 5280.|
|x5t|String|The **x
### [trustFrameworkKeySet ](https://docs.microsoft.com/graph/api/resources/trustframeworkkeyset?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique identifier of the trustframework keyset Inherited from entity.|
|keys|trustFrameworkKey collection|A collection of the keys.|
