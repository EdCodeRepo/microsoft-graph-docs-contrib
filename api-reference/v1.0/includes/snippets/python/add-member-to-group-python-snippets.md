---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = ReferenceCreate(
	odata_id = "https://graph.microsoft.com/v1.0/directoryObjects/{id}",
)

await graph_client.groups.by_group_id('group-id').members.ref.post(request_body)


```