---
title: "Axiomatic Causal Interventions for Reverse Engineering Relevance Computation in Neural Retrieval Models"
author: "Catherine Chen, Jack Merullo, and Carsten Eickhoff"
collection: publications
permalink: publications/2024-axiomatic-causal-interventions
excerpt: ''
date: "2024-07-14"
venue: 'To appear in SIGIR 2024'
paperurl: ''
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Neural models have demonstrated remarkable performance across diverse ranking tasks. However, the processes and internal mechanisms along which they determine relevance are still largely unknown. Existing approaches for analyzing neural ranker behavior with respect to IR properties rely either on assessing overall model behavior or employing probing methods that may offer an incomplete understanding of causal mechanisms. To provide a more granular understanding of internal model decision-making processes, we propose the use of causal interventions to reverse engineer neural rankers, and demonstrate how mechanistic interpretability methods can be used to isolate components satisfying term-frequency axioms within a ranking model. We identify a group of attention heads that detect duplicate tokens in earlier layers of the model, then communicate with downstream heads to compute overall document relevance. More generally, we propose that this style of mechanistic analysis opens up avenues for reverse engineering the processes neural retrieval models use to compute relevance. This work aims to initiate granular interpretability efforts that will not only benefit retrieval model development and training, but ultimately ensure safer deployment of these models.

*Camera ready manuscript in preparation*

<!-- [Download paper here](https://aclanthology.org/2023.emnlp-main.901.pdf) -->

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). --> 