---
title: Quran-um-Majid
layout: default
description: teks alquran, terjemahan dan tafsir
---

## {{ page.title }}

### Peringatan

Proyek ini sedang dikerjakan bertahap, masih dalam tahap pembangunan

{% assign pages = site.pages | sort: 'title' %}

### Daftar Surat

<ul>
    {% for item in pages %}
        {% if item.dir == page.dir and item.path != page.path %}
           <li class="spasi"><a href="{{ item.url }}">{{ item.title }}</a></li>
        {% endif %}
   {% endfor %}
</ul>