---
title: "Fully Cooperative Multi-Agent Reinforcement Learning"
collection: publications
permalink: /publications/research_thesis
excerpt: "Developed a Multi-Agent RL architecture that successfully learned policies to accomplish complex strategic tasks in a cooperative setting, exploiting the standard MAS paradigm of Centralized Learning with Decentralized Execution."
date: 2019-06-15
venue: "Master's Thesis, IIIT-Bangalore"
classes: wide
---
# Abstract
<img src="../assets/images/fcmadrl.png" width="50%" height="50%" style="float:right;">
Coordination of autonomous vehicles, automating warehouse management system or another real world complex problem like large-scale fleet management can be easily fashioned as cooperative multi-agent systems. Presently, algorithms in Reinforcement Learning (RL), which are designed for single agents, work poorly in multi-agent settings and hence there is a need for RL frameworks in Multi-Agent Systems (MAS). But, Multi-Agent Reinforcement Learning (MARL) poses its own challenges, some of the major ones being the problem of non-stationarity and the exponential growth of the joint action space with increasing number of agents. A possible solution to these complexities is to use Centralised learning and Decentralised execution of policies, however the question of using the notion of centralised learning to the fullest still remains open. As apart of this thesis, we developed an architecture, adopting the framework of centralised learning with decentralised execution, where all the actions of the individual agents are given as input to a central agent and it outputs information for them to utilize. Thus, the system of individual agents are given the opportunity of using some extra information (about other agents affecting the environment directly) from a central agent which also helps in easing their training. Results for the same are showcased on the Multi-Agent Particle Environment (MPE) by OpenAI. An extension of the architecture for the case of warehouse logistics is also shown in the thesis.

[ [Thesis](https://www.dropbox.com/s/aj94skskcqigf3h/thesis_final_draft.pdf?dl=0) ] [ [Code](https://github.com/Nikunj-Gupta/FCMADRL) ]

