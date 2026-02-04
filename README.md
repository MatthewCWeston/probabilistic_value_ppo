# Probabilistic Value Function Research

This repo will consist of three files. 
 - The first, `prob_val_writeup_clean.ipynb`, consists of a novel implementation of a probabilistic value head for actor-critic reinforcement learning, and the code required to evaluate it and compare it to the two most prominent probabilstic PPO implementations identified in existing literature.
 - The second, `Distributional PPO Writeup.pdf`, summarizes the results of this comparison, positing that it results in substantially reduced KL divergence from the ground truth state value distribution.
   - The third, `RLlib_AlphaStar.ipynb`, is an augmented implementation of AlphaStar in RLlib, which is referenced in the appendix.
   - The appendix of the writeup consists of an in-depth discussion of the research process associated with this project, and its context within a larger project that I've undertaken.
