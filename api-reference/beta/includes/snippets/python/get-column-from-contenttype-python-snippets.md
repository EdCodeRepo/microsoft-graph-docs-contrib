---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)


result = await graph_client.sites.by_site_id('site-id').content_types.by_content_type_id('contentType-id').columns.by_column_definition_id('columnDefinition-id').get()


```