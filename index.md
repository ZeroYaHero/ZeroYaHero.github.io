---
layout: default
title: ZeroYaHero
---

{% include nav.html %}

<img src="{{ '/assets/Supplements/T_ZeroBanner.png' | relative_url }}" alt="ZeroYaHero">

I make games, tools, shaders, and renders. Some of the work here has its own GitHub
repository. Some of it does not.

- [Projects]({{ '/projects/' | relative_url }}) — Games, tools, and more technically demanding projects.
- [Content]({{ '/content/' | relative_url }}) — Shaders, assets, and renders.
- [Design]({{ '/design/' | relative_url }}) — Logos and branding.
- [Experience]({{ '/experience/' | relative_url }}) — My experiences.

## Contact

Interested in doing work? Email me!
[zeroyaheroofficial@gmail.com](mailto:zeroyaheroofficial@gmail.com)

{% for link in site.header_links %}
- [{{ link.name }}]({{ link.url }})
{%- endfor %}

<img src="{{ '/assets/Supplements/T_ZeroPortrait.png' | relative_url }}" alt="ZeroYaHero portrait" width="200">
