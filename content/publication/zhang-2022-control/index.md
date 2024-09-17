---
title: 'Control Barrier Function Meets Interval Analysis: Safety-Critical Control
  with Measurement and Actuation Uncertainties'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sequoyah Walters
  - Xiangru Xu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-09-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-conference']

# Publication name and optional abbreviated publication name.
publication: '*American Control Conference (ACC)*'
publication_short: ''

abstract: This paper presents a framework for designing provably safe feedback controllers for sampled-data control affine systems with measurement and actuation uncertainties. Based on the interval Taylor model of nonlinear functions, a sampled-data control barrier function (CBF) condition is proposed which ensures the forward invariance of a safe set for sampled-data systems. ℝeachable set overapproximation and Lasserre’s hierarchy of polynomial optimization are used for finding a margin term in the sampled-data CBF condition. Sufficient conditions for a safe controller in the presence of measurement and actuation uncertainties are proposed. The effectiveness of the proposed method is illustrated by a numerical example and an experimental example that implements the proposed controller on the Crazyflie quadcopter in real-time.

# Summary. An optional shortened abstract.
summary: This paper presents a framework for designing provably safe feedback controllers for sampled-data control affine systems with measurement and actuation uncertainties.

tags:
  - Safe Controller
  - Sampled-data System
  - System with Uncertainties
  - Control Barrier Function

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: DOI
  url: https://doi.org/10.23919/ACC53348.2022.9867681

url_pdf: 'https://arxiv.org/pdf/2110.00915'
url_code: 'https://github.com/wisc-arclab/SampleDataCBF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/m3lbH_SdjJ8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Experiment result of proposed safe controller (RSDCBF)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: '' #example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->