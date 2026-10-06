---
title:          "RankSteer: Can Pointwise LLM Rankers Be Calibrated at the Representation Level?"
date:           2026-10-01 00:00:00 +0800
selected:       true
pub:            "EMNLP"
pub_pre:        ""
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  Large language models (LLMs) are strong zero-shot pointwise rankers, but lag behind pairwise and listwise methods. Beyond missing comparative signals, we identify a calibration gap: ranking-relevant information encoded in hidden states is not fully captured by the scalar output head. We propose RankSteer, a post-hoc activation-steering framework that calibrates ranking via projection-based interventions along multiple directions at inference time: decision, evidence, and, optionally, role. This is achieved without updating model weights or introducing cross-document comparisons. We instantiate RankSteer on two structurally distinct pointwise variants %4. What did we find and observe improvements over their respective baselines on most TREC DL and BEIR datasets across three backbones. This suggests that the calibration gap is a general property of pointwise rankers. Our additional geometric analysis shows that steering improves ranking by concentrating each query's document representations along an existing ranking geometry, offering new insight into how LLMs internally represent and calibrate relevance judgments.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Yumeng Wang
  - Catherine Chen
  - Suzan Verberne
links:
  Paper: https://arxiv.org/abs/2602.03422
---
