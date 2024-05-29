---
title: 'ExTea: An Evolutionary Algorithm-Based Approach for Enhancing Explainability in Time-Series Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yexu Zhou
  - Haibin Zhao
  - Likun Fang
  - Till Riedel
  - Michael Beigl

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2024-09-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases*
publication_short: In *ECMLPKDD*

abstract: In the expanding realm of sensor-based applications, the reliance on time-series data has surged, posing challenges in explaining the decisions of complex black-box time-series models. Existing Explainable Artificial Intelligence (XAI) approaches such as SBXAI, MCXAI and TS-MULE offer insights into these models but face limitations in generating multiple explanations, exploring time-series-specific characteristics, optimizing found cognitive blocks, and setting appropriate hyperparameters. Addressing these challenges, we introduce an EXplainable artificial intelligence method targeting Time-series model based on Evolutionary Algorithm (ExTea). ExTea conceptualizes explanations as evolving individuals and employs an innovative pyramidal structure for optimizing potential explanations, categorized into newborn, tested, and elite stages. This approach incorporates time-series characteristics into the fitness function of individual evaluation, thereby enhancing the overall explanatory power. Extensive experiments on six benchmark datasets with four target models demonstrate that the performance of ExTea significantly exceeds the state-of-the-art time-series XAI algorithms, SBXAI and MCXAI.

# Summary. An optional shortened abstract.
summary: We introduce an EXplainable artificial intelligence method targeting Time-series model based on Evolutionary Algorithm (ExTea). ExTea conceptualizes explanations as evolving individuals and employs an innovative pyramidal structure for optimizing potential explanations, categorized into newborn, tested, and elite stages.

tags: [explainable artificial intelligence, time-series, evolutionary algorithm, Baldwin effect]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#TODO TO update
url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-031-26409-2_35'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
url_project: 'https://www.sdsc-bw.de/'
# url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-031-26409-2_35'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - SDSC

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
