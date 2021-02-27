---
title: Tanya-Jawab Puasa
layout: default
description: halaman indeks tanya-jawab puasa
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

### Tidak ada Pertanyaan yang ditemukan?

Ajukan pertanyaan anda dengan [klik di sini](https://docs.google.com/forms/d/e/1FAIpQLSd7EzKOkw_kIod9LPxTKA7zM8uQEfGL-FBWbQOtfzH7v8xEog/viewform)

Jika sudah ditemukan jawabannya, insya Allah pertanyaan beserta jawabannya akan diposting di halaman ini.