---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)


result = await graph_client.identity_governance.lifecycle_workflows.workflows.by_workflow_id('workflow-id').task_reports.by_task_report_id('taskReport-id').get()


```