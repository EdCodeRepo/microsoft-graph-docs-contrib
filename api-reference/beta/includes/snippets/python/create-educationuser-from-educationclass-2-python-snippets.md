---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = ReferenceCreate(
	odata_id = "https://graph.microsoft.com/beta/education/users/14011",
)

await graph_client.education.classes.by_education_class_id('educationClass-id').teachers.ref.post(request_body)


```