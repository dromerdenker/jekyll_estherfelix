---
title: "posts RAO"
layout: page
---
{% for post in site.posts %}
    {% if post.path contains "RAO" %}
- [{{ post.title }} post]({{ post.url }})  {{post.date | date_to_string}}
    {% endif %}
{% endfor %}