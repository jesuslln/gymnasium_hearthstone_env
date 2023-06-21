This repository contains a PIP package which is an OpenAI environment for
simulating an environment in which Hearthstone is played.

## Working on Documentation

## Installation

Install the [OpenAI gym](https://gym.openai.com/docs/).

Install Fireplace Hearthstone Simulator

```
git clone https://github.com/jleclanche/fireplace
cd fireplace
pip install .
```

Then install this package via

```
git clone https://github.com/SethKitchen/hearthstone-gym
cd hearthstone-gym
python -m pip install -e .
```

## Usage

```
import gym
import gym_hearthstone

env = gym.make('Hearthstone-v0')
actions=env.get_possible_actions()
env.step(actions[0])
```


## The Environment

Uses Fireplace and random MAGE/WARRIOR decks -- updates to expand

## With Help From 

https://github.com/SethKitchen/hearthstone-gym

https://github.com/albertwujj/HearthEnv
