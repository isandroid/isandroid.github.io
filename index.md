---
title: Beranda
layout: default
---

Selamat datang di pustaka pribadi milik Isa Mujahid Islam. Semoga bisa memberikan manfaat untuk kita semua.

### Menu Istimewa

- [Islam](/islam)

- [Referensi](/ref)

- [Tag-tag Blog](/tag)

- [Tanya-Jawab Puasa](/tanya-jawab/puasa)

### Blog

<ul>
  {% assign sorted = site.posts | sort: 'title' %}
  {% for post in sorted %}
    <li class="spasi">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>