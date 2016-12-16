---
title: Games
permalink: /games/
---
Berikut adalah daftar game individual per kontent

<ul class="post-list game-list">
  {% for game in site.games %}
    <li>
      <h2>
        <a class="post-link" href="{{ game.url | relative_url }}">{{ game.title | escape }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>
