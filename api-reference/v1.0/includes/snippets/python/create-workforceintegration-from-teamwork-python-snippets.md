---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = WorkforceIntegration(
	display_name = "displayName-value",
	api_version = 99,
	encryption = WorkforceIntegrationEncryption(
		protocol = WorkforceIntegrationEncryptionProtocol.SharedSecret,
		secret = "secret-value",
	),
	is_active = True,
	url = "url-value",
	supported_entities = WorkforceIntegrationSupportedEntities.None,
)

result = await graph_client.teamwork.workforce_integrations.post(request_body = request_body)


```