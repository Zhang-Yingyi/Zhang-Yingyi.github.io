---
title:          "Causality-aware Graph Aggregation Weight Estimator for Popularity Debiasing in Top-K Recommendation"
date:           2025-11-05 00:01:00 +0800
selected:       true
pub:            "CIKM 2025 Research Track"
pub_date:       "2025"
abstract: >-
  Graph-based recommender systems leverage neighborhood aggregation to generate node representations, which is highly sensitive to popularity bias, resulting in an echo effect during information propagation. Existing graph-based debiasing solutions refine the aggregation process with attempts such as edge reconstruction or weight adjustment. However, these methods remain inadequate in fully alleviating popularity bias. Specifically, this is because 1) they provide no insights into graph aggregation rationality, thus lacking an optimality guarantee; 2) they fail to well balance the training and debiasing process, which undermines the effectiveness.In this paper, we propose a novel approach to mitigate popularity bias through rational modeling of the graph aggregation process. We reveal that graph aggregation is a special form of backdoor adjustment in causal inference, where the aggregation weight corresponds to the historical interaction likelihood distribution. Based on this insight, we devise an encoder-decoder architecture, namely Causality-aware Graph Aggregation Weight Estimator for Debiasing (CAGED), to approximate the unbiased aggregation weight by optimizing the evidence lower bound of the interaction likelihood. In order to enhance the debiasing effectiveness during early training stages, we further design a momentum update strategy that incrementally refines the aggregation weight matrix. Extensive experiments on three datasets demonstrate that CAGED outperforms existing graph-based debiasing methods. Our implementation is available at https://github.com/QueYork/CAGED.
cover:          /assets/images/covers/Yue_CAGED.png
authors:
- Que Yue
- Yingyi Zhang
- Xiangyu Zhao#
- Chen Ma
links:
  Paper: https://dl.acm.org/doi/10.1145/3746252.3761155
---