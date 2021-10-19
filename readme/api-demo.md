# Api Demo

{% swagger method="get" path="/users" baseUrl="/api" summary="Opis get " %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" required="true" name="id" type="String" %}
opis parametra
{% endswagger-parameter %}

{% swagger-parameter in="path" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="title" type="String" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="response ok" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="post" path="/users" baseUrl="" summary="Opis post " %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="id" type="String" %}
opis
{% endswagger-parameter %}

{% swagger-parameter in="cookie" %}

{% endswagger-parameter %}
{% endswagger %}

{% swagger method="put" path="" baseUrl="" summary="Opis put" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}
