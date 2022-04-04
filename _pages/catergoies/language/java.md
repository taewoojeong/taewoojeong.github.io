---
layout: archive
title: JAVA
permalink: /categories/languagejava
autor_profile: true
sidebar:
  title: Posts
  nav: "sidebar-contents"
---

## - {{ site.categories.LANGUAGEJAVA | size }} 개의 포스트

{% assign posts = site.categories.LANGUAGEJAVA %}

{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
