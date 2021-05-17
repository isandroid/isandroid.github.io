---
title: Beranda
layout: beranda
---

### Pencarian Internal Pustaka

<i class="fa fa-search" aria-hidden="true"></i> [Pencarian (didukung oleh Google)](/cari)
{% comment %}
<i class="fa fa-search" aria-hidden="true"></i> [Pencarian dalam artikel Blog](/cari-blog)

<i class="fa fa-search" aria-hidden="true"></i> [Pencarian dalam Halaman](/cari-halaman)
{% endcomment %}

### Artikel Unggulan

<i class="fa fa-thumbs-up" aria-hidden="true"></i> [<mark>Puasa Syawal</mark>](/2021/05/14/puasa-syawal.html)

<i class="fa fa-thumbs-up" aria-hidden="true"></i> [<mark>Khalifah Islam (Ahmadiyah) Saat Ini</mark>](/2021/04/03/khalifah-islam-saat-ini.html)

<i class="fa fa-thumbs-up" aria-hidden="true"></i> [<mark>Pernyataan Khalifah Islam Ahmadiyah  tentang Palestina dan Israel</mark>](/2021/05/17/pernyataan-khalifah-islam-ahmadiyah-saat-ini-tentang-palestina-israel.html)

{% comment %}

- [Tata Cara Shalat Id](/2021/05/01/shalat-hari-raya.html)

{% endcomment %}

### Menu Istimewa

<i class="fa fa-book" aria-hidden="true"></i> [Quran-um-Majid](/quran/) (Dalam proses)

<i class="fa fa-moon-o" aria-hidden="true"></i> [Islam](/islam/)

<i class="fa fa-flag-o" aria-hidden="true"></i> [Puasa](/puasa)

<i class="fa fa-bookmark" aria-hidden="true"></i> [Referensi Internal](/ref/)

<i class="fa fa-book" aria-hidden="true"></i> [Buku-Buku](/buku/)

<i class="fa fa-tags" aria-hidden="true"></i> [Tag-tag Blog](/tag)

<i class="fa fa-question-circle" aria-hidden="true"></i> [Tanya-Jawab tentang Puasa](/tanya-jawab/puasa/)

{% comment %}
### Hitungan Mundur Bulan Ramadhan (perkiraan)

<!-- Display the countdown timer in an element -->
<h4 id="ramadhan" style="color:green;"></h4>

Keterangan: 

- Waktu diatas adalah perhitungan qomariyah 1 Ramadhan 1442 H 
- Waktu terbenam matahari (Maghrib) di Jakarta
- Malam harinya memulai ibadah shalat Tarawih
- Keesokan harinya (setelah fajar) dilaksanakan ibadah puasa.

<script>
// Set the date we're counting down to
var countDownDate = new Date("Apr 12, 2021 17:56:01").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="ramadhan"
  document.getElementById("ramadhan").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("ramadhan").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

### Artikel tentang Puasa

{% for tag in site.tags %}
{% if tag contains "puasa" %}
  <ul>
    {% assign sorted2 = tag[1] | sort: 'title' %}
    {% for post in sorted2 %}
      <li class="spasi"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}
{% endcomment %}