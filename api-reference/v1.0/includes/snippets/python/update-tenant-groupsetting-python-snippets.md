---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = GroupSetting(
	values = [
		SettingValue(
			name = "AllowToAddGuests",
			value = "false",
		),
	],
)

result = await graph_client.group_settings.by_group_setting_id('groupSetting-id').patch(request_body)


```