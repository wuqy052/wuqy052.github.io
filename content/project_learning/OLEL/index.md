---
title: Neuro-computations of Observational Learning vs. Experiential Learning
summary: How does the brain decide when to rely on others vs. past experience when making decisions?
date: 2025-03-01
weight: 5
tags:
  - Social Learning
  - Arbitration
  - fMRI
---
### An Ice Cream Decision
![ice cream problem](olel_1.png)
You’re at an ice cream shop with your friend Bob. There are three options: chocolate, vanilla, and strawberry.

- Bob gets chocolate again - last time he bought the chocolate one.
- You tried strawberry last time and didn’t like it.
- You assume Bob’s taste is similar to yours.

So, you choose chocolate—based on your own experience and Bob’s.

We face situations like this daily, where we blend firsthand experience with observed behavior. This study explores **the neuro-computational basis of how we integrate observational and experiential learning**.

### A Social Pearl Hunting Task
To answer the question, I designed a social pearl hunting task, adapted from [Charpentier et al., 2024 ](https://www.nature.com/articles/s41467-024-48548-y).

![social pearl hunting task](olel_2.png)

Participants gather pearls using two information sources:
1. **Observational learning (OL)**: Watch a partner choose a coral, then see the resulting shell. The partner knows which shell is better but can only choose corals.
2. **Experiential learning (EL)**: Choose a shell and receive direct feedback (pearl or not).

### Disentangling Observational and Experiential Strategies

![OL strategy](olel_3.png "OL consistent choice: the partner chooses blue-orange coral,, which generates a blue shell. next they repeat their choice, indicating their preference for a blue shell")
In an **OL-consistent choice**, one infers the preference of the partner by observing two consecutive trials - whether the partner repeat the coral choice (they want the current shell), or switch the coral choice (they want the other shell).

![EL strategy](olel_4.png "EL consistent chioce: yourself choose blue and do not see a pearl, the next trial you should switch to yellow") 
In an **EL-consistent choice**, one repeat the past choice if that choice yielded a pearl, and switch otherwise.

### Reliability-based Arbitration

![Computational framework](olel_5.png "Reliability-based arbitration model") 
We propose a **reliability-based arbitration model** to explain the decisions: 
- Two systems compute shell values using prediction errors:
  - **State Prediction Error (SPE)** for OL: mismatch between predicted and actual shell from the partner’s coral.
  - **Reward Prediction Error (RPE)** for EL: mismatch between expected and actual reward.
 - Values computed from the two systems are flexibly combined based on the reliability - a function of the prediction errors. 

### Neural Signatures of Decision Systems

Where does the brain compute these values?

![OL and EL value](olel_6.png) 
We found the OL-based decision signal in the **dorsal medial prefrontal cortex (dmPFC), temporal-parietal junction (TPJ), and superior temporal gyrus (STG)**. EL-based decision value in the **ventromedial prefrontal cortex (vmPFC)**.
![Integrated value](olel_7.png)
We also saw the integrated decision value in both **vmPFC and STG**.


### Conference Talk
On Apr 2024, I presented the above results at the Social Affective Neuroscience Society (SANS) annual meeting as a Data Blitz titled **_Neuro-computational Mechanism Of Reliability-based Arbitration Between Observational And Experiential Learning_**. 

📥 **[Download PDF](uploads/OLEL_poster.pdf)**
<iframe src="/uploads/OLEL_poster.pdf#toolbar=0&navpanes=0&scrollbar=0" width="100%" height="600px"></iframe>

