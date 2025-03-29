---
layout: default
title: Home
---

# Welcome to My Website

This is a GitHub Pages site using Jekyll with my custom markdown CSS styling.

## Recent Posts

{% for post in site.posts limit:5 %}

- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}

![avatar](assets/avatar.jpeg)

> Make Programming Great Again
