---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = AccessPackageAssignmentRequest(
	request_type = "AdminAdd",
	access_package_assignment = AccessPackageAssignment(
		target = AccessPackageSubject(
			email = "user@contoso.com",
		),
		assignment_policy_id = "2264bf65-76ba-417b-a27d-54d291f0cbc8",
		access_package_id = "a914b616-e04e-476b-aa37-91038f0b165b",
	),
)

result = await graph_client.identity_governance.entitlement_management.access_package_assignment_requests.post(request_body)


```