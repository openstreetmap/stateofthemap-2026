---
layout: session
title: "OSM Skeleton: Completing the Backbone of OSM Data"
code: "8SKDAR"
speaker_names: ['Séverin Ménard']
affiliations: None
room: "Talks IV/Workshops II/BoF III - Amphi Picard or Navier (Carnot)"
length: "20"
time: "Saturday, 09:30"
time_iso: "2026-08-29T07:30:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

This presentation introduces a new step-by-step approach that aims at helping to fix the incompleteness and heterogeneity of the OSM data. 
It first focuses on the OSM features that comprise the backbone of homogeneous OpenStreetMap data, before broadening the perspective to include other objects: the nodes representing settlements, the main road connecting them to the main road network, as well as the residential area showing the extent of the settlement.
The OSM Skeleton project aims to identify all missing, inaccurate, incomplete, or obsolete objects in the OSM data backbone in order to resolve inconsistencies. OSM Skeleton uses external data to identify the missing features and performs spatial analysis, crossed features and various metrics to analyze incompleteness and heterogeneity. For instance, the approach introduces a hybrid analytic feature that combines residential and street network areas. 
Each type of issue, whether confirmed or potential, is represented by a specific layer at national scale and can be resolved by clicking to access the relevant area in an OSM editor to modify the existing OSM data using the available imagery. The most significant issues are displayed at all scales, while minor ones are displayed at higher zoom levels.
All the issues can be processed by a click giving access to a webpage providing mapping instructions and buttons to open the area in either JOSM or iD. Forecasting next mapping steps involving field mapping, the OSM Skeleton approach also performs an analysis of the completeness of points of interest (POIs) for cities and towns. 
Initially developed in two regions of Africa and South America, the methodology reveals regional or national patterns, highlighting significant contrasts between regions and between small towns with the same region. Daily updated statistics categorized by issue or first-level administrative division provide a complete overview of the issues at hand. 
Technically, the OSM Skeleton approach uses standard PostgreSQL-generated Open Geospatial Consortium (OGC) layers. These layers can be used on ready online maps provided by a spatial data infrastructure (SDI) or in any OGC-compatible client. All layers can be downloaded natively in various GIS formats. Rather than relying on remote mapping, OSM Skeleton aims to expand local OSM activities, including imagery and field mapping, as well as the local promotion of enhanced, complete OSM data.

<hr>

OpenStreetMap relies on a wide variety of contributions in terms of mapped themes, covered areas, and completeness levels. This flexibility is key to its richness and success. However, it also generates a high degree of data heterogeneity and incompleteness, which is often cited by its detractors or those seeking to minimize its value.
Some services, such as dashboard.ohsome.org and github.com/hotosm/osm-analytics, have attempted to address these concerns about heterogeneity and incompleteness, but they seem to have been discontinued.  Although there are projects aimed at validating OSM data, such as Osmose, MapRoulette and OSMCha, none of them has succeeded in resolving these issues or is truly committed to doing so.
This presentation introduces a new step-by-step approach that first focuses on the OSM features that comprise the backbone of homogeneous OpenStreetMap data, before broadening the perspective to include other objects: the nodes representing settlements, the main road connecting them to the main road network, as well as the residential area showing the extent of the settlement.
The OSM Skeleton project aims to identify all missing, inaccurate, incomplete, or obsolete objects in the OSM data backbone in order to resolve inconsistencies. OSM Skeleton uses external data to identify the missing features and performs spatial analysis, crossed features and various metrics to analyze incompleteness and heterogeneity. For instance, the approach introduces a hybrid analytic feature that combines residential and street network areas. 
Each type of issue, whether confirmed or potential, is represented by a specific layer at national scale and can be resolved by clicking to access the relevant area in an OSM editor to modify the existing OSM data using the available imagery. The most significant issues are displayed at all scales, while minor ones are displayed at higher zoom levels.
All the issues can be processed by a click giving access to a webpage providing mapping instructions and buttons to open the area in either JOSM or iD. Initially developed in two regions of Africa and South America, the methodology reveals regional or national patterns, highlighting significant contrasts between regions and between small towns with the same region. Daily updated statistics categorized by issue or first-level administrative division provide a complete overview of the issues at hand. 
Forecasting next mapping steps involving field mapping, the OSM Skeleton approach also performs an analysis of the completeness of points of interest (POIs) for cities and towns. It provides both a category (e.g., health, education, other amenities, shops, offices) an a global score. This analysis also reveals significant differences between cities and towns, and can easily be used to organize mapping activities that focus on the least mapped cities and towns. 
Technically, the OSM Skeleton approach does not use a dedicated backend served by a separate web service on the front-end. Instead, analyses are automatically produced in PostgreSQL and made available as WMS/WFS layers. These analyses are shared as thematic maps by country via a spatial data infrastructure (SDI) based on geOrchestra.  However, they can also natively be used in any Open Geospatial Consortium (OGC) client (such as QGIS) or downloaded in various geographic information system (GIS) formats. Providing this information on a smartphone is also planned.
Beyond its technical aspects, the OSM Skeleton approach aims not to rely on remote mappers but to serve as an opportunity to expand local OSM activities, by involving local OSM contributors as much as possible. This involves not only the mapping activities, but also promoting locally enhanced, more homogeneous OSM data, which could leverage previous field mapping projects coordinated by Les Libres Géographes. Identifying potential mappers for the field mapping activities is an interesting challenge that would require defining new recruitment approaches.
The presentation will cover the various aspects of the approach and demonstrate different analysis layers, heterogeneity contexts, and a complete workflow.

Note for French participants: je peux refaire la présentation en français dans une session Birds of feathers si certaines personnes sont intéressées.

