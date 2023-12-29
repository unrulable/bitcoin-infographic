---
title: Blockchain
layout: default
permalink: /blockchain/
collection: blockchain
entries_layout: grid
---
<hr/>
<div style="text-align: center;">
  {% for post in site.categories.blockchain %}
    <h2>{{ post.title }}</h2>
    <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
  {% endfor %}
</div>
