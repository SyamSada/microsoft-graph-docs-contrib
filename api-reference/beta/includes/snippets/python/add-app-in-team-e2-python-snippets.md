---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = TeamsAppInstallation(
	consented_permission_set = TeamsAppPermissionSet(
		resource_specific_permissions = [
			TeamsAppResourceSpecificPermission(
				permission_value = "OnlineMeeting.ReadBasic.Chat",
				permission_type = TeamsAppResourceSpecificPermissionType.Delegated,
			),
			TeamsAppResourceSpecificPermission(
				permission_value = "ChatMessage.Read.Chat",
				permission_type = TeamsAppResourceSpecificPermissionType.Application,
			),
		]
	),
	additional_data = {
			"teams_app@odata_bind" : "https://graph.microsoft.com/beta/appCatalogs/teamsApps/7023576d-9e40-47ca-9cf2-daae6838e785",
	}
)

result = await graph_client.teams.by_team_id('team-id').installed_apps.post(request_body = request_body)


```