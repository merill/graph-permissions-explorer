# Insights-UserMetric.Read.All

> Allows an app to read user metrics insights, such as daily and monthly active users, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A,D|[daily GET /userInsightsRoot/daily/summary](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-summary?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/daily/activeUsers](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-activeusers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/daily/authentications](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-authentications?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/daily/mfaCompletions](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-mfacompletions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/daily/requests](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-requests?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/daily/signUps](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-signups?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/daily/userCount](https://docs.microsoft.com/graph/api/dailyuserinsightmetricsroot-list-usercount?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/monthly/activeUsers](https://docs.microsoft.com/graph/api/monthlyuserinsightmetricsroot-list-activeusers?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/monthly/authentications](https://docs.microsoft.com/graph/api/monthlyuserinsightmetricsroot-list-authentications?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/monthly/mfaCompletions](https://docs.microsoft.com/graph/api/monthlyuserinsightmetricsroot-list-mfacompletions?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/monthly/requests](https://docs.microsoft.com/graph/api/monthlyuserinsightmetricsroot-list-requests?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsights/monthly/signUps](https://docs.microsoft.com/graph/api/monthlyuserinsightmetricsroot-list-signups?view=graph-rest-beta&tabs=http)|
|Beta|A,D|[GET /reports/userInsightsRoot/monthly/summary](https://docs.microsoft.com/graph/api/monthlyuserinsightmetricsroot-list-summary?view=graph-rest-beta&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|7d249730-51a3-4180-8ec1-214f144f1bff|
|**Consent Type**|Admin|
|**Display String**|Read user metrics insights|
|**Description**|Allows an app to read user metrics insights, such as daily and monthly active users, on behalf of the signed-in user.|
## Application Permission
|||
|-|-|
|**Id**|34cbd96c-d824-4755-90d3-1008ef47efc1|
|**Display String**|Read all user metrics insights|
|**Description**|Allows an app to read all user metrics insights, such as daily and monthly active users, without a signed-in user.|
## Resources
### [activeUsersMetric ](https://docs.microsoft.com/graph/api/resources/activeusersmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|count|Int64|The total number of users who made at least one authentication request within the specified time period.|
|factDate|Date|Date of the insight.|
|id|String|Identifier for the user insight. Inherited from entity.|
### [authenticationsMetric ](https://docs.microsoft.com/graph/api/resources/authenticationsmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| appid | String | The ID of the Microsoft Entra application. Supports `$filter` (`eq`). |
| attemptsCount | Int64 | The number of authentication requests made in the specified period. Supports `$filter` (`eq`). |
| country | String | The location where the customers authenticated from. Supports `$filter` (`eq`). |
| factDate | Date | The date of the user insight. |
| id | String | Identifier for the user insight. Inherited from entity.|
| os | String | The platform for the device that the customers used. Supports `$filter` (`eq`). |
| successCount | Int64 | Number of successful authentication requests. Supports `$filter` (`eq`). |
### [insightSummary ](https://docs.microsoft.com/graph/api/resources/insightsummary?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|activeUsers|Int64|Daily active users.|
|appId|String|The ID of the Microsoft Entra application.|
|authenticationCompletions|Int64|Daily authentication completions.|
|authenticationRequests|Int64|Daily authentication requests.|
|factDate|Date|The date of the insight.|
|id|String|Identifier for the insight. Inherited from entity.|
|os|String|The platform for the device that the customers used. Supports `$filter` (`eq`).|
|securityTextCompletions|Int64|Daily MFA SMS completions.|
|securityTextRequests|Int64|Daily MFA SMS requests.|
|securityVoiceCompletions|Int64|Daily MFA Voice completions.|
|securityVoiceRequests|Int64|Daily MFA Voice requests.|
### [mfaCompletionMetric ](https://docs.microsoft.com/graph/api/resources/mfacompletionmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|appId|String|The ID of the Microsoft Entra application. Supports `$filter` (`eq`).|
|attemptsCount|Int64|Number of users who attempted to sign up. Supports `$filter` (`eq`).|
|factDate|Date|The date of the user insight.|
|id|String|Identifier for the user insight. Inherited from entity.|
|mfaMethod|String|The MFA authentication method used by the customers. Supports `$filter` (`eq`).|
|os|String|The platform of the device that the customers used. Supports `$filter` (`eq`).|
|successCount|Int64|Number of users who signed up successfully. Supports `$filter` (`eq`).|
### [userCountMetric ](https://docs.microsoft.com/graph/api/resources/usercountmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|count|Int64| The total number of users in the tenant over time.|
|factDate|Date| The date of the insight.|
|id|String| Identifier for the insight. Inherited from entity.|
### [userRequestsMetric ](https://docs.microsoft.com/graph/api/resources/userrequestsmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|factDate|Date|The date of the user insight.|
|id|String|Identifier for the user insight. Inherited from entity.|
|requestCount|Int64|Number of requests to the tenant. Supports `$filter` (`eq`).|
### [userSignUpMetric ](https://docs.microsoft.com/graph/api/resources/usersignupmetric?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|count|Int64|The total number of users who signed up in the specified period. Supports `$filter` (`eq`).|
|factDate|Date|The date of the user insight.|
|id|String|Identifier for the user insight. Inherited from entity.|
|os|String|The device plaform that the customers used. Supports `$filter` (`eq`).|
