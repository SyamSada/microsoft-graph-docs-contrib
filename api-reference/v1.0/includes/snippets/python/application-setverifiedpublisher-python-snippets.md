---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = SetVerifiedPublisherPostRequestBody(
	verified_publisher_id = "1234567",
)

await graph_client.applications.by_application_id('application-id').set_verified_publisher.post(request_body = request_body)


```