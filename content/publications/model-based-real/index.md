---
title: "Model-Based Real-Time Motion Tracking Using Dynamical Inverse Kinematics"
authors:
- admin
- Yeshasvi Tirupachuri
- Kourosh Darvish
- Stefano Dafarra
- Gabriele Nava
- Claudia Latella
- Daniele Pucci

author_notes:
date: "2020-10-20T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Algorithms"
publication_short: ""

abstract: 

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: true

hugoblox:
  ids:
    arxiv: 

links:
  - type: pdf
    url: https://www.mdpi.com/1999-4893/13/10/266/pdf?version=1603336000
  - type: code
    url: https://github.com/robotology/human-dynamics-estimation
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  - type: source
    url: "https://www.mdpi.com/1999-4893/13/10/266"
  # - type: video
  #   url: "https://www.youtube.com/watch?v=z0aoTzdx25Y&feature=youtu.be"

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This paper contributes towards the development of motion tracking algorithms for time-critical applications, proposing an infrastructure for dynamically solving the inverse kinematics of highly articulate systems such as humans. The method presented is model-based, it makes use of velocity correction and differential kinematics integration in order to compute the system configuration. The convergence of the model towards the measurements is proved using Lyapunov analysis. An experimental scenario, where the motion of a human subject is tracked in static and dynamic configurations, is used to validate the inverse kinematics method performance on human and humanoid models. Moreover, the method is tested on a human-humanoid retargeting scenario, verifying the usability of the computed solution in real-time robotics applications. Our approach is evaluated both in terms of accuracy and computational load, and compared to iterative optimization algorithms.