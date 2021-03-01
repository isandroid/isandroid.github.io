---
title: Tanya-Jawab Puasa
layout: default
description: halaman tanya-jawab hal-hal tentang puasa
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

### Tidak Menemukan Pertanyaan yang cocok?

Ajukan pertanyaan anda dengan [klik di sini](https://docs.google.com/forms/d/e/1FAIpQLSd7EzKOkw_kIod9LPxTKA7zM8uQEfGL-FBWbQOtfzH7v8xEog/viewform)

Jika sudah ditemukan jawabannya, insya Allah pertanyaan beserta jawabannya akan diposting di halaman ini.