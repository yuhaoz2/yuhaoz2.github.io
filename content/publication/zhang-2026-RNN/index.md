---
title: 'Forward and Backward Reachability Analysis of Closed-loop Recurrent Neural Networks via Hybrid Zonotopes'

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

date: '2026-01-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-conference']

# Publication name and optional abbreviated publication name.
publication: '*American Control Conference (ACC)* [accepted]'
publication_short: ''

abstract: Recurrent neural networks (RNNs) are widely employed to model complex dynamical systems due to their hidden-state structure, which inherently captures temporal dependencies. This work presents a hybrid zonotope–based approach for computing exact forward and backward reachable sets of closed-loop RNN systems with ReLU activation functions. The method formulates state-pair sets to compute reachable sets as hybrid zonotopes without requiring unrolling. To improve scalability, a tunable relaxation scheme is proposed that ranks unstable ReLU units across all layers using a triangle-area score and selectively applies convex relaxations within a fixed binary limit in the hybrid zonotopes. This scheme enables an explicit trade-off between computational complexity and approximation accuracy, with exact reachability as a special case. In addition, a sufficient condition is derived to certify the safety of closed-loop RNN systems. Numerical examples demonstrate the effectiveness of the proposed approach.

# Summary. An optional shortened abstract.
summary: This work introduces an novel approach to compute the reachable sets for recurrent neural networks in closed-loop systems.

tags:
  - Recurrent Neural Network 
  - Reachable Set
  - Hybrid Zonotope

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: ''

url_pdf: ''
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
  caption: 'RNN (left) and RNN in a closed-loop system (right)'
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