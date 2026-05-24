---
layout: session
title: "OpenStreetMap on Board: How We Fit Europe into 700 High-Speed Trains"
code: "TV9DUV"
speaker_names: ['Benjamin Demonet']
affiliations: None
room: "Talks III - Amphi Cauchy (Carnot)"
length: "20"
time: "Friday, 12:25"
time_iso: "2026-08-28T10:25:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

How do you deliver smooth, detailed mapping to millions of passengers aboard French TGV trains while working within tight storage and server resource constraints? This talk traces the journey of renewing the mapping system for the WiFi portal on board the TGV fleet (700 train sets).

We will explain our choice of PMTiles technology to move to vector tiles without relying on a heavy cartographic server. We will share our research into data size optimization — from studying the impact of building footprints to managing zoom levels — and walk through the trade-offs required to ship a complete European base map on board. Finally, we will cover the specific work done on railway data (routes, diversion paths) and the custom design created to give passengers an immersive experience at 300 km/h.

<hr>

1. The Context: An On-Board Server Under Constraints

   The TGV WiFi portal runs on an embedded server with shared resources.
   - The challenge: No dedicated cartographic server — we needed an ultra-lightweight &#34;static&#34; solution.
   - The constraint: Limited disk space to store data covering all of Europe, requiring careful thought about the size of every feature.

2. The Technical Solution: PMTiles and a Lightweight Architecture

   Why PMTiles (Protomaps)?
   - Direct file reading with no complex cartographic backend.
   - Easy deployment and updates across 700 independent train sets.

3. Size Study: Balancing Richness and Lightness

   This is the heart of our experience report. We ran extensive tests to reduce the size of the European file:
   - The weight of buildings: Analysis of the savings achieved by removing building footprints (which account for the majority of vector layer file size).
   - Zoom level management: How far down can we go without losing value for the passenger?
   - The final decision: Why, despite our reduction tests, we ultimately chose to keep buildings and high zoom levels to prioritize user experience — and how we optimized everything else.

4. Making the Most of Railway Data

   A TGV map should, above all, speak the language of rail. We integrated specific datasets:
   - Railway data file: A focus on rail infrastructure sourced from OSM.
   - Full TGV route coverage: Integration of high-speed lines as well as conventional lines and diversion routes for incident management.

5. Design and Outlook

   - Custom styles: Three bespoke styles developed in line with the client's visual identity guidelines.
   - 3D exploration: A presentation of our exploratory work to integrate 3D rendering into the on-board map display.

