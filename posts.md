---
layout: default
title: Posts
---

## Posts

{% for post in site.posts %}

- [{{ post.title }} - {{ post.date | date: "%B %d, %Y" }}]({{ site.baseurl }}{{ post.url }})
  {% endfor %}
