---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = UpgradePostRequestBody(
	consented_permission_set = TeamsAppPermissionSet(
		resource_specific_permissions = [
			TeamsAppResourceSpecificPermission(
				permission_value = "Channel.Create.Group",
				permission_type = TeamsAppResourceSpecificPermissionType.Application,
			),
			TeamsAppResourceSpecificPermission(
				permission_value = "ChannelMeeting.ReadBasic.Group",
				permission_type = TeamsAppResourceSpecificPermissionType.Delegated,
			),
		],
	),
)

await graph_client.teams.by_team_id('team-id').installed_apps.by_teams_app_installation_id('teamsAppInstallation-id').upgrade.post(request_body)


```