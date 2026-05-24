---
layout: session
title: "Milan to Paris via Dundee: ohsome 2.0 has arrived!"
code: "S9MD3B"
speaker_names: ['Benjamin Herfort']
affiliations: None
room: "Talks II - Amphi Bienvenüe (Bienvenüe)"
length: "20"
time: "Sunday, 12:35"
time_iso: "2026-08-30T10:35:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

The ohsome framework makes OSM data analysis, data quality assessment and data download simple - for community members, researchers and developers. SOTM 2026 marks a fundamental milestone for us as we want to **introduce ohsome-planet** and **release ohsome API v2.0**. During this talk you can get insights about design decisions, new features, common use cases and the road map ahead.

<hr>

What makes the processing and analysis of OSM data at global scale challenging? There are at least three things worth pointing out:

1. Raw OSM data doesn’t come in GIS-ready format. You can’t easily filter for points or polygons or by geographic area. 
2. OSM’s database has massively grown over the past 20 years and as of today the data doesn’t fit on a usual consumer laptop anymore. The OSM planet history .pbf file has about 150 GB. 
3. Third, OSM data is scattered, e.g. latest information about elements, information about edit history and changeset information come from different sources. Often you want to analyze these aspects together.

To tackle these problems, we are developing the ohsome framework for almost 10 years now. And we are still not done yet!

We have introduced the ohsome framework to the wider OSM community at State of the Map 2018 in Milan. At State of the Map Europe 2025 in Dundee we have talked about ohsomeDB, a powerful Postgres database extended with PostGIS and Citus that drastically improves performance for OSM analytics questions. Now, at SOTM 2026 we want to make these resources available for the OSM community by **introducing ohsome-planet** and releasing **ohsome API v2.0**. 

We have developed [ohsome-planet](https://github.com/GIScience/ohsome-planet) in order to transform raw OSM data into a GIS-ready data format, namely Parquet with native Geo support. (Geo)Parquet comes with many advantages when working with very large spatial datasets and has been widely adopted in the GIS-tech domain. ohsome-planet does the processing heavy tasks of building geometries, including complex multipolygon relations, and enables you to join element with changeset information. With ohsome-planet we tackle the first challenge and bring raw OSM data into a GIS-ready format without loosing any detail or metadata. ohsome-planet can be used by anyone and also works with OSM raw data country extracts.

The [ohsome API](https://docs.ohsome.org/ohsome-api/v1/) helps reseachers and community members to analyse and extract OSM data and tackles challenge 2 (data size) and challenge 3 (scattered data sources). You can filter for tags, travel in time and tailor data analysis to your custom defined area-of-interest. As processing happens on the server side (at HeiGIT), you can analyse even large regions (e.g. countries) with a normal laptop. Due to major performance improvements, complex queries, e.g. calculating the proportion of all German roads that have a name tag, now only take a few seconds. With v2.0 you can also filter for changeset information, e.g. hashtags. 

To summarize: In this talk we will describe the ohsome tech stack with a focus on ohsome-planet and ohsome API. We will show an usage of the ohsome API v2.0 to create country data quality reports that inspect various dimensions of data quality such as completeness, currentness and attribute completeness.

If you have used the ohsome API before, there is very likely a need to transition some of your scripts our analysis to the new structure. During the conference, we are very likely organizing a spontaneous / self-organized sessions to assist you with that. SOTM is an important event for us to collect feedback and problem reports from OSM community members and users of ohsome. We are curious to learn more about OSM and what you want to do with the data beyond creating beautiful maps.

