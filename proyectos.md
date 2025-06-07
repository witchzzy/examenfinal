---
layout: default
title: "Proyectos"
permalink: /proyectos/
---

# Lista de Proyectos

<ul>
  {% for proyecto in site.proyectos %}
    <li>
      <a href="{{ proyecto.url }}">{{ proyecto.title }}</a>
    </li>
  {% endfor %}
</ul>

