---
layout: session
title: "Creating maps for the outdoors community in France: successes and challenges"
code: "QJJS3X"
speaker_names: ["StC"]
affiliations: None
room: "La Réunion"
length: "20"
time: "Saturday, 10:05"
time_iso: "2026-08-29T08:05:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

The Outdoors Group in France has a selfish purpose: help create OSM-based maps that we and our fellow outdoors practitioners and professionals can safely use to plan and carry out our favorite activities.  We are end users, originally mostly hikers and mountain bikers, who came to OSM to create better maps and who discovered on the way that this will require other classes of end users to adopt OSM or at least find their way around it: route operators, tourism offices, land managers, mountain rescue services, etc.

This talk reports on our collective successes and remaining challenges  in turning OSM-based maps into reliable and safe maps for outdoors activities in France and onboarding other end-users. Successes include going from zero to 30.000 km of node networks in a few years, maintaining route continuity above 90% on ~200.000 km of hiking routes, and starting collaborations with a few route operators. The challenges that we report on include better engagement of various categories of end users such as local institutions and land managers. Analyzing these challenges directs us toward  a few irritants that we need to manage to make OSM more inclusive towards them; this includes some mapping principles and semantic models in OSM, the need for better tooling for relation management, and perhaps additional governance bodies.

In addition to reporting on our successes and remaining challenges, the goal of this talk proposal is also to recruit participants for a BOF session with outdoors mappers and map developers from other countries, possibly with an actual outdoors mapping session in or near Paris

<hr>

_The talk will present the French Outdoors group and its approach to contributing that makes it end-user-centric in various ways. The talk will illustrate its successes in making OSM a significant player for outdoors maps in France. It will describe the remaining challenges that we'd like to discuss with the community, particularly outdoor mappers from other countries and application developers. We hope to have mountain professionals present for the talk, and our goal is to recruit participants for a BOF session on tagging and modeling improvements that would help us meet our remaining challenges._ 

The group emerged in 2021 as a bunch of hikers and mountain bikers who felt  that OSM had the potential to support better maps and new digital solutions for our activities. We started organizing ourselves, reaching out to other contributors, creating a Telegram channel and a Matrix room,  and launching initiatives. Today the group includes mountain professionals, tourism professionals, geographical information system managers in various institutions, etc. Some historical OSM contributors also observe our topics and how we address them.

Being end-users before being contributors, we follow community rules and principles but we care more about results (maps that we can use, data obtained, etc) than about advocating principles. This helps us focus, but also to sympathize with other end-user groups: tourism offices trying to attract hikers, natural reserves trying to protect endangered species, mountain rescue services complaining about trusting inaccurate maps, operators seeking solutions to manage their equipments..

Our successes, following previous works by countless contributors, make OSM a contender when selecting a hiking map. They include:
- an in-depth understanding of the hiking ecosystem and its many moving parts, which makes for various end-users that need engaging;
- the refinement of how to engage the different types of end-users and address their concerns, so as to obtain more data;
- progress from sketchy hiking and biking maps, compared to neighboring countries, to ~95% of continuous routes, thanks to QA tools such as Knooppuntnet and Waymarkedtrails
- the mapping of ~30.000 km of node networks, of pilgrimage routes, of a significant number of local routes;
- new features in renderers, e.g. forest compartments;
- a contribution to the cartes.app outdoors style, that both appeals to French end users and serves as a sandbox for experimenting with modeling.

These successes make talks growingly easier with various end-users, but not enough yet to start a virtuous circle and stabilize OSM as the best ecosystem for outdoors maps. Among the few challenges that we are working on: 

- there are too many routes, changing too often, for us to maintain. We must find how a significant fraction of the ~3000 route French operators can update &#34;their&#34; routes themselves. We get in touch, convince them to publish data, help them do so, then try and convince them to become regular contributors... and fail. Whereas we are eager enough to learn the OSM tools and culture, they are not. We need to make OSM more inclusive for them, creating new tools if necessary, and maybe convincing the community to adapt some principles or practices;

- reaching 100% quality is currently impossible because of mismatches between the OSM tagging model and the designs chosen by route operators. For instance, there are dozens of &#34;routes&#34; designed as networks of loops, sometimes disconnected from each other, and we cannot reflect the designer's intention without triggering false alarms in QA systems. More general modeling can be designed but consensus will require comparing notes with other countries;

- one to two routes are broken every day by other contributors who are not notified of the consequences of their changes. All editing tools are concerned, and we need to campaign for better support for relation integrity in at least JOSM and iD. History management is also an issue for relations, making it hard to find when and how a relation has been broken. Until then, we reach a plateau where contribution time is goes more to maintenance and less to new projects;

-  more and more land owners or local authorities create accounts for deleting ways, and who end up in conflict with traditional contributors. Finding rendering rules that satisfy everybody and popularizing them among map developers remains a challenge; communicating these rules to land owners and local authorities will be an even greater challenge;

- more and more mountain incidents involve OSM-based maps. To avoid bad press,  we need to create efficient processes with mountain rescue services and mountain federations so as to modify problematic ways. To stabilize the situation we may need the new tags about non-paths, scrambling routes, etc that have been discussed but not concluded upon in the last years.

Hopefully some of these challenges will provide a basis for an interesting BOF session after the talk.

