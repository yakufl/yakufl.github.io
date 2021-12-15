---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

My research interests lie in understanding the welfare effects of public policy programs. I am particularly interested in examining health and socio-economic inequalities. My research combines rigorous economic theory, applied econometrics, rich micro data and large-scale simulations to answer important questions at the intersection of public policy and population health.

My other main research agenda focuses on early childhood development, parental investments, and household bargaining decisions in both developed and developing economies. In a new avenue of research, I leverage social media data to explore the effects of daylight savings times on expressed sentiment.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
