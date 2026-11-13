---
layout: default
title: Tech Art
permalink: /techart/
description: >-
  Shaders, VFX, procedural assets, and renders by ZeroYaHero.
---

{% include nav.html %}

# **Tech Art**

Shaders, assets, art tools, and renders. Made in Unreal, Blender, or procedural texture node editors (Substance Designer, Material Maker, etc)

---

## Niagara FX Cosmetics Content & Framework

<img src="{{ '/assets/content/cosmetics/cosmetics.gif' | relative_url }}" alt="Cosmetics" width="500">

<img src="https://skillicons.dev/icons?i=unreal,blender&theme=dark" alt="Tools">

- Cosmetics created using Blender, Unreal Material Graph, and Niagara particles for a confidential client.
- The effects use a custom framework that makes it easy for the client to add new effects and to configure their spawn point via game event without writing code. Simply creating an entity prefab of the cosmetic and setting certain variables (ie: what type) allows it to properly be instantiated in the world during the right event.

---

## Procedural Environment Generation System

<img src="{{ '/assets/projects/stormbox/procenv_demo.gif' | relative_url }}" alt="procedural environment" width="500">

<img src="https://skillicons.dev/icons?i=unreal,blender&theme=dark" alt="Tools">

- Procedural environment generation system using my own implementation of Perlin noise with fractal brownian motion, VerseNoise.
- Uses spatial hashing to prevent collisions and enable foliage spawning.
- Empowers the user to easily add a terrain or foliage asset into the pool of prefabs.
- Biomes use a combination of VerseNoise and a voroni diagram for temperature and humidity values.
- Parameterized to easily change the density of land as well as the probablity of all asset types or biomes.

<a class="btn" href="https://github.com/ZeroYaHero/StormBox/#storm-box">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

---

## Thumbnail Sparkle and Outline Utility Shader

<img src="{{ '/assets/content/thumbnail/T_ThumbnailUtility.png' | relative_url }}" alt="Thumbnail utility shader" width="500">

<img src="{{ '/assets/icons/s3d.png' | relative_url }}" alt="Substance 3D" width="48">

- Substance graph created for a client to easily add sparkles and outline for items intended to be used in thumbnails.

<!-- I worked with a content creator who managed a popular UGC gamemode in Fortnite. Each
time they updated their mode, they usually updated the thumbnail with a sparkling *new*
item. The problem? A different "guy" did the image every time. This was inefficient, so
I created a Substance graph that does the process for you and gives you access to some
parameters. -->

