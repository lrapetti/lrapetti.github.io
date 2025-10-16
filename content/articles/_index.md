---
title: 'Articles'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    content:
      text: |-
        A complete and updated list of articles can be found in [Google Scholar](https://scholar.google.com/citations?user=5M-IE-wAAAAJ&hl=en).
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
        - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
        - publications
        exclude_featured: false
    design:
      view: citation
---
