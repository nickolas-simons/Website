---
layout: post
title:  "Flicker"
summary: "Windows,UE5,C++,Jam,Solo"
preview: /assets/flicker/flicker_preview.webp
image: /assets/flicker/flicker_preview.webp
background: /assets/flicker/flicker2.webp
order: 5
location: "Personal"
itchio_embed: 3985332
itchio_url: https://nickolas-simons.itch.io/flicker
---

![Title Image](/assets/flicker/flicker_banner.webp)

### Overview
Submission for the 7 day 2025 Epic Megajam. Entered for the 'One Man Army' and 'Use It or Lose It' special modifiers.

**Theme:** "However vast the darkness, we must supply our own light"

**Assets:** Some audio assets come from weloveindies, all other game assets made by me during the jam.

{% if page.itchio_embed %}
<div class="itch-embed">
  <iframe frameborder="0" src="https://itch.io/embed/{{ page.itchio_embed }}?bg_color=444150&amp;fg_color=ffcf7b&amp;link_color=fa705b&amp;border_color=333333;linkback=true" width="720" height="167">
    <a href="{{ page.itchio_url }}">Flicker by nickolas-simons</a>
  </iframe>
</div>
{% endif %}

### Development Details
   - **Platform/Engine:** Developed on UE5 for PC
   - **Time:** Oct 2025, 7 days
   - **Team:** Solo

### Notable Features
- Only a single 512x512 RGBA texture is sampled during the game, using a combination of gradient texturing and procedural or noise based post-processing effects (sampled from the texture) for most shaders.
- Animation for character baked from new locomotor plugin introduced in UE 5.6 (excluding additive layers).
- Fire effects are created using a blend based upon sine of a signed distance field multiplied with the time since burn activation.

### Gallery

![Flicker screenshot 1](/assets/flicker/flicker1.webp)

![Flicker screenshot 4](/assets/flicker/flicker4.webp)

![Flicker screenshot 3](/assets/flicker/flicker3.webp)

<div class="video-max-wrapper" style="width: 100%; max-width: 800px; margin: 0 auto; aspect-ratio: 16 / 9;">
  <iframe 
    src="https://www.youtube-nocookie.com/embed/ZTP6DVDzDF4?si=JCzbYDOFE63UiDGL" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen
    style="width: 100%; height: 100%; display: block;">
   iframe>
</div>
