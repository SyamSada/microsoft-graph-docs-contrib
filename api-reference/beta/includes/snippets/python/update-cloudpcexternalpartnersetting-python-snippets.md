---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = CloudPcExternalPartnerSetting(
	odata_type = "#microsoft.graph.cloudPcExternalPartnerSetting",
	enable_connection = True,
)

result = await graph_client.device_management.virtual_endpoint.external_partner_settings.by_external_partner_setting_id('cloudPcExternalPartnerSetting-id').patch(request_body = request_body)


```