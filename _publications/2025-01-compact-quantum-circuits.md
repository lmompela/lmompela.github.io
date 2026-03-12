---
title: "Compact Quantum Circuits for Martinican Creole LID: A Typologically Informed Proof-of-Concept"
collection: publications
permalink: /publication/2025-compact-quantum-circuits
excerpt: 'A proof-of-concept for language identification using quantum circuits for Martinican Creole.'
date: 2025-01-01
venue: 'QNLPAI 2025 Proceedings, Springer'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-032-13883-5_11'
citation: 'Mompelat, L. (2026). Compact Quantum Circuits for Martinican Creole LID: A Typologically Informed Proof-of-Concept. In: Cavar, D., Aggarwal, V., Busemeyer, J., Chen, S.YC. (eds) Quantum AI and NLP. QNLPAI 2025. Communications in Computer and Information Science, vol 2659. Springer, Cham.'
---

We present the first Quantum-Natural-Language-Processing (QNLP) proof of concept for token-level language identification in Martinican Creole, a low-resource language with substantial lexical overlap with French. Our approach compares: (1) a character-bigram baseline, (2) a classical logistic regression model trained on three interpretable intra-token features (entropy, vowel ratio, syllable complexity), and (3) a compact three-qubit variational circuit embedding the same features in product-state and entangled configurations.

On token-level macro-F1 and accuracy, the classical model performs slightly better than the entangled variant, reflecting its robustness on high-frequency items where individual features are most discriminative. However, a type-level analysis shows a different pattern: the entangled embedding reduces the number of distinct misclassified types and uniquely corrects a sizable subset that both the classical and product-state models miss. The rescued set is heterogeneous (i.e., mixing frequent Creole items and proper names with cross-lingual orthography), and some gains are dataset-contingent serendipitous effects, since the models are context-blind and rely only on intra-token features.

Our findings demonstrate that even minimal quantum embeddings can capture non-linear interactions between interpretable features in ways that simple linear models and product mappings cannot. The results highlight the potential of hardware-efficient QNLP for fine-grained, low-resource language identification, especially in settings where context is unavailable but token-internal cues are strong. We conclude with a roadmap for extending this work to richer feature sets, context-aware hybrid architectures, and cross-lingual transfer to other Creole and closely related language pairs.

 [Download paper here](https://link.springer.com/chapter/10.1007/978-3-032-13883-5_11)
