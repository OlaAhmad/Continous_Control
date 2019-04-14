# Project 2: Continuous_Control

### Introduction

### Getting started

Download the Continous_Control repository from the top-right button. You can also clone the repository and downloaded from a terminal in your workspace directory using the following command line:
    
    git clone https://github.com/OlaAhmad/Continuous_Control.git
        
### Usage

Go to the Navigation folder and open the Navigation notebook to train the DQN agent as follows:

    cd Continuous_Control
    Jupyter notebook Continuous_Control-2.ipynb

When runing the notebook, the actor-critic agent will start training over a number of episodes; Two neural networks will start training and simultaneously update their parameters every number of iterations. The updated parameters of the trained acrchitectures are saved in checkpoint files

### Codes

We added two files to train the agent using the notebook: 
1. model.py: builds actor and critic neural network architectures. 
2. dqn_agent.py: interacts with Banana enviornement and learns the agent from it.
We used and adapted the codes from the lesson (ddpg-pendulum).

### Resources

* udacity/deep-reinforcement-learning

