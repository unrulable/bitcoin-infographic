---
title: Mining
layout: default
permalink: /nodes/
collection: nodes
entries_layout: grid
---
<hr/>
<div style="text-align: center;">
    {% for post in site.categories.nodes %}
    <h2>{{ post.title }}</h2>
    <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
    <br/>
    {% endfor %}
</div>