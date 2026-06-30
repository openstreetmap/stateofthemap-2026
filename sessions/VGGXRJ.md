---
layout: session
title: "Clearance: Quality Proxy for OSM Replication. The Roadmap up to v1.0"
code: "VGGXRJ"
speaker_names: ["Frédéric Rodrigo"]
affiliations: None
room: "Guadeloupe"
length: "20"
time: "Saturday, 16:45"
time_iso: "2026-08-29T14:45:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

Clearance is an open-source quality-control proxy for OpenStreetMap replication. Rather than letting every changeset flow directly into downstream systems, it holds suspicious or potentially breaking changes for review while keeping compliant data flowing continuously. It acts as a standard OSM data source, providing PBF extracts, diffs and an Overpass API compatible endpoint of the filtered local copy. It is already used by over 40 organizations, including emergency services in Navarre, Spain, and is under review by the French railway infrastructure company SNCF Réseau and Belgian crisis services.
This talk will cover the last year's improvements and the roadmap up to version 1.0, including features funded by the NLnet/NGI0 project. It will focus on:
    • multi-object conflation; 
    • diff rearrangement to allow partial validation while keeping data coherence; 
    • change detection in network continuity to avoid breaks or false connections, such as in road networks or power grids.

