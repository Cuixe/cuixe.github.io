---
layout: default
title: Coding for the life
---

{% for post in site.posts %}
    [{{ post.date | date_to_string }} - {{post.title}}]({{ post.url }}) 
{% endfor %}