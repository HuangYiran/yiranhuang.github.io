---
title: High-Q: Analyzing the hazard potential of cycle paths with the help of AI algorithms
summary: Smart data Solutions center (SDSC) aimed at leveraging smart data technologies for SMEs in Baden-Württemberg's manufacturing sector. This initiative, supported by the Ministry of Science, Research and Art Baden-Württemberg (MWK), focuses on facilitating SMEs' access to and use of smart data. Through analyzing real industrial datasets, we aim to foster SME awareness and readiness for data innovation, particularly in Industry 4.0 contexts. Our collaboration with companies demonstrates the project's capacity to generate actionable insights and integrate smart technologies into existing systems, promoting data-driven innovation across the region.
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
    icon_pack: academicons
    name: Homepage
    url: https://www.sdsc-bw.de/highq-computerloesungen-gmbh
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

For 20 years, highQ Computerlösungen GmbH has been supporting companies, municipalities and financial institutions with intelligent software solutions for more effective planning, implementation, optimization and controlling of their tasks. The IT solutions make public transportation, for example, smoother and more environmentally friendly. www.highq.de.

In order to analyze the hazard potential of cycle paths, HighQ prepared seven individual data sets; the SDSC-BW experts in turn contributed free data. The database contained, for example, information from reports on bicycle accidents from the last 20 years (Germany-wide) as well as evaluations of cycle path questionnaires. Other helpful data on German traffic routes and traffic images from the Open-Street-Map portal were also included. The file formats were different: including georeferenced files (GEO) and CSV files ideal for analytics.

When it comes to determining the safety of cycle paths, the research potential is huge. The aim of the SDSC-BW project was to explore this potential. Due to the numerous problems, even the creation of a framework proved difficult. First and foremost were the diverse, sometimes confusing data sources - including different websites that store data in their own way. Integrating this data (and its updates) efficiently and quickly into the framework was a complex problem. In addition, the definition of the research objective "more security" was very vague and lacked achievable markers. Other problems included the fact that cities were inconsistent in their approach to data collection.

The ongoing analysis of the available data focused the attention of the SDSC experts on route planning. The aim was to work efficiently with the data. To this end, the team made slight updates, corrected existing deficiencies within the data and finally evaluated it effectively. Based on this, the team was able to carry out implementations and test structures.

Within four weeks, the team created a framework and filled it with methodology. This makes it possible to display hazard factors as well as route recommendations when planning a route via an online map service. The hazard factor is influenced by recorded accidents. For ease of interpretation, it is translated into a value range between zero and one. Newly developed neural networks enable a prediction for areas with insufficient data.