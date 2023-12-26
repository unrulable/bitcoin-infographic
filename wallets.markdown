---
title: Bitcoin Wallets
layout: default
permalink: /wallets/
collection: wallets
entries_layout: grid
---
<h1>Pictures Related to the Bitcoin Wallets</h1>

<hr/>
{% for post in site.categories.wallets %}
  <h2>{{ post.title }}</h2>
  <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
{% endfor %}