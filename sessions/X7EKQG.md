---
peertube: https://peertube.openstreetmap.fr/videos/watch/e904f5b4-20e4-4aff-a9ce-125759b1f998
layout: session
title: "Reviewing OSM Changes Before Integration: Introducing LeBonTag"
code: "X7EKQG"
speaker_names: ["Bruno Béguin", "Mathieu Ambrosy"]
affiliations: None
room: "La Réunion"
length: "20"
time: "Saturday, 09:30"
time_iso: "2026-08-29T07:30:00Z"
resources: [{ description: "Slides (PDF)", url: "https://pretalx.com/media/sotm2026/submissions/X7EKQG/resources/SOTM2026-LeBonTag_TunjURh.pdf" },{ description: "LeBonTag Documentation", url: "https://documentation.lebontag.fr/" },{ description: "LeBonTag Git", url: "https://gitlab.com/Geonov/lebontag-v2" },{ description: "Geonov Website", url: "https://www.geonov.fr/" },{ description: "LeBonTag Website", url: "https://www.lebontag.fr/" }]
recording: True
prerecorded: False
language: en
---

LeBonTag is an open-source web application that allows organizations to review OpenStreetMap changes before integrating them into their own datasets.

Originally initiated by Montpellier Méditerranée Métropole to support its internal data workflows, LeBonTag enables a human-in-the-loop process to monitor, inspect, and validate OSM edits before integration.

<hr>

OpenStreetMap is increasingly used as a data source in operational contexts. However, directly integrating upstream changes into downstream databases can lead to inconsistencies or unwanted modifications.

LeBonTag is an open-source tool designed to introduce a validation step between OpenStreetMap and external systems. It was initially developed in collaboration with Montpellier Méditerranée Métropole, which needed a way to safely integrate OSM data into its internal workflows.

Instead of automatically importing changes, users can review and decide which edits should be accepted.

In this talk, we will present:

- The problem of uncontrolled OSM data integration
- How LeBonTag allows users to visualize and review OSM changes
- The validation workflow: inspecting objects, accepting or rejecting edits
- An overview of additional modules, such as a data quality module used to check tags, geometry, or consistency on OSM objects
- Feedback and lessons learned from real-world usage

LeBonTag is designed as a modular platform, where different tools can support various needs around OSM data. Other modules, such as statistics or analysis tools, can be developed within the same framework.
Other local french administrations have participated to the improvement of the software (Brest, FireDpt Hérault, Paris, Clermont).

This session focuses on a practical approach to working with
OpenStreetMap: combining automation and human validation to ensure data quality and consistency before integration.

**Key takeaways**

- Why reviewing OSM changes before integration can be important
- How to implement a human-in-the-loop validation workflow
- How modular tools can support different OSM data use cases
- Practical insights from building and using a real-world tool

