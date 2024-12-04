---
layout: post
title:  "DeepRNA-Twist: Language Model Guided RNA Torsion Angle Prediction with Attention-Inception Network"
date:   2024/10/24
image: ../images/p_twist.png
categories: preprints
authors: "Abrar Rahman Abir, Md Toki Tahmid, Rafiqul Islam Rayan, M. Saifur Rahman"
venue: "bioRxiv"
arxiv: https://www.biorxiv.org/content/10.1101/2024.10.24.619978v1
code: N/A
doi: N/A
excerpt: "RNA torsion and pseudo-torsion angles are critical in determining the three-dimensional conformation of RNA molecules, which in turn governs their biological functions. However, current methods are limited by structural complexity and flexibility of RNA, as it can adopt multiple conformations, with experimental techniques being costly and computational approaches struggling to capture the intricate sequence dependencies needed for accurate predictions. To address these challenges, we introduce DeepRNA-Twist, a novel deep learning framework designed to predict RNA torsion and pseudo-torsion angles directly from sequence. DeepRNA-Twist utilizes RNA language model embeddings, which provides rich, context-aware feature representations of RNA sequences. Additionally, it introduces 2A3IDC module (Attention Augmented Inception Inside Inception with Dilated CNN), combining inception networks with dilated convolutions and multi head attention mechanism. The dilated convolutions capture long-range dependencies in the sequence without requiring a large number of parameters, while the multi-head attention mechanism enhances the ability of the model to focus on both local and global structural features simultaneously. DeepRNA-Twist was rigorously evaluated on benchmark datasets, including RNA-Puzzles, CASP-RNA, and SPOT-RNA 1D, and demonstrated significant improvements over existing methods, achieving state-of-the-art accuracy. Source code is available at https://github.com/abrarrahmanabir/DeepRNA-Twist
"
---
