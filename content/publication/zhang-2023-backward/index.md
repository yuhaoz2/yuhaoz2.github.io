---
title: 'Backward Reachability Analysis of Neural Feedback Systems Using Hybrid Zonotopes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hang Zhang
  - Xiangru Xu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-06-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: '*IEEE Control Systems Letters*'
publication_short: ''

abstract: The proliferation of neural networks in safety-critical applications necessitates the development of effective methods to ensure their safety. This letter presents a novel approach for computing the exact backward reachable sets of neural feedback systems with known linear system models based on hybrid zonotopes. It is shown that the input-output relationship imposed by a ReLU-activated neural network can be exactly described by a hybrid zonotope-represented graph set. Based on that, the one-step exact backward reachable set of a neural feedback system is computed as a hybrid zonotope in the closed form. In addition, a necessary and sufficient condition is formulated as a mixed-integer linear program to certify whether the trajectories of a neural feedback system can avoid unsafe regions in finite time. Numerical examples are provided to demonstrate the efficiency of the proposed approach.

# Summary. An optional shortened abstract.
summary: A novel approach for computing the exact backward reachable sets of neural feedback systems.

tags:
  - Neural Network Control System
  - Reachable Set
  - Hybrid Zonotope

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: https://doi.org/10.1109/LCSYS.2023.3289572

url_pdf: 'https://arxiv.org/pdf/2303.10513'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/NrvZJXsfryA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Backward reachable sets computed by various methods'
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