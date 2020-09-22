---
layout: default
title: RayoLab - Libros
excerpt: Libros - RayoLab @ Universidad de Chile
sitemap: true
permalink: /libros
---
# Libros y Capítulos

{% for publi in site.data.publications.libros %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}