---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = CreateOrGetPostRequestBody(
	chat_info = ChatInfo(
		thread_id = "19:7ebda77322dd4505ac4dedb5b67df076@thread.tacv2",
	),
	start_date_time = "2020-02-06T01:49:21.3524945+00:00",
	end_date_time = "2020-02-06T02:19:21.3524945+00:00",
	external_id = "7eb8263f-d0e0-4149-bb1c-1f0476083c56",
	participants = MeetingParticipants(
		attendees = [
			MeetingParticipantInfo(
				identity = IdentitySet(
					user = Identity(
						id = "1f35f2e6-9cab-44ad-8d5a-b74c14720000",
					),
				),
				upn = "test1@contoso.com",
			),
		]
	),
	subject = "Create a meeting with customId provided",
)

result = await graph_client.me.online_meetings.create_or_get.post(request_body = request_body)


```