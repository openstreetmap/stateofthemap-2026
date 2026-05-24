---
layout: session
title: "Emergency Services using OpenStreetMap in Germany"
code: "3GRKKJ"
speaker_names: ['dadavid']
affiliations: None
room: "Talks I / Opening - Amphi Caquot (Coriolis)"
length: "40"
time: "Friday, 14:30"
time_iso: "2026-08-28T12:30:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

OpenStreetMap is widely used throughout the emergeny services - but this is not well known in the broader OSM community. In this talk, firefighters and emergency service practicioners will give an overview of how they use and contribute to OSM. 

We'll show all scales of OSM integration, from grass roots activities like hydrant mapping to full scale adoption by the entire department for planning, dispatch and emergency vehicle routing.

<hr>

Most mappers know that the data they add to OSM is occasionally used by emergency services, and this can be very motivating for some. But just how common is OpenStreetMap in the fire and ambulance services? Very! In fact, there aren't many control rooms that _don't_ use OSM, be it just as a background map or even for geocoding, dispatch, and routing. 

We will walk the audience through an incident and highlight how OSM is used at each stage. This example shows the maximum integeration of OSM, which is already state-of-the-art in some departments, but of course not in all ≈250 fire and ambulance control rooms in Germany. 

Starting with the 112 emergency call, geocoding software helps the dispatcher locate the caller by the addresses and POIs that they reference. OSM's strength here is the POI data as well as `old_name` and `loc_name`, important parts of how callers describe where they are but data that is missing from the usual government sources. Locating the caller is the first and often most difficult step of the call, but it is getting easier with the advent of AML. 
In the next step, a suitable vehicle is selected by routing ETE and then dispatched and routed to the incident. Routing emergency vehicles with lights and sirens is not a trivial task, and commercially available routing graphs lack the ability for customization. OSM is a great road network source here as routing engines can take into account that access, turn restrictions, speed limits and weight limits need to be interpreted differently. Also, we can't avoid traffic jams as the incidents we respond to are usually the ones that created the congestion in the first place.
At the scene, many ambulance crews then use OSM to find the exact housenumber and the entrance of a building and fire crews check the location and dimensions of fire hydrants. 

We are a group of emergency service practicioners, mostly from the control room, emergency vehicle routing, and demand planning side of the fire and ambulance services. In this talk, we want to show the other members of the community how we use OSM in our professional and personal lives and how we approach editing and quality assurance.

