---
layout: default
title: Notes
---

## Notes

{% for post in site.categories.notes %}

- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}

{% endfor %}
