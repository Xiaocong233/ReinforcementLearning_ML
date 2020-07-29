## Description
Contains Python templates of Upper Confidence Bound and Thompson Sampling algorithms aimed to solve Multi-armed Bandit Problems for Reinforcement Learning
  - different solutions towards exploration and exploitation
  
## RL_Tutorial
- a handcrafted Reinforcement Learning tutorial mixed with theories and practical code implementations
  - serve as an introduction or review of RL for beginners and intermediate level students
  - read first!

## Epsilon Greedy/Gaussian Epsilon Greedy Algorithms Template
  - simulate and solve a basic multi-armed bandit problems
    - Epsilon Greedy for Bernoulli models
    - Gaussian Epsilon Greedy for Gaussian models
  - during each iteration, only sample the bandit with the current highest estimation value, except for some occasions(controlled by epsilon) sampling randomly from all bandits

## Optimistic Initial Values Template
  - similar to basic Greedy Algorithm
    - only initialize estimation values for all bandits to be extremely high(variables p_estimate), thus making the algorithm do automatic exploration as sample means for bandits decrease

## Upper Confidence Bound/Thompson Sampling Algorithms Template
  - templates created by modifying after the demo code provided by [SuperDataScience Team](https://www.superdatascience.com/)
  - both aims to resolve multi-armed bandits problem
    - UCB creates a distribution of estimations of the most optimal choice of item from a deterministic approach after a certain number of training samples provided
    - whereas Thompson Sampling does the same but with a probabilisitc approach, usually functions better
  - can be ran through Jupyter Notebook or in Python terminal
    - substitude 'ENTER_THE_NAME_OF_YOUR_DATASET_HERE.csv' with dataset
      - expects a click-through rate type dataset with row representing each training sample, column with binary digits representing either an item is not picked or is picked (0 or 1)
    - adjust rows variables according to the amount of training sample you would like to provide, defaulted to entire dataset
