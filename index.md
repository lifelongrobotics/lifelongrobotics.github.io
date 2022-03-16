# Life-long Learning of High-level Cognitive and Reasoning Skills

There has been a tremendous advancement in machine learning methods over the past ten years. These advancements are reflected in robotics research primarily as ad-hoc solutions to different problems, such as learning to grasp simple objects [1, 2], learning movement primitives from demonstrations [3, 4] and so on. Although such solutions push the frontiers of robotics research, there is still a large gap between current methods and generally capable agents that learn skills and representations of progressive complexity to solve increasingly complex problems in an environment without forgetting previously learned skills, which is the ultimate aim of artificial intelligence research. Several studies [5, 6, 7, 8] focus on learning representations in an open-ended, continual manner in order to develop general skills without manually designing reward functions or curricula. The main advantage of open-ended (or life-long, or continual) learning is that the learning loop never stops by design; the agent autonomously generates new challenges, tasks, environments, and goals to explore and learn new skills. This opens new possibilities for learning emergent skills not foreseen in hindsight. However, these methods do not precisely fit robot learning as we cannot arbitrarily evolve the embodiment of the agent and the real world.

This workshop will focus on how to create open-ended or life-long learning systems [9, 10] that will allow for a robot to autonomously explore its environment and learn ever-growing representations for perception and actuation. This is an underexplored area in robotics and artificial intelligence research that can contribute to the development of generally capable agents. We will discuss the necessary elements (e.g., methods, environments, datasets, embodiments) for a life-long learning setting. We will encourage participants to take part in discussions with the following points:

- How to adopt the current open-ended methods for life-long robot learning
- Are the current machine learning methods sufficient for life-long learning?
- How to combine the current toolset of ML for life-long learning
- How to design end-to-end systems for life-long learning
- What are the necessary components for a life-long learning system? Which parts should we take for granted?
- How to design appropriate environments both in simulation and real-world that support life-long learning

We believe that approaching robot learning from a life-long learning perspective might be a feasible approach for truly intelligent robots. Stimulating discussions with the robotics community will be very valuable to understand if such an approach is indeed worth exploring or not.

[1] Pinto, Lerrel, and Abhinav Gupta. "Supersizing self-supervision: Learning to grasp from 50k tries and 700 robot hours." 2016 IEEE international conference on robotics and automation (ICRA). IEEE, 2016.
[2] Murali, Adithyavairavan, et al. "Learning to grasp without seeing." International Symposium on Experimental Robotics. Springer, Cham, 2018.
[3] Paraschos, Alexandros, et al. "Probabilistic movement primitives." Advances in neural information processing systems 26 (2013).
[4] Seker, Muhammet Yunus, et al. "Conditional Neural Movement Primitives." Robotics: Science and Systems. Vol. 10. 2019.
[5] Wang, Rui, et al. "Paired open-ended trailblazer (poet): Endlessly generating increasingly complex and diverse learning environments and their solutions." arXiv preprint arXiv:1901.01753 (2019).
[6] Wang, Rui, et al. "Enhanced poet: Open-ended reinforcement learning through unbounded invention of learning challenges and their solutions." International Conference on Machine Learning. PMLR, 2020.
[7] Team, Open Ended Learning, et al. "Open-ended learning leads to generally capable agents." arXiv preprint arXiv:2107.12808 (2021).
[8] Parker-Holder, Jack, et al. "Evolving Curricula with Regret-Based Environment Design." arXiv preprint arXiv:2203.01302(2022).
[9] Thrun, Sebastian, and Tom M. Mitchell. "Lifelong robot learning." Robotics and autonomous systems 15.1-2 (1995): 25-46.
[10] Oztop, Erhan, and Emre Ugur. (2021) Lifelong Robot Learning. In: Ang M.H., Khatib O., Siciliano B. (eds) Encyclopedia of Robotics. Springer, Berlin, Heidelberg, 2021.
