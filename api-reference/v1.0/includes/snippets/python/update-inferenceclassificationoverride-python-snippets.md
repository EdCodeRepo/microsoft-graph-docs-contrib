---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = InferenceClassificationOverride(
	classify_as = InferenceClassificationType.Focused,
)

result = await graph_client.me.inference_classification.overrides.by_inference_classification_override_id('inferenceClassificationOverride-id').patch(request_body)


```