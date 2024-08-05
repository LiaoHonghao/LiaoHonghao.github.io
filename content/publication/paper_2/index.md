---
title: "Research on Object Navigation Method Based on Deep Reinforcement Learning (Working paper, in Chinese)"
authors:
- admin
date: "2022-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Autonomous navigation is the basic ability requirement for robots to complete many other tasks. In recent years, the emerging deep reinforcement learning provides a solution for autonomous objective navigation of robots, but the existing visual objective navigation methods based on deep reinforcement learning have some problems such as poor cross-scene generalization ability. In this paper, an end-to-end visual object navigation model with strong ability of cross-scene generalization is proposed based on previous ideas. To solve the problem of weak cross-scene generalization, this paper proposes a state representation method combining objective detection results with depth image and a reward function representation method combining objective detection results. Since the state representation contains less scene-specific information, the combination of the state representation and the reward function representation ensures that the model can have strong cross-objective generalization ability as well as cross-scene generalization ability. In addition, the AI2THOR simulation scene is made into the Offline AI2THOR Dataset in this paper. Compared with the direct real-time rendering of AI2THOR simulation platform, the Offline AI2THOR Dataset can greatly improve the interaction speed and realize the cross-platform use of simulation scenes. On the basis of this dataset, the proposed navigation model is trained and experimented. Experimental results show that the proposed model has better navigation performance and has improved cross-objective generalization ability and cross-scene generalization ability.

# Summary. An optional shortened abstract.
summary: An end-to-end deep reinforcement learning based visual objective navigation framework.

tags:
- Deep Reinforcement Learning
- Visual Objective Navigation

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: uploads/Research_on_object_navigation_method_based_on_DRL.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: 'uploads/slide.pptx'
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

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
