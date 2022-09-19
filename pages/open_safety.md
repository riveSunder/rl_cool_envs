o## Open Safety Gym

* [repo](https://github.com/riveSunder/OpenSafety) (MIT License)

This is a safety-focused suite of RL environments using the [PyBullet](https://pybullet.org/wordpress/) physics simulator. Most of the tasks reward locomotion while carrying some sort of cargo, incurring significant cost if the cargo drops below a threshold. There is also a balancing locomotion task, and a goal-seeking, cargo-carrying task based on the PyBullet simulation of the [MIT Racecar](https://mit-racecar.github.io/). Finally, there is a version of the Kuka robotic arm grasping task that includes a block tower that incurs a cost when knocked over.

You can use the provided example of a constrained version of a simple Gaussian evolution strategy from [SafeAgents](https://github.com/riveSunder/SafeAgents). An earlier version of OpenSafety was used to run a simple ad-hoc experiment testing the reward hypothesis (also known as the reinforcement learning hypothesis. The result of this experiment showed that in a task rewarding locomotion with a cost incurred for losing balance, an agent could learn to stay upright while moving forward whether the cost was incurred explicitly or combined with the reward signal. 


![Balancing under the reward hypothesis](https://github.com/riveSunder/OpenSafety/raw/master/assets/reward_hypothesis_2.gif)
<div align="center">
Left to right. An agent evolved with only a locomotion reward (without a balance cost) falls over while moving forward. Agents evolved while constrained by an explicit cost signal learned to balance while moving, and agents evolved with a combined balance cost and locomotion reward were also able to learn balance and locomotion together. 
</div>
<br><br>

OpenSafety was developed as an open source alternative to [Safety Gym](https://web.archive.org/web/20220717150118/https://openai.com/blog/safety-gym/). Safety Gym was devloped by Alex Ray, Joshua Achiam, and Dario Amodei while at OpenAI, and it depends on the MuJoCo physics simulator, which required a prohibitive license fee but has since been acquired by DeepMind for the [express purpose](https://www.deepmind.com/blog/open-sourcing-mujoco) of making it freely available. However, Safety Gym and OpenSafety are different enough to be considered on their own.  
