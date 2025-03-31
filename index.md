---
layout: default
---

![avatar](assets/images/avatar.jpeg)

# Joolowweng

Pythonista | BA Math at [OSU](https://www.threads.net/@theohiostateuniversity) | Make Code Great Again

{% if site.posts.size > 0 %}

## [{{ site.posts.first.title }}]({{ site.posts.first.url | relative_url }})

{{ site.posts.first.date | date: "%B %d, %Y" }}

{{ site.posts.first.excerpt | markdownify }}
[Read more]({{ site.posts.first.url | relative_url }})

{% endif %}
