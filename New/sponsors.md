---
layout: default
title: Sponsors
description: Liste des sponsors de la LIFE
---

# Nos Sponsors

Vous trouverez sur cette page la liste de nos sponsors ainsi qu'une présentation de chacun. En cliquant sur les logos vous pourrez accéder à leurs différents sites.
N'hésitez pas à y jeter un oeil, chacun d'eux peut vous intéresser !

{% for sponsor in site.sponsors %}
## {{ sponsor.name }}

{{ sponsor.content | markdownify }}
{% endfor %}

[back](./)
