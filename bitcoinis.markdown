---
title: Bitcoin Is...
layout: default
permalink: /bitcoinis/
collection: bitcoinis
entries_layout: grid
---

<h1>Bitcoin is...</h1>
{% for post in site.categories.bitcoinis %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}