---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = OnlineMeeting(
	start_date_time = "2019-07-12T14:30:34.2444915-07:00",
	end_date_time = "2019-07-12T15:00:34.2464912-07:00",
	subject = "User meeting",
	join_meeting_id_settings = JoinMeetingIdSettings(
		is_passcode_required = True,
	),
)

result = await graph_client.me.online_meetings.post(request_body = request_body)


```