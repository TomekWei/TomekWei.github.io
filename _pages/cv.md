---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **University of Illinois Urbana-Champaign (UIUC), Urbana, IL, USA**  
  B.S. in Math & Computer Science, Expected 06/2026  
  * Relevant Courses: AI Efficiency: Sys. & Algor. (CS598), Machine Learning Systems (CS498), Distributed Systems (CS425), Parallel Programming (CS483), System Programming / Operating System  

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

* Wei, T., et al. *RecScale: System-Aware Scaling Laws for Deep Learning Recommendation Models.*  
  Under submission to the 21st ACM European Conference on Computer Systems (EuroSys 2026).

* Fan, J., Wei, T., et al. *Adaptive Divergence Regularized Policy Optimization for Fine-tuning Generative Models.*  
  Accepted at the Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025).

* Venkatraman, A., Cao, H., Wei, T., et al. *MSAFlow: A Unified Approach for MSA Representation, Augmentation, and Family-based Protein Design.*  
  Accepted at the NeurIPS AI4Science Workshop 2025; Under submission to the International Conference on Learning Representations (ICLR 2026).

Research Highlights
======
* **RecScale: System-Aware Scaling Laws for Deep Learning Recommendation Models** (Mar 2024 – Aug 2025)  
  - Developed a system-aware framework addressing memory/communication bottlenecks in scaling DLRMs.  
  - Achieved up to **16× memory reduction** and **3.3× speedup** on 64 GPUs, with preserved accuracy.  

* **Adaptive Divergence Regularized Policy Optimization (ADRPO)** (Mar 2025 – May 2025)  
  - Introduced adaptive regularization for RL fine-tuning of generative models.  
  - Enabled a **2B parameter SD3 model** to outperform **4.8B–12B baselines** in alignment, semantic control, and human preference metrics.  

* **MSAFlow: Unified Approach for MSA Representation, Compression, and Augmentation** (Mar 2025 – Aug 2025)  
  - Built a 130M-parameter generative autoencoder for multiple-sequence alignments.  
  - Reduced storage to **6.5%** while improving AF3 zero-shot structure prediction (TM-score 0.62 vs. 0.55 baseline).  

<!-- Skills
======
* **Programming Languages**: C/C++, Python, Java, Verilog, Arm Assembly  
* **Technologies**: MongoDB, Docker, OpenCV, PyTorch, TorchRec  
* **Core Courses**: AI Efficiency, ML Systems, Distributed Systems, Parallel Programming, Operating Systems   -->

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
No experience yet.

Service and Leadership
======
To be updated.
