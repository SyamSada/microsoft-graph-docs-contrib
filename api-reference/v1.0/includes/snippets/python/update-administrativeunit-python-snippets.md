---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = AdministrativeUnit(
	display_name = "Greater Seattle District Technical Schools",
)

result = await graph_client.directory.administrative_units.by_administrative_unit_id('administrativeUnit-id').patch(request_body = request_body)


```