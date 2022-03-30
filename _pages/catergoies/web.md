---
layout: archive
title: Web
permalink: /categories/web
autor_profile: true
sidebar:
  title: Posts
  nav: "sidebar-contents"
---

## - {{ site.categories.WEB | size }} 개의 포스트

{% assign posts = site.categories.WEB %}

{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
