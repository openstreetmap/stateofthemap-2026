---
layout: session
title: "When Maps Mislead: Lessons from Outdoor Navigation with OpenStreetMap"
code: "VUYNMB"
speaker_names: ['Jakub Zmrzlik']
affiliations: None
room: "Talks II - Amphi Bienvenüe (Bienvenüe)"
length: "20"
time: "Saturday, 15:40"
time_iso: "2026-08-29T13:40:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

Mapy.com is a widely used mapping application with a strong focus on hiking and cycling, used daily by millions of people.

It is built largely on OpenStreetMap — but using OSM in a real product at this scale quickly shows that the data is not always complete, consistent, or ready to use as-is.

In this talk, I will share what we have learned while running Mapy.com in production. Not an introduction to the product, but practical experience: what works well, what causes problems, and what we had to change or interpret to make the data usable for everyday outdoor navigation.

A key part is understanding what a good outdoor map actually needs. For us, that means things like a complete network of marked hiking and cycling routes, usable terrain information, and details that help people orient themselves in real conditions. When parts of this are missing or inconsistent, the result can be routes that look fine on the map but don’t work well in reality. In practice, the biggest challenge is often not incorrect data, but missing connections and incomplete route networks, combined with strong regional differences in data quality.

We see this in practice — situations where navigation leads people into terrain they are not prepared for are not rare, and they show how important data quality really is.

We will also look at attributes like surface and difficulty, access restrictions, and seasonal limitations, which are often critical for deciding whether a route is actually suitable. I will also touch on overtourism and how maps can better reflect real-world constraints instead of just showing everything that exists.

Finally, I will share how this experience feeds back into OpenStreetMap — what we contribute, where we still see gaps, and where better cooperation between companies and the community could help.

This talk is for anyone interested in how OpenStreetMap is actually used in practice, especially beyond the “it works on the map” level.

<hr>

This talk builds on practical experience from running a large-scale outdoor mapping application based on OpenStreetMap.

In addition to the topics mentioned in the abstract, the presentation will include concrete examples of how OSM data is processed and adapted for real-world use. This includes handling incomplete route networks, dealing with inconsistent tagging across regions, and making cartographic decisions where the data is ambiguous or missing.

A specific focus will be on outdoor use cases such as hiking and cycling, where data quality has a direct impact on user safety and decision-making. Examples will include routing across fragmented trail networks, interpreting terrain and surface information, and dealing with missing or unreliable difficulty classifications.

The talk will also highlight how different regions vary significantly in data completeness and quality, and how this affects both rendering and routing. This leads to practical questions such as when to trust the data, when to apply heuristics, and when to fall back to alternative approaches.

Another important aspect is how map data reflects real-world constraints, including access restrictions, seasonal closures, and protected areas. These factors are increasingly relevant in the context of overtourism and responsible outdoor navigation.

Finally, the presentation will include examples of how these challenges are communicated back to the OpenStreetMap community, including contributions, feedback loops, and areas where better data models or tagging practices could improve usability.

The goal of the talk is to provide a realistic view of using OpenStreetMap in production, especially in demanding outdoor scenarios, and to encourage discussion about how the ecosystem can evolve to better support these use cases.

