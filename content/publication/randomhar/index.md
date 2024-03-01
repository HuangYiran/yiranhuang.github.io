---
title: 'randomHAR: Improving Ensemble Deep Learners for Human Activity Recognition with Sensor Selection and Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yexu Zhou
  - Likun Fang
  - Till Riedel
  - Michael Beigl

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
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Deep learning has proven to be an effective approach in the field of Human activity recognition (HAR), outperforming other architectures that require manual feature engineering. Despite recent advancements, challenges inherent to HAR data, such as noisy data, intra-class variability and inter-class similarity, remain. To address these challenges, we propose an ensemble method, called randomHAR. The general idea behind randomHAR is training a series of deep learning models with the same architecture on randomly selected sensor data from the given dataset. Besides, an agent is trained with the reinforcement learning algorithm to identify the optimal subset of the trained models that are utilized for runtime prediction. In contrast to existing work, this approach optimizes the ensemble process rather than the architecture of the constituent models. To assess the performance of the approach, we compare it against two HAR algorithms, including the current state of the art, on six HAR benchmark datasets. The result of the experiment demonstrates that the proposed approach outperforms the state-of-the-art method, ensembleLSTM.

# Summary. An optional shortened abstract.
summary: Deep learning has proven to be an effective approach in the field of Human activity recognition (HAR), outperforming other architectures that require manual feature engineering. Despite recent advancements, challenges inherent to HAR data, such as noisy data, intra-class variability and inter-class similarity, remain. To address these challenges, we propose an ensemble method, called randomHAR. 

tags: [Human Activity Recognition, Deep Learning]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2307.07770'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
url_project: 'https://www.sdsc-bw.de/'
# url_slides: ''
url_source: 'https://arxiv.org/abs/2307.07770'
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
