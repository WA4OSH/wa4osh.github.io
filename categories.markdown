---
layout: page
title: Categories
permalink: /categories/
---

## HAM Radio

Projects, field reports, and technical notes on amateur radio operations,
ARES/EMCOMM, LoRa-APRS, and microwave.

{% for post in site.posts %}
{% if post.categories contains 'ham-radio' %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endif %}
{% endfor %}

---

## AI Partnership

Notes on AI-assisted systems engineering, GoBox build log, and excerpts from
the AI Partnership Handbook in progress.

{% for post in site.posts %}
{% if post.categories contains 'ai-partnership' %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endif %}
{% endfor %}

---

## GoBox Build Log

{% for post in site.posts %}
{% if post.categories contains 'gobox' %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endif %}
{% endfor %}
