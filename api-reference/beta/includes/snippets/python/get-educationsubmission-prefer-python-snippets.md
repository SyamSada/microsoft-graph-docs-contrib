---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


request_configuration = EducationSubmissionRequestBuilder.EducationSubmissionRequestBuilderGetRequestConfiguration(
headers = {
		'Prefer' : "include-unknown-enum-members",
}

)

result = await graph_client.education.classes.by_classe_id('educationClass-id').assignments.by_assignment_id('educationAssignment-id').submissions.by_submission_id('educationSubmission-id').get(request_configuration = request_configuration)


```