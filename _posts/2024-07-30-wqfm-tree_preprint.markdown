---
layout: post
title:  "wQFM-TREE: Highly Accurate and Scalable Quartet-Based Species Tree Inference from Gene Trees"
date:   2024/07/30
image: /images/wqfm-tree.jpg
categories: preprints
authors: "Abdur Rafi, Ahmed Mahir Sultan Rumi, Sheikh Azizul Hakim, Sohaib Sohaib, Md Toki Tahmid, Rabib Jahin Ibn Momin, Tanjeem Azwad Zaman, Rezwana Reaz, Md. Shamsuzzoha Bayzid"
venue: "bioRxiv"
arxiv: https://www.biorxiv.org/content/10.1101/2024.07.30.605630v1
code: N/A
doi: N/A
excerpt: "Summary methods are becoming increasingly popular for species tree estimation from multi-locus data in the presence of gene tree discordance. ASTRAL, a leading method in this class, solves the Maximum Quartet Support Species Tree problem within a constrained solution space constructed from the input gene trees. In contrast, alternative heuristics such as wQFM and wQMC operate by taking a set of weighted quartets as input and employ a divide-and-conquer strategy to construct the species tree. Recent studies showed wQFM to be more accurate than ASTRAL and wQMC, though its scalability is hindered by the computational demands of explicitly generating and weighting Θ(n4) quartets. Here, we introduce wQFM-TREE, a novel summary method that enhances wQFM by circumventing the need for explicit quartet generation and weighting, thereby enabling its application to large datasets. Unlike wQFM, wQFM-TREE can also handle polytomies. Extensive simulations under diverse and challenging model conditions, with hundreds or thousands of taxa and genes, consistently demonstrate that wQFM-TREE matches or improves upon the accuracy of ASTRAL. Specifically, wQFM-TREE outperformed ASTRAL in 25 of 27 model conditions analyzed in this study involving 200-1000 taxa, with statistically significant differences in 20 of these conditions. Moreover, we applied wQFM-TREE to re-analyze the green plant dataset from the One Thousand Plant Transcriptomes Initiative. Its remarkable accuracy and scalability position wQFM-TREE as a highly competitive alternative to leading methods in the field. Additionally, the algorithmic and …
"
---
