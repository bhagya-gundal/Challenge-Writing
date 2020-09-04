
<img src="kin.png" width="300"/> 

Kinesso, the Marketing Engine of IPG, is focused on creating data-driven solutions through enhanced or newly-created products and services, maximizing the impact of traditional and addressable media. Kinesso’s core principle is to drive smarter business decisions and better outcomes for clients using our suite of data and technology services.

# Reinforcement Learning Challenge 2020

## Introduction:

Learning to act optimally on time series data is of practical uses in various industries. The value of taking an action depends on future actions and states, which makes it difficult to be modeled using a conventional machine leanrning techniques. This is where reinforcement learning comes in picture. In this challenge you will be working on multivariate time series data. To get started on the challenge, begin by finding a multivariate time series dataset whose dependent/target variable is a real number and has finite action choices/actions. In this challenge, you will build a open-gym ai (openAI gym) environment for that dataset to be able to run for an RL algorithm. You are encouraged to run any of the following TF-agent algorithms - DQN, REINFORCE, DDPG, TD3, PPO or SAC on it. Please go through step by step implementation guide to meet the requirements of challenge.


Currently the following algorithms are available under TF-Agents:

*   [DQN: __Human level control through deep reinforcement learning__ Mnih et
    al., 2015](https://deepmind.com/research/dqn/)
*   [DDPG: __Continuous control with deep reinforcement learning__ Lillicrap et
    al., 2015](https://arxiv.org/abs/1509.02971)
*   [TD3: __Addressing Function Approximation Error in Actor-Critic Methods__
    Fujimoto et al., 2018](https://arxiv.org/abs/1802.09477)
*   [REINFORCE: __Simple Statistical Gradient-Following Algorithms for
    Connectionist Reinforcement Learning__ Williams,
    1992](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf)
*   [PPO: __Proximal Policy Optimization Algorithms__ Schulman et al., 2017](https://arxiv.org/abs/1707.06347)
*   [SAC: __Soft Actor Critic__ Haarnoja et al., 2018](https://arxiv.org/abs/1812.05905)

## Eligibility: 
The challenge is open to the current Northeastern University students.
The purpose of this challenge is to pre-screen candidates for a Programmer Analyst position during the Fall 2020. The position involves working closely with Kinesso. We sincerely appreciate your interest and hope to see you participate in this challenge!

## Resources:
To get started, we recommend checking out one of the Colab tutorials:

* Reinforcement Learning - Thompson Sampling & the Multi-Armed Bandit Problem
    https://colab.research.google.com/drive/1gdR7k7jtSRqYnPNHcbAKdIjGRjQXpfnA

    https://github.com/nikbearbrown/Google_Colab/blob/master/Thompson_Sampling_%26_The_Multi_Armed_Bandit_Problem.ipynb

* Andre Cianflone - Thompson sampling

  https://colab.research.google.com/drive/1BHVH712x2Q2As9E5nN5Y8UR74T8w6AMO



## Implementation Guide
Please incorporate below guidelines in your solution: 

- Load the data 
    - Please find a muti-variate time series data. 
    - The depenent variable must be a real number with defined action choices.
- Data Pre-processing
    - Perform necessary pre-processing steps for time series data.
    - Example - Check if data is stationery or not? Cast your Date column in date datatype and set it as your index.
    - Perform E-D-A on the data and visulize features like patterns, unusual observations, changes over time, and relationships between variables.
              
- Create a open-gym ai environment 

- Run one of the TF-Agents algorithms 

- Compare the RL learner 

- Describe signals and action space for the five TF-Agents algorithms 
    - (DQN, REINFORCE, DDPG, TD3, PPO or SAC). 
    - Can they take continuous or only discrete signals? 
    - Can the agent only be used in any environment which has a discrete action space?
- What are the pros and cons of the five TF-Agents algorithms?
    - Please describe various pros and cons of each of the TF-Agent algorithms briefly.


## Your submission:

Deadline for the project is " ". The notebook should include a detailed analysis of our data, the models used and your scientific conclusions

When you're finished, please place the notebook and any other code you wrote into a zipped folder and e-mail to "ni.bear@northeastern.edu".



