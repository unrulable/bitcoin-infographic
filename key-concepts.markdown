---
title: Key Concepts
layout: default
permalink: /keyconcepts/
collection: keyconcepts
entries_layout: grid
---
<hr/>
<div style="text-align:center;">
    {% for post in site.categories.keyconcepts %}
        <h2>{{ post.title }}</h2>
        <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
    {% endfor %}
</div>