---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = Group(
	display_name = "myGroup",
)

result = await graph_client.sites.by_site_id('site-id').term_store.groups.post(request_body)


```