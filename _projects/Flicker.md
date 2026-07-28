---
layout: post
title:  "Flicker"
summary: "Solo Developer"
preview: /assets/flicker_preview.png
background: /assets/flicker_banner.png
order: 5
itchio_embed: 3985332
itchio_url: https://nickolas-simons.itch.io/flicker
---

![Title Image](/assets/flicker_banner.png)

**Overview:**
Submission for the 7 day 2025 Epic Megajam. Entered for the 'One Man Army' and 'Use It or Lose It' special modifiers.

**Theme:** "However vast the darkness, we must supply our own light"

**Assets:** Some audio assets come from weloveindies, all other game assets made by me during the jam.

**Development Details:**
   - **Platform/Engine:**   Developed on UE5 for PC
   - **Time:**  7 days
   - **Team:**  Solo

**Notable Features**
   - Only a single 512x512 RGBA texture is sampled during the game, using a combination of gradient texturing and procedural or noise based post-processing effects (sampled from the texture) for most shaders.
   - Animation for character baked from new locomotor plugin introduced in UE 5.6 (excluding additive layers).
   - Fire effects are created using a blend based upon sine of a signed distance field multiplied with the time since burn activation.

{% if page.itchio_embed %}
<div class="itch-embed">
  <iframe frameborder="0" src="https://itch.io/embed/{{ page.itchio_embed }}?linkback=true" width="552" height="167">
    <a href="{{ page.itchio_url }}">Flicker by nickolas-simons</a>
  </iframe>
</div>
{% endif %}

See the [itch.io page]({{ page.itchio_url }} "flicker itch page") to play.

![Flicker screenshot 1](/assets/flicker1.png)
![Flicker screenshot 2](/assets/flicker2.png)

![Flicker screenshot 3](/assets/flicker3.png)
![Flicker screenshot 4](/assets/flicker4.png)

Link to [gameplay footage](https://youtu.be/ZTP6DVDzDF4 "flicker gameplay").
   