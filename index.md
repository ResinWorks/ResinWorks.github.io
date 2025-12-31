---
layout: default
title: Home
---

# Welcome

てすと１

## recent

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## works

準備中...

## リンク

- https://resinworks.github.io/
