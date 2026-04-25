---
layout: default
title: Publications
nav: publications
hero_kicker: Research Output
hero_title: Publications
hero_text: This page displays the full publication list in the specified order. Home page display can be controlled separately in _data/publications.yml.
---

## Publications

{% assign publications = site.data.publications | sort: "order" %}
{% for pub in publications %}
  {% include publication-card.html pub=pub %}
{% endfor %}
