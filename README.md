## Description
Contains Python templates of Upper Confidence Bound and Thompson Sampling algorithms aimed to solve Multi-armed Bandit Problems for Reinforcement Learning

## Python Epsilon Greedy/Gaussian Epsilon Greedy Algorithms Template
  - simulate and solve a basic multi-armed bandit problems
    - Epsilon Greedy for Bernoulli models
    - Gaussian Epsilon Greedy for Gaussian models

## Python Upper Confidence Bound/Thompson Sampling Algorithms Template
  - templates created by modifying after the demo code provided by [SuperDataScience Team](https://www.superdatascience.com/)
  - both aims to resolve multi-armed bandits problem
    - UCB creates a distribution of estimations of the most optimal choice of item from a deterministic approach after a certain number of training samples provided
    - whereas Thompson Sampling does the same but with a probabilisitc approach, usually functions better
  - can be ran through Jupyter Notebook or in Python terminal
    - substitude 'ENTER_THE_NAME_OF_YOUR_DATASET_HERE.csv' with dataset
      - expects a click-through rate type dataset with row representing each training sample, column with binary digits representing either an item is not picked or is picked (0 or 1)
    - adjust rows variables according to the amount of training sample you would like to provide, defaulted to entire dataset
