---
title: List of pages
layout: colors
tags: primary
---
<ul>
 {% for items in collections.colors reversed %}
 <li><a href="{{ items.url }}">{{ items.data.title }}</a>: {{ items.data.description }}</li>
 {% endfor %}
</ul>