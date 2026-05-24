---
layout: session
title: "Sneaking in OSM data into a big old company"
code: "K8XYAN"
speaker_names: ['Céline DURUPT', 'Tristram']
affiliations: None
room: "Talks III - Amphi Cauchy (Carnot)"
length: "20"
time: "Friday, 11:15"
time_iso: "2026-08-28T09:15:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

SNCF Réseau is the railway infrastructure manager of France. Culturally in this big (53 000 employees), old (founded in 1938 to nationalize pre-existing railway companies) company, geographic and open data is little well known nor used. 
We replaced outdated internal data with OpenStreetMap’s railway track data (and not only as a base layer!). In this talk, we will tell you how we pulled this off.

<hr>

Our strategy was to very gradually expose our users to OpenStreetMap data, to convince them of its quality. First in cartographic layers without interaction with our data, then by replacing missing data in our internal database, and eventually by fully replacing it as a geographical data source.
We contributed to OSM’s railway tracks data in France (which was already in a very high quality thanks to OSM’s community) and use the Clearance tool to monitor its quality.
We use this railway track data in libLRS and OSRD, two open-source projects developed by SNCF Réseau that need geographic representation of railway infrastructure.
To compensate for the current lack of open data describing railway signals and stations, we also developed a tool that, based on OSM data, fills in the gaps automatically with realistic objects and allows our projects to run in a demonstration environment in any place of the world.
Our next step is to convince other projects inside the company to use this data source and contribute to enhance it!

