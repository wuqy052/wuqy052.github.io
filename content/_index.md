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
    id: featureproject
    content:
      title: 🔎 Featured Research
      text: Two main projects during my PhD research. 
      filters:
        folders:
          - project_attention
          - project_learning
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: card
    id: news
    content:
      title: News & Highlights
      items:
        - title: Interview with Nature
          subtitle: 2024-11-01
          content: |
            My research on social attention in autism was featured in Nature.  
            [Read article](https://www.nature.com/articles/example)
          image: /images/news/nature-spotlight.jpg

        - title: Lab Website Launched
          subtitle: 2023-06-20
          content: |
            We launched our new lab website showcasing projects and people.  
            [Visit lab site](https://mylab.example.com)
          image: /images/news/lab-site.png
    design:
      columns: 1
      view: compact
---
