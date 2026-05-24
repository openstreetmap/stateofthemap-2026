---
layout: session
title: "Upgrading the OSM Front Page"
code: "EFTDVX"
speaker_names: ['Frank Elsinga']
affiliations: None
room: "Talks I / Opening - Amphi Caquot (Coriolis)"
length: "20"
time: "Saturday, 15:05"
time_iso: "2026-08-29T13:05:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

As a mapper, we spend hours micro-mapping surface types, tactile paving, complex building geometries or trees. But when you check the map, they are invisible.

Legacy web cartography forces a compromise:
**To keep standard Vector Tiles (MVT) small enough for network transfer, rendering pipelines systematically drop niche tags and simplify geometries**.

MapLibre is now the default vector renderer on the OpenStreetMap front page. Moving from static rasters to interactive vectors is the next step in improving this experience.
To make the front page a true 1:1 reflection of the database, we must eliminate this data-loss.

This talk covers the MapLibre technical roadmap for rendering the complete OSM tag dictionary directly in the browser. We detail the integration of two technologies:
- **MapLibre Tile (MLT)**: A vector data compression specification that reduces bandwidth, allowing the delivery of heavy, unfiltered OSM datasets to the client.
- **WebGPU**: Shifting the computational bottleneck from the CPU to the GPU, enabling browsers to render massive MLT payloads, dynamic styling, and 3D geometries at 60fps.

The presentation features a live, split-screen benchmark using dense data to compare the older raster maps vs legacy MVT/WebGL vs the MLT/WebGPU pipeline.
Attendees will see how upgrading the shared open-source infrastructure is necessary to visualize **every** mapper’s contribution.

