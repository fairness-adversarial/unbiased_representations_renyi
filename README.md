# Unbiased_representations_renyi
Repository for the paper "Learning Unbiased Representations via Rényi Minimization"

In recent years, significant work has been done to include fairness constraints in the training objective of machine learning algorithms.
Many state-of the-art algorithms tackle this challenge by learning a fair representation which captures all the relevant information to predict the output Y while not containing any information about a sensitive attribute S. In this paper, we propose an adversarial algorithm to learn unbiased representations via the Hirschfeld-Gebelein-Renyi (HGR) maximal correlation coefficient. We leverage recent work which has been done to estimate this coefficient by learning deep neural network transformations and use it as a min-max game to penalize the intrinsic bias in a multi dimensional latent representation. Compared to other dependence measures, the HGR coefficient captures more information about the non-linear dependencies with the sensitive variable, making the algorithm more efficient in mitigating bias in the representation. We empirically evaluate and compare our approach and demonstrate significant improvements over existing works in the field.

## Requirements
 1. Carl package: the code requires the Carl package to be installed (which can be cloned from https://github.com/diana-hep/carl.git).
 2. Matplotlib version: the code requires version 2.2.3 of Matplotlib.
