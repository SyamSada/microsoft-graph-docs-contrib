---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var result = await graphClient.Users.GetAsync((requestConfiguration) =>
{
	requestConfiguration.QueryParameters.Select = new string []{ "id","displayName","mail","identities" };
	requestConfiguration.QueryParameters.Filter = "endsWith(userPrincipalName,'";
	requestConfiguration.Headers.Add("ConsistencyLevel", "eventual");
});


```