# Deep-Q-Learning-CartPole
This project demonstrates a basic implementation of Deep Q-Learning (DQN) in the context of reinforcement learning. The environment used is the CartPole task provided by OpenAI Gym, a popular simulation framework for developing and comparing reinforcement learning algorithms.

## Let's dive into our implementation
The purpose of this project is to train an agent that **Move right** or **Move left** the cart in order to balance
a pole attached to a cart
![CartPole image](https://miro.medium.com/v2/resize:fit:1200/1*J4-wdru4yvInCo-SoRqZbA.png)

In this project, I focused on the implementation of both policy and target networks, paying particular attention to the update rule. Specifically, I ensured that the target network was updated at appropriate intervals, maintaining stability during training by preventing large, unstable shifts in the policy network's behavior.