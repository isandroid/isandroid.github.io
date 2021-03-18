---
title: Shalat
layout: default
description: penjelasan tentang shalat
---

## {{page.title}}

Shalat berasal dari bahasa arab, yaitu dari kata (صَلَّى - يُصَلِّي) yang berarti berdoa, meminta rahmat (Allah), menjelaskan dan terpisah [[^almmany_sholla]]

[^almmany_sholla]: [Kamus Almaany kata _shollaa_](https://www.almaany.com/id/dict/ar-id/%D8%B5%D9%84%D9%91%D9%89/)

### Artikel Shalat

{% for tag in site.tags %}
{% if tag contains "shalat" %}
  <ul>
  	{% assign sorted2 = tag[1] | sort: 'title' %}
    {% for post in sorted2 %}
      <li class="spasi"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}

### Planing

#### Dasar 
	
- Perintah Shalat

- Meninggalkan shalat

- Hikmah Shalat

- Shalat Berjamaah

	- Imam Shalat

	- Makmum

	- Shaf Shalat

- Shalat di Rumah

#### Bersuci

- Wudhu

- Tayammum

- Mandi

- Istinja

#### Pra Shalat

- Syarat Wajib

- Syarat Sah

- Azan

- Iqomat

- (menutup aurat)

- (Kesucian Tempat Shalat)

- (Mengenal Waktu Shalat)

- (Menghadap Qiblat)

- Waktu-waktu Shalat

- Waktu-waktu Terlarang Shalat

- Tempat terlarang Shalat

- Doa masuk Masjid

- Menunggu Shalat di Masjid

- Tawajjuh

#### Shalat

##### Rukun Shalat

- Niat

- Takbiratul Ihrom

- Membaca Alfatihah

- Rukuk

- I'tidal

- Sujud

- Duduk diantara Dua Sujud

- Tahiyat

	- Tahiyat Awal

	- Tahiyat Akhir

- Salam

##### Macam-Macam Shalat

- Shalat Fardhu

- Shalat Jum’at

- Shalat Jenazah

- [Shalat Tahajud](/shalat/tahajud)

- [Shalat Witir](/shalat/witir)

- Shalat Tarawih

- Shalat Hari Raya

- Shalat Gerhana

- Shalat Hari Raya

- Shalat Rawatib

- Shalat Jenazah

- Shalat Musafir

	- Shalat di Kendaraan

	- Shalat sambil Berjalan

	- Shalat Jamak

	- Shalat Jamak-Qoshor

- Shalat Hajat

- Shalat Tasbih

- Shalat Istikharah

- Shalat Dhuha

- Shalat Khauf

- Shalat Istisqa

##### Pasca Shalat

- Dzikir

- Doa

- Doa keluar Masjid

- Hal Lainnya

- Qunut

- Sujud Sahwi

- Sujud Tilawah

- Sujud Syukur

- Memakai Sandal

- Memakai Kaos Kaki

- Memberi Isyarat ketika Shalat

- Gerakan-gerakan lain dalam Shalat

- Tanda-tanda orang Munafik Shalat

- Meludah dan Membuang Ingus

- Shalat ketika Sakit

- Lewat di Depan orang Shalat

- Membaca doa dalam bahasa sendiri

- Larangan membaca doa dari Alquran

- Terlambat Shalat

	- Sengaja melambatkan diri ke Masjid

	- Keadaan tetap mendapatkan satu Rakaat


### Catatan kaki