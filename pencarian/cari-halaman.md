---
title: Pencarian dalam Halaman Pustaka
layout: pencarian
permalink: /cari-halaman
published: false
---

## {{ page.title }}

<form action="{{ page.permalink }}" method="get">
  <label for="search-box">Search</label>
  <input type="text" id="search-box" name="query">
  <input type="submit" value="search">
</form>

<p>&nbsp;</p>

<ul id="search-results"></ul>

<script>
  window.store = {
    {% for page in site.pages %}
      "{{ page.url | slugify }}": {
        "title": "{{ page.title | xml_escape }}",
        "content": {{ page.content | strip_html | strip_newlines | jsonify }},
        "url": "{{ page.url | xml_escape }}"
      }
      {% unless forloop.last %},{% endunless %}
    {% endfor %}
  };
</script>
<script src="/assets/js/lunr.min.js"></script>
<script src="/assets/js/search.js"></script>
