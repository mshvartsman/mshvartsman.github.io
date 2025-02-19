---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
---

I am inspired by the foundational vision of scientists like [Newell](http://chil.rice.edu/tambo/teaching/psyc101GL/Newell%20%281973%29.pdf) and [Licklider](https://groups.csail.mit.edu/medg/people/psz/Licklider.html) and the sci-fi dream of downloading brains into computers. The realization of both these past visions and future dreams is still far, but it drives my interest of developing theory and tools for understanding how humans do stuff and how computers can help them or do it for them. I discuss some major lines of work below -- for a complete list of publications, see my [Publications page](/publications/). 

## Psychophysics and human perception ## 

Human perception is a sophisticated inference process by which people take ambiguous and noisy external stimuli and use it to build a coherent model of the world. While fundamental findings in the domain go back to the dawn of psychology and are well-explained by simple models such as the Weber-Fechner law, much remains unknown when it comes to complex stimuli, senses other than vision or audition, multisensory integration, and how perception is affected by other contextual information. As part of the [AEPsych](https://github.com/facebookresearch/aepsych) project, we bring sophisticated models from applied statistics and probabilistic machine learning to learn more in this domain. 

Owen, L., Browder, J., Letham, B., Stocek, G., Tymms, C., and **Shvartsman, M.**
(Submitted). Adaptive Nonparametric Psychophysics. Preprint available at arXiv:[2104.09549](https://arxiv.org/abs/2104.09549).

## Methods for neural data analysis ##

Probabilistic latent variable models applied to fMRI data have been successful in a variety of tasks, including identifying similarity patterns in neural data, aligning multi-subject datasets, identifying brain network topologies, and mapping between brain and behavior. We use matrix-variate normal models to unify some of these methods into a single framework, which gives us gain the ability to reuse noise modeling assumptions, algorithms, and code across models.

### Selected publications: ###
Kumar, M., ..., **Shvartsman, M.**, et al. (Submitted). BrainIAK: The Brain Imaging Analysis Kit. Preprint available at OSF: [10.31219/osf.io/db2ev](https://osf.io/db2ev/). 

Cai, M. B., **Shvartsman, M.**, Wu, A. Zhang, H. and Zhu, X. (2020). Incorporating
structured assumptions with probabilistic graphical models in fMRI data analysis.
Neuropsychologia, 144:107500. doi:[10.1016/j.neuropsychologia.2020.107500](https://doi.org/10.1016/j.neuropsychologia.2020.107500)

Boring, M., Ridgeway, K., **Shvartsman, M.**, and Jonker, T. (2020). Continuous
decoding of cognitive load from electroencephalography reveals task-general and taskspecific
correlates. Journal of Neural Engineering. doi:[10.1088/1741-2552/abb9bc](https://doi.org/10.1088/1741-2552/abb9bc)

**Shvartsman, M.**, Aoi, M., Charles, A., Sundaram, N., Wilke, T., and Cohen, J.  Matrix-normal models for fMRI analysis. AISTATS 2018. Extended version on arXiv:[1711.03058](https://arxiv.org/abs/1711.03058). 

## The dynamics of human decision-making ##

Combining information from perception and memory to make decisions in real time is the fundamental perception-action feedback loop that describes humans' (and machines') ability to interact with the world. Random walk models are a de facto standard theory of the dynamics of simple two-alternative decisions in humans and animals, with work going back to the 1960s bolstered by modern neuroscientific evidence. But those models don't straightforwardly handle more challenging settings, for example when a memory retrieval might change the internal context in the middle of a decision, when there are more than two alternatives, unknown evidence distributions, sequences of decisions, and so on. In many such settings, those models become difficult to analyze, intractable to estimate, or both. I'm interested in pushing these models in those challenging directions in a way that retains their nice properties while bringing them into more complicated tasks and settings. 

### Selected publications: ###

**Shvartsman, M.**, Srivastava, V., and Cohen, J. D. (2017) Exploring fixed-threshold and optimal policies in multi-alternative decision making. Poster presented at the Multi-disciplinary Conference on Reinforcement Learning and Decision Making (RLDM), Ann Arbor, MI. [pdf](/files/rldm2017/shvartsmanSrivastavaCohen_rldm2017_submitted.pdf)  
**Shvartsman, M.**, Srivastava, V., Sundaram, N., and Cohen, J. D. (2016) Using behavior to decode allocation of attention in context dependent decision making. In Reitter, D., and Ritter, F., Proceedings of the 14th International Conference on Cognitive Modeling (ICCM 2016). [pdf](/files/shvartsman_iccm2016_cameraready.pdf)  
**Shvartsman, M.**, Srivastava, V., and Cohen, J. D. (2015). A Theory of Decision Making under Dynamic Context. In Cortes C., Lawrence N.D., Lee D.D., Sugiyama M., and Garnett R., Proceedings of Advances in Neural Information Processing Systems 28\. [pdf](/files/nips2015/shvartsmanSrivastavaCohen_nips2015_cameraready.pdf), [code](https://github.com/mshvartsman/cddm).  


## Psycholinguistics ## 

My dissertation was concerned with understanding adaptive eye-movement behavior in a simple wordlist-reading task. By abstracting away from sentence-level complexity, I was able to investigate the way that moment-by-moment eye movement decisions are jointly driven by the ongoing process of word recognition and the memory of previous words. Other projects in this domain drive at the way people use their working memory to understand sentences, 

Some key findings:

*   Participants in our simple wordlist-reading task adapt their behavior to differences in quantitatively-expressed payoff, this adaptation is expressed in small but significant differences on the level of individual saccade decisions, and an adaptive model that is trying to optimize behavior in this task makes the same adaptation.
*   Spillover lexical frequency effects — the robust fact that a high-frequency word results in the following word being read faster — cannot be solely a simple consequence of parafoveal preview alone, excluding a prominent candidate explanation for the effect (provided by the E-Z Reader model of Reichle and colleagues).
*   Memory-driven sampling of past input can explain spillover effects in the absence of parafoveal preview, and doing so may in fact be adaptive under certain conditions.

### Selected publications: ###
Parker, D., **Shvartsman, M.**, & Van Dyke, J. A. (2017). The cue-based retrieval theory of sentence comprehension: New findings and new challenges. In Escobar, L., Torrens, V., Parodi, T. (eds.) Language Processing and Disorders. Newcastle: Cambridge Scholars Publishing. 
**Shvartsman, M.**. (2014). Adaptive eye movement control in a simple linguistic task. Ph.D thesis, University of Michigan. [pdf](/files/shvartsman_thesis.pdf).  
**Shvartsman, M.**, Lewis, R. L., and Singh, S. (2014). Computationally Rational Saccadic Control: An Explanation of Spillover Effects Based on Sampling from Noisy Perception and Memory. In Demberg, W. and O'Donnell, T., Proceedings of the 5th Workshop on Cognitive Modeling and Computational Linguistics, Baltimore. [pdf](/files/shvartsman-et-al-2014-cmcl.pdf)  
Lewis, R. L., **Shvartsman, M.**, and Singh, S. (2013). The adaptive nature of eye movements in linguistic tasks: how payoff and architecture shape speed-accuracy trade-offs. _Topics in Cognitive Science_, 5(3), 581–610\. DOI: [10.1111/tops.12032](http://dx.doi.org/10.1111/tops.12032). [pdf](/files/LewisShvartsmanSingh2013.pdf).  
