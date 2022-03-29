---
layout: archive
title: Web
permalink: /categories/web
autor_profile: true
sidebar:
  title: Posts
  nav: "sidebar-contents"
---

## <h2> - {{ site.categories.WEB | size }} 개의 포스트 </h2>

{% assign posts = site.categories.BOJ %}

{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
