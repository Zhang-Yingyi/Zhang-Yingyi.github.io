---
title:          "CuSMer: Multimodal Intent Recognition in Customer Service via Data Augment and LLM Merge"
date:           2025-05-23 00:01:00 +0800
selected:       true
pub:            "WWW 2025 Competition Track"
pub_date:       "2025"
abstract: >-
  The increasing complexity of e-commerce customer service (CS) scenarios, driven by rapid product evolution and user base growth, presents unique challenges for intent recognition. Unlike generic user-generated content (UGC), CS-UGC exhibits multimodal complexity (e.g., product inquiries, return requests) that traditional methods struggle to address due to (1) Limited CS domain-specific knowledge, which hampers the ability of large language models (LLMs) to handle multimodal CS data, and (2) The complexity and noise in CS UGC, which undermines the robustness of traditional approaches. In this paper, we propose Customer Service Augmented LLM Merge (CuSMer), a novel framework integrating semi-supervised learning with model merging techniques through dual pipelines: (i) pseudo-labeling → fine-tuning → LLM merging and (ii) image augmentation → fine-tuning → LLM merging. These piplines enhance the robustness of LLMs against noisy, out-of-distribution data while improving their multimodal understanding of CS scenarios. Evaluated on Alibaba's real-world datasets, CuSMer demonstrates superior robustness in noisy environments and enhanced multimodal understanding compared to baseline LLMs. It achieved third place in the first round and first place in the final round in the WWW25 - Competition: Multimodal Dialogue System Intent Recognition Challenge, validating its scalability and effectiveness for industrial CS applications.
cover:          /assets/images/covers/cusmer.png
authors:
- Zhipeng Li
- Binglin Wu
- Yingyi Zhang
- Xianneng Li#
links:
  Paper: https://dl.acm.org/doi/abs/10.1145/3701716.3718373
---