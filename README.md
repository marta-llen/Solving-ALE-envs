# Solving-ALE-envs

This repository contains code for solving Atari Learning Environment (ALE) environments using reinforcement learning.

## Part 1: Bowling 

In this part, we aim to solve the Bowling environment using a DQN and a REINFORCE algorithms. 

To run the code you should use the requirements.txt file to install the necessary packages. Aditionally, in the case of wanting to track the results with `wandb`, you should change the KEY to login to your account in the line: 

```
wandb.login(key="KEY")
```
Moreover, you should check the paths of the directories when trying the models saved. 

#### DQN 
This directory contains the code for the DQN algorithm (`qlearning_bowling.py`) and the evaluation code (`eval_bowling_dqn.ipnyb`). Also, there can be found the plots for the results. 

There are three directories:
- `evaluation_results`: video of performance of the agent using the best model saved
- `models_dqn`: best_model_dqn.pth and latest_model_dqn.pth
- `videos_dqn`: videos of training. 

#### REINFORCE 
This directory contains the code for the REINFORCE algorithm (`bowling_reinforce.py` and `bowling_finetune.py`) and the evaluation code (`bowling_reinforce_eval.ipnyb`).

There are four directories:
- `finetuned_bowling_models`: models saved during finetuning
- `finetuned_bowling_videos`: videos of the agent playing the game during finetuning
- `models_reinforce`: models saved during training
- `videos_reinforce`: videos of training

### Part 2 - Boxing 

In this part, we aim to solve the Boxing environment using a PPO and a REINFORCE with policy gradients algorithms. 

As in the previous part, to run the code you should use the requirements.txt file to install the necessary packages. Aditionally, in the case of wanting to track the results with `wandb`, you should change the KEY to login to your account in the line: 

```
wandb.login(key="KEY")
```
Moreover, you should check the paths of the directories when trying the models saved. 

#### PPO

This directory contains the code for the PPO algorithm (`ppo_boxing.py`) and the evaluation code (`eval_boxing_ppo.ipnyb`). Also, there can be found the plots for the results. 

There are two directories:
- `models_boxing_ppo`: it contains the best model saved during training
- `videos_Boxing_evaluation`: videos of the agent during evaluation

#### REINFORCE with policy gradients

This directory contains the code for the REINFORCE with policy gradients algorithm (`boxing_agent.py`) and the evaluation code (`boxing_reinforce_evaluation.py`). 

There are two directories:
- `boxing_models_reinforce`: it contains the best model saved during training
- `boxing_video_reinforce`: videos of the agent during evaluation


### Part 3 - Pong

In this part, we aim to solve the Boxing environment using a DQN algorithm. 

To run the code you should use the requirements3.txt file to install the necessary packages. Aditionally, in the case of wanting to track the results with `wandb`, you should change the KEY to login to your account in the line: 

```
wandb.login(key="KEY")
```
Moreover, as previously, you should check the paths of the directories when trying the models saved. 

There is the code for the training part (`part3_train.py`) and the evaluation part (`eval_part3.ipnyb`). 

There are two directories:
- `models`: it contains the best model saved during training. Inside the best model saved, there is the video of the best performance, a plot and the metrics. 
- `wrong approaches`: it contains two wrong approaches of the exercises due to the misunderstanding of the instructions. Also it has its models saved.



