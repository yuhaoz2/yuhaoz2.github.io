---
title: 'Data-driven Stability Analysis of Neural Network Control Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jeremy Coulson
  - Xiangru Xu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-06-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: '*IEEE Control Systems Letters*'
publication_short: ''

abstract: |
  This letter studies the problem of verifying stability of neural network control systems in which the plant dynamics are unknown but the neural network controller is known. We derive sufficient conditions for stability that are directly computable from a finite-length trajectory of the closed-loop system, without requiring an explicit model of the plant. The proposed conditions take the form of linear matrix inequalities and, as a byproduct, yield an estimate of the region of attraction. Both the noiseless and noisy data settings are considered: in the noiseless case, data-driven sufficient conditions are derived to guarantee stability; in the noisy case, sufficient conditions are derived to ensure robust stability of all systems consistent with the data. The effectiveness of the proposed approach is demonstrated on an inverted pendulum example.

# Summary. An optional shortened abstract.
summary: This work introduces an novel data-driven approach to verify stability of neural network control systems.

tags:
  - Neural Network Control System
  - Data-driven
  - Stability
  - Linear Matrix Inequality

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: 'https://doi.org/10.1109/LCSYS.2026.3706012'

url_pdf: 'https://xu.me.wisc.edu/wp-content/uploads/sites/1196/2026/06/Data-driven-Stability-Analysis-of-Neural-Network-Control-Systems.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Data-driven stability analysis of an unknown LTI system in feedback with a known feedforward neural network controller'
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