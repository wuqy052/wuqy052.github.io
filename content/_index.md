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
  - block: timeline
    content:
      title: News & Highlights
      items:
        - title: Interview with Nature
          date: 2024-11-01
          text: |
            My research on social attention in autism was featured in Nature's Spotlight series.  
            <a href="https://www.nature.com/articles/example" target="_blank" class="text-blue-600 underline">Read the article</a>.
          image: /images/news/nature-spotlight.jpg

        - title: Lab Website Launched
          date: 2023-06-20
          text: |
            I launched my lab’s official website showcasing our latest projects and collaborators.  
            <a href="https://mylab.example.com" target="_blank" class="text-blue-600 underline">Visit the lab website</a>.
          image: /images/news/lab-site.png

---
