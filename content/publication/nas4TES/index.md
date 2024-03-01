---
title: 'Enhancing Efficiency in HAR Models: NAS Meets Pruning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yexu Zhou
  - Tobias King
  - admin
  - Likun Fang
  - Tobias Röddiger
  - Till Riedel
  - Michael Beigl

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2024-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 22nd International Conference on Pervasive Computing and Communications*
publication_short: In *PerCom*

abstract: Real-time monitoring of human activities using wearable devices often requires the deployment of machine learning models on resource-constrained edge devices. Stateof- the-art Human Activity Recognition neural network models, while effective, already suffer from excessive size and complexity. Furthermore, our systematic analysis reveals that, even worse, the computational cost and model size of most SOTA HAR models escalate significantly with an increase in sensor channels. With advancements in sensor technology making it easier to scale sensor deployments that capture human activities, addressing this challenge becomes critical for practical applicability. In this work, we propose an integrated neural architecture search framework to further lighten HAR models. To counteract the negative effects of scaling at deployment time, the proposed framework simultaneously selects and reduces the number of sensor channels, prunes filters, and decreases the temporal dimensions while training the model on optimized hardware. This results in models that are not only smaller in size but also have less model complexity. We conducted experiments on three HAR datasets, demonstrating that our framework outperforms two state-of-theart pruning methods in reducing model size and complexity, while achieving superior performance. Furthermore, we successfully applied our proposed framework to the deployment of a HAR model on a microcontroller, highlighting its feasibility for realworld implementation.

# Summary. An optional shortened abstract.
summary: Real-time monitoring of human activities using wearable devices often requires the deployment of machine learning models on resource-constrained edge devices. Stateof- the-art Human Activity Recognition neural network models, while effective, already suffer from excessive size and complexity. Furthermore, our systematic analysis reveals that, even worse, the computational cost and model size of most SOTA HAR models escalate significantly with an increase in sensor channels. In this work, we propose an integrated neural architecture search framework to further lighten HAR models. To counteract the negative effects of scaling at deployment time, the proposed framework simultaneously selects and reduces the number of sensor channels, prunes filters, and decreases the temporal dimensions while training the model on optimized hardware.

tags: [NAS, TinyML, Wearable Computing, Pervasive Sensing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
