---
layout: single
title: "Posts"
permalink: /posts/
author_profile: true
---

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
  <p>{{ post.excerpt }}</p>
  <hr>
{% endfor %}
