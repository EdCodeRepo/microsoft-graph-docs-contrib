---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = Team(
	display_name = "My Class Team",
	description = "My Class Team’s Description",
	additional_data = {
			"template@odata_bind" : "https://graph.microsoft.com/beta/teamsTemplates('educationClass')",
	}
)

result = await graph_client.teams.post(request_body)


```