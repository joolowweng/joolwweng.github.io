---
layout: default
title: Journal
---

## Journal

{% for post in site.categories['journal'] %}

- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}

{% endfor %}
