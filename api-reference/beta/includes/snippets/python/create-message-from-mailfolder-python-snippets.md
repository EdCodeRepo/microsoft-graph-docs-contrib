---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = Message(
	received_date_time = "2016-10-19T10:37:00Z",
	sent_date_time = "2016-10-19T10:37:00Z",
	has_attachments = True,
	subject = "subject-value",
	body = ItemBody(
		content_type = BodyType.Text,
		content = "content-value",
	),
	body_preview = "bodyPreview-value",
)

result = await graph_client.me.mail_folders.by_mail_folder_id('mailFolder-id').messages.post(request_body)


```