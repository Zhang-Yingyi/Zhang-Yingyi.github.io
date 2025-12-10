---
title:          "Entire Cost Enhanced Multi-Task Model for Online-to-Offline Conversion Rate Prediction"
date:           2022-08-11 00:01:00 +0800
selected:       true
pub:            "DL4SR’22: Workshop on Deep Learning for Search and Recommendation, co-located with the 31st ACM International Conference on
Information and Knowledge Management (CIKM)"
pub_date:       "2022"
abstract: >-
  Predicting users’ conversion rate (CVR) is essentially important for ranking systems in industrial Online-to-Offline (O2O) applications. Numerous efforts have been made in CVR modeling to achieve state-of-the-art performance. However, existing methods mainly focus on the Business-to-Customer (B2C) scenario, which makes implementations to O2O meet with mixed success. This can be revealed via several scenario-specific challenges. For example, O2O users in different locations generally encounter different candidates of surrounding stores. This leads to users’ behavioral regularity becoming essentially prominent. Besides, O2O users’ conversion includes a two-stage cost, i.e., online order cost and offline transportation cost. This inspires that users’ location sensitivity deserves additional attention compared with conventional scenarios. Motivated by these characteristics, we propose a novel CVR prediction method for the O2O scenario, named Entire Cost enhanced Multi-task Model (ECMM): i) users’ historical behavior sequences across different locations are modeled to capture the users’ preference of behavioral regularity; ii) both online order cost and offline transportation cost are modeled to predict the users’ aggregated preference for conversion. By designing two novel attention mechanisms, i.e., convert attention and sliding window attention, ECMM can be trained end-to-end to appropriately fit O2O characteristics. Extensive experiments have been carried out under a real-world industrial O2O platform Meituan. Both offline and rigorous online A/B tests under the billion-level data scale demonstrate the superiority of the proposed ECMM over the highly optimized state-of-the-art baselines.

cover:          /assets/images/covers/paper2022.png
authors:
  - Yingyi Zhang
  - Xianneng Li#
  - Yahe Yu
  - ect.
links:
  Paper: https://ceur-ws.org/Vol-3317/Paper4.pdf
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---