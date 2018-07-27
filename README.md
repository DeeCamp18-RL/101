# RL101: a Gentle Introduction to Reinforcement Learning

## Tasks
1. 配置环境：配置一个带有Tensorflow、OpenAI Gym和Jupyter Notebook的Python Virtual Environment.
2. Gym Basics：在[Gym](https://gym.openai.com/docs/)中挑选一个Environment，并设计一个random dummy agent与环境互动123个episode.
3. Value Estimation：基于Tensorflow实现一个DQN，并在Gym中Solve [Pendulum-v0](https://gym.openai.com/envs/Pendulum-v0/)这个环境.
4. Policy Optimization: 基于Tensorflow实现REINFORCE算法，并在Gym中Solve [Pendulum-v0](https://gym.openai.com/envs/Pendulum-v0/)这个环境.
5. Actor Critic：基于Tensorflow实现一个DPG agent，并在Gym中Solve [Pendulum-v0](https://gym.openai.com/envs/Pendulum-v0/)这个环境.

## Courses
1. [David Silver RL Course at UCL](www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
1. [UCB RL Course](http://rail.eecs.berkeley.edu/deeprlcourse-fa17/index.html#lectures)

## Books
1. [Reinforcement Learning Introduction by Sutton](http://incompleteideas.net/book/the-book-2nd.html): 可能是RL方面最全面的教材，涉及方方面面，但是理论对于初学者来说有些不必要地多。

## Classical Papers
1. [DQN](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf): deep RL的开山之作，提出了target network，experience replay等off-policy值估计的利器；
1. REINFORCE: Sutton RL intro, "13.3 REINFORCE: Monte Carlo Policy Gradient"
1. [DPG](http://proceedings.mlr.press/v32/silver14.pdf): 连续动作空间问题比较经典的算法，使用神经网络实现了Silver之前工作提出的“确定性策略梯度”。  
