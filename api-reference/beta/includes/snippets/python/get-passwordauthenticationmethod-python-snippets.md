---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)


result = await graph_client.me.authentication.password_methods.by_password_authentication_method_id('passwordAuthenticationMethod-id').get()


```