

# V2alpha1CronJobStatus

CronJobStatus represents the current state of a cron job.
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | [**List&lt;V1ObjectReference&gt;**](V1ObjectReference.md) | A list of pointers to currently running jobs. |  [optional]
**lastScheduleTime** | [**DateTime**](DateTime.md) | Information when was the last time the job was successfully scheduled. |  [optional]



