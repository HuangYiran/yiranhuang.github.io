---
title: VAF - A machine learning approach for the most important factors that influence production time
summary: In this joint project, the SDSC-BW has shown how valuable our data is. For us as a medium-sized company, the collaboration with the research experts was particularly helpful.
tags:
  - SDSC
date: '2023-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Picture from SDSC Website
  focal_point: Smart

links:
  - icon: archive
    icon_pack: fab
    name: Homepage
    url: https://vaf-bopfingen.de/index.php/de/
  - icon: obp
    icon_pack: fab
    name: Project
    url: https://www.sdsc-bw.de/vaf-gbh/
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

VAF is a world-renowned manufacturer of special machines for the automotive industry, a medium-sized family business that employs over 450 people and is represented all over the world. Its main activities include the supply of special machines and systems for well-known automotive manufacturers and their suppliers.

VAF has a wide range of products. They differ in terms of production times, production processes and raw materials, among other things. To investigate which factors ultimately determine production times, VAF has made a large dataset available: it comprises around 250,000 production records from 2008 to 2021, each of which maps a production process and contains 33 different attributes; e.g. the raw material used for production, the production method used, the form of the production target and the production time. Most attribute values in the dataset are stored as text regardless of their type, which was a major difficulty in this project.

This task was associated with two difficulties: 1) the requirement of interpretability limits the choice of models and 2) the large number of features stored as text makes it difficult to analyse and at the same time affects the performance of some models.there are many complex models whose decisions are difficult to explain, deep neural networks are one of the typical examples. Attributes stored using text are mostly contextual and can be handled well by semantic analysis, but it requires a large amount of data and time and is not interpretable. Instead, some simple methods can add or remove information.

When analysing potential free of charge, the experts at SDSC-BW focus on pre-processing the data. This includes analysing the data distribution, correcting erroneous data, processing "character type" data and, through research, constructing new attributes based on the original attributes using mathematical operators. The newly processed data was then tested on a number of different "simple" models and attempts were made to improve the performance of the models through ensemble.

After six weeks of work, the SDSC-BW experts experimentally tested the feasibility of using attributes to predict production times and determined which attributes have the greatest influence on time. In addition, the experts visualised the influence of some attributes in the form of a tree diagram and provided an opportunity to further investigate the influence of other attributes