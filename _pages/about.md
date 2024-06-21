---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Jason Kong, a 2nd-year undergrad student in the CSE department at UC San Diego, working under the guidance of Professor. Tajana Rosing. My research focuses on hardware-software co-design and LLM systems. 

**Current Research**
======
I am currently engaged in cutting-edge research in hyper-dimensional computing (HDC), processing-in-memory (PIM) architectures, and compression methods for large language models (LLMs), under the supervision of [Professor Tajana Šimunić Rosing](https://cseweb.ucsd.edu/~trosing/) at the [PRISM center](https://prism.ucsd.edu/) and [SeeLab](http://varys.ucsd.edu/).

**Projects and Publications**
======
- **TinyAgent: Quantization-aware Model Compression and Adaptation for On-device LLM Agent Deployment**
  - **Abstract** Deploying LLMs on edge devices is challenging due to stringent memory resources and compute constraints. In edge applications, existing deployment solutions for LLM agents disaggregate the fine-tuning process for domain-specific adaptation and the post-training model compression process. As a result, it requires extensive experimentation to find a readily available model compression technique that minimizes a fine-tuned model's performance loss while satisfying a target hardware's memory constraints. To address this problem, we propose TinyAgent, which optimizes the deployment workflow by using a quantization-aware model compression technique for specialized decision-making LLM agents under resource-constrained environments. Our approach takes into account both deployment-time hardware constraints and challenges in post-training quantization during fine-tuning. Experimental results demonstrate that our approach not only achieves 8
 less memory usage to make LLM inference possible across a variety of edge devices, but also consistently speeds up LLM inference by up to 
 without compromising accuracy.
