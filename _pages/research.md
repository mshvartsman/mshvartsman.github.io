---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
---

My primary research interest is in building a computationally-implementable theory of human behavior and estimating it jointly from neural and behavioral data. This is a baby step towards the sci-fi dream of downloading brains into computers! I discuss some major lines of work below -- for a complete list of publications, see my [Publications page](/publications/). 

## The dynamics of decision-making from multiple stimuli ##

Combining information from perception and memory to make decisions in real time is the fundamental perception-action feedback loop that describes humans' (and machines') ability to interact with the world. Random walk models are a de facto standard theory of the dynamics of simple two-alternative decisions, with work going back to Stone's 1960 application of Wald's 1948 sequential probability ratio test (SPRT) and more recently supported by a wealth of neuroscientific evidence from labs like Shadlen's, Brody's and others. But those models don't straightforwardly handle more challenging settings, for example when a memory retrieval might change the internal context in the middle of a decision, when there are more than two alternatives, unknown evidence distributions, sequences of decisions, and so on. In many such settings, those models become difficult to analyze, intractable to estimate, or both. I'm interested in pushing these models in those challenging directions in a way that retains their nice properties while bringing them into more complicated tasks and settings. Some key findings:

*  A wide number of psychological lab tasks (e.g. Stroop, Flanker, AX-CPT, Cueing, prospective memory) can be modeled as the process of combining information from two sources to make a single decision.
*  Using this understanding, we developed a single model that covers the above tasks, and potentially others. We used it to make cross-task predictions using parameter estimates in other authors' papers, and infer the allocation of attention between stimuli or evidence sources from behavior.
*  In a separate line of work, we undertook rational analysis to investigate how certain behaviors in humans are consistent with rational decision making under a few distinct possible sets of computational bounds, and how the process of memory could be helpful for smoothing out the effects of misperceived stimuli. 

### Selected publications: ###

**Shvartsman, M.**, Srivastava, V., and Cohen, J. D. (2017) Exploring fixed-threshold and optimal policies in multi-alternative decision making. Poster presented at the Multi-disciplinary Conference on Reinforcement Learning and Decision Making (RLDM), Ann Arbor, MI. [pdf](/files/rldm2017/shvartsmanSrivastavaCohen_rldm2017_submitted.pdf)  
**Shvartsman, M.**, Srivastava, V., Sundaram, N., and Cohen, J. D. (2016) Using behavior to decode allocation of attention in context dependent decision making. In Reitter, D., and Ritter, F., Proceedings of the 14th International Conference on Cognitive Modeling (ICCM 2016). [pdf](/files/shvartsman_iccm2016_cameraready.pdf)  
**Shvartsman, M.**, Srivastava, V., and Cohen, J. D. (2015). A Theory of Decision Making under Dynamic Context. In Cortes C., Lawrence N.D., Lee D.D., Sugiyama M., and Garnett R., Proceedings of Advances in Neural Information Processing Systems 28\. [pdf](/files/nips2015/shvartsmanSrivastavaCohen_nips2015_cameraready.pdf), [code](https://github.com/mshvartsman/cddm).  

## Matrix-variate models of for neural data analysis ##

Probabilistic latent variable models applied to fMRI data have been successful in a variety of tasks, including identifying similarity patterns in neural data, aligning multi-subject datasets, identifying brain network topologies, and mapping between brain and behavior. We use matrix-variate normal models to unify some of these methods into a single framework, which gives us gain the ability to reuse noise modeling assumptions, algorithms, and code across models.

**Shvartsman, M.**, Aoi, M., Charles, A., Sundaram, N., Wilke, T., and Cohen, J.  Matrix-normal models for fMRI analysis. AISTATS 2018. Extended version on arxiv:[1711.03058](https://arxiv.org/abs/1711.03058). 

## Adaptive eye-movement control

My dissertation was concerned with understanding adaptive eye-movement behavior in a simple wordlist-reading task. By abstracting away from sentence-level complexity, I was able to investigate the way that moment-by-moment eye movement decisions are jointly driven by the ongoing process of word recognition and the memory of previous words. Some key findings:

*   Participants in our simple wordlist-reading task adapt their behavior to differences in quantitatively-expressed payoff, this adaptation is expressed in small but significant differences on the level of individual saccade decisions, and an adaptive model that is trying to optimize behavior in this task makes the same adaptation.
*   Spillover lexical frequency effects — the robust fact that a high-frequency word results in the following word being read faster — cannot be solely a simple consequence of parafoveal preview alone, excluding a prominent candidate explanation for the effect (provided by the E-Z Reader model of Reichle and colleagues).
*   Memory-driven sampling of past input can explain spillover effects in the absence of parafoveal preview, and doing so may in fact be adaptive under certain conditions.

### Selected publications: ###

**Shvartsman, M.**. (2014). Adaptive eye movement control in a simple linguistic task. Ph.D thesis, University of Michigan. [pdf](/files/shvartsman_thesis.pdf).  
**Shvartsman, M.**, Lewis, R. L., and Singh, S. (2014). Computationally Rational Saccadic Control: An Explanation of Spillover Effects Based on Sampling from Noisy Perception and Memory. In Demberg, W. and O'Donnell, T., Proceedings of the 5th Workshop on Cognitive Modeling and Computational Linguistics, Baltimore. [pdf](/files/shvartsman-et-al-2014-cmcl.pdf)  
Lewis, R. L., **Shvartsman, M.**, and Singh, S. (2013). The adaptive nature of eye movements in linguistic tasks: how payoff and architecture shape speed-accuracy trade-offs. _Topics in Cognitive Science_, 5(3), 581–610\. DOI: [10.1111/tops.12032](http://dx.doi.org/10.1111/tops.12032). [pdf](/files/LewisShvartsmanSingh2013.pdf).  