<!-- [View the showcase video](https://x.com/ZeroYaHero/status/1822694817567998083) -->

---

## HP Customizer

<p><a href="https://x.com/ZeroYaHero/status/1915778658246983900">
<img src="{{ '/assets/projects/hpcustomizer/hp_customizer.gif' | relative_url }}" alt="HP Customizer" width="450">
</a></p>

![Unreal](https://skillicons.dev/icons?i=unreal&theme=light)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

- Commission work for Raider464 and [used in his most popular game](https://fortnite.gg/island?code=1832-0431-4852).
- Visual interactive component for modifying player settings.
- Utilizes a few tricks with manipulating UVs and object scale in tandem with Verse's animation controller to smoothly interpolate the health bar values with higher refresh rate.

<!-- Mechanic made in Verse and the UE material graph. The visual component lets players 
modify their own health. This was a commissioned piece for
[Raider464's most popular game, which hits a peak CCU of around ~8k daily](https://fortnite.gg/island?code=1832-0431-4852). -->

<!-- [View the showcase video](https://x.com/ZeroYaHero/status/1915778658246983900) -->

---

## Reload Realistics: Logo Renders

<div class="render-grid">
  <img src="{{ '/assets/design/reloadrealistics/RR_SkyRenderV4SquarePS.png' | relative_url }}" alt="Reload Realistics square render">
  <img src="{{ '/assets/design/reloadrealistics/RR_SkyRenderLogoPS.png' | relative_url }}" alt="Reload Realistics wide render">
  <img src="{{ '/assets/design/reloadrealistics/RR_SkyRenderV1.png' | relative_url }}" alt="Reload Realistics first render">
</div>

![BlenderIllustrator](https://skillicons.dev/icons?i=blender,illustrator&theme=dark)

- Game announcement keyart/renders.
- Icon/logo design done in illustrator, render in Blender, and final edits in Photoshop.

<!-- I made a gamemode with another content creator called Reload Realistics. I wanted us to
have distinct and clean branding, so I made two different logos for us and rendered them
in a scene with clouds in Blender. -->

---

## Knockout Tour Inspired Post-Processing and Emissive Shaders

<img src="{{ '/assets/content/knockout/T_Knockout.png' | relative_url }}" alt="Knockout shader" width="500">

![Unreal](https://skillicons.dev/icons?i=unreal&theme=light)

- Post-processing shader effect influenced by Mario Kart World's new Knockout Tour mode.
- Created in Unreal Engine's Material Graph.

<!-- The new MKW game inspired this. I wanted to see if I could recreate the post-process
effect that you see near the checkpoints. It brings a thrill and an adrenaline that I had
not felt in a while. At first I intended to make a game that parodies the concept. It
ended up as a fun warmup instead. -->

<!-- [View the showcase video](https://x.com/ZeroYaHero/status/1986094793387315574) -->

---

## Battle Royale Storm / Zone Inspired Shader

<img src="{{ '/assets/content/storm/T_Storm.png' | relative_url }}" alt="Storm shader" width="500">

![Unreal](https://skillicons.dev/icons?i=unreal&theme=light)

- Recreated the Fortnite storm (also referred to as zone) in UEFN with Material Graph.
- Customizable flickering speed, tiling size, tiling offset, noise speed, noise size, color, etc.

<!-- In a battle royale, the storm or the closing zone is one of the most important shaders,
because it tells the player what to avoid. Unreal Editor for Fortnite gives no way to
read or modify some of the materials that Epic Games uses for their own BR, which is
understandable. I wanted something similar to build my skills. With pure exploration, and
much trial and error, I got something pretty close.

[View the showcase video](https://x.com/ZeroYaHero/status/1687967828215754753) -->


---

## Promotional Shaders

<img src="{{ '/assets/content/promo/promo_pic.png' | relative_url }}" alt="Promotional shaders" width="600">

![UnrealIllustrator](https://skillicons.dev/icons?i=unreal,illustrator&theme=dark)

- Promotional animated assets that use Materials (shaders) in Unreal Engine with a custom "keyframe" setup that normalizes duration to easily modify timing and speed of events.
- No flipbooks or sequencer used.
- Sold to multiple clients within Fortnite's ecosystem.

<!-- These shaders use the Unreal material graph with no flipbooks and a "keyframe" like
setup. I created multiple shader functions to make the process easier. I created the
vector art in Adobe Illustrator. -->

<!-- [View the showcase video](https://x.com/ZeroYaHero/status/1928556416593260632) -->

---

## "Dead by Daylight" Inspired QTE/Skill Check
{: #qte }

<img src="{{ '/assets/projects/qte/qte_demo.gif' | relative_url }}" alt="qte" width="450">

<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

<!-- Hand drawn assets in Procreate. I then scripted the UI in Verse. The logic is simple.
The track is a normalized 0 to 1 range. When the player presses the button, the system
evaluates the position and compares it to the "critical" point at a very low float
tolerance. On a miss, the system compares the position at the "safe zone" tolerance (the
red box). Critical and safe hit can each give a different amount of progress, the total
necessary progress is customizable, and the progress can be configured to be universal to a lobby
or individual. -->

- Quick-time event (also referred to as a skill check) created in Verse.
- Easily triggerable and configurable to share progress between individuals or the lobby.

<a class="btn" href="https://gist.github.com/ZeroYaHero/17463e55a8f0a9be01fcd9c55fe1a8e0">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Gist
</a>

<!-- [View the gist](https://gist.github.com/ZeroYaHero/17463e55a8f0a9be01fcd9c55fe1a8e0) -->
<!-- [View the showcase video](https://x.com/ZeroYaHero/status/1735732924182327667) -->

---

## Cardboard Box Model and Fire Dissolve Shader

<img src="{{ '/assets/content/firedissolve/burn_demo.gif' | relative_url }}" alt="Fire dissolve demo" width="500">

![UnrealBlender](https://skillicons.dev/icons?i=unreal,blender&theme=dark)
<img src="{{ '/assets/icons/s3d.png' | relative_url }}" alt="Substance 3D" width="48">

- Throwaway dissolve animation for a cardboard box (which I modeled in Blender and textured with Substance 3D suite).
- The animated effect takes advantage of Unreal Engine Material graph nodes "bounding box" and "object scale" to make the box appear as it is burning while also using vertex displacement to keep it proportional.

<!-- One of my games, [Storm Box](https://github.com/ZeroYaHero/StormBox), used completely
procedural elements. The game generated the terrain, randomized the direction of the safe
zone, and generated the spawn location of the players. The inevitable issue: when you
generate things, you need a way to delete them. This was a way to delete the cardboard
boxes that players spawned in. I scrapped it later. -->

---

## Sci-Fi Cube Study Shader

<img src="{{ '/assets/content/scificube/T_SciFiCube.png' | relative_url }}" alt="Sci-fi cube shader" width="500">

<img src="{{ '/assets/icons/s3d.png' | relative_url }}" alt="Substance 3D" width="48">

- Substance 3D Painter study.

<!-- [View the reference](https://shineyquiney.artstation.com/projects/aa39z) ·
[View the showcase video](https://x.com/ZeroYaHero/status/1819143137819820472) -->
