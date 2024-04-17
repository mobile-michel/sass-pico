---
title: Version colors
date: 2023-11-01
layout: colors
tags: primary
css: /assets/css/colors/colors.css
---
<ul>
 {% for items in collections.colors reversed %}
 <li><a href="{{ items.url | url }}">{{ items.data.title }}</a>: {{ items.data.description }}</li>
 {% endfor %}
</ul>