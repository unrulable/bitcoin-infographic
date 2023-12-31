---
title: Transactions
layout: default
permalink: /transactions/
collection: transactions
entries_layout: grid
---
<hr/>
<div style="text-align:center;">
    {% for post in site.categories.transactions %}
        <h2>{{ post.title }}</h2>
        <a href="{{ post.url }}"><img src="{{ post.thumbnailImage }}"/></a>
    {% endfor %}
</div>