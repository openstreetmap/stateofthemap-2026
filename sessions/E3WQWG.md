---
layout: session
title: "A Swiss Army knife for geographical data voxelization"
code: "E3WQWG"
speaker_names: ['Pierre-Yves Rollo', 'Théo SZANTO']
affiliations: None
room: "Talks II - Amphi Bienvenüe (Bienvenüe)"
length: "20"
time: "Saturday, 11:15"
time_iso: "2026-08-29T09:15:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

Over 10 years ago, the French Institute of Geographic Information (IGN) created &#34;Minecraft on demand&#34;, a web service that uses real geographical data to build playable worlds for voxel games such as Minecraft (worlds made of small unit cubes). After 135,000 voxel world generations, including more than 6,000 from OSM data, the service turned out to be limited, missing flexibility and using only a small fraction of OSM data. The institute capitalized on its experience to design a new standalone and flexible tool able to exploit the full richness of OSM data and much more.

As many generation constraints as possible have been removed. For instance, size of created world is only limited by game format and not anymore by memory size. The extremely high configurability makes this tool very versatile. Decisions are driven by the user’s creativity and not by the software. All the tasks, ranging from data loading, processing, all the way to rendering are described through a human readable configuration file, so that even non-programmers can easily fine-tune their pipeline. This new tool can be seen as the &#34;Swiss Army knife&#34; of geographical data voxelization (conversion of data into voxel worlds).

The tool is open source, modular and can be extended with Java modules. It paves the way for new community-maintained features, such as support for new geographical data formats, processing algorithms, or voxel formats. Consequently, the tool has the potential to natively manipulate any type of data (vector, raster, point cloud...) originating from any provider (OSM Overpass, OGC WFS/WMS, local files...), process it in various ways, and create any voxel-based format as a result (Luanti, Minecraft, Lego...). For instance, it is possible to create a Luanti world with terrain elevation imported from OpenDEM, and any feature from OSM (road network, buildings, land use...).
 
While most of the existing tools are focused on &#34;fun&#34; or educational usages, this one makes no assumption about the user's intent, and can be used for any purpose, including:
- Immersive exploration (e.g. for citizen participation)
- Rebuild in context (e.g. of a monument)
- Thematic rendering (e.g. based on a tag such as restaurant's cuisine)
- Mixing/custom sources (e.g. with local files)
- And many more to discover!

<hr>

During our presentation, we will showcase the versatility and potential of our new tool.

After providing context on our project, we will present a quick state of the art of existing geodata voxelization tools (Arnis, VoxelEarth…), their limits, and how our contribution overcomes them. We will show examples of generated worlds, the corresponding pipeline configuration, and the impact of the user’s choices on the worlds. Consequently, we will illustrate the potential of our new tool through new possible usages and applications, and will finally, conclude by presenting the next key steps of the project.

The examples we will show include:
- A complete pipeline fetching some features from OSM using Overpass and rendering them in Luanti (free and open-source voxel game engine)
- Modifying the rendering of a feature
- Adding a new data source from local file
- Changing the processing of a feature
- Changing the output format to make a Minecraft world instead
- Moving the area into another country
- Another pipeline mixing several data sources (both local and from multiple providers)

We choose to present at the State of the Map 2026 event for multiple reasons. First and most obvious, our tool can handle OSM data, making it logical to introduce it to the OSM community. Second, we believe that the &#34;open&#34; philosophy we have in mind for this tool (released under the AGPL license) matches well with the spirit of the OSM community. Last, the timing of this event is particularly well aligned with our project's timeline, and we believe that the timing is perfect time for the community members interested in this topic to join us!

