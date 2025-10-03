[**Mathematics of multi-agent learning systems at the interface of game theory and artificial intelligence**](https://arxiv.org/pdf/2403.07017?)

* 将演化博弈论和多智能体学习结合起来
* 演化博弈论中个体可以在博弈后复制对方的策略
* 智能体学习智能体得到奖励，并不知道交互对象的策略，往往其交互对象是环境也没有策略\
* 若要结合演化博弈论，需要假定在智能体交互的场景下，且智能体可以感知交互对象的策略，进而调整自己的策略权重，复制或学习对方的策略权重

[**Evolutionary game selection creates cooperative environments**](https://arxiv.org/pdf/2311.11128)

* 考虑了博弈的变化，不是固定的博弈类型
* 博弈选择会创造一个更有利于合作的环境，不利于合作的博弈会被淘汰，没有玩家会想参与类似囚徒困境的劣质博弈，策略和博弈组合不够吸引人
* 玩家会学习榜样玩家（总收益高）的博弈类型和博弈策略，学习概率和收益差成正比
* 博弈阶段和学习阶段是独立的，不会直接学习博弈对象的策略

*想法*

不止学习榜样，遇到收益比自己低的玩家，要主动摒弃他的博弈类型和策略，可以更快地学习？


[**ALYMPICS: LLM Agents meet Game Theory Exploring Strategic Decision-Making with AI Agents**](https://www.alphaxiv.org/abs/2311.03220)
* 提供一个用于博弈的实验平台，大模型驱动参与者，可进行角色设定

[**A Game Theory-Reinforcement Learning Approach to Cooperation for UAVs**](https://www.alphaxiv.org/private/448f0c11-d285-48cc-bc55-ce226dcd1214)
* 将博弈论和强化学习结合，解决动态环境下无人机集群的协作问题
* 将无人机集群的协作问题建模为带有“非对称环境反馈”的公共物品博弈（Public Goods Game, PGG），考虑了资源限制（例如通信带宽、能源），非对称意味着合作者和背叛者（不分享信息者）的收益计算方式不同，合作者的收益乘数会根据环境动态变化
* 将描述群体策略演化的博弈论“复制动态方程”与强化学习的“选择和变异机制”在数学上统一起来

* 引入一种名为频率调整Q学习，使得无人机能够在未知和动态变化的环境中自主学习最优策略，解决了传统博弈论模型通常是静态的，以及传统强化学习模型难以描述复杂多智能体策略互动的问题
