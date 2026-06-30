---
layout: session
title: "From OpenStreetMap APIs to Insightful Data Analysis: Extraction, Analysis, and Mapping with R"
code: "83LBSJ"
speaker_names: ["Louis Laurian"]
affiliations: None
room: "La Réunion"
length: "20"
time: "Friday, 15:05"
time_iso: "2026-08-28T13:05:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

Alongside the enrichment of the OpenStreetMap database over the years, numerous tools have been developed to interact with or to create derivative products: editors, data extraction tools, geocoding services, slippy maps, or routing engines. Most of these tools are accessible via scripting languages through APIs or dedicated libraries. Among these languages, R stands out as a free and open source programming language and software for statistical computing and data visualization. Complemented by more than 23,500 user-contributed packages hosted on the Comprehensive R Archive Network in 2026, the language’s versatility allows users to build unified workflows within an environment conducive to reproducible research. R is widely used for research purposes in many fields beyond statistics, such as biology, social sciences, or geomatics. A subset of its packages forms a robust and mature spatial ecosystem that makes it easy to handle and display spatial data. Consequently, R provides seamless access to various APIs and tools for downloading and filtering OpenStreetMap data, querying shortest routes and itineraries, or generating both static and interactive maps. 

As part of our research activities, we have developed some of the key OpenStreetMap-related R packages. For example, the _osrm_ package has enabled the integration of time-distance calculations in many academic studies by providing a straightforward access to the OSRM routing engine. The package has been widely used in numerous published papers across various disciplines (health, transport, environmental science, or education). Thus, we argue that R enables researchers to efficiently use OpenStreetMap thanks to a unified and reproducible environment and specialized packages.

In this presentation, we first explore a curated selection of R packages designed to interact with the OpenStreetMap database. We begin with packages that download and extract data, such as _osmextract_ and _osmdata_. Then, we explore solutions that interface third party softwares for geocoding (Nominatim with _tidygeocoder_) and routing (OSRM with _osrm_, Valhalla with _valh_). Finally, we address dynamic cartography (using _leaflet_) and creation of static maps from raster tiles (using _maptiles_) or from vector objects (using _maposm_). 

To illustrate the practical application of these tools, we conclude with a short, seamless and fully reproducible example. From the geocoding of an address, to the extraction of amenities or the use of routing engines and till the creation of a publication-ready map, we propose a complete workflow that harness the power of R ecosystem to create insightful analysis from OpenStreetMap data.

