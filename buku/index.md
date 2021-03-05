---
title: Daftar Buku-Buku berbentuk teks
layout: default
description: halaman indeks buku-buku berupa teks
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