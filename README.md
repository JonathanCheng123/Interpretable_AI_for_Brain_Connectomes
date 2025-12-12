# Interpretable_AI_for_Brain_Connectomes
This repository contains the ipynb's for our project: Interpretable AI for Brain Connectomes. 

# Data
Our prediction models are trained on data from the Human Connectome Project. Specifically, we use data from the Aging Adult Brain Connectome (AABC) Project, which can be found here for registered users: https://balsa.wustl.edu/project?project=AABC

We model the connectomes as a 379 x 379 connectivity matrix, where each entry represents the functional connectivity between 2 brain regions. The mappings of the 379 regions of interest to actual brain regions is here: https://neuroimaging-core-docs.readthedocs.io/en/latest/pages/atlases.html

# Files
GAT_ravlt_learning_score.ipynb: python notebook for predictions/spectral clustering/analysis on ravlt learning score.

GAT_Age.ipynb: python notebook for predictions/spectral clustering/analysis on age.

GAT_Cognition_moca_sum.ipynb: python notebook for predictions/spectral clustering/analysis on moca score.

GAT_PSQI.ipynb: python notebook for predictions/spectral clustering/analysis on psqi score.

CondGATVAE.ipynb: python notebook for conditional variational graph autoencoder on four outcome variables (age, moca, ravlt, psqi)

GATVAE: python notebook for variational GAT autoencoder (unconditioned)

VAE.ipynb: python notebook for variational autoencoder for adjacency upper-triangular
