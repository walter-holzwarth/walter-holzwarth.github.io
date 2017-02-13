---
index: true
---

# Herzlich Wilkommen

{% if site.construction %}

Hier entsteht eine neue Internetpräsenz

{% elsif site.maintainance %}

Hier wird gerade gearbeitet - bitte kommen Sie später nochmal vorbei!

{% else %}

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}

{% endif %}
