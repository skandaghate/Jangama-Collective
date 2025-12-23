---
title: Performances
---

## Performances

{% for post in site.posts %}
{% if post.category == "performance" %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%Y" }}
{% endif %}
{% endfor %}
