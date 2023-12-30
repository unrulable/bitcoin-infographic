---
title: Blockchain
layout: default
permalink: /gettingstarted/
collection: gettingstarted
entries_layout: grid
---
<hr/>
<div style="text-align:center;">
    {% for post in site.categories.gettingstarted %}
        <h2>{{ post.title }}</h2>
        <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
    {% endfor %}
</div>