 # Navigation Project - Banana Simulator
 
 For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.
 
 ## Getting Started
 
 The goal of this project was to create Deep Reinforcement Learning (DQN) algorithm to play banana simulator. The agent’s goal is to collect as many yellow bananas (reward +1) as possible in given time, and avoid blue bananas (reward -1).
 
 ### Prerequisites
 
 Jupyter Notebook with installed:
 * unityagents
 * numpy
 * torch
 * collections
 
 Banana simulator:
 * mac: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip
 * win: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip
 * Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
 
 
 ### Environment
 The environment state space observed by agent has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.
 ### Actions
 To achieve the goal, agent can undertake one of four actions: move forward, backward, left and right.
 
 ### Agent’s goal
 
 Thee task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.
 
 ### How to run the code
 
 ###### Learning agent
 to learn basic agent set:
 ```
 run_training = True
 ```
 to learn comparison networks set (this may take quite a long time):
 ```
 run_training_of_comparison_networks = True
 ```
 
 ###### Use pre-trained model
 To use pre-trained model set:
 ```
 run_training = False
 run_training_of_comparison_networks = False
 run_test = True
 ```
 
 ### Solution Description
 
 Solution description can be found in Report.pdf
 
 ### Thanks
