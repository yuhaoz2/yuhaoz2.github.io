---
title: Presentation at 2023 IEEE CDC

event: IEEE 62nd Conference on Decision and Control (CDC)
event_url: https://cdc2023.ieeecss.org/index.html

location: Singapore
address:
  street: 10 Bayfront Ave
  city: Singapore
  region: 
  postcode: '018956'
  country: Singapore

summary: A novel approach for computing the exact backward reachable sets of neural feedback systems.
abstract: 'The proliferation of neural networks in safety-critical applications necessitates the development of effective methods to ensure their safety. This letter presents a novel approach for computing the exact backward reachable sets of neural feedback systems with known linear system models based on hybrid zonotopes. It is shown that the input-output relationship imposed by a ReLU-activated neural network can be exactly described by a hybrid zonotope-represented graph set. Based on that, the one-step exact backward reachable set of a neural feedback system is computed as a hybrid zonotope in the closed form. In addition, a necessary and sufficient condition is formulated as a mixed-integer linear program to certify whether the trajectories of a neural feedback system can avoid unsafe regions in finite time. Numerical examples are provided to demonstrate the efficiency of the proposed approach.

# Summary. An optional shortened abstract.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-12-15T13:00:00Z'
date_end: '2023-12-15T13:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-15T00:00:00Z'

authors:
  - admin

tags:   
  - Neural Network Control System
  - Reachable Set
  - Hybrid Zonotope

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Backward reachable sets computed by various methods'
  focal_point: #Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://doi.org/10.1109/LCSYS.2023.3289572'
url_slides: ''
url_video: 'https://youtu.be/NrvZJXsfryA'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
#  - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
