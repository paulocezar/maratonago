---
layout: minimal
title: Arquivo
permalink: /arquivo/
---

## Postagens Antigas

{% for post in site.posts %}
  * {{ post.date | date: "%Y/%m/%d" }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
