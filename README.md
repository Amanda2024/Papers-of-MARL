# Papers-of-MARL

Related papers for multi-agent reforcement learning.


## 2021.8.9-2021.8.15

- [Provable Representation Learning for Imitation with Contrastive Fourier Features](https://arxiv.org/pdf/2105.12272.pdf)  

  **提出用contrastive learning**方法从offline dataset表征state，可以证明在使用该方法优化表征state的函数和强化学习过程时，等价于将学习的policy与收集offline dataset的target policy的距离的upper bound降低，不需要考虑target policy表征的形式，理论上可以将error降到0。相较Behavior Cloning方法（Bisimulation-based）性能大幅提升，实验在tabular case和Atari2600上训练的DQN均做了实验。（learning dynamic and reward）BC对target policy采集数据的形式有限制，且由于数据未全覆盖且空间大sample efficiency比较低  
  
- [Pretraining Representations for Data-Efficient
Reinforcement Learning](https://arxiv.org/pdf/2106.04799.pdf)  
