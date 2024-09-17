---
title: 'Reachability Analysis and Safety Verification of Neural Feedback Systems via
  Hybrid Zonotopes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiangru Xu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-07-03T00:00:00Z'
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

abstract: Hybrid zonotopes generalize constrained zonotopes by introducing additional binary variables and possess some unique properties that make them convenient to represent nonconvex sets. This paper presents novel hybrid zonotope-based methods for the reachability analysis and safety verification of neural feedback systems. Algorithms are proposed to compute the input-output relationship of each layer of a feed-forward neural network, as well as the exact reachable sets of neural feedback systems. It is shown that a ReLU-activated feed-forward neural network can be exactly represented by a hybrid zonotope. In addition, a sufficient and necessary condition is formulated as a mixed-integer linear program to certify whether the trajectories of a neural feedback system can avoid unsafe regions. The proposed approach is shown to yield a formulation that provides the tightest convex relaxation for the reachable sets of the neural feedback system. Complexity reduction techniques for the reachable sets are developed to balance the computation efficiency and approximation accuracy. Two numerical examples demonstrate the superior performance of the proposed approach compared to other existing methods.

# Summary. An optional shortened abstract.
summary: This paper presents novel hybrid zonotope-based methods for the reachability analysis and safety verification of neural feedback systems. Algorithms are proposed to compute the input-output relationship of each layer of a feed-forward neural network, as well as the exact reachable sets of neural feedback systems.

tags:
  - Neural Network Control System
  - Reachable Set
  - Hybrid Zonotope

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: https://doi.org/10.23919/ACC55779.2023.10156417

url_pdf: 'https://arxiv.org/pdf/2210.03244'
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
  caption: 'The neural feedback system maps a hybrid zonotope into another hybrid zonotope'
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