# RL cool envs


## Safety Environments

### Open Safety Gym[^note1]
* [Code](https://github.com/riveSunder/OpenSafety) (MIT License)
* [Example](https://github.com/riveSunder/SafeAgents)
* [More details](pages/open_safety.md)
OpenSafety is a safety-focused suite of RL environments using the [PyBullet](https://pybullet.org/wordpress/) physics simulator. Most of the tasks reward locomotion while carrying some sort of cargo, incurring significant cost if the cargo drops below a threshold. There is also a balancing locomotion task, and a goal-seeking, cargo-carrying task baed on the PyBullet simulation of the [MIT Racecar](https://mit-racecar.github.io/). You can use the provided exapmle of a constrained version of a simple Gaussian evolution strategy from [SafeAgents](https://github.com/riveSunder/SafeAgents).

### OpenAI Safety Gym
* [Code](https://github.com/openai/safety-gym) (MIT License) (MuJoCo dependency)
* [Baselines](https://github.com/openai/safety-starter-agents)
* [Blog](https://openai.com/blog/safety-gym/)
* [Paper (pdf)](https://cdn.openai.com/safexp-short.pdf)


### SafeLife
* [Code](https://github.com/PartnershipOnAI/safelife) (Apache 2.0)
* [Blog](https://www.partnershiponai.org/safelife/)
* [Paper](https://arxiv.org/abs/1912.01217)

## Games

### LRCubeRL
Learning Rubik's Cube with Reinforcement Learning
* [Code](https://github.com/riveSunder/lrcuberl)

### RL Simple Games
Real simple games, like tic-tac-toe and hexapawn.
* [Code](https://github.com/riveSunder/rl-simple-games)

## Human/Machine Collaboration

# Environments from YT

### CARLE
Cellular Automata reinforcement learning environment
* [Code](https://github.com/rivesunder/carle)
* [Blog post: How to break your random network distillation](https://rivesunder.gitlab.io/rl/2019/08/24/breaking_rnd.html)

 
# Cool and Little-Known Environments

### balance-bot by yconst
* [Code](https://github.com/yconst/balance-bot)
* Blog [part I](https://backyardrobotics.eu/2017/11/27/build-a-balancing-bot-with-openai-gym-pt-i-setting-up/), [Part II](https://backyardrobotics.eu/2017/11/29/build-a-balancing-bot-with-openai-gym-pt-ii-the-robot-and-environment/)
* Notes: This environment is part of a tutorial on building an RL environment using the open source [PyBullet](https://pybullet.org) physics engine. The task is a self-balancing robot that must learn to stay upright. I haven't experimented with the environment yet, but the tutorial on building robots with PyBullet is really useful. If that sounds interesting you'll also want to dive into the [PyBullet quickstart guide](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit)

# Safety 

# Multi-agent

### Flatland
[]()

# Generalization

### procgen
* [Code](https://github.com/openai/procgen)
* [Baselines](https://github.com/openai/train-procgen)
* [Blog](https://openai.com/blog/procgen-benchmark/)
* [Paper (pdf)](https://cdn.openai.com/procgen.pdf)

[^note1]: This is my own (RiveSunder's) work.

* Also check out [Awesome Deep RL](https://github.com/kengz/awesome-deep-rl) by kengz
