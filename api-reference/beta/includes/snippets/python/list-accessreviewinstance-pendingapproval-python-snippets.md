---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = PendingAccessReviewInstancesRequestBuilder.PendingAccessReviewInstancesRequestBuilderGetQueryParameters(
		expand = ["definition"],
		top = 100,
		skip = 0,
)

request_configuration = PendingAccessReviewInstancesRequestBuilder.PendingAccessReviewInstancesRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.me.pending_acces_review_instances.get(request_configuration = request_configuration)


```