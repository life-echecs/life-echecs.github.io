---
title: Résultats
---

Les résultats des différents tournois seront mis à jour au fur et à mesure.

## Résultats des phases de qualification

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2024.resultats_qualifs %}
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

## Tournoi de qualification 1

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2024.resultats_q1 %}
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
    {% for row in site.data.tournaments.2024.resultats_q2 %}
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

<!-- ## Tournoi de qualification 3

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2024.resultats_q3 %}
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

## Tournoi de qualification 4

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2024.resultats_q4 %}
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
</div> -->
