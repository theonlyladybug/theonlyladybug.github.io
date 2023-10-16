---
title: "How Does Attention Work in Vision Transformers? A Visual Analytics Attempt"
venue: "PacificVis 2023"
authors: "Yiran Li, Junpeng Wang, Xin Dai, Liang Wang, Chin-Chia Michael Yeh, Yan Zheng, Liang Wang, Kwan-Liu Ma"
abstract: "Vision transformer (ViT) expands the success of transformer models from sequential data to images. The model decomposes an image into many smaller patches and arranges them into a sequence. Multi-head self-attentions are then applied to the sequence to learn the attention between patches. Despite many successful interpretations of transformers on sequential data, little effort has been devoted to the interpretation of ViTs, and many questions remain unanswered. For example, among the numerous attention heads, which one is more important? How strong are individual patches attending to their spatial neighbors in different heads? What attention patterns have individual heads learned? In this work, we answer these questions through a visual analytics approach. Specifically, we first identify ___what___ heads are more important in ViTs by introducing multiple pruning-based metrics. Then, we profile the spatial distribution of attention strengths between patches inside individual heads, as well as the trend of attention strengths across attention layers.
Third, using an autoencoder-based learning solution, we summarize all possible attention patterns that individual heads could learn. Examining the attention strengths and patterns of the important heads, we answer ___why___ they are important. Through concrete case studies with experienced deep learning experts on multiple ViTs, we validate the effectiveness of our solution that deepens the understanding of ViTs from *head importance*, *head attention strength*, and *head attention pattern*."
preprint_url: "https://drive.google.com/file/d/1EF4qeumN8kczKvdJ2CtFV5dYIATYbifN/view?usp=share_link"
arxiv_url: "https://arxiv.org/abs/2303.13731"
preview: "pubs/pvis23_vit_preview.png"
# teaser: "pubs/pvis23_vit_teaser.png"
# teaser_caption: "Figure 1: Our system contains four components. The imageoverview{} (A) lays out all images for selection. The headimportance{} (B) shows all heads in different importance metrics (B1) and dissects a head's importance through partial pruning (B2, B3). The attention strengths between patches in a head are shown in the attnstrength{} (C), where users first obtain an overview of all heads (C1), and then focus on one head (C2, C3). 
#  The attnpattern{} (D) clusters all heads by their attention pattern (D1), and presents the pattern details in one head (D2${\sim}$D5)."
bibtex: "@article{li2023does,\n    title={How Does Attention Work in Vision Transformers? A Visual Analytics Attempt},\n    author={Li, Yiran and Wang, Junpeng and Dai, Xin and Wang, Liang and Yeh, Chin-Chia Michael and Zheng, Yan and Zhang, Wei and Ma, Kwan-Liu},\n    journal={IEEE Transactions on Visualization and Computer Graphics},\n    year={2023},\n   publisher={IEEE}\n}"
permalink: "/publication/pvis2023vit"
date: 2023-03-24
collection: "publications"
---
