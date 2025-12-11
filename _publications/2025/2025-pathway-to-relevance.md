---
title:          "Pathway to Relevance: How Cross-Encoders Implement a Semantic Variant of BM25"
date:           2025-04-06 00:00:00 +0800
selected:       true
pub:            "EMNLP"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Mechanistic interpretation has greatly contributed to a more detailed understanding of generative language models, enabling significant progress in identifying structures that implement key behaviors through interactions between internal components. In contrast, interpretability in information retrieval (IR) remains relatively coarse-grained, and much is still unknown as to how IR models determine whether a document is relevant to a query. In this work, we address this gap by mechanistically analyzing how one commonly used model, a cross-encoder, estimates relevance. We find that the model extracts traditional relevance signals, such as term frequency and inverse document frequency, in early-to-middle layers. These concepts are then combined in later layers, similar to the well-known probabilistic ranking function, BM25. Overall, our analysis offers a more nuanced understanding of how IR models compute relevance. Isolating these components lays the groundwork for future interventions that could enhance transparency, mitigate safety risks, and improve scalability.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Meng Lu
  - Catherine Chen
  - Carsten Eickhoff
links:
  Paper: https://aclanthology.org/2025.emnlp-main.1297/
  Code: https://github.com/mlu108/CrossEncoderBM25
---
