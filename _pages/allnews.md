---
title: "News"
layout: textlay
excerpt: "biLAB at New York University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
<p> {{ article.text}}</p>
{% endfor %}
