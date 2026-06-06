---
layout: session
title: "How Carto’Cité maintains OSM data for 436 train stations efficiently using PostGIS and QGIS"
code: "CXXRXD"
speaker_names: ['Antoine Riche']
affiliations: None
room: "Talks III - Amphi Cauchy (Carnot)"
length: "20"
time: "Friday, 16:45"
time_iso: "2026-08-28T14:45:00Z"
resources: []
recording: True
prerecorded: False
language: en
---

SNCF Transilien has mapped with great details 436 train stations in the Greater Paris area. This work was conducted in several stages, between 2018 and 2022. An application using this data helps travelers to find their way inside and around railway stations. The app displays multi-level floor plans, enables users to find equipments and services, and provides indoor/outdoor routing with an option to use elevators rather than stairways.

Ensuring these services function properly requires to **maintain the data**. This means both updating it when a station or its neighbourhood has changed, and preserving the high quality of the data. The latter is achieved by checking changes to the data inside and around railway stations. This **moderation work** is achieved through an innovative process that enables us to :
- compare the data for each station between 2 dates freely defined
- detect and classify changes that need to be checked 
- apply a whitelist to avoid checking one's own changes
- review those changes and produce a report 

We set up a project that is based on **PostGIS** and **QGIS**, makes use of **osmium** and **osm2pgsql**, and requires a small amount of SQL code to detect changes. This project enables us to efficiently moderate the data changes that can impact the SNCF app. 

This talk will present our methodology, which can be replicated and adapted to all sorts of OSM data, along with a few helpful tricks.

<hr>

### Résumé (french abstract)

## Comment Carto’Cité maintient efficacement les données OSM de 436 gares avec PostGIS et QGIS

SNCF Transilien a cartographié de manière très détaillée les 436 gares de son réseau sur OSM. Ce travail s’est déroulé en plusieurs étapes, entre 2018 et 2022. Une application utilisant ces données aide les voyageurs à s’orienter à l’intérieur et aux abords des gares. L'application affiche des plans d'étage à plusieurs niveaux, permet aux utilisateurs de localiser les équipements et les services, et propose un guidage intérieur/extérieur avec la possibilité d'utiliser les ascenseurs plutôt que les escaliers.

Maintenir le bon fonctionnement de cette application nécessite de **maintenir les données**. Il s'agit à la fois d'actualiser les données suite aux travaux réalisés en gare, et de garantir leur haut niveau de qualité en vérifiant les contributions de la communauté. Pour effectuer ce travail de **modération**, Carto’Cité a mis en place une approche originale qui permet de :
- comparer les données de chaque gare entre 2 dates définies librement
- détecter les modifications à vérifier en fonction de critères configurables
- appliquer une liste blanche pour éviter de vérifier nos propres modifications
- réaliser un suivi de ces signalements et produire un rapport

Nous avons mis en place un projet basé sur **PostGIS** et **QGIS**, qui utilise **osmium** et **osm2pgsql**, et nécessite une petite quantité de code SQL pour détecter les modifications. Ce projet nous permet de modérer efficacement les modifications de données susceptibles d'avoir un impact sur l'application SNCF. 

Cette présentation exposera notre méthodologie, qui peut être reproduite et adaptée à toutes sortes de données OSM, ainsi que quelques astuces utiles.

