---
layout: session
title: "CoMaps - How to make a community-based map &amp; navigation app based on OpenStreetMap"
code: "DDJRVU"
speaker_names: ['Bastian Greshake Tzovaras']
affiliations: None
room: "Talks II - Amphi Bienvenüe (Bienvenüe)"
length: "20"
time: "Friday, 16:45"
time_iso: "2026-08-28T14:45:00Z"
resources: [{ description: "Code repository", url: "https://codeberg.org/comaps/comaps" },{ description: "CoMaps website", url: "https://www.comaps.app/" }]
recording: True
prerecorded: False
language: en
---

CoMaps started in May 2025 as a fork of Organic Maps, with the goal of providing digital maps and navigation tools that are 100% open source and transparently made by and for community. Since then, the community has shipped ~2 updated app versions per month. Among other things, those have improved core features, made the app more international, expanded the integration with the OSM ecosystem and reduced the existence of single points of failures in the provisioning of the app. Here, we share some of updates, how CoMaps is governed and how you can get involved.

<hr>

CoMaps is a project that creates digital map applications that exists for Android, iOS and Linux and is based on a wide range of open data commons, which of course includes OpenStreetMap - but also other allied projects such as Wikipedia, Wikimedia Commons, and Panoramax. The project is focused on providing tools that center on respecting people’s privacy and on being able to use use its features offline. As of April 2026, around 11 months after the project started, the CoMaps community consists of around 50 contributors who have helped the development of CoMaps, &gt;250 translators who are working on providing the project in ~80 languages, and thousands of engaged users who provide feedback, support, feature ideas and more via various channels, from the Codeberg software forge over various language-specific Matrix channels to Mastodon and other social media channels.

Collectively, the community’s goal is to ensure that the projects remains free and open source software. To that end, CoMaps has been actively working on how to implement collective approaches for collective decision making and governance, as well as on improving the CoMaps application and the backend infrastructure, to ensure that the CoMaps contributor community does not become a single point of failure or bottleneck.

In its collective decision making, CoMaps has been experimenting with how to implement different methods since its initial announcement. The project’s name, color scheme and logo were each decided in a collaborative process, in which people could add their suggestions and where the final outputs were selected in an open voting scheme after several rounds of refinements (and which nevertheless did **not** result in the name _Mappy McMapFace_!). In a similar way, the CoMaps contributor community continues to work together in order to refine and improve its decision making processes and collective goal setting, through an ongoing dialogue that focuses on finding consensus where possible, using voting as a last resort. Through this, the project already adopted guidelines for the (in)acceptable use of artificial intelligence within the project and refined its mission statement, to help outline the broad development direction.

The project takes a similar collaborative approach to provisioning and maintaining its infrastructure: To ensure that CoMaps users can quickly download maps for offline use, the project runs a small content delivery network, consisting of currently 6 servers around the globe, half of which are donated “in kind” by contributors, including the French OpenStreetMap chapter. These donated servers are complemented by rented hardware, which are also used for creating the custom map files that CoMaps uses and that combine data from OpenStreetMap, Wikipedia and other openly licensed data sources. This is made possible thanks to the generous donations from people around the globe. Following CoMaps commitment to transparency, all income and expenses can be viewed on the project’s OpenCollective page. So far, the project exclusively uses donations for paying for infrastructure (servers, domains, …) or smaller expenses like ordering stickers to share at conferences like SotM or FOSDEM, while all contributions are made by unpaid volunteers, from software development and design , over support, to outreach and community engagement.

On a technological level, the CoMaps project has been implementing a range of new features. Among those are an improved routing engine, expanded integrations for more languages (including offline Wikipedia articles, support for right-to-left languages), and expanding the POI pages to include data such as links to Panoramax and displaying the “last checked” dates from OSM. To make CoMaps an even better citizen of the OSM ecosystem, the integrated editor for OSM has also been expanded to support a wider range of objects. As part of the project’s dedication to avoid reliance on external infrastructure, CoMaps also supports the self-hosting of the map files since December 2025, instead of exclusively relying on CoMaps’ own content delivery network. This additionally allows supporting new use cases, for example the local serving of map files in regions without internet connection, for example in the field in disaster situations or humanitarian deployments.

In this talk, we aim to showcase these social and community aspects of how CoMaps has grown, continues to work as a collaborative project today, as well as dive into some of those technical details of how CoMaps has already improved since its first release in 2025, and showcase how those changes came to be. Furthermore, we will give an idea of some of the larger pieces of work that are currently ongoing to improve CoMaps and make it even more useful for a wide range of users, including the work on large feature ideas such as real-time traffic and public transit integrations. Lastly, we want to invite people to join us in co-developing CoMaps, ensuring that it continues growing into a serious alternative for commercial map and navigation applications.

