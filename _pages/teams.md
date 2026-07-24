---
layout: default
title: Teams
permalink: /teams/
---

<h1>Teams Test</h1>

<p>Počet tímov: {{ site.teams | size }}</p>

<ul>
{% for team in site.teams %}
  <li>
    <a href="{{ team.url | relative_url }}">
      {{ team.title }}
    </a>
  </li>
{% endfor %}
</ul>
