---
title: Résultats
---

## Tournoi de qualification 1

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2023.resultats_q1 %}
        {% if forloop.first %}
        <tr>
        {% for pair in row %}
            <th>{{ pair[0] }}</th>
        {% endfor %}
        </tr>
        {% endif %}

        {% tablerow pair in row %}
        {{ pair[1] }}
        {% endtablerow %}
    {% endfor %}
    </table>
</div>

*NB: Certains joueurs ayant rencontré des bugs de connexion, ils ont pu obtenir 0.5pt en compensation.*

## Tournoi de qualification 2

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2023.resultats_q2 %}
        {% if forloop.first %}
        <tr>
        {% for pair in row %}
            <th>{{ pair[0] }}</th>
        {% endfor %}
        </tr>
        {% endif %}

        {% tablerow pair in row %}
        {{ pair[1] }}
        {% endtablerow %}
    {% endfor %}
    </table>
</div>

*NB: Pour départager l'EFREI et l'INSA Strasbourg à la seconde place, nous avons appliqué le point 2.3 du règlement "En cas d’égalité entre 2 équipes, l’équipe qualifiée serait celle dont la somme des places des 4 premiers joueurs est la plus faible."*
