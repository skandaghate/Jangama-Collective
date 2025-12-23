---
title: Home
---

## We are Jangama.

A theatre collective rooted in movement, memory, and resistance.  
We work with bodies, space, and silence.

---

### Current Work

{% for post in site.posts limit:3 %}
- **[{{ post.title }}]({{ post.url }})**  
  {{ post.excerpt | strip_html | truncate: 120 }}
{% endfor %}

---

### Journal

Fragments. Notes. Rehearsal thoughts.  
[Read more →](/journal)
