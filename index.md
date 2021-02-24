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
  {% for post in site.posts %}
    <li class="spasi">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>