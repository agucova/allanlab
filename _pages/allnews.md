---
layout: textlay
title: Noticias
excerpt: Noticias - Rayolab @ Universidad de Chile
sitemap: false
permalink: /noticias.html
---
# Noticias

{% for article in site.data.news.entradas %}

<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
