---
layout: session
title: "The Power of quality in OpenStreetMap"
code: "BY7FZ7"
speaker_names: ["François Lacombe", "Marina Petkova", "Tobias Augspurger"]
affiliations: None
room: "Guadeloupe"
length: "20"
time: "Saturday, 17:55"
time_iso: "2026-08-29T15:55:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

As OpenStreetMap becomes more mature and complete, the challenges now lie in ensuring data quality. Mappers may receive customised feedback on their contributions, and data reusers are seeking greater confidence in the information they rely on.

Over the past year, we at [MapYourGrid](https://mapyourgrid.org/) have been working on assessing and improving the quality of power infrastructure data in OpenStreetMap. This work relies on existing quality assurance and monitoring tools, such as [Osmose](https://wiki.openstreetmap.org/wiki/Osmose) and [Podoma](https://wiki.openstreetmap.org/wiki/Podoma), with a quality comparison approach through a new platform, [GridInspector](https://mapyourgrid.dynartio.com/gridinspector.html).

With this talk, we aim to share with the community how we built a coherent quality assurance strategy. We will present our experience combining multiple tools, and show how automation can support continuous monitoring and business-grade consistency testing.
We will also explore what comes next: moving towards a highly automated quality assessment process for power infrastructure data. This includes leveraging Earth observation data and designing human-in-the-loop validation processes to balance automation with local knowledge and mapper expertise.
While intended with power infrastructure data in mind, the methods we present are designed to be broadly used in many fields. Thus this presentation won’t be dedicated to the power infrastructure topic but only use it as an example. In fact, we would love to discuss with the community how these tools and methods can be replicated to other fields (i.e. assessing data quality for waterways or road and urban infrastructures).   

Attendees will leave with practical insights on building a QA strategy, leveraging existing tools more effectively, and designing feedback loops that benefit both contributors and data reusers.

<hr>

Data quality is at the core of the digital age. It drives the value we got out of many fields documented in the OpenStreetMap database. 
Most volunteers pursue high quality contributions in order to accomplish great rendering. However, data quality remains a subjective topic.

Scientific work has already been done on the matter and established norms now define appropriate frameworks to assess data quality, particularly when it comes to geographical data.
OpenStreetMap has the opportunity to build on these foundations and improve its own set of quality assessment tools to serve its community and to be taken as an example for a more global vision.
It all started from a practical need: when collaborating, contributors need meaningful feedback to improve their mapping. It then expands with the need to encourage more people to join the effort and drive them with common practice. It's also a matter of building trust for reusers who may rely on data they do not fully understand.

The time has come to create our own definition of quality and what matters in our respective fields. So what does quality actually mean in OpenStreetMap? 
Is this about completeness? Consistency? Or maybe accuracy? Could it be all of this at the same time?

The ecosystem already includes well known and used software:

- [Osmose QA](https://wiki.openstreetmap.org/wiki/Osmose)
- [Clearance](https://wiki.openstreetmap.org/wiki/Clearance)
- Editors validation rulesets

And it could also include more recent attempts you may have heard about:

- [Podoma](https://wiki.openstreetmap.org/wiki/Podoma)
- [GridInspector](https://mapyourgrid.dynartio.com/gridinspector.html)
- Many external software consuming OpenStreetMap data

Those tools may suffer from lack of maintenance, visibility, or integration, and could benefit from renewed interest and coordination around quality monitoring. 

But quality tooling is not enough if it’s not properly used and understood. It's also about strategies, insights and shared practices between members of the community.

Building on our experience at MapYourGrid, we want to share a practical vision of what quality monitoring can look like. 
We will use concrete situations we faced and explain what value came from monitoring and automating problem detection.

Here are the points we will make:

- Explain what quality topics we focus on
- Describe what situations we faced with concrete situations from MapYourGrid
- Quantify what value came out of monitoring and automated problem detection at world scale
- Spot what features are currently missing in our common tools
- Explore solutions and set resources to get them included in the future

We welcome anyone who shares the same concern about quality in their own field and we are confident we could find the appropriate path together.

