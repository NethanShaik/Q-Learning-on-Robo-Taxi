<img width="271" alt="image" src="https://github.com/NethanShaik/Q-Learning-on-Robo-Taxi/assets/66028026/687bd284-9ac3-428b-9102-beb3b486c5d2">

The concept of this project is to show how Reinforcement Learning works in the background, where the agent is placed in an environment and takes decisions upon taking a step and is either rewarded points or given a penalty based on it’s decision for training. 

Q - Learning is a type of reinforcement learning approach where the model learns through a set of iterations over a period of time by taking the right action. The agent learns by exploring the environment and updates the model as the exploration continues and starts exploiting based on the information it has learned. It uses two methods [3]:

Temporal Difference
Bellman’s equation

For this exercise, we will be using the Bellman’s equation that will be implemented in the program

Q(s,a) = Q(s,a) + α * (r + γ * max(Q(s',a')) - Q(s,a))

Where:
Q(s,a) is the expected award reward for taking the action
α is the learning rate
Gamma is the discount factor
max(Q(s,a)) is the highest expected reward for all possible actions 

![image](https://github.com/NethanShaik/Q-Learning-on-Robo-Taxi/assets/66028026/7c8a823f-91d2-4120-9d90-ee2e4fb1d0be)
