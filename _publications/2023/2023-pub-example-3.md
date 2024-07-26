---
title:          "M3REC: A Meta-based Multi-scenario Multi-task Recommendation Framework"
date:           2023-06-28 00:01:00 +0800
selected:       true
pub:            "In Proceedings of the 17th ACM Conference on Recommender Systems (RecSys ’23)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"
abstract: >-
  Users in recommender systems exhibit multi-behavior in multiple business scenarios on real-world e-commerce platforms. A crucial challenge in such systems is to make recommendations for each business scenario at the same time. On top of this, multiple predictions (e.g., Click Through Rate and Conversion Rate) need to be made simultaneously in order to improve the platform revenue. Research focus on making recommendations for several business scenarios is in the field of Multi-Scenario Recommendation (MSR), and Multi-Task Recommendation (MTR) mainly attempts to solve the possible problems in collaboratively executing different recommendation tasks. However, existing researchers have paid attention to either MSR or MTR, ignoring the integration of MSR and MTR that faces the issue of conflict between scenarios and tasks. To address the above issue, we propose a Meta-based Multi-scenario Multi-task RECommendation framework (M3REC) to serve multiple tasks in multiple business scenarios by a unified model. However, integrating MSR and MTR in a proper manner is non-trivial due to: 1) Unified representation problem: Users’ and items’ representation behave Non-i.i.d in different scenarios and tasks which takes inconsistency into recommendations. 2) Synchronous optimization problem: Tasks distribution varies in different scenarios, and a unified optimization method is needed to optimize multi-tasks in multi-scenarios. Thus, to unified represent users and items, we design a Meta-Item-Embedding Generator (MIEG) and a User-Preference Transformer (UPT). The MIEG module can generate initialized item embedding using item features through meta-learning technology, and the UPT module can transfer user preferences in other scenarios. Besides, the M3REC framework uses a specifically designed backbone network together with a task-specific aggregate gate to promote all tasks to achieve the purpose of optimizing multiple tasks in multiple business scenarios within one model. Experiments on two public datasets have shown that M3REC outperforms those compared MSR and MTR state-of-the-art methods.

cover:          /assets/images/covers/paper3.png
authors:
  - Zerong Lan
  - Yingyi Zhang
  - Xianneng Li#
links:
  Paper: https://dl.acm.org/doi/10.1145/3604915.3608828
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---