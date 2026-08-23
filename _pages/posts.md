---
title: Posts
layout: gridlay
sitemap: false
permalink: /Posts/
---

# Posts

Research notes, field experiences, coding, seismology, and other things I find interesting.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

{% endfor %}
