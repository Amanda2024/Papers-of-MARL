# Papers-of-MARL

Related papers for multi-agent reforcement learning.


## 2021.8.9-2021.8.15

- [Multi-Agent Coordination in Adversarial Environments through Signal Mediated Strategies](https://arxiv.org/pdf/2102.05026.pdf)  

  设计了two-player中心化采样缓冲池（该buffer可以利用彼此的动作进行训练），设计了信号中介策略框架（每个agent的策略在每个episode开始前condition on一个信号，该信号表征多智能体策略之间的均衡）  
  
- [Signal Instructed Coordination in Cooperative Multi-agent Reinforcement Learning](https://arxiv.org/pdf/1909.04224.pdf)  

    受到相关均衡CE的启发，设计一个中心信号控制器，每个agent的策略都依托于这个隐含全局信息的信号中；主要学习目标有三个：对齐智能体策略和协作信号、减轻其他智能体策略的不确定性以降低协作难度、学到多样性策略；

- [Attention Actor-Critic algorithm for Multi-Agent Constrained
Co-operative Reinforcement Learning](https://arxiv.org/pdf/2101.02349.pdf)

    受限MARL一方面要最小化累积cost，另一方面要满足约束；文中提出训练一个对偶拉格朗日的方式，以拉格朗日乘子权重作为约束的权重去求解最优策略；

- [Modeling the Interaction between Agents in Cooperative
Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2102.06042.pdf)
