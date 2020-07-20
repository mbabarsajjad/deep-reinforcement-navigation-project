# Navigation Project
Project 1 of Udacity's Deep Reinforcement Learning nanodegree program

## Project Details
In this project, an agent is trained for collecting as many as possible yellow bananas while avoiding the blue bananas in a large square world.  

The state space has 37 dimensions and the following 4 discrete actions:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.  

The task is episodic, and in order to solve the environment, the agent has to get an average score of +13 over 100 consecutive episodes.

## Getting Started
Following libraries are required:
Python 3.x , Jupyter Notebook, NumPy, matplotlib, PyTorch, UnityEnvironment

## Instructions
Apart from the main Navigation.ipynb file, there are following two additional files which are used in the project:
- model.py: where a neural network is defined using PyTorch and
- dqn_agent: where a DQN agent is defined
