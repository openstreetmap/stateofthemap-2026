---
layout: session
title: "Handling Temporary Closures in OpenStreetMap"
code: "RU3UY3"
speaker_names: ['Matteo']
affiliations: None
room: "Talks I / Opening - Amphi Caquot (Coriolis)"
length: "20"
time: "Sunday, 12:35"
time_iso: "2026-08-30T10:35:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

Temporary closures of paths and roads are common in real-world environments, particularly in hiking regions and protected landscapes. However, representing these changes in OpenStreetMap remains challenging. While OSM provides tagging mechanisms such as access restrictions and conditional tags, their use for temporary closures is inconsistent, and their interpretation by routing engines and map applications varies widely.

This talk presents the results of a thesis investigating how temporary closures can be effectively handled within the OSM ecosystem. It introduces a structured approach for modelling different types of closures using existing OSM tags and defines practical decision rules for their application. The talk further examines how these tagging strategies are interpreted by routing engines and demonstrates their impact on routing results under different scenarios.

In addition, the talk presents a prototype workflow for integrating closure information into a dynamically updated mapping service and discusses visualization strategies for communicating closures clearly.

The results provide practical recommendations for improving the representation of temporary closures in OSM and highlight current limitations in handling time-dependent data.

<hr>

Temporary closures are a common part of the real world: a hiking trail blocked due to rockfall, a road closed for construction, or a path restricted for environmental protection. Yet in OpenStreetMap (OSM), these situations are often missing, inconsistently mapped, or not properly interpreted by routing engines. As a result, users may be guided along routes that are no longer accessible.

This talk presents the results of a master’s thesis on how temporary closures can be better handled in the OSM ecosystem. It looks at three key aspects: tagging, visualization, and routing. First, it explores how different types of closures, such as time-limited, mode-specific, or partial restrictions, can be represented using existing OSM tags. Based on this, a set of practical guidelines is proposed to help mappers decide how to tag closures in different situations.

The talk then shows how these closures can be visualized clearly in maps, and how they affect routing in practice. Using a prototype workflow, it demonstrates how closure information can be integrated into a dynamically updated mapping service and highlights where current tools fall short.

The goal is to provide practical insights for both contributors and developers, and to contribute to the broader discussion of how OSM can better handle time-dependent, changing information.

