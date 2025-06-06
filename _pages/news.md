---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

{% for post in site.news reversed %}
  <h3>{{ post.title }}</h3>
  <p>{{ post.date }}</p>
  {{ post.content }}
{% endfor %} 