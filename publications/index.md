---
layout: default
title: Publications
nav: publications
hero_kicker: Research Output
hero_title: Publications
---

## Publications

{% assign publications = site.data.publications | sort: "order" %}
{% for pub in publications %}
  {% include publication-card.html pub=pub %}
{% endfor %}
