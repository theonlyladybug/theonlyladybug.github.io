---
title: "Visual Analytics of Neuron Vulnerability to Adversarial Attacks on Convolutional Neural Networks"
venue: "ACM Transactions on Interactive Intelligent Systems"
authors: "Yiran Li, Junpeng Wang, Takanori Fujiwara, and Kwan-Liu Ma"
abstract: "Adversarial attacks on a convolutional neural network (CNN)—injecting human-imperceptible perturbations into an input image—could fool a high-performance CNN into making incorrect predictions. The success of adversarial attacks raises serious concerns about the robustness of CNNs, and prevents them from being used in safety-critical applications, such as medical diagnosis and autonomous driving. Our work introduces a visual analytics approach to understanding adversarial attacks by answering two questions: (1) Which neurons are more vulnerable to attacks? and (2) Which image features do these vulnerable neurons capture during the prediction? For the first question, we introduce multiple perturbation-based measures to break down the attacking magnitude into individual CNN neurons and rank the neurons by their vulnerability levels. For the second, we identify image features (e.g., cat ears) that highly stimulate a user-selected neuron to augment and validate the neuron’s responsibility. Furthermore, we support an interactive exploration of a large number of neurons by aiding with hierarchical clustering based on the neurons’ roles in the prediction. To this end, a visual analytics system is designed to incorporate visual reasoning for interpreting adversarial attacks. We validate the effectiveness of our system through multiple case studies as well as feedback from domain experts."
official_url: "https://dl.acm.org/doi/full/10.1145/3587470"
preprint_url: "https://drive.google.com/file/d/1YG7jYDk0Sy28IKXB7vZWMdDOumYZhzqe/view?usp=sharing"
arxiv_url: "https://arxiv.org/abs/2303.02814"
preview: "pubs/tiis2023-adversarial-preview.png"
teaser: "pubs/tiis2023-adversarial-teaser.png"
teaser_caption: "Using our visual analytics system to explore and interpret the adversarial attacks. The Data Overview (a) visualizes the benign images' similarities (a1) and the adversarial images' similarities (a2) based on the CNN penultimate layer’s activation. The color encoding of the points can be switched between using true labels and using predicted labels (a2 and a3). The Prediction Matrix (a4) shows the distribution of images based on true and adversarial labels, where the darker orange color represents more images in the cell. The Image Grid View (b) lists benign images and adversarial counterparts corresponding to the selection made in the Data Overview (here the cat-dog cell is selected in a4). For the selected image in the Image Grid View, the Neuron Vulnerability View (c) organizes neurons based on the differences in their values of activation x weight. The Receptive Field View (d) informs the RFs and vulnerability maps to help interpret each neuron's behavior. The Neuron Cluster View (e) shows the dendrogram constructed based on the similarity of each neuron's behavior and facilitates efficient interpretation of multiple neurons' behaviors. "
bibtex: "@article{li2023visual,\n   title={Visual Analytics of Neuron Vulnerability to Adversarial Attacks on Convolutional Neural Networks},\n    author={Li, Yiran and Wang, Junpeng and Fujiwara, Takanori and Ma, Kwan-Liu},\n    journal={ACM Transactions on Interactive Intelligent Systems},\n    year={2023},\n    publisher={ACM New York, NY}\n}"
permalink: "/publication/tiis2023-adversarial"
date: 2023-03-15
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
