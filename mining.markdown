---
title: Mining
layout: default
permalink: /mining/
collection: mining
entries_layout: grid
---
<hr/>
<div style="text-align: center;">
    {% for post in site.categories.mining %}
    <h2>{{ post.title }}</h2>
    <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
    <br/>
    {% endfor %}
</div>