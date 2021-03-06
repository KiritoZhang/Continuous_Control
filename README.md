
# Project 2: Continuous Control

### Project link
https://github.com/KiritoZhang/Continuous_Control

### Project Details

For this project, I will work with the Reacher environment.( https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher)


In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.



### Solving the Environment

In this project I chose to solve the first environmental problem, even though the agent scored +30 on average in 100 consecutive episodes.


### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - **_Version 1: One Agent_**
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)


2. Place the file in the DRLND GitHub repository, in the `p2_continuous-control/` folder, and unzip (or decompress) the file. 


3. Finally, you need to install some libraries via pip.
    - unityagents
    - collections
    - matplotlib
    - numpy
    - random
    - time
    - copy
    - os
    - torch

### Instructions

I have solved the environmental problem in `Continuous_Control.ipynb`, just need to run the code in order.

