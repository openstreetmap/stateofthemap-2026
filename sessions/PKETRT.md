---
layout: session
title: "Style-as-Code: Moving Beyond &#34;Off-the-Shelf&#34; to Unlock the Full Richness of OSM Data"
code: "PKETRT"
speaker_names: ["paul goullencourt"]
affiliations: None
room: "Martinique"
length: "20"
time: "Friday, 15:40"
time_iso: "2026-08-28T13:40:00Z"
resources: []
recording: True
prerecorded: False
language: fr
---

OpenStreetMap is one of the richest databases in the world. state of the map

whenever it comes to creating a vector base map, we all run into the same wall: the daunting complexity of MapLibre/Mapbox GL style files. The result? We tend to fall back on &#34;off-the-shelf&#34; styles or minor variations, smoothing over the semantic richness of the underlying data.

As a GIS engineer at Tesmo Maps / SNCF Connect, I had to rethink my methods to stop being held back by my tools. In this talk, I share my hands-on experience building an industrial-grade workflow to regain full control over map rendering:

- **Style-as-Code:** Why and how I moved away from visual editors (such as Maputnik) to work directly with JSON in a text editor.
- **The &#34;Live Edit&#34; workflow:** A walkthrough of my toolstack — simple, reproducible, and built entirely on open-source components.
- **The Design/OSM translator:** My method for collaborating with designers who have no background in geography or the OSM data model, and turning their creative intentions into complex technical filters.

The goal is to show that anyone can build and maintain a large number of fully custom styles.

<hr>

1. The Problem: The JSON Wall 

Why do we keep getting stuck with the same base maps? I will revisit the challenge of maintaining 5,000-line files and the inability of conventional tools to handle evolving data schemas. 

2. Style-as-Code 

I will detail the advantages of the code-based approach: version control with Git, modularity, and above all the ability to modify hundreds of layers at once. I will cover the use of tools like Stamen's map-gl-style-build to break down an unwieldy style into logical, reusable components. 

3. Live Edit Stack Demo 

How to set up your environment so that style work becomes as fluid as web development. I will show how I use MapLibre to preview changes instantly and how I compare styles side by side to validate rendering quality. 

4. Collaborating with Creatives 

The GIS engineer as translator. I will share my tips for bridging the gap between a client or designer's vision — often aesthetic in nature — and the technical reality of OSM. 

Conclusion: Cartography for everyone — customization is no longer a luxury reserved for web giants. By industrializing our methods, we can all produce maps that reflect our own vision and do justice to the richness of the OpenStreetMap data model

