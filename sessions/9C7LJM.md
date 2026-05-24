---
layout: session
title: "A new stack for OpenStreetMap vector tiles"
code: "9C7LJM"
speaker_names: ['Matt White']
affiliations: None
room: "Talks IV/Workshops II/BoF III - Amphi Picard or Navier (Carnot)"
length: "5"
time: "Saturday, 17:25"
time_iso: "2026-08-29T15:25:00Z"
resources: [{ description: "Ascend Maps Github", url: "https://github.com/styluslabs/maps" }]
recording: True
prerecorded: False
language: en
---

This talk presents an open-source stack for building, rendering, and using OpenStreetMap vector tiles. [Ascend Maps](https://github.com/styluslabs/maps) is a cross-platform application for interactive maps. It is highly customizable, with hiking, cycling, and transit views for the base map, user-editable sources, styles, and shaders for custom maps, and plugins for search, routing, and map sources.

[tangram-ng](https://github.com/styluslabs/tangram-ng) extends the Tangram ES map engine originally created by Mapzen, adding support for 3D terrain, embedded SVG, and additional raster formats, along with substantial performance and stability improvements.

[geodesk-tiles](https://github.com/styluslabs/geodesk-tiles) builds vector tiles on demand from a GeoDesk library, making it possible to start serving tiles for the whole world instantly.  geodesk-tiles also provides geocoding for worldwide place and POI search.

