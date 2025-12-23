---
title: Journal
---

## Journal

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})**  
  <small>{{ post.date | date: "%d %B %Y" }}</small>
{% endfor %}
