# UdacityNavigation

Implementation of Deep Q-learning to the Unity ML-Agent collecting yellow bananas. Unity Machine Learning Agents (ML-Agents) is an open-source Unity plugin that enables games and simulations to serve as environments for training intelligent agents.

## Project Details

The project environment has an agent that should be learned to navigate (and collect bananas) in a large, square world.
The simulation contains a single agent that navigates a large environment.  At each time step, it has four actions at its disposal:
- `0` - walk forward 
- `1` - walk backward
- `2` - turn left
- `3` - turn right

The state space has `37` dimensions and contains the agent's velocity, along with a ray-based perception of objects around the agent's forward direction.  A reward of `+1` is provided for collecting a yellow banana, and a reward of `-1` is provided for collecting a blue banana. 
The environment is considered solved when the agent gets an average score of +13 over 100 consecutive episodes.

## Getting Started

Follow the instructions in the DRLND GitHub repository to set up the Python environment [here](https://github.com/udacity/deep-reinforcement-learning#dependencies). 

Additionally, install PyTorch (the project utilized PyTorch ver 0.4.0). 

## Instructions

Run sections 1-3 on the `Navigation.ipynb` in order to observe the performance of the random policy of the agent.

Run the rest of the `Navigation.ipynb` in order to train the agent and observe the performance of the smart agent.
