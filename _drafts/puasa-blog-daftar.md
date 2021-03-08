### Serial Ceramah Puasa

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
