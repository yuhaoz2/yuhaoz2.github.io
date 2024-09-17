---
title: Presentation at 2022 IEEE CDC

event: IEEE 61st Conference on Decision and Control (CDC)
event_url: https://cdc2022.ieeecss.org/index.html

location: Cancun, Mexico
address:
  street: Km 14.5, Blvd
  city: Cancun
  region: QR
  postcode: '77500 '
  country: Mexico

summary: A novel set-based method is proposed to compute both exact and over-approximated reachable sets for neural feedback systems.
abstract: 'Artificial neural networks have recently been utilized in many feedback control systems and introduced new challenges regarding the safety of such systems. This paper considers the safe verification problem for a dynamical system with a given feedforward neural network as the feedback controller by using a constrained zonotope-based approach. A novel set-based method is proposed to compute both exact and over-approximated reachable sets for neural feedback systems with linear models, and linear program-based sufficient conditions are presented to verify whether the trajectories of such a system can avoid unsafe regions represented as constrained zonotopes. The results are also extended to neural feedback systems with nonlinear models. The computational efficiency and accuracy of the proposed method are demonstrated by two numerical examples where a comparison with state-of-the-art methods is also provided.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-12-07T13:00:00Z'
date_end: '2022-12-07T13:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-15T00:00:00Z'

authors:
  - admin

tags:   
  - Neural Network Control System
  - Reachable Set
  - Constrained Zonotope

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Overview of proposed approach'
  focal_point: #Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://doi.org/10.1109/CDC51059.2022.9992655'
url_slides: ''
url_video: 'https://youtu.be/w-jEzc0_VJI'

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

{{< youtube w-jEzc0_VJI >}}

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
