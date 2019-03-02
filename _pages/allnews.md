---
layout: textlay
title: Noticias
excerpt: Noticias - Rayolab @ Universidad de Chile
sitemap: false
---
# Noticias

{% for article in site.data.news %}

<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
