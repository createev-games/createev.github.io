---
layout: page
title: Games
permalink: /games/
---
<ul>
  {% for game in site.games %}
    <li>
      <h3><a href="{{ game.url }}">{{ game.name }}</a></h3>
      {{ game.short_description }}
    </li>
  {% endfor %}
</ul>
