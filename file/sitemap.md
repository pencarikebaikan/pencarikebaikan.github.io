---
layout: null
title: sitemap
permalink: /file/sitemap/
---

{% for post in site.posts %}
{{ site.url }}{{ post.url }}
{% endfor %}


{% for page in site.pages %}
{{ site.url }}{{ page.url }}
{% endfor %}
