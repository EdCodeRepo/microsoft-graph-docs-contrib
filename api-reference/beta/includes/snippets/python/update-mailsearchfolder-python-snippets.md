---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = MailSearchFolder(
	odata_type = "microsoft.graph.mailSearchFolder",
	filter_query = "contains(subject, 'Analytics')",
)

result = await graph_client.me.mail_folders.by_mail_folder_id('mailFolder-id').patch(request_body)


```