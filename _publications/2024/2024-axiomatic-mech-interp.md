---
title:          "Axiomatic Causal Interventions for Reverse Engineering Relevance Computation in Neural Retrieval Models"
date:           2024-07-11 00:01:00 +0800
selected:       true
pub:            "SIGIR"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  Neural models have demonstrated remarkable performance across diverse ranking tasks. However, the processes and internal mechanisms along which they determine relevance are still largely unknown. Existing approaches for analyzing neural ranker behavior with respect to IR properties rely either on assessing overall model behavior or employing probing methods that may offer an incomplete understanding of causal mechanisms. To provide a more granular understanding of internal model decision-making processes, we propose the use of causal interventions to reverse engineer neural rankers, and demonstrate how mechanistic interpretability methods can be used to isolate components satisfying term-frequency axioms within a ranking model. We identify a group of attention heads that detect duplicate tokens in earlier layers of the model, then communicate with downstream heads to compute overall document relevance. More generally, we propose that this style of mechanistic analysis opens up avenues for reverse engineering the processes neural retrieval models use to compute relevance. This work aims to initiate granular interpretability efforts that will not only benefit retrieval model development and training, but ultimately ensure safer deployment of these models.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Catherine Chen
  - Jack Merullo
  - Carsten Eickhoff
links:
#   Code: https://github.com/luost26/academic-homepage
  Paper: https://dl.acm.org/doi/abs/10.1145/3626772.3657841
---
