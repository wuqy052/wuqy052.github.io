# Dissecting Social Attention in Autism through Large-Scale Remote Eye-tracking
Background:
Perceiving and engaging in conversations are reported as key challenges by autistic people. The increasing use of new
teleconferencing platforms, like Zoom, has made it more common to communicate and interact through these platforms.
However, there is limited research on how autistic individuals perceive and understand online conversations. In this study, we
measured gaze dynamics as autistic and non-autistic adults viewed online conversations, using a novel webcam-based eye
tracking technology.
Objectives:
Using WebGazer, an open-source package for webcam-based eye tracking, our study aimed to:
1. Validate the use of a webcam-based remote eye-tracking method in autistic populations
2. Build computational models that predict individual gaze preferences incorporating multiple factors, such as visual and
conversational features
3. Quantitatively compare how these different features influence attention allocation across the wide spectrum of autistic
traits
Methods:
Adult participants (N = 58; 29 autistic) watched four videos (2.5 to 4 minutes each) depicting online conversations among four
characters (occupying four quadrants on the screen). The videos were created based on custom scripts, varying in turn-taking
speed (fast vs. slow) and overall tone (neutral vs. emotional). In each video, features of interest were annotated and categorized
into three main types: the speaker at each moment (“speaker”), facial expressions and body gestures (“movement”), and other
distractions in the background (“object”). We preprocessed the data to precisely estimate the moment-to-moment quadrant
location of the gaze. We quantified weights of attention allocation (i.e., attention weights) for each of the features through
regression models fitted to each individual’s gaze patterns for each video. These attention weights were then analyzed in relation
to participants’ autistic traits. We further explored attention shifts over time using a hidden Markov model.
Results:
Data quality, as assessed by two validation schemes (4-dot validation and quadrant-based image free-viewing), was good and
comparable between groups (t(56) = 1.23, p = 0.22). The regression analysis revealed reduced attention weights for the “speaker”
feature in autistic participants compared to the non-autistic group; that is, greater self-reported autistic traits (from the Autism
Spectrum Quotient) were correlated with reduced gaze onto a person in the video when that person was speaking (r = -0.35, p =
0.016), particularly for videos with longer turn-taking durations. Furthermore, the subsequent hidden Markov modeling suggested
that autistic traits are associated with a greater tendency to switch attention from looking at speakers to random states (e.g.,
looking at irrelevant features or mind wandering) (r = 0.31, p = 0.025). These findings are now being replicated in a larger
sample and will be linked to validated autism diagnoses in our planned future work. 

Conclusions:
In this study, we characterized attention differences while watching online conversations in autistic and non-autistic individuals
across the autism spectrum. Our study also established a pipeline for employing remote webcam-based methods, laying the
groundwork for larger-scale studies with more diverse samples, to better understand the heterogeneity in visual social
engagement behaviors and potential subgroups within the autism spectrum. 


In May 2024, I presented some preliminary results in the oral session "8B — Social Cognition and Social Behavior" at the International Society for Autism Research (INSAR) 2024 Annual Meeting. [Abstract book]

We are currently working on a pre-registered experiment using the same paradigm: 
T