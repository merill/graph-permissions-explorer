# RecordsManagement.ReadWrite.All

> Allow the application to create, update and delete any data from Records Management, such as configuration, labels, and policies on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[](https://docs.microsoft.com/graph/api/security-retentionlabel-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/authorities/{authorityTemplateId}](https://docs.microsoft.com/graph/api/security-labelsroot-delete-authorities?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/authorities/{authorityTemplateId}/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-authorities?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/categories/{categoryTemplateId}](https://docs.microsoft.com/graph/api/security-labelsroot-delete-categories?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/categories/{categoryTemplateId}/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-categories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /security/labels/categories/{categoryTemplateId}/subcategories/{subcategoryTemplateId}/$ref](https://docs.microsoft.com/graph/api/security-categorytemplate-delete-subcategories?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/citations/{citationTemplateId}](https://docs.microsoft.com/graph/api/security-labelsroot-delete-citations?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/citations/{citationTemplateId}/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-citations?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/departments/{departmentTemplateId}](https://docs.microsoft.com/graph/api/security-labelsroot-delete-departments?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/departments/{departmentTemplateId}/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-departments?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/filePlanReferences/{filePlanReferenceTemplateId}](https://docs.microsoft.com/graph/api/security-labelsroot-delete-fileplanreferences?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/filePlanReferences/{filePlanReferenceTemplateId}/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-fileplanreferences?view=graph-rest-1.0&tabs=http)|
|V1|D|[DELETE /security/labels/retentionLabels/{retentionLabelId}](https://docs.microsoft.com/graph/api/security-retentionlabel-delete?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/authorityTemplate](https://docs.microsoft.com/graph/api/security-labelsroot-delete-authorities?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/authorityTemplate/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-authorities?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/categoryTemplate](https://docs.microsoft.com/graph/api/security-labelsroot-delete-categories?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/categoryTemplate/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-categories?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/citationTemplate](https://docs.microsoft.com/graph/api/security-labelsroot-delete-citations?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/citationTemplate/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-citations?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/departmentTemplate](https://docs.microsoft.com/graph/api/security-labelsroot-delete-departments?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/departmentTemplate/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-departments?view=graph-rest-1.0&tabs=http)|
|Beta|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/filePlanReferenceTemplate](https://docs.microsoft.com/graph/api/security-labelsroot-delete-fileplanreferences?view=graph-rest-beta&tabs=http)|
|V1|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/descriptors/filePlanReferenceTemplate/$ref](https://docs.microsoft.com/graph/api/security-labelsroot-delete-fileplanreferences?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /security/labels/retentionLabels/{retentionLabelId}/eventType/$ref](https://docs.microsoft.com/graph/api/security-retentioneventtype-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /security/triggers/retentionEvents/{retentionEventId}](https://docs.microsoft.com/graph/api/security-retentionevent-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /security/triggers/retentionEvents/{retentionEventId}/retentionEventType/$ref](https://docs.microsoft.com/graph/api/security-retentioneventtype-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[DELETE /security/triggerTypes/retentionEventTypes/{retentionEventTypeId}/$ref](https://docs.microsoft.com/graph/api/security-retentioneventtype-delete?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/authorities](https://docs.microsoft.com/graph/api/security-labelsroot-list-authorities?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/authorities/{authorityTemplateId}](https://docs.microsoft.com/graph/api/security-authoritytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/categories](https://docs.microsoft.com/graph/api/security-labelsroot-list-categories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/categories/{categoryTemplateId}](https://docs.microsoft.com/graph/api/security-categorytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/categories/{categoryTemplateId}/subcategories](https://docs.microsoft.com/graph/api/security-categorytemplate-list-subcategories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/categories/{categoryTemplateId}/subcategories/{subcategoryTemplateId}](https://docs.microsoft.com/graph/api/security-subcategorytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/citations](https://docs.microsoft.com/graph/api/security-labelsroot-list-citations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/citations/{citationTemplateId}](https://docs.microsoft.com/graph/api/security-citationtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/departments](https://docs.microsoft.com/graph/api/security-labelsroot-list-departments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/departments/{departmentTemplateId}](https://docs.microsoft.com/graph/api/security-departmenttemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/filePlanReferences](https://docs.microsoft.com/graph/api/security-labelsroot-list-fileplanreferences?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/filePlanReferences/{filePlanReferenceTemplateId}](https://docs.microsoft.com/graph/api/security-fileplanreferencetemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/labels/retentionLabels](https://docs.microsoft.com/graph/api/security-labelsroot-list-retentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/labels/retentionLabels/{retentionLabelId}](https://docs.microsoft.com/graph/api/security-retentionlabel-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/retentionLabels/{retentionLabelId}/descriptors/authorityTemplate](https://docs.microsoft.com/graph/api/security-authoritytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/retentionLabels/{retentionLabelId}/descriptors/categoryTemplate](https://docs.microsoft.com/graph/api/security-categorytemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/retentionLabels/{retentionLabelId}/descriptors/citationTemplate](https://docs.microsoft.com/graph/api/security-citationtemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/retentionLabels/{retentionLabelId}/descriptors/departmentTemplate](https://docs.microsoft.com/graph/api/security-departmenttemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/retentionLabels/{retentionLabelId}/descriptors/filePlanReferenceTemplate](https://docs.microsoft.com/graph/api/security-fileplanreferencetemplate-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/labels/retentionLabels/{retentionLabelId}/eventType](https://docs.microsoft.com/graph/api/security-retentioneventtype-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/triggers/retentionEvents](https://docs.microsoft.com/graph/api/security-retentionevent-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/triggers/retentionEvents/{retentionEventId}](https://docs.microsoft.com/graph/api/security-retentionevent-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /security/triggers/retentionEvents/{retentionEventId}/labels/{retentionLabelId}](https://docs.microsoft.com/graph/api/security-retentionlabel-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/triggers/retentionEvents/{retentionEventId}/retentionEventType](https://docs.microsoft.com/graph/api/security-retentioneventtype-get?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/triggerTypes/retentionEventTypes](https://docs.microsoft.com/graph/api/security-retentioneventtype-list?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[GET /security/triggerTypes/retentionEventTypes/{retentionEventTypeId}](https://docs.microsoft.com/graph/api/security-retentioneventtype-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /security/labels/retentionLabels/{retentionLabelId}](https://docs.microsoft.com/graph/api/security-retentionlabel-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /security/labels/retentionLabels/{retentionLabelId}/eventType](https://docs.microsoft.com/graph/api/security-retentioneventtype-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /security/triggers/retentionEvents/{retentionEventId}/retentionEventType](https://docs.microsoft.com/graph/api/security-retentioneventtype-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[PATCH /security/triggerTypes/retentionEventTypes/{retentionEventTypeId}](https://docs.microsoft.com/graph/api/security-retentioneventtype-update?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/labels/authorities](https://docs.microsoft.com/graph/api/security-labelsroot-post-authorities?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/labels/categories](https://docs.microsoft.com/graph/api/security-labelsroot-post-categories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/labels/categories/{categoryTemplateId}/subcategories](https://docs.microsoft.com/graph/api/security-categorytemplate-post-subcategories?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/labels/citations](https://docs.microsoft.com/graph/api/security-labelsroot-post-citations?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/labels/departments](https://docs.microsoft.com/graph/api/security-labelsroot-post-departments?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/labels/filePlanReferences](https://docs.microsoft.com/graph/api/security-labelsroot-post-fileplanreferences?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /security/labels/retentionLabels](https://docs.microsoft.com/graph/api/security-labelsroot-post-retentionlabel?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/triggers/retentionEvents](https://docs.microsoft.com/graph/api/security-retentionevent-post?view=graph-rest-1.0&tabs=http)|
|V1|A,D|[POST /security/triggerTypes/retentionEventTypes](https://docs.microsoft.com/graph/api/security-retentioneventtype-post?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|f2833d75-a4e6-40ab-86d4-6dfe73c97605|
|**Consent Type**|Admin|
|**Display String**|Read and write Records Management configuration, labels, and policies|
|**Description**|Allow the application to create, update and delete any data from Records Management, such as configuration, labels, and policies on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|eb158f57-df43-4751-8b21-b8932adb3d34|
|**Display String**|Read and write Records Management configuration, labels and policies|
|**Description**|Allow the application to create, update and delete any data from Records Management, such as configuration, labels, and policies without the signed in user.|
## Resources
### [authorityTemplate ](https://docs.microsoft.com/graph/api/resources/security-authoritytemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|Represents the user who created the authority descriptor. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the authority descriptor is created. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|displayName|String|Unique string that defines an authority name. Inherited from microsoft.graph.security.filePlanDescriptorTemplate.|
|id|String|Unique ID of the authority. Inherited from microsoft.graph.entity. Read-only.|
### [categoryTemplate ](https://docs.microsoft.com/graph/api/resources/security-categorytemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|Represents the user who created the category descriptor. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the category descriptor is created. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|displayName|String|Unique string that defines a category name. Inherited from microsoft.graph.security.filePlanDescriptorTemplate.|
|id|String|Unique ID of the category. Inherited from microsoft.graph.entity. Read-only.|
### [citationTemplate ](https://docs.microsoft.com/graph/api/resources/security-citationtemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|citationJurisdiction|String|Represents the jurisdiction or agency that published the citation.|
|citationUrl|String|Represents the URL to the published citation.|
|createdBy|microsoft.graph.identitySet|Represents the user who created the citation descriptor. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the citation descriptor is created. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|displayName|String|Unique string that defines a citation name. Inherited from microsoft.graph.security.filePlanDescriptorTemplate.|
|id|String|Unique ID of the citation. Inherited from microsoft.graph.entity. Read-only.|
### [departmentTemplate ](https://docs.microsoft.com/graph/api/resources/security-departmenttemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|Represents the user who created the department descriptor. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the department descriptor is created. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|displayName|String|Unique string that defines a department name. Inherited from microsoft.graph.security.filePlanDescriptorTemplate.|
|id|String|Unique ID of the department. Inherited from microsoft.graph.entity. Read-only.|
### [dispositionReviewStage ](https://docs.microsoft.com/graph/api/resources/security-dispositionreviewstage?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|id|String|Unique ID for each stage. |
|name|String|Name representing each stage within a collection. |
|reviewersEmailAddresses|String collection|A collection of reviewers at each stage. |
|stageNumber|String|The unique sequence number for each stage of the disposition review. |
### [eventQuery ](https://docs.microsoft.com/graph/api/resources/security-eventquery?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|queryType|microsoft.graph.security.queryType|Represents the type of query associated with an event. 'files' for SPO and ODB and 'messages' for EXO.The possible values are: `files`, `messages`, `unknownFutureValue`.|
|query|String|Represents unique identification for the  query. 'Asset ID' for SharePoint Online and OneDrive for Business, 'keywords' for Exchange Online.|
### [filePlanDescriptor ](https://docs.microsoft.com/graph/api/resources/security-fileplandescriptor?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|authority|microsoft.graph.security.filePlanAuthority|Represents the file plan descriptor of type authority applied to a particular retention label.|
|appliedCategory|microsoft.graph.security.filePlanAppliedCategory|Represents the file plan descriptor of type category applied to a particular retention label.|
|citation|microsoft.graph.security.filePlanCitation|Represents the file plan descriptor of type citation applied to a particular retention label.|
|department|microsoft.graph.security.filePlanDepartment|Represents the file plan descriptor of type department applied to a particular retention label.|
|filePlanReference|microsoft.graph.security.filePlanReference|Represents the file plan descriptor of type filePlanReference applied to a particular retention label.  |
### [filePlanReferenceTemplate ](https://docs.microsoft.com/graph/api/resources/security-fileplanreferencetemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|Represents the user who created the file plan reference descriptor. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the filePlanReference descriptor is created. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|displayName|String|Unique string that defines a filePlanReference name. Inherited from microsoft.graph.security.filePlanDescriptorTemplate.|
|id|String|Unique ID of the filePlanReference. Inherited from microsoft.graph.entity. Read-only.|
### [retentionDuration ](https://docs.microsoft.com/graph/api/resources/security-retentionduration?view=graph-rest-1.0&tabs=http)

### [retentionEvent ](https://docs.microsoft.com/graph/api/resources/security-retentionevent?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|The user who created the retentionEvent.|
|createdDateTime|DateTimeOffset|The date time when the retentionEvent was created.|
|description|String|Optional information about the event.|
|displayName|String|Name of the event.|
|eventPropagationResults|microsoft.graph.security.eventPropagationResult collection|Represents the success status of a created event and additional information.|
|eventQueries|microsoft.graph.security.eventQuery collection| Represents the workload (SharePoint Online, OneDrive for Business, Exchange Online) and identification information associated with a retention event.|
|eventStatus|microsoft.graph.security.retentionEventStatus|Status of event propogation to the scoped locations after the event has been created.|
|eventTriggerDateTime|DateTimeOffset|Optional time when the event should be triggered.|
|id|String|Represents the unique ID of the user who created the retentionEvent. entity.|
|lastModifiedBy|microsoft.graph.identitySet|The user who last modified the retentionEvent.|
|lastModifiedDateTime|DateTimeOffset|The latest date time when the retentionEvent was modified.|
|lastStatusUpdateDateTime|DateTimeOffset|Last time the status of the event was updated.|
### [retentionEventType ](https://docs.microsoft.com/graph/api/resources/security-retentioneventtype?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|The user who created the retentionEventType.|
|createdDateTime|DateTimeOffset|The date time when the retentionEventType was created.|
|description|String|Optional information about the event type.|
|displayName|String|Name of the event type.|
|id|String|Represents the unique ID of the user who created the retentionEventType. entity.|
|lastModifiedBy|microsoft.graph.identitySet|The user who last modified the retentionEventType.|
|lastModifiedDateTime|DateTimeOffset|The latest date time when the retentionEventType was modified.|
### [retentionLabel ](https://docs.microsoft.com/graph/api/resources/security-retentionlabel?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|actionAfterRetentionPeriod|microsoft.graph.security.actionAfterRetentionPeriod| Specifies the action to take on the labeled document after the period specified by the retentionDuration property expires. The possible values are: `none`, `delete`, `startDispositionReview`, `unknownFutureValue`.|
|behaviorDuringRetentionPeriod|microsoft.graph.security.behaviorDuringRetentionPeriod|Specifies how the behavior of a document with this label should be during the retention period. The possible values are: `doNotRetain`, `retain`, `retainAsRecord`, `retainAsRegulatoryRecord`, `unknownFutureValue`.|
|createdBy|microsoft.graph.identitySet|Represents the user who created the retentionLabel.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the retentionLabel is created.|
|descriptionForAdmins|String|Provides label information for the admin. Optional.|
|descriptionForUsers|String|Provides the label information for the user. Optional.|
|displayName|String|Unique string that defines a label name.|
|id|String|Unique ID of the retentionLabel.|
|isInUse|Boolean|Specifies whether the label is currently being used.|
|lastModifiedBy|microsoft.graph.identitySet|The user who last modified the retentionLabel.|
|lastModifiedDateTime|DateTimeOffset|The latest date time when the retentionLabel was modified.|
|retentionDuration|microsoft.graph.security.retentionDuration|Specifies the number of days to retain the content.|
|retentionTrigger|microsoft.graph.security.retentionTrigger|Specifies whether the retention duration is calculated from the content creation date, labeled date, or last modification date. The possible values are: `dateLabeled`, `dateCreated`, `dateModified`, `dateOfEvent`, `unknownFutureValue`.|
|defaultRecordBehavior|microsoft.graph.security.defaultRecordBehavior|Specifies the locked or unlocked state of a record label when it is created.The possible values are: `startLocked`, `startUnlocked`, `unknownFutureValue`.|
|labelToBeApplied|String|Specifies the replacement label to be applied automatically after the retention period of the current label ends. |
### [subcategoryTemplate ](https://docs.microsoft.com/graph/api/resources/security-subcategorytemplate?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|createdBy|microsoft.graph.identitySet|Represents the user who created the subcategory descriptor. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|createdDateTime|DateTimeOffset|Represents the date and time in which the subcategory descriptor is created. Inherited from microsoft.graph.security.filePlanDescriptorTemplate. Read-only.|
|displayName|String|Unique string that defines a subcategory name. Inherited from microsoft.graph.security.filePlanDescriptorTemplate.|
|id|String|Unique ID of the subcategory. Inherited from microsoft.graph.entity. Read-only.|
