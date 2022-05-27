---
layout: page
title: UFES - CCENS - Disciplinas
permalink: /ufes
order: 3
---

<ul>
{% for ii in site.data.ufes %}
    <li><a href="{{ii.url}}">{{ii.disciplina}}</a></li>
{% endfor %}
</ul>
