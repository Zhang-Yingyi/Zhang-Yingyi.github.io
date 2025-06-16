---
title:          "Modeling variational anchoring effect for recommender systems"
date:           2024-07-30 00:01:00 +0800
selected:       true
pub:            "KDD 2024 Workshop Amazon KDD Cup"
pub_date:       "2024"
abstract: >-
  Users generally have a tendency to rely on numerical information of recommendations presented on the web page when judging the recommended items, which refers to a classic psychological concept, anchoring effect. Learning users' psychology from explicit behaviors has been widely applied in RS and performs well on capturing user preferences and guiding the prediction tasks of recommendations. Recent studies have empirically proven that the anchoring effect can mislead users to click/purchase items that are not liked in principle, which will bring bias and noise to behavior data. However, vast majority of existing recommendation algorithms trained on behavior data ignore the anchoring bias, which results in suboptimal recommendations. In this paper, we propose a novel method named Variational Anchoring Effect Encoder (VAEE) to model the anchoring effect and mitigate the anchoring bias for recommender systems. The proposed method mainly includes two steps: 1) User Anchoring Effect Module which aims to reconstruct the unanchored user preferences with a Variational Autoencoder (VAE)-based deep structure, and 2) User Anchoring Debias Module that generate the recommendation results with the reconstructed unbiased user representations. Extensive experiments on real-world datasets are conducted to demonstrate that reducing anchoring effect can bring particular improvement in AUC and the proposed VAEE is attachable to most existing recommendation models. We also compare the recommendation quality when using different anchoring feature subsets, which indicates that the learned representation of anchoring effect is authentic and truly effective to restore users’ true preferences.
cover:          /assets/images/covers/yudi_CAI.png
authors:
- Yudi Xiao
- Yingyi Zhang
- Xianneng Li#
links:
  Paper: https://ieeexplore.ieee.org/document/10605368
---