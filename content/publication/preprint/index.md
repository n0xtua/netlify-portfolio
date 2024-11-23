---
title: "Deep Attention Driven Reinforcement Learning (DAD-RL) for Autonomous Decision-Making in Dynamic Environment"
authors:
- admin
- Jayabrata Chowdhury
- Venkataramanan Shivaraman
- Sumit Dangi
- Suresh Sundaram
- P.B.Sujit
date: "2024-09-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Conference Paper"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Autonomous Vehicle (AV) decision making in urban environments is inherently challenging due to the dynamic interactions with surrounding vehicles. For safe planning, AV must understand the weightage of various spatiotemporal interactions in a scene. Contemporary works use colossal transformer architectures to encode interactions mainly for trajectory prediction, resulting in increased computational complexity. To address this issue without compromising spatiotemporal understanding and performance, we propose the simple Deep Attention Driven Reinforcement Learning (DADRL) framework, which dynamically assigns and incorporates the significance of surrounding vehicles into the ego's RL driven decision making process. We introduce an AV centric spatiotemporal attention encoding (STAE) mechanism for learning the dynamic interactions with different surrounding vehicles. To understand map and route context, we employ a context encoder to extract features from context maps. The spatiotemporal representations combined with contextual encoding provide a comprehensive state representation. The resulting model is trained using the Soft Actor Critic (SAC) algorithm. We evaluate the proposed framework on the SMARTS urban benchmarking scenarios without traffic signals to demonstrate that DADRL outperforms recent state of the art methods. Furthermore, an ablation study underscores the importance of the context-encoder and spatio temporal attention encoder in achieving superior performance.

# Summary. An optional shortened abstract.
summary: ""

tags:
- AI, Robotics

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2407.08932
url_code: 'https://github.com/jayabrata97/Deep-Attention-Driven-Reinforccement-Learning-DAD-RL'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
