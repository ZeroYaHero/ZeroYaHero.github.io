---
layout: default
title: Projects
permalink: /projects/
description: >-
  Games, tools, and technically demanding projects built by ZeroYaHero,
  from engine plugins to shipped game jam entries.
---

{% include nav.html %}

# Projects

Games, tools, and other technically demanding software.

---

## Waves @ [Kelson Marine Co.]({{ '/experience/#kelson' | relative_url }})

<img src="{{ '/assets/projects/kelson/KelsonWaveGifs.gif' | relative_url }}" alt="kelsonwavesgif" width="600">

![cpp](https://skillicons.dev/icons?i=cpp,cmake,cs,python,unity&theme=dark)

Improved Kelson's VR visualization for ocean waves in Unity. 

Previously they used sum-of-wave-components for the water surface which was resource demanding and unconvincing. The system requires an offline wave simulation model and a real-time wave renderer to agree on ocean surface at every point and time. I reverse-engineered a Unity high-performance real-time water rendering package built on FFTs. I applied ocean-engineer-advised modifications, came up with novel solutions for computing below surface velocities and accelerations, and finally implemented it as an alternative simulation mode inside Kelson's C++ framework. 

This resulted in Kelson having a visualization-optimized gerstner wave simulation model and better looking waves with stronger performance in Unity.

---

## ZeRayTracer

<img src="https://github.com/ZeroYaHero/ZeRayTracer/blob/main/renders/chapter_14.png?raw=true" alt="ZeRayTracer render" width="600">

![cpp](https://skillicons.dev/icons?i=cpp,cmake,visualstudio&theme=dark)

CPU ray tracer programmed in C++ with CMake. Contains different
material types, camera effects, and multithreading.

[GitHub](https://github.com/ZeroYaHero/ZeRayTracer)

---

## Zetris

<img src="{{ '/assets/projects/zetris/ZETRIS_LOGO.png' | relative_url }}" alt="Zetris logo" width="300">

<img src="{{ '/assets/projects/zetris/ZETRIS_GAME.png' | relative_url }}" alt="Zetris gameplay" width="600">

![c](https://skillicons.dev/icons?i=c,cmake,visualstudio,clion&theme=dark)

Retro game clone written in C. The playfield is encoded into 32 bit integers
and the pieces are encoded in 16 bit integers. Bitwise operators rotate the pieces,
detect collision, and lock the cells. Unique project structure. It offers a default renderer with Raylib, and
I intend to add others in the future.

[GitHub](https://github.com/ZeroYaHero/Zetris)

---

## UEFN Class Generator

<img src="{{ '/assets/projects/classgen/classgen_demo.gif' | relative_url }}" alt="demo" width="600">

![UnrealGodot](https://skillicons.dev/icons?i=unreal,godot&theme=dark)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

GUI that generates Verse code and UEFN devices (UE actor properties) from a set of
configurations. The tool combines the configurations with a cartesian product. Was a quick project that didn't need to look pretty. I created this tool for
contract work and I used it there. The source is available, so I do not go into more
detail here.

[GitHub](https://github.com/ZeroYaHero/UEFNClassGenerator)

---

## Storm Box
{: #stormbox }

<img src="{{ '/assets/projects/stormbox/T_StormBoxRender.png' | relative_url }}" alt="Storm Box render" width="600">

![Tools Used](https://skillicons.dev/icons?i=unreal,blender,python,photoshop,illustrator&theme=light)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">
<img src="{{ '/assets/icons/s3d.png' | relative_url }}" alt="Substance 3D" width="48">

Full game published myself in Fortnite UGC ecosystem.

- Procedural and randomized storm
- Procedural and randomized environment generation system, which uses [VerseNoise](#versenoise)

  <img src="{{ '/assets/projects/stormbox/procenv_demo.gif' | relative_url }}" alt="Procedural environment demo" width="350">
- UE materials (storm, UI, landscape)
- Substance 3D materials (lobby walls, floor, and ceiling, cardboard box, platform)
- Blender models and rigs (cardboard box, platform, terrain prefabs, lobby)
- Logo design
- Blender key art and renders (logo, animation, and thumbnail)

[GitHub](https://github.com/ZeroYaHero/StormBox)

---

## VerseNoise

<img src="{{ '/assets/projects/versenoise/versenoise_demo.gif' | relative_url }}" alt="noise" width="500">

![Unreal](https://skillicons.dev/icons?i=unreal&theme=dark)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

Custom noise program in UE/UEFN Verse. Perlin noise inspired it, and it uses Fractal
Brownian Motion (FBM). Verse has no native noise method and no bitwise operators, so the
program depends completely on `mod`. This made performance a challenge.

[GitHub](https://github.com/ZeroYaHero/VerseNoise) ·
[Video](https://x.com/ZeroYaHero/status/1765820934768771317)

---

## Wordhole
{: #wordhole }

<img src="{{ '/assets/design/wordhole/word_hole_pixel_black_hole.png' | relative_url }}" alt="BugByte logo" width="300">

<img src="{{ '/assets/projects/wordhole/wordholegif.gif' | relative_url }}" alt="BugByte screenshot" width="600">

![tools](https://go-skill-icons.vercel.app/api//icons?i=unity,cs,aseprite&theme=dark)

Team project for Game Design course. I pitched the idea as "scrabble meets tetris," taking advantage of them both being played on a grid. I did most of the logic programming (though it is a vertical slice), and worked on the innovative scoring mechanic. I also did all of the shader work.

---

## HP Customizer

<p><a href="https://x.com/ZeroYaHero/status/1915778658246983900">
<img src="{{ '/assets/projects/hpcustomizer/hp_customizer.gif' | relative_url }}" alt="HP Customizer" width="450">
</a></p>

![Unreal](https://skillicons.dev/icons?i=unreal&theme=light)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

Mechanic made in Verse and the UE material graph. The visual component lets players 
modify their own health. This was a commissioned piece for
[Raider464's most popular game, which hits a peak CCU of around ~8k daily](https://fortnite.gg/island?code=1832-0431-4852).

[Video](https://x.com/ZeroYaHero/status/1915778658246983900)

---

## VerseVolumes: OOP Trigger Volume Tool

<img src="{{ '/assets/projects/versevolumes/T_Volume.png' | relative_url }}" alt="VerseVolumes" width="450">

<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

Commission for another UEFN creator. OOP is not my favorite, and as I do more the more I
prefer ECS (or just simple composition over inheritance trees). For this project I wanted to experiment with it in an extreme way. The tool abstracts
trigger volumes and lets the user select positions or source the transforms of entities
and actors.

[GitHub](https://github.com/ZeroYaHero/VerseVolumes)

---

## "Dead by Daylight" Inspired QTE/Skill Check
{: #qte }

<img src="{{ '/assets/projects/qte/qte_demo.gif' | relative_url }}" alt="qte" width="450">

<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

Hand drawn assets in Procreate. I then scripted the UI in Verse. The logic is simple.
The track is a normalized 0 to 1 range. When the player presses the button, the system
evaluates the position and compares it to the "critical" point at a very low float
tolerance. On a miss, the system compares the position at the "safe zone" tolerance (the
red box). Critical and safe hit can each give a different amount of progress, the total
necessary progress is customizable, and the progress can be configured to be universal to a lobby
or individual.

[Gist](https://gist.github.com/ZeroYaHero/17463e55a8f0a9be01fcd9c55fe1a8e0) ·
[Video](https://x.com/ZeroYaHero/status/1735732924182327667)

---

## BugByte

<img src="{{ '/assets/projects/bugbyte/T_BugByteLogo.png' | relative_url }}" alt="BugByte logo" width="400">

<img src="{{ '/assets/projects/bugbyte/bbdemo.png' | relative_url }}" alt="BugByte screenshot" width="600">

![GodotBlender](https://skillicons.dev/icons?i=godot,blender&theme=light)

BugByte is a work-in-progress narrative game created in Godot. The current elements feature a terminal emulator I created in engine which the player uses to progress through the story.