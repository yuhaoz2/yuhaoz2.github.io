---
title: 'Formal Reachability and Robust Stability Analysis of Neural Network Control Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-08-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-08-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: '*The University of Wisconsin - Madison ProQuest Dissertations & Theses*'
publication_short: ''

abstract: |
  Neural networks are increasingly integrated into the closed-loop architecture of modern autonomous and robotic systems, where they are used to represent control policies, perception modules, or components of system models. While such neural network–enabled systems have demonstrated strong empirical performance in complex and uncertain environments, neural networks are known to be highly sensitive to small input perturbations. When embedded in feedback loops, this sensitivity can lead to significant deviations in system behavior, posing serious challenges for safety-critical applications. These challenges highlight the need for rigorous, formal analysis tools capable of characterizing and certifying the behavior of neural network control systems. This dissertation addresses this need by developing systematic and theoretically grounded methods for analyzing and certifying key properties of neural network control systems.

  The first part of this dissertation addresses the reachability analysis of neural networks using set-based computational methods. This dissertation presents the first systematic application of hybrid zonotopes to the reachability analysis of neural networks, employing them as a unified and expressive set representation for computing both forward and backward reachable sets. By exploiting the structural properties of neural networks, the proposed methods enable exact or provably over-approximated representations of the neural network input–output mapping, allowing reachable sets to be efficiently computed through set-propagation operations. To overcome the scalability challenges associated with large neural networks, this dissertation further introduces tunable and computationally efficient network reduction and abstraction techniques that provide a flexible trade-off between approximation accuracy and computational complexity.

  The second part of this dissertation studies the hybrid-zonotopes-based reachability analysis and safety verification of neural network control systems by building upon the results developed in the first part. Both the neural network controller and the plant dynamics are represented using hybrid zonotopes, enabling their interconnection to be encoded through simple hybrid-zonotope set operations. Consequently, when the initial and target sets of the neural network control system are expressed as hybrid zonotopes, the corresponding forward and backward reachable sets can also be constructed within the same representation framework. Based on the computed reachable sets, safety verification problems are formulated as mixed-integer linear programs, enabling sound and, in certain cases, complete safety certification for neural network control systems.

  The third part of this dissertation investigates the robust stability properties of neural network control systems, with particular emphasis on robustness in the presence of modeling uncertainties. By integrating classical Lyapunov stability theory with quadratic constraint–based abstractions of neural networks, we derive novel robust stability certificates for neural network control systems with interval matrix uncertainties, formulated as linear matrix inequalities. To mitigate the associated computational burden, three relaxed sufficient conditions are developed, and their equivalence in terms of feasibility is rigorously established. The proposed stability framework is further extended to a data-driven setting, where explicit system models are unavailable but input–state observations of system behavior are accessible. Collectively, these results establish a rigorous framework for the stability verification of neural network control systems.

# Summary. An optional shortened abstract.
summary: This thesis explores formal reachability and stability analysis in neural network control systems.

tags:
  - Neural Network Control System
  - Reachability
  - Stability
  - Hybrid Zonotope

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: ''

url_pdf: 'https://www.proquest.com/docview/3301479860?pq-origsite=gscholar&fromopenview=true&sourcetype=Dissertations%20&%20Theses'
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
  caption: 'A closed-loop control system incorporating NN-based controller and perception module'
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