---
layout: default
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
  <h2><a href="{{ project.url | relative_url }}"> {{ project.title | escape }} </a></h2>
  <p>{{ project.description }}</p>
{% endfor %}