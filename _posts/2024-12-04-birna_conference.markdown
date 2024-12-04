---
layout: post
title:  "BiRNA-BERT: Adaptive Tokenization for Efficient RNA Language Modeling"
date:   2024/07/04
image: ../images/c_birna.png
categories: conference
authors: "Md Toki Tahmid, Haz Sameen Shahgir, Sazan Mahbub, Yue Dong, Md Shamsuzzoha Bayzid"
venue: "NeurIPS 2024 ENLSP Workshop, Oral/Spotlight"
arxiv: https://www.biorxiv.org/content/10.1101/2024.07.02.601703v2
code: https://github.com/buetnlpbio/BiRNA-BERT
doi: N/A
excerpt: "Recent advancements in Transformer-based models have spurred interest in their use for biological sequence analysis. However, adapting models like BERT is challenging due to sequence length, often requiring truncation for proteomics and genomics tasks. Additionally, advanced tokenization and relative positional encoding techniques for long contexts in NLP are often not directly transferable to DNA/RNA sequences, which require nucleotide or character-level encodings for tasks such as 3D torsion angle prediction. To tackle these challenges, we propose an adaptive dual tokenization scheme for bioinformatics that utilizes both nucleotide-level (NUC) and efficient BPE tokenizations. Building on the dual tokenization, we introduce BiRNA-BERT, a 117M parameter Transformer encoder pretrained with our proposed tokenization on 36 million coding and non-coding RNA sequences. BiRNA-BERT achieves state-of-the-art results in long-sequence downstream tasks and performs comparable to 6 times larger models in short-sequence tasks with 27 times less pre-training compute. In addition, our empirical experiments and ablation studies demonstrate that NUC is often preferable over BPE for bioinformatics tasks, given sufficient VRAM availability. This further highlights the advantage of BiRNA-BERT, which can dynamically adjust its tokenization strategy based on sequence length. It utilizes NUC for shorter sequences and switching to BPE for longer ones, eliminating the need for truncation.
"
---
