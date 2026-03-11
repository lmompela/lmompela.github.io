---
title: "Simple Morphology, Complex Models: A Benchmark Study and Error Analysis of POS Tagging for Martinican Creole"
collection: publications
permalink: /publication/2025-simple-morphology-complex-models
excerpt: 'A benchmark study and error analysis of part-of-speech tagging for Martinican Creole.'
date: 2025-01-03
venue: 'Proceedings of the 2025 Language models And RePresentations (LARP) Conference'
paperurl: 'https://aclanthology.org/2025.clasp-main.1/'
citation: 'Ludovic Mompelat. 2025. Simple Morphology, Complex Models: A Benchmark Study and Error Analysis of POS Tagging for Martinican Creole. In <i>Proceedings of the 2025 CLASP Conference on Language models And RePresentations</i> (LARP), pages 1–10, Gothenburg, Sweden. Association for Computational Linguistics.'
---

Part-of-speech (POS) tagging is a foundational task in NLP pipelines, but its development for Creole languages remains limited due to sparse annotated data and structural divergence from high-resource languages. This paper presents the first POS tagging benchmarks for Martinican Creole (MC) as well as a linguistically motivated evaluation framework, comparing three fine-tuned transformer-based models (mBERT, XLM-Roberta, and CreoleVal). Rather than focusing solely on aggregate metrics, we perform detailed error analysis, examining model specific confusion patterns, lexical disambiguation, and out-of-vocabulary behavior. Our results yield F1 scores of 0.92 for mBERT (best on the X tag and connector distinctions), 0.91 for XLM-Roberta (strongest on numeric tags and conjunction structures), and 0.94 for CreoleVal (leading on both functional and content categories and lowest OOV error rate). We propose future directions involving model fusion, targeted and linguistically motivated annotation, and reward-guided Large Language Models data augmentation to improve our current tagger. Our linguistically grounded error analysis for MC exposes key tagging challenges and demonstrates how targeted annotation and ensemble methods can meaningfully boost accuracy in under-resourced settings.

[Download paper here](https://aclanthology.org/2025.clasp-main.1/)
