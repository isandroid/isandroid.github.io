---
title: Beranda
layout: default
---

Selamat datang di pustaka daring pribadi milik Isa Mujahid Islam. Situs ini dibuat sebagai tempat untuk mengumpulkan bahan-bahan rujukan pribadi. Walaupun begitu, siapapun yang ingin mengambil manfaat dari situs ini, saya persilakan.

Situs ini masih terus dalam pengembangan. Masih banyak kekurangan dimana-mana. Saya secara pribadi menerima masukan yang membangun demi sempurnanya situs ini.

### Menu Istimewa

- [Islam](/islam/)

- [Referensi Internal](/ref/)

- [Buku-Buku](/buku/)

- [Tag-tag Blog](/tag)

- [Artikel-artikel Puasa](/puasa)

- [Tanya-Jawab Puasa](/tanya-jawab/puasa/)

### Blog

<ul>
  {% assign sorted = site.posts | sort: 'title' %}
  {% for post in sorted %}
    <li class="spasi">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>