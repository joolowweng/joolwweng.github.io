---
layout: default
---

![avatar](assets/images/avatar.png)

# Joolowweng

Pythonista | BA Math at [OSU](https://www.threads.net/@theohiostateuniversity) | Make Coding Great Again

{% if site.posts.size > 0 %}

## [{{ site.posts.first.title }}]({{ site.posts.first.url | relative_url }})

{{ site.posts.first.categories | first | capitalize }} - {{ site.posts.first.date | date: "%B %d, %Y" }}

{{ site.posts.first.excerpt | markdownify }}
[Read more]({{ site.posts.first.url | relative_url }})

{% if site.posts.size > 1 %}

{% for post in site.posts limit: 5 %}
{% if post != site.posts.first %}

## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.categories | first | capitalize }} - {{ post.date | date: "%B %d, %Y" }}

{% endif %}
{% endfor %}

{% endif %}
{% endif %}
