---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: View Projects
        url: /projects/
    design:
      css_class: ""
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 0.85
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: What I build
      subtitle: ''
      text: |-
        I work on practical software that sits between research, experimentation, and product thinking.

        - Research tools for psychology and behavioral experiments
        - Fast prototypes and hackathon-style product ideas
        - Lightweight web apps, automations, and data workflows

        I like building things that are useful, simple, and easy to keep improving.
    design:
      columns: '1'
  - block: collection
    content:
      title: Selected Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3
---
