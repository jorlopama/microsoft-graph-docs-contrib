---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = HealthOverviewsRequestBuilder.HealthOverviewsRequestBuilderGetQueryParameters(
		expand = ["issues"],
)

request_configuration = HealthOverviewsRequestBuilder.HealthOverviewsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.admin.service_announcement.health_overviews.get(request_configuration = request_configuration)


```