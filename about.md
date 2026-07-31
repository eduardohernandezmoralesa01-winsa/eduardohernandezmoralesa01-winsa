---
layout: default
title: Acerca de / Bitácora de Investigación
permalink: /about/
---

# Bitácora de Investigación: Avances, Teoría y Resultados

Este es el espacio dinámico de GSRL. Aquí Eduardo Hernández-Morales publica periódicamente los avances de las simulaciones del laboratorio, el desarrollo de nueva teoría matemática, preprints y los resultados en tiempo real de los algoritmos de control.

## Entradas Recientes

{% for post in site.posts %}
<div class="post-entry">
  <div class="post-entry-date">{{ post.date | date: "%B %Y" }}</div>
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
  <a href="{{ post.url | relative_url }}">Leer artículo completo &rarr;</a>
</div>
{% endfor %}

---

> **Nota de uso:** cada vez que se actualiza el sitio, solo se agrega una nueva entrada en Markdown (`.md`) dentro de `_posts/` con la fecha, el título de la nueva teoría o avance, y el texto detallado. Ver `_posts/` en el repositorio para el formato exacto.
