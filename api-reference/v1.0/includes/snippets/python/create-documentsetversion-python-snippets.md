---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = DocumentSetVersion(
	comment = "v1",
	should_capture_minor_version = False,
)

result = await graph_client.sites.by_site_id('site-id').lists.by_list_id('list-id').items.by_item_id('listItem-id').document_set_versions.post(request_body = request_body)


```