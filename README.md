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
* [Blog (Partnership on AI)](https://www.partnershiponai.org/safelife/)
* [Blog (Weights and Biases)](https://wandb.ai/stacey/saferlife/reports/Measuring-Safety-in-Reinforcement-Learning--VmlldzoyNjk3MTM)
* [Benchmarks](https://wandb.ai/safelife/v1dot2/benchmark)
* [Paper](https://arxiv.org/abs/1912.01217)


### AI safety gridworlds
* [Code](https://github.com/deepmind/ai-safety-gridworlds) (Apache 2.0)
* [Paper](https://arxiv.org/abs/1711.09883)
* 

<!-- ### Safer RL
* [Code](https://github.com/RongRG/saferRL) (MIT License)
* [Docs]() 
This project is not yet ready to explore.
-->

## Games


### LRCubeRL
Learning Rubik's Cube with Reinforcement Learning
* [Code](https://github.com/riveSunder/lrcuberl)

### RL Simple Games
Real simple games, like tic-tac-toe and hexapawn.
* [Code](https://github.com/riveSunder/rl-simple-games)

## Open-ended

### CARLE [^note1]
Cellular Automata reinforcement learning environment
* [Code](https://github.com/rivesunder/carle)
* [Blog post: How to break your random network distillation](https://rivesunder.gitlab.io/rl/2019/08/24/breaking_rnd.html)

# Generalization

### procgen
* [Code](https://github.com/openai/procgen)
* [Baselines](https://github.com/openai/train-procgen)
* [Blog](https://openai.com/blog/procgen-benchmark/)
* [Paper (pdf)](https://cdn.openai.com/procgen.pdf)

[^note1]: These envs are my own (RiveSunder's) work.

* Also check out [Awesome Deep RL](https://github.com/kengz/awesome-deep-rl) by kengz
