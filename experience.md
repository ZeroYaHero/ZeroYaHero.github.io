---
layout: default
title: Experience
permalink: /experience/
---

{% include nav.html %}

# Experience

<!-- TODO: one or two sentences. What kind of work do you want next? -->

---

## A & M Home Services

*<!-- TODO: role -->* · <!-- TODO: start date – end date -->

<!-- TODO: what you did. Two or three bullets is enough. -->

Branding work for this company is on the [Design]({{ '/design/' | relative_url }}) page.

---

## Zero Station Framing

*<!-- TODO: role -->* · <!-- TODO: start date – end date -->

<!-- TODO: what you did. -->

---

## JobBeaconMaine

*<!-- TODO: role -->* · <!-- TODO: start date – end date -->

<!-- TODO: what you did. -->

Branding work for this company is on the [Design]({{ '/design/' | relative_url }}) page.

---

## Freelance and Contract

*Unreal Editor for Fortnite, Verse, and technical art* · <!-- TODO: date range -->

- **HP Customizer.** Commissioned mechanic in Verse and the UE material graph, built for
  [Raider464's most popular game, which hits a peak CCU of around 10k daily](https://fortnite.gg/island?code=1832-0431-4852).
- **VerseVolumes.** Commissioned trigger volume tool for another UEFN creator. The tool
  abstracts trigger volumes and sources transforms from positions, entities, or actors.
- **UEFN Class Generator.** GUI that generates Verse code and UEFN devices from a set of
  configurations. I built it for contract work and used it there.
- **Thumbnail Sparkle and Outline Utility.** Substance graph for a content creator who ran
  a popular UGC gamemode, so that a thumbnail update no longer needed an outside artist.
- **Reload Realistics.** Gamemode built with another content creator. I made the branding,
  the renders, and the holographic UI shaders.

The full breakdown of each piece is on the [Projects]({{ '/projects/' | relative_url }})
and [Content]({{ '/content/' | relative_url }}) pages.

---

## Own Work

*Games, tools, and engines* · <!-- TODO: date range -->

- **Storm Box.** Full game that I made and published myself in the Fortnite UGC ecosystem.
  Procedural storm, procedural environment generation, materials, models, and key art.
- **Zetris.** Retro game clone engine written in C. The playfield packs into 32 bit
  integers and the pieces into 16 bit integers, with bitwise operators for rotation,
  collision, and locking.
- **ZeRayTracer.** CPU ray tracer written from scratch in C++ with a CMake build, with
  several material types, camera effects, and multithreading.
- **BugByte.** Work-in-progress narrative arcade game in Godot.

---

## Contact

[zeroyaheroofficial@gmail.com](mailto:zeroyaheroofficial@gmail.com)

{% for link in site.header_links %}
- [{{ link.name }}]({{ link.url }})
{%- endfor %}
