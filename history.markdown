---
title: Bitcoin History
layout: default
permalink: /history/
collection: history
entries_layout: grid
---
<h1>Pictures Related to Bitcoin History</h1>

<hr/>
{% for post in site.categories.history %}
  <h2>{{ post.title }}</h2>
  <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
{% endfor %}