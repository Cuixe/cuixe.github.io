---
layout: default
title: Coding for the life
---
{{ site.url }}
{% for post in site.posts %}
    [{{ post.date | date_to_string }} - {{post.title}}]({{ post.url }}) 
{% endfor %}
