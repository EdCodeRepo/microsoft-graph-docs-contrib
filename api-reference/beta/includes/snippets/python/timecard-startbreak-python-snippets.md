---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = StartBreakPostRequestBody(
	notes = ItemBody(
		content_type = BodyType.Text,
		content = "start break smaple notes",
	),
	additional_data = {
			"at_aproved_location" : True,
	}
)

result = await graph_client.teams.by_team_id('team-id').schedule.time_cards.by_time_card_id('timeCard-id').start_break.post(request_body)


```