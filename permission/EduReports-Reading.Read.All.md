# EduReports-Reading.Read.All

> Allows the app to read all tenant users reading assignments submissions data without a signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|Beta|A|[GET /education/reports/readingAssignmentSubmission](https://docs.microsoft.com/graph/api/readingassignmentsubmission-get?view=graph-rest-beta&tabs=http)|
|Beta|A|[GET /education/reports/reflectCheckInResponses](https://docs.microsoft.com/graph/api/reflectcheckinresponse-get?view=graph-rest-beta&tabs=http)|
## Application Permission
|||
|-|-|
|**Id**|ad248c30-1919-40c8-b3d2-304481894e88|
|**Display String**|Read all tenant reading assignments submissions data|
|**Description**|Allows the app to read all tenant users reading assignments submissions data without a signed-in user.|
## Resources
### [readingAssignmentSubmission ](https://docs.microsoft.com/graph/api/resources/readingassignmentsubmission?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|accuracyScore|Double|Accuracy score of the reading progress.|
|action|String|Indicates whether the submission is an attempt by the student or a miscue edit done by the educator. The possible values are `Attempt` and `EditMiscue`.
|assignmentId|String|ID of the assignment with which this submission is associated.|
|challengingWords|challengingWord collection|List of words that the student found challenging during the reading session.|
|classId|String|ID of the class this reading progress is associated with.|
|insertions|Int64|Insertions of the reading progress.|
|mispronunciations|Int64|Mispronunciations of the reading progress.|
|missedExclamationMarks|Int64 |Number of exclamation marks missed in the reading passage.|
|missedPeriods|Int64 |Number of periods missed in the reading passage.|
|missedQuestionMarks|Int64|Number of question marks missed in the reading passage.|
|missedShorts|Int64|Number of short words missed during the reading session.|
|monotoneScore|Double|Score that reflects the student's use of intonation and expression. Lower scores indicate more monotone reading.|
|omissions|Int64|Omissions of the reading progress.|
|repetitions|Int64|Number of times the student repeated words or phrases during the reading session.|
|selfCorrections|Int64|Number of times the student self-corrected their reading errors.|
|studentId|String|ID of the user this reading progress is associated with.|
|submissionId|String|ID of the submission this reading progress is associated with.|
|submissionDateTime|DateTimeOffset|Date and time of the submission this reading progress is associated with. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|unexpectedPauses|Int64|Number of unexpected pauses made during the reading session.|
|wordCount|Int64|Words count of the reading progress.|
|wordsPerMinute|Double|Words per minute of the reading progress.|
### [reflectCheckInResponse ](https://docs.microsoft.com/graph/api/resources/reflectcheckinresponse?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|checkInId|String|Identifier for the Reflect check-in.|
|checkInTitle|String|The question or prompt of the Reflect check-in that this response addresses.|
|classId|String|ID of the class associated with the Reflect check-in.|
|createdDateTime|DateTimeOffset|Date and time when the Reflect check-in was created. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
|creatorId|String|ID of the user who created the Reflect check-in.|
|isClosed|Boolean|Indicates whether the Reflect check-in is closed (`true`) or open (`false`).|
|responderId|String|ID of the user who responded to the Reflect check-in.|
|responseEmotion|responseEmotionType|Represents the pleasantness level of the response that indicates how pleasant the responder felt. The possible values are: `none`, `confident`, `excited`, `happy`, `motivated`, `peaceful`, `ambitious`, `cheerful`, `comfortable`, `creative`, `determined`, `energized`, `focused`, `fulfilled`, `grateful`, `included`, `inspired`, `optimistic`, `proud`, `successful`, `valuable`, `annoyed`, `bored`, `calm`, `confused`, `glad`, `content`, `pensive`, `reserved`, `restless`, `shocked`, `tired`, `angry`, `depressed`, `exhausted`, `lonely`, `nervous`, `anxious`, `apathetic`, `concerned`, `disappointed`, `frightened`, `frustrated`, `hopeless`, `hurt`, `jealous`, `miserable`, `overwhelmed`, `skeptical`, `stressed`, `stuck`, `worthless`, `awed`, `ashamed`, `curious`, `sensitive`, `sad`, `unknownFutureValue`.|
|responseFeedback|responseFeedbackType|Represents the exact emotion name that the responder felt during the Reflect check-in response. The possible values are: `none`, `notDetected`, `veryUnpleasant`, `unpleasant`, `neutral`, `pleasant`, `veryPleasant`, `unknownFutureValue`.|
|submitDateTime|DateTimeOffset|Date and time when the response to the Reflect check-in was submitted. The timestamp type represents date and time information using ISO 8601 format and is always in UTC. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|
