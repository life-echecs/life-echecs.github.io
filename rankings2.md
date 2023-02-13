---
title: Table test
---

<div class="table-container">
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
    {% for row in site.data.tournaments.2022.q1 %}
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
