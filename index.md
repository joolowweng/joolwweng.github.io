---
layout: default
---

![avatar](assets/images/avatar.jpeg)

#

{% if site.posts.size > 0 %}

## [{{ site.posts.first.title }}]({{ site.posts.first.url | relative_url }})

{{ site.posts.first.date | date: "%B %d, %Y" }}

{{ site.posts.first.excerpt | markdownify | strip_html | truncatewords: 100 }}

{% endif %}
