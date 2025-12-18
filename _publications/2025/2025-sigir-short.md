---
title:          "Towards Best Practices of Axiomatic Activation Patching in Information Retrieval"
date:           2025-07-13 00:00:00 +0800
selected:       false
pub:            "SIGIR"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
 Mechanistic interpretability research, which aims to uncover the internal processes of machine learning models, has gained significant attention. One state-of-the-art technique, activation patching, has been applied to analyzing neural ranker behavior in relation to information retrieval (IR) axioms. To date, however, this remains a rapidly evolving topic in IR, with no established methodology for measuring results or constructing datasets to ensure pronounced, robust, and consistent patching effects. In this study, based on experimental results, we provide recommendations on measuring patching effects and designing diagnostic datasets for investigating term frequency. We identify the rareness and informativeness of injected terms as a key factor influencing the magnitude of patching effects. Additionally, we find that low score differences between baseline and perturbed documents introduce significant noise, which can be mitigated by filtering or applying penalty scores to the metric. More generally, we provide practical recommendations for the reliable application of activation patching in IR, advancing future interpretability research of neural ranking models. Our code is available at https://github.com/polgrisha/best-practices-ir-patching.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Gregory Polyakov
  - Catherine Chen
  - Carsten Eickhoff
links:
  Paper: https://dl.acm.org/doi/abs/10.1145/3726302.3730256
  Code: https://github.com/polgrisha/best-practices-ir-patching
---
