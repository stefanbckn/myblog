---
layout: single
title: Antwerp Stats
permalink: /antwerp-stats/
classes: wide
---
## G5 - Na speeldag 18

<table>
  {% for row in site.data.G5 limit:5 %}
    {% if forloop.first %}
    <thead>
      <tr>
        {% for pair in row %}
          <th>{{ pair[0] }}</th>
        {% endfor %}
      </tr>
    </thead>
    {% endif %}    
    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

## Antwerp resultaten JPL

<table>
  {% for row in site.data.antwerp %}
    {% if forloop.first %}
    <thead>
      <tr>
        {% for pair in row %}
          <th>{{ pair[0] }}</th>
        {% endfor %}
      </tr>
    </thead>  
    {% endif %}
    
    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>
