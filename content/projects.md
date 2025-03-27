---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '2rem'

# Page sections
sections:
  - block: markdown
    id: projectoverview
    content:
      title: ''
      text: |
        ![Overview](/images/wordcloud.png) 
        I study the social dimensions of cognition — how attention, perception, learning, and decision-making are shaped by social context.
        
        This includes processing socially meaningful stimuli, learning about or from others, and making decisions during interpersonal interactions.
        
        Many of these processes are altered in psychiatric conditions. My research aims to develop novel tasks and computational models to better understand and characterize social functioning challenges in clinical populations.
        
  - block: collection
    id: socialattn
    content:
      title: Social Attention
      text: I study social attention using eye-tracking (ET) across screen-based, webcam-based, and smartphone platforms. I apply feature-based visual saliency models to capture individual differences in attention allocation during naturalistic video viewing.
      filters:
        folders:
          - project_attention
    design:
      view: showcase
      fill_image: false
  - block: collection
    id: sociallearn
    content:
      title: Social Learning
      text: Another key focus of my research is social learning, particularly observational learning. I investigate the underlying neuro-computations of different learning strategies using computational modeling and neuroimaging.
      filters:
        folders:
          - project_learning
      design:
        view: showcase
---
