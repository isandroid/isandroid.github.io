---
title: Tag-tag
layout: default
---

## Tag-Tag Blog

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ol>
    {% for post in tag[1] %}
      <li class="spasi"><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ol>
{% endfor %}

### Artikel Istimewa

<i class="fa fa-money" aria-hidden="true"></i> [Utang](/utang)

<i class="fa fa-users" aria-hidden="true"></i> [Pardah](/islam/pardah)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NzE3NzMzMjddfQ==
-->