---
layout: default
title: Oscar's Blog Posts
---
# {{ page.title }}
{% for post in site.posts %}
- {{ post.date }} >> <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
