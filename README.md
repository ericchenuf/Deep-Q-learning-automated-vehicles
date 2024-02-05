# Deep-Q-learning-automated-vehicles

### Project Title: Investigating Reward Functions in Autonomous Vehicle Training with DQN

## Overview

> This project aims to explore the influence of various reward functions on the performance of autonomous vehicles using Deep Q-Learning (DQN). Leveraging the highway-env simulator, we will train an agent across multiple driving scenarios—including highways, merge environments, and intersections—to understand how different reward structures affect learning outcomes and safety requirements.

> Objectives
To understand the effect of varying reward functions within a Q-learning framework that integrates Convolutional Neural Network (CNN) approaches, specifically DQN, as outlined by Mnih et al. (2016).
To evaluate the agent's performance in various simulated driving environments to identify optimal reward function configurations for enhancing safety and efficiency in autonomous vehicles.

## Methodology
> Our approach involves training a reinforcement learning agent using the DQN algorithm, where the CNN serves as a function approximator for the Q-value function. The environments provided by the highway-env simulator will serve as testing grounds to train and evaluate our agent under different conditions and reward schemes.

## Environments
> Highway: Navigating in traffic on a multi-lane road.
> Merge: Merging into traffic from an on-ramp.  
> Intersection: Navigating complex intersections with varying traffic patterns.

## Installation
```{python}
bash
# Clone this repository
git clone [repository-url]
```
# Install dependencies
```{python}
pip install -r requirements.txt
```
# Model Training 
```{python}
# Run training session
python train.py --env [environment-name]
```
# Evaluate the trained model
python evaluate.py --model [model-path]
