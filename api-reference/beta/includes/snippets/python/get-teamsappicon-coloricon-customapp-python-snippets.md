---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)


result = await graph_client.app_catalogs.teams_apps.by_teams_app_id('teamsApp-id').app_definitions.by_teams_app_definition_id('teamsAppDefinition-id').color_icon.get()


```