---
layout: post
title:  "BiRNA-BERT allows efficient RNA language modeling with adaptive tokenizationns"
date:   2024/7/4
image: /images/birna.jpg
categories: research
authors: "Md Toki Tahmid, Haz Sameen Shahgir, Sazan Mahbub, Yue Dong, Md Shamsuzzoha Bayzid"
venue: "NeurIPS 2024 ENLSP Workshop - Oral/Spotlight, NeurIPS 2024 FM4Science Workshop"
arxiv: https://www.biorxiv.org/content/biorxiv/early/2024/08/26/2024.07.02.601703.full.pdf
code: https://github.com/buetnlpbio/BiRNA-BERT
# website: https://leonidk.github.io/fmb-plus
---
Recent advancements in Transformer-based models have spurred interest in their use for biological sequence analysis. However, adapting models like BERT is challenging due to sequence length, often requiring truncation for proteomics and genomics tasks. Additionally, advanced tokenization and relative positional encoding techniques for long contexts in NLP are often not directly transferable to DNA/RNA sequences, which require nucleotide or character-level encodings for tasks such as 3D torsion angle prediction. To tackle these challenges, we propose an adaptive dual tokenization scheme for bioinformatics that utilizes both nucleotide-level (NUC) and efficient BPE tokenizations. Building on the dual tokenization, we introduce BiRNA-BERT, a 117M parameter Transformer encoder pretrained with our proposed tokenization on 36 million coding and non-coding RNA sequences. BiRNA-BERT achieves state-of-the-art results in long-sequence downstream tasks and performs comparable to 6 times larger models in short-sequence tasks with 27 times less pre-training compute. In addition, our empirical experiments and ablation studies demonstrate that NUC is often preferable over BPE for bioinformatics tasks, given sufficient VRAM availability. This further highlights the advantage of BiRNA-BERT, which can dynamically adjust its tokenization strategy based on sequence length. It utilizes NUC for shorter sequences and switching to BPE for longer ones, eliminating the need for truncation.