# InformationProtectionPolicy.Read.All

> Allows an app to read published sensitivity labels and label policy settings for the entire organization or a specific user, without a signed in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[GET /me/informationProtection/policy/labels](https://docs.microsoft.com/graph/api/informationprotectionpolicy-list-labels?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/informationProtection/policy/labels/{id}](https://docs.microsoft.com/graph/api/informationprotectionlabel-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/security/informationProtection/labelPolicySettings](https://docs.microsoft.com/graph/api/security-informationprotectionpolicysetting-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/security/informationProtection/sensitivityLabels](https://docs.microsoft.com/graph/api/security-informationprotection-list-sensitivitylabels?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /me/security/informationProtection/sensitivityLabels/{sensitivityLabelId}](https://docs.microsoft.com/graph/api/security-sensitivitylabel-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /users/{id | user-principal-name}/informationProtection/policy/labels](https://docs.microsoft.com/graph/api/informationprotectionpolicy-list-labels?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /users/{id | user-principal-name}/informationProtection/policy/labels/{id}](https://docs.microsoft.com/graph/api/informationprotectionlabel-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /users/{usersId}/security/informationProtection/labelPolicySettings](https://docs.microsoft.com/graph/api/security-informationprotectionpolicysetting-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /users/{usersId}/security/informationProtection/sensitivityLabels](https://docs.microsoft.com/graph/api/security-informationprotection-list-sensitivitylabels?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /users/{usersId}/security/informationProtection/sensitivityLabels/{sensitivityLabelId}](https://docs.microsoft.com/graph/api/security-sensitivitylabel-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /informationProtection/policy/labels/evaluateClassificationResults](https://docs.microsoft.com/graph/api/informationprotectionlabel-evaluateclassificationresults?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /informationProtection/policy/labels/evaluateRemoval](https://docs.microsoft.com/graph/api/informationprotectionlabel-evaluateremoval?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /informationprotection/policy/labels/extractLabel](https://docs.microsoft.com/graph/api/informationprotectionlabel-extractlabel?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /me/security/informationProtection/sensitivityLabels/evaluateApplication](https://docs.microsoft.com/graph/api/security-sensitivitylabel-evaluateapplication?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/{id}/informationProtection/policy/labels/evaluateApplication](https://docs.microsoft.com/graph/api/informationprotectionlabel-evaluateapplication?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/{usersId}/security/informationProtection/sensitivityLabels/evaluateApplication](https://docs.microsoft.com/graph/api/security-sensitivitylabel-evaluateapplication?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/{usersId}/security/informationProtection/sensitivityLabels/evaluateClassificationResults](https://docs.microsoft.com/graph/api/security-sensitivitylabel-evaluateclassificationresults?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/{usersId}/security/informationProtection/sensitivityLabels/evaluateRemoval](https://docs.microsoft.com/graph/api/security-sensitivitylabel-evaluateremoval?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/{usersId}/security/informationProtection/sensitivityLabels/extractContentLabel](https://docs.microsoft.com/graph/api/security-sensitivitylabel-extractcontentlabel?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/me/security/informationProtection/sensitivityLabels/evaluateClassificationResults](https://docs.microsoft.com/graph/api/security-sensitivitylabel-evaluateclassificationresults?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/me/security/informationProtection/sensitivityLabels/evaluateRemoval](https://docs.microsoft.com/graph/api/security-sensitivitylabel-evaluateremoval?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST /users/me/security/informationProtection/sensitivityLabels/extractContentLabel](https://docs.microsoft.com/graph/api/security-sensitivitylabel-extractcontentlabel?view=graph-rest-beta&tabs=http)|
|Beta|A|[POST me/informationProtection/policy/labels/evaluateApplication](https://docs.microsoft.com/graph/api/informationprotectionlabel-evaluateapplication?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|19da66cb-0fb0-4390-b071-ebc76a349482|
|**Display String**|Read all published labels and label policies for an organization.|
|**Description**|Allows an app to read published sensitivity labels and label policy settings for the entire organization or a specific user, without a signed in user.|
## Resources
### [addcontentfooteraction](https://docs.microsoft.com/graph/api/resources/addcontentfooteraction?view=graph-rest-1.0&tabs=http)
| Property      | Type   | Description                                                   |
| :------------ | :----- | :------------------------------------------------------------ |
| alignment     | String | Possible values are: `left`, `right`, `center`.               |
| fontColor     | String | Color of the font to use for the footer.                      |
| fontName      | String | Name of the font to use for the footer.                       |
| fontSize      | Int32  | Font size to use for the footer.                              |
| margin        | Int32  | The margin of the header from the bottom of the document.     |
| text          | String | The contents of the footer itself.                            |
| uiElementName | String | The name of the UI element where the footer should be placed. |
### [addcontentheaderaction](https://docs.microsoft.com/graph/api/resources/addcontentheaderaction?view=graph-rest-1.0&tabs=http)
| Property      | Type   | Description                                                   |
| :------------ | :----- | :------------------------------------------------------------ |
| alignment     | String | Possible values are: `left`, `right`, `center`.               |
| fontColor     | String | Color of the font to use for the header.                      |
| fontName      | String | Name of the font to use for the header.                       |
| fontSize      | Int32  | Font size to use for the header.                              |
| margin        | Int32  | The margin of the header from the top of the document.        |
| text          | String | The contents of the header itself.                            |
| uiElementName | String | The name of the UI element where the header should be placed. |
### [applylabelaction](https://docs.microsoft.com/graph/api/resources/applylabelaction?view=graph-rest-1.0&tabs=http)
| Property                    | Type                                                                     | Description                                                                                                                                                                                       |
| :-------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| actionSource                | String                                                                   | Possible values are: `manual`, `automatic`, `recommended`, `default`.                                                                                                                             |
| actions                     | informationProtectionAction collection | The collection of specific actions that should be taken by the consuming application to label the document. See  informationProtectionAction for the full list. |
| label                       | labelDetails                                          | Object that describes the details of the label to apply.                                                                                                                                          |
| responsibleSensitiveTypeIds | Guid collection                                                          | If the label was the result of an automatic classification, supply the list of sensitive info type GUIDs that resulted in the returned label.                                                     |
### [classificationresult](https://docs.microsoft.com/graph/api/resources/classificationresult?view=graph-rest-1.0&tabs=http)
| Property        | Type  | Description                                                            |
| :-------------- | :---- | :--------------------------------------------------------------------- |
| confidenceLevel | Int32 | The confidence level, 0 to 100, of the result.                         |
| count           | Int32 | The number of instances of the specific information type in the input. |
| sensitiveTypeId | GUID  | The GUID of the discovered sensitive information type.                 |
### [contentinfo](https://docs.microsoft.com/graph/api/resources/contentinfo?view=graph-rest-1.0&tabs=http)
| Property   | Type                                       | Description                                                                                                                     |
| :--------- | :----------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| format     | String                                     | Possible values are: `default`, `email`.                                                                                        |
| identifier | String                                     | Identifier used for Azure Information Protection Analytics.                                                                     |
| metadata   | keyValuePair collection | Existing Microsoft Purview Information Protection metadata is passed as key/value pairs, where the key is the MSIP_Label_GUID_PropName. |
| state      | String                                     | Possible values are: `rest`, `motion`, `use`.                                                                                   |
### [customaction](https://docs.microsoft.com/graph/api/resources/customaction?view=graph-rest-1.0&tabs=http)
| Property   | Type                                       | Description                                          |
| :--------- | :----------------------------------------- | :--------------------------------------------------- |
| name       | String                                     | Name of the custom action.                           |
| properties | keyValuePair collection | Properties, in key value pair format, of the action. |
### [downgradejustification](https://docs.microsoft.com/graph/api/resources/downgradejustification?view=graph-rest-1.0&tabs=http)
| Property             | Type    | Description                                                                                          |
| :------------------- | :------ | :--------------------------------------------------------------------------------------------------- |
| isDowngradeJustified | Boolean | Indicates whether the downgrade is or isn't justified.                                              |
| justificationMessage | String  | Message that indicates why a downgrade is justified. The message appears in administrative logs. |
### [informationprotectionaction](https://docs.microsoft.com/graph/api/resources/informationprotectionaction?view=graph-rest-1.0&tabs=http)

### [informationprotectioncontentlabel](https://docs.microsoft.com/graph/api/resources/informationprotectioncontentlabel?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|assignmentMethod|String| Possible values are: `standard`, `privileged`, `auto`.|
|creationDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|
|label|labelDetails| Details on the label that is currently applied to the file. |
### [informationprotectionlabel](https://docs.microsoft.com/graph/api/resources/informationprotectionlabel?view=graph-rest-1.0&tabs=http)
| Property    | Type    | Description                                                                                     |
| :---------- | :------ | :---------------------------------------------------------------------------------------------- |
| color       | String  | The color that the UI should display for the label, if configured.                              |
| description | String  | The admin-defined description for the label.                                                    |
| id          | String  | The label ID is a globally unique identifier (GUID)                                             |
| isActive    | Boolean | Indicates whether the label is active or not. Active labels should be hidden or disabled in UI. |
| name        | String  | The plaintext name of the label.                                                                |
| sensitivity | Int32   | The sensitivity value of the label, where lower is less sensitive.                              |
| tooltip     | String  | The tooltip that should be displayed for the label in a UI.                                     |
| parent      | labelDetails   | The parent label associated with a child label. Null if label has no parent.

### [justifyaction](https://docs.microsoft.com/graph/api/resources/justifyaction?view=graph-rest-1.0&tabs=http)

### [keyValuePair ](https://docs.microsoft.com/graph/api/resources/keyvaluepair?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|name|String|Name for this key-value pair|
|value|String|Value for this key-value pair|
### [labelingoptions](https://docs.microsoft.com/graph/api/resources/labelingoptions?view=graph-rest-1.0&tabs=http)
| Property               | Type                                                | Description                                                                                                                   |
| :--------------------- | :-------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| assignmentMethod       | String                                              | Possible values are: `standard`, `privileged`, `auto`.                                                                        |
| downgradeJustification | downgradeJustification | The downgrade justification object that indicates if downgrade was justified and, if so, the reason.                          |
| extendedProperties     | keyValuePair collection          | Extended properties will be parsed and returned in the standard MIP labeled metadata format as part of the label information. |
| labelId                | Guid                                                | The GUID of the label that should be applied to the information.                                                              |
### [metadataaction](https://docs.microsoft.com/graph/api/resources/metadataaction?view=graph-rest-1.0&tabs=http)
| Property         | Type                                       | Description                                                                        |
| :--------------- | :----------------------------------------- | :--------------------------------------------------------------------------------- |
| metadataToAdd    | keyValuePair collection | A collection of key value pairs that should be added to the file.                  |
| metadataToRemove | String collection                          | A collection of strings that indicate which keys to remove from the file metadata. |
### [protectadhocaction](https://docs.microsoft.com/graph/api/resources/protectadhocaction?view=graph-rest-1.0&tabs=http)

### [protectdonotforwardaction](https://docs.microsoft.com/graph/api/resources/protectdonotforwardaction?view=graph-rest-1.0&tabs=http)

### [recommendlabelaction](https://docs.microsoft.com/graph/api/resources/recommendlabelaction?view=graph-rest-1.0&tabs=http)
| Property                    | Type                                                                     | Description                                                                      |
| :-------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| actionSource                | String                                                                   | Possible values are: `manual`, `automatic`, `recommended`, `default`.            |
| actions                     | informationProtectionAction collection | Actions to take if the label is accepted by the user.                            |
| label                       | labelDetails                                          | The label that is being recommended.                                             |
| responsibleSensitiveTypeIds | Guid collection                                                          | The sensitive information type GUIDs that caused the recommendation to be given. |
### [removecontentfooteraction](https://docs.microsoft.com/graph/api/resources/removecontentfooteraction?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                                                |
| :------------- | :---------------- | :--------------------------------------------------------- |
| uiElementNames | String collection | The name of the UI element of the footer to be removed. |
### [removecontentheaderaction](https://docs.microsoft.com/graph/api/resources/removecontentheaderaction?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                                                |
| :------------- | :---------------- | :--------------------------------------------------------- |
| uiElementNames | String collection | The name of the UI element of the header to be removed. |
### [removeprotectionaction](https://docs.microsoft.com/graph/api/resources/removeprotectionaction?view=graph-rest-1.0&tabs=http)

### [removewatermarkaction](https://docs.microsoft.com/graph/api/resources/removewatermarkaction?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                           |
| :------------- | :---------------- | :------------------------------------ |
| uiElementNames | String collection | The name of the UI element of footer to be removed. |
### [addContentFooterAction ](https://docs.microsoft.com/graph/api/resources/security-addcontentfooteraction?view=graph-rest-1.0&tabs=http)
| Property      | Type   | Description                                                   |
| :------------ | :----- | :------------------------------------------------------------ |
| alignment     | String | The horizontal alignment of the footer.                       |
| fontColor     | String | Color of the font to use for the footer.                      |
| fontName      | String | Name of the font to use for the footer.                       |
| fontSize      | Int32  | Font size to use for the footer.                              |
| margin        | Int32  | The margin of the header from the bottom of the document.     |
| text          | String | The contents of the footer itself.                            |
| uiElementName | String | The name of the UI element where the footer should be placed. |
### [addContentHeaderAction ](https://docs.microsoft.com/graph/api/resources/security-addcontentheaderaction?view=graph-rest-1.0&tabs=http)
| Property      | Type   | Description                                                   |
| :------------ | :----- | :------------------------------------------------------------ |
| alignment     | String | The horizontal alignment of the header.                       |
| fontColor     | String | Color of the font to use for the header.                      |
| fontName      | String | Name of the font to use for the header.                       |
| fontSize      | Int32  | Font size to use for the header.                              |
| margin        | Int32  | The margin of the header from the top of the document.        |
| text          | String | The contents of the header itself.                            |
| uiElementName | String | The name of the UI element where the header should be placed. |
### [addWatermarkAction ](https://docs.microsoft.com/graph/api/resources/security-addwatermarkaction?view=graph-rest-1.0&tabs=http)
| Property      | Type   | Description                                                                 |
| :------------ | :----- | :-------------------------------------------------------------------------- |
| fontColor     | String | Color of the font to use for the watermark.                                 |
| fontName      | String | Name of the font to use for the watermark.                                  |
| fontSize      | Int32  | Font size to use for the watermark.                                         |
| layout        | String | The layout of the watermark. Possible values are: `horizontal`, `diagonal`. |
| text          | String | The contents of the watermark itself.                                       |
| uiElementName | String | The name of the UI element where the watermark should be placed.            |
### [applyLabelAction ](https://docs.microsoft.com/graph/api/resources/security-applylabelaction?view=graph-rest-1.0&tabs=http)
| Property                    | Type                                                                                           | Description                                                                                                                                   |
| :-------------------------- | :--------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------- |
| actions                     | informationProtectionAction collection | The collection of actions that should be implemented by the caller.                                                                           |
| actionSource                | actionSource                                      | Specifies why the label was selected. Possible values are: `manual`, `automatic`, `recommended`, `default`.                                   |
| responsibleSensitiveTypeIds | GUID collection                                                                                | If the label was the result of an automatic classification, supply the list of sensitive info type GUIDs that resulted in the returned label. |
### [classificationResult ](https://docs.microsoft.com/graph/api/resources/security-classificationresult?view=graph-rest-1.0&tabs=http)
| Property        | Type  | Description                                                            |
| :-------------- | :---- | :--------------------------------------------------------------------- |
| confidenceLevel | Int32 | The confidence level, 0 to 100, of the result.                         |
| count           | Int32 | The number of instances of the specific information type in the input. |
| sensitiveTypeId | GUID  | The GUID of the discovered sensitive information type.                 |
### [contentInfo ](https://docs.microsoft.com/graph/api/resources/security-contentinfo?view=graph-rest-1.0&tabs=http)
| Property      | Type                                                                                      | Description                                                                                                                     |
| :------------ | :---------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| contentFormat | String                                                                                    | The format of the content to be labeled. Possible values are: `file`, `email`.                                                                     |
| identifier    | String                                                                                    | Identifier used for Azure Information Protection Analytics.                                                                     |
| metadata      | keyValuePair collection | Existing Microsoft Purview Information Protection metadata is passed as key-value pairs, where the key is the `MSIP_Label_GUID_PropName`. |
| state         | contentState                                                                              | The usage state of the content. The possible values are: `rest`, `motion`, or `use`.                                                                                |
### [contentLabel ](https://docs.microsoft.com/graph/api/resources/security-contentlabel?view=graph-rest-1.0&tabs=http)
| Property         | Type           | Description                                                                                                                                                                                                                      |
| :--------------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| assignmentMethod | String         | Describes whether the label was applied by an automated (`standard`) process or a person (`privileged`).                                                                                                                         |
| creationDateTime | DateTimeOffset | Timestamp of when the **c
### [customAction ](https://docs.microsoft.com/graph/api/resources/security-customaction?view=graph-rest-1.0&tabs=http)
| Property   | Type                                       | Description                                          |
| :--------- | :----------------------------------------- | :--------------------------------------------------- |
| name       | String                                     | Name of the custom action.                           |
| properties | keyValuePair collection | Properties, in key-value pair format, of the action. |
### [downgradeJustification ](https://docs.microsoft.com/graph/api/resources/security-downgradejustification?view=graph-rest-1.0&tabs=http)
| Property             | Type    | Description                                                                                          |
| :------------------- | :------ | :--------------------------------------------------------------------------------------------------- |
| isDowngradeJustified | Boolean | Indicates whether the downgrade is or isn't justified.                                              |
| justificationMessage | String  | Message that indicates why a downgrade is justified. The message appears in administrative logs. |
### [informationProtectionAction ](https://docs.microsoft.com/graph/api/resources/security-informationprotectionaction?view=graph-rest-1.0&tabs=http)

### [informationProtectionPolicySetting ](https://docs.microsoft.com/graph/api/resources/security-informationprotectionpolicysetting?view=graph-rest-1.0&tabs=http)
| Property                         | Type    | Description                                                                   |
| :------------------------------- | :------ | :---------------------------------------------------------------------------- |
| id                               | String  | Unique identifier for the policy.                                             |
| isDowngradeJustificationRequired | Boolean | Exposes whether justification input is required on label downgrade.           |
| isMandatory                      | Boolean | Exposes whether mandatory labeling is enabled.                                |
| moreInfoUrl                      | String  | Exposes the more information URL that can be configured by the administrator. |
### [justifyAction ](https://docs.microsoft.com/graph/api/resources/security-justifyaction?view=graph-rest-1.0&tabs=http)

### [keyValuePair ](https://docs.microsoft.com/graph/api/resources/security-keyvaluepair?view=graph-rest-1.0&tabs=http)
| Property | Type   | Description                    |
| :------- | :----- | :----------------------------- |
| name     | String | Name for this key-value pair.  |
| value    | String | Value for this key-value pair. |
### [labelingOptions ](https://docs.microsoft.com/graph/api/resources/security-labelingoptions?view=graph-rest-1.0&tabs=http)
| Property               | Type                                                         | Description                                                                                                                                                                                |
| :--------------------- | :----------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| assignmentMethod       | String                                                       | Describes whether the label was applied by an automated (`standard`) process or a person (`privileged`). |
| downgradeJustification | downgradeJustification | The downgrade justification object that indicates if downgrade was justified and, if so, the reason.                                                                                       |
| extendedProperties     | keyValuePair collection                   | Extended properties will be parsed and returned in the standard Microsoft Purview Information Protection labeled metadata format as part of the label information.                                 |
| labelId                | GUID                                                         | The GUID of the label that should be applied to the information.                                                                                                                           |
### [metadataAction ](https://docs.microsoft.com/graph/api/resources/security-metadataaction?view=graph-rest-1.0&tabs=http)
| Property         | Type                                       | Description                                                                        |
| :--------------- | :----------------------------------------- | :--------------------------------------------------------------------------------- |
| metadataToAdd    | keyValuePair collection | A collection of key-value pairs that should be added to the file.                  |
| metadataToRemove | String collection                          | A collection of strings that indicate which keys to remove from the file metadata. |
### [protectAdhocAction ](https://docs.microsoft.com/graph/api/resources/security-protectadhocaction?view=graph-rest-1.0&tabs=http)

### [protectByTemplateAction ](https://docs.microsoft.com/graph/api/resources/security-protectbytemplateaction?view=graph-rest-1.0&tabs=http)
| Property   | Type   | Description                                                                                                  |
| :--------- | :----- | :----------------------------------------------------------------------------------------------------------- |
| templateId | String | The unique identifier for a protection template in Microsoft Purview Information Protection to apply to the content. |
### [protectDoNotForwardAction ](https://docs.microsoft.com/graph/api/resources/security-protectdonotforwardaction?view=graph-rest-1.0&tabs=http)

### [recommendLabelAction ](https://docs.microsoft.com/graph/api/resources/security-recommendlabelaction?view=graph-rest-1.0&tabs=http)
| Property                    | Type                                                                                           | Description                                                                                                 |
| :-------------------------- | :--------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------- |
| actions                     | informationProtectionAction collection | Actions to take if the label is accepted by the user.                                                       |
| actionSource                | String                                                                                         | Specifies why the label was selected. Possible values are: `manual`, `automatic`, `recommended`, `default`. |
| responsibleSensitiveTypeIds | GUID collection                                                                                | The sensitive information type GUIDs that caused the recommendation to be given.                            |
### [removeContentFooterAction ](https://docs.microsoft.com/graph/api/resources/security-removecontentfooteraction?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                                                |
| :------------- | :---------------- | :--------------------------------------------------------- |
| uiElementNames | String collection | The name of the UI element of the footer to be removed. |
### [removeContentHeaderAction ](https://docs.microsoft.com/graph/api/resources/security-removecontentheaderaction?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                                                |
| :------------- | :---------------- | :--------------------------------------------------------- |
| uiElementNames | String collection | The name of the UI element of the header to be removed. |
### [removeProtectionAction ](https://docs.microsoft.com/graph/api/resources/security-removeprotectionaction?view=graph-rest-1.0&tabs=http)

### [removeWatermarkAction ](https://docs.microsoft.com/graph/api/resources/security-removewatermarkaction?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                                            |
| :------------- | :---------------- | :----------------------------------------------------- |
| uiElementNames | String collection | The name of the UI element of watermark to be removed. |
### [sensitivityLabel ](https://docs.microsoft.com/graph/api/resources/security-sensitivitylabel?view=graph-rest-1.0&tabs=http)
| Property       | Type              | Description                                                                                                |
| :------------- | :---------------- | :--------------------------------------------------------------------------------------------------------- |
| color          | String            | The color that the UI should display for the label, if configured.                                         |
| contentFormats | String collection | Returns the supported content formats for the label.                                                       |
| description    | String            | The admin-defined description for the label.                                                               |
| hasProtection  | Boolean           | Indicates whether the label has protection actions configured.                                             |
| id             | String            | The label ID is a globally unique identifier (GUID).                                                       |
| isActive       | Boolean           | Indicates whether the label is active or not. Active labels should be hidden or disabled in the UI.        |
| isAppliable    | Boolean           | Indicates whether the label can be applied to content. `False` if the label is a parent with child labels. |
| name           | String            | The plaintext name of the label.                                                                           |
| sensitivity    | Int32             | The sensitivity value of the label, where lower is less sensitive.                                         |
| tooltip        | String            | The tooltip that should be displayed for the label in a UI.                                                |
