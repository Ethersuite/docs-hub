---
description: Use the following endpoints to manage Custom Domains.
---

# Custom Domains

#### Fetch custom domains

{% swagger src="../hub-api.yml" path="/v1/custom-domains" method="get" expanded="true" %}
[hub-api.yml](../hub-api.yml)
{% endswagger %}

#### Get a custom domain's details

{% swagger src="../hub-api.yml" path="/v1/custom-domains/{id}" method="get" expanded="true" %}
[hub-api.yml](../hub-api.yml)
{% endswagger %}

#### Add a custom domain

{% swagger src="../hub-api.yml" path="/v1/custom-domains" method="post" expanded="true" %}
[hub-api.yml](../hub-api.yml)
{% endswagger %}

#### Obtain DNS setup instruction

{% swagger src="../hub-api.yml" path="/v1/custom-domains/{id}/instructions" method="get" expanded="true" %}
[hub-api.yml](../hub-api.yml)
{% endswagger %}

#### Attempt domain verification

{% swagger src="../hub-api.yml" path="/v1/custom-domains/{id}/verify" method="get" expanded="true" %}
[hub-api.yml](../hub-api.yml)
{% endswagger %}

#### Delete a custom domain

{% swagger src="../hub-api.yml" path="/v1/custom-domains" method="delete" expanded="true" %}
[hub-api.yml](../hub-api.yml)
{% endswagger %}
