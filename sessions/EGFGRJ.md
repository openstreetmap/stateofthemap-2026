---
layout: session
title: "GeoDesk: The OpenStreetMap toolkit that's fast, easy and fun"
code: "EGFGRJ"
speaker_names: ["Martin"]
affiliations: None
room: "Tahiti"
length: "20"
time: "Sunday, 12:35"
time_iso: "2026-08-30T10:35:00Z"
resources: []
recording: False
prerecorded: False
language: en
---

The world is big. So is the global OpenStreetMap dataset -- and it's growing bigger each day. This is great, of course, since OSM is becoming ever more complete and detailed. But working with this data volume requires high-end hardware, SQL skills, and ample patience.

GeoDesk takes a novel approach, with a database engine designed specifically for OSM data, with orders-of-magnitude improvements in import times, storage requirements and query speed. The software is 100% free and open-source and runs on Windows, Linux and macOS, with modest hardware requirements.

In this talk, I'll cover the basics of the GeoDesk workflows: how to import OSM data and perform basic queries using the command line, and export results in various formats. I will also give an introduction to the three GeoDesk SDKs for Python, Java, and C++. These toolkits allow more sophisticated spatial queries and can be integrated with other popular libraries (e.g. JTS, Shapely, and GEOS) to build full-fledged geospatial applications.

Finally, I will briefly outline the project roadmap for the 3.0 release coming this fall.

<hr>

This talk is split into 4 parts:

## Introduction and general concepts

Here, we'll cover [Geo-Object Libraries](https://wiki.openstreetmap.org/wiki/Geo-Object_Library), the single-file database format behind GeoDesk: how it is structured; what makes it so efficient; how it stores nodes, ways, and relations; how it handles areas. Also a quick refresher on map projections, with a focus on the Mercator variant used by GOLs.

## The GOL Tool

The [GOL Tool](https://docs.geodesk.com/gol) is a cross-platform command-line application. I'll show how to create a GOL from a planet file (or extract in OSM-PBF format); how to download ready-made GOLs; and how to run basic queries and visualize their results.

## Toolkit basics

I'll cover how to work with features, geometries and query result sets, with short examples from the [GeoDesk Python toolkit](https://docs.geodesk.com/python). I'll show how to perform various tag-based and spatial queries, how to convert between different projections, and how to perform advanced geometric operations.

## Advanced toolkit features / roadmap

I'll give a brief intro to the Java and C++ toolkits. I'll also outline what's coming in Version 3.0.

Instead of a live demo, I'll use annotated slides showing detailed inputs and outputs. The purpose of the talk is to give attendees enough background to explore the examples at their leisure, based on the documentation at docs.geodesk.com.

For more information, please see www.geodesk.com or follow @geodesk@en.osm.town.

