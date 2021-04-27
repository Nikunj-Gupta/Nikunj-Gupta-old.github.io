---
layout: page 
title: Efficient RL Using Better Feedback 
description: Designing Rewards for Stage-wise Learning of Complex Goals using Reinforcement Learning
img: /assets/img/rl-diagram.png 
importance: 1
category: abb
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <b>Test Bed: CartPole (Inverted Pendulum) Environment</b> <br>
        <cite> ”A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying an action of +1 or -1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over. A reward of +1 is provided for every timestep that the pole remains upright. The episode ends when the pole is more than 15 degrees from vertical, or the cart moves more than 2.4 units from the center." </cite> <br><br>
        <p>CartPole-v0 defines "solving" as getting average reward of 195.0 over 100 consecutive trials. This environment corresponds to the version of the cart-pole problem described by Barto, Sutton, and Anderson [Barto83].</p> 
    </div>
    <div style="height:32%;width:32%;">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/cartpole.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<br><br>
We explored and designed various different types of reward signals for this problem and compared the agent's cumulative rewards accumulated over episodes. The types of reward signals can be abstractly described in the following categories: 
* Positive rewards 
* Negative rewards 
* Reward gradient 
* Variable Force 
* Force Gradient 


<a href="https://drive.google.com/file/d/0Bz-47WwEsrqLbkJJa1pmZmgxOVk/view">Report</a> 

