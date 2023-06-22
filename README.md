This repository contains a PIP package which is an OpenAI environment for
simulating an environment in which Hearthstone is played.

## Installation

Install the [OpenAI gym](https://gym.openai.com/docs/).

Install Fireplace Hearthstone Simulator

```
git clone https://github.com/jleclanche/fireplace
cd fireplace
pip install .
```

To install stable baselines check the wiki.

## Usage

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
