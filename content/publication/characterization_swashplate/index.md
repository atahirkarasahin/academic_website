---
abstract: Reinforcement learning (RL) has demonstrated the ability to maintain the plasticity of the policy throughout short-term training in aerial robot control. However, these policies have been shown to loss of plasticity when extended to long-term learning in non-stationary environments. For example, the standard proximal policy optimization (PPO) policy is observed to collapse in long-term training settings and lead to significant control performance degradation. To address this problem, this work proposes a cost-aware framework that uses a retrospective cost mechanism (RECOM) to balance rewards and losses in RL training with a nonstationary environment. Using a cost gradient relation between rewards and losses, our framework dynamically updates the learning rate to actively train the control policy in a disturbed wind environment. Our experimental results show that our framework learned a policy for the hovering task without policy collapse in variable wind conditions and has a successful result of 11.72% less dormant units than L2 regularization with PPO.
# author_notes:
# - Equal contribution
# - Equal contribution
authors:
- Ali Tahir Karasahin
date: "2025-03-10T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2503.00282"
featured: true
image: 
  #caption: ""
  focal_point: ""
  preview_only: false
# projects:
# - example2
publication: arXiv
publication_short: ""
publication_types:
- "2"
publishDate: "2024-07-05T00:00:00Z"
slides: example
summary: Maintaining Plasticity in Reinforcement Learning: A Cost-Aware Framework for Aerial Robot Control in Non-stationary Environments
tags: []
title: Maintaining Plasticity in Reinforcement Learning: A Cost-Aware Framework for Aerial Robot Control in Non-stationary Environments
# url_code: ""
# url_dataset: ""
url_pdf: "https://arxiv.org/abs/2503.00282"
# url_poster: ""
# url_project: ""
# url_slides: ""
# url_source: ""
# url_video: ""
---
