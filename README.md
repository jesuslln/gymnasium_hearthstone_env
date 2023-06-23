This repository is an implementation of Hearthstone for a gymnasium environment.
The objective of this repo is to create a simple approach for the development 
of AI algorithms in hearthstone.

This repository contains a PIP package which is an OpenAI environment for
simulating an environment in which Hearthstone is played.

## Installation

Follow the Instalation steps:

Create a venv using python 3.9

Install the requirements.txt
[OpenAI gymnasium](https://github.com/Farama-Foundation/Gymnasium).
[Fireplace simulator](https://github.com/jleclanche/fireplace)
[Stable Baselines](https://github.com/DLR-RM/stable-baselines3)

## Usage

Try to run the file run1M.py in the ./runs folder

```
import gymnasium as gym
import gym_hearthstone

env = gym.make('Hearthstone-v0')
actions=env.get_possible_actions()
env.step(actions[0])
```

Check the wiki for more detail.

## With Help From 

https://github.com/SethKitchen/hearthstone-gym

https://github.com/albertwujj/HearthEnv
