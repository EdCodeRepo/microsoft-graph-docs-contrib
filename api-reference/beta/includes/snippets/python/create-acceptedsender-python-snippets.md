---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = ReferenceCreate(
	odata_id = "https://graph.microsoft.com/beta/users/alexd@contoso.com",
)

await graph_client.groups.by_group_id('group-id').accepted_senders.ref.post(request_body)


```