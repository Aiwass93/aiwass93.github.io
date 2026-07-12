---
layout: default
title: Links
lang: en
---
<h1>Links</h1>
{% for section in site.data.links %}<section>
<h2>{{ section.title | escape }}</h2>
{% for link in section.links %}<p>{{ link.name | escape }}: <a href="{{ link.url | escape }}">{{ link.label | escape }}</a>{% if link.description %}<br>
{{ link.description | escape }}{% endif %}</p>{% endfor %}
</section>{% endfor %}
<p><a href="/">back</a></p>
