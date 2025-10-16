---
title: "Shared Control of Robot-Robot Collaborative Lifting with Agent Postural and Force Ergonomic Optimization"
authors:
- admin
- Yeshasvi Tirupachuri
- Alberto Ranavolo
- Tomohiro Kawakami
- Takahide Yoshiike
- Daniele Pucci

author_notes:
date: "2021-05-30T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "2021 IEEE International Conference on Robotics and Automation (ICRA)"
publication_short: "ICRA 2021"

abstract: 

# Summary. An optional shortened abstract.
summary: 

tags:
# - Source Themes
featured: true

# hugoblox:
#   ids:
#     arxiv: 

links:
  - type: pdf
    url: https://arxiv.org/abs/2104.13630
  # - type: code
  #   url: https://github.com/ami-iit/paper_rapetti_2023_icra_ergonomic_payload_lifting
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  - type: source
    url: "https://ieeexplore.ieee.org/abstract/document/9561623"
  - type: video
    url: "https://www.youtube.com/watch?v=PQ3dTbSXiP8"

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

Humans show specialized strategies for efficient collaboration. Transferring similar strategies to humanoid robots can improve their capability to interact with other agents, leading the way to complex collaborative scenarios with multiple agents acting on a shared environment. In this paper we present a control framework for robot-robot collaborative lifting. The proposed shared controller takes into account the joint action of both the robots thanks to a centralized controller that communicates with them, and solves the whole-system optimization. Efficient collaboration is ensured by taking into account the ergonomic requirements of the robots through the optimization of posture and contact forces. The framework is validated in an experimental scenario with two iCub humanoid robots performing different payload lifting sequences.