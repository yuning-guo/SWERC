---
title: "News"
layout: textlay
excerpt: "Solar & W. Env. Research Center - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}}
{% endfor %}
