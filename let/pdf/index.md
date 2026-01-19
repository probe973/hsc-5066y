---
layout: default
title: PDFs
---

<ul>
{% assign docs = site.static_files | where: "path", "assets/pdf" %}
{% for file in site.static_files %}
  {% if file.path contains '/pdf/' %}
    <li><a href="{{ file.path | relative_url }}">{{ file.name }}</a></li>
  {% endif %}
{% endfor %}
</ul>
