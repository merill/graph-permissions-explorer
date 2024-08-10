# ChannelMessage.UpdatePolicyViolation.All

> Allows the app to update Microsoft Teams channel messages by patching a set of Data Loss Prevention (DLP) policy violation properties to handle the output of DLP processing.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|A|[PATCH /teams/(team-id)/channels/{channel-id}/messages/{message-id}](https://docs.microsoft.com/graph/api/chatmessage-update?view=graph-rest-1.0&tabs=http)|
|V1|A|[PATCH /teams/(team-id)/channels/{channel-id}/messages/{message-id}/replies/{reply-id}](https://docs.microsoft.com/graph/api/chatmessage-update?view=graph-rest-1.0&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|4d02b0cc-d90b-441f-8d82-4fb55c34d6bb|
|**Display String**|Flag channel messages for violating policy|
|**Description**|Allows the app to update Microsoft Teams channel messages by patching a set of Data Loss Prevention (DLP) policy violation properties to handle the output of DLP processing.|
