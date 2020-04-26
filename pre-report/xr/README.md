## 主要工作
* English: Solve non-stationary problem in the large-scale multi-agent systems. 
For resource scheduling among multi-agents, increase system overall utility through iteratively and collaboratively cooperating among agents.

中文：解决大规模多智体系统中的非稳态问题，针对多智体间的资源调度，使用迭代化和协同化的多智体间协作，提升系统的整体效用。


* English: Accelerate the training speed of multi-agent learning procedure.
For multi-objective decision problem, provide a real-time update to an outdated decision and maintain system stability

中文： 
提升多智体学习过程的训练速度，针对多目标决策问题，实时更新过时的决策，保持多智体系统稳定。 


* English: Develop efficient and privacy-preserving communication mechanisms to reduce the overhead of communication among multi-agents, and prevent privacy leakage.

中文：开发高效且具备隐私保护的多智体间通信机制，降低通信开销，避免用户隐私数据泄露。


* English: Introduce fault-tolerant optimization framework to alleviate the influence of single-point failure problem in distributed multi-agent systems.

中文： 设计具有容错性的决策框架，降低单点故障在分布式多智体系统中的影响。


## 版本2：

1. 指南说明：支持敏感数据不共享条件下的可信任协同训练

主要工作：
* 针对多智体协同决策的数据接入和共享过程，设计数据的敏感度模型，建立访问敏感数据的保护机制。
* 在多智体通信中，为敏感数据人为添加数据模糊，针对该不可靠数据交换模型，设计可量化、可信任的协同训练协议。

2. 指南说明：构建虚拟共有模型，完成宏观任务目标

主要工作：
* 协同调度多智体的训练目标，优化单个智体的分布式模型训练过程，完成集中式共有模型的训练目标。