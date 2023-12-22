---
title: "Umbra: A Visual Analysis Approach for Defense Construction Against Inference Attacks on Sensitive Information"
venue: "IEEE Transactions on Visualization and Computer Graphics"
authors: "Xumeng Wang, Chris Bryan, Yiran Li, Rusheng Pan, Yanling Liu, Wei Chen, and Kwan-Liu Ma"
abstract: "Collecting and analyzing anonymous personal information is required as a part of data analysis processes, such as medical diagnosis and restaurant recommendation. Such data should ostensibly be stored so that specific individual information cannot be disclosed. Unfortunately, inference attacks—integrating background knowledge and intelligent models—hinder classic sanitization techniques like syntactic anonymity and differential privacy from exhaustively protecting sensitive information. As a solution, we introduce a three-stage approach empowered within a visual interface, which depicts underlying inference behaviors via a Bayesian Network and supports a customized defense against inference attacks from unknown adversaries. In particular, our approach visually explains the process details of the underlying privacy preserving models, allowing users to verify if the results sufficiently satisfy the requirements of privacy preservation. We demonstrate the effectiveness of our approach through two case studies and expert reviews."
official_url: "https://ieeexplore.ieee.org/abstract/document/9258413"
preprint_url: "https://drive.google.com/file/d/1LEGmInqr-SkzwGieqbZVbSgojKv1kCnZ/view?usp=sharing"
preview: "pubs/tvcg2020-umbra-preview.png"
teaser: "pubs/tvcg2020-umbra-teaser.png"
teaser_caption: "An integrated layout of our system navigated by (a) a three-stage workflow. Each stage has a dual-column interface, with a data description view ((b), (d), and (f) ) on the left, and a model exploration view ((c), (e), and (g)) on the right. The interface of the Inference Initialization Stage con- sists of a State Initialization View (b) that displays attribute distributions with utility-mapping opacity for event definition, and an Inference Initialization View (c) that depicts all underlying inferences among events by an inference graph. The second interface for the Data Sanitization Stage provides a selected group of records in a Data Table View (d), together with a list of candidate solutions, and an overview summarizing changes of all solutions in a Solution Recommendation View (e). The interface for the Result Verification Stage supports users in verifying the distributions in the Data Trim View (f), and evaluating the processed data’s resistance to other attacks in Attack Simulation View (g)."
bibtex: "@article{wang2020umbra,\n    title={Umbra: A visual analysis approach for defense construction against inference attacks on sensitive information},\n    author={Wang, Xumeng and Bryan, Chris and Li, Yiran and Pan, Rusheng and Liu, Yanling and Chen, Wei and Ma, Kwan-Liu},\n    journal={IEEE Transactions on Visualization and Computer Graphics},\n    volume={28},\n    number={7},\n    pages={2776--2790},\n    year={2020},\n    publisher={IEEE}\n}"
permalink: "/publication/tvcg2020-umbra"
date: 2020-11-12
collection: "publications"
---
<!-- ![image](/images/pubs/tvcg-instant-vnr-teaser.png) -->

<!-- 
<figure>
<img src="/images/pubs/tvcg-instant-vnr-teaser.png" alt="image">
<figcaption align = "center">Figure 1: A) An overview of our work. The sampling step randomly and uniformly generates sample using the ground truth (GT) data. The ground truth data can be loaded via out-of-core streaming. The training step optimizes the neural network. The rendering step renders the neural network via in-shader or sample-streaming methods. Our approach accommodates both pre-training and online-training. Our novel contributions are highlighted in yellow. B) The architecture of our neural network with the multi-resolution hash grid encoding method.</figcaption>
</figure> -->

<!-- ### Video 

<p>
<iframe src="https://drive.google.com/file/d/17wSgIm_VsoeGhfyZwMpOnCYy2Mj3ydGv/preview" width="960" height="540" allow="autoplay"></iframe>
</p>

### Note

This manuscript was originally titled "Instant Neural Representation for Interactive Volume Rendering", but in response to the valuable feedback received from reviewers, the title was subsequently revised. -->
