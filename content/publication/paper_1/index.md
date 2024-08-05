---
title: "Integrating Controllable Motion Skills from Demonstrations"
authors:
- admin
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The expanding applications of legged robots require their mastery of versatile motion skills. Correspondingly, researchers must address the challenge of integrating multiple diverse motion skills into controllers. While existing reinforcement learning (RL)-based approaches have achieved notable success in multi-skill integration for legged robots, these methods often require intricate reward engineering or are restricted to integrating a predefined set of motion skills constrained by specific task objectives, resulting in limited flexibility. In this work, we introduce a flexible multi-skill integration framework named Controllable Skills Integration (CSI). CSI enables the integration of a diverse set of motion skills with varying styles into a single policy without the need for complex reward tuning. Furthermore, in a hierarchical control manner, the trained low-level policy can be coupled with a high-level Natural Language Inference (NLI) module to enable preliminary language-directed skill control. Our experiments demonstrate that CSI can flexibly integrate a diverse array of motion skills more comprehensively and facilitate the transitions between different skills. Additionally, CSI exhibits good scalability as the number of motion skills to be integrated increases significantly.

# Summary. An optional shortened abstract.
summary: A flexible imitation learning-based multi-skill integration framework for legged robots.

tags:
- Imitation Learning

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: uploads/working_paper.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
