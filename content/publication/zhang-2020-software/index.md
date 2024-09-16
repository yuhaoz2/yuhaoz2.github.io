---
title: 'A software architecture for autonomous taxiing of aircraft'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guillaume Poupart-Lafarge
  - Huaiyuan Teng
  - Joshua Wilhelm
  - Jean-Baptiste Jeannin
  - Necmiye Ozay
  - Eelco Scholte

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-01-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-conference']

# Publication name and optional abbreviated publication name.
publication: '*AIAA Scitech 2020 Forum*'
publication_short: ''

abstract: Recent progress in self-driving capabilities of cars suggests that one could also automate aircraft taxi operations, a seemingly easier problem. In this paper we describe a high-level software architecture for self-taxiing, and we identify its specific challenges. The architecture is selected to ease the mapping of specifications to the different implemented functionalities, allowing for modular verification. We then focus on two of the modules in this architecture. We describe how to obtain a low-level list of taxiways from high-level Air Traffic Control instructions, and how to design GPS-based controllers for lateral and longitudinal control of the aircraft. This architecture is implemented in simulation based on the X-Plane flight simulator, for which different controllers for one of the low-level functionalities is evaluated using falsification tools S-TaLiRo and Breach.

# Summary. An optional shortened abstract.
summary: In this paper we describe a high-level software architecture for self-taxiing, and we identify its specific challenges.

tags:
  - Self-taxiing algorithm
  - Model Predictive Control
  - Falsification
  - X-Plane Flight Simulator

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: DOI
  url: https://doi.org/10.2514/6.2020-0139

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
  caption: 'Proposed Architecture'
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