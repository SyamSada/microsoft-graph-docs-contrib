---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = QueryPostRequestBody(
	requests = [
		SearchRequest(
			entity_types = [
				EntityType.ChatMessage,
			]
			query = SearchQuery(
				query_string = "test",
			),
			from = 0,
			size = 15,
			enable_top_results = True,
		),
	]
)

result = await graph_client.search.query.post(request_body = request_body)


```