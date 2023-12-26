---
title: Bitcoin Is...
layout: default
permalink: /bitcoinis/
collection: bitcoinis
entries_layout: grid
---

<h1>Bitcoin is...</h1>

<hr/>
{% for post in site.categories.bitcoinis %}
  <h2>{{ post.title }}</h2>
  <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
{% endfor %}