---
title: Beranda
layout: default
---

### Pencarian di Pustaka

- [Pencarian](/cari)

### Menu Istimewa

- [Quran-um-Majid](/quran/) (Dalam proses)

- [Islam](/islam/)

- [Referensi Internal](/ref/)

- [Buku-Buku](/buku/)

- [Tag-tag Blog](/tag)

- [Hal-Hal tentang Puasa](/puasa) (Dalam proses)

- [Tanya-Jawab tentang Puasa](/tanya-jawab/puasa/)

- [Utang](/utang)

- [Pardah](/islam/pardah)

<!--
### Blog

<ul>
  {% assign sorted = site.posts | sort: 'title' %}
  {% for post in sorted %}
    <li class="spasi">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
-->

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