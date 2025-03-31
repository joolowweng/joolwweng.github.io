---
layout: default
title: Journal
---

## Journal

{% for post in site.posts %}
{% if post.category == "journal" %}

- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}

{% endif %}
{% endfor %}
