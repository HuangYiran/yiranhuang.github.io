---
title: 'Optimizing AutoML for Tiny Edge Systems: A Baldwin-effect Inspired Genetic Algorithm'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yexu Zhou
  - Haibin Zhao
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

abstract: Tiny edge systems used in IoT devices, wearables or smart textiles are characterized by the need of processing complex sensor data streams under various device constraints. Due to the high number of constraints and the complexity of the optimization of the hyper-parameter space for machine learning based processing, genetic algorithms (GAs) seem to be a perfect fit to enable AutoML for those embedded devices. However, due to aspects such as the high interdependence between optimization parameters, the simultaneous existence of multiple conflicting objectives and complex effects of embedded feature engineering, we made the experience that GA approaches fail to converge within this high dimensional design space. We introduce a novel Genetic Algorithm (GA) customized for AutoML tasks, addressing the unique challenges posed by highly embedded machine learning domains. The proposed approach addresses parameter interdependencies through utilizing the Baldwin-effect in biological evolution, enhances resource utilization by early elimination of less promising individuals, and augments the insufficient capabilities of existing machine learning features via the integration of carefully designed neural network features. Empirical evaluations conducted on two benchmark datasets support the superiority of our proposed method over conventional genetic algorithms. Furthermore, we demonstrate the effect of the different components introduced by our algorithms through an ablation study.

# Summary. An optional shortened abstract.
summary: Tiny edge systems used in IoT devices, wearables or smart textiles are characterized by the need of processing complex sensor data streams under various device constraints. Due to the high number of constraints and the complexity of the optimization of the hyper-parameter space for machine learning based processing, genetic algorithms (GAs) seem to be a perfect fit to enable AutoML for those embedded devices.  We introduce a novel Genetic Algorithm (GA) customized for AutoML tasks, addressing the unique challenges posed by highly embedded machine learning domains.

tags: [AutoML, TinyML, Wearable Computing, Multiobjective Optimization, Pervasive Sensing]

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
