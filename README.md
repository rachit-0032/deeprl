# Cooperative Multi Agent Reinforcement Learning for UAVs

In the recent decade, the UAVs have gained a lot of importance, be it for defence missions or for maintaining law and order by enabling surveillance of an area. For efficient use of the UAVs, they have to be made autonomous as only then it would be possible for them to do complex tasks. To achieve the autonomous behaviour of UAVs, they can be trained prior to their deployment in unknown environments to take appropriate decisions under different situations. This opens up the door for the use of Reinforcement Learning to find the optimal behaviour of the UAVs.

Multi-agent systems, although more challenging to implement, are far more efficient than single-agent systems. Thus, in this work, we create and simulate a Multi-Agent Reinforcement Learning system for cooperative behaviour of multiple UAVs in an unknown environment. For scalability, deep neural networks are used as value function approximators.

In collaborative scenarios, decentralized control policy based on local observations and communications with connected neighbours is evaluated in different environments. The concept of differential privacy is explored with use of noisy observations in the communication networks. Each agent makes individual decision based on the observations made individually and from the communication made with neighbours in the network. This paper finally judges the learnability of multiple agents in a more practical, noise-enabled decentralised fashion environment which is less explored in literature.

The aim of this work, therefore, is to understand the multi-agent reinforcement learning (MARL) problem in the cooperative scenarios and then do a generalized approach study to do algorithmic novelties and numerous experimental simulations to validate the results which could later be applied to a variety of use-cases, along with trying to mimic practical scenarios.

The MDP of Cooperative Adaptive Cruise Control (CACC) Scenarios is as follows:
![alt text](https://github.com/rachit-0032/deeprl-btp/blob/efa85171d2c124bfdf48f39f6ce418fc6a697c36/MDP_TrafficProblem.png?raw=true)

We explore multiple pathways to understanding the effect of de-centralization actor and critic model, along with simulating the effect of addition of noise in the communication of agents over numerous scnearios. The following concepts are explored in our project thesis:
![alt text](https://github.com/rachit-0032/deeprl-btp/blob/2e96196e201c21b7f0736519c6f95ad799fe3173/Contents.png?raw=true)
