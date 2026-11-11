---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. student at the **Institute for Interdisciplinary Information Sciences, Tsinghua University**, advised by [Prof. Yang Gao](https://yang-gao.weebly.com/). I received my B.E. in Automation from the IEEE Honor Class at **Shanghai Jiao Tong University**. I study how robots perceive, act, and keep improving in the physical world. My research is in robotics and embodied AI, including agentic robotics, reliable evaluation of robot policies, and autonomous policy improvement.


I mainly write in Python, C++, and Matlab, and I care about readable names, clear comments, a clean file layout, and careful commit history.

# 🎖 Honors and Awards
- *2023.10* COSCO Scholarship
- *2022.10* Suzhou Yu Cai Scholarship
- *2022.4* COMAP, M Prize
- *2021.10* SJTU Scholarship, Grade B

# 📖 Educations
- *2024.09 - now*, PhD. student, Institute for Interdisciplinary Information Sciences, Tsinghua University, Beijing.  
- *2020.09 - 2024.06*, B.E., Shanghai Jiao Tong University, Shanghai.  
  **Score**: 91.02/100 **Rank**: 1/28

# 💬 Language
- *CET6* 660
- *TOEFL* 104 (Reading 29, Listening 29, Speaking 22, Writing 24)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2027 Inproceeding</div><img src='images/skill-space-shooting.png' alt="Skill-Space Shooting loop. A likely failure interrupts the rollout. The robot tries a skill from a shared library and learns from verified repairs." width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skill-Space Shooting for Autonomous Robot Policy Improvement](https://arxiv.org/abs/2609.38178)

Zihang Rui\*, Renhao Wang\*, Haoxu Huang, Yang Gao

[**Project Page**](https://skill-space-shooting.github.io/) | [**Paper**](https://arxiv.org/abs/2609.38178)
- Skill-space shooting improves a robot task policy without minimal human intervention. When a failure is likely, the robot tries a reusable skill, and a foundation model selects and checks the repair.
- Successful repair segments become imitation-learning supervision. Shared skills also reduce the teaching needed to improve on new tasks.
- \*Equal contribution. Submitted to ICLR 2027.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2027 Inproceeding</div><img src='images/ci-mse.jpg' alt="Critical Interval MSE" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Critical Interval MSE: Toward Reliable Offline Validation for Robot Manipulation Policies](https://arxiv.org/abs/2606.29898)

Haoxu Huang, Tongsam Zheng, Yifan Chen, Jiacheng You, Yang Gao

[**Project Page**](https://ci-mse.github.io/) | [**Paper**](https://arxiv.org/abs/2606.29898) | [**Code**](https://github.com/CI-MSE/CI-MSE)
- CI-MSE is an offline validation metric that scores manipulation policies only on task-critical segments, such as contact, grasping, insertion, and fine alignment.
- With rollout-time action alignment, it tracks real rollout success more closely than raw MSE: Spearman correlation improves from −0.61 to −0.87 across 27 policy checkpoints.
- Submitted to ICRA 2027.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/copa.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models](https://arxiv.org/abs/2403.08248)

Haoxu Huang, Fanqi Lin, Yingdong Hu, Shengjie Wang, Yang Gao

[**Project Page**](https://copa-2024.github.io/)
- CoPa is a novel framework that incorporates common sense knowledge embedded within foundation vision-language models (VLMs), such as GPT-4V, into the low-level robotic manipulation tasks. 
- CoPa is capable of handling diverse open-set instructions and objects in a zero-training manner. 
</div>
</div>


