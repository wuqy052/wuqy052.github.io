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
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: background.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: project
    content:
      title: Featured Research
      filters:
        folders:
          - project_attention
          - project_learning
        featured_only: true
    design:
      view: article-grid
      columns: 2

---
