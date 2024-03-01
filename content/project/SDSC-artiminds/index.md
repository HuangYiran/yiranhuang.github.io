---
title: Artiminds - Find a better starting position
summary: Data-driven approaches allow you to concentrate on the essentials. Detailed optimisation is automated. This saves a lot of time and effort.
tags:
  - SDSC
date: '2023-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Homepage of SDSC project
  focal_point: Smart

links:
  - icon: archive
    icon_pack: fab
    name: Homepage
    url: https://www.artiminds.com/de/
  - icon: obp
    icon_pack: fab
    name: Project
    url: https://www.sdsc-bw.de/artiminds/
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

ArtiMinds Robotics GmbH specialises in the development and distribution of software products for the standardisation and optimisation of workflows when using robots in automation. Our aim is to simplify the programming and operation of industrial robots and to enable cost-efficient integration and maintenance as well as flexible automation.

The data provided by ArtiMinds came from an experiment in which a robotic arm searches for holes to place a component on an electronic board. The experiment consisted of 120 runs, which generated a total of 2,487 observations. The start and end positions of the robot arm, its force and the runtime were recorded for each observation. The runs comprised four variants: Baseline (neither displacement nor drift), with a linear drift, with a displacement of the board and with a constant displacement. All runs were based on the so-called spiral search strategy, in which the path is arranged in a spiral.

During automated assembly with electronic components, a circuit board is guided to a specific position in front of the robot arm by means of a conveyor track. The process is stochastic because the PCBs almost never stop at the same, ideal position: The robot arm has to search for the placement holes every time. With conventional search strategies, it can normally do this within a second. However, there are cases in which the robot arm needs more time. This can lead to a cancellation and thus to a delay in the entire production process. For this reason, ArtiMinds would like to estimate the expected search time (better planning of production time) and know whether and how a better starting position and search path can be found based on the data (reduction of search time).

Based on the data collected during the robot arm exploration, the SDSC-BW experts analysed the starting position of the robot arm, the exploration position and the search results - with the aim of determining the search path of the robot arm and the distribution of the target points. By optimising the starting position and the search path, the average search time of the robot arm is reduced.

Mithilfe der Datenanalyse entdeckte das Expertenteam die Beziehung zwischen Startposition, Suchbahn des Roboterarms und durchschnittlichem Zeitaufwand. Anhand dessen entwickelte es eine Methode, die die Startposition und die Suchbahn des Roboterarms als Input verwendet und die zu erwartende Suchzeit des Roboterarms liefert. ArtiMinds kann diese Methode als Bewertungsfunktion des Optimierungs-algorithmus verwenden und hat so die Möglichkeit, die optimale Startposition und Suchbahn zu ermitteln.