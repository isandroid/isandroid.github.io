---
title: Islam
layout: default
description: halaman indeks
---

## {{ page.title }}

{% assign pages = site.pages | sort: 'title' %}

<ul>
    {% for item in pages %}
        {% if item.dir == page.dir and item.path != page.path %}
           <li class="spasi"><a href="{{ item.url }}">{{ item.title }}</a></li>
        {% endif %}
   {% endfor %}
</ul>