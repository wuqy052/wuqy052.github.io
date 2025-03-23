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
      title: Cognitive Neuroscience * Social Processes * Psychiatry
      text: |
        ![Overview](/images/wordcloud.png) 

        I am broadly interested in the social component of cognitions - attention, perception, learning, and decision-making. 
        
        The social component can be a socially meaningful sensory stimuli, a learning task that involves the knowledge about or from another person, or a decision that is made during the interaction with others. 
        
        A lot of these processes are affected in psychiatric conditions. Part of my research is to develop novel paradigms and computational models to characterize the challenges of social functioning in clinical populations.
        
  - block: collection
    id: socialattn
    content:
      title: Social Attention
      text: I study social attention through eye-tracking (ET), including screen-based ET, webcam-based ET, and smartphone ET. I apply feature-based visual saliency models to characterize individual differences in attention allocations during video free viewing. 
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
      text: Another main focus of my research is the study of social learning, especially observational learning. I'm interested in understanding the neuro-computations of different learning strategies through computational models and neuroimaging.  
      filters:
        folders:
          - project_learning
      design:
        view: showcase
---
