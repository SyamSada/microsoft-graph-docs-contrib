---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new Group
{
	Description = "Group with designated owner and members",
	DisplayName = "Operations group",
	GroupTypes = new List<string>
	{
	},
	MailEnabled = false,
	MailNickname = "operations2019",
	SecurityEnabled = true,
	AdditionalData = new Dictionary<string, object>
	{
		{
			"owners@odata.bind" , new List<string>
			{
				"https://graph.microsoft.com/beta/users/26be1845-4119-4801-a799-aea79d09f1a2",
			}
		},
		{
			"members@odata.bind" , new List<string>
			{
				"https://graph.microsoft.com/beta/users/ff7cb387-6688-423c-8188-3da9532a73cc",
				"https://graph.microsoft.com/beta/users/69456242-0067-49d3-ba96-9de6f2728e14",
			}
		},
	},
};
var result = await graphClient.Groups.PostAsync(requestBody);


```