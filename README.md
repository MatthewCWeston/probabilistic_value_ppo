# Probabilistic Value Function Research

Some content involving probabilistic value in PPO. There's also an RLlib implementation of AlphaStar, stored here because it was relevant to a writeup I was working on.

`prob_val.ipynb` contains:
 - Implementations of EPPO, Beta-NLL, and generic probabilistic value loss in RLlib.
 - A script to quantitatively compare the value distribution modeling behavior of all three on a toy environment.
 - Sample results of this script.
 - A pair of alternative advantage calculation functions, and comparison of their performance on a toy environment demonstrating an edge case in which standard advantage normalization struggles.
