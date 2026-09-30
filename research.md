---
layout: page
title: Research
ornament: corner-research.svg
ornament_corners: [top-left]
permalink: /research/
---
{% assign sections = "conference:Conference Publications,journal:Journal Publications,manuscript:Manuscripts" | split: "," %}
{% for s in sections %}
  {% assign parts = s | split: ":" %}
  {% assign pubs = site.data.publications | where: "type", parts[0] %}
  {% if pubs.size > 0 %}
<h2>{{ parts[1] }}</h2>
<ul class="pubs">
  {% for pub in pubs %}
    {% include publication.html %}
  {% endfor %}
</ul>
  {% endif %}
{% endfor %}
