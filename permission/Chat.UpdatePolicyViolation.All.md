# Chat.UpdatePolicyViolation.All

> Allows the app to update Microsoft Teams 1-to-1 or group chat messages by patching a set of Data Loss Prevention (DLP) policy violation properties to handle the output of DLP processing.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[PATCH /teams/(team-id)/channels/{channel-id}/messages/{message-id}](https://docs.microsoft.com/graph/api/chatmessage-update?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /teams/(team-id)/channels/{channel-id}/messages/{message-id}/replies/{reply-id}](https://docs.microsoft.com/graph/api/chatmessage-update?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|7e847308-e030-4183-9899-5235d7270f58|
|**Display String**|Flag chat messages for violating policy|
|**Description**|Allows the app to update Microsoft Teams 1-to-1 or group chat messages by patching a set of Data Loss Prevention (DLP) policy violation properties to handle the output of DLP processing.|
