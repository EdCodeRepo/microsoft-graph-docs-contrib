---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = ItemRetentionLabel(
	retention_settings = RetentionLabelSettings(
		is_record_locked = True,
	),
)

result = await graph_client.drives.by_drive_id('drive-id').items.by_drive_item_id('driveItem-id').retention_label.patch(request_body)


```