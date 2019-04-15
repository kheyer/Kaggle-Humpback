# Humpback Whale Identification Challenge

This notebook detailed my solution to Kaggle's [Humpback Whale Identification Challenge](https://www.kaggle.com/c/whale-categorization-playground). The goal of the challenge is to train a model that can classify whale species from photos of whale tails. This is made difficult by the fact that over half the possible categories are represented by a single image. Data augmentation is used to expand the dataset and offset the class imbalance.

The notebook file contains the full solution, including dataset exploration, preprocessing and model training. The solution in the notebook scored 59/528 on the leaderboard. 

The classification model is a fine-tuned Resnet34 model. The model is trained using stochastic gradient descent with warm restarts. 
