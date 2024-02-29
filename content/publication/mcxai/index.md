---
title: 'McXai: Local Model-Agnostic Explanation As Two Games'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yexu Zhou

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2023-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conference on Neural Networks*
publication_short: In *IJCNN*

abstract: To this day, various approaches for providing local explanation of black box machine learning models have been introduced. Despite these efforts, existing methods suffer from deficiencies such as being difficult to comprehend, only considering one feature at a time and disregarding inter-feature dependencies, lacking meaningful values for each feature, or only highlighting features that support the model’s decision. To overcome these drawbacks, this study presents a new approach to explain the predictions of any black box classifier, called Monte Carlo tree search for eXplainable Artificial Intelligence (McXai). It employs a reinforcement learning strategy and models the explanation generation as two distinct games. In the first game, the objective is to identify feature sets that support the model’s decision, while in the second game, the aim is to find feature sets that lead to alternative decisions. The output is a human-friendly representation in the form of a tree structure, where each node represents a set of features to be examined, with less specific interpretations at the top of the tree. Our experiments demonstrate that the features identified by McXai are more insightful with regard to the classifications compared to traditional algorithm like LIME and Gram-cam. Furthermore, the ability to identify misleading features provides guidance towards improved robustness of the black box classifier.

# Summary. An optional shortened abstract.
summary: To this day, various approaches for providing local explanation of black box machine learning models have been introduced. Despite these efforts, existing methods suffer from deficiencies such as being difficult to comprehend, only considering one feature at a time and disregarding inter-feature dependencies, lacking meaningful values for each feature, or only highlighting features that support the model’s decision. To overcome these drawbacks, this study presents a new approach to explain the predictions of any black box classifier, called Monte Carlo tree search for eXplainable Artificial Intelligence (McXai).

tags: [XAI, Deep Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10191756'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
url_project: 'https://www.sdsc-bw.de/'
# url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/10191756'
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
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
