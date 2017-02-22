---
title: Aktuelle Golfreisen
---

{% if site.construction %}

Hier entsteht eine neue Internetpräsenz

{% else %}

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}

{% endif %}
