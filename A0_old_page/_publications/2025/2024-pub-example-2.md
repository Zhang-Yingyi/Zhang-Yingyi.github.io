---
title:          "LSRP: A Leader-Subordinate Retrieval Framework for Privacy-Preserving Cloud-Device Collaboration"
date:           2025-08-05 00:01:00 +0800
selected:       true
pub:            "KDD 2025 Research Track"
pub_date:       "2025"
abstract: >-
  Cloud-device collaboration leverages on-cloud Large Language Models (LLMs) for handling public user queries and on-device Small Language Models (SLMs) for processing private user data, collectively forming a powerful and privacy-preserving solution. However, existing approaches often fail to fully leverage the scalable problem-solving capabilities of on-cloud LLMs while underutilizing the advantage of on-device SLMs in accessing and processing personalized data. This leads to two interconnected issues: 1) Limited utilization of the problem-solving capabilities of on-cloud LLMs, which fail to align with personalized user-task needs, and 2) Inadequate integration of user data into on-device SLM responses, resulting in mismatches in contextual user information. In this paper, we propose a Leader-Subordinate Retrieval framework for Privacy-preserving cloud-device collaboration (LSRP), a novel solution that bridges these gaps by: 1) enhancing on-cloud LLM guidance to on-device SLM through a dynamic selection of task-specific leader strategies named as user-to-user retrieval-augmented generation (U-U-RAG), and 2) integrating the data advantages of on-device SLMs through small model feedback Direct Preference Optimization (SMFB-DPO) for aligning the on-cloud LLM with the on-device SLM. Experiments on two datasets demonstrate that LSRP consistently outperforms state-of-the-art baselines, significantly improving question-answer relevance and personalization, while preserving user privacy through efficient on-device retrieval. 
cover:          /assets/images/covers/LSRP.png
authors:
- Yingyi Zhang
- Pengyue Jia
- Xianneng Li#
- Xiangyu Zhao#
- etc.
links:
  Paper: https://arxiv.org/abs/2505.05031
---