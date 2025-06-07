---
layout: default
title: "Proyectos"
permalink: /proyectos/
---

# Lista de Proyectos

<ul>
  {% for proyecto in site.proyectos %}
    <li><strong>{{ proyecto.title }}</strong>: {{ proyecto.content | markdownify }}</li>
  {% endfor %}
</ul>

