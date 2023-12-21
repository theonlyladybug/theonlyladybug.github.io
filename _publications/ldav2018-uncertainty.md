---
title: "Visual Analysis of Simulation Uncertainty Using Cost-Effective Sampling"
venue: "IEEE Symposium on Large Data Analysis and Visualization (LDAV) 2018"
authors: "Annie Preston, Yiran Li, Franz Sauer, and Kwan-Liu Ma"
abstract: "Studying large, complex simulations entails understanding their uncertainties. However, visualization tools that rapidly quantify simulation uncertainty may require precise tuning, give limited information, or struggle to disentangle uncertainty sources. We propose a fast, scalable regression-based approach that uses bootstrapping on small samples of simulation data to model the effect of uncertainty from discreteness. We test the approach on three types of simulations with unique sources of uncertainty: particles (dark matter), ensembles (ocean), and discretized flows (traffic). We create a visualization tool to facilitate this modeling, showing training data and predictions in real time. Scientists, who need to provide only modest supervision, can use our tool to quickly understand how initial conditions and parameterizations affect observable quantities, their uncertainties, and their agreement with experimental data. We show that our tool offers a speedup of several orders of magnitude over comparable uncertainty calculation approaches."
official_url: "https://ieeexplore.ieee.org/abstract/document/8739182"
preview: "pubs/ldav2018_preview.png"
teaser: "pubs/ldav2018_teaser.png"
teaser_caption: "Prediction, and sampled uncertainties, for the dark matter halo case study, shown in our full interface. At left, we see the set of samples the user has chosen.
The user has highlighted two samples to show in the uncertainty view. In the middle panel, we see that the user has scaled the “size” values as input into the prediction
model. At right, we see the measured uncertainties for the samples (pink, green), and the predicted uncertainties (gray), shown in stacked boxplots. Because the halo
mass function spans several orders of magnitude, it is difficult to show in one view; instead, we are showing the boxplots centered around their medians for each mass
bin. The quality indicator boxes on the bottom of the right panel show that most predictions have a very high confidence. (Axis labels are enlarged for display purposes.)"
bibtex: "@INPROCEEDINGS{preston2018visual,\n    author={Preston, Annie and Li, Yiran and Sauer, Franz and Ma, Kwan-Liu},\n    booktitle={2018 IEEE 8th Symposium on Large Data Analysis and Visualization (LDAV)},\n    title={Visual Analysis of Simulation Uncertainty Using Cost-Effective Sampling},\n    year={2018},\n    pages={1-11},\n    doi={10.1109/LDAV.2018.8739182}}"
permalink: "/publication/ldav2018-uncertainty"
date: 2018-10-21
collection: "publications"
---
