---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = DecisionsRequestBuilder.DecisionsRequestBuilderGetQueryParameters(
		expand = ["insights"],
)

request_configuration = DecisionsRequestBuilder.DecisionsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.acce_reviews.definitions.by_definition_id('accessReviewScheduleDefinition-id').instances.by_instance_id('accessReviewInstance-id').decisions.get(request_configuration = request_configuration)


```