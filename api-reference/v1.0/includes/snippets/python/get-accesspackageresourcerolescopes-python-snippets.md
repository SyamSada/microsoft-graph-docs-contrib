---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = AccessPackageRequestBuilder.AccessPackageRequestBuilderGetQueryParameters(
		expand = ["resourceRoleScopes($expand=role,scope)"],
)

request_configuration = AccessPackageRequestBuilder.AccessPackageRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.entitlement_management.acce_packages.by_acces_package_id('accessPackage-id').get(request_configuration = request_configuration)


```