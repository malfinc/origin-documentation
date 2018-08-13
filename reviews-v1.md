---
description: Last updated 2018-08-13T01:43:27-07:00
---

# Reviews v1

{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/reviews" %}
  {% api-method-summary %}
    index
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.690+00:00">2018-08-13T08:43:27.690+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="POST" host="https://origin.poutineer.com" path="/v1/reviews" %}
  {% api-method-summary %}
    create
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.693+00:00">2018-08-13T08:43:27.693+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="GET" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    show
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.696+00:00">2018-08-13T08:43:27.696+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="PATCH" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.699+00:00">2018-08-13T08:43:27.699+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="PUT" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    update
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.702+00:00">2018-08-13T08:43:27.702+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Content-Type" type="string" required=true %}
        `application/vnd.api+json`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}
  {% endapi-method-response %}
{% endapi-method %}
{% api-method method="DELETE" host="https://origin.poutineer.com" path="/v1/reviews/{id}" %}
  {% api-method-summary %}
    destroy
  {% endapi-method-summary %}

  {% api-method-description %}
    *Last updated <time time="2018-08-13T08:43:27.705+00:00">2018-08-13T08:43:27.705+00:00</time>*.
  {% endapi-method-description %}

  {% api-method-request %
    {% api-method-headers %}
      {% api-method-parameter name="If-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-None-Match" type="Etag" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-None-Match)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Modified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Modified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="If-Unmodified-Since" type="HTTP-date" required=false %}
        [Mozilla Documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/If-Unmodified-Since)
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

    {% api-method-headers %}
      {% api-method-parameter name="Accept" type="string" required=true %}
        `application/vnd.api+json` OR `*/*`
      {% endapi-method-parameter %}
    {% endapi-method-headers %}

  {% endapi-method-response %}
{% endapi-method %}