---
layout: default
title: Design
permalink: /design/
description: >-
  Logos, branding, and visual identity work by ZeroYaHero, including
  client marks and personal projects.
---

{% include nav.html %}

# Design

UI, logos, and branding.

---

## **[UNANNOUNCED]** Navigation Menu

<img src="{{ '/assets/design/navmenu/navmenu.gif' | relative_url }}" alt="NavMenu">

<img src="https://go-skill-icons.vercel.app/api//icons?i=affinity,unreal&theme=dark" alt="Tools">

Navigation menu created within Unreal Engine using Unreal Motion Graphics for a confidential client. 

The buttons are not designed in isolation. The project this is created for utilizes in-world buttons that have a similar style: italic bold text, centered icons, colorful outlines, and a background of shimmering blocks. I took that look and translated it into UI components. 

The icons are created myself in affinity and sent through a pipeline (MaterialMaker texture graph) which generates their signed distance fields (SDFs). Those signed distance fields are used to increase the stroke/outline of the icons on hover. 

I am really happy with how this turned out, and as usual I shoot for "under promise over deliver" so the client is now intending on utilizing the button styles for other projects in the future.

--- 

## **[UNANNOUNCED]** Cosmetics Shop

<img src="{{ '/assets/design/shop/shop.gif' | relative_url }}" alt="Cosmetics Shop">

<img src="https://go-skill-icons.vercel.app/api//icons?i=illustrator,unreal&theme=dark" alt="Tools">

Cosmetics shop system for a confidential client. 

- Made with Unreal Motion Graphics and Verse
- Leverages Fortnite microtransactions (Verse UnrealEngine.com/Marketplace module). 
- The cosmetics themselves (at least the initial batch) are created by myself. Example can be seen in Tech Art page.
- All of the materials are custom made in Unreal Material Graph. 
- Icons for each page as well as the rarity for each cosmetic type made in illustrator.

Utilizes a hand written code abstraction I call `widget_group` which makes it easy to define data models for widgets with Verse binds. The abstraction is written with the idea of exclusive user interface "pages" in mind. This allows me to make widgets that are traditionally hard to parameterize into something easily customizable. Also prevents the need to constantly allocate resources/memory for new instances of UI.

---

## A & M Home Services

<div class="logo-grid">
  <img src="{{ '/assets/design/amhome/MainLogoW.png' | relative_url }}" alt="A & M Home Services main logo">
  <!-- <img src="{{ '/assets/design/amhome/MainLogoCircleW.png' | relative_url }}" alt="A & M Home Services circle logo"> -->
  <img src="{{ '/assets/design/amhome/MainLogoTextW.png' | relative_url }}" alt="A & M Home Services logo with text">
  <img src="{{ '/assets/design/amhome/LogoTextCircleW.png' | relative_url }}" alt="A & M Home Services circle logo with text">
  <!-- <img src="{{ '/assets/design/amhome/LogoCricleTextSparkleW.png' | relative_url }}" alt="A & M Home Services circle logo with sparkle"> -->
  <img class="wide" src="{{ '/assets/design/amhome/LogoWideTextW.png' | relative_url }}" alt="A & M Home Services wide logo">
  <!-- <img class="wide" src="{{ '/assets/design/amhome/CircleLogoWideTextW.png' | relative_url }}" alt="A & M Home Services wide circle logo"> -->
</div>

