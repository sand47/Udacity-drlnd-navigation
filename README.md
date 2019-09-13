# Udacity-drlnd-navigation
This project is the exercise of Udacity deep-reinforcement-learning-nanodegree Navigation project 

# The Environment

For this project, our aim is to train an agent to navigate in a large, square world to collect as much as bananas as possible.
<br>
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.
<br> <br>
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:
<br> <br>
0 - move forward.<br>
1 - move backward.<br>
2 - turn left.<br>
3 - turn right.<br>
<br> <br>
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.
I have consider a Deep Q-learning algorithm and resulting output is a average score of +15 in 543 episodes.

## Getting Started
- clone this project to your computer <br>
- download the unity environment. You need only select the environment that matches your operating system <br>
- Use the Navigation.ipynb file to train the agent
