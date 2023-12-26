---
title: Blockchain
layout: default
permalink: /blockchain/
collection: blockchain
entries_layout: grid
---

<h1>Pictures Related to the Bitcoin Blockchain</h1>

<hr/>
{% for post in site.categories.blockchain %}
  <h2>{{ post.title }}</h2>
  <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
{% endfor %}