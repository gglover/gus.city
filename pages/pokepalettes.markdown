---
layout: default
title: Pokepalettes
permalink: /projects/pokepalettes
---

<h2 markdown="0">{% include external_link.html title='pokepalettes.com' href='https://pokepalettes.com' %}</h2>

A simple, one-page site that breaks down the color palettes used in pokemon sprites. Some designers have told me that they use it for inspiration. Most people just visit to get blasted with pretty colors.

<div class="card">
  <a href="https://pokepalettes.com">
    <img alt="pokepalettes.com screen shot with Porygon featured" src="/assets/images/pokepalettes.jpg" />
  </a>
</div>

I originally built this in my college dorm to learn jQuery. A few years later I refined the idea and rewrote the site in backbone.js (rip). 
The focus for me was creating something smooth, performant, and fun to use. This was before `image-rendering: pixelated;` was widely supported
in the CSS spec so I expand the 96x96 png sprites pixel-by-pixel onto a `<canvas>`.

I was blessed to ride the algorithm all the way to the Reddit front page. I earned a few write-ups as a result.

<div markdown="0"> 
{% include external_link.html title='fastcompany.com' href='https://www.fastcompany.com/3049601/pokemon-palettes-turns-pikachu-into-a-design-tool' %}
{% include external_link.html title='onepagelove.com' href='https://onepagelove.com/pokemon-palettes' %}
</div>