![Illustrator](https://skillicons.dev/icons?i=illustrator&theme=light)

Logo work for a local residential window washing company.

---

## Zero Station Framing

<div class="logo-grid">
  <img src="{{ '/assets/design/zsframe/ZSOrangeFinal.png' | relative_url }}" alt="ZS main logo color and text">
  <img src="{{ '/assets/design/zsframe/ZSWhiteAlpha.png' | relative_url }}" alt="ZS main logo">
  <img src="{{ '/assets/design/zsframe/ZSWhiteFramingAlpha.png' | relative_url }}" alt="ZS main logo and text">
</div>

![Illustrator](https://skillicons.dev/icons?i=illustrator&theme=light)

Logo work for a local art framing company.

---

## **[WORK-IN-PROGRESS & UNANNOUNCED]** "Clock" Menu & HUD

<img src="{{ '/assets/design/clock/clock.gif' | relative_url }}" alt="Clock Menu">

<img src="https://go-skill-icons.vercel.app/api//icons?i=affinity,unreal&theme=dark" alt="Tools">

Clock menu that enables a player to calibrate their local timezone, alarms, timers, and start a stopwatch for a confidential client. The navigation is intended to mimic a clock app on a mobile phone. I had the idea of introducing a world map to roughly match the area of the timezone that a player configures. Eventually, I made it so the world map also transitions between day and night lighting assuming 12 AM is midnight and 12 PM is midday. 

This utilizes the same `widget_group` abstraction as the Cosmetics Shop.

The widgets are split into reusable components with their own Verse binds.

The textures used for this menu were created in MaterialMaker. I took a texture of the world map and generated a signed distance field (SDF) which is used for the coast and waves. Packed in the same texture split between the color channels is world map gradient, light positions, noise, and clouds.

---

## ZeroYaHero

<div class="logo-grid">
  <!-- <img src="https://media.discordapp.net/attachments/1074148411261059142/1195179481921495070/title_screen.gif?ex=6a8e4321&is=6a8cf1a1&hm=eb7d196dd7595eaada520e3865e2194dbcc54f61ee3f1e08f085ba6f4578f219&=&width=640&height=216" alt="Zero pixel"> -->
  <img src="{{ '/assets/brand/T_ZeroFaceLogo.png' | relative_url }}" alt="ZeroYaHero face logo">
  <img src="{{ '/assets/brand/T_ZeroPortrait.png' | relative_url }}" alt="ZeroYaHero portrait">
  <img class="wide" src="{{ '/assets/brand/T_ZeroBanner.png' | relative_url }}" alt="ZeroYaHero banner">
</div>

![tools](https://go-skill-icons.vercel.app/api//icons?i=illustrator,affinity,aseprite&theme=dark)

All ZeroYaHero logos or branding is done by myself.

---

## Storm Box

<!-- <img src="{{ '/assets/projects/stormbox/T_StormBoxRender.png' | relative_url }}" alt="Storm Box key art" width="384"> -->

<div class="logo-grid">
  <img src="{{ '/assets/design/stormbox/T_SB_Logo_V0.png' | relative_url }}" alt="logov1">
  <img src="{{ '/assets/design/stormbox/T_SB_Logo_V1.png' | relative_url }}" alt="logov2">
  <img src="{{ '/assets/design/stormbox/T_SB_LogoOutline.png' | relative_url }}" alt="logofinal">
</div>

![Illustrator](https://skillicons.dev/icons?i=illustrator&theme=light)

I made the logos for my game [Storm Box]({{ '/software/#stormbox' | relative_url }}). Here is a few iterations before ending on the final.

---

## Reload Realistics

<div class="logo-grid">
  <img src="{{ '/assets/design/reloadrealistics/T_ReloadLogo.png' | relative_url }}" alt="Reload Realistics logo">
  <img src="{{ '/assets/design/reloadrealistics/T_RR.png' | relative_url }}" alt="Reload Realistics monogram">
</div>

![Illustrator](https://skillicons.dev/icons?i=illustrator&theme=light)

I made a gamemode with another content creator called Reload Realistics. I wanted us to
have distinct and clean branding, so I made two different logos that mirrored a similar style that Epic Game's used for their Reload mode without infringing.

[Social media post](https://x.com/Ken_Beans_/status/1891223525136138741?s=20)

---

## JobBeaconMaine

<div class="logo-grid">
  <img src="{{ '/assets/design/jobbeacon/T_Circle.png' | relative_url }}" alt="JobBeaconMaine circle logo">
  <img src="{{ '/assets/design/jobbeacon/T_Square.png' | relative_url }}" alt="JobBeaconMaine square logo">
  <img class="wide" src="{{ '/assets/design/jobbeacon/T_HeaderElongatedText.png' | relative_url }}" alt="JobBeaconMaine wide header with text">
  <img class="wide" src="{{ '/assets/design/jobbeacon/T_HeaderShortenedNoText.png' | relative_url }}" alt="JobBeaconMaine short header">
</div>

![Illustrator](https://skillicons.dev/icons?i=illustrator&theme=light)

Databases course full-stack web application team project. I designed my teams logos and branding.\\

---

## BugByte

<img src="{{ '/assets/projects/bugbyte/T_BugByteLogo.png' | relative_url }}" width="500" alt="bugbyte logo">

![Illustrator](https://skillicons.dev/icons?i=illustrator&theme=light)

Logo created for my Godot based indie game project.

---

## Wordhole

<img src="{{ '/assets/design/wordhole/word_hole_pixel_black_hole.png' | relative_url }}" width="400" alt="Wordhole logo">

![tools](https://go-skill-icons.vercel.app/api//icons?i=aseprite&theme=dark)

Logo I made for [Game Design course team project]({{ '/software/#wordhole' | relative_url }}).

---

## "Dead by Daylight" Inspired QTE/Skill Check Texture Art

<img src="{{ '/assets/design/qte/T_QTEAssets.png' | relative_url }}" width="600" alt="qte art">

Custom art assets created in Procreate used for the [QTE/Skill Check I created in UEFN with Verse]({{ '/software/#qte' | relative_url }}).