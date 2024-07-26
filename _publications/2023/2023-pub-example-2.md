---
title:          "Meta-Generator Enhanced Multi-Domain Recommendation"
date:           2023-01-11 00:01:00 +0800
selected:       true
pub:            "In Companion Proceedings of the ACM Web Conference 2023 (WWW’23 Companion - industry truck)"
pub_date:       "2023"
abstract: >-
  Large-scale e-commercial platforms usually contain multiple business fields, which require industrial algorithms to characterize user intents across multiple domains. Numerous efforts have been made in user multi-domain intent modeling to achieve state-of-the-art performance. However, existing methods mainly focus on the domains having rich user information, which makes implementation to domains with sparse or rare user behavior meet with mixed success. Hence, in this paper, we propose a novel method named Meta-generator enhanced multi-Domain model (MetaDomain) to address the above issue. MetaDomain mainly includes two steps, 1) users’ multi-domain intent representation and 2) users’ multi-domain intent fusion. Specifically, in users’ multi-domain intent representation, we use the gradient information from a domain intent extractor to train the domain intent meta-generator, where the domain intent extractor has the input of users’ sequence feature and domain meta-generator has the input of users’ basic feature, hence the capability of generating users’ intent with sparse behavior. Afterward, in users’ multi-domain intent fusion, a domain graph is used to represent the high-order multi-domain connectivity. Extensive experiments have been carried out under a real-world industrial platform named Meituan. Both offline and rigorous online A/B tests under the billion-level data scale demonstrate the superiority of the proposed MetaDomain method over the state-of-the-art baselines. Furthermore comparing with the method using multi-domain sequence features, MetaDomain can reduce the serving latency by 20%. Currently, MetaDomain has been deployed in Meituan one of the largest worldwide Online-to-Offline(O2O) platforms.

cover:          /assets/images/covers/paper2.png
authors:
  - Yingyi Zhang*
  - Xianneng Li*
  - Yahe Yu
  - ect.
links:
  Paper: https://dl.acm.org/doi/10.1145/3543873.3584652
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---