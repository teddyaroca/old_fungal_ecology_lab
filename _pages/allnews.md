---
title: "Fungal Ecology Lab - News"
layout: textlay
excerpt: "Fungal Ecology Lab at UNL."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
