---
layout: post
title:  "RNA-DCGen: Dual Constrained RNA Sequence Generation with LLM-Attack"
date:   2024/09/23
image: /images/rna-dcgen.jpg
categories: conference
authors: "Haz Sameen Shahgir*, Md. Rownok Zahan Ratul*, Md Toki Tahmid*, Khondker Salman Sayeed, Atif Rahman (*Equal Contribution)"
venue: "NeurIPS 2024 MLSB Workshop"
arxiv: https://www.biorxiv.org/content/10.1101/2024.09.23.614570v1
code: N/A
doi: N/A
excerpt: "Designing RNA sequences with specific properties is critical for developing personalized medications and therapeutics. While recent diffusion and flow-matching-based generative models have made strides in conditional sequence design, they face two key limitations: specialization for fixed constraint types, such as tertiary structures, and lack of flexibility in imposing additional conditions beyond the primary property of interest. To address these challenges, we introduce RNA-DCGen, a generalized framework for RNA sequence generation that is adaptable to any structural or functional properties through straightforward finetuning with an RNA language model (RNA-LM). Additionally, RNA-DCGen can enforce conditions on the generated sequences by fixing specific conserved regions. On RNA generation conditioned on RNA distance maps, RNA-DCGen generates sequences with an average R2 score of 0.625 compared to random sequences that score only 0.118 over 250 generations as judged by a separate more capable RNA-LM. When conditioned on RNA secondary structures, RNA-DCGen achieves an average F1 score of 0.4 against a random baseline of 0.006.
"
---
