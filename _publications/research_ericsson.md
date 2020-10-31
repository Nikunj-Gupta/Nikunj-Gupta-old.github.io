---
title: "Optimal Storage of Inventory in a Self-Sustained Warehouse"
collection: publications
permalink: /publications/research_ericsson
excerpt: "Modelled the ’fetch and store’ segment of inventory management as a reinforcement learning problem and developed
methods to determine a near optimal policy under an average cost-based reward criterion."
date: 2018-08-15
venue: "Research Intern, Ericsson Research Bangalore"
classes: wide
---
# Summary 
<!-- <img src="../assets/images/fcmadrl.png" width="50%" height="50%" style="float:right;"> -->

Worked on single-agent reinforcement learning for a simplistic version of autonomous warehouse management; implementing Q-table learning (later DQN algorithms to scale it up) for a single agent to learn to determine an optimal landmark in a self-sustained warehouse based on a cost-based reward function. The use case in mind was that the agent must learn to optimally place inventory in a self-sustained warehouse based on the current demand and available supply. Based on the use case, we designed a reward signal comprising of various costs -

* distance between agent and rack,
* size and dimensions of the product to be picked or dropped, and
* weight of the product to be carried by the robot 

We tested our approach on a test set (of customer orders, assuming infinite supply) created using a Poisson distribution. We saw that it performs better than a simple random placement of products in the warehouse. Apparently, the Amazon warehouses follow a random placement of products in racks.

[However, Amazon achieves cost optimization by maintaining a mapping of
products and the racks where they are stored (both products and racks have
bar-codes) and utilizing a shortest path finding algorithm, lets the agents know
the best route to fetch a particular item. We speculated that this strategy
augmented with our optimal placement would reduce the costs to quite an
extent.]

[ [Report](https://github.com/Nikunj-Gupta/EricssonResearch/blob/master/Document.pdf) ] [ [Code](https://github.com/Nikunj-Gupta/EricssonResearch) ] 