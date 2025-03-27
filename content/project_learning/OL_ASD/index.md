---
title: Emulation and Imitation during Observational Learning
summary: With 2 large online datasets, I found that individuals with higher autistic traits are less likely to infer the others' goals.
date: 2025-03-01
weight: 2
tags:
  - Social Learning
  - Computational Psychiatry
  - Autism
featured: true
---

## Observational Learning

We learn about the world by observing others and inferring from social cues. Two strategies are typically involved during observational learning:
1. Goal emulation: inferring others’ goals and choosing actions based on that inference
2. Action imitation: directly copying observed actions without inferring goals

In this study, over 1,000 online participants completed a task designed to dissociate these two strategies.

![The observational learning task](ol_1.png "The Observational learning task. In ‘observe’ trials, participants saw the choice options of the agent—three slot machines, one was unavailable (grayed out)—followed by a video showing the partner’s action (button press) and the chosen slot machine (bent arm). In ‘play’ trials, participants saw their own choice options and made a response, followed by choice feedback (bent arm) and token feedback. The proportion of colors on each slot machine corresponds to the probability of generating each colored token from that slot machine.")

## Computational Models of Observational Learning

To capture participants’ strategies, we developed and compared several computational models:
1. Imitation model: repeat the partner's most recent action (left or right slot machine)
2. Emulation model: infers slot machine values through Bayesian learning based on the partner’s choice history
3. Fixed mixture model: combine imitation and emulation with a fixed probability
4. Dyanamic arbitration model: combine imitation and emulation with a changing probability, depending on the reliability of each strategy
5. Non-learning model: inattentive or task-irrelevant behaviors

![Computational models](ol_2.png "In the imitation model, action values are computed by the partner’s most recent action. In the emulation model, a player first updates the token value according to the partner’s choice, and then computes action values by combining token values and probabilities. The weight is a fixed parameter in the fixed mixture model and a changing variable in the dynamic arbitration model. Emulation bias represents a predisposition of emulation while flexibly updating the weight, trial by trial.")

## Individual differences in autistic traits

Human social behavior features profound individual differences. Some people are outgoing, others reclusive. Autism has emerged as a dimensional construct that underlines difficulties in social interaction and communication. 

Building on prior work linking autistic traits to social learning differences, we hypothesized that **individuals with higher levels of autism-like traits would be less likely to rely on emulation**.

A couple of results supported our hypothesis, here are two of them.

Using computational model fits, we grouped participants into four strategy types: a non-learning group, an imitation group, an emulation group, and a mixture group. Autistic trait scores varied across groups, with the lowest in the emulation group and highest in the non-learning group.

![Strategy groups](ol_3.png "Violin plots of the distribution of autistic score in each of the four strategy groups (error bars are centered at the mean and represent s.d.)")

Second, we looked at one parameter in the dynamic arbitration model - the emulation bias. This parameter represents one's inherent propensity of performing emulation over imitation, independent of the reliabilities of each strategy. We found that higher autistic traits were associated with reduced emulation bias.

![Emulation bias](ol_4.png "Correlation between emulation bias and autistic traits")


## Publication

Now published at _Nature Mental Health_ titled [Individual differences in autism-like traits are associated with reduced goal emulation in a computational model of observational learning](https://www.nature.com/articles/s44220-024-00287-1).

## On Media

Please also check the post about this work on _PsyPost_ [Autistic traits linked to specific pattern of social learning, study finds](https://www.psypost.org/autistic-traits-linked-to-specific-pattern-of-social-learning-study-finds/).



