---
layout: page
title: Other projects
permalink: /other
order: 3
---

<ul>
{% for ii in site.data.other_links %}
    <li><a href="{{ii.url}}">{{ii.description}}</a></li>
{% endfor %}
</ul>
