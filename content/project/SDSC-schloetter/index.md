---
title: Schloetter - Predict sales volumes intelligently
summary: In our joint project, the SDSC-BW discovered correlations that are relevant to our production. We will now investigate these data correlations and develop further steps to optimise our production.
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
    url: https://www.schloetter.de
  - icon: obp
    icon_pack: fab
    name: Project
    url: https://www.sdsc-bw.de/schloetter/
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
Dr.-Ing. Max Schlötter GmbH & Co. KG, headquartered in Geislingen, is one of the leading companies for electroplating technology in Germany. The company's core competences lie in the development and manufacture of electroplating chemicals for surface coating and the construction of electroplating systems. The medium-sized company can look back on more than 100 years of experience in electro-chemical research.

Schlötter provided the data analysis experts at SDSC-BW with sales data from the last 13 years: a total of around one million data elements. The data contained sales information for each product on each day, such as sales volume, warehouse address, customer number, order time, delivery time, etc.

The sales volume of Schlötter products is influenced by many factors, including market competition, economic changes and marketing strategies. It is therefore difficult to produce high-quality sales forecasts. "Surprise orders", where the order volume is often suddenly many times higher than usual, make forecasting even more difficult. Inaccurate forecasts can lead to various losses in this context: Under-forecasting leads to lost orders and special trips Over-forecasting leads to unnecessary storage costs.

In order to reduce the losses caused by inaccurate forecasts, the SDSC-BW team tried to optimise the prediction of the sales volume with the help of machine learning. To do this, it considered the problem as a time series forecasting task. As an underprediction can lead to a threefold higher loss compared to an overprediction, the experts defined an asymmetric evaluation metric. They then extracted various features from the sales data time series, including statistical information (such as mean values and autocorrelations) or frequency information (such as Fourier transformation). Based on these features, they tested different models to identify the best one. Finally, the team compared the optimised model with Schlötter's forecasting strategy.

Through detailed analysis and extensive research, the experts at SDCS-BW developed a method that automatically and adaptively predicts the sales volumes of different Schlötter products. The new model achieved better results than the forecasting strategy previously used by Schlötter.