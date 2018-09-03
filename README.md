
![](images/logo5.png)

![](https://img.shields.io/badge/Uploading-12%25-blue.svg)  [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/andri27_it)

<br>

### I designed this Challenge for you and me: Learn Deep Reinforcement Learning in depth in 60 days!!

You heard about the amazing results achieved by [Deepmind with AlphaGo Zero](https://www.youtube.com/watch?time_continue=24&v=tXlM99xPQC8) and by [OpenAI in Dota 2](https://www.youtube.com/watch?v=l92J1UvHf6M)! Don't you want to know how they work?
This is the right opportunity for you and me to finally learn Deep RL and use it on new exciting projects.

> The ultimate aim is to use these general-purpose technologies and apply them to all sorts of important real world problems. 
> **Demis Hassabis**
<br>

This repository wants to guide you through the Deep Reinforcement Learning algorithms, from the most basic ones to the highly advanced AlphaGo Zero. You will find the **main topics organized by week** and the **resources suggested to learn them**. Also, every week I will provide **practical examples** implemented in python to help you better digest the theory. You are highly encouraged to modify and play with them!

<br>

This is my first project of this kind, so please, if you have any idea, suggestion or improvement contact me at andrea.lonza@gmail.com.


#### During the whole challenge, I will update continuously this repository.. **so stay tuned**! #60DaysRLChallenge


## Projects (Yet to decide)
 - **Q-learning**
 - **DQN**
 - **AC2**
 - **ES**
 - **AlphaGo Zero**

## Week 1 - Introduction

 - #### [An introduction to Reinforcement Learning](https://www.youtube.com/watch?v=JgvyzIkgxF0) by Arxiv Insights
 - #### [Introduction and course overview](https://www.youtube.com/watch?v=Q4kF8sfggoI&index=1&list=PLkFD6_40KJIznC9CDbVTjAF2oyt8_VAe3) - CS294 by Levine
 - #### [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/) by Karpathy

## Week 2 - RL Basics: *MDP, Dynamic Programming and Model-Free Control*

> Those who cannot rember the part are condomned to repeat it - George Santayana 


This week, we will learn about the basic blocks of reinforcement learning, starting from the definition of the problem all the way through the estimation and optimization of the functions that are used to express the quality of a policy or state.

----

### Theoretical material

 - #### [Markov Decision Process](https://www.youtube.com/watch?v=lfHX2hHRMVQ&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=2) - RL by David Silver
 Formalizing RL problem using MDP
  - Markov Processes
  - Markov Decision Processes

 - #### [Planning by Dynamic Programming](https://www.youtube.com/watch?v=Nd1-UUMVfz4&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=3) - RL by David Silver
 How to solve *known* MDP 
  - Policy iteration
  - Value iteration

 - #### [Model-Free Prediction](https://www.youtube.com/watch?v=PnHCvfgC_ZA&index=4&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-) - RL by David Silver
 *Estimate* the value function of *unknown* MDP
  - Monte Carlo Learning
  - Temporal Difference Learning
  - TD($$\lambda$$)

 - #### [Model-Free Control](https://www.youtube.com/watch?v=0g4j2k_Ggc4&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=5) - RL by David Silver
 *Optimise* the value function of an *unknown* MDP
  - $$\epsilon$$-greedy policy iteration
  - GLIE Monte Carlo Search
  - SARSA
  - Importance Sampling

----

### Project of the Week

[Q-learning applied to FrozenLake](Week2/frozenlake_Qlearning.ipynb). For exercise, you can solve the game using SARSA or implement Q-learning by yourself. In the former case, only few changes are needed. 

----

#### To know more
- Read chapters 3,4,5,6,7 of [Reinforcement Learning An Introduction - Sutton, Barto](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)


## Week 3 - Value Function Approximation and DQN

## Week 4 - A2C and A3C

## Week 5 - RL in continous space - TRPO/PPO

## Week 6 - Evolution Strategies and Genetic Algorithms

## Week 7 - I2A

## Week 8 - AlphaGoZero + Bonus

## Last 4 days - Review + sharing


## Best RL papers

## Best resources

:tv: [Deep Reinforcement Learning](https://www.youtube.com/playlist?list=PLkFD6_40KJIznC9CDbVTjAF2oyt8_VAe3) - UC Berkeley class by Levine, check [here](http://rail.eecs.berkeley.edu/deeprlcourse/) their site.

:tv: [Reinforcement Learning course](https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ) - by David Silver, DeepMind. Great introductory lectures by Silver, a lead researcher on AlphaGo. They follow the book Reinforcement Learning by Sutton & Barto.

:notebook: [Reinforcement Learning: An Introduction](https://www.amazon.com/Reinforcement-Learning-Introduction-Adaptive-Computation/dp/0262193981/ref=sr_1_2?s=books&ie=UTF8&qid=1535898372&sr=1-2&keywords=reinforcement+learning+sutton) - by Sutton & Barto. The "Bible" of reinforcement learning. [Here](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf) you can find the PDF draft of the second version.


## Additional resources 

:books: [Awesome Reinforcement Learning](https://github.com/aikorea/awesome-rl). A curated list of resources dedicated to reinforcement learning