---
layout: default
title: Software
permalink: /software/
description: >-
  Games, tools, and technically demanding projects built by ZeroYaHero.
---

{% include nav.html %}

# **Software**

tools, games, and other technically demanding software.

---

## Waves @ [Kelson Marine Co.]({{ '/experience/#kelson' | relative_url }})

<img src="{{ '/assets/projects/kelson/KelsonWaveGifs.gif' | relative_url }}" alt="kelsonwavesgif" width="600">

![cpp](https://skillicons.dev/icons?i=cpp,cmake,cs,python,unity&theme=dark)

- Improved wave visualization and simulation for Kelson's VR demo.
<!-- - Solution introduced horizontal vertex displacement (non-linear waves). -->
- Replaced sum-of-sin waves C++ simulation mode with a FFT-based one. Tested with Catch2 and profiled with Google Benchmark.
- Improved editor framerate by 60%.
- Project initiated by myself after pitching a few ideas to create big impact.
- Learned and applied relevant fundamentals of oceanography.
<!-- - Applied ocean-engineer-advised modifications and came up with novel solutions for computing below surface velocities and accelerations. -->

<a class="btn" href="https://www.linkedin.com/feed/update/urn:li:activity:7495546694785249295/">
  <span class="icon">{% include icon.html name="linkedin" %}</span>LinkedIn Post
</a>

<!-- [LinkedIn post](https://www.linkedin.com/feed/update/urn:li:activity:7495546694785249295/) -->

<!-- My biggest accomplishment at Kelson Marine Co. was improving their VR visualization for ocean waves in Unity. Previously they used sum-of-wave-components for the water surface which was resource demanding and "unconvincing". The functional requirements ask for an offline wave simulation model and a real-time wave renderer to agree on ocean surface universally. I reverse-engineered a Unity-based high-performance real-time water rendering package built on FFTs. I applied ocean-engineer-advised modifications, came up with novel solutions for computing below surface velocities and accelerations, and finally implemented it as an alternative simulation mode inside Kelson's C++ framework.  -->

---

## VerseFNItemPreview

<img src="{{ '/assets/projects/versepreview/VerseFNItemPreviewGIF.gif' | relative_url }}" alt="versefnitempreview" width="600">

![extension](https://skillicons.dev/icons?i=vscode,typescript,cs,dotnet,unreal&theme=dark)

- VSCode extension for Verse and UEFN.
- Parses local game archive files with CUE4Parse C# ASP.NET core backend.
- Extracts and exports textures of Fortnite item entity assets.
- Utilizes Levenshtein string distance to compare parsed assets with hovered Verse tokens.
<!-- - Extension requests icons for a given asset which the backend fetches from a cache or exports on demand. -->
- Leverages GitHub workflows to automatically build and deploy.

<a class="btn" href="https://github.com/ZeroYaHero/VerseFNItemPreview">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

<!-- VSCode extension for Verse language and the Unreal Editor for Fortnite (UEFN). It provides icon/thumbnail preview on hover of reflected Fortnite item entities in your code or digest files. I made this for my own usecase where I was getting frustrated on the inconsistent naming convention of the items in code and their actor counterparts in the content drawer. This preview allows you to better understand what items you are granting to players ahead of time instead of needing to do a reverse lookup or starting session! -->

<!-- [View the repository](https://github.com/ZeroYaHero/UEFNClassGenerator/#uefn-class-generator) -->

---

## ZeRayTracer

<img src="https://github.com/ZeroYaHero/ZeRayTracer/blob/main/renders/chapter_14.png?raw=true" alt="ZeRayTracer render" width="600">

![cpp](https://skillicons.dev/icons?i=cpp,cmake,visualstudio&theme=dark)

- Software ray tracer programmed in C++ with a CMake build system.
- Different material types, camera effects, and multithreading.

<!-- CPU ray tracer programmed in C++ with CMake. Contains different material types, camera effects, and multithreading. -->

<a class="btn" href="https://github.com/ZeroYaHero/ZeRayTracer/#zeray-tracer">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

---

## UEFNClassGenerator

<img src="{{ '/assets/projects/classgen/classgen_demo.gif' | relative_url }}" alt="demo" width="600">

![UnrealGodot](https://skillicons.dev/icons?i=unreal,godot&theme=dark)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

<!-- GUI that generates Verse code and UEFN devices (UE actor properties) from a set of
configurations. The tool combines the configurations with a cartesian product. Was a quick project that didn't need to look pretty. I created this tool for
contract work and I used it there. The source is available, so I do not go into more
detail here. -->

- Deterministic tool that generates Verse code and UEFN devices (UE actor properties) from a set of configurations via cartesian product.
- Replaces a manual workflow with an automated one that consumes ~75% less time. 
- Created to complete work for client.
- GUI put together in Godot due to UI toolkit (controls) being similar to Unreal's Slate widget containers.
  - The components are default styled. The look of this tool was not nearly as important as the core functionality.

<a class="btn" href="https://github.com/ZeroYaHero/UEFNClassGenerator/#uefn-class-generator">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

---

## Zetris

<img src="{{ '/assets/projects/zetris/ZETRIS_LOGO.png' | relative_url }}" alt="Zetris logo" width="300">

<img src="{{ '/assets/projects/zetris/ZETRIS_GAME.png' | relative_url }}" alt="Zetris gameplay" width="600">

![c](https://skillicons.dev/icons?i=c,cmake,visualstudio,clion&theme=dark)

<!-- Retro game clone written in C. The playfield is encoded into 32 bit integers
and the pieces are encoded in 16 bit integers. Bitwise operators rotate the pieces,
detect collision, and lock the cells. Unique project structure. It offers a default renderer with Raylib, and
I intend to add others in the future. -->

- Retro game clone written in C with a CMake build system.
- Playfield and pieces encoded in 32 and 16 bit integers respectively.
- Collision detected with bitwise operators.
- Almost universally on the stack.
- Unique "model view" project architecture enabling logic to be lean and renderer to be implemented independently.

<a class="btn" href="https://github.com/ZeroYaHero/Zetris">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

<!-- [View the repository](https://github.com/ZeroYaHero/Zetris) -->

---

## VerseNoise

<img src="{{ '/assets/projects/versenoise/versenoise_demo.gif' | relative_url }}" alt="noise" width="500">

![Unreal](https://skillicons.dev/icons?i=unreal&theme=dark)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

- Custom 2D and 3D noise library written in Verse.
- Inspired by Perlin noise and uses fractal brownian motion.

<!-- Custom noise program in UE/UEFN Verse. Perlin noise inspired it, and it uses Fractal
Brownian Motion (FBM). Verse has no native noise method and no bitwise operators, so the
program depends completely on `mod`. This made performance a challenge. -->

<a class="btn" href="https://github.com/ZeroYaHero/VerseNoise/#versenoise">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

---

## VerseVolumes

<img src="{{ '/assets/projects/versevolumes/T_Volume.png' | relative_url }}" alt="VerseVolumes" width="450">

<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

- Verse library created for a client.
- Alternative lightweight trigger volume implementation.
- Features different shapes with variety of options to set boundaries and positioning.
- Implemented with an object oriented inheritance hierarchy.

<a class="btn" href="https://github.com/ZeroYaHero/VerseVolumes">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

<!-- Commission for another UEFN creator. OOP is not my favorite, and as I do more the more I
prefer ECS (or just simple composition over inheritance trees). For this project I wanted to experiment with it in an extreme way. The tool abstracts
trigger volumes and lets the user select positions or source the transforms of entities
and actors. -->

<!-- [View the repository](https://github.com/ZeroYaHero/VerseVolumes) -->

---

## Reload Realistics
{: #reloadrealistics }

<img src="{{ '/assets/design/reloadrealistics/RR_SkyRenderLogoPS.png' | relative_url }}" alt="reload realistics render" width="600">

![tools](https://skillicons.dev/icons?i=unreal&theme=dark)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">

<!-- Game published in Fortnite's UGC ecosystem in mid 2025 using Unreal Editor for Fortnite (UEFN) inspired by the release of Fortnite Reload a year prior, with the goal of being slightly faster and more arcade-y. -->

- Game published in Fortnite's UGC ecosystem with UEFN and Verse.
- Unique project gamemode management system.
- Explicit game state management.
- High quality UMG user interface recreations.

<a class="btn" href="https://github.com/ZeroYaHero/ReloadRealistics/#reload-realistics">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

<!-- [View the repository](https://github.com/ZeroYaHero/ReloadRealistics/#reload-realistics) -->

---

## Storm Box
{: #stormbox }

<img src="{{ '/assets/projects/stormbox/T_StormBoxRender.png' | relative_url }}" alt="Storm Box render" width="600">

![Tools Used](https://skillicons.dev/icons?i=unreal,blender,python,photoshop,illustrator&theme=dark)
<img src="{{ '/assets/icons/verse.jpeg' | relative_url }}" alt="Verse" width="48">
<img src="{{ '/assets/icons/s3d.png' | relative_url }}" alt="Substance 3D" width="48">


- Game published in Fortnite's UGC ecosystem with UEFN and Verse.
- Randomized storm and procedural environment generation systems.
- Modeled and textured lobby environment with Blender and Substance 3D suite.

<a class="btn" href="https://github.com/ZeroYaHero/StormBox/#storm-box">
  <span class="icon">{% include icon.html name="github" %}</span>GitHub Repository
</a>

---

## Wordhole
{: #wordhole }

<img src="{{ '/assets/design/wordhole/word_hole_pixel_black_hole.png' | relative_url }}" alt="Wordholelogo" width="300">

<img src="{{ '/assets/projects/wordhole/wordholegif.gif' | relative_url }}" alt="wordhole logo" width="600">

![tools](https://skillicons.dev/icons?i=unity,cs&theme=dark)

- Team project for Game Design course.
- Pitched the idea as "scrabble meets tetris" taking advantage of a shared grid.
- Responsible for scoring, word recognition, gravity, and shaders. 

<!-- Team project for Game Design course. I pitched the idea as "scrabble meets tetris," taking advantage of them both being played on a grid. I did most of the logic programming (though it is a vertical slice), and worked on the innovative scoring mechanic. I also did all of the shader work. -->

---

## BugByte

<img src="{{ '/assets/projects/bugbyte/T_BugByteLogo.png' | relative_url }}" alt="BugByte logo" width="400">

<img src="{{ '/assets/projects/bugbyte/bbdemo.png' | relative_url }}" alt="BugByte screenshot" width="600">

![GodotBlender](https://skillicons.dev/icons?i=godot&theme=dark)

- Work-in-progress narrative game created in Godot.
- Features a hand written terminal emulation system.

<!-- BugByte is a work-in-progress narrative game created in Godot. The current elements feature a terminal emulator I created in engine which the player uses to progress through the story. -->