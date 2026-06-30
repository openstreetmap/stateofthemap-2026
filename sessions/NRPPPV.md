---
layout: session
title: "Where are my ways?"
code: "NRPPPV"
speaker_names: ["Michael Reichert"]
affiliations: None
room: "La Réunion"
length: "20"
time: "Sunday, 09:30"
time_iso: "2026-08-30T07:30:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

The talk will present the web application *Where are my ways?*. It shows all deleted ways in their last visible version on the OpenStreetMap database. The talk will focus on the challenges raised by the OpenStreetMap data model and show how vandals can still evade such a tool. It will also present findings about the different types of deletions.

<hr>

OpenStreetMap data has become the source for map data for outdoor activities. Hikers and cyclists sometimes use private tracks and paths or ways where they are not welcome. Some land owners or authorities delete those tracks and paths instead of adding proper access or lifecycle tags. Many deletions are reverted but some are overseen.

Overpass Attic queries are the only soultion for end users and limited to a certain point of time in the past. In addition, overpass-api.de is overloaded.

Living in a region where almost all tracks and paths seem to be mapped, the author wondered what was mapped. In order to visit these locations and check a few of them, he developed a tool to find all deleted ways in a certain region of interest.

This talk will present *[Where are my ways?](https://michreichert.de/projects/wamy/)* It consists of a preprocessing toolchain and a map application showing all deleted OpenStreetMap ways as they appeard before their deletion.

Nodes and ways have independent histories in the OpenStreetMap data model. Modifying a node does not cause a way to get a new version. Merging ways is a deletion of one way from technical point of view. These challenges will by explained in the talk.

The talk will also present findings about the different types of deletions which have happened in OpenStreetMap.

The application is free software and available on [Codeberg](https://codeberg.org/nakaner/deleted-map).

