---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


result = await graph_client.privileged_access.by_privileged_acce_id('privilegedAccess-id').role_assignment_requests.by_role_assignment_request_id('governanceRoleAssignmentRequest-id').update_request.post()


```