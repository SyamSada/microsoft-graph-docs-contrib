---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


result = await graph_client.print.shares.by_share_id('printerShare-id').jobs.by_job_id('printJob-id').start.post()


```