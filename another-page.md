---
layout: default
title: Another page
description: This is just another page
---

## Welcome to another page

{% for sponsor in site.sponsors %}
  <h2>{{ sponsor.name }} </h2>
  <p>{{ sponsor.content | markdownify }}</p>
{% endfor %}

[back](./)
