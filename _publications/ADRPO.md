---
title: "Adaptive Divergence Regularized Policy Optimization for Fine-tuning Generative Models."
collection: publications
permalink: /publication/ADRPO
excerpt: 'We propose ADRPO, a method that dynamically adjusts divergence regularization strength based on advantage estimates, enabling more effective fine-tuning of generative models by automatically balancing exploration and exploitation at the sample level.'
date: 2025-09-27
venue: 'Sep 27, 2025'
paperurl: 'http://TomekWei.github.io/files/13815_Adaptive_Divergence_Regu.pdf'
citation: 

---
### Keywords
Reinforcement learning, generative models, adaptive regularization, advantage estimation, fine-tuning, flow matching, text-to-image generation, exploration-exploitation trade-off

### TL;DR
We propose ADRPO, a method that dynamically adjusts divergence regularization strength based on advantage estimates, enabling more effective fine-tuning of generative models by automatically balancing exploration and exploitation at the sample level.

### Abstract
Balancing exploration and exploitation during reinforcement learning fine-tuning of generative models presents a critical challenge, as existing approaches rely on fixed divergence regularization that creates an inherent dilemma: strong regularization preserves model capabilities but limits reward optimization, while weak regularization enables greater alignment but risks instability or reward hacking. 

We introduce Adaptive Divergence Regularized Policy Optimization (ADRPO), which automatically adjusts regularization strength based on advantage estimates—reducing regularization for high-value samples while applying stronger regularization to poor samples, enabling policies to navigate between exploration and aggressive exploitation according to data quality.  

Our implementation with Wasserstein-2 regularization for flow matching generative models achieves remarkable results on text-to-image generation, achieving better semantics alignment and diversity than offline methods like DPO and online methods with fixed regularization like ORW-CFM-W2.  

ADRPO also enables 2B parameter SD3 model to surpass much larger models with 4.8B and 12B parameters in attribute binding, semantic consistency, artistic style transfer, and compositional control while maintaining generation diversity.  

ADRPO can also generalize to KL-regularized LLM fine-tuning, enhancing existing online RL methods like GRPO while requiring no additional networks or complex architectural changes. In LLM fine-tuning tasks, we observe that ADRPO even demonstrates an emergent ability to escape local optima by actively increasing exploration to discover superior policies, thus offering an effective, plug-and-play solution to the exploration-exploitation challenge in generative model fine-tuning.


[Full Paper (PDF)](http://TomekWei.github.io/files/13815_Adaptive_Divergence_Regu.pdf)
