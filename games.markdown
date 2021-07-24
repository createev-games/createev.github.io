---
layout: page
title: Games
permalink: /games/
---
I develop games using Unity engine, C#, and Adobe Illustrator.
Ocassionally I participate in Game Jams and share results on itch.io.

<ul>
  {% for game in site.games %}
    <li>
      <h3><a href="{{ game.url }}">{{ game.name }}</a></h3>
      {{ game.short_description }}
    </li>
  {% endfor %}
</ul>
