---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = Custodian(
	email = "AdeleV@contoso.com",
	apply_hold_to_sources = True,
)

result = await graph_client.compliance.ediscovery.cases.by_case_id('case-id').custodians.post(request_body)


```