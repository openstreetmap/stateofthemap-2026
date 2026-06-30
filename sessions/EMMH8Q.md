---
layout: session
title: "Sourdough and Layercake: removing technical barriers to using OSM data for cartography and analysis"
code: "EMMH8Q"
speaker_names: ["Jake Low"]
affiliations: None
room: "Guadeloupe"
length: "20"
time: "Friday, 17:20"
time_iso: "2026-08-28T15:20:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

This talk presents two projects: Sourdough (a new vector tile schema) and Layercake (thematic extracts of OSM data in cloud-native formats). These projects serve different audiences but have similar design goals: to make it easier for people to use OSM data, reduce accidental complexity in data consumers' workflows, and strengthen feedback loops between OSM data users and the mapping community. I will discuss these design goals in depth, along with the technical decisions each project makes in pursuit of them, and conclude with announcements about new features and future roadmaps for both projects.

<hr>

OpenStreetMap's flexible data model is one of the project's greatest strengths, but it's also a barrier to using OSM data. Converting raw OSM data into forms suitable for displaying a map or analyzing with traditional GIS software typically requires writing code, using specialized tools, and having a deep understanding of OSM's nodes/ways/relations data model and tagging conventions.

Sourdough and Layercake are two projects I created with the goal of making OSM data easier to use.

- **Sourdough** is a vector tile schema that organizes OSM data into tile layers that directly reflect OSM's tagging conventions, and includes as much data from OSM as possible to support a wide range of cartographic use cases
- **Layercake** is thematic extracts (buildings, roads, etc) of OSM data in cloud-native file formats, ready to use in software like DuckDB and QGIS

These two projects serve different audiences, but share a common design philosophy: convert OSM data into ready-to-use formats while staying faithful to OSM's taxonomy and tagging conventions. Doing so reduces accidental complexity for downstream users, while avoiding the creation of new, leaky abstractions. It also creates a strong feedback channel that helps highlight gaps or inconsistencies in OSM's tagging practices so that we as a community can improve it.

This talk will showcase both projects, discuss the technical decisions that they make in pursuit of these goals, and conclude with announcements about new features and future roadmaps for both.

