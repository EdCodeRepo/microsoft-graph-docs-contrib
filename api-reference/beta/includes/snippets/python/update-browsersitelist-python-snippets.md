---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = BrowserSiteList(
	display_name = "Production Site List A",
	description = "Production site list for team A",
)

result = await graph_client.admin.edge.internet_explorer_mode.site_lists.by_browser_site_list_id('browserSiteList-id').patch(request_body)


```