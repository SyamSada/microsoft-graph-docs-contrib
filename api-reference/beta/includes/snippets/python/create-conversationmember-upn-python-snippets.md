---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = AadUserConversationMember(
	odata_type = "#microsoft.graph.aadUserConversationMember",
	roles = [
		"owner",
	]
	additional_data = {
			"user@odata_bind" : "https://graph.microsoft.com/v1.0/users('jacob@contoso.com')",
	}
)

result = await graph_client.teams.by_team_id('team-id').members.post(request_body = request_body)


```