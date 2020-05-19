# unbiased_representations_renyi
Repository for the paper "Learning Unbiased Representations via Rényi Minimization"

In recent years, significant work has been done to include fairness constraints in the training objective of machine learning algorithms. 
Many state-of the-art algorithms tackle this challenge by learning a fair representation which capture all the relevant information to predict the output Y 
while not containing any information about a sensitive attribute S. In this paper,  we propose an adversarial algorithm to learn unbiased representations via Rényi minimization. 
The idea is to predict the output Y while minimizing the ability of an adversarial neural network to find the estimated transformations which are required to predict the HGR coefficient. 
Compared to the state of the art, this algorithm offers the possibility to provide additional degrees of freedom to capture more information about the non-linearity
of the sensitive variable.  We empirically assess and compare our approach and demonstrate significant improvements on previously presented work in the field.
