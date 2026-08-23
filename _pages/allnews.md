---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron" style="background-color: transparent; border: none;">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}

</div>
