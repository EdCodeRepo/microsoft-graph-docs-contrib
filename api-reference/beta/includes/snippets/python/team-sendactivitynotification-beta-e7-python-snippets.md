---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = SendActivityNotificationPostRequestBody(
	topic = TeamworkActivityTopic(
		source = TeamworkActivityTopicSource.EntityUrl,
		value = "https://graph.microsoft.com/beta/teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}",
	),
	activity_type = "reservationStatusUpdated",
	preview_text = ItemBody(
		content = "You have moved up the queue",
	),
	recipient = AadUserNotificationRecipient(
		odata_type = "microsoft.graph.aadUserNotificationRecipient",
		user_id = "jacob@contoso.com",
	),
	template_parameters = [
		KeyValuePair(
			name = "reservationId",
			value = "TREEE433",
		),
		KeyValuePair(
			name = "currentSlot",
			value = "23",
		),
	],
)

await graph_client.teams.by_team_id('team-id').send_activity_notification.post(request_body)


```